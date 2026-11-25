# Scope and taxonomy

Included are GitHub projects that directly participate in video generation, editing, media analysis, digital humans, code motion, agent automation, media acquisition, or evaluation. Pure commercial products, demo pages with no reviewable implementation, generic image generators, and video-unrelated general agents do not enter the main catalogue.

| Category | Primary role |
| --- | --- |
| Video editors and production workbenches | Timelines, canvases, nodes, project files, or a complete production interface |
| Agent video production and automation | Multi-step execution systems from goal/script to media, editing, QC, and export |
| Knowledge shorts, clipping and explainers | Knowledge videos, digital-human narration, long-video clipping, and social shorts |
| Agent Skills, MCP and editing tools | Skills, MCP, CLIs, and deterministic tools invoked by coding agents |
| Code-to-video and motion graphics | Videos rendered from code such as HTML/React/Canvas/Three.js/Python |
| Animation, 3D and coding building blocks | General animation, vector, 3D rendering, and GIF encoding tools used to build video scenes; marked as adjacent infrastructure |
| ComfyUI and open-source video generation | Diffusion/DiT video models, ComfyUI workflows, and generation runtimes |
| Digital humans, portrait animation and lip sync | Portrait-driven talking heads, real-time digital humans, and lip sync |
| Download, capture, transcoding and media CLIs | Licensed media download, livestream handling, transcoding, muxing, and basic processing |
| Benchmarks, research and external indexes | Video generation/editing benchmarks, research code, and coverage indexes |
| Historical and restricted versions | Historically open releases or projects whose current license is no longer open |

Each repository has exactly one primary category. A Skill may call Remotion, FFmpeg, or model APIs, but it is not duplicated into three categories for that reason.

## Key boundaries

- Downvid/VidBee are product layers; yt-dlp, FFmpeg, and the like are their underlying tools.
- A Skill/MCP is not a standalone editor; the host, renderer, and external services must be stated.
- "Local project files" does not mean model APIs, ASR, TTS, or media search stay offline.
- Code-generated video, diffusion video, and real-footage editing are different production methods.
- Model code license, weight license, training data, output policy, and portrait rights must be verified separately.
- Download tools apply only to content the user is entitled to save and process, within platform terms.
- Benchmark results are comparable only under the same models, inputs, budgets, and scoring protocols.
