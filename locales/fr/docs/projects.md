# Fiches projets et preuves

Chaque positionnement provient du README officiel lu à un commit figé ; tous les projets n'ont pas été installés ni exécutés. Un rafraîchissement des métriques ne relance pas automatiquement la revue des fonctionnalités ni des licences.


## [Concat](https://github.com/jub0t/Concat)

Éditeur multi-piste local multiplateforme avec sous-titres, TTS, détourage, images clés, effets et export 4K.

- Catégorie : Éditeurs vidéo et ateliers de production ; Candidat principal.
- Périmètre d'application : Les modèles locaux doivent être téléchargés au premier usage ; l'IA intégrée et un workflow génératif complet ne relèvent pas du même périmètre.
- État de maintenance : Commits sur les 90 derniers jours ; 443 commits sur 30 jours, 1608 commits sur 90 jours.
- Licence : [AGPL-3.0](https://api.github.com/repos/jub0t/Concat/license) ; Licence ouverte vérifiée. Identifiée via GitHub licenseInfo ; les poids de modèles, médias, polices, dépendances tierces et services managés relèvent de leurs propres licences
- Vérification fonctionnelle : 2026-11-12 ; [Source1](https://github.com/jub0t/Concat/blob/504a814ebe61d4f47bba4cd7949dc2580ecc405c/README.md#L6).

## [Jellyfish](https://github.com/Forget-C/Jellyfish)

Atelier de production de dramas courts IA couvrant découpage du script, plans, gestion des assets personnages et décors, génération de shots et export.

- Catégorie : Éditeurs vidéo et ateliers de production ; Candidat principal.
- Périmètre d'application : La réutilisation des assets aide à la cohérence sans garantir la qualité de génération ; les services de modèles, les coûts et les contraintes de déploiement restent à valider selon la configuration.
- État de maintenance : Commits sur les 90 derniers jours ; 1289 commits sur 30 jours, 1666 commits sur 90 jours.
- Licence : [Apache-2.0](https://github.com/Forget-C/Jellyfish/blob/a9678194ddf2d9be3ccbe78d4287d87d5089e123/LICENSE) ; Licence ouverte vérifiée. LICENSE racine sous Apache-2.0 ; les modèles, les médias et les conditions des services tiers sont à part.
- Vérification fonctionnelle : 2026-11-20 ; [Source1](https://github.com/Forget-C/Jellyfish/blob/a9678194ddf2d9be3ccbe78d4287d87d5089e123/README.md#L30).

## [Clypra](https://github.com/AIEraDev/Clypra)

Éditeur vidéo multiplateforme accéléré par le matériel, construit en Rust/Tauri/React.

- Catégorie : Éditeurs vidéo et ateliers de production ; Candidat principal.
- Périmètre d'application : Éditeur généraliste avant tout ; l'étendue des fonctions IA et la maturité mobile sont à vérifier version par version.
- État de maintenance : Commits sur les 90 derniers jours ; 282 commits sur 30 jours, 1682 commits sur 90 jours.
- Licence : [MIT](https://api.github.com/repos/AIEraDev/Clypra/license) ; Licence ouverte vérifiée. Identifiée via GitHub licenseInfo ; les poids de modèles, médias, polices, dépendances tierces et services managés relèvent de leurs propres licences
- Vérification fonctionnelle : 2026-11-12 ; [Source1](https://github.com/AIEraDev/Clypra/blob/aa6b9c619cf98f7a1dfab6446345ec5f5660b93c/README.md#L9).

## [CozyClay](https://github.com/HaD0Yun/CozyClay)

Outil navigateur de construction de décors, placement des personnages, découpage de plans et prévisualisation vidéo par IA.

- Catégorie : Éditeurs vidéo et ateliers de production ; Candidat principal.
- Périmètre d'application : La sortie est surtout de la prévisualisation et des références de plans ; la qualité de la génération finale dépend du modèle vidéo externe.
- État de maintenance : Commits sur les 90 derniers jours ; 180 commits sur 30 jours, 2127 commits sur 90 jours.
- Licence : [AGPL-3.0](https://api.github.com/repos/HaD0Yun/CozyClay/license) ; Licence ouverte vérifiée. Identifiée via GitHub licenseInfo ; les poids de modèles, médias, polices, dépendances tierces et services managés relèvent de leurs propres licences
- Vérification fonctionnelle : 2026-11-12 ; [Source1](https://github.com/HaD0Yun/CozyClay/blob/297dd2a8a077613b329962d68e2a9bb4355be091/README.md#L6).

## [Huobao Drama](https://github.com/chatfire-AI/huobao-drama)

Plateforme web/desktop qui, d'une phrase ou d'un roman collé, réécrit le script, génère images, vidéos de plans, doublage et sous-titres, puis assemble un drame court complet ; l'arrière-plan est orchestré par des agents Mastra et les skills sont éditables dans l'interface.

- Catégorie : Éditeurs vidéo et ateliers de production ; Candidat principal.
- Périmètre d'application : Licence CC BY-NC-SA-4.0 interdisant explicitement l'usage commercial (services payants, déploiements commerciaux et revente inclus) ; les capacités de texte, d'image et de vidéo exigent chacune de configurer ses propres clés API de services de modèles, le README orientant vers les clés FireMux de l'auteur ; la référence à des ressources locales pour Seedance suppose une adresse publique accessible PUBLIC_BASE_URL, la version desktop sans entrée publique échoue directement ; stockage via SQLite et le répertoire data — la migration exige la copie manuelle des fichiers médias.
- État de maintenance : Commits sur les 90 derniers jours ; 18 commits sur 30 jours, 108 commits sur 90 jours.
- Licence : [CC BY-NC-SA-4.0 (usage commercial interdit)](https://github.com/chatfire-AI/huobao-drama/blob/24d4c17612e71cf10c8eeb1a8b6439afa73e2c07/LICENSE) ; Code source visible mais non open source OSI. LICENSE contient le texte intégral CC BY-NC-SA 4.0 ; la section licence du README interdit explicitement l'usage commercial, qui suppose une autorisation écrite de l'auteur ; GitHub licenseInfo l'identifie donc comme NOASSERTION ; les services de modèles appelés, les médias et les droits des doublages sont à part
- Vérification fonctionnelle : 2026-11-25 ; [Source1](https://github.com/chatfire-AI/huobao-drama/blob/24d4c17612e71cf10c8eeb1a8b6439afa73e2c07/README.md#L33) · [Source2](https://github.com/chatfire-AI/huobao-drama/blob/24d4c17612e71cf10c8eeb1a8b6439afa73e2c07/README.md#L55) · [Source3](https://github.com/chatfire-AI/huobao-drama/blob/24d4c17612e71cf10c8eeb1a8b6439afa73e2c07/README.md#L131).

## [OpenChatCut](https://github.com/0xsline/OpenChatCut)

Éditeur vidéo conversationnel IA local-first avec timeline multi-piste, Agent Skills, MCP et rendu Remotion.

- Catégorie : Éditeurs vidéo et ateliers de production ; Candidat principal.
- Périmètre d'application : Les capacités respectives de l'agent intégré, de la version desktop et des coding agents externes doivent être vérifiées séparément.
- État de maintenance : Commits sur les 90 derniers jours ; 22 commits sur 30 jours, 396 commits sur 90 jours.
- Licence : [AGPL-3.0](https://api.github.com/repos/0xsline/OpenChatCut/license) ; Licence ouverte vérifiée. Identifiée via GitHub licenseInfo ; les poids de modèles, médias, polices, dépendances tierces et services managés relèvent de leurs propres licences
- Vérification fonctionnelle : 2026-11-12 ; [Source1](https://github.com/0xsline/OpenChatCut/blob/9242a95aea248ff3a8dab495514384e858320d47/README.md#L12).

## [Editroom](https://github.com/robbietilton/Editroom)

Monteur vidéo natif en Swift pour macOS : 4K temps réel sans proxy, étalonnage, rampes de vitesse, transitions, mixage audio et exports avec cible de loudness intégrés, plus des coupes en langage naturel via Claude, ChatGPT ou un modèle local.

- Catégorie : Éditeurs vidéo et ateliers de production ; Candidat principal.
- Périmètre d'application : Exige macOS 14 ou plus sur Apple silicon ; l'option Local de Magic demande en plus Apple Intelligence sous macOS 26, et les options Claude et ChatGPT supposent ces applications connectées à votre forfait. Les 7,5 Mo et le 4K « sans proxy ni buffer » sont les affirmations du README, sans installation ni mesure ici ; le chiffre de 23 Mo du post ne correspond ni au README ni au DMG de v1.0.11, qui pèse 12 238 527 octets. Claude et ChatGPT modifient le projet ouvert via MCP et les montages Magic sont annulables, mais le périmètre d'envoi de chaque mode reste à vérifier selon vos médias et vos exigences de confidentialité.
- État de maintenance : Commits sur les 90 derniers jours ; 428 commits sur 30 jours, 428 commits sur 90 jours.
- Licence : [MIT (application) + FFmpeg inclus LGPL-2.1+, Sparkle MIT](https://github.com/robbietilton/Editroom/blob/6390ae7f3847d924126b2d4f7a964b9fee4e71a2/LICENSE) ; Licence composite/conditionnelle. La LICENSE racine est MIT ; l'application embarque FFmpeg 9.1 sous LGPL-2.1+ (aucune partie GPL ou non libre, construit depuis les sources de ffmpeg.org par scripts/build-ffmpeg.sh et exécuté comme programme séparé uniquement pour re-empaqueter les formats que macOS ne lit pas), et Sparkle est MIT ; redistribuer oblige à fournir les sources de FFmpeg et ses options de configure, documentées dans Vendor/ffmpeg/README.md.
- Vérification fonctionnelle : 2026-11-27 ; [Source1](https://github.com/robbietilton/Editroom/blob/6390ae7f3847d924126b2d4f7a964b9fee4e71a2/README.md#L5) · [Source2](https://github.com/robbietilton/Editroom/blob/6390ae7f3847d924126b2d4f7a964b9fee4e71a2/README.md#L7) · [Source3](https://github.com/robbietilton/Editroom/blob/6390ae7f3847d924126b2d4f7a964b9fee4e71a2/README.md#L50) · [Source4](https://github.com/robbietilton/Editroom/blob/6390ae7f3847d924126b2d4f7a964b9fee4e71a2/README.md#L59) · [Source5](https://github.com/robbietilton/Editroom/blob/6390ae7f3847d924126b2d4f7a964b9fee4e71a2/README.md#L87).

## [OpenDirector](https://github.com/ThinkFlowLab/OpenDirector)

Workflow de création vidéo agentique, de la conversation et du canvas à l'organisation des médias jusqu'à l'export de la timeline.

- Catégorie : Éditeurs vidéo et ateliers de production ; Candidat principal.
- Périmètre d'application : Première version du projet ; stabilité de production complète et coûts de modèles restent à éprouver.
- État de maintenance : Commits sur les 90 derniers jours ; 341 commits sur 30 jours, 364 commits sur 90 jours.
- Licence : [Apache-2.0](https://api.github.com/repos/ThinkFlowLab/OpenDirector/license) ; Licence ouverte vérifiée. Identifiée via GitHub licenseInfo ; les poids de modèles, médias, polices, dépendances tierces et services managés relèvent de leurs propres licences
- Vérification fonctionnelle : 2026-11-12 ; [Source1](https://github.com/ThinkFlowLab/OpenDirector/blob/39288dfdf4f816798e5479c53363258fceeb6e11/README.md#L18).

## [AID Studio](https://github.com/shijue-aid/aid-studio)

Atelier auto-hébergeable de création de BD animées, dramas courts et productions audiovisuelles IA : script, personnages et décors, storyboard, génération d'images et de vidéos, doublage, canvas infini et prévisualisation 3D.

- Catégorie : Éditeurs vidéo et ateliers de production ; Candidat principal.
- Périmètre d'application : Les appels de modèles, le stockage et le calcul peuvent être facturés séparément ; les packs officiels d'assets (images, audio, vidéos) sont distribués séparément selon les versions ; le déploiement exige MySQL, Redis, Docker et d'autres dépendances ; les droits du contenu généré sur le script, les personnages et les médias restent à vérifier.
- État de maintenance : Commits sur les 90 derniers jours ; 44 commits sur 30 jours, 112 commits sur 90 jours.
- Licence : [MIT](https://github.com/shijue-aid/aid-studio/blob/9b78452d047b577d31d301c8998287139c93a312/LICENSE) ; Licence ouverte vérifiée. LICENSE racine du dépôt sous MIT ; NOTICE conserve les paternités tierces comme RuoYi-Vue ; le pack d'assets d'exemple officiel est distribué séparément ; les conditions des fournisseurs de modèles, du stockage et des ressources de calcul sont à part
- Vérification fonctionnelle : 2026-11-23 ; [Source1](https://github.com/shijue-aid/aid-studio/blob/9b78452d047b577d31d301c8998287139c93a312/README.md#L13) · [Source2](https://github.com/shijue-aid/aid-studio/blob/9b78452d047b577d31d301c8998287139c93a312/README.md#L43) · [Source3](https://github.com/shijue-aid/aid-studio/blob/9b78452d047b577d31d301c8998287139c93a312/README.md#L46).

## [CutVoke](https://github.com/frankShan001/CutVoke)

Éditeur vidéo open source local-first multiplateforme avec serveur MCP intégré, permettant à des agents comme Claude Code, Codex ou Cursor de monter aux côtés des humains sur la même timeline multi-piste non destructive.

- Catégorie : Éditeurs vidéo et ateliers de production ; Candidat principal.
- Périmètre d'application : Le package desktop embarque des composants tiers dont FFmpeg (GPLv3) ; les sous-titres peuvent utiliser faster-whisper en local, le modèle devant être téléchargé au premier usage ; les agents connectés sont majoritairement des services cloud — compte, coûts et politiques de données à part ; v0.3.6 est un aperçu gelé, désynchronisé de main, dont le README liste des problèmes connus (réutilisation de la fenêtre d'export, expiration de la préécoute, rognage des sous-titres verticaux longs) ; le package macOS est signé ad-hoc sans notarisation ; le projet a été créé en 2026-09 et reste peu mature.
- État de maintenance : Commits sur les 90 derniers jours ; 407 commits sur 30 jours, 548 commits sur 90 jours.
- Licence : [MIT](https://github.com/frankShan001/CutVoke/blob/a4920ad493c6317774141a9bccbd55eafe439b7c/LICENSE) ; Licence ouverte vérifiée. LICENSE racine du dépôt sous MIT ; le package desktop embarque des composants tiers sous leurs propres licences dont FFmpeg (GPLv3) ; les recettes d'effets communautaires, le modèle faster-whisper et les conditions des services IA connectés sont à part
- Vérification fonctionnelle : 2026-11-25 ; [Source1](https://github.com/frankShan001/CutVoke/blob/a4920ad493c6317774141a9bccbd55eafe439b7c/README.md#L28) · [Source2](https://github.com/frankShan001/CutVoke/blob/a4920ad493c6317774141a9bccbd55eafe439b7c/README.md#L121) · [Source3](https://github.com/frankShan001/CutVoke/blob/a4920ad493c6317774141a9bccbd55eafe439b7c/README.md#L159).

## [OpenReel Video](https://github.com/Augani/openreel-video)

Éditeur timeline open source, navigateur et desktop, avec coupe, sous-titres, mixage audio et export sans filigrane.

- Catégorie : Éditeurs vidéo et ateliers de production ; Candidat principal.
- Périmètre d'application : Capacités d'édition généralistes avant tout ; ne pas le considérer automatiquement comme un agent génératif.
- État de maintenance : Commits sur les 90 derniers jours ; 9 commits sur 30 jours, 20 commits sur 90 jours.
- Licence : [MIT](https://api.github.com/repos/Augani/openreel-video/license) ; Licence ouverte vérifiée. Identifiée via GitHub licenseInfo ; les poids de modèles, médias, polices, dépendances tierces et services managés relèvent de leurs propres licences
- Vérification fonctionnelle : 2026-11-12 ; [Source1](https://github.com/Augani/openreel-video/blob/367d7e90b61b5181f9861b852bb8b9d7a7d2954a/README.md#L7).

## [AI Video Production Editor](https://github.com/LudwigKienle/ai-video-production-editor)

Atelier local couvrant script, traitement de mise en scène, storyboard, génération des plans, puis montage, étalonnage et export.

- Catégorie : Éditeurs vidéo et ateliers de production ; Candidat principal.
- Périmètre d'application : Le BYOK envoie quand même les requêtes aux services de modèles configurés ; certaines capacités managées/facturées supposent des projets externes.
- État de maintenance : Commits sur les 90 derniers jours ; 11 commits sur 30 jours, 144 commits sur 90 jours.
- Licence : [GPL-3.0](https://api.github.com/repos/LudwigKienle/ai-video-production-editor/license) ; Licence ouverte vérifiée. Identifiée via GitHub licenseInfo ; les poids de modèles, médias, polices, dépendances tierces et services managés relèvent de leurs propres licences
- Vérification fonctionnelle : 2026-11-12 ; [Source1](https://github.com/LudwigKienle/ai-video-production-editor/blob/a368af45b6cfd35e22bd3b5e101db198e1ac89a9/README.md#L4).

## [MakeMyClip Editor](https://github.com/MakeMyClip/editor)

Encapsule les capacités de montage de FFmpeg via une timeline dans le navigateur local, un CLI, MCP et un Skill.

- Catégorie : Éditeurs vidéo et ateliers de production ; Candidat principal.
- Périmètre d'application : L'édition locale ne nécessite pas son API cloud ; UI navigateur, CLI et outils agent sont des entrées différentes du même projet.
- État de maintenance : Commits sur les 90 derniers jours ; 151 commits sur 30 jours, 153 commits sur 90 jours.
- Licence : [MIT](https://api.github.com/repos/MakeMyClip/editor/license) ; Licence ouverte vérifiée. Identifiée via GitHub licenseInfo ; les poids de modèles, médias, polices, dépendances tierces et services managés relèvent de leurs propres licences
- Vérification fonctionnelle : 2026-11-12 ; [Source1](https://github.com/MakeMyClip/editor/blob/f6f05206c1d2234d74134da27d322caebb260e6d/README.md#L7).

## [OpenKatana](https://github.com/rk0neki/OpenKatana)

Moteur de montage vidéo piloté par agent : Studio, CLI, MCP et ComfyUI.

- Catégorie : Éditeurs vidéo et ateliers de production ; Candidat principal.
- Périmètre d'application : Plutôt un moteur d'édition par code ; les modèles de génération effectifs et les applications ComfyUI restent à configurer.
- État de maintenance : Commits sur les 90 derniers jours ; 87 commits sur 30 jours, 126 commits sur 90 jours.
- Licence : [Apache-2.0](https://api.github.com/repos/rk0neki/OpenKatana/license) ; Licence ouverte vérifiée. Identifiée via GitHub licenseInfo ; les poids de modèles, médias, polices, dépendances tierces et services managés relèvent de leurs propres licences
- Vérification fonctionnelle : 2026-11-12 ; [Source1](https://github.com/rk0neki/OpenKatana/blob/b9282bf0740a7df5b5a8862b5e289ef4cd642641/README.md#L7).

## [OpenScene](https://github.com/Theorvane/OpenScene)

Éditeur vidéo desktop local où des agents IA peuvent manipuler la timeline, générer des médias et exporter.

- Catégorie : Éditeurs vidéo et ateliers de production ; Candidat principal.
- Périmètre d'application : La branche par défaut est une branche de développement ; le mobile et les capacités de génération sont à valider contre l'implémentation courante.
- État de maintenance : Commits sur les 90 derniers jours ; 42 commits sur 30 jours, 111 commits sur 90 jours.
- Licence : [MIT](https://api.github.com/repos/Theorvane/OpenScene/license) ; Licence ouverte vérifiée. Identifiée via GitHub licenseInfo ; les poids de modèles, médias, polices, dépendances tierces et services managés relèvent de leurs propres licences
- Vérification fonctionnelle : 2026-11-12 ; [Source1](https://github.com/Theorvane/OpenScene/blob/4bd3d3c4c15fb27dd0b521065643b3a2d516be08/README.md#L8).

## [Waoowaoo](https://github.com/waooAI/waoowaoo)

Atelier de création d'images et de vidéos IA gérant médias de référence et contenus générés via canvas et Assistant, avec assemblage de segments vidéo.

- Catégorie : Éditeurs vidéo et ateliers de production ; Licence restreinte.
- Périmètre d'application : Version encore en bêta ; les capacités image et vidéo dépendent du modèle ; les appels à des modèles externes comme OpenRouter peuvent être payants.
- État de maintenance : Commits sur les 90 derniers jours ; 0 commits sur 30 jours, 6 commits sur 90 jours.
- Licence : [Elastic License 2.0](https://github.com/waooAI/waoowaoo/blob/dfec20e32298ed675050329e4a41477024148399/LICENSE) ; Code source visible mais non open source OSI. Sous ELv2 depuis v0.5.0-beta.1 : interdit d'héberger les fonctions principales comme service pour des tiers sans autorisation ; ce n'est pas une licence OSI open source, les versions anciennes peuvent être sous une autre licence.
- Vérification fonctionnelle : 2026-11-20 ; [Source1](https://github.com/waooAI/waoowaoo/blob/dfec20e32298ed675050329e4a41477024148399/README_zh.md#L24).

## [SeeCut](https://github.com/YeJe-cpu/SeeCut)

Espace de skills faisant comprendre, monter, rendre et contrôler visuellement par un coding agent des vidéos courtes d'explication face caméra.

- Catégorie : Éditeurs vidéo et ateliers de production ; Licence restreinte.
- Périmètre d'application : C'est un skill/processus, pas un NLE desktop autonome ; le brouillon CapCut n'est qu'un ajustement ultérieur optionnel.
- État de maintenance : Commits sur les 90 derniers jours ; 1 commits sur 30 jours, 11 commits sur 90 jours.
- Licence : [PolyForm Noncommercial-1.0.0](https://github.com/YeJe-cpu/SeeCut/blob/b05d7ed27404a064060e0d370402f562b0c0c02e/LICENSE) ; Code source visible mais non open source OSI. Usage non commercial uniquement, ce n'est pas une licence open source OSI
- Vérification fonctionnelle : 2026-11-12 ; [Source1](https://github.com/YeJe-cpu/SeeCut/blob/b05d7ed27404a064060e0d370402f562b0c0c02e/README.md#L5).

## [ScriptCut](https://github.com/FernandoAbishai/ScriptCut)

Montage local, découpage en formats courts et export réseaux sociaux pilotés depuis l'édition du texte de transcription.

- Catégorie : Éditeurs vidéo et ateliers de production ; Candidat principal.
- Périmètre d'application : Axé sur le dégrossissage par le texte ; cela ne remplace pas un atelier complet d'effets visuels et de génération.
- État de maintenance : Commits sur les 90 derniers jours ; 0 commits sur 30 jours, 62 commits sur 90 jours.
- Licence : [AGPL-3.0](https://api.github.com/repos/FernandoAbishai/ScriptCut/license) ; Licence ouverte vérifiée. Identifiée via GitHub licenseInfo ; les poids de modèles, médias, polices, dépendances tierces et services managés relèvent de leurs propres licences
- Vérification fonctionnelle : 2026-11-12 ; [Source1](https://github.com/FernandoAbishai/ScriptCut/blob/12c6fe495939da344e6af3e942a45dfdfb2132fa/README.md#L7).

## [Cutline](https://github.com/Aepzie/cutline)

Éditeur timeline dans le navigateur offrant une interface MCP de premier plan pour une manipulation en direct par des agents.

- Catégorie : Éditeurs vidéo et ateliers de production ; Candidat principal.
- Périmètre d'application : Les fichiers proxy pour les gros médias et le chemin d'encodage du navigateur restent à évaluer selon le mode de déploiement.
- État de maintenance : Commits sur les 90 derniers jours ; 0 commits sur 30 jours, 109 commits sur 90 jours.
- Licence : [MIT](https://api.github.com/repos/Aepzie/cutline/license) ; Licence ouverte vérifiée. Identifiée via GitHub licenseInfo ; les poids de modèles, médias, polices, dépendances tierces et services managés relèvent de leurs propres licences
- Vérification fonctionnelle : 2026-11-12 ; [Source1](https://github.com/Aepzie/cutline/blob/ab71520285881d8dfa78f5ebca00f8a166e84962/README.md#L8).

## [Moyin Creator](https://github.com/MemeCalculate/moyin-creator)

Outil desktop Electron de production audiovisuelle IA qui enchaîne automatiquement un pipeline en cinq étapes — script, personnages, scènes, mise en scène, Seedance 2.0 — pour produire en série des dramas courts et des séries d'animation.

- Catégorie : Éditeurs vidéo et ateliers de production ; Candidat principal.
- Périmètre d'application : Les clés API du fournisseur d'IA sont à la charge de l'utilisateur (multi-fournisseurs et rotation de clés pris en charge), la génération étant facturée par le fournisseur ; double licence AGPL-3.0 et commerciale : modifications fermées, intégration dans un produit commercial ou SaaS supposent l'achat d'une licence commerciale ; la cohérence des personnages dépend de la bible des personnages et des images de référence — cohérence inter-plans et qualité du montage final à valider selon le modèle utilisé ; depuis le 2026-08-27, la branche par défaut ne porte que des modifications de README ; la dernière release est une étiquette de version custom annotée sponsor ; les versions des paquets hébergés citées dans le README divergent de celles des Releases.
- État de maintenance : Aucun commit depuis 91–365 jours ; 0 commits sur 30 jours, 0 commits sur 90 jours.
- Licence : [AGPL-3.0 + double licence commerciale](https://github.com/MemeCalculate/moyin-creator/blob/7e5c5655de94d49885e13c369f0a71212893a0aa/COMMERCIAL_LICENSE.md) ; Licence composite/conditionnelle. LICENSE contient le texte AGPL-3.0 ; le README et COMMERCIAL_LICENSE.md déclarent une double licence : modifications fermées, intégration dans un produit commercial ou un SaaS sans ouverture du code supposent une licence commerciale ; l'usage interne de dépendances comme `@opencut/ai-core` et les conditions des services de modèles sont à part
- Vérification fonctionnelle : 2026-11-25 ; [Source1](https://github.com/MemeCalculate/moyin-creator/blob/7e5c5655de94d49885e13c369f0a71212893a0aa/README.md#L70) · [Source2](https://github.com/MemeCalculate/moyin-creator/blob/7e5c5655de94d49885e13c369f0a71212893a0aa/README.md#L105) · [Source3](https://github.com/MemeCalculate/moyin-creator/blob/7e5c5655de94d49885e13c369f0a71212893a0aa/README.md#L122).

## [Hypit](https://github.com/hypit-ai/hypit)

Permet aux coding agents de dupliquer des vidéos de référence en workflows éditables et rejouables, puis de générer des variantes de contenu par lot.

- Catégorie : Production vidéo agentique et automatisation ; Licence restreinte.
- Périmètre d'application : Dupliquer des vidéos populaires engage la vidéo source, les personnes, la musique, les médias et les droits de marque ; les modèles de génération et les API sont des services externes optionnels, coûts et flux de données dépendant du fournisseur.
- État de maintenance : Commits sur les 90 derniers jours ; 16 commits sur 30 jours, 704 commits sur 90 jours.
- Licence : [Hypit Open Source License (Apache-2.0 modifiée)](https://github.com/hypit-ai/hypit/blob/6bacce093695ccc2bde5aa5d7de230e9682ffa79/LICENSE) ; Code source visible mais non open source OSI. Restreint l'hébergement multi-locataire, la redistribution commerciale et la suppression des mentions de marque/copyright ; ces usages supposent une licence commerciale — ce n'est pas un Apache-2.0 standard
- Vérification fonctionnelle : 2026-11-13 ; [Source1](https://github.com/hypit-ai/hypit/blob/6bacce093695ccc2bde5aa5d7de230e9682ffa79/README.md#L51) · [Source2](https://github.com/hypit-ai/hypit/blob/6bacce093695ccc2bde5aa5d7de230e9682ffa79/README.md#L164) · [Source3](https://github.com/hypit-ai/hypit/blob/6bacce093695ccc2bde5aa5d7de230e9682ffa79/README.md#L338).

## [OpenMotion](https://github.com/nexu-io/openmotion)

Atelier de duplication de vidéos de référence et de motion design de marque pour coding agents locaux, avec Motion.md, timeline visuelle et export MP4.

- Catégorie : Production vidéo agentique et automatisation ; Candidat principal.
- Périmètre d'application : Les vidéos de référence, les personnes, la musique, la marque et les médias doivent être autorisés séparément ; la génération de médias dépend d'API/abonnements fournis, les modèles embarqués et les composants tiers suivant leurs propres LICENSE/NOTICE.
- État de maintenance : Commits sur les 90 derniers jours ; 842 commits sur 30 jours, 847 commits sur 90 jours.
- Licence : [Apache-2.0](https://github.com/nexu-io/openmotion/blob/fcbaa2b0296167b0f14f47aa6c414f5bdd41316f/LICENSE) ; Licence ouverte vérifiée. LICENSE racine du dépôt sous Apache-2.0 standard ; les templates intégrés, les icônes de modèles et les composants vendor ont leurs propres LICENSE/NOTICE, à conserver et vérifier en cas de distribution ou de réutilisation
- Vérification fonctionnelle : 2026-11-17 ; [Source1](https://github.com/nexu-io/openmotion/blob/fcbaa2b0296167b0f14f47aa6c414f5bdd41316f/README.md#L40) · [Source2](https://github.com/nexu-io/openmotion/blob/fcbaa2b0296167b0f14f47aa6c414f5bdd41316f/README.md#L308) · [Source3](https://github.com/nexu-io/openmotion/blob/fcbaa2b0296167b0f14f47aa6c414f5bdd41316f/README.md#L386).

## [OpenMontage](https://github.com/OpenMontageInc/OpenMontage)

Système de production vidéo multi-pipelines pour coding agents : recherche, script, médias, doublage, sous-titres et rendu.

- Catégorie : Production vidéo agentique et automatisation ; Candidat principal.
- Périmètre d'application : Certains fournisseurs de génération et de voix sont des services payants ; un grand nombre de fichiers de skill n'égale pas une chaîne validée de bout en bout.
- État de maintenance : Commits sur les 90 derniers jours ; 147 commits sur 30 jours, 272 commits sur 90 jours.
- Licence : [AGPL-3.0](https://api.github.com/repos/OpenMontageInc/OpenMontage/license) ; Licence ouverte vérifiée. Identifiée via GitHub licenseInfo ; les poids de modèles, médias, polices, dépendances tierces et services managés relèvent de leurs propres licences
- Vérification fonctionnelle : 2026-11-12 ; [Source1](https://github.com/OpenMontageInc/OpenMontage/blob/fecb9a1e3cc23ef84de30b272059457a427f16f8/README.md#L14).

## [OpenFilm](https://github.com/openfilm/openfilm)

Permet aux coding agents de créer, inspecter, éditer et rendre des vidéos par le code, avec une interface éditable.

- Catégorie : Production vidéo agentique et automatisation ; Candidat principal.
- Périmètre d'application : Les plans par code diffèrent d'une timeline de médias réels ; les licences des banques de médias et de sons sont à vérifier asset par asset.
- État de maintenance : Commits sur les 90 derniers jours ; 123 commits sur 30 jours, 305 commits sur 90 jours.
- Licence : [MIT](https://api.github.com/repos/openfilm/openfilm/license) ; Licence ouverte vérifiée. Identifiée via GitHub licenseInfo ; les poids de modèles, médias, polices, dépendances tierces et services managés relèvent de leurs propres licences
- Vérification fonctionnelle : 2026-11-12 ; [Source1](https://github.com/openfilm/openfilm/blob/f59cd4e0973feaf6917dcf3229b178b6baf9ad3f/README.md#L7).

## [Rea Video](https://github.com/JuneYaooo/rea-video)

Déconstruit en retour les parts tournées, IA et code d'une vidéo et produit un plan de duplication au niveau du plan ainsi qu'un VIDEO.md.

- Catégorie : Production vidéo agentique et automatisation ; Infrastructure adjacente.
- Périmètre d'application : Fait surtout de l'analyse et de la planification de duplication ; ne se confond pas avec un montageur ou un générateur final.
- État de maintenance : Commits sur les 90 derniers jours ; 219 commits sur 30 jours, 219 commits sur 90 jours.
- Licence : [Apache-2.0](https://api.github.com/repos/JuneYaooo/rea-video/license) ; Licence ouverte vérifiée. Identifiée via GitHub licenseInfo ; les poids de modèles, médias, polices, dépendances tierces et services managés relèvent de leurs propres licences
- Vérification fonctionnelle : 2026-11-12 ; [Source1](https://github.com/JuneYaooo/rea-video/blob/4111ad9adb4936d92f6d57657000b414fee9f01f/README.md#L8).

## [Video Autopilot Kit](https://github.com/Hao0321/video-autopilot-kit)

Framework d'automatisation pour la planification vidéo, l'audit, la revue et l'apprentissage des effets.

- Catégorie : Production vidéo agentique et automatisation ; Candidat principal.
- Périmètre d'application : Le montage et le rendu effectifs dépendent d'Editkin ; installer seul ce dépôt ne produit pas de montage fini.
- État de maintenance : Commits sur les 90 derniers jours ; 9 commits sur 30 jours, 33 commits sur 90 jours.
- Licence : [MIT](https://api.github.com/repos/Hao0321/video-autopilot-kit/license) ; Licence ouverte vérifiée. Identifiée via GitHub licenseInfo ; les poids de modèles, médias, polices, dépendances tierces et services managés relèvent de leurs propres licences
- Vérification fonctionnelle : 2026-11-12 ; [Source1](https://github.com/Hao0321/video-autopilot-kit/blob/b48c7d9a624ebceaa3a99f3f4aad6006e2be53fb/README.md#L1).

## [Video Director](https://github.com/win4r/video-director)

Guide Claude Code pour planifier, rendre et contrôler des courts métrages via HTML/Canvas/SVG/Three.js/GSAP/Remotion.

- Catégorie : Production vidéo agentique et automatisation ; Candidat principal.
- Périmètre d'application : Surtout optimisé pour des modèles Claude précis ; la qualité n'est pas héritée automatiquement par d'autres agents.
- État de maintenance : Commits sur les 90 derniers jours ; 17 commits sur 30 jours, 20 commits sur 90 jours.
- Licence : [MIT](https://api.github.com/repos/win4r/video-director/license) ; Licence ouverte vérifiée. Identifiée via GitHub licenseInfo ; les poids de modèles, médias, polices, dépendances tierces et services managés relèvent de leurs propres licences
- Vérification fonctionnelle : 2026-11-12 ; [Source1](https://github.com/win4r/video-director/blob/02d1912ab251bf5235b45e8e7aad81b4bc786b15/README.md#L11).

## [Video Use](https://github.com/browser-use/video-use)

Montage, sous-titres, étalonnage, incrustation de motion design et contrôle de sortie sur des rushes bruts via coding agent et FFmpeg.

- Catégorie : Production vidéo agentique et automatisation ; Candidat principal.
- Périmètre d'application : Ce n'est pas un outil d'automatisation de la vidéo par le navigateur ; les dépendances exactes et les flux cloud sont à vérifier selon la configuration du projet.
- État de maintenance : Commits sur les 90 derniers jours ; 0 commits sur 30 jours, 5 commits sur 90 jours.
- Licence : [MIT](https://github.com/browser-use/video-use/blob/43cfc566833548093455c9d4a46bd69913b7e552/LICENSE) ; Licence ouverte vérifiée. LICENSE racine sous MIT ; les services de modèles, les médias et les dépendances externes relèvent d'autres licences.
- Vérification fonctionnelle : 2026-11-21 ; [Source1](https://github.com/browser-use/video-use/blob/43cfc566833548093455c9d4a46bd69913b7e552/README.md#L7).

## [WeVisCut](https://github.com/Tencent/WeVisCut)

Transforme des articles de savoir ou des scripts d'explication en vidéos de plusieurs minutes via planification, recherche de médias, montage, contrôle et réparation.

- Catégorie : Production vidéo agentique et automatisation ; Candidat principal.
- Périmètre d'application : Le modèle de stratégie 9B, le runtime d'outils et Studio doivent être déployés dans l'environnement officiel ; les résultats de l'auteur ne valent pas classement inter-projets.
- État de maintenance : Commits sur les 90 derniers jours ; 2 commits sur 30 jours, 28 commits sur 90 jours.
- Licence : [Apache-2.0](https://github.com/Tencent/WeVisCut/blob/94dc8a7fe43a5e0da21e97d5aaf470a39329db3a/LICENSE) ; Licence ouverte vérifiée. La LICENSE racine précise que le code, les paramètres et les poids publics sont sous Apache-2.0 ; les composants tiers sont à part
- Vérification fonctionnelle : 2026-11-12 ; [Source1](https://github.com/Tencent/WeVisCut/blob/94dc8a7fe43a5e0da21e97d5aaf470a39329db3a/README.md#L7).

## [NeonClipping](https://github.com/iamajmeena/neonclipping)

Collez un lien pour découper localement de longues vidéos YouTube/Twitch/Kick ou vos propres MP4 en segments 9:16 aux sous-titres incrustés, avec titres et accroches générés.

- Catégorie : Vidéos courtes de savoir, extraits et vulgarisation ; Candidat principal.
- Périmètre d'application : Le montage repose sur yt-dlp, Streamlink, faster-whisper, FFmpeg et éventuellement un modèle Ollama local ; sans sous-titres YouTube, la source exige une reconnaissance locale ou une importation de sous-titres, avec perte de qualité ; la vitesse annoncée et les 187 contrôles du README sont des auto-tests de l'auteur, pas un benchmark indépendant ; le téléchargement et la redistribution sont encadrés par les conditions des plateformes et les droits des médias.
- État de maintenance : Commits sur les 90 derniers jours ; 89 commits sur 30 jours, 89 commits sur 90 jours.
- Licence : [MIT](https://github.com/iamajmeena/neonclipping/blob/052500437bc8d44ed5c8311e8ce686373e098086/LICENSE) ; Licence ouverte vérifiée. LICENSE racine du dépôt sous MIT ; les dépendances du fichier requirements comme yt-dlp, faster-whisper, Streamlink, av et static-ffmpeg, ainsi que les poids téléchargés via Ollama et les polices système relèvent d'autres licences
- Vérification fonctionnelle : 2026-11-23 ; [Source1](https://github.com/iamajmeena/neonclipping/blob/052500437bc8d44ed5c8311e8ce686373e098086/README.md#L5) · [Source2](https://github.com/iamajmeena/neonclipping/blob/052500437bc8d44ed5c8311e8ce686373e098086/README.md#L45) · [Source3](https://github.com/iamajmeena/neonclipping/blob/052500437bc8d44ed5c8311e8ce686373e098086/README.md#L114).

## [Clipmint](https://github.com/kleZ799/clipmint)

Convertit podcasts, interviews, tutoriels et VOD en Shorts/Reels/TikTok verticaux sous-titrés.

- Catégorie : Vidéos courtes de savoir, extraits et vulgarisation ; Candidat principal.
- Périmètre d'application : La détection des moments forts, le recadrage et la publication dépendent de modèles locaux et de la configuration des plateformes.
- État de maintenance : Commits sur les 90 derniers jours ; 185 commits sur 30 jours, 615 commits sur 90 jours.
- Licence : [MIT](https://api.github.com/repos/kleZ799/clipmint/license) ; Licence ouverte vérifiée. Identifiée via GitHub licenseInfo ; les poids de modèles, médias, polices, dépendances tierces et services managés relèvent de leurs propres licences
- Vérification fonctionnelle : 2026-11-12 ; [Source1](https://github.com/kleZ799/clipmint/blob/f2f7ed16871a390d0fd5274fb28b157f22ac57e3/README.md#L7).

## [ChrisHKAI Video](https://github.com/ChrisHKAI/ChrisHKAI-Video)

Skill de coding agent organisant les ressources publiques d'un créateur en courts métrages 3D façon jouet.

- Catégorie : Vidéos courtes de savoir, extraits et vulgarisation ; Candidat principal.
- Périmètre d'application : La qualité du montage complet sous Codex n'est pas encore validée ; l'usage des ressources publiques et les droits à l'image incombent à l'utilisateur.
- État de maintenance : Commits sur les 90 derniers jours ; 168 commits sur 30 jours, 207 commits sur 90 jours.
- Licence : [MIT](https://api.github.com/repos/ChrisHKAI/ChrisHKAI-Video/license) ; Licence ouverte vérifiée. Identifiée via GitHub licenseInfo ; les poids de modèles, médias, polices, dépendances tierces et services managés relèvent de leurs propres licences
- Vérification fonctionnelle : 2026-11-12 ; [Source1](https://github.com/ChrisHKAI/ChrisHKAI-Video/blob/15b66ee613e621f82ba781d27547a67e76c55f50/README.md#L7).

## [Lanshu AI Presenter Video](https://github.com/cclank/lanshu-create-ai-presenter-video)

Agent Skill transformant un sujet ou un script en vidéo d'explication validée avec avatar numérique ou style.

- Catégorie : Vidéos courtes de savoir, extraits et vulgarisation ; Candidat principal.
- Périmètre d'application : L'avatar, la voix, la synchronisation labiale et la reconnaissance dépendent des fournisseurs externes choisis au runtime.
- État de maintenance : Commits sur les 90 derniers jours ; 1 commits sur 30 jours, 17 commits sur 90 jours.
- Licence : [MIT](https://api.github.com/repos/cclank/lanshu-create-ai-presenter-video/license) ; Licence ouverte vérifiée. Identifiée via GitHub licenseInfo ; les poids de modèles, médias, polices, dépendances tierces et services managés relèvent de leurs propres licences
- Vérification fonctionnelle : 2026-11-12 ; [Source1](https://github.com/cclank/lanshu-create-ai-presenter-video/blob/762d3ee42623b75a4ec63ad6aa61ace69d78ce6e/README.md#L23).

## [Claude Animated Shorts](https://github.com/mromidev/claude-animated-shorts)

Skill de courts métrages verticaux d'histoires animées avec Three.js, Remotion, musique et effets sonores.

- Catégorie : Vidéos courtes de savoir, extraits et vulgarisation ; Candidat principal.
- Périmètre d'application : Pack méthodologique bâti sur un seul exemple terminé ; la généralisation thématique et visuelle reste à éprouver.
- État de maintenance : Commits sur les 90 derniers jours ; 2 commits sur 30 jours, 2 commits sur 90 jours.
- Licence : [MIT](https://api.github.com/repos/mromidev/claude-animated-shorts/license) ; Licence ouverte vérifiée. Identifiée via GitHub licenseInfo ; les poids de modèles, médias, polices, dépendances tierces et services managés relèvent de leurs propres licences
- Vérification fonctionnelle : 2026-11-12 ; [Source1](https://github.com/mromidev/claude-animated-shorts/blob/e3b817b6afc6cd413466d43f11ba31209e034bbf/README.md#L5).

## [Vibe Knowledge](https://github.com/andyhuo520/vibe-knowledge)

Skill de capsules de savoir : vérification du point de savoir, rédaction, doublage, vidéo par code, contrôle qualité et pack de publication.

- Catégorie : Vidéos courtes de savoir, extraits et vulgarisation ; Candidat principal.
- Périmètre d'application : Les plans enrichis peuvent appeler des plateformes de génération externes ; comparer séparément l'illustration de base par code et le niveau enrichi.
- État de maintenance : Commits sur les 90 derniers jours ; 3 commits sur 30 jours, 3 commits sur 90 jours.
- Licence : [MIT](https://api.github.com/repos/andyhuo520/vibe-knowledge/license) ; Licence ouverte vérifiée. Identifiée via GitHub licenseInfo ; les poids de modèles, médias, polices, dépendances tierces et services managés relèvent de leurs propres licences
- Vérification fonctionnelle : 2026-11-12 ; [Source1](https://github.com/andyhuo520/vibe-knowledge/blob/c3a13a85f7cc560e5d396f063baecea4b2748e1e/README.md#L5).

## [Vox Director](https://github.com/alisa0808/vox-director)

Agent Skill de bout en bout : du sujet à une vidéo d'explication/publicité en collage papier façon Vox.

- Catégorie : Vidéos courtes de savoir, extraits et vulgarisation ; Candidat principal.
- Périmètre d'application : La génération des médias dépend d'Atlas Cloud et de FFmpeg ; l'imitation de style appelle la prudence sur la marque et les droits.
- État de maintenance : Commits sur les 90 derniers jours ; 0 commits sur 30 jours, 1 commits sur 90 jours.
- Licence : [MIT](https://api.github.com/repos/alisa0808/vox-director/license) ; Licence ouverte vérifiée. Identifiée via GitHub licenseInfo ; les poids de modèles, médias, polices, dépendances tierces et services managés relèvent de leurs propres licences
- Vérification fonctionnelle : 2026-11-12 ; [Source1](https://github.com/alisa0808/vox-director/blob/6a85a7c341610442a6a5b1885e6e0217ab82a11f/README.md#L5).

## [Video to Shorts Skill](https://github.com/social-media-skills/video-to-shorts-skill)

Fait transformer par un agent de longues vidéos ou des podcasts en shorts verticaux sous-titrés mot à mot, avec publication optionnelle.

- Catégorie : Vidéos courtes de savoir, extraits et vulgarisation ; Candidat principal.
- Périmètre d'application : La publication automatique engage des identifiants de plateforme ; le téléchargement de la vidéo source doit respecter les conditions et les autorisations.
- État de maintenance : Commits sur les 90 derniers jours ; 3 commits sur 30 jours, 3 commits sur 90 jours.
- Licence : [MIT](https://api.github.com/repos/social-media-skills/video-to-shorts-skill/license) ; Licence ouverte vérifiée. Identifiée via GitHub licenseInfo ; les poids de modèles, médias, polices, dépendances tierces et services managés relèvent de leurs propres licences
- Vérification fonctionnelle : 2026-11-12 ; [Source1](https://github.com/social-media-skills/video-to-shorts-skill/blob/2e20fb008b584f3927798f36f580401d75318600/README.md#L3).

## [Pixelle-Video](https://github.com/ATH-MaaS/Pixelle-Video)

Génère texte, images ou vidéos, doublage et assemblage en vidéo courte à partir d'un sujet ; workflows ComfyUI et API médias pris en charge.

- Catégorie : Vidéos courtes de savoir, extraits et vulgarisation ; Candidat principal.
- Périmètre d'application : L'adresse AIDC-AI d'origine a migré ; la configuration, les coûts et les licences des médias de ComfyUI local, RunningHub ou des API de modèles sont à vérifier séparément.
- État de maintenance : Aucun commit depuis 91–365 jours ; 0 commits sur 30 jours, 0 commits sur 90 jours.
- Licence : [Apache-2.0](https://github.com/ATH-MaaS/Pixelle-Video/blob/848b054e4fae40dabc62ec58e960b573e83793ac/LICENSE) ; Licence ouverte vérifiée. LICENSE racine sous Apache-2.0 ; NOTICE énumère les dépendances tierces et leurs licences.
- Vérification fonctionnelle : 2026-11-20 ; [Source1](https://github.com/ATH-MaaS/Pixelle-Video/blob/848b054e4fae40dabc62ec58e960b573e83793ac/README.md#L52).

## [Atlas Explainer](https://github.com/AtlasCloudAI/atlas-explainer)

Skill/CLI générant une vidéo d'explication papercraft doublée à partir d'un seul sujet.

- Catégorie : Vidéos courtes de savoir, extraits et vulgarisation ; Candidat principal.
- Périmètre d'application : La génération des images et de la voix dépend de l'API Atlas Cloud — ce n'est pas une chaîne entièrement locale.
- État de maintenance : Aucun commit depuis 91–365 jours ; 0 commits sur 30 jours, 0 commits sur 90 jours.
- Licence : [MIT](https://api.github.com/repos/AtlasCloudAI/atlas-explainer/license) ; Licence ouverte vérifiée. Identifiée via GitHub licenseInfo ; les poids de modèles, médias, polices, dépendances tierces et services managés relèvent de leurs propres licences
- Vérification fonctionnelle : 2026-11-12 ; [Source1](https://github.com/AtlasCloudAI/atlas-explainer/blob/02f0d82392191a1c980a8a40348eb686b9e157dd/README.md#L3).

## [FFmpeg Skill](https://github.com/kajisho5/ffmpeg-skill)

CLI et MCP offrant aux coding agents montage FFmpeg local, sous-titres, export de formats et contrôle de sortie.

- Catégorie : Agent Skills, MCP et outils de montage ; Candidat principal.
- Périmètre d'application : Nécessite FFmpeg et Python sur la machine ; le skill, le build FFmpeg et les médias suivent leurs propres licences, et les résultats effectifs n'ont pas été testés.
- État de maintenance : Commits sur les 90 derniers jours ; 575 commits sur 30 jours, 1003 commits sur 90 jours.
- Licence : [MIT](https://github.com/kajisho5/ffmpeg-skill/blob/45df6b9ab0740cecc15d0169165e8cfbcefdfb0b/LICENSE) ; Licence ouverte vérifiée. LICENSE racine du dépôt de skill sous MIT ; les licences de FFmpeg et des encodeurs sont à vérifier selon le build précis.
- Vérification fonctionnelle : 2026-11-21 ; [Source1](https://github.com/kajisho5/ffmpeg-skill/blob/45df6b9ab0740cecc15d0169165e8cfbcefdfb0b/README.md#L67).

## [Claude Code Video Toolkit](https://github.com/digitalsamba/claude-code-video-toolkit)

Skills, templates, commandes et outils pour Claude Code : script, doublage, musique, génération d'images et de vidéos, contrôle qualité, rendu et publication, avec migration possible vers Codex et Kiro CLI.

- Catégorie : Agent Skills, MCP et outils de montage ; Candidat principal.
- Périmètre d'application : Nécessite Node 22+ et Claude Code ; les modèles IA sont déployés sur vos propres comptes cloud GPU Modal/RunPod à votre coût ; le coût de 0,33 $ et la vidéo d'exemple du README sont des auto-tests de l'auteur ; les add-ons communautaires, les skills de design tiers et les services de publication managés ont leurs propres licences et conditions ; les contenus générés, les voix clonées et les médias restent à vérifier.
- État de maintenance : Commits sur les 90 derniers jours ; 438 commits sur 30 jours, 551 commits sur 90 jours.
- Licence : [MIT](https://github.com/digitalsamba/claude-code-video-toolkit/blob/b3437fcd462c23b3c46cfd28f8cb61b71039269b/LICENSE) ; Licence ouverte vérifiée. LICENSE racine du dépôt sous MIT (copyright Digital Samba) ; les poids des modèles appelés (Qwen3-TTS, FLUX.2, Ideogram 4, ACE-Step, LTX-Video, etc.), les services externes comme ElevenLabs, le moteur de rendu Remotion et les add-ons communautaires (par exemple arkiv sous PolyForm Perimeter) ont des licences indépendantes
- Vérification fonctionnelle : 2026-11-24 ; [Source1](https://github.com/digitalsamba/claude-code-video-toolkit/blob/b3437fcd462c23b3c46cfd28f8cb61b71039269b/README.md#L9) · [Source2](https://github.com/digitalsamba/claude-code-video-toolkit/blob/b3437fcd462c23b3c46cfd28f8cb61b71039269b/README.md#L12) · [Source3](https://github.com/digitalsamba/claude-code-video-toolkit/blob/b3437fcd462c23b3c46cfd28f8cb61b71039269b/README.md#L66).

## [Video Shotcraft](https://github.com/Vincentwei1021/video-shotcraft)

Fournit aux agents des recettes de plans, des storyboards, des animations Remotion, un montage rythmé et un contrôle image par image.

- Catégorie : Agent Skills, MCP et outils de montage ; Candidat principal.
- Périmètre d'application : La bibliothèque de plans est une méthode créative et un actif de code ; elle ne remplace pas un éditeur timeline généraliste.
- État de maintenance : Commits sur les 90 derniers jours ; 38 commits sur 30 jours, 54 commits sur 90 jours.
- Licence : [Apache-2.0](https://api.github.com/repos/Vincentwei1021/video-shotcraft/license) ; Licence ouverte vérifiée. Identifiée via GitHub licenseInfo ; les poids de modèles, médias, polices, dépendances tierces et services managés relèvent de leurs propres licences
- Vérification fonctionnelle : 2026-11-12 ; [Source1](https://github.com/Vincentwei1021/video-shotcraft/blob/6700db2ba80572ebc777b99d72049679fed9840c/README.md#L26).

## [Remocn](https://github.com/Remocn/remocn)

Plugin Claude Code, skill d'agent et serveur MCP pour produire des vidéos Remotion à partir de 935 composants sous licence MIT : l'agent établit d'abord le storyboard, puis écrit la vidéo.

- Catégorie : Agent Skills, MCP et outils de montage ; Candidat principal.
- Périmètre d'application : Exige Remotion et la CLI shadcn qui installe les composants ; `scene-reviewer` ne vérifie que les images fixes (texte rogné, images vides, contraste faible), la qualité finale et le temps de rendu n'ont pas été mesurés ; composants, polices et MCP hébergé ont leurs propres conditions, et Remotion se licence à part.
- État de maintenance : Commits sur les 90 derniers jours ; 149 commits sur 30 jours, 187 commits sur 90 jours.
- Licence : [MIT](https://github.com/Remocn/remocn/blob/ac1e4081edcc70757db4dc4af32b079cb9ae5490/LICENSE) ; Licence ouverte vérifiée. La LICENSE racine est MIT ; le README indique les composants sous MIT, tandis que le moteur Remotion, les polices et le service MCP hébergé restent soumis à leurs propres conditions.
- Vérification fonctionnelle : 2026-11-26 ; [Source1](https://github.com/Remocn/remocn/blob/ac1e4081edcc70757db4dc4af32b079cb9ae5490/README.md#L9) · [Source2](https://github.com/Remocn/remocn/blob/ac1e4081edcc70757db4dc4af32b079cb9ae5490/README.md#L37) · [Source3](https://github.com/Remocn/remocn/blob/ac1e4081edcc70757db4dc4af32b079cb9ae5490/README.md#L73).

## [Kinocut](https://github.com/KyaniteLabs/kinocut)

MCP/Python/CLI de montage vidéo local avec garde-fous, pré-vols, reçus et portes qualité.

- Catégorie : Agent Skills, MCP et outils de montage ; Candidat principal.
- Périmètre d'application : Encapsule FFmpeg ainsi que Whisper/HyperFrames en option ; des outils typés ne garantissent pas le sens du montage.
- État de maintenance : Commits sur les 90 derniers jours ; 371 commits sur 30 jours, 698 commits sur 90 jours.
- Licence : [Apache-2.0](https://api.github.com/repos/KyaniteLabs/kinocut/license) ; Licence ouverte vérifiée. Identifiée via GitHub licenseInfo ; les poids de modèles, médias, polices, dépendances tierces et services managés relèvent de leurs propres licences
- Vérification fonctionnelle : 2026-11-12 ; [Source1](https://github.com/KyaniteLabs/kinocut/blob/4ad02dba114cf12163663e7cd39da92d4f735212/README.md#L13).

## [Manju Laoli Skill](https://github.com/lixiaoxiao9888-create/manju-laoli-skill)

Pack de skills OpenClaw pour BD animées et dramas courts IA : script, verrouillage des assets, storyboard, scènes de combat, prompts d'alimentation Seedance et contrôles automatiques.

- Catégorie : Agent Skills, MCP et outils de montage ; Candidat principal.
- Périmètre d'application : Cible les plateformes d'agents OpenClaw, Coze, Dify, etc. ; la seule filière de modèle vidéo du pack est Seedance 2.5/2.0 ; l'auteur marque le pack en bêta et agrège du contenu open source sans lister item par item les NOTICE externes de règles et de médias ; le pack ne contient aucune image — les médias sont générés sur des plateformes externes et leurs droits restent à obtenir.
- État de maintenance : Commits sur les 90 derniers jours ; 10 commits sur 30 jours, 53 commits sur 90 jours.
- Licence : [MIT](https://github.com/lixiaoxiao9888-create/manju-laoli-skill/blob/a01e647ac10134918a5de1b18bfe9317e5541a44/LICENSE) ; Licence ouverte vérifiée. Racine du dépôt et short-drama-director tous deux sous MIT ; l'auteur marque le projet en bêta et agrège du contenu open source sans NOTICE tiers item par item — la redistribution des textes de la base de règles et des exemples reste à vérifier
- Vérification fonctionnelle : 2026-11-23 ; [Source1](https://github.com/lixiaoxiao9888-create/manju-laoli-skill/blob/a01e647ac10134918a5de1b18bfe9317e5541a44/README.md#L60) · [Source2](https://github.com/lixiaoxiao9888-create/manju-laoli-skill/blob/a01e647ac10134918a5de1b18bfe9317e5541a44/README.md#L72) · [Source3](https://github.com/lixiaoxiao9888-create/manju-laoli-skill/blob/a01e647ac10134918a5de1b18bfe9317e5541a44/README.md#L137).

## [Remotion Agent Skills](https://github.com/remotion-dev/skills)

Skills officiels permettant aux coding agents de créer, prévisualiser et rendre des vidéos Remotion.

- Catégorie : Agent Skills, MCP et outils de montage ; Candidat principal.
- Périmètre d'application : Nécessite Remotion et un hôte prenant en charge les Agent Skills ; aucune licence trouvée à la racine de ce dépôt ; Remotion lui-même a ses propres conditions.
- État de maintenance : Commits sur les 90 derniers jours ; 9 commits sur 30 jours, 31 commits sur 90 jours.
- Licence : [Licence à vérifier](https://github.com/remotion-dev/skills/tree/6f55706d1069e512430582ad86e4e57dc07afe1b) ; Licence à vérifier. Aucun LICENSE trouvé à la racine ni dans l'arborescence du dépôt ; les licences du produit Remotion et de chaque paquet sont à vérifier séparément.
- Vérification fonctionnelle : 2026-11-20 ; [Source1](https://github.com/remotion-dev/skills/blob/6f55706d1069e512430582ad86e4e57dc07afe1b/README.md#L5).

## [pixelfx](https://github.com/patch-gg/pixelfx)

Bibliothèque de 244 effets pixel et animations dessinés par code, avec un skill Claude Code de génération d'effets et des outils de spritesheet et d'export GIF/MP4.

- Catégorie : Agent Skills, MCP et outils de montage ; Candidat principal.
- Périmètre d'application : Bibliothèque d'effets et d'assets de mouvements, sans script, montage ni publication ; la police Patch Pixel de `gallery/fonts` est sous copyright Patch, hors MIT ; une partie du code est adaptée de Sprite Fusion et Hollow Crown (tous deux MIT), la paternité est à conserver selon NOTICE ; utiliser les assets exportés dans une vidéo suppose de vérifier les contenus tiers affichés.
- État de maintenance : Commits sur les 90 derniers jours ; 10 commits sur 30 jours, 10 commits sur 90 jours.
- Licence : [MIT (code et effets) + police Patch Pixel exclue](https://github.com/patch-gg/pixelfx/blob/5294518ce7c72e48b6100a744596e0acf57f2826/NOTICE.md) ; Licence composite/conditionnelle. Le README déclare code et effets sous MIT, usage commercial autorisé ; NOTICE liste les effets Sprite Fusion adaptés de Hugo Duprez et Hollow Crown (tous deux MIT), dont la paternité est à conserver ; `gallery/fonts/PatchPixel-Regular.woff2` reste tous droits réservés par Patch, hors MIT
- Vérification fonctionnelle : 2026-11-24 ; [Source1](https://github.com/patch-gg/pixelfx/blob/5294518ce7c72e48b6100a744596e0acf57f2826/README.md#L7) · [Source2](https://github.com/patch-gg/pixelfx/blob/5294518ce7c72e48b6100a744596e0acf57f2826/README.md#L89) · [Source3](https://github.com/patch-gg/pixelfx/blob/5294518ce7c72e48b6100a744596e0acf57f2826/README.md#L156).

## [Wallstreet Explainer](https://github.com/HeyChengC/wallstreet-explainer)

Skill de coding agent pour capsules financières/tech en style Wall Street : langage visuel de style, templates de composants graphiques, scripts de recherche d'extraits, de captures d'écran, de doublage, de détourage, de rendu et de mixage.

- Catégorie : Agent Skills, MCP et outils de montage ; Candidat principal.
- Périmètre d'application : Nécessite un hôte comme Claude Code, plus ffmpeg installé, des dépendances Python/Node, Playwright et le téléchargement de cinq polices ; les médias proviennent de téléchargements yt-dlp et de captures de pages d'actualité citées en commentaire — la provenance et les droits de redistribution restent à vérifier ; les images tiers, captures, logos et personnes de l'échantillon ne sont pas sous MIT.
- État de maintenance : Commits sur les 90 derniers jours ; 10 commits sur 30 jours, 16 commits sur 90 jours.
- Licence : [MIT (code et documentation) + médias tiers des échantillons exclus](https://github.com/HeyChengC/wallstreet-explainer/blob/b79bc0573455cb5fe335e78f653012e658fa9758/LICENSE) ; Licence composite/conditionnelle. LICENSE = texte MIT avec clauses additionnelles excluant explicitement les images de vidéos, captures de presse, logos et photos de examples/ ; GitHub l'identifie donc comme NOASSERTION. Les polices se téléchargent séparément et suivent leurs propres licences
- Vérification fonctionnelle : 2026-11-23 ; [Source1](https://github.com/HeyChengC/wallstreet-explainer/blob/b79bc0573455cb5fe335e78f653012e658fa9758/README.md#L3) · [Source2](https://github.com/HeyChengC/wallstreet-explainer/blob/b79bc0573455cb5fe335e78f653012e658fa9758/README.md#L37) · [Source3](https://github.com/HeyChengC/wallstreet-explainer/blob/b79bc0573455cb5fe335e78f653012e658fa9758/README.md#L92).

## [ReelBench Skills](https://github.com/eternityspring/reelbench-skills)

Ensemble de skills d'analyse, de duplication et de production vidéo pour Claude Code/Codex.

- Catégorie : Agent Skills, MCP et outils de montage ; Candidat principal.
- Périmètre d'application : Certains produits liés et services de médias sont payants ou externes ; vérifier skill par skill.
- État de maintenance : Commits sur les 90 derniers jours ; 1 commits sur 30 jours, 21 commits sur 90 jours.
- Licence : [Apache-2.0](https://api.github.com/repos/eternityspring/reelbench-skills/license) ; Licence ouverte vérifiée. Identifiée via GitHub licenseInfo ; les poids de modèles, médias, polices, dépendances tierces et services managés relèvent de leurs propres licences
- Vérification fonctionnelle : 2026-11-12 ; [Source1](https://github.com/eternityspring/reelbench-skills/blob/8d8444894524c9beedbf8815dab517afb3ce3cbe/README.md#L5).

## [Video Agent Skills](https://github.com/Melvynx/video-agent-skills)

Organisation par skills Markdown du script, de la recherche, du montage, de la traduction et de la publication pour shorts/YouTube.

- Catégorie : Agent Skills, MCP et outils de montage ; Candidat principal.
- Périmètre d'application : Les skills n'embarquent ni tous les modèles ni les moteurs de rendu ; il faut un hôte et des outils locaux.
- État de maintenance : Commits sur les 90 derniers jours ; 1 commits sur 30 jours, 26 commits sur 90 jours.
- Licence : [MIT](https://api.github.com/repos/Melvynx/video-agent-skills/license) ; Licence ouverte vérifiée. Identifiée via GitHub licenseInfo ; les poids de modèles, médias, polices, dépendances tierces et services managés relèvent de leurs propres licences
- Vérification fonctionnelle : 2026-11-12 ; [Source1](https://github.com/Melvynx/video-agent-skills/blob/f4542923f7f796a1fa0e544cbfc1109d5eec87d8/README.md#L3).

## [Awesome Motion Design Agent Skills](https://github.com/frankxai/awesome-motion-design-agent-skills)

Cinq workflows de motion livrés en SKILL.md (dont remotion-video-agent et web-motion-auditor) et un index choisi d'outils GSAP, Motion, Remotion, Rive, Lottie et 3D.

- Catégorie : Agent Skills, MCP et outils de montage ; Candidat principal.
- Périmètre d'application : Les entrées de l'index pointent vers des dépôts tiers dont il faut vérifier séparément la licence et la disponibilité ; les skills n'apportent que méthode, listes de contrôle et aiguillage, donc la qualité du mouvement et de la vidéo dépend de l'agent hôte et des bibliothèques choisies ; le README conseille de scanner d'abord les packs tiers avec SkillSpector.
- État de maintenance : Commits sur les 90 derniers jours ; 9 commits sur 30 jours, 19 commits sur 90 jours.
- Licence : [CC0-1.0](https://github.com/frankxai/awesome-motion-design-agent-skills/blob/e7dc6e2e728c918ffcea5edb2d7c94e2a6f7785d/LICENSE) ; Licence ouverte vérifiée. La LICENSE racine est CC0 1.0 Universal ; les projets, polices et médias tiers visés par l'index et les skills restent sous leurs propres licences.
- Vérification fonctionnelle : 2026-11-26 ; [Source1](https://github.com/frankxai/awesome-motion-design-agent-skills/blob/e7dc6e2e728c918ffcea5edb2d7c94e2a6f7785d/README.md#L15) · [Source2](https://github.com/frankxai/awesome-motion-design-agent-skills/blob/e7dc6e2e728c918ffcea5edb2d7c94e2a6f7785d/README.md#L51) · [Source3](https://github.com/frankxai/awesome-motion-design-agent-skills/blob/e7dc6e2e728c918ffcea5edb2d7c94e2a6f7785d/README.md#L57).

## [HyperFrames Motion Library](https://github.com/nutllwhy/hyperframes-motion-library)

Bibliothèque locale de templates de motion design et d'assets paramétriques reposant sur HyperFrames.

- Catégorie : Agent Skills, MCP et outils de montage ; Candidat principal.
- Périmètre d'application : Bibliothèque d'assets animés, sans script complet, génération de médias ni flux de publication.
- État de maintenance : Commits sur les 90 derniers jours ; 2 commits sur 30 jours, 2 commits sur 90 jours.
- Licence : [MIT](https://api.github.com/repos/nutllwhy/hyperframes-motion-library/license) ; Licence ouverte vérifiée. Identifiée via GitHub licenseInfo ; les poids de modèles, médias, polices, dépendances tierces et services managés relèvent de leurs propres licences
- Vérification fonctionnelle : 2026-11-12 ; [Source1](https://github.com/nutllwhy/hyperframes-motion-library/blob/98c40ca18f23d7dc021a5d84308ab10599482cff/README.md#L3).

## [Video Editing Skill](https://github.com/social-media-skills/video-editing-skill)

Fait effectuer par l'agent la première passe de montage et le traitement des sous-titres sur des explications face caméra, des cours, des interviews et des vlogs.

- Catégorie : Agent Skills, MCP et outils de montage ; Candidat principal.
- Périmètre d'application : Ciblé sur la première passe de dégrossissage ; ne remplace pas la revue finale humaine, l'étalonnage ni l'habillage complexe.
- État de maintenance : Commits sur les 90 derniers jours ; 3 commits sur 30 jours, 3 commits sur 90 jours.
- Licence : [MIT](https://api.github.com/repos/social-media-skills/video-editing-skill/license) ; Licence ouverte vérifiée. Identifiée via GitHub licenseInfo ; les poids de modèles, médias, polices, dépendances tierces et services managés relèvent de leurs propres licences
- Vérification fonctionnelle : 2026-11-12 ; [Source1](https://github.com/social-media-skills/video-editing-skill/blob/f94d0517d717de281ee23569094aac616d32f4ef/README.md#L1).

## [GSAP Skills](https://github.com/greensock/gsap-skills)

Agent Skills officiels guidant les coding agents sur les timelines, l'animation et les plugins GSAP.

- Catégorie : Agent Skills, MCP et outils de montage ; Candidat principal.
- Périmètre d'application : Skill d'animation web nécessitant un agent hôte ; le rendu effectif en vidéo se fait avec des outils vidéo ; la licence des produits GSAP est à vérifier à part.
- État de maintenance : Aucun commit depuis 91–365 jours ; 0 commits sur 30 jours, 0 commits sur 90 jours.
- Licence : [MIT](https://github.com/greensock/gsap-skills/blob/aed9cfd3277740755f6bfc1155c7aa645403b760/LICENSE) ; Licence ouverte vérifiée. LICENSE racine du dépôt de skills sous MIT ; la bibliothèque GSAP et les médias tiers suivent leurs propres conditions.
- Vérification fonctionnelle : 2026-11-21 ; [Source1](https://github.com/greensock/gsap-skills/blob/aed9cfd3277740755f6bfc1155c7aa645403b760/README.md#L23).

## [Narrator AI CLI Skill](https://github.com/NarratorAI-Studio/narrator-ai-cli-skill)

Guide l'agent pour piloter narrator-ai-cli et produire automatiquement des vidéos de commentaire de films et séries.

- Catégorie : Agent Skills, MCP et outils de montage ; Candidat principal.
- Périmètre d'application : Skill machine-readable d'un CLI, pas un moteur de rendu autonome ; les services backend et les templates sont à part.
- État de maintenance : Aucun commit depuis 91–365 jours ; 0 commits sur 30 jours, 0 commits sur 90 jours.
- Licence : [MIT](https://api.github.com/repos/NarratorAI-Studio/narrator-ai-cli-skill/license) ; Licence ouverte vérifiée. Identifiée via GitHub licenseInfo ; les poids de modèles, médias, polices, dépendances tierces et services managés relèvent de leurs propres licences
- Vérification fonctionnelle : 2026-11-12 ; [Source1](https://github.com/NarratorAI-Studio/narrator-ai-cli-skill/blob/4b17c6f2175bd532c92db778a847f8fb6bdd3177/README.md#L9).

## [OpenClip Agent Skills](https://github.com/OpenClip-App/agent-skills)

Skills agent pour le découpage de longues vidéos, la transcription, la conversion, les miniatures, le détourage et les idées UGC.

- Catégorie : Agent Skills, MCP et outils de montage ; Candidat principal.
- Périmètre d'application : Les skills pilotent un MCP OpenClip managé ; les vidéos et les identifiants transitent par un service externe.
- État de maintenance : Aucun commit depuis 91–365 jours ; 0 commits sur 30 jours, 0 commits sur 90 jours.
- Licence : [MIT](https://api.github.com/repos/OpenClip-App/agent-skills/license) ; Licence ouverte vérifiée. Identifiée via GitHub licenseInfo ; les poids de modèles, médias, polices, dépendances tierces et services managés relèvent de leurs propres licences
- Vérification fonctionnelle : 2026-11-12 ; [Source1](https://github.com/OpenClip-App/agent-skills/blob/ea02c98db69c437616df1db4a4400cde1f4a0832/README.md#L1).

## [MCP Video Editing](https://github.com/mfortne/mcp-video-editing)

Encapsulation MCP, bibliothèque Python et CLI de FFmpeg, HyperFrames et flux réutilisables en local.

- Catégorie : Agent Skills, MCP et outils de montage ; Candidat principal.
- Périmètre d'application : Le rendu effectif dépend des versions des outils externes ; apparenté à Kinocut mais dépôt distinct.
- État de maintenance : Aucun commit depuis 91–365 jours ; 0 commits sur 30 jours, 0 commits sur 90 jours.
- Licence : [Apache-2.0](https://api.github.com/repos/mfortne/mcp-video-editing/license) ; Licence ouverte vérifiée. Identifiée via GitHub licenseInfo ; les poids de modèles, médias, polices, dépendances tierces et services managés relèvent de leurs propres licences
- Vérification fonctionnelle : 2026-11-12 ; [Source1](https://github.com/mfortne/mcp-video-editing/blob/97ecab83d26c24bfe77be663784399b203b1fa55/README.md#L3).

## [HyperFrames](https://github.com/heygen-com/hyperframes)

Écosystème de code-video HTML/CSS/JS et d'Agent Skills, avec migration possible depuis Remotion et validation image par image.

- Catégorie : Code-to-video et motion design ; Candidat principal.
- Périmètre d'application : Le projet et le service de génération managé HeyGen relèvent de niveaux différents ; les templates précis et les médias externes sont à licencier à part.
- État de maintenance : Commits sur les 90 derniers jours ; 1867 commits sur 30 jours, 4119 commits sur 90 jours.
- Licence : [Apache-2.0](https://api.github.com/repos/heygen-com/hyperframes/license) ; Licence ouverte vérifiée. Identifiée via GitHub licenseInfo ; les poids de modèles, médias, polices, dépendances tierces et services managés relèvent de leurs propres licences
- Vérification fonctionnelle : 2026-11-12 ; [Source1](https://github.com/heygen-com/hyperframes/blob/234fb1aeef13f8d86b4f7f4cb1af624db3a81ec2/README.md#L5).

## [Remotion](https://github.com/remotion-dev/remotion)

Framework de base pour créer et rendre des vidéos par code en React/TypeScript.

- Catégorie : Code-to-video et motion design ; Licence restreinte.
- Périmètre d'application : Infrastructure de code-video généraliste, sans planification agentique ni modèles de génération embarqués.
- État de maintenance : Commits sur les 90 derniers jours ; 2582 commits sur 30 jours, 6798 commits sur 90 jours.
- Licence : [Remotion License](https://github.com/remotion-dev/remotion/blob/51fd2b4a06a2b2ff0d4eb058dfe4db2b7275bac3/LICENSE.md) ; Code source visible mais non open source OSI. Gratuit pour particuliers, organisations à but non lucratif et petites structures ; les organisations commerciales au-delà des seuils supposent une licence d'entreprise — ce n'est pas de l'open source OSI courant
- Vérification fonctionnelle : 2026-11-12 ; [Source1](https://github.com/remotion-dev/remotion/blob/51fd2b4a06a2b2ff0d4eb058dfe4db2b7275bac3/README.md#L2).

## [raea](https://github.com/shinyobjectz/raea)

Moteur et atelier agent desktop pour écrire vidéos, animations, 3D et jeux en React/TypeScript, rendus sur un GPU local.

- Catégorie : Code-to-video et motion design ; Candidat principal.
- Périmètre d'application : Le moteur, le CLI et l'application desktop sont utilisables gratuitement ; le stockage cloud, la recherche multi-machines et la publication relèvent des offres Pro/Team ; la FSL-1.1-ALv2 interdit les produits concurrents, chaque version passant sous Apache-2.0 deux ans après sa publication ; les sources d'exemple, les modèles, les runtime binaires, les composants tiers et les médias des comptes suivent des licences distinctes.
- État de maintenance : Commits sur les 90 derniers jours ; 1607 commits sur 30 jours, 1610 commits sur 90 jours.
- Licence : [FSL-1.1-ALv2](https://github.com/shinyobjectz/raea/blob/0c9fc255f2287f0530fc773b895cb5d1877a6f54/LICENSE) ; Code source visible mais non open source OSI. LICENSE racine du dépôt sous Functional Source License 1.1 (ALv2 Future License) : interdit d'utiliser le logiciel pour un produit ou service commercial concurrent de raea ou de ses produits existants ; chaque version passe sous Apache-2.0 deux ans après sa publication ; NOTICE et LICENSES listent en plus les licences tierces des ports HyperFrames, de Bevy, FFmpeg, QuickJS, etc.
- Vérification fonctionnelle : 2026-11-22 ; [Source1](https://github.com/shinyobjectz/raea/blob/0c9fc255f2287f0530fc773b895cb5d1877a6f54/README.md#L13) · [Source2](https://github.com/shinyobjectz/raea/blob/0c9fc255f2287f0530fc773b895cb5d1877a6f54/README.md#L42) · [Source3](https://github.com/shinyobjectz/raea/blob/0c9fc255f2287f0530fc773b895cb5d1877a6f54/README.md#L111).

## [Lemo Opuscar](https://github.com/lemomo-ai/lemo-opuscar)

Fournit des styles cinéma, des exemples et des consignes STYLE.md pour que les coding agents fassent des vidéos par code.

- Catégorie : Code-to-video et motion design ; Licence restreinte.
- Périmètre d'application : Le projet recommande Claude avec un effort de raisonnement rehaussé ; réutiliser les médias, personnes, marques et voix des démos demande des vérifications séparées.
- État de maintenance : Commits sur les 90 derniers jours ; 94 commits sur 30 jours, 151 commits sur 90 jours.
- Licence : [Code MIT + documentation CC BY-NC (licence additive)](https://github.com/lemomo-ai/lemo-opuscar/blob/f9e204293930952b61ba921cd8944d05f121beee/LICENSE) ; Licence composite/conditionnelle. Code sous MIT ; la documentation Markdown sous CC BY-NC 4.0, avec permission supplémentaire de lire, modifier et livrer avec les fichiers du projet pour des vidéos personnelles ou de clients ; tout autre usage commercial suppose une licence. Les médias d'exemple et certains doublages ont des restrictions propres.
- Vérification fonctionnelle : 2026-11-21 ; [Source1](https://github.com/lemomo-ai/lemo-opuscar/blob/f9e204293930952b61ba921cd8944d05f121beee/README.md#L7).

## [Manim Community](https://github.com/ManimCommunity/manim)

Moteur vidéo d'animation mathématique et de vulgarisation programmée en Python.

- Catégorie : Code-to-video et motion design ; Candidat principal.
- Périmètre d'application : Adapté à la vulgarisation par code ; ce n'est pas un agent IA génératif ; dépendances de rendu et polices à vérifier à part.
- État de maintenance : Commits sur les 90 derniers jours ; 29 commits sur 30 jours, 80 commits sur 90 jours.
- Licence : [MIT](https://github.com/ManimCommunity/manim/blob/ab7f9527fa2b37893aacc367e21b723845f44ef0/LICENSE) ; Licence ouverte vérifiée. Fichier de licence du projet vérifié ; composants tiers, médias et services managés à part.
- Vérification fonctionnelle : 2026-11-20 ; [Source1](https://github.com/ManimCommunity/manim/blob/ab7f9527fa2b37893aacc367e21b723845f44ef0/README.md#L20).

## [GiveMotion](https://github.com/givemotion/givemotion)

Moteur de code-video où l'agent écrit HTML/CSS, prévisualise, contrôle puis rend un MP4.

- Catégorie : Code-to-video et motion design ; Candidat principal.
- Périmètre d'application : L'animation par code convient au motion design et à l'explication ; elle ne vaut pas montage de rushes réels ni génération par diffusion.
- État de maintenance : Commits sur les 90 derniers jours ; 64 commits sur 30 jours, 243 commits sur 90 jours.
- Licence : [MIT](https://api.github.com/repos/givemotion/givemotion/license) ; Licence ouverte vérifiée. Identifiée via GitHub licenseInfo ; les poids de modèles, médias, polices, dépendances tierces et services managés relèvent de leurs propres licences
- Vérification fonctionnelle : 2026-11-12 ; [Source1](https://github.com/givemotion/givemotion/blob/8a7949e685bbfaec8bde20fad9aa8734cdfa6038/README.md#L6).

## [SenseNova Code2Video](https://github.com/OpenSenseNova/SenseNova-6.8-Code2Video)

Génère du code exécutable avec un petit modèle ouvert pour rendre de courtes vidéos.

- Catégorie : Code-to-video et motion design ; Candidat principal.
- Périmètre d'application : Axé pour l'instant sur la vidéo courte en code pur ; les poids du modèle, l'environnement d'inférence et les outils de génération sont à vérifier séparément.
- État de maintenance : Commits sur les 90 derniers jours ; 1 commits sur 30 jours, 3 commits sur 90 jours.
- Licence : [À vérifier](https://github.com/OpenSenseNova/SenseNova-6.8-Code2Video/blob/776ae79824e338ba5d63fef66167455edc94ad26/README.md) ; Licence à vérifier. Aucune licence racine trouvée ; les conditions sur les poids du modèle et la réutilisation du code restent à confirmer
- Vérification fonctionnelle : 2026-11-12 ; [Source1](https://github.com/OpenSenseNova/SenseNova-6.8-Code2Video/blob/776ae79824e338ba5d63fef66167455edc94ad26/README.md#L3).

## [Manim](https://github.com/3b1b/manim)

Moteur d'animation Python pour la vulgarisation mathématique.

- Catégorie : Code-to-video et motion design ; Infrastructure adjacente.
- Périmètre d'application : Outil d'animation généraliste et dépôt correspondant à la version de 3Blue1Brown ; pas un agent vidéo IA complet.
- État de maintenance : Commits sur les 90 derniers jours ; 0 commits sur 30 jours, 1 commits sur 90 jours.
- Licence : [MIT](https://api.github.com/repos/3b1b/manim/license) ; Licence ouverte vérifiée. Identifiée via GitHub licenseInfo ; les poids de modèles, médias, polices, dépendances tierces et services managés relèvent de leurs propres licences
- Vérification fonctionnelle : 2026-11-12 ; [Source1](https://github.com/3b1b/manim/blob/fafa083a4fb274bba9cabde0b6e2f50ba6da0622/README.md#L2).

## [Motion Canvas](https://github.com/motion-canvas/motion-canvas)

Crée des animations, des explications et du motion design en TypeScript via des fonctions génératrices.

- Catégorie : Code-to-video et motion design ; Infrastructure adjacente.
- Périmètre d'application : Framework d'animation généraliste ; les capacités agent viennent de skills ou d'un hôte de niveau supérieur.
- État de maintenance : Aucun commit depuis 91–365 jours ; 0 commits sur 30 jours, 0 commits sur 90 jours.
- Licence : [MIT](https://api.github.com/repos/motion-canvas/motion-canvas/license) ; Licence ouverte vérifiée. Identifiée via GitHub licenseInfo ; les poids de modèles, médias, polices, dépendances tierces et services managés relèvent de leurs propres licences
- Vérification fonctionnelle : 2026-11-12 ; [Source1](https://github.com/motion-canvas/motion-canvas/blob/7b91435c301d530351dcf5ebb91dd139c002e405/README.md#L6).

## [Godot](https://github.com/godotengine/godot)

Moteur de jeu open source pour construire des scènes 2D et 3D, des interactions et des animations.

- Catégorie : Animation, 3D et briques de base du codage ; Infrastructure adjacente.
- Périmètre d'application : Un moteur de jeu n'est pas un système de génération vidéo automatique ; l'enregistrement ou l'export d'un montage supposent un flux dédié.
- État de maintenance : Commits sur les 90 derniers jours ; 524 commits sur 30 jours, 1884 commits sur 90 jours.
- Licence : [MIT](https://github.com/godotengine/godot/blob/73ca6be2cebd5192d8b279979d04f29ea45c266e/LICENSE.txt) ; Licence ouverte vérifiée. Fichier de licence du projet vérifié ; composants tiers, médias et services managés à part.
- Vérification fonctionnelle : 2026-11-20 ; [Source1](https://github.com/godotengine/godot/blob/73ca6be2cebd5192d8b279979d04f29ea45c266e/README.md#L11).

## [three.js](https://github.com/mrdoob/three.js)

Bibliothèque JavaScript de scènes et de rendu 3D, pour alimenter des animations par code en contenu 3D.

- Catégorie : Animation, 3D et briques de base du codage ; Infrastructure adjacente.
- Périmètre d'application : Bibliothèque de rendu généraliste ; ne sort pas de vidéo automatiquement ; les médias et les environnements WebGL/WebGPU sont à gérer soi-même.
- État de maintenance : Commits sur les 90 derniers jours ; 316 commits sur 30 jours, 886 commits sur 90 jours.
- Licence : [MIT](https://github.com/mrdoob/three.js/blob/8b92052852735b67cfa8393f78e707b3f07a0eec/LICENSE) ; Licence ouverte vérifiée. Fichier de licence du projet vérifié ; composants tiers, médias et services managés à part.
- Vérification fonctionnelle : 2026-11-20 ; [Source1](https://github.com/mrdoob/three.js/blob/8b92052852735b67cfa8393f78e707b3f07a0eec/README.md#L11).

## [Motion](https://github.com/motiondivision/motion)

Bibliothèque d'animation d'interfaces et de mises en page pour JavaScript, React et Vue.

- Catégorie : Animation, 3D et briques de base du codage ; Infrastructure adjacente.
- Périmètre d'application : Composant de motion design généraliste ; se combine avec un moteur de rendu vidéo, ne fournit pas d'agent vidéo en soi.
- État de maintenance : Commits sur les 90 derniers jours ; 461 commits sur 30 jours, 1399 commits sur 90 jours.
- Licence : [MIT](https://github.com/motiondivision/motion/blob/cd009de7a4314e065d4d9df683057124792d5b34/LICENSE.md) ; Licence ouverte vérifiée. Fichier de licence du projet vérifié ; composants tiers, médias et services managés à part.
- Vérification fonctionnelle : 2026-11-20 ; [Source1](https://github.com/motiondivision/motion/blob/cd009de7a4314e065d4d9df683057124792d5b34/README.md#L3).

## [Blender](https://github.com/blender/blender)

Suite de création 3D couvrant modélisation, rigging, animation, rendu, compositing et montage vidéo.

- Catégorie : Animation, 3D et briques de base du codage ; Infrastructure adjacente.
- Périmètre d'application : Le dépôt GitHub est un miroir officiel ; les add-ons tiers, les modèles et les médias suivent leurs propres licences.
- État de maintenance : Commits sur les 90 derniers jours ; 1180 commits sur 30 jours, 3333 commits sur 90 jours.
- Licence : [GPL-2.0-or-later](https://github.com/blender/blender/blob/611d97903ad34434934f4cb1e586155c03eddd66/COPYING) ; Licence ouverte vérifiée. COPYING renvoie au texte de licence GPL ; les assets et composants tiers sont à part.
- Vérification fonctionnelle : 2026-11-20 ; [Source1](https://github.com/blender/blender/blob/611d97903ad34434934f4cb1e586155c03eddd66/.github/README.md#L14).

## [Babylon.js](https://github.com/BabylonJS/Babylon.js)

Moteur JavaScript de scènes 3D, de jeux et de rendu, base possible pour le motion design par code.

- Catégorie : Animation, 3D et briques de base du codage ; Infrastructure adjacente.
- Périmètre d'application : Moteur de rendu 3D temps réel par défaut ; l'encodage vidéo suppose des outils raccordés ; le README précise que le CDN de démo n'est pas destiné à la production.
- État de maintenance : Commits sur les 90 derniers jours ; 156 commits sur 30 jours, 342 commits sur 90 jours.
- Licence : [Apache-2.0](https://github.com/BabylonJS/Babylon.js/blob/6226e393cef4295d8509b8a83e82572b2af4c9c9/license.md) ; Licence ouverte vérifiée. Fichier de licence du projet vérifié ; composants tiers, médias et services managés à part.
- Vérification fonctionnelle : 2026-11-20 ; [Source1](https://github.com/BabylonJS/Babylon.js/blob/6226e393cef4295d8509b8a83e82572b2af4c9c9/readme.md#L1).

## [Konva](https://github.com/konvajs/konva)

Bibliothèque de scène Canvas 2D avec interaction d'objets, transformations, animations et export.

- Catégorie : Animation, 3D et briques de base du codage ; Infrastructure adjacente.
- Périmètre d'application : Composant canvas généraliste ; l'export vidéo ou audio demande d'autres outils.
- État de maintenance : Commits sur les 90 derniers jours ; 32 commits sur 30 jours, 219 commits sur 90 jours.
- Licence : [MIT](https://github.com/konvajs/konva/blob/bf1927c1cfec7f47eb608a470aff6ca99dd09aa9/LICENSE) ; Licence ouverte vérifiée. Fichier de licence du projet vérifié ; composants tiers, médias et services managés à part.
- Vérification fonctionnelle : 2026-11-20 ; [Source1](https://github.com/konvajs/konva/blob/bf1927c1cfec7f47eb608a470aff6ca99dd09aa9/README.md#L16).

## [Two.js](https://github.com/jonobr1/two.js)

Crée des figures 2D et des scènes animées via WebGL, Canvas ou SVG.

- Catégorie : Animation, 3D et briques de base du codage ; Infrastructure adjacente.
- Périmètre d'application : Bibliothèque fondamentale de dessin 2D ; produire des fichiers audio/vidéo suppose d'y raccorder rendu et encodage.
- État de maintenance : Commits sur les 90 derniers jours ; 15 commits sur 30 jours, 47 commits sur 90 jours.
- Licence : [MIT](https://github.com/jonobr1/two.js/blob/bd48e27ff8f3333ef442fb3d032cb6b5391f26dc/LICENSE) ; Licence ouverte vérifiée. Fichier de licence du projet vérifié ; composants tiers, médias et services managés à part.
- Vérification fonctionnelle : 2026-11-20 ; [Source1](https://github.com/jonobr1/two.js/blob/bd48e27ff8f3333ef442fb3d032cb6b5391f26dc/README.md#L8).

## [Shifty](https://github.com/jeremyckahn/shifty)

Moteur d'animation de tweening en TypeScript avec easings et contrôles de lecture.

- Catégorie : Animation, 3D et briques de base du codage ; Infrastructure adjacente.
- Périmètre d'application : Bibliothèque de tweening bas niveau ; aucun flux de génération ni d'export vidéo embarqué.
- État de maintenance : Commits sur les 90 derniers jours ; 8 commits sur 30 jours, 14 commits sur 90 jours.
- Licence : [MIT](https://github.com/jeremyckahn/shifty/blob/ee4c8ed53503d5a6bf658ccdbba5af58674e3245/LICENSE-MIT) ; Licence ouverte vérifiée. Fichier de licence du projet vérifié ; composants tiers, médias et services managés à part.
- Vérification fonctionnelle : 2026-11-20 ; [Source1](https://github.com/jeremyckahn/shifty/blob/ee4c8ed53503d5a6bf658ccdbba5af58674e3245/README.md#L7).

## [Ola](https://github.com/franciscop/ola)

Bibliothèque légère d'interpolation temporelle en temps réel de valeurs numériques.

- Catégorie : Animation, 3D et briques de base du codage ; Infrastructure adjacente.
- Périmètre d'application : Ne traite que l'interpolation de valeurs ; scènes, timeline et export restent à votre charge.
- État de maintenance : Commits sur les 90 derniers jours ; 0 commits sur 30 jours, 3 commits sur 90 jours.
- Licence : [MIT](https://github.com/franciscop/ola/blob/b269059c570405421acfcc55c84b3347cbeb0674/LICENSE) ; Licence ouverte vérifiée. Fichier de licence du projet vérifié ; composants tiers, médias et services managés à part.
- Vérification fonctionnelle : 2026-11-20 ; [Source1](https://github.com/franciscop/ola/blob/b269059c570405421acfcc55c84b3347cbeb0674/readme.md#L3).

## [Anime.js](https://github.com/juliangarnier/anime)

Animations en timeline sur des propriétés CSS, SVG, DOM et JavaScript.

- Catégorie : Animation, 3D et briques de base du codage ; Infrastructure adjacente.
- Périmètre d'application : Moteur d'animation web généraliste ; le rendu vidéo et la synchronisation audio demandent des outils supplémentaires.
- État de maintenance : Aucun commit depuis 91–365 jours ; 0 commits sur 30 jours, 0 commits sur 90 jours.
- Licence : [MIT](https://github.com/juliangarnier/anime/blob/01b81be1df6843ccfe0a71c0699a746bf740dd77/LICENSE.md) ; Licence ouverte vérifiée. Fichier de licence du projet vérifié ; composants tiers, médias et services managés à part.
- Vérification fonctionnelle : 2026-11-20 ; [Source1](https://github.com/juliangarnier/anime/blob/01b81be1df6843ccfe0a71c0699a746bf740dd77/README.md#L13).

## [Proton](https://github.com/drawcall/Proton)

Bibliothèque JavaScript d'animation de particules pour des effets de flammes, feux d'artifice et explosions.

- Catégorie : Animation, 3D et briques de base du codage ; Infrastructure adjacente.
- Périmètre d'application : Bibliothèque d'effets fondamentale, pas un outil autonome de rendu ou de montage vidéo.
- État de maintenance : Aucun commit depuis 91–365 jours ; 0 commits sur 30 jours, 0 commits sur 90 jours.
- Licence : [MIT](https://github.com/drawcall/Proton/blob/b4fdef5e5416d70a788978bec0fb4a1be26514b4/LICENSE) ; Licence ouverte vérifiée. Fichier de licence du projet vérifié ; composants tiers, médias et services managés à part.
- Vérification fonctionnelle : 2026-11-20 ; [Source1](https://github.com/drawcall/Proton/blob/b4fdef5e5416d70a788978bec0fb4a1be26514b4/README.md#L26).

## [Lottie Web](https://github.com/airbnb/lottie-web)

Analyse et affiche dans le web des animations vectorielles Lottie exportées.

- Catégorie : Animation, 3D et briques de base du codage ; Infrastructure adjacente.
- Périmètre d'application : Un lecteur n'est pas un éditeur vidéo ; les licences des ressources d'animation et de leur mode de génération restent à part.
- État de maintenance : Aucun commit depuis plus de 365 jours ; 0 commits sur 30 jours, 0 commits sur 90 jours.
- Licence : [MIT](https://github.com/airbnb/lottie-web/blob/bede03d25d232826e0c9dca1733d542d8a7754fb/LICENSE.md) ; Licence ouverte vérifiée. Fichier de licence du projet vérifié ; composants tiers, médias et services managés à part.
- Vérification fonctionnelle : 2026-11-20 ; [Source1](https://github.com/airbnb/lottie-web/blob/bede03d25d232826e0c9dca1733d542d8a7754fb/README.md#L3).

## [TweenJS](https://github.com/CreateJS/TweenJS)

Tweening et lecture en chaîne pour des valeurs JavaScript et des propriétés CSS.

- Catégorie : Animation, 3D et briques de base du codage ; Infrastructure adjacente.
- Périmètre d'application : Bibliothèque de tweening à coupler avec un moteur de rendu et des outils d'export.
- État de maintenance : Aucun commit depuis plus de 365 jours ; 0 commits sur 30 jours, 0 commits sur 90 jours.
- Licence : [MIT](https://github.com/CreateJS/TweenJS/blob/6df2b9ce7e68d3d824cc490b67cab2bc3204810a/LICENSE.txt) ; Licence ouverte vérifiée. Fichier de licence du projet vérifié ; composants tiers, médias et services managés à part.
- Vérification fonctionnelle : 2026-11-20 ; [Source1](https://github.com/CreateJS/TweenJS/blob/6df2b9ce7e68d3d824cc490b67cab2bc3204810a/README.md#L3).

## [LUME](https://github.com/lume/lume)

Construit des scènes graphiques interactives 2D et 3D avec des éléments HTML.

- Catégorie : Animation, 3D et briques de base du codage ; Infrastructure adjacente.
- Périmètre d'application : Composant 3D/graphique généraliste ; ne fournit pas de chaîne de production vidéo complète.
- État de maintenance : Aucun commit depuis plus de 365 jours ; 0 commits sur 30 jours, 0 commits sur 90 jours.
- Licence : [MIT](https://github.com/lume/lume/blob/6336e365f1c02af6316017bcd6d7f79bd2efe13b/LICENSE) ; Licence ouverte vérifiée. Fichier de licence du projet vérifié ; composants tiers, médias et services managés à part.
- Vérification fonctionnelle : 2026-11-20 ; [Source1](https://github.com/lume/lume/blob/6336e365f1c02af6316017bcd6d7f79bd2efe13b/README.md#L23).

## [gifenc](https://github.com/mattdesl/gifenc)

Encode des GIFs animés avec transparence dans le navigateur ou sous Node.js.

- Catégorie : Animation, 3D et briques de base du codage ; Infrastructure adjacente.
- Périmètre d'application : Produit du GIF ; pas d'export MP4, de montage ni de génération IA directs.
- État de maintenance : Aucun commit depuis plus de 365 jours ; 0 commits sur 30 jours, 0 commits sur 90 jours.
- Licence : [MIT](https://github.com/mattdesl/gifenc/blob/27db5b982dba701ca440b55ea36fad3999040973/LICENSE.md) ; Licence ouverte vérifiée. Fichier de licence du projet vérifié ; composants tiers, médias et services managés à part.
- Vérification fonctionnelle : 2026-11-20 ; [Source1](https://github.com/mattdesl/gifenc/blob/27db5b982dba701ca440b55ea36fad3999040973/README.md#L5).

## [VRGameDevGirl AI Video Builder](https://github.com/vrgamegirl19/comfyui-vrgamedevgirl)

Gère dans ComfyUI, scène par scène, la planification, les prompts, la génération, le rythme, la revue et l'assemblage final.

- Catégorie : ComfyUI et génération vidéo open source ; Licence restreinte.
- Périmètre d'application : Certains nœuds personnalisés ont été extraits en paquets séparés ; les modèles, la VRAM et la compatibilité d'installation sont à valider workflow par workflow.
- État de maintenance : Commits sur les 90 derniers jours ; 117 commits sur 30 jours, 667 commits sur 90 jours.
- Licence : [VRGameDevGirl Community and Commercial License](https://github.com/vrgamegirl19/comfyui-vrgamedevgirl/blob/b419bb5c2468432704e0339035844620f1b3ec18/LICENSE) ; Code source visible mais non open source OSI. Les contenus générés sont commercialisables ; la vente, l'hébergement ou l'intégration commerciale du logiciel lui-même supposent une licence commerciale écrite
- Vérification fonctionnelle : 2026-11-12 ; [Source1](https://github.com/vrgamegirl19/comfyui-vrgamedevgirl/blob/b419bb5c2468432704e0339035844620f1b3ec18/README.md#L1).

## [LTX-Video](https://github.com/Lightricks/LTX-Video)

Modèles vidéo ouverts et outils d'inférence pour le texte et l'image vers la vidéo ainsi que la génération audio-visuelle.

- Catégorie : ComfyUI et génération vidéo open source ; Candidat principal.
- Périmètre d'application : Selon les versions LTX, le matériel, les poids et les capacités audio varient fortement.
- État de maintenance : Commits sur les 90 derniers jours ; 2 commits sur 30 jours, 2 commits sur 90 jours.
- Licence : [Apache-2.0](https://api.github.com/repos/Lightricks/LTX-Video/license) ; Licence ouverte vérifiée. Identifiée via GitHub licenseInfo ; les poids de modèles, médias, polices, dépendances tierces et services managés relèvent de leurs propres licences
- Vérification fonctionnelle : 2026-11-12 ; [Source1](https://github.com/Lightricks/LTX-Video/blob/50f0aef1297574a4b29acbdb874e3a363a6d5f2e/README.md#L4).

## [HunyuanVideo](https://github.com/Tencent-Hunyuan/HunyuanVideo)

Modèle de base de génération vidéo à grande échelle open source de Tencent, avec cadre d'inférence.

- Catégorie : ComfyUI et génération vidéo open source ; Licence restreinte.
- Périmètre d'application : Exigences matérielles élevées ; la licence du code et les politiques des poids et des sorties sont à vérifier séparément.
- État de maintenance : Commits sur les 90 derniers jours ; 0 commits sur 30 jours, 3 commits sur 90 jours.
- Licence : [Tencent Hunyuan Community License](https://github.com/Tencent-Hunyuan/HunyuanVideo/blob/4eda9cb44c3be82a6b9c4261897cb6bd3cfb084e/LICENSE.txt) ; Code source visible mais non open source OSI. Comporte des exclusions géographiques, une politique d'utilisation et des clauses dérivées sur les modèles ; ce n'est pas une licence OSI standard
- Vérification fonctionnelle : 2026-11-12 ; [Source1](https://github.com/Tencent-Hunyuan/HunyuanVideo/blob/4eda9cb44c3be82a6b9c4261897cb6bd3cfb084e/README.md#L1).

## [Wan2.2](https://github.com/Wan-Video/Wan2.2)

Modèles ouverts de génération vidéo de la série Wan d'Alibaba, couvrant le texte et l'image vers la vidéo.

- Catégorie : ComfyUI et génération vidéo open source ; Candidat principal.
- Périmètre d'application : Les tailles de modèle, les paramètres actifs et les conditions de licence varient selon le checkpoint précis.
- État de maintenance : Commits sur les 90 derniers jours ; 0 commits sur 30 jours, 2 commits sur 90 jours.
- Licence : [Apache-2.0](https://api.github.com/repos/Wan-Video/Wan2.2/license) ; Licence ouverte vérifiée. Identifiée via GitHub licenseInfo ; les poids de modèles, médias, polices, dépendances tierces et services managés relèvent de leurs propres licences
- Vérification fonctionnelle : 2026-11-12 ; [Source1](https://github.com/Wan-Video/Wan2.2/blob/1ea34ff48f87168174e12956e200b1d908b1c5ff/README.md#L1).

## [Mochi](https://github.com/genmoai/mochi)

Modèle de génération vidéo open source de Genmo avec code d'inférence.

- Catégorie : ComfyUI et génération vidéo open source ; Candidat principal.
- Périmètre d'application : Les poids, la VRAM, la durée et les limites de résolution sont à valider selon la version.
- État de maintenance : Commits sur les 90 derniers jours ; 0 commits sur 30 jours, 2 commits sur 90 jours.
- Licence : [Apache-2.0](https://api.github.com/repos/genmoai/mochi/license) ; Licence ouverte vérifiée. Identifiée via GitHub licenseInfo ; les poids de modèles, médias, polices, dépendances tierces et services managés relèvent de leurs propres licences
- Vérification fonctionnelle : 2026-11-12 ; [Source1](https://github.com/genmoai/mochi/blob/15c9bad662df1fa3e7b53136423695b286484c08/README.md#L1).

## [Open-Sora](https://github.com/hpcaitech/Open-Sora)

Cadre open source efficace d'entraînement et d'inférence pour la génération vidéo.

- Catégorie : ComfyUI et génération vidéo open source ; Candidat principal.
- Périmètre d'application : Un cadre de recherche et des checkpoints de modèle ne valent pas un outil desktop de montage fini.
- État de maintenance : Aucun commit depuis 91–365 jours ; 0 commits sur 30 jours, 0 commits sur 90 jours.
- Licence : [Apache-2.0](https://api.github.com/repos/hpcaitech/Open-Sora/license) ; Licence ouverte vérifiée. Identifiée via GitHub licenseInfo ; les poids de modèles, médias, polices, dépendances tierces et services managés relèvent de leurs propres licences
- Vérification fonctionnelle : 2026-11-12 ; [Source1](https://github.com/hpcaitech/Open-Sora/blob/7ad6a96a135feb81f755c84fb391818718f6beb2/README.md#L2).

## [Bernini](https://github.com/bytedance/Bernini)

Cadre de recherche en génération et édition vidéo associant un planificateur sémantique et un rendu DiT.

- Catégorie : ComfyUI et génération vidéo open source ; Recherche/benchmark.
- Périmètre d'application : Les benchmarks du papier ne se confondent pas avec un verdict de capacité déduit du score de maintenance d'un éditeur produit.
- État de maintenance : Aucun commit depuis 91–365 jours ; 0 commits sur 30 jours, 0 commits sur 90 jours.
- Licence : [Apache-2.0](https://api.github.com/repos/bytedance/Bernini/license) ; Licence ouverte vérifiée. Identifiée via GitHub licenseInfo ; les poids de modèles, médias, polices, dépendances tierces et services managés relèvent de leurs propres licences
- Vérification fonctionnelle : 2026-11-12 ; [Source1](https://github.com/bytedance/Bernini/blob/e6c2cf11843470b08491745947abcba9c3c6b079/README.md#L3).

## [HunyuanVideo-I2V](https://github.com/Tencent-Hunyuan/HunyuanVideo-I2V)

Cadre image-vers-vidéo personnalisable bâti sur HunyuanVideo.

- Catégorie : ComfyUI et génération vidéo open source ; Licence restreinte.
- Périmètre d'application : Distinct du projet T2V de base ; vérifier les références d'entrée et la licence des poids.
- État de maintenance : Aucun commit depuis 91–365 jours ; 0 commits sur 30 jours, 0 commits sur 90 jours.
- Licence : [Tencent Hunyuan Community License](https://github.com/Tencent-Hunyuan/HunyuanVideo-I2V/blob/c8bba70b9517f08d770a9a2a3d1e93cc6d5b7949/LICENSE.txt) ; Code source visible mais non open source OSI. Comporte des exclusions géographiques, une politique d'utilisation et des clauses dérivées sur les modèles ; ce n'est pas une licence OSI standard
- Vérification fonctionnelle : 2026-11-12 ; [Source1](https://github.com/Tencent-Hunyuan/HunyuanVideo-I2V/blob/c8bba70b9517f08d770a9a2a3d1e93cc6d5b7949/README.md#L9).

## [CogVideo / CogVideoX](https://github.com/zai-org/CogVideo)

Modèles open source texte/image-vers-vidéo et code d'inférence.

- Catégorie : ComfyUI et génération vidéo open source ; Candidat principal.
- Périmètre d'application : Un générateur de modèle n'est pas un atelier de montage ; les poids, la VRAM, la résolution et la licence du modèle restent à vérifier version par version.
- État de maintenance : Aucun commit depuis plus de 365 jours ; 0 commits sur 30 jours, 0 commits sur 90 jours.
- Licence : [Apache-2.0](https://api.github.com/repos/zai-org/CogVideo/license) ; Licence ouverte vérifiée. Identifiée via GitHub licenseInfo ; les poids de modèles, médias, polices, dépendances tierces et services managés relèvent de leurs propres licences
- Vérification fonctionnelle : 2026-11-12 ; [Source1](https://github.com/zai-org/CogVideo/blob/7a1af7154511e0ce4e4be8d62faa8c5e5a3532d2/README.md#L1).

## [LiveTalking](https://github.com/lipku/LiveTalking)

Système de streaming interactif en temps réel combinant plusieurs backends d'avatars numériques.

- Catégorie : Avatars numériques, animation de portrait et synchronisation labiale ; Candidat principal.
- Périmètre d'application : Les licences, le matériel, la latence et les rendus varient fortement selon le backend.
- État de maintenance : Commits sur les 90 derniers jours ; 6 commits sur 30 jours, 14 commits sur 90 jours.
- Licence : [Apache-2.0](https://api.github.com/repos/lipku/LiveTalking/license) ; Licence ouverte vérifiée. Identifiée via GitHub licenseInfo ; les poids de modèles, médias, polices, dépendances tierces et services managés relèvent de leurs propres licences
- Vérification fonctionnelle : 2026-11-12 ; [Source1](https://github.com/lipku/LiveTalking/blob/c7269433a2b6ecebcd9342445d2ecc882c98b0da/README.md#L250).

## [MuseTalk](https://github.com/TMElyralab/MuseTalk)

Modèle de présentateur virtuel piloté par l'audio pour une synchronisation labiale temps réel de haute qualité.

- Catégorie : Avatars numériques, animation de portrait et synchronisation labiale ; Candidat principal.
- Périmètre d'application : Le code, les poids du modèle, les portraits d'entrée et les limites d'usage commercial sont à vérifier séparément.
- État de maintenance : Commits sur les 90 derniers jours ; 1 commits sur 30 jours, 1 commits sur 90 jours.
- Licence : [MIT](https://github.com/TMElyralab/MuseTalk/blob/0a89dec45a0192b824e3cf4daf96c239440c5ed8/LICENSE) ; Licence ouverte vérifiée. LICENSE racine vérifiée manuellement ; les droits sur les modèles, les données et les médias de personnes sont à part
- Vérification fonctionnelle : 2026-11-12 ; [Source1](https://github.com/TMElyralab/MuseTalk/blob/0a89dec45a0192b824e3cf4daf96c239440c5ed8/README.md#L1).

## [LivePortrait](https://github.com/KlingAIResearch/LivePortrait)

Cadre efficace d'animation de portrait, d'assemblage et de contrôle par redirection.

- Catégorie : Avatars numériques, animation de portrait et synchronisation labiale ; Candidat principal.
- Périmètre d'application : Le dépôt a été transféré à KlingAIResearch ; les droits des médias conducteurs et des personnes incombent à l'utilisateur.
- État de maintenance : Aucun commit depuis 91–365 jours ; 0 commits sur 30 jours, 0 commits sur 90 jours.
- Licence : [MIT](https://github.com/KlingAIResearch/LivePortrait/blob/9b294b3d0536135442ea73cb01e6cb3ca7029dd3/LICENSE) ; Licence ouverte vérifiée. LICENSE racine vérifiée manuellement ; les droits sur les modèles, les données et les images de personnes sont à part
- Vérification fonctionnelle : 2026-11-12 ; [Source1](https://github.com/KlingAIResearch/LivePortrait/blob/9b294b3d0536135442ea73cb01e6cb3ca7029dd3/readme.md#L1).

## [SadTalker](https://github.com/OpenTalker/SadTalker)

Génère une vidéo de tête parlante à partir d'un seul portrait et d'un fichier audio.

- Catégorie : Avatars numériques, animation de portrait et synchronisation labiale ; Candidat principal.
- Périmètre d'application : Le portrait généré engage les droits de la personne ; suivre les indications du dépôt actuel pour le modèle et ses dépendances.
- État de maintenance : Aucun commit depuis plus de 365 jours ; 0 commits sur 30 jours, 0 commits sur 90 jours.
- Licence : [Apache-2.0](https://github.com/OpenTalker/SadTalker/blob/cd4c0465ae0b54a6f85af57f5c65fec9fe23e7f8/LICENSE) ; Licence ouverte vérifiée. LICENSE racine vérifiée manuellement ; les composants tiers sont à part
- Vérification fonctionnelle : 2026-11-12 ; [Source1](https://github.com/OpenTalker/SadTalker/blob/cd4c0465ae0b54a6f85af57f5c65fec9fe23e7f8/README.md#L6).

## [Wav2Lip](https://github.com/Rudrabha/Wav2Lip)

Implémentation de recherche classique de la synchronisation labiale audio-vidéo.

- Catégorie : Avatars numériques, animation de portrait et synchronisation labiale ; Licence restreinte.
- Périmètre d'application : Le code et les poids ouverts limitent l'usage surtout au personnel, à la recherche et au non commercial ; exclu des recommandations courantes d'open source commercial.
- État de maintenance : Aucun commit depuis plus de 365 jours ; 0 commits sur 30 jours, 0 commits sur 90 jours.
- Licence : [Licence personnelle/recherche/non commerciale](https://github.com/Rudrabha/Wav2Lip/blob/bac9a81e63ecc153202353372e5724b83d9e6322/README.md#L207) ; Code source visible mais non open source OSI. Le README interdit explicitement l'usage commercial du modèle open source
- Vérification fonctionnelle : 2026-11-12 ; [Source1](https://github.com/Rudrabha/Wav2Lip/blob/bac9a81e63ecc153202353372e5724b83d9e6322/README.md#L1).

## [FFmpeg](https://github.com/FFmpeg/FFmpeg)

Chaîne à outils bas niveau de transcodage vidéo, filtres, muxing, composition et traitement de flux.

- Catégorie : Téléchargement, capture, transcodage et médias CLI ; Infrastructure adjacente.
- Périmètre d'application : La licence peut être LGPL ou GPL selon les options de build ; beaucoup de projets de niveau supérieur ne sont que des encapsulations.
- État de maintenance : Commits sur les 90 derniers jours ; 414 commits sur 30 jours, 3019 commits sur 90 jours.
- Licence : [LGPL-2.1+ ; GPL-2.0+ une fois les composants GPL activés](https://github.com/FFmpeg/FFmpeg/blob/23c454005319dee4a5bcae5c370f75fdeb325230/LICENSE.md) ; Licence composite/conditionnelle. La licence finale dépend des options de compilation et des composants liés
- Vérification fonctionnelle : 2026-11-12 ; [Source1](https://github.com/FFmpeg/FFmpeg/blob/23c454005319dee4a5bcae5c370f75fdeb325230/README.md#L1).

## [yt-dlp](https://github.com/yt-dlp/yt-dlp)

Téléchargeur audio-vidéo en ligne de commande riche en fonctions couvrant un grand nombre de sites.

- Catégorie : Téléchargement, capture, transcodage et médias CLI ; Candidat principal.
- Périmètre d'application : C'est le CLI de résolution bas niveau de produits comme Downvid/VidBee ; il ne fournit pas d'atelier de montage complet.
- État de maintenance : Commits sur les 90 derniers jours ; 38 commits sur 30 jours, 79 commits sur 90 jours.
- Licence : [Unlicense](https://api.github.com/repos/yt-dlp/yt-dlp/license) ; Licence ouverte vérifiée. Identifiée via GitHub licenseInfo ; les poids de modèles, médias, polices, dépendances tierces et services managés relèvent de leurs propres licences
- Vérification fonctionnelle : 2026-11-12 ; [Source1](https://github.com/yt-dlp/yt-dlp/blob/412e7f0a4b0588fe884a02b344ac66a06538475b/README.md#L16).

## [Streamlink](https://github.com/streamlink/streamlink)

CLI qui résout les flux en direct en ligne et les enchaîne vers un lecteur local.

- Catégorie : Téléchargement, capture, transcodage et médias CLI ; Candidat principal.
- Périmètre d'application : Orienté lecture/enregistrement de flux ; pas équivalent à un téléchargement VOD généraliste ni à un éditeur.
- État de maintenance : Commits sur les 90 derniers jours ; 28 commits sur 30 jours, 154 commits sur 90 jours.
- Licence : [BSD-2-Clause](https://api.github.com/repos/streamlink/streamlink/license) ; Licence ouverte vérifiée. Identifiée via GitHub licenseInfo ; les poids de modèles, médias, polices, dépendances tierces et services managés relèvent de leurs propres licences
- Vérification fonctionnelle : 2026-11-12 ; [Source1](https://github.com/streamlink/streamlink/blob/993f9f1b63bd7a87292e05eda98d461ddc1f62c9/README.md#L13).

## [Downvid](https://github.com/Downvid/downvid)

GUI/WebUI multiplateforme de téléchargement vidéo bâti sur yt-dlp et FFmpeg.

- Catégorie : Téléchargement, capture, transcodage et médias CLI ; Candidat principal.
- Périmètre d'application : Surtout une couche produit ; la résolution des sites vient de yt-dlp, et l'usage suppose le respect des conditions des plateformes et des droits des contenus.
- État de maintenance : Commits sur les 90 derniers jours ; 52 commits sur 30 jours, 354 commits sur 90 jours.
- Licence : [MIT](https://api.github.com/repos/Downvid/downvid/license) ; Licence ouverte vérifiée. Identifiée via GitHub licenseInfo ; les poids de modèles, médias, polices, dépendances tierces et services managés relèvent de leurs propres licences
- Vérification fonctionnelle : 2026-11-12 ; [Source1](https://github.com/Downvid/downvid/blob/770bd3e3bf6157f1a2dd0ccb67ea6ce2a4b31807/README.md#L7).

## [VidBee](https://github.com/nexmoe/VidBee)

Télécharge les médias puis exécute en local transcription, annotation des locuteurs, résumés, traduction et dialogue avec les médias.

- Catégorie : Téléchargement, capture, transcodage et médias CLI ; Candidat principal.
- Périmètre d'application : Le téléchargement est fourni par l'écosystème yt-dlp ; les résumés IA peuvent appeler un modèle distant choisi par l'utilisateur.
- État de maintenance : Commits sur les 90 derniers jours ; 11 commits sur 30 jours, 51 commits sur 90 jours.
- Licence : [MIT](https://api.github.com/repos/nexmoe/VidBee/license) ; Licence ouverte vérifiée. Identifiée via GitHub licenseInfo ; les poids de modèles, médias, polices, dépendances tierces et services managés relèvent de leurs propres licences
- Vérification fonctionnelle : 2026-11-12 ; [Source1](https://github.com/nexmoe/VidBee/blob/6082e2604f0c37d942cdb896040aa0c88b5c527f/README.md#L2).

## [cobalt](https://github.com/imputnet/cobalt)

Application web de téléchargement de médias sans publicité ni pistage, avec API auto-hébergeable, couvrant YouTube, TikTok, Instagram et d'autres sites.

- Catégorie : Téléchargement, capture, transcodage et médias CLI ; Candidat principal.
- Périmètre d'application : Le monorepo contient api, web et la documentation ; aucune API pré-hébergée publique, il faut déployer sa propre instance ; ne traite que le contenu publiquement accessible, téléchargement et redistribution restant à la charge de l'utilisateur ; la marque et la mascotte sont sous copyright propre et ne suivent pas la licence du code.
- État de maintenance : Aucun commit depuis 91–365 jours ; 0 commits sur 30 jours, 0 commits sur 90 jours.
- Licence : [AGPL-3.0 (api et reste) + CC-BY-NC-SA-4.0 (web)](https://github.com/imputnet/cobalt/blob/a636575b09de1fc55d9b8cd98cac88f5f2f16b42/README.md#L59) ; Licence composite/conditionnelle. api et le reste du dépôt sous AGPL-3.0, le code web sous CC-BY-NC-SA-4.0 à usage non commercial ; marque et mascotte sous copyright séparé, seul l'hébergement non commercial d'instances non modifiées est autorisé ; les composants comme ffmpeg/libav.js relèvent d'autres licences
- Vérification fonctionnelle : 2026-11-23 ; [Source1](https://github.com/imputnet/cobalt/blob/a636575b09de1fc55d9b8cd98cac88f5f2f16b42/README.md#L28) · [Source2](https://github.com/imputnet/cobalt/blob/a636575b09de1fc55d9b8cd98cac88f5f2f16b42/README.md#L33) · [Source3](https://github.com/imputnet/cobalt/blob/a636575b09de1fc55d9b8cd98cac88f5f2f16b42/README.md#L45).

## [Lux](https://github.com/iawia002/lux)

CLI écrit en Go pour le téléchargement vidéo multi-sites.

- Catégorie : Téléchargement, capture, transcodage et médias CLI ; Candidat principal.
- Périmètre d'application : La couverture de résolution et la fréquence des mises à jour de sites constituent le principal risque de maintenance.
- État de maintenance : Aucun commit depuis 91–365 jours ; 0 commits sur 30 jours, 0 commits sur 90 jours.
- Licence : [MIT](https://api.github.com/repos/iawia002/lux/license) ; Licence ouverte vérifiée. Identifiée via GitHub licenseInfo ; les poids de modèles, médias, polices, dépendances tierces et services managés relèvent de leurs propres licences
- Vérification fonctionnelle : 2026-11-12 ; [Source1](https://github.com/iawia002/lux/blob/dd00f6d258d80b6684a0b9402d7124e5c18ef42f/README.md#L1).

## [you-get](https://github.com/soimort/you-get)

Utilitaire Python en ligne de commande pour télécharger des médias depuis des pages web.

- Catégorie : Téléchargement, capture, transcodage et médias CLI ; Candidat principal.
- Périmètre d'application : La couverture des sites et l'activité de maintenance sont à comparer séparément de celles de yt-dlp.
- État de maintenance : Aucun commit depuis plus de 365 jours ; 0 commits sur 30 jours, 0 commits sur 90 jours.
- Licence : [MIT](https://github.com/soimort/you-get/blob/049548f3f3f35e67ba8d3181c71fdc71d11cf260/LICENSE.txt) ; Licence ouverte vérifiée. LICENSE.txt racine vérifiée manuellement
- Vérification fonctionnelle : 2026-11-12 ; [Source1](https://github.com/soimort/you-get/blob/049548f3f3f35e67ba8d3181c71fdc71d11cf260/README.md#L1).

## [Aurora / AgentEdit-Bench](https://github.com/yeates/Aurora)

Unifie le montage vidéo par un agent à usage d'outils et fournit AgentEdit-Bench.

- Catégorie : Benchmarks, recherche et index externes ; Recherche/benchmark.
- Périmètre d'application : AgentEdit-Bench n'est pas directement comparable horizontalement aux métriques de VEFX ou EditVerse.
- État de maintenance : Commits sur les 90 derniers jours ; 4 commits sur 30 jours, 4 commits sur 90 jours.
- Licence : [MIT](https://api.github.com/repos/yeates/Aurora/license) ; Licence ouverte vérifiée. Identifiée via GitHub licenseInfo ; les poids de modèles, médias, polices, dépendances tierces et services managés relèvent de leurs propres licences
- Vérification fonctionnelle : 2026-11-12 ; [Source1](https://github.com/yeates/Aurora/blob/2599b748c56b29b67b9be352dc091b8ddf72ae8f/README.md#L3).

## [Awesome AI Video for Creators](https://github.com/sasateguh/awesome-ai-video-for-creators)

Classe les outils open source par workflow de créateur : montage, sous-titres, clipping, doublage et vidéo par code.

- Catégorie : Benchmarks, recherche et index externes ; Infrastructure adjacente.
- Périmètre d'application : Les instantanés externes d'étoiles évoluent ; les données finales reviennent au dépôt officiel.
- État de maintenance : Commits sur les 90 derniers jours ; 9 commits sur 30 jours, 15 commits sur 90 jours.
- Licence : [CC0-1.0](https://api.github.com/repos/sasateguh/awesome-ai-video-for-creators/license) ; Licence ouverte vérifiée. Identifiée via GitHub licenseInfo ; les poids de modèles, médias, polices, dépendances tierces et services managés relèvent de leurs propres licences
- Vérification fonctionnelle : 2026-11-12 ; [Source1](https://github.com/sasateguh/awesome-ai-video-for-creators/blob/3b88db72b425a89b751b6ea279532e3ae0a3d6f9/README.md#L1).

## [CutCraft Bench](https://github.com/AlibabaResearch/cut-craft-bench)

Évalue l'exécution de techniques de montage professionnelles dans la génération audio-vidéo multi-plans, avec une baseline agent.

- Catégorie : Benchmarks, recherche et index externes ; Recherche/benchmark.
- Périmètre d'application : La cohérence générée et l'éditabilité sont des métriques distinctes ; ne pas se limiter à un score global.
- État de maintenance : Commits sur les 90 derniers jours ; 0 commits sur 30 jours, 5 commits sur 90 jours.
- Licence : [À vérifier](https://github.com/AlibabaResearch/cut-craft-bench/blob/df2b35d63822d0832679fe675a274c33c51f7f75/README.md) ; Licence à vérifier. Aucune licence racine trouvée
- Vérification fonctionnelle : 2026-11-12 ; [Source1](https://github.com/AlibabaResearch/cut-craft-bench/blob/df2b35d63822d0832679fe675a274c33c51f7f75/README.md#L6).

## [Awesome Video Editing](https://github.com/devanasolver/awesome-video-editing)

Recense les outils open source de montage vidéo, les Agent Skills et les médias disponibles.

- Catégorie : Benchmarks, recherche et index externes ; Infrastructure adjacente.
- Périmètre d'application : Sert de base de découverte et de couverture ; ne participe pas aux jugements de capacité.
- État de maintenance : Commits sur les 90 derniers jours ; 0 commits sur 30 jours, 2 commits sur 90 jours.
- Licence : [CC0-1.0](https://github.com/devanasolver/awesome-video-editing/blob/637c0b63835cccaca2c5362baa7e564fee89a6dc/LICENSE) ; Licence ouverte vérifiée. Le contenu du répertoire est sous CC0
- Vérification fonctionnelle : 2026-11-12 ; [Source1](https://github.com/devanasolver/awesome-video-editing/blob/637c0b63835cccaca2c5362baa7e564fee89a6dc/README.md#L1).

## [Awesome AI Video](https://github.com/thoxakihiko/awesome-ai-video)

Recense les modèles, outils et ressources texte/image-vers-vidéo.

- Catégorie : Benchmarks, recherche et index externes ; Infrastructure adjacente.
- Périmètre d'application : Comprend des produits commerciaux et des modèles ; pas directement une liste d'outils open source.
- État de maintenance : Commits sur les 90 derniers jours ; 0 commits sur 30 jours, 3 commits sur 90 jours.
- Licence : [CC0-1.0](https://api.github.com/repos/thoxakihiko/awesome-ai-video/license) ; Licence ouverte vérifiée. Identifiée via GitHub licenseInfo ; les poids de modèles, médias, polices, dépendances tierces et services managés relèvent de leurs propres licences
- Vérification fonctionnelle : 2026-11-12 ; [Source1](https://github.com/thoxakihiko/awesome-ai-video/blob/45e9e2bfb3e1e1193e4725ce94bba45d0f342c5a/README.md#L1).

## [VEFX-Bench](https://github.com/Visko-Platform/VEFX-Bench)

Évalue le respect des instructions et la qualité en montage vidéo généraliste et effets visuels.

- Catégorie : Benchmarks, recherche et index externes ; Recherche/benchmark.
- Périmètre d'application : Les versions modèles, données, reward et API commerciales doivent être figées avant toute comparaison.
- État de maintenance : Aucun commit depuis 91–365 jours ; 0 commits sur 30 jours, 0 commits sur 90 jours.
- Licence : [Apache-2.0](https://api.github.com/repos/Visko-Platform/VEFX-Bench/license) ; Licence ouverte vérifiée. Identifiée via GitHub licenseInfo ; les poids de modèles, médias, polices, dépendances tierces et services managés relèvent de leurs propres licences
- Vérification fonctionnelle : 2026-11-12 ; [Source1](https://github.com/Visko-Platform/VEFX-Bench/blob/a82437764d1e2a2068e5e183075f437d5bd0568b/README.md#L9).

## [EditVerse](https://github.com/adobe-research/EditVerse)

Code de recherche en génération et édition d'images et de vidéos, avec EditVerseBench.

- Catégorie : Benchmarks, recherche et index externes ; Licence restreinte.
- Périmètre d'application : Le code de recherche et les téléchargements de données dépendent de sources externes ; les résultats doivent être reproduits selon le réglage du papier.
- État de maintenance : Aucun commit depuis plus de 365 jours ; 0 commits sur 30 jours, 0 commits sur 90 jours.
- Licence : [Adobe Research License (fichiers partiels)](https://github.com/adobe-research/EditVerse/blob/eeca9ce9f99db2d5c90e775853735025523c9334/LICENSE.md) ; Code source visible mais non open source OSI. LICENSE ne couvre que les fichiers explicitement listés, les autres fichiers sont hors de cette licence
- Vérification fonctionnelle : 2026-11-12 ; [Source1](https://github.com/adobe-research/EditVerse/blob/eeca9ce9f99db2d5c90e775853735025523c9334/README.md#L1).

## [Video-Bench](https://github.com/Video-Bench/Video-Bench)

Organise et exécute des évaluations multidimensionnelles des modèles de génération vidéo.

- Catégorie : Benchmarks, recherche et index externes ; Recherche/benchmark.
- Périmètre d'application : Un benchmark de génération ne dit rien de la qualité d'un éditeur timeline ni d'un système de production.
- État de maintenance : Aucun commit depuis plus de 365 jours ; 0 commits sur 30 jours, 0 commits sur 90 jours.
- Licence : [Apache-2.0](https://api.github.com/repos/Video-Bench/Video-Bench/license) ; Licence ouverte vérifiée. Identifiée via GitHub licenseInfo ; les poids de modèles, médias, polices, dépendances tierces et services managés relèvent de leurs propres licences
- Vérification fonctionnelle : 2026-11-12 ; [Source1](https://github.com/Video-Bench/Video-Bench/blob/d40b917c4238011aea27d24f85b1e3bf996715bd/README.md#L1).

## [Palmier Pro](https://github.com/palmier-io/palmier-pro)

Éditeur vidéo pensé pour l'IA dont les anciennes versions du code source sont sorties sous GPLv3.

- Catégorie : Versions historiques et restreintes ; Référence historique.
- Périmètre d'application : Après v0.7.6, les binaires sont propriétaires et le code source correspondant n'est pas public ; seul last-gpl-source compte comme version open source historique.
- État de maintenance : Archivé / historique ; 5 commits sur 30 jours, 9 commits sur 90 jours.
- Licence : [GPL-3.0 (sources jusqu'à v0.7.6) / binaires propriétaires ensuite](https://github.com/palmier-io/palmier-pro/blob/dfc810b561f1692947eb81bbb689e078923ebb59/README.md#L112) ; Licence composite/conditionnelle. last-gpl-source et les sources antérieures à v0.7.6 sont sous GPLv3 ; les binaires suivants n'ont pas de code source public correspondant
- Vérification fonctionnelle : 2026-11-12 ; [Source1](https://github.com/palmier-io/palmier-pro/blob/dfc810b561f1692947eb81bbb689e078923ebb59/README.md#L2).
