# Méthode de classement et limites

Les métriques GitHub sont collectées en lots via l'API GraphQL à un instant UTC figé. L'instantané n'est remplacé de façon atomique que si tous les lots réussissent.

- étoiles : proxy de l'attention de la communauté.
- commits 30/90 jours : historique complet de la branche par défaut, commits de documentation, de fusion et de robots inclus.
- dernier commit : horodatage du HEAD de la branche par défaut ; les pushes d'autres branches ou les changements de métadonnées du dépôt ne comptent pas comme mises à jour de code.
- releases, archivage et identification de licence sont conservés séparément pour l'audit.

Stratification d'abord en quatre paliers — actif sur les 90 derniers jours, aucun commit depuis 91–365 jours, aucun commit depuis plus de 365 jours, archivé/historique — puis calcul :

```text
P = min(1, ln(1 + stars) / ln(1 + 100000))
A = min(1, ln(1 + commits_90d) / ln(1 + 500))
R = exp(-days_since_default_branch_HEAD / 90)
score_de_maintenance = 100 × (0.40P + 0.35A + 0.25R)
```

Le score de maintenance n'est ni un score de qualité de montage, de sens du cadrage, de capacité des modèles génératifs, de vitesse, de VRAM, de coût ni de sécurité des droits. Les monorepos et les commits de robots peuvent gonfler l'activité ; un dépôt de modèle stable peut aussi publier rarement pendant de longues périodes.

L'identification automatique des licences et la revue humaine sont distinctes. Remotion, Hunyuan, Wav2Lip, Palmier, FFmpeg, etc. adoptent des licences conditionnelles, composites ou liées à une version ; poids de modèles, médias, polices et services tiers peuvent avoir des conditions propres.

Une évaluation comparative des capacités devrait figer médias, script, version des modèles, budget et matériel, et relever séparément le taux de réussite de génération, la cohérence des plans, les sous-titres et la synchronisation labiale, l'éditabilité de la timeline, le volume de retouches humaines, la durée de rendu, la VRAM, le coût API et la licence de sortie.
