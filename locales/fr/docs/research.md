# Méthode de recherche, mots-clés et journal de couverture

Date de recherche : 2026-11-12. L'objectif était de cartographier l'écosystème de génération et de montage vidéo par IA à partir des 22 projets de référence fournis par l'utilisateur, et non de mélanger modèles génératifs, NLE traditionnels, téléchargeurs et Skills dans un seul classement.

## Mots-clés

| Direction | Mots-clés anglais | Mots-clés chinois |
| --- | --- | --- |
| Montage agentique | agent video editor, video MCP, editing skill | Agent 剪辑、视频 Skill、剪辑 MCP |
| Production complète | agentic video production, script-to-video, timeline | 视频生产 Agent、脚本成片、时间线 |
| Vidéos courtes de savoir | explainer video, knowledge article to video, shorts | 知识类短视频、讲解视频、长视频切片 |
| Code-to-video | Remotion, HyperFrames, HTML video, motion graphics | 代码成片、动效、数据故事 |
| Avatars numériques | digital presenter, talking avatar, lip sync | 数字人、口播、肖像动画、唇同步 |
| Modèles génératifs | text-to-video, image-to-video, video diffusion | 文生视频、图生视频、视频扩散模型 |
| Médias CLI | video downloader CLI, FFmpeg, yt-dlp, Streamlink | 视频下载 CLI、转码、直播流 |
| Évaluation | video editing benchmark, VFX benchmark, agent editing | 视频编辑评测、多镜头剪辑、AgentEdit |

## Processus en trois passes

| Passe | Lots | Résultats | Nouvelles sources | Taux de nouvelles sources |
| --- | ---: | ---: | ---: | ---: |
| 1 | 14 | 394 | 377 | 95.7% |
| 2 | 7 | 130 | 101 | 77.7% |
| 3 | 7 | 270 | 208 | 77.0% |

La première passe a couvert les projets de l'utilisateur, la recherche GitHub, le comparatif CLI, les risques, les benchmarks et l'index externe Awesome Video Editing.

La deuxième passe a examiné OpenFilm, OpenKatana, Kinocut, OpenMontage, OpenClip, MakeMyClip, WeVisCut, VidBee et GiveMotion, ainsi que de nouvelles entités comme VEFX/CutCraft/AgentEdit.

La troisième passe a complété les modèles vidéo open source, les avatars numériques, la vulgarisation, les bases du Code-to-video et les CLI de téléchargement, puis a enregistré en lot les README primaires et les métriques GitHub de tous les projets retenus.

La raison d'arrêt est la limite de trois passes fixée à l'avance, pas la saturation de l'espace de recherche. Le taux de nouvelles sources du troisième tour restait élevé ; le catalogue doit donc être tenu à jour par incréments.

## Content factory

Appels de `/search/api/query` via la voie curl de `content-factory-search-api`. Requêtes :

- `AI 视频剪辑 OR 视频生成 OR 知识类短视频`
- `SeeCut OR OpenChatCut OR Clypra OR ReelBench`
- `Downvid OR yt-dlp OR 视频下载 CLI`
- `OpenFilm OR OpenKatana OR Kinocut OR WeVisCut`

Les requêtes partent des 30 derniers jours et s'étendent par paliers à 90/180/365 jours selon les règles du skill quand les résultats sont clairsemés. Après normalisation, la content factory a contribué 69 sources et aidé à découvrir Clypra, GeekReel, VidBee, WeVisCut, OpenFilm, OpenMontage ainsi que l'écosystème des skills vidéo agent. Les requêtes larges sur la vidéo IA ont aussi produit beaucoup de benchmarks de modèles et de contenu hors sujet ; la décision finale sur chaque projet revient au dépôt officiel.

Aucune adresse de service privée, clé ni article interne de la content factory n'a été committé dans le dépôt public.

## Corrections clés sur la taxonomie

- **Downvid n'est pas un résolveur de même niveau que yt-dlp.** C'est un GUI/WebUI multiplateforme : la résolution vient de yt-dlp, la fusion et le transcodage de FFmpeg.
- **VidBee est un produit de compréhension média après téléchargement.** Outre le téléchargement : transcription locale, annotation des locuteurs, résumés, traduction et dialogue avec les médias.
- **SeeCut est un espace de skills agent, pas un NLE autonome.**
- **Video Autopilot Kit planifie et audite ; Editkin effectue le rendu.**
- **CozyClay est un outil de prévisualisation et de planification de plans.** La génération finale est confiée à un modèle vidéo externe.
- **Rea Video fait de la rétro-ingénierie et de la planification de duplication.** Ce n'est pas le montageur final.
- **OpenFilm/GiveMotion/HyperFrames relèvent du code-vers-la-vidéo.** On ne les compare pas directement aux capacités d'une timeline traditionnelle.
- **Les dépôts de modèles génératifs et les applications de création sont séparés.** Wan, Hunyuan, LTX, CogVideo, Mochi, etc. fournissent modèles et code d'inférence, pas une gestion complète de production.

