# Contributing guide

New projects and corrections to category, feature boundary, or license are welcome.

1. Edit `data/projects.json`; do not edit generated tables directly.
2. Provide the canonical GitHub repository, one primary category, purpose, limitations, and README evidence at a pinned commit.
3. State clearly whether it is a workbench, agent system, Skill/MCP, code motion, generation model, digital human, CLI, or benchmark.
4. Do not present roadmaps, demo reels, or author benchmarks as independently tested conclusions.
5. Verify code, model weights, media assets, fonts, third-party APIs, and output-content licensing separately.
6. Download/capture projects must retain the platform-terms and content-rights boundaries.
7. After adding a project, run:

```sh
python scripts/refresh_metrics.py
python scripts/build.py
python -m unittest discover -s tests -v
python scripts/build.py --check
```

Do not commit API keys, private videos, unauthorized assets, internal content-factory addresses, or personal data. Change records go under `record/` as `YYYY-MM-DD-<topic>.md`, in the language used at verification time.

## Multilingual files

- `data/projects.json` is the canonical reviewed wording in Chinese; a fact changes there once.
- Other languages read `locales/<lang>/entries.json` (`description`, `boundary`, `license_label`, `license_note`, plus `name` when the canonical name contains Chinese) and `locales/<lang>/ui.json`. `zh` falls back to `data/projects.json`, so there is no `locales/zh/entries.json`.
- When you add a project or re-word its purpose, boundary or licence verdict, update the es/hi/fr locales in the same pull request; otherwise `python scripts/build.py --check` and `python -m unittest discover -s tests -v` fail.
- Static prose: English lives in root `docs/` and `CONTRIBUTING.md`, the other locales in the same relative paths under `locales/<lang>/`. Links inside a mirror resolve from that file's own directory — `docs/research.md` needs `../../../research/…` there, `CONTRIBUTING.md` needs `../../…` — while `docs/readme-intro.md` is inlined into the README and resolves from the locale root.
- Generated files (`README.md`, `docs/projects.md`, `docs/rankings.md`, `data/rankings.csv` and their locale mirrors) are never edited by hand; run `python scripts/build.py`.
