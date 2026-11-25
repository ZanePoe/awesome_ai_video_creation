# Périmètre et taxonomie

Sont retenus les projets GitHub capables de participer directement à la génération vidéo, au montage, à l'analyse de médias, aux avatars numériques, au motion design par code, à l'automatisation agent, à l'obtention de médias ou à l'évaluation. Les produits purement commerciaux, les pages de démo sans implémentation vérifiable, les générateurs d'images ordinaires et les agents généralistes sans lien avec la vidéo n'entrent pas dans le catalogue principal.

| Catégorie | Rôle principal |
| --- | --- |
| Éditeurs vidéo et ateliers de production | Fournissent timeline, canvas, nœuds, fichiers de projet ou interface de production complète |
| Production vidéo agentique et automatisation | Systèmes multi-étapes du but/script jusqu'aux médias, au montage, au contrôle qualité et à l'export |
| Vidéos courtes de savoir, extraits et vulgarisation | Vidéos de savoir, explications avec avatar, découpage de longues vidéos et formats courts sociaux |
| Agent Skills, MCP et outils de montage | Skills, MCP, CLI et outils déterministes appelés par des coding agents |
| Code-to-video et motion design | Rendu vidéo par code : HTML/React/Canvas/Three.js/Python, etc. |
| Animation, 3D et briques de base du codage | Outils génériques d'animation, de vectoriel, de rendu 3D et d'encodage GIF pour construire des scènes vidéo ; classés infrastructure adjacente |
| ComfyUI et génération vidéo open source | Modèles vidéo diffusion/DiT, workflows ComfyUI et runtime de génération |
| Avatars numériques, animation de portrait et synchronisation labiale | Pilotage par portrait, têtes parlantes, avatars temps réel et lip sync |
| Téléchargement, capture, transcodage et médias CLI | Téléchargement de médias légalement autorisés, flux en direct, transcodage, muxing et traitement de base |
| Benchmarks, recherche et index externes | Benchmarks de génération/édition vidéo, code de recherche et index de couverture |
| Versions historiques et restreintes | Versions open source passées ou projets dont la licence actuelle n'est plus ouverte |

Chaque dépôt n'a qu'une catégorie principale. Un skill peut appeler Remotion, FFmpeg ou une API de modèle sans être dupliqué pour autant dans trois catégories.

## Frontières importantes

- Downvid/VidBee sont des couches produit ; yt-dlp, FFmpeg, etc. en sont les outils sous-jacents.
- Un Skill/MCP n'est pas un éditeur autonome : il faut préciser l'hôte, le moteur de rendu et les services externes.
- Un « fichier de projet local » ne garantit pas que les API de modèles, l'ASR, le TTS ou la recherche de médias restent hors ligne.
- Vidéo générée par code, vidéo par diffusion et montage de rushes réels sont des modes de production distincts.
- Les licences du code du modèle, des poids, des données d'entraînement, de la politique de sortie et des droits à l'image doivent être vérifiées séparément.
- Les outils de téléchargement ne s'appliquent qu'au contenu que l'utilisateur a le droit de sauvegarder et de traiter, dans le respect des conditions des plateformes.
- Les résultats de benchmark ne sont comparables qu'à modèle, entrées, budget et protocole de notation identiques.