## Downvid et CLI

Les entrées OpenViking et l'historique local disponibles ne permettent pas d'identifier de façon unique le « CLI utilisé auparavant » par l'utilisateur ; aucune spéculation n'a été faite. Le [comparatif CLI](cli-comparison.md) final couvre :

- Downvid : GUI/WebUI, dépend de yt-dlp + FFmpeg.
- VidBee : desktop + CLI, enchaîne transcription locale et compréhension média après téléchargement.
- yt-dlp : le CLI principal de résolution multi-sites et de téléchargement.
- you-get / Lux : des voies CLI plus légères, respectivement Python / Go.
- Streamlink : du flux en direct vers le lecteur ou le pipeline d'enregistrement.
- FFmpeg : transcodage, filtres, fusion et muxing, sans résolution de sites.

Si le nom du CLI historique est confirmé plus tard, il pourra rejoindre ce comparatif comme entrée incrémentale.

## Corrections sur les licences

- SeeCut : PolyForm Noncommercial.
- Remotion : gratuit pour particuliers et petites organisations ; une licence commerciale devient nécessaire quand l'entreprise atteint les seuils prévus.
- VRGameDevGirl : source-available ; les contenus générés sont commercialisables, mais la vente du logiciel lui-même suppose une autorisation.
- HunyuanVideo / I2V : licence communautaire Tencent, avec exclusions géographiques et politique d'utilisation.
- Wav2Lip : usage personnel, recherche et non commercial.
- Palmier : source GPL avant la v0.7.6, binaires propriétaires ensuite sans code source public correspondant.
- EditVerse : l'Adobe Research License ne couvre que les fichiers explicitement listés.
- FFmpeg : LGPL par défaut ; la licence globale change dès que des composants GPL spécifiques sont activés.
- SenseNova Code2Video, CutCraft : aucune licence racine explicite trouvée.

La description des licences ne remplace pas un avis juridique ; médias, polices, musique, images de personnes, données d'entraînement et sorties des modèles gardent des frontières de droits propres.

## Couverture

Les 22 URL GitHub de la base utilisateur sont toutes entrées dans le registre de recherche ; taux de couverture des URL : 100%. Le seul non-retour, `CLI-oriented`, est une simple expression de la description de la base, pas un projet.

La couverture de l'index externe `devanasolver/awesome-video-editing` atteint 53.3%. Son périmètre inclut aussi des NLE traditionnels, des outils audio, des sous-titres, du screen recording, des icônes, des polices, des HDRI, des sites de musique/vidéo gratuits et de nombreuses URL de badges. Ce catalogue ne recopie volontairement ni tous les sites de médias ni tous les outils traditionnels ; ce manque relève donc d'une différence de périmètre, et les projets de l'index externe directement liés à la vidéo IA/agent ont servi de pistes de découverte.

## Ce que cette passe n'a pas fait

Les projets du catalogue n'ont pas été installés ni exécutés, les gros poids de modèles n'ont pas été téléchargés, aucune API de génération payante n'a été appelée, aucun téléchargement, retrait de filigrane, montage ou publication sur les médias de l'utilisateur n'a été exécuté, et aucun benchmark n'a été reproduit de façon uniforme.

Les étoiles et le volume de commits GitHub ne servent qu'au classement de maintenance. Une comparaison réelle devrait figer médias, script, modèles, matériel, budget API et format de sortie, puis relever le taux de réussite du montage, le volume de retouches humaines, la cohérence des plans, les sous-titres et la synchronisation labiale, le temps de rendu, la VRAM, les coûts et les licences.

## Fichiers vérifiables

- [Journal de recherche](../../../research/search-log.json)
- [Décisions d'inclusion et preuves figées](../../../research/decisions.json)
- [Couverture des projets de l'utilisateur](../../../research/coverage-user.json)
- [Couverture de l'index externe](../../../research/coverage-external.json)
- [Instantané des métriques initiales](../../../research/initial-metrics.json)
- [État de la recherche](../../../research/status.json)
- [Vérification de complétude](../../../research/verification.json)

Le registre de recherche contient 686 sources, 144 jugements et 216 jeux de métriques GitHub. Les textes de pages complets et les journaux d'outils locaux restent hors du dépôt.
