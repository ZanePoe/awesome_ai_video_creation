# Guide de contribution

Les ajouts de projets et les corrections de catégorie, de frontière fonctionnelle ou de licence sont bienvenus.

1. Modifiez `data/projects.json`, n'éditez jamais directement les tableaux générés.
2. Fournissez le dépôt GitHub canonique, une catégorie principale, l'usage, les limites et des preuves README lues à un commit figé.
3. Précisez s'il s'agit d'un atelier, d'un système agent, d'un Skill/MCP, d'animation par code, d'un modèle génératif, d'un avatar numérique, d'un CLI ou d'un benchmark.
4. Ne présentez pas une roadmap, un échantillon ou le benchmark de l'auteur comme une conclusion de test indépendante.
5. Vérifiez séparément les licences du code, des poids de modèles, des médias, des polices, des API tierces et du contenu de sortie.
6. Les projets de téléchargement/capture doivent conserver les conditions des plateformes et les frontières d'autorisation des contenus.
7. Après un ajout, exécutez :

```sh
python scripts/refresh_metrics.py
python scripts/build.py
python -m unittest discover -s tests -v
python scripts/build.py --check
```

Ne commitez aucune clé API, vidéo privée, média non autorisé, adresse interne de content factory ni donnée personnelle. Les journaux de modification se placent dans le dossier `record/`, nommés `YYYY-MM-DD-<sujet>.md` avec un sujet en chinois, et gardent le texte d'origine (en chinois) tel qu'il était au moment de la vérification.

## Fichiers multilingues

- `data/projects.json` porte le texte validé canonique, en chinois ; un fait ne se corrige qu'à cet endroit.
- Les autres langues lisent `locales/<lang>/entries.json` (`description`, `boundary`, `license_label`, `license_note`, plus `name` lorsque le nom canonique contient des caractères chinois) et `locales/<lang>/ui.json`. `zh` retombe sur `data/projects.json`, il n'existe donc pas de `locales/zh/entries.json`.
- Lors d'un ajout ou d'une reformulation d'un usage, d'une limite ou d'une conclusion de licence, mets à jour les quatre langues dans la même pull request ; sinon `python scripts/build.py --check` et `python -m unittest discover -s tests -v` échouent.
- Prose statique : l'anglais vit dans `docs/` et `CONTRIBUTING.md` à la racine, les autres langues dans les mêmes chemins relatifs sous `locales/<lang>/`. Dans une copie, les liens se résolvent depuis le dossier du fichier lui-même : `locales/<lang>/docs/research.md` écrit `../../../research/…`, `locales/<lang>/CONTRIBUTING.md` écrit `../../…` ; `docs/readme-intro.md` fait exception car il est inséré dans le README et se résout depuis la racine de la langue.
- Les fichiers générés (`README.md`, `docs/projects.md`, `docs/rankings.md`, `data/rankings.csv` et leurs copies locales) ne sont jamais modifiés à la main ; lance `python scripts/build.py`.
