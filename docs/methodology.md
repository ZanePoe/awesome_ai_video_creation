# Ranking method and limits

GitHub metrics are collected in batches at a fixed UTC time through the GraphQL API. A snapshot is replaced atomically only when every batch succeeds. The one exception is a repository GitHub can no longer resolve (renamed away or deleted): its previous record is carried forward and marked `missing_upstream` with a `missing_since` timestamp, so a single vanished project cannot break the daily refresh. Rate limits, transport failures and partial GraphQL responses still abort the run and keep the previous snapshot whole.

- stars: a proxy for community attention.
- 30/90-day commits: full-history counts on the default branch, including docs, merge, and bot commits.
- Last commit: the default-branch HEAD time; pushes to other branches or repository metadata changes are not passed off as code updates.
- Release, archive, and license identification are stored separately for audit.

Projects are first split into four tiers — commits within the last 90 days, no commits for 91–365 days, no commits for over 365 days, and archived/historical — and then scored:

```text
P = min(1, ln(1 + stars) / ln(1 + 100000))
A = min(1, ln(1 + commits_90d) / ln(1 + 500))
R = exp(-days_since_default_branch_HEAD / 90)
maintenance_score = 100 × (0.40P + 0.35A + 0.25R)
```

The maintenance score is not a score for final-video quality, editing taste, generation-model capability, speed, VRAM, cost, or copyright safety. Monorepos and bot commits can inflate activity; a stable model repository may also commit rarely for long.

Automated license detection and manual review are kept separate. Remotion, Hunyuan, Wav2Lip, Palmier, FFmpeg, and others use conditional, composite, or version-dependent licenses; model weights, media assets, fonts, and third-party services may carry additional terms.

A unified capability evaluation should fix the media, script, model versions, budget, and hardware, and separately record generation success rate, shot consistency, subtitle/lip sync, timeline editability, amount of manual revision, render time, VRAM, API cost, and output licensing.
