🌐 **English** · [简体中文](locales/zh/README.md) · [Español](locales/es/README.md) · [हिन्दी](locales/hi/README.md) · [Français](locales/fr/README.md)

# awesome_ai_video_creation

**Curated open-source AI video generation, editing, agentic production, code-to-video, digital presenters, ComfyUI workflows, media CLIs, and benchmarks — with evidence-linked descriptions and reproducible GitHub maintenance rankings.**

This directory covers the full pipeline: licensed media acquisition, script and shot planning, image/video generation, digital humans, timeline editing, subtitles and voiceover, motion graphics, quality checks, and export. Models, workbenches, Skills, CLIs and benchmarks are categorized separately.

[Category index](#category-index) · [Project details](docs/projects.md) · [CLI comparison](docs/cli-comparison.md) · [Rankings](docs/rankings.md) · [Research log](docs/research.md) · [Contributing](CONTRIBUTING.md)

```mermaid
flowchart LR
    A[Topic / Script / Media] --> B[Shot planning / Storyboard]
    B --> C[Live footage / Generative models / Code motion]
    C --> D[Timeline / Subtitles / Voiceover / Music]
    D --> E[Review / QC / Repair]
    E --> D
    E --> F[Export / Release package]
```

The first release provides a verifiable ecosystem map; it does not claim to cover every video model, commercial API or traditional NLE plugin.

## Jump to a category

[Video editors and production workbenches](#video-editors-and-production-workbenches) · [Agent video production and automation](#agent-video-production-and-automation) · [Knowledge shorts, clipping and explainers](#knowledge-shorts-clipping-and-explainers) · [Agent Skills, MCP and editing tools](#agent-skills-mcp-and-editing-tools) · [Code-to-video and motion graphics](#code-to-video-and-motion-graphics) · [Animation, 3D and coding building blocks](#animation-3d-and-coding-building-blocks) · [ComfyUI and open-source video generation](#comfyui-and-open-source-video-generation) · [Digital humans, portrait animation and lip sync](#digital-humans-portrait-animation-and-lip-sync) · [Download, capture, transcoding and media CLIs](#download-capture-transcoding-and-media-clis) · [Benchmarks, research and external indexes](#benchmarks-research-and-external-indexes) · [Historical and restricted versions](#historical-and-restricted-versions)

## Current coverage

**109 projects, of which 22 are user-reference projects and 87 were added in this round.** Feature verification: 2026-11-25; metrics snapshot: `2026-11-25T00:17:13+00:00` (UTC).

Within each category, projects are first tiered by maintenance status, then ranked by a blend of stars (40%), 90-day default-branch commits (35%) and recency of the last commit (25%). The maintenance score does not represent final-video quality, model capability, copyright safety or production readiness.

## Active core projects at a glance

Shows only core candidates with a verified open license and commits in the last 90 days; restricted-license projects, base models, research benchmarks and adjacent tools are excluded from this table.

| Project | Positioning | Stars | 90-day commits | Last commit (UTC) | Maintenance score |
| --- | --- | --- | --- | --- | --- |
| [HyperFrames](https://github.com/heygen-com/hyperframes) | HTML/CSS/JS-based code video and agent skill ecosystem, migratable from Remotion with frame-by-frame verification. | 89,564 | 3,965 | 2026-11-24 | 99.6 |
| [Concat](https://github.com/jub0t/Concat) | Local-first cross-platform multitrack editor with subtitles, TTS, background removal, keyframes, effects and 4K export. | 19,997 | 1,677 | 2026-11-25 | 94.4 |
| [OpenMontage](https://github.com/OpenMontageInc/OpenMontage) | Multi-pipeline video production system for coding agents covering research, scripts, assets, voiceover, subtitles and rendering. | 83,059 | 272 | 2026-11-16 | 93.6 |
| [OpenMotion](https://github.com/nexu-io/openmotion) | Reference-video cloning and branded motion workbench for local coding agents, with Motion.md, a visual timeline and MP4 export. | 16,018 | 758 | 2026-11-24 | 93.6 |
| [FFmpeg Skill](https://github.com/kajisho5/ffmpeg-skill) | CLI and MCP giving coding agents local FFmpeg cutting, subtitles, format export and output checks. | 10,672 | 966 | 2026-11-24 | 92.0 |
| [Jellyfish](https://github.com/Forget-C/Jellyfish) | AI short-drama production workbench covering script breakdown, storyboards, character and scene asset management, shot generation and export. | 7,311 | 1,665 | 2026-11-23 | 90.4 |
| [yt-dlp](https://github.com/yt-dlp/yt-dlp) | Feature-rich command-line audio/video downloader supporting a large number of sites. | 210,460 | 81 | 2026-11-24 | 89.7 |
| [OpenFilm](https://github.com/openfilm/openfilm) | Lets coding agents create, inspect, edit and render videos in code, with an editable interface. | 9,289 | 298 | 2026-11-23 | 88.4 |
| [Clypra](https://github.com/AIEraDev/Clypra) | Rust/Tauri/React hardware-accelerated cross-platform video editor. | 3,374 | 1,916 | 2026-11-22 | 87.5 |
| [Claude Code Video Toolkit](https://github.com/digitalsamba/claude-code-video-toolkit) | Skills, templates, commands and tools for Claude Code covering scripts, voiceover, music, image and video generation, QA, rendering and publishing, portable to Codex and Kiro CLI. | 2,751 | 537 | 2026-11-24 | 87.5 |
| [CozyClay](https://github.com/HaD0Yun/CozyClay) | In-browser scene blocking, character staging, shot cutting and AI video previs tool. | 2,026 | 2,169 | 2026-11-24 | 86.3 |
| [Manim Community](https://github.com/ManimCommunity/manim) | Video engine for programmatic math and explainer animations in Python. | 42,881 | 78 | 2026-11-23 | 86.3 |

## Category index

`★User reference` marks projects provided directly by the user. Models, editors, Skills, CLIs and benchmarks are categorized separately.

| Category | Count | Top projects by maintenance rank |
| --- | --- | --- |
| Video editors and production workbenches | 19 | Concat, Jellyfish, Clypra |
| Agent video production and automation | 9 | Hypit, OpenMontage, OpenMotion |
| Knowledge shorts, clipping and explainers | 10 | NeonClipping, Clipmint, ChrisHKAI Video |
| Agent Skills, MCP and editing tools | 16 | FFmpeg Skill, Claude Code Video Toolkit, Video Shotcraft |
| Code-to-video and motion graphics | 9 | HyperFrames, Remotion, raea |
| Animation, 3D and coding building blocks | 15 | Godot, three.js, Motion |
| ComfyUI and open-source video generation | 9 | VRGameDevGirl AI Video Builder, LTX-Video, HunyuanVideo |
| Digital humans, portrait animation and lip sync | 5 | LiveTalking, MuseTalk, LivePortrait |
| Download, capture, transcoding and media CLIs | 8 | FFmpeg, yt-dlp, Streamlink |
| Benchmarks, research and external indexes | 8 | Aurora / AgentEdit-Bench, Awesome AI Video for Creators, CutCraft Bench |
| Historical and restricted versions | 1 | Palmier Pro |

### Video editors and production workbenches

| Project | Positioning | Stars | 90-day commits | Last commit (UTC) | Maintenance score | License |
| --- | --- | --- | --- | --- | --- | --- |
| [Concat](https://github.com/jub0t/Concat) · ★User reference | Local-first cross-platform multitrack editor with subtitles, TTS, background removal, keyframes, effects and 4K export. | 19,997 | 1,677 | 2026-11-25 | 94.4 | AGPL-3.0 |
| [Jellyfish](https://github.com/Forget-C/Jellyfish) | AI short-drama production workbench covering script breakdown, storyboards, character and scene asset management, shot generation and export. | 7,311 | 1,665 | 2026-11-23 | 90.4 | Apache-2.0 |
| [Clypra](https://github.com/AIEraDev/Clypra) · ★User reference | Rust/Tauri/React hardware-accelerated cross-platform video editor. | 3,374 | 1,916 | 2026-11-22 | 87.5 | MIT |
| [CozyClay](https://github.com/HaD0Yun/CozyClay) · ★User reference | In-browser scene blocking, character staging, shot cutting and AI video previs tool. | 2,026 | 2,169 | 2026-11-24 | 86.3 | AGPL-3.0 |
| [Huobao Drama](https://github.com/chatfire-AI/huobao-drama) · License caution | Web/desktop platform that turns a one-line idea or a pasted novel into rewritten script, images, storyboard videos, voiceover, subtitles and a finished short drama, orchestrated by a Mastra agent backend with UI-editable skills. | 17,971 | 108 | 2026-11-21 | 84.4 | CC BY-NC-SA-4.0 (no commercial use) |
| [OpenChatCut](https://github.com/0xsline/OpenChatCut) · ★User reference | Local-first conversational AI video editor with a multitrack timeline, Agent Skills, MCP and Remotion rendering. | 3,310 | 403 | 2026-11-12 | 83.7 | AGPL-3.0 |
| [OpenDirector](https://github.com/ThinkFlowLab/OpenDirector) | Agent video creation workflow from conversation, canvas and asset organization through timeline export. | 437 | 348 | 2026-11-24 | 79.0 | Apache-2.0 |
| [AID Studio](https://github.com/shijue-aid/aid-studio) | Self-hostable AI workbench for comic dramas, short dramas and film/TV creation covering scripts, characters and scenes, storyboards, image and video generation, voiceover, infinite canvas and 3D previs. | 1,764 | 125 | 2026-11-22 | 77.6 | MIT |
| [CutVoke](https://github.com/frankShan001/CutVoke) | Local-first cross-platform open-source video editor with a built-in MCP server, letting agents such as Claude Code, Codex and Cursor edit alongside humans on one non-destructive multitrack timeline. | 45 | 505 | 2026-11-24 | 73.3 | MIT |
| [OpenReel Video](https://github.com/Augani/openreel-video) · ★User reference | Open-source timeline editor for browser and desktop with cutting, subtitles, mixing and watermark-free export. | 6,446 | 19 | 2026-11-23 | 71.9 | MIT |
| [AI Video Production Editor](https://github.com/LudwigKienle/ai-video-production-editor) · ★User reference | Local workbench covering script, directing, storyboarding and shot generation through editing, grading and export. | 194 | 144 | 2026-11-20 | 70.1 | GPL-3.0 |
| [MakeMyClip Editor](https://github.com/MakeMyClip/editor) | Wraps FFmpeg editing in a local browser timeline, CLI, MCP and Skill. | 36 | 153 | 2026-11-16 | 63.6 | MIT |
| [OpenKatana](https://github.com/rk0neki/OpenKatana) | Agent-driven studio, CLI, MCP and ComfyUI video editing engine. | 85 | 126 | 2026-11-04 | 62.5 | Apache-2.0 |
| [OpenScene](https://github.com/Theorvane/OpenScene) | Local desktop video editor that lets AI agents operate the timeline, generate media and export. | 11 | 113 | 2026-11-24 | 60.3 | MIT |
| [Waoowaoo](https://github.com/waooAI/waoowaoo) · License caution | AI image and video creation workbench that manages reference media, generates content and merges clips via a canvas and an Assistant. | 14,979 | 6 | 2026-09-21 | 56.6 | Elastic License 2.0 |
| [SeeCut](https://github.com/YeJe-cpu/SeeCut) · ★User reference · License caution | Skill workspace where a coding agent understands, cuts, renders and visually QA-checks talking-head shorts. | 487 | 11 | 2026-10-30 | 54.3 | PolyForm Noncommercial-1.0.0 |
| [ScriptCut](https://github.com/FernandoAbishai/ScriptCut) | Edit the transcript to cut locally, package shorts and export for social media. | 23 | 62 | 2026-10-14 | 50.1 | AGPL-3.0 |
| [Cutline](https://github.com/Aepzie/cutline) | Browser timeline editor with a first-class MCP interface for live agent operation. | 1 | 109 | 2026-10-16 | 45.0 | MIT |
| [Moyin Creator](https://github.com/MemeCalculate/moyin-creator) · License caution | Electron desktop tool for AI film/TV production that chains a five-stage pipeline — script → characters → scenes → directing → Seedance 2.0 — to batch-produce short dramas and anime series. | 4,871 | 2 | 2026-08-27 | 44.9 | AGPL-3.0 + commercial dual license |

### Agent video production and automation

| Project | Positioning | Stars | 90-day commits | Last commit (UTC) | Maintenance score | License |
| --- | --- | --- | --- | --- | --- | --- |
| [Hypit](https://github.com/hypit-ai/hypit) · License caution | Lets coding agents clone reference videos into editable, repeatable full workflows and batch-generate content variants. | 31,391 | 783 | 2026-11-24 | 95.8 | Hypit Open Source License (modified Apache-2.0) |
| [OpenMontage](https://github.com/OpenMontageInc/OpenMontage) | Multi-pipeline video production system for coding agents covering research, scripts, assets, voiceover, subtitles and rendering. | 83,059 | 272 | 2026-11-16 | 93.6 | AGPL-3.0 |
| [OpenMotion](https://github.com/nexu-io/openmotion) | Reference-video cloning and branded motion workbench for local coding agents, with Motion.md, a visual timeline and MP4 export. | 16,018 | 758 | 2026-11-24 | 93.6 | Apache-2.0 |
| [OpenFilm](https://github.com/openfilm/openfilm) | Lets coding agents create, inspect, edit and render videos in code, with an editable interface. | 9,289 | 298 | 2026-11-23 | 88.4 | MIT |
| [Rea Video](https://github.com/JuneYaooo/rea-video) · ★User reference | Reverse-analyzes a video's live, AI and code components and outputs a shot-level replication plan and VIDEO.md. | 12,996 | 215 | 2026-11-24 | 88.1 | Apache-2.0 |
| [Video Autopilot Kit](https://github.com/Hao0321/video-autopilot-kit) · ★User reference | Automation framework for video planning, auditing, review and learning from results. | 2,358 | 51 | 2026-11-13 | 71.1 | MIT |
| [Video Use](https://github.com/browser-use/video-use) | Editing, subtitles, grading, motion overlays and output checks on raw footage via a coding agent plus FFmpeg. | 31,531 | 5 | 2026-10-08 | 60.9 | MIT |
| [Video Director](https://github.com/win4r/video-director) · ★User reference | Guides Claude Code to plan, render and check short films with HTML/Canvas/SVG/Three.js/GSAP/Remotion. | 528 | 19 | 2026-11-07 | 59.2 | MIT |
| [WeVisCut](https://github.com/Tencent/WeVisCut) | Turns knowledge articles or narration scripts into multi-minute videos through planning, media retrieval, editing, checking and repair. | 114 | 29 | 2026-10-30 | 54.4 | Apache-2.0 |

### Knowledge shorts, clipping and explainers

| Project | Positioning | Stars | 90-day commits | Last commit (UTC) | Maintenance score | License |
| --- | --- | --- | --- | --- | --- | --- |
| [NeonClipping](https://github.com/iamajmeena/neonclipping) | Paste a link to cut long YouTube/Twitch/Kick videos or your own MP4s locally into 9:16 clips with burned-in subtitles, titles and hooks. | 2,482 | 89 | 2026-11-24 | 77.4 | MIT |
| [Clipmint](https://github.com/kleZ799/clipmint) | Turns podcasts, interviews, tutorials and VODs into subtitled vertical Shorts/Reels/TikToks. | 68 | 620 | 2026-11-24 | 74.5 | MIT |
| [ChrisHKAI Video](https://github.com/ChrisHKAI/ChrisHKAI-Video) · ★User reference | Coding-agent Skill organizing a creator's public materials into 3D toy-style short films. | 162 | 198 | 2026-11-24 | 72.4 | MIT |
| [Lanshu AI Presenter Video](https://github.com/cclank/lanshu-create-ai-presenter-video) · ★User reference | Agent Skill turning a topic or script into a verified digital-human/stylized explainer video. | 3,079 | 16 | 2026-10-11 | 59.2 | MIT |
| [Claude Animated Shorts](https://github.com/mromidev/claude-animated-shorts) · ★User reference | Skill for vertical animated story shorts made with Three.js, Remotion, score and sound effects. | 4,811 | 2 | 2026-11-01 | 54.8 | MIT |
| [Vibe Knowledge](https://github.com/andyhuo520/vibe-knowledge) · ★User reference | Knowledge-short Skill from fact-checking and script writing, voiceover and code-to-video to QA and release packages. | 805 | 3 | 2026-10-28 | 49.5 | MIT |
| [Vox Director](https://github.com/alisa0808/vox-director) | End-to-end agent Skill from topic to Vox-style paper-collage explainer/ad videos. | 3,127 | 1 | 2026-10-05 | 46.2 | MIT |
| [Video to Shorts Skill](https://github.com/social-media-skills/video-to-shorts-skill) | Lets an agent turn long videos or podcasts into vertical shorts with word-level captions and optional publishing. | 4 | 3 | 2026-11-11 | 35.0 | MIT |
| [Pixelle-Video](https://github.com/ATH-MaaS/Pixelle-Video) | Generates copy, images or video, voiceover and composited shorts from a topic, with ComfyUI workflows and media APIs. | 30,491 | 0 | 2026-06-14 | 39.9 | Apache-2.0 |
| [Atlas Explainer](https://github.com/AtlasCloudAI/atlas-explainer) | Skill/CLI generating a voiceover papercraft-style explainer video from one topic. | 3 | 0 | 2026-07-10 | 10.2 | MIT |

### Agent Skills, MCP and editing tools

| Project | Positioning | Stars | 90-day commits | Last commit (UTC) | Maintenance score | License |
| --- | --- | --- | --- | --- | --- | --- |
| [FFmpeg Skill](https://github.com/kajisho5/ffmpeg-skill) | CLI and MCP giving coding agents local FFmpeg cutting, subtitles, format export and output checks. | 10,672 | 966 | 2026-11-24 | 92.0 | MIT |
| [Claude Code Video Toolkit](https://github.com/digitalsamba/claude-code-video-toolkit) | Skills, templates, commands and tools for Claude Code covering scripts, voiceover, music, image and video generation, QA, rendering and publishing, portable to Codex and Kiro CLI. | 2,751 | 537 | 2026-11-24 | 87.5 | MIT |
| [Video Shotcraft](https://github.com/Vincentwei1021/video-shotcraft) · ★User reference | Shot recipes, storyboards, Remotion animation, beat editing and frame-by-frame checks for agents. | 22,444 | 54 | 2026-11-21 | 81.5 | Apache-2.0 |
| [Kinocut](https://github.com/KyaniteLabs/kinocut) | Local video editing MCP/Python/CLI with guardrails, preflight checks, receipts and quality gates. | 280 | 659 | 2026-11-24 | 79.5 | Apache-2.0 |
| [Remotion Agent Skills](https://github.com/remotion-dev/skills) · License caution | Official Skills for coding agents to create, preview and render Remotion videos. | 7,954 | 31 | 2026-11-24 | 75.6 | License unverified |
| [Manju Laoli Skill](https://github.com/lixiaoxiao9888-create/manju-laoli-skill) | OpenClaw skill suite for AI comic dramas and short dramas covering scripts, asset locking, storyboards, fight scenes, Seedance prompting and machine checks. | 3,081 | 50 | 2026-11-19 | 73.5 | MIT |
| [pixelfx](https://github.com/patch-gg/pixelfx) · License caution | Library of 244 code-drawn pixel effects and animations with a Claude Code effect-generation skill plus sprite-sheet and GIF/MP4 export tools. | 9,055 | 10 | 2026-11-12 | 66.9 | MIT (code and effects) + Patch Pixel font excluded |
| [Wallstreet Explainer](https://github.com/HeyChengC/wallstreet-explainer) · License caution | Coding-agent Skill for Wall-Street-style finance/tech explainer shorts with style language, graphic component templates, and footage-finding, screenshot, voiceover, keying, rendering and mixing scripts. | 1,312 | 16 | 2026-11-20 | 64.7 | MIT (code and docs) + third-party sample assets excluded |
| [ReelBench Skills](https://github.com/eternityspring/reelbench-skills) · ★User reference | Video analysis, cloning and production skill set for Claude Code/Codex. | 1,253 | 21 | 2026-11-09 | 63.3 | Apache-2.0 |
| [Video Agent Skills](https://github.com/Melvynx/video-agent-skills) | Organizes scripts, research, editing, translation and publishing for shorts/YouTube via Markdown skills. | 211 | 26 | 2026-11-06 | 57.5 | MIT |
| [HyperFrames Motion Library](https://github.com/nutllwhy/hyperframes-motion-library) · ★User reference | Local motion template and parameterized asset library built on HyperFrames. | 326 | 2 | 2026-10-28 | 44.8 | MIT |
| [Video Editing Skill](https://github.com/social-media-skills/video-editing-skill) | Runs the first editing pass and caption handling for talking heads, courses, interviews and vlogs. | 10 | 3 | 2026-11-11 | 37.7 | MIT |
| [GSAP Skills](https://github.com/greensock/gsap-skills) | Official Agent Skills teaching coding agents the GSAP timeline, motion and plugins. | 19,019 | 0 | 2026-04-21 | 36.5 | MIT |
| [Narrator AI CLI Skill](https://github.com/NarratorAI-Studio/narrator-ai-cli-skill) · ★User reference | Guides an agent to drive narrator-ai-cli for automated film-commentary videos. | 3,323 | 0 | 2026-07-05 | 33.3 | MIT |
| [OpenClip Agent Skills](https://github.com/OpenClip-App/agent-skills) | Agent skills for long-video clipping, transcription, conversion, thumbnails, cutouts and UGC creative. | 1 | 0 | 2026-08-07 | 9.8 | MIT |
| [MCP Video Editing](https://github.com/mfortne/mcp-video-editing) | Wraps FFmpeg, HyperFrames and local reusable pipelines in an MCP, Python library and CLI. | 2 | 0 | 2026-06-04 | 7.5 | Apache-2.0 |

### Code-to-video and motion graphics

| Project | Positioning | Stars | 90-day commits | Last commit (UTC) | Maintenance score | License |
| --- | --- | --- | --- | --- | --- | --- |
| [HyperFrames](https://github.com/heygen-com/hyperframes) | HTML/CSS/JS-based code video and agent skill ecosystem, migratable from Remotion with frame-by-frame verification. | 89,564 | 3,965 | 2026-11-24 | 99.6 | Apache-2.0 |
| [Remotion](https://github.com/remotion-dev/remotion) · License caution | Base framework for creating and rendering video in code with React/TypeScript. | 75,476 | 6,717 | 2026-11-24 | 99.0 | Remotion License |
| [raea](https://github.com/shinyobjectz/raea) · License caution | Engine and desktop agent workbench for writing video, motion, 3D and games in React/TypeScript, rendered on the local GPU. | 5,002 | 1,457 | 2026-11-24 | 89.3 | FSL-1.1-ALv2 |
| [Lemo Opuscar](https://github.com/lemomo-ai/lemo-opuscar) · License caution | Cinematic style, examples and STYLE.md guidance for coding agents making video in code. | 20,684 | 148 | 2026-11-23 | 87.2 | MIT code + CC BY-NC docs (additional license) |
| [Manim Community](https://github.com/ManimCommunity/manim) | Video engine for programmatic math and explainer animations in Python. | 42,881 | 78 | 2026-11-23 | 86.3 | MIT |
| [GiveMotion](https://github.com/givemotion/givemotion) | Code video engine where agents write HTML/CSS, preview, check and render MP4s. | 92 | 243 | 2026-11-19 | 70.1 | MIT |
| [Manim](https://github.com/3b1b/manim) | Python animation engine for math explainers. | 96,918 | 1 | 2026-09-09 | 54.5 | MIT |
| [SenseNova Code2Video](https://github.com/OpenSenseNova/SenseNova-6.8-Code2Video) · ★User reference · License caution | Small open model that generates executable code rendered into short videos. | 767 | 2 | 2026-10-27 | 47.5 | Unverified |
| [Motion Canvas](https://github.com/motion-canvas/motion-canvas) | Creates animations, explainers and motion graphics with TypeScript and generator functions. | 20,204 | 0 | 2026-07-02 | 39.4 | MIT |

### Animation, 3D and coding building blocks

| Project | Positioning | Stars | 90-day commits | Last commit (UTC) | Maintenance score | License |
| --- | --- | --- | --- | --- | --- | --- |
| [Godot](https://github.com/godotengine/godot) | Open-source game engine for building 2D/3D scenes, interaction and animation. | 120,738 | 1,923 | 2026-11-24 | 100.0 | MIT |
| [three.js](https://github.com/mrdoob/three.js) | JavaScript 3D scene and rendering library that supplies 3D content for code motion. | 119,308 | 874 | 2026-11-24 | 99.9 | MIT |
| [Motion](https://github.com/motiondivision/motion) | UI and layout animation library for JavaScript, React and Vue. | 35,531 | 1,390 | 2026-11-24 | 96.3 | MIT |
| [Blender](https://github.com/blender/blender) | 3D creation suite covering modeling, rigging, animation, rendering, compositing and video editing. | 22,468 | 3,310 | 2026-11-25 | 94.8 | GPL-2.0-or-later |
| [Babylon.js](https://github.com/BabylonJS/Babylon.js) | JavaScript 3D scene, game and rendering engine usable as code-motion infrastructure. | 26,439 | 342 | 2026-11-24 | 93.2 | Apache-2.0 |
| [Konva](https://github.com/konvajs/konva) | 2D Canvas scene graph with object interaction, transforms, animation and export. | 15,012 | 217 | 2026-11-23 | 88.4 | MIT |
| [Two.js](https://github.com/jonobr1/two.js) | 2D shapes and animated scenes via WebGL, Canvas or SVG. | 8,762 | 47 | 2026-11-17 | 76.3 | MIT |
| [Shifty](https://github.com/jeremyckahn/shifty) | TypeScript tweening engine with easings and playback control. | 1,598 | 14 | 2026-11-14 | 63.2 | MIT |
| [Ola](https://github.com/franciscop/ola) | Lightweight animation library for real-time numeric smoothing. | 1,869 | 3 | 2026-10-24 | 51.6 | MIT |
| [Anime.js](https://github.com/juliangarnier/anime) | Timeline animation of CSS, SVG, DOM and JavaScript properties. | 75,039 | 0 | 2026-08-09 | 46.6 | MIT |
| [Proton](https://github.com/drawcall/Proton) | JavaScript particle animation library for fire, fireworks, explosions and similar effects. | 2,531 | 0 | 2026-03-06 | 28.6 | MIT |
| [Lottie Web](https://github.com/airbnb/lottie-web) | Parses and renders exported Lottie vector animations in the web. | 32,572 | 0 | 2024-11-19 | 36.1 | MIT |
| [TweenJS](https://github.com/CreateJS/TweenJS) | Tweens and chained playback for JavaScript numbers and CSS properties. | 3,578 | 0 | 2021-03-27 | 28.4 | MIT |
| [LUME](https://github.com/lume/lume) | Builds interactive 2D and 3D graphic scenes using HTML elements. | 1,576 | 0 | 2025-10-14 | 25.9 | MIT |
| [gifenc](https://github.com/mattdesl/gifenc) | Encodes GIFs with animation and transparency in the browser or Node.js. | 382 | 0 | 2024-09-19 | 20.7 | MIT |

### ComfyUI and open-source video generation

| Project | Positioning | Stars | 90-day commits | Last commit (UTC) | Maintenance score | License |
| --- | --- | --- | --- | --- | --- | --- |
| [VRGameDevGirl AI Video Builder](https://github.com/vrgamegirl19/comfyui-vrgamedevgirl) · ★User reference · License caution | ComfyUI workflow suite managing planning, prompts, generation, pacing, review and final assembly per scenario. | 904 | 677 | 2026-11-24 | 83.6 | VRGameDevGirl Community and Commercial License |
| [LTX-Video](https://github.com/Lightricks/LTX-Video) | Open video models and inference tools for text/image-to-video and audio-visual generation. | 11,479 | 2 | 2026-11-02 | 58.2 | Apache-2.0 |
| [HunyuanVideo](https://github.com/Tencent-Hunyuan/HunyuanVideo) · License caution | Tencent's open large video-generation foundation model and inference framework. | 12,827 | 3 | 2026-10-08 | 55.4 | Tencent Hunyuan Community License |
| [Wan2.2](https://github.com/Wan-Video/Wan2.2) | Alibaba's Wan family of open video generation models covering text/image-to-video and related tasks. | 18,891 | 2 | 2026-09-21 | 52.6 | Apache-2.0 |
| [Mochi](https://github.com/genmoai/mochi) | Genmo's open video generation model and inference code. | 3,767 | 2 | 2026-10-22 | 52.1 | Apache-2.0 |
| [Open-Sora](https://github.com/hpcaitech/Open-Sora) | Open-source efficient video generation training and inference framework. | 29,949 | 0 | 2026-04-09 | 37.8 | Apache-2.0 |
| [Bernini](https://github.com/bytedance/Bernini) | Video generation and editing research framework combining a semantic planner and a DiT renderer. | 1,373 | 0 | 2026-08-13 | 33.0 | Apache-2.0 |
| [HunyuanVideo-I2V](https://github.com/Tencent-Hunyuan/HunyuanVideo-I2V) · License caution | Customizable image-to-video framework built on HunyuanVideo. | 1,858 | 0 | 2026-04-07 | 28.1 | Tencent Hunyuan Community License |
| [CogVideo / CogVideoX](https://github.com/zai-org/CogVideo) | Open text/image-to-video models and inference code. | 13,229 | 0 | 2025-11-04 | 33.3 | Apache-2.0 |

### Digital humans, portrait animation and lip sync

| Project | Positioning | Stars | 90-day commits | Last commit (UTC) | Maintenance score | License |
| --- | --- | --- | --- | --- | --- | --- |
| [LiveTalking](https://github.com/lipku/LiveTalking) | Real-time interactive streaming system combining multiple digital-human backends. | 11,131 | 8 | 2026-10-20 | 61.5 | Apache-2.0 |
| [MuseTalk](https://github.com/TMElyralab/MuseTalk) | Audio-driven virtual human model for real-time high-quality lip sync. | 7,031 | 1 | 2026-11-19 | 58.2 | MIT |
| [LivePortrait](https://github.com/KlingAIResearch/LivePortrait) | Efficient portrait animation, retargeting and control framework. | 19,566 | 0 | 2026-06-01 | 37.9 | MIT |
| [SadTalker](https://github.com/OpenTalker/SadTalker) | Generates talking-head video from a single portrait and audio. | 14,220 | 0 | 2023-10-10 | 33.2 | Apache-2.0 |
| [Wav2Lip](https://github.com/Rudrabha/Wav2Lip) · License caution | Classic audio-video lip-sync research implementation. | 13,284 | 0 | 2025-06-22 | 33.1 | Personal/research/non-commercial license |

### Download, capture, transcoding and media CLIs

| Project | Positioning | Stars | 90-day commits | Last commit (UTC) | Maintenance score | License |
| --- | --- | --- | --- | --- | --- | --- |
| [FFmpeg](https://github.com/FFmpeg/FFmpeg) · License caution | Low-level toolchain for transcoding, filtering, muxing, compositing and stream processing. | 68,093 | 2,986 | 2026-11-24 | 98.7 | LGPL-2.1+; GPL-2.0+ once GPL components are enabled |
| [yt-dlp](https://github.com/yt-dlp/yt-dlp) | Feature-rich command-line audio/video downloader supporting a large number of sites. | 210,460 | 81 | 2026-11-24 | 89.7 | Unlicense |
| [Streamlink](https://github.com/streamlink/streamlink) | CLI that resolves online livestreams and pipes them to a local player. | 11,998 | 155 | 2026-11-18 | 84.4 | BSD-2-Clause |
| [Downvid](https://github.com/Downvid/downvid) · ★User reference | Cross-platform video download GUI/WebUI built on yt-dlp and FFmpeg. | 1,678 | 354 | 2026-11-11 | 80.4 | MIT |
| [VidBee](https://github.com/nexmoe/VidBee) | Downloads media, then runs local transcription, speaker labeling, summarization, translation and media chat. | 11,207 | 51 | 2026-11-21 | 78.6 | MIT |
| [cobalt](https://github.com/imputnet/cobalt) · License caution | Ad- and tracker-free media download web app and self-hostable API covering YouTube, TikTok, Instagram and more. | 47,172 | 0 | 2026-04-06 | 39.3 | AGPL-3.0 (api and the rest) + CC-BY-NC-SA-4.0 (web) |
| [Lux](https://github.com/iawia002/lux) | Multi-site video download CLI written in Go. | 31,857 | 0 | 2025-12-29 | 36.7 | MIT |
| [you-get](https://github.com/soimort/you-get) | Python command-line tool downloading media from web pages. | 56,849 | 0 | 2025-04-27 | 38.1 | MIT |

### Benchmarks, research and external indexes

| Project | Positioning | Stars | 90-day commits | Last commit (UTC) | Maintenance score | License |
| --- | --- | --- | --- | --- | --- | --- |
| [Aurora / AgentEdit-Bench](https://github.com/yeates/Aurora) | Unifies video editing through a tool-using agent and ships AgentEdit-Bench. | 461 | 4 | 2026-11-13 | 52.5 | MIT |
| [Awesome AI Video for Creators](https://github.com/sasateguh/awesome-ai-video-for-creators) | Organizes open-source editing, captioning, clipping, voiceover and code-video tools by creator workflow. | 19 | 15 | 2026-11-24 | 50.9 | CC0-1.0 |
| [CutCraft Bench](https://github.com/AlibabaResearch/cut-craft-bench) · License caution | Benchmarks professional editing-technique execution in multi-shot audio-video generation, with agent baselines. | 43 | 5 | 2026-09-14 | 34.5 | Unverified |
| [Awesome Video Editing](https://github.com/devanasolver/awesome-video-editing) | Curates open-source video editing tools, agent skills and usable media. | 5 | 2 | 2026-10-17 | 28.8 | CC0-1.0 |
| [Awesome AI Video](https://github.com/thoxakihiko/awesome-ai-video) | Curates text/image-to-video models, tools and resources. | 3 | 3 | 2026-09-27 | 25.7 | CC0-1.0 |
| [VEFX-Bench](https://github.com/Visko-Platform/VEFX-Bench) | Benchmarks instruction following and quality for general video editing and visual effects. | 177 | 0 | 2026-05-16 | 20.9 | Apache-2.0 |
| [EditVerse](https://github.com/adobe-research/EditVerse) · License caution | Image/video generation and editing research code plus EditVerseBench. | 140 | 0 | 2025-10-09 | 17.4 | Adobe Research License (some files) |
| [Video-Bench](https://github.com/Video-Bench/Video-Bench) | Organizes and runs multi-dimensional evaluations of video generation models. | 82 | 0 | 2025-06-09 | 15.4 | Apache-2.0 |

### Historical and restricted versions

| Project | Positioning | Stars | 90-day commits | Last commit (UTC) | Maintenance score | License |
| --- | --- | --- | --- | --- | --- | --- |
| [Palmier Pro](https://github.com/palmier-io/palmier-pro) · ★User reference · Archived/historical · License caution | AI-oriented video editor whose older sources were released under GPLv3. | 14,803 | 10 | 2026-11-20 | 70.5 | GPL-3.0 (source up to v0.7.6) / later binaries proprietary |

## How to choose

- Have footage and need to cut: see editors/workbenches or Skills/MCP.
- From topic and script to finished video: see Agent production and knowledge shorts.
- Motion graphics, product demos and data stories: see Code-to-video.
- Local diffusion generation: see ComfyUI and open models.
- Digital humans/talking heads: see portrait animation and lip sync, and check person consent first.
- Getting properly licensed media: see [CLI comparison](docs/cli-comparison.md).

Full boundaries in [project details](docs/projects.md); category definitions in [Scope and taxonomy](docs/taxonomy.md).

## Data and maintenance

- [Balanced, stars, activity and recent-commit rankings](docs/rankings.md)
- [Downvid and download/media CLI comparison](docs/cli-comparison.md)
- [Ranking method and limits](docs/methodology.md)
- [Search keywords, sources and coverage](docs/research.md)
- [Contributing guide](CONTRIBUTING.md)

```sh
python scripts/refresh_metrics.py
python scripts/build.py
python -m unittest discover -s tests -v
python scripts/build.py --check
```

## Licenses and acknowledgements

Original curation and scripts in this catalogue use the [MIT](LICENSE) license; linked projects, models, weights, media and fonts follow their own licenses. Source-available, non-commercial, community-model and conditional licenses keep their original boundaries.

Project discovery referenced external indexes such as [Awesome Video Editing](https://github.com/devanasolver/awesome-video-editing); every final entry was verified against its official repository.

The [change records](record/) keep each entry in the language used at verification time (Chinese), so the source and original wording of every decision stay auditable.
