# Comparatif Downvid et CLI vidéo

L'utilisateur a mentionné avoir utilisé un autre CLI, mais les traces OpenViking et l'historique local consultables ne permettent pas d'identifier son nom de façon unique. Cette page compare les projets vérifiables dominants et ne spécule pas sur l'identité d'un outil historique.

| Projet | Forme | Usage principal | Rapport à Downvid | Frontière clé |
| --- | --- | --- | --- | --- |
| Downvid | GUI desktop / WebUI | Téléchargement multi-sites, choix de format et fusion FFmpeg | Couche produit, dépend en interne de yt-dlp et FFmpeg | La capacité de résolution suit yt-dlp ; respecter les conditions des sites |
| VidBee | Application desktop + CLI | Téléchargement, transcription, annotation des locuteurs, résumés, traduction et dialogue avec les médias | Chaîne de compréhension média plus large que Downvid | Les fournisseurs IA peuvent sortir du réseau local ; le téléchargement repose toujours sur yt-dlp |
| yt-dlp | CLI Python | Résolution audio-vidéo multi-sites, téléchargement, métadonnées, post-traitement | Résolveur bas niveau principal de Downvid/VidBee | Prise en main CLI coûteuse ; les changements de sites exigent des mises à jour fréquentes |
| you-get | CLI Python | Téléchargement simple de médias depuis des pages web | Alternative CLI directe plus légère | Activité et couverture de sites à comparer avec yt-dlp |
| Lux | CLI Go | Téléchargement vidéo multi-sites | Alternative au style binaire unique | L'adaptation aux sites et la fréquence de maintenance sont le risque central |
| Streamlink | CLI Python | Achemine les flux en direct vers un lecteur ou un pipeline d'enregistrement | Complément pour le direct, pas un téléchargement VOD généraliste | Orienté flux temps réel plutôt que montage |
| FFmpeg | Chaîne à outils C | Transcodage, filtres, fusion, muxing, diffusion | Socle de fusion/transcodage de Downvid | Les options de build décident LGPL/GPL ; ce n'est pas un résolveur de sites |

## Suggestions de choix

- Pour du « cliquer-et-utiliser » : Downvid.
- Pour enchaîner transcription, résumé et recherche de médias après téléchargement : VidBee.
- Pour scripter, traiter par lots et contrôler précisément formats et post-traitement : yt-dlp + FFmpeg.
- Pour travailler surtout sur du direct : Streamlink.
- Pour une expérience CLI simple ou binaire unique : examiner you-get et Lux séparément, en confirmant d'abord que les sites cibles sont toujours pris en charge.

Ce catalogue n'assimile pas la capacité de téléchargement à une « autorisation sans filigrane ». Qu'un outil puisse résoudre un contenu ne donne à l'utilisateur aucun droit de le télécharger, de retirer son filigrane, de le remonter ni de le publier.
