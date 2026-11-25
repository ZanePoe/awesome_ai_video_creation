# योगदान मार्गदर्िका

नए प्रोजेक्ट जोड़ने, श्रेणी, फ़ंक्शन-सीमा या लाइसेंस सुधारने के लिए आपका स्वागत है।

1. `data/projects.json` बदलें, जनरेट की गई तालिकाओं को सीधे एडिट न करें।
2. canonical GitHub रिपॉज़िटरी, एक मुख्य श्रेणी, उपयोग, सीमाओं का विवरण और फ़िक्स किए गए commit के README प्रमाण दें।
3. स्पष्ट करें कि वह वर्कबेंच है, Agent सिस्टम, Skill/MCP, कोड मोशन, जनरेटिव मॉडल, डिजिटल प्रस्तोता, CLI या benchmark।
4. roadmap, सैंपल क्लिप या लेखक के benchmark को स्वतंत्र परीक्षण-निष्कर्ष की तरह न लिखें।
5. कोड, मॉडल वेट, सामग्री, फ़ॉन्ट, थर्ड-पार्टी API और आउटपुट कंटेंट के लाइसेंस अलग-अलग जाँचें।
6. डाउनलोड/संग्रह प्रोजेक्ट में प्लेटफ़ॉर्म के नियम और सामग्री अधिकार की सीमा अनिवार्य रूप से रखें।
7. नया प्रोजेक्ट जोड़ने के बाद चलाएँ:

```sh
python scripts/refresh_metrics.py
python scripts/build.py
python -m unittest discover -s tests -v
python scripts/build.py --check
```

API key, निजी वीडियो, बिना अधिकार की सामग्री, आंतरिक content-factory पते या व्यक्तिगत डेटा कमिट न करें। परिवर्तन रिकॉर्ड `record/YYYY-MM-DD-<चीनी-विषय>.md` नाम से रखा जाता है।

## बहुभाषी फ़ाइलें

- `data/projects.json` चीनी में canonical समीक्षा डेटा है: तथ्य यहीं एक बार बदले जाते हैं।
- अन्य भाषाओं का पाठ `locales/<lang>/entries.json` (`description`, `boundary`, `license_label`, `license_note`; जिन प्रोजेक्ट का canonical नाम चीनी अक्षरों में है उनके लिए बिना-चीनी `name`) और `locales/<lang>/ui.json` से आता है; `zh` सीधे `data/projects.json` पर गिरता है, इसलिए `locales/zh/entries.json` नहीं है।
- नया प्रोजेक्ट जोड़ते समय या भूमिका, सीमा और लाइसेंस-निष्कर्ष बदलते समय उसी PR में en/es/hi/fr चारों locale पूरे करें, वरना `python scripts/build.py --check` और `python -m unittest discover -s tests -v` फेल होंगे।
- स्थैतिक दस्तावेज़: अंग्रेज़ी रूट की `docs/` और `CONTRIBUTING.md` में, अन्य भाषाएँ `locales/<lang>/` में उसी सापेक्ष पाथ पर। मिरर में सापेक्ष लिंक उस फ़ाइल की अपनी डायरेक्टरी से resolves होते हैं: `locales/<lang>/docs/research.md` में रिपॉज़िटरी रूट की ओर `../../../research/…` लिखें, `locales/<lang>/CONTRIBUTING.md` में `../../…` लिखें; `docs/readme-intro.md` अपवाद है, क्योंकि वह README में जोड़ा जाता है और भाषा-रूट से resolves होता है।
- जनरेटेड फ़ाइलें (`README.md`, `docs/projects.md`, `docs/rankings.md`, `data/rankings.csv` और हर भाषा-मिरर की उसी नाम की फ़ाइलें) हाथ से न बदलें, वे `python scripts/build.py` बनाता है।
