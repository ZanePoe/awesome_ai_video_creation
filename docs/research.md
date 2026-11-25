# Search method, keywords, and coverage log

Research date: 2026-11-12. The goal was to map the AI video generation and editing ecosystem out of 22 user-reference projects, not to mix generation models, traditional NLEs, downloaders, and Skills into one leaderboard.

## Keywords

| Direction | English keywords | Chinese keywords |
| --- | --- | --- |
| Agent editing | agent video editor, video MCP, editing skill | Agent 剪辑、视频 Skill、剪辑 MCP |
| Full production | agentic video production, script-to-video, timeline | 视频生产 Agent、脚本成片、时间线 |
| Knowledge shorts | explainer video, knowledge article to video, shorts | 知识类短视频、讲解视频、长视频切片 |
| Code-to-video | Remotion, HyperFrames, HTML video, motion graphics | 代码成片、动效、数据故事 |
| Digital humans | digital presenter, talking avatar, lip sync | 数字人、口播、肖像动画、唇同步 |
| Generation models | text-to-video, image-to-video, video diffusion | 文生视频、图生视频、视频扩散模型 |
| Media CLI | video downloader CLI, FFmpeg, yt-dlp, Streamlink | 视频下载 CLI、转码、直播流 |
| Evaluation | video editing benchmark, VFX benchmark, agent editing | 视频编辑评测、多镜头剪辑、AgentEdit |

## The three rounds

| Round | Batches | Results | New sources | New-source rate |
| --- | ---: | ---: | ---: | ---: |
| 1 | 14 | 394 | 377 | 95.7% |
| 2 | 7 | 130 | 101 | 77.7% |
| 3 | 7 | 270 | 208 | 77.0% |

Round 1 covered user projects, GitHub search, CLI comparison, risks, benchmarks, and the Awesome Video Editing external index.

Round 2 re-checked OpenFilm, OpenKatana, Kinocut, OpenMontage, OpenClip, MakeMyClip, WeVisCut, VidBee, and GiveMotion, plus new entities such as VEFX/CutCraft/AgentEdit.

Round 3 filled in open-source video models, digital humans, knowledge explainers, Code-to-video infrastructure, and download CLIs, and registered first-party READMEs and GitHub metrics for all final projects in bulk.

The stopping reason was the preset three-round limit, not a saturated search space. Round 3 still had a high new-source rate, so the catalogue should be maintained incrementally.

## Content factory

Calls used the curl path of `content-factory-search-api` against `/search/api/query`. Queries included:

- `AI 视频剪辑 OR 视频生成 OR 知识类短视频`
- `SeeCut OR OpenChatCut OR Clypra OR ReelBench`
- `Downvid OR yt-dlp OR 视频下载 CLI`
- `OpenFilm OR OpenKatana OR Kinocut OR WeVisCut`

Queries started at the last 30 days and widened stepwise to 90/180/365 days per the skill rules when results were sparse. After normalization, the content factory contributed 69 sources and helped discover Clypra, GeekReel, VidBee, WeVisCut, OpenFilm, OpenMontage, and the agent video Skill ecosystem. Broad AI-video queries also produced many model evaluations and irrelevant items; final project judgments went back to official repositories.

No private service addresses, keys, or internal article bodies were committed to the public repository.

## Key taxonomy corrections

- **Downvid is not a peer parser of yt-dlp.** It is a cross-platform GUI/WebUI whose extraction comes from yt-dlp and whose merging and transcoding come from FFmpeg.
- **VidBee is a post-download media-understanding product.** Beyond downloading it does local transcription, speaker labeling, summarization, translation, and media chat.
- **SeeCut is an agent Skill workspace, not a standalone NLE.**
- **Video Autopilot Kit handles planning and auditing; Editkin does the actual rendering.**
- **CozyClay is a previs and shot-blocking tool.** Final generation is done by external video models.
- **Rea Video does reverse breakdown and replication planning.** It is not a final editor.
- **OpenFilm/GiveMotion/HyperFrames belong to code-to-video.** Traditional timeline capabilities cannot be compared directly.
- **Model repositories are separated from creation apps.** Wan, Hunyuan, LTX, CogVideo, Mochi, and the like provide models and inference code, not full production management.

## Downvid and CLIs

The currently reachable OpenViking and local history entries could not uniquely identify the CLI the user said they had used before, so no guess was made. The final [CLI comparison](cli-comparison.md) covers:

- Downvid: GUI/WebUI depending on yt-dlp + FFmpeg.
- VidBee: desktop + CLI that continues with local transcription and media understanding after downloading.
- yt-dlp: the primary low-level CLI for multi-site extraction and download.
- you-get / Lux: lighter Python / Go CLI routes.
- Streamlink: livestream into a player/recording pipeline.
- FFmpeg: transcoding, filters, merging, and muxing; it does not do site extraction.

If the historical CLI's name is later confirmed, it can be added to this comparison as an incremental entry.

## License corrections

- SeeCut: PolyForm Noncommercial.
- Remotion: free for individuals/small organizations; a commercial license is required once company-size conditions are met.
- VRGameDevGirl: source-available; generated content may be commercialized, but commercializing the software itself requires authorization.
- HunyuanVideo / I2V: Tencent community license with territory exclusions and an acceptable-use policy.
- Wav2Lip: personal, research, and non-commercial use.
- Palmier: source was GPL up to v0.7.6; later binaries are proprietary with no corresponding public source.
- EditVerse: the Adobe Research License covers only the explicitly listed files.
- FFmpeg: LGPL by default; enabling certain GPL components changes the overall license.
- SenseNova Code2Video, CutCraft: no explicit root-directory license found.

License descriptions are not legal advice; media, fonts, music, portrait rights, training data, and model outputs each keep their own rights boundaries.

## Coverage

All 22 GitHub URLs from the user baseline entered the research ledger — 100% URL coverage. The single miss, `CLI-oriented`, is an ordinary phrase in the baseline description, not a project.

External coverage of `devanasolver/awesome-video-editing` is 53.3%. Its scope also includes traditional NLEs, audio tools, subtitles, screen recording, icons, fonts, HDRIs, free music/video sites, and many badge URLs. This catalogue deliberately does not copy all asset sites and traditional tools, so the gap is a scope difference; items in that external index directly relevant to AI/agent video were used as discovery leads.

## What this round did not do

It did not install and run the catalogue's projects, download large model weights, call paid generation APIs, download/watermark-strip/edit/publish user media, or reproduce benchmarks under a unified harness.

GitHub stars and commit counts are used only for maintenance ranking. A real comparison should fix the media, script, models, hardware, API budget, and output formats, and record finish rate, manual revision volume, shot consistency, subtitles and lip sync, render time, VRAM, cost, and licensing.

## Verifiable files

- [Search log](../research/search-log.json)
- [Inclusion decisions and pinned evidence](../research/decisions.json)
- [User project coverage](../research/coverage-user.json)
- [External index coverage](../research/coverage-external.json)
- [Initial metrics snapshot](../research/initial-metrics.json)
- [Research status](../research/status.json)
- [Verification](../research/verification.json)

The research ledger contains 686 sources, 144 decisions, and 216 GitHub metric records. Full page text and local tool logs stayed on the local machine.
