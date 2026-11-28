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

**113 projects, of which 22 are user-reference projects and 91 were added in this round.** Feature verification: 2026-11-27; metrics snapshot: `2026-11-28T10:43:31+00:00` (UTC).

Within each category, projects are first tiered by maintenance status, then ranked by a blend of stars (40%), 90-day default-branch commits (35%) and recency of the last commit (25%). The maintenance score does not represent final-video quality, model capability, copyright safety or production readiness.

## Active core projects at a glance

Shows only core candidates with a verified open license and commits in the last 90 days; restricted-license projects, base models, research benchmarks and adjacent tools are excluded from this table.

| Project | Positioning | Stars | 90-day commits | Last commit (UTC) | Maintenance score |
| --- | --- | --- | --- | --- | --- |
| [HyperFrames](https://github.com/heygen-com/hyperframes) | HTML/CSS/JS-based code video and agent skill ecosystem, migratable from Remotion with frame-by-frame verification. | 91,752 | 4,168 | 2026-11-28 | 99.7 |
| [Concat](https://github.com/jub0t/Concat) | Local-first cross-platform multitrack editor with subtitles, TTS, background removal, keyframes, effects and 4K export. | 22,604 | 1,616 | 2026-11-27 | 94.5 |
| [OpenMotion](https://github.com/nexu-io/openmotion) | Reference-video cloning and branded motion workbench for local coding agents, with Motion.md, a visual timeline and MP4 export. | 17,054 | 857 | 2026-11-27 | 93.7 |
| [OpenMontage](https://github.com/OpenMontageInc/OpenMontage) | Multi-pipeline video production system for coding agents covering research, scripts, assets, voiceover, subtitles and rendering. | 83,959 | 267 | 2026-11-16 | 92.7 |
| [FFmpeg Skill](https://github.com/kajisho5/ffmpeg-skill) | CLI and MCP giving coding agents local FFmpeg cutting, subtitles, format export and output checks. | 12,100 | 1,044 | 2026-11-28 | 92.7 |
| [Jellyfish](https://github.com/Forget-C/Jellyfish) | AI short-drama production workbench covering script breakdown, storyboards, character and scene asset management, shot generation and export. | 7,428 | 1,955 | 2026-11-28 | 90.9 |
| [OpenFilm](https://github.com/openfilm/openfilm) | Lets coding agents create, inspect, edit and render videos in code, with an editable interface. | 9,664 | 307 | 2026-11-27 | 88.9 |
| [yt-dlp](https://github.com/yt-dlp/yt-dlp) | Feature-rich command-line audio/video downloader supporting a large number of sites. | 211,288 | 75 | 2026-11-24 | 88.4 |
| [Clypra](https://github.com/AIEraDev/Clypra) | Rust/Tauri/React hardware-accelerated cross-platform video editor. | 3,389 | 1,643 | 2026-11-28 | 88.2 |
| [Claude Code Video Toolkit](https://github.com/digitalsamba/claude-code-video-toolkit) | Skills, templates, commands and tools for Claude Code covering scripts, voiceover, music, image and video generation, QA, rendering and publishing, portable to Codex and Kiro CLI. | 2,813 | 550 | 2026-11-27 | 87.2 |
| [Manim Community](https://github.com/ManimCommunity/manim) | Video engine for programmatic math and explainer animations in Python. | 43,022 | 80 | 2026-11-26 | 86.3 |
| [CozyClay](https://github.com/HaD0Yun/CozyClay) | In-browser scene blocking, character staging, shot cutting and AI video previs tool. | 1,895 | 2,104 | 2026-11-28 | 86.2 |

## Category index

`★User reference` marks projects provided directly by the user. Models, editors, Skills, CLIs and benchmarks are categorized separately.

| Category | Count | Top projects by maintenance rank |
| --- | --- | --- |
| Video editors and production workbenches | 20 | Concat, Jellyfish, Clypra |
| Agent video production and automation | 9 | Hypit, OpenMotion, OpenMontage |
| Knowledge shorts, clipping and explainers | 10 | NeonClipping, Clipmint, ChrisHKAI Video |
| Agent Skills, MCP and editing tools | 19 | FFmpeg Skill, Claude Code Video Toolkit, Video Shotcraft |
| Code-to-video and motion graphics | 9 | HyperFrames, Remotion, raea |
| Animation, 3D and coding building blocks | 15 | three.js, Godot, Motion |
| ComfyUI and open-source video generation | 9 | VRGameDevGirl AI Video Builder, LTX-Video, HunyuanVideo |
| Digital humans, portrait animation and lip sync | 5 | LiveTalking, MuseTalk, LivePortrait |
| Download, capture, transcoding and media CLIs | 8 | FFmpeg, yt-dlp, Streamlink |
| Benchmarks, research and external indexes | 8 | Aurora / AgentEdit-Bench, Awesome AI Video for Creators, CutCraft Bench |
| Historical and restricted versions | 1 | Palmier Pro |

### Video editors and production workbenches

| Project | Positioning | Stars | 90-day commits | Last commit (UTC) | Maintenance score | License |
| --- | --- | --- | --- | --- | --- | --- |
| [Concat](https://github.com/jub0t/Concat) · ★User reference | Local-first cross-platform multitrack editor with subtitles, TTS, background removal, keyframes, effects and 4K export. | 22,604 | 1,616 | 2026-11-27 | 94.5 | AGPL-3.0 |
| [Jellyfish](https://github.com/Forget-C/Jellyfish) | AI short-drama production workbench covering script breakdown, storyboards, character and scene asset management, shot generation and export. | 7,428 | 1,955 | 2026-11-28 | 90.9 | Apache-2.0 |
| [Clypra](https://github.com/AIEraDev/Clypra) · ★User reference | Rust/Tauri/React hardware-accelerated cross-platform video editor. | 3,389 | 1,643 | 2026-11-28 | 88.2 | MIT |
| [CozyClay](https://github.com/HaD0Yun/CozyClay) · ★User reference | In-browser scene blocking, character staging, shot cutting and AI video previs tool. | 1,895 | 2,104 | 2026-11-28 | 86.2 | AGPL-3.0 |
| [Editroom](https://github.com/robbietilton/Editroom) · License caution | Native Swift video editor for macOS: realtime 4K without proxies, built-in grading, speed ramps, transitions, audio mixing and loudness-target exports, plus natural-language cuts through Claude, ChatGPT or an on-device model. | 1,070 | 457 | 2026-11-28 | 83.7 | MIT (app) + bundled FFmpeg LGPL-2.1+, Sparkle MIT |
| [Huobao Drama](https://github.com/chatfire-AI/huobao-drama) · License caution | Web/desktop platform that turns a one-line idea or a pasted novel into rewritten script, images, storyboard videos, voiceover, subtitles and a finished short drama, orchestrated by a Mastra agent backend with UI-editable skills. | 18,064 | 102 | 2026-11-21 | 83.2 | CC BY-NC-SA-4.0 (no commercial use) |
| [OpenChatCut](https://github.com/0xsline/OpenChatCut) · ★User reference | Local-first conversational AI video editor with a multitrack timeline, Agent Skills, MCP and Remotion rendering. | 3,385 | 379 | 2026-11-12 | 82.6 | AGPL-3.0 |
| [OpenDirector](https://github.com/ThinkFlowLab/OpenDirector) | Agent video creation workflow from conversation, canvas and asset organization through timeline export. | 476 | 373 | 2026-11-28 | 79.7 | Apache-2.0 |
| [AID Studio](https://github.com/shijue-aid/aid-studio) | Self-hostable AI workbench for comic dramas, short dramas and film/TV creation covering scripts, characters and scenes, storyboards, image and video generation, voiceover, infinite canvas and 3D previs. | 1,845 | 114 | 2026-11-27 | 77.7 | MIT |
| [CutVoke](https://github.com/frankShan001/CutVoke) | Local-first cross-platform open-source video editor with a built-in MCP server, letting agents such as Claude Code, Codex and Cursor edit alongside humans on one non-destructive multitrack timeline. | 53 | 557 | 2026-11-28 | 73.8 | MIT |
| [OpenReel Video](https://github.com/Augani/openreel-video) · ★User reference | Open-source timeline editor for browser and desktop with cutting, subtitles, mixing and watermark-free export. | 6,587 | 16 | 2026-11-28 | 71.4 | MIT |
| [AI Video Production Editor](https://github.com/LudwigKienle/ai-video-production-editor) · ★User reference | Local workbench covering script, directing, storyboarding and shot generation through editing, grading and export. | 196 | 144 | 2026-11-20 | 69.2 | GPL-3.0 |
| [MakeMyClip Editor](https://github.com/MakeMyClip/editor) | Wraps FFmpeg editing in a local browser timeline, CLI, MCP and Skill. | 57 | 153 | 2026-11-16 | 64.3 | MIT |
| [OpenKatana](https://github.com/rk0neki/OpenKatana) | Agent-driven studio, CLI, MCP and ComfyUI video editing engine. | 90 | 126 | 2026-11-04 | 62.0 | Apache-2.0 |
| [OpenScene](https://github.com/Theorvane/OpenScene) | Local desktop video editor that lets AI agents operate the timeline, generate media and export. | 11 | 112 | 2026-11-28 | 60.2 | MIT |
| [ScriptCut](https://github.com/FernandoAbishai/ScriptCut) | Edit the transcript to cut locally, package shorts and export for social media. | 23 | 66 | 2026-11-27 | 59.4 | AGPL-3.0 |
| [Waoowaoo](https://github.com/waooAI/waoowaoo) · License caution | AI image and video creation workbench that manages reference media, generates content and merges clips via a canvas and an Assistant. | 15,005 | 6 | 2026-09-21 | 56.1 | Elastic License 2.0 |
| [SeeCut](https://github.com/YeJe-cpu/SeeCut) · ★User reference · License caution | Skill workspace where a coding agent understands, cuts, renders and visually QA-checks talking-head shorts. | 494 | 11 | 2026-10-30 | 53.6 | PolyForm Noncommercial-1.0.0 |
| [Cutline](https://github.com/Aepzie/cutline) | Browser timeline editor with a first-class MCP interface for live agent operation. | 1 | 109 | 2026-10-16 | 44.4 | MIT |
| [Moyin Creator](https://github.com/MemeCalculate/moyin-creator) · License caution | Electron desktop tool for AI film/TV production that chains a five-stage pipeline — script → characters → scenes → directing → Seedance 2.0 — to batch-produce short dramas and anime series. | 4,888 | 0 | 2026-08-27 | 38.4 | AGPL-3.0 + commercial dual license |

### Agent video production and automation

| Project | Positioning | Stars | 90-day commits | Last commit (UTC) | Maintenance score | License |
| --- | --- | --- | --- | --- | --- | --- |
| [Hypit](https://github.com/hypit-ai/hypit) · License caution | Lets coding agents clone reference videos into editable, repeatable full workflows and batch-generate content variants. | 31,726 | 662 | 2026-11-25 | 95.1 | Hypit Open Source License (modified Apache-2.0) |
| [OpenMotion](https://github.com/nexu-io/openmotion) | Reference-video cloning and branded motion workbench for local coding agents, with Motion.md, a visual timeline and MP4 export. | 17,054 | 857 | 2026-11-27 | 93.7 | Apache-2.0 |
| [OpenMontage](https://github.com/OpenMontageInc/OpenMontage) | Multi-pipeline video production system for coding agents covering research, scripts, assets, voiceover, subtitles and rendering. | 83,959 | 267 | 2026-11-16 | 92.7 | AGPL-3.0 |
| [OpenFilm](https://github.com/openfilm/openfilm) | Lets coding agents create, inspect, edit and render videos in code, with an editable interface. | 9,664 | 307 | 2026-11-27 | 88.9 | MIT |
| [Rea Video](https://github.com/JuneYaooo/rea-video) · ★User reference | Reverse-analyzes a video's live, AI and code components and outputs a shot-level replication plan and VIDEO.md. | 14,099 | 222 | 2026-11-28 | 88.5 | Apache-2.0 |
| [Video Autopilot Kit](https://github.com/Hao0321/video-autopilot-kit) · ★User reference | Automation framework for video planning, auditing, review and learning from results. | 2,374 | 33 | 2026-11-13 | 68.0 | MIT |
| [Video Director](https://github.com/win4r/video-director) · ★User reference | Guides Claude Code to plan, render and check short films with HTML/Canvas/SVG/Three.js/GSAP/Remotion. | 551 | 20 | 2026-11-26 | 63.5 | MIT |
| [Video Use](https://github.com/browser-use/video-use) | Editing, subtitles, grading, motion overlays and output checks on raw footage via a coding agent plus FFmpeg. | 31,689 | 2 | 2026-10-08 | 56.5 | MIT |
| [WeVisCut](https://github.com/Tencent/WeVisCut) | Turns knowledge articles or narration scripts into multi-minute videos through planning, media retrieval, editing, checking and repair. | 117 | 27 | 2026-10-30 | 53.4 | Apache-2.0 |

### Knowledge shorts, clipping and explainers

| Project | Positioning | Stars | 90-day commits | Last commit (UTC) | Maintenance score | License |
| --- | --- | --- | --- | --- | --- | --- |
| [NeonClipping](https://github.com/iamajmeena/neonclipping) | Paste a link to cut long YouTube/Twitch/Kick videos or your own MP4s locally into 9:16 clips with burned-in subtitles, titles and hooks. | 2,976 | 89 | 2026-11-24 | 77.1 | MIT |
| [Clipmint](https://github.com/kleZ799/clipmint) | Turns podcasts, interviews, tutorials and VODs into subtitled vertical Shorts/Reels/TikToks. | 73 | 615 | 2026-11-26 | 74.5 | MIT |
| [ChrisHKAI Video](https://github.com/ChrisHKAI/ChrisHKAI-Video) · ★User reference | Coding-agent Skill organizing a creator's public materials into 3D toy-style short films. | 169 | 208 | 2026-11-27 | 72.6 | MIT |
| [Lanshu AI Presenter Video](https://github.com/cclank/lanshu-create-ai-presenter-video) · ★User reference | Agent Skill turning a topic or script into a verified digital-human/stylized explainer video. | 3,086 | 17 | 2026-11-26 | 68.8 | MIT |
| [Claude Animated Shorts](https://github.com/mromidev/claude-animated-shorts) · ★User reference | Skill for vertical animated story shorts made with Three.js, Remotion, score and sound effects. | 5,265 | 2 | 2026-11-01 | 54.4 | MIT |
| [Vibe Knowledge](https://github.com/andyhuo520/vibe-knowledge) · ★User reference | Knowledge-short Skill from fact-checking and script writing, voiceover and code-to-video to QA and release packages. | 854 | 3 | 2026-10-28 | 49.0 | MIT |
| [Vox Director](https://github.com/alisa0808/vox-director) | End-to-end agent Skill from topic to Vox-style paper-collage explainer/ad videos. | 3,248 | 1 | 2026-10-05 | 45.8 | MIT |
| [Video to Shorts Skill](https://github.com/social-media-skills/video-to-shorts-skill) | Lets an agent turn long videos or podcasts into vertical shorts with word-level captions and optional publishing. | 4 | 3 | 2026-11-11 | 34.2 | MIT |
| [Pixelle-Video](https://github.com/ATH-MaaS/Pixelle-Video) | Generates copy, images or video, voiceover and composited shorts from a topic, with ComfyUI workflows and media APIs. | 30,583 | 0 | 2026-06-14 | 39.8 | Apache-2.0 |
| [Atlas Explainer](https://github.com/AtlasCloudAI/atlas-explainer) | Skill/CLI generating a voiceover papercraft-style explainer video from one topic. | 3 | 0 | 2026-07-10 | 10.0 | MIT |

### Agent Skills, MCP and editing tools

| Project | Positioning | Stars | 90-day commits | Last commit (UTC) | Maintenance score | License |
| --- | --- | --- | --- | --- | --- | --- |
| [FFmpeg Skill](https://github.com/kajisho5/ffmpeg-skill) | CLI and MCP giving coding agents local FFmpeg cutting, subtitles, format export and output checks. | 12,100 | 1,044 | 2026-11-28 | 92.7 | MIT |
| [Claude Code Video Toolkit](https://github.com/digitalsamba/claude-code-video-toolkit) | Skills, templates, commands and tools for Claude Code covering scripts, voiceover, music, image and video generation, QA, rendering and publishing, portable to Codex and Kiro CLI. | 2,813 | 550 | 2026-11-27 | 87.2 | MIT |
| [Video Shotcraft](https://github.com/Vincentwei1021/video-shotcraft) · ★User reference | Shot recipes, storyboards, Remotion animation, beat editing and frame-by-frame checks for agents. | 23,201 | 56 | 2026-11-27 | 82.5 | Apache-2.0 |
| [Remocn](https://github.com/Remocn/remocn) | Claude Code plugin, agent skill and MCP server for making Remotion videos from 935 MIT-licensed components: the agent plans a storyboard first, then writes the video. | 2,000 | 189 | 2026-11-27 | 80.7 | MIT |
| [Kinocut](https://github.com/KyaniteLabs/kinocut) | Local video editing MCP/Python/CLI with guardrails, preflight checks, receipts and quality gates. | 287 | 698 | 2026-11-25 | 78.8 | Apache-2.0 |
| [Manju Laoli Skill](https://github.com/lixiaoxiao9888-create/manju-laoli-skill) | OpenClaw skill suite for AI comic dramas and short dramas covering scripts, asset locking, storyboards, fight scenes, Seedance prompting and machine checks. | 3,353 | 53 | 2026-11-26 | 75.1 | MIT |
| [Remotion Agent Skills](https://github.com/remotion-dev/skills) · License caution | Official Skills for coding agents to create, preview and render Remotion videos. | 8,212 | 31 | 2026-11-24 | 74.8 | License unverified |
| [pixelfx](https://github.com/patch-gg/pixelfx) · License caution | Library of 244 code-drawn pixel effects and animations with a Claude Code effect-generation skill plus sprite-sheet and GIF/MP4 export tools. | 9,699 | 10 | 2026-11-12 | 66.3 | MIT (code and effects) + Patch Pixel font excluded |
| [Wallstreet Explainer](https://github.com/HeyChengC/wallstreet-explainer) · License caution | Coding-agent Skill for Wall-Street-style finance/tech explainer shorts with style language, graphic component templates, and footage-finding, screenshot, voiceover, keying, rendering and mixing scripts. | 1,386 | 16 | 2026-11-20 | 64.0 | MIT (code and docs) + third-party sample assets excluded |
| [Awesome Motion Design Agent Skills](https://github.com/frankxai/awesome-motion-design-agent-skills) | Five installable SKILL.md motion workflows (including remotion-video-agent and web-motion-auditor) plus a curated index of GSAP, Motion, Remotion, Rive, Lottie and 3D tools. | 287 | 24 | 2026-11-28 | 62.8 | CC0-1.0 |
| [ReelBench Skills](https://github.com/eternityspring/reelbench-skills) · ★User reference | Video analysis, cloning and production skill set for Claude Code/Codex. | 1,263 | 21 | 2026-11-09 | 62.5 | Apache-2.0 |
| [Video Agent Skills](https://github.com/Melvynx/video-agent-skills) | Organizes scripts, research, editing, translation and publishing for shorts/YouTube via Markdown skills. | 223 | 27 | 2026-11-28 | 62.5 | MIT |
| [AI Filmmaking Camera Control (Seedance 2.5)](https://github.com/sirioberati/ai-filmmaking-camera-control-seedance-2-5) · License caution | 137 cinematic camera-move templates with a previs pipeline: three.js plus Remotion render striped-pill reference clips, ready-made prompts hand them to Seedance 2.5, and Tein MCP or API setup plus a cinematic-previs skill drive the work. | 425 | 5 | 2026-11-07 | 51.0 | MIT (code, prompts, notes, pill clips) + Remotion's own licence, Quaternius CC0, third-party material excluded |
| [HyperFrames Motion Library](https://github.com/nutllwhy/hyperframes-motion-library) · ★User reference | Local motion template and parameterized asset library built on HyperFrames. | 332 | 2 | 2026-10-28 | 44.1 | MIT |
| [Video Editing Skill](https://github.com/social-media-skills/video-editing-skill) | Runs the first editing pass and caption handling for talking heads, courses, interviews and vlogs. | 15 | 3 | 2026-11-11 | 38.2 | MIT |
| [GSAP Skills](https://github.com/greensock/gsap-skills) | Official Agent Skills teaching coding agents the GSAP timeline, motion and plugins. | 19,211 | 0 | 2026-04-21 | 36.4 | MIT |
| [Narrator AI CLI Skill](https://github.com/NarratorAI-Studio/narrator-ai-cli-skill) · ★User reference | Guides an agent to drive narrator-ai-cli for automated film-commentary videos. | 3,349 | 0 | 2026-07-05 | 33.1 | MIT |
| [OpenClip Agent Skills](https://github.com/OpenClip-App/agent-skills) | Agent skills for long-video clipping, transcription, conversion, thumbnails, cutouts and UGC creative. | 2 | 0 | 2026-08-07 | 10.9 | MIT |
| [MCP Video Editing](https://github.com/mfortne/mcp-video-editing) | Wraps FFmpeg, HyperFrames and local reusable pipelines in an MCP, Python library and CLI. | 2 | 0 | 2026-06-04 | 7.3 | Apache-2.0 |

### Code-to-video and motion graphics

| Project | Positioning | Stars | 90-day commits | Last commit (UTC) | Maintenance score | License |
| --- | --- | --- | --- | --- | --- | --- |
| [HyperFrames](https://github.com/heygen-com/hyperframes) | HTML/CSS/JS-based code video and agent skill ecosystem, migratable from Remotion with frame-by-frame verification. | 91,752 | 4,168 | 2026-11-28 | 99.7 | Apache-2.0 |
| [Remotion](https://github.com/remotion-dev/remotion) · License caution | Base framework for creating and rendering video in code with React/TypeScript. | 76,255 | 6,839 | 2026-11-27 | 98.9 | Remotion License |
| [raea](https://github.com/shinyobjectz/raea) · License caution | Engine and desktop agent workbench for writing video, motion, 3D and games in React/TypeScript, rendered on the local GPU. | 5,399 | 1,615 | 2026-11-27 | 89.7 | FSL-1.1-ALv2 |
| [Lemo Opuscar](https://github.com/lemomo-ai/lemo-opuscar) · License caution | Cinematic style, examples and STYLE.md guidance for coding agents making video in code. | 22,171 | 151 | 2026-11-26 | 87.5 | MIT code + CC BY-NC docs (additional license) |
| [Manim Community](https://github.com/ManimCommunity/manim) | Video engine for programmatic math and explainer animations in Python. | 43,022 | 80 | 2026-11-26 | 86.3 | MIT |
| [GiveMotion](https://github.com/givemotion/givemotion) | Code video engine where agents write HTML/CSS, preview, check and render MP4s. | 105 | 255 | 2026-11-27 | 72.0 | MIT |
| [SenseNova Code2Video](https://github.com/OpenSenseNova/SenseNova-6.8-Code2Video) · ★User reference · License caution | Small open model that generates executable code rendered into short videos. | 791 | 3 | 2026-11-26 | 55.4 | Unverified |
| [Manim](https://github.com/3b1b/manim) | Python animation engine for math explainers. | 97,049 | 1 | 2026-09-09 | 54.1 | MIT |
| [Motion Canvas](https://github.com/motion-canvas/motion-canvas) | Creates animations, explainers and motion graphics with TypeScript and generator functions. | 20,446 | 0 | 2026-07-02 | 39.3 | MIT |

### Animation, 3D and coding building blocks

| Project | Positioning | Stars | 90-day commits | Last commit (UTC) | Maintenance score | License |
| --- | --- | --- | --- | --- | --- | --- |
| [three.js](https://github.com/mrdoob/three.js) | JavaScript 3D scene and rendering library that supplies 3D content for code motion. | 119,596 | 894 | 2026-11-28 | 100.0 | MIT |
| [Godot](https://github.com/godotengine/godot) | Open-source game engine for building 2D/3D scenes, interaction and animation. | 120,995 | 1,873 | 2026-11-26 | 99.6 | MIT |
| [Motion](https://github.com/motiondivision/motion) | UI and layout animation library for JavaScript, React and Vue. | 35,692 | 1,396 | 2026-11-26 | 95.9 | MIT |
| [Blender](https://github.com/blender/blender) | 3D creation suite covering modeling, rigging, animation, rendering, compositing and video editing. | 22,647 | 3,362 | 2026-11-28 | 94.8 | GPL-2.0-or-later |
| [Babylon.js](https://github.com/BabylonJS/Babylon.js) | JavaScript 3D scene, game and rendering engine usable as code-motion infrastructure. | 26,493 | 343 | 2026-11-27 | 93.0 | Apache-2.0 |
| [Konva](https://github.com/konvajs/konva) | 2D Canvas scene graph with object interaction, transforms, animation and export. | 15,044 | 219 | 2026-11-25 | 88.0 | MIT |
| [Two.js](https://github.com/jonobr1/two.js) | 2D shapes and animated scenes via WebGL, Canvas or SVG. | 8,799 | 44 | 2026-11-17 | 75.1 | MIT |
| [Shifty](https://github.com/jeremyckahn/shifty) | TypeScript tweening engine with easings and playback control. | 1,629 | 14 | 2026-11-14 | 62.5 | MIT |
| [Ola](https://github.com/franciscop/ola) | Lightweight animation library for real-time numeric smoothing. | 1,907 | 3 | 2026-10-24 | 51.1 | MIT |
| [Anime.js](https://github.com/juliangarnier/anime) | Timeline animation of CSS, SVG, DOM and JavaScript properties. | 75,178 | 0 | 2026-08-09 | 46.3 | MIT |
| [Proton](https://github.com/drawcall/Proton) | JavaScript particle animation library for fire, fireworks, explosions and similar effects. | 2,558 | 0 | 2026-03-06 | 28.6 | MIT |
| [Lottie Web](https://github.com/airbnb/lottie-web) | Parses and renders exported Lottie vector animations in the web. | 32,634 | 0 | 2024-11-19 | 36.1 | MIT |
| [TweenJS](https://github.com/CreateJS/TweenJS) | Tweens and chained playback for JavaScript numbers and CSS properties. | 3,602 | 0 | 2021-03-27 | 28.4 | MIT |
| [LUME](https://github.com/lume/lume) | Builds interactive 2D and 3D graphic scenes using HTML elements. | 1,603 | 0 | 2025-10-14 | 25.9 | MIT |
| [gifenc](https://github.com/mattdesl/gifenc) | Encodes GIFs with animation and transparency in the browser or Node.js. | 404 | 0 | 2024-09-19 | 20.9 | MIT |

### ComfyUI and open-source video generation

| Project | Positioning | Stars | 90-day commits | Last commit (UTC) | Maintenance score | License |
| --- | --- | --- | --- | --- | --- | --- |
| [VRGameDevGirl AI Video Builder](https://github.com/vrgamegirl19/comfyui-vrgamedevgirl) · ★User reference · License caution | ComfyUI workflow suite managing planning, prompts, generation, pacing, review and final assembly per scenario. | 908 | 661 | 2026-11-24 | 82.7 | VRGameDevGirl Community and Commercial License |
| [LTX-Video](https://github.com/Lightricks/LTX-Video) | Open video models and inference tools for text/image-to-video and audio-visual generation. | 11,517 | 2 | 2026-11-02 | 57.5 | Apache-2.0 |
| [HunyuanVideo](https://github.com/Tencent-Hunyuan/HunyuanVideo) · License caution | Tencent's open large video-generation foundation model and inference framework. | 12,839 | 3 | 2026-10-08 | 54.9 | Tencent Hunyuan Community License |
| [Wan2.2](https://github.com/Wan-Video/Wan2.2) | Alibaba's Wan family of open video generation models covering text/image-to-video and related tasks. | 18,985 | 2 | 2026-09-21 | 52.1 | Apache-2.0 |
| [Mochi](https://github.com/genmoai/mochi) | Genmo's open video generation model and inference code. | 3,769 | 2 | 2026-10-22 | 51.5 | Apache-2.0 |
| [Open-Sora](https://github.com/hpcaitech/Open-Sora) | Open-source efficient video generation training and inference framework. | 29,958 | 0 | 2026-04-09 | 37.7 | Apache-2.0 |
| [Bernini](https://github.com/bytedance/Bernini) | Video generation and editing research framework combining a semantic planner and a DiT renderer. | 1,372 | 0 | 2026-08-13 | 32.7 | Apache-2.0 |
| [HunyuanVideo-I2V](https://github.com/Tencent-Hunyuan/HunyuanVideo-I2V) · License caution | Customizable image-to-video framework built on HunyuanVideo. | 1,858 | 0 | 2026-04-07 | 28.0 | Tencent Hunyuan Community License |
| [CogVideo / CogVideoX](https://github.com/zai-org/CogVideo) | Open text/image-to-video models and inference code. | 13,236 | 0 | 2025-11-04 | 33.3 | Apache-2.0 |

### Digital humans, portrait animation and lip sync

| Project | Positioning | Stars | 90-day commits | Last commit (UTC) | Maintenance score | License |
| --- | --- | --- | --- | --- | --- | --- |
| [LiveTalking](https://github.com/lipku/LiveTalking) | Real-time interactive streaming system combining multiple digital-human backends. | 11,407 | 12 | 2026-11-27 | 71.5 | Apache-2.0 |
| [MuseTalk](https://github.com/TMElyralab/MuseTalk) | Audio-driven virtual human model for real-time high-quality lip sync. | 7,064 | 1 | 2026-11-19 | 57.3 | MIT |
| [LivePortrait](https://github.com/KlingAIResearch/LivePortrait) | Efficient portrait animation, retargeting and control framework. | 19,602 | 0 | 2026-06-01 | 37.7 | MIT |
| [SadTalker](https://github.com/OpenTalker/SadTalker) | Generates talking-head video from a single portrait and audio. | 14,228 | 0 | 2023-10-10 | 33.2 | Apache-2.0 |
| [Wav2Lip](https://github.com/Rudrabha/Wav2Lip) · License caution | Classic audio-video lip-sync research implementation. | 13,292 | 0 | 2025-06-22 | 33.1 | Personal/research/non-commercial license |

### Download, capture, transcoding and media CLIs

| Project | Positioning | Stars | 90-day commits | Last commit (UTC) | Maintenance score | License |
| --- | --- | --- | --- | --- | --- | --- |
| [FFmpeg](https://github.com/FFmpeg/FFmpeg) · License caution | Low-level toolchain for transcoding, filtering, muxing, compositing and stream processing. | 68,309 | 3,014 | 2026-11-28 | 98.7 | LGPL-2.1+; GPL-2.0+ once GPL components are enabled |
| [yt-dlp](https://github.com/yt-dlp/yt-dlp) | Feature-rich command-line audio/video downloader supporting a large number of sites. | 211,288 | 75 | 2026-11-24 | 88.4 | Unlicense |
| [Streamlink](https://github.com/streamlink/streamlink) | CLI that resolves online livestreams and pipes them to a local player. | 12,009 | 156 | 2026-11-27 | 86.0 | BSD-2-Clause |
| [Downvid](https://github.com/Downvid/downvid) · ★User reference | Cross-platform video download GUI/WebUI built on yt-dlp and FFmpeg. | 1,692 | 361 | 2026-11-28 | 84.0 | MIT |
| [VidBee](https://github.com/nexmoe/VidBee) | Downloads media, then runs local transcription, speaker labeling, summarization, translation and media chat. | 11,225 | 51 | 2026-11-21 | 77.7 | MIT |
| [cobalt](https://github.com/imputnet/cobalt) · License caution | Ad- and tracker-free media download web app and self-hostable API covering YouTube, TikTok, Instagram and more. | 47,486 | 0 | 2026-04-06 | 39.2 | AGPL-3.0 (api and the rest) + CC-BY-NC-SA-4.0 (web) |
| [Lux](https://github.com/iawia002/lux) | Multi-site video download CLI written in Go. | 31,861 | 0 | 2025-12-29 | 36.6 | MIT |
| [you-get](https://github.com/soimort/you-get) | Python command-line tool downloading media from web pages. | 56,851 | 0 | 2025-04-27 | 38.1 | MIT |

### Benchmarks, research and external indexes

| Project | Positioning | Stars | 90-day commits | Last commit (UTC) | Maintenance score | License |
| --- | --- | --- | --- | --- | --- | --- |
| [Aurora / AgentEdit-Bench](https://github.com/yeates/Aurora) | Unifies video editing through a tool-using agent and ships AgentEdit-Bench. | 470 | 4 | 2026-11-13 | 51.7 | MIT |
| [Awesome AI Video for Creators](https://github.com/sasateguh/awesome-ai-video-for-creators) | Organizes open-source editing, captioning, clipping, voiceover and code-video tools by creator workflow. | 25 | 15 | 2026-11-24 | 50.9 | CC0-1.0 |
| [CutCraft Bench](https://github.com/AlibabaResearch/cut-craft-bench) · License caution | Benchmarks professional editing-technique execution in multi-shot audio-video generation, with agent baselines. | 45 | 5 | 2026-09-14 | 34.2 | Unverified |
| [Awesome Video Editing](https://github.com/devanasolver/awesome-video-editing) | Curates open-source video editing tools, agent skills and usable media. | 6 | 2 | 2026-10-17 | 28.7 | CC0-1.0 |
| [Awesome AI Video](https://github.com/thoxakihiko/awesome-ai-video) | Curates text/image-to-video models, tools and resources. | 3 | 3 | 2026-09-27 | 25.2 | CC0-1.0 |
| [VEFX-Bench](https://github.com/Visko-Platform/VEFX-Bench) | Benchmarks instruction following and quality for general video editing and visual effects. | 177 | 0 | 2026-05-16 | 20.8 | Apache-2.0 |
| [EditVerse](https://github.com/adobe-research/EditVerse) · License caution | Image/video generation and editing research code plus EditVerseBench. | 140 | 0 | 2025-10-09 | 17.4 | Adobe Research License (some files) |
| [Video-Bench](https://github.com/Video-Bench/Video-Bench) | Organizes and runs multi-dimensional evaluations of video generation models. | 82 | 0 | 2025-06-09 | 15.4 | Apache-2.0 |

### Historical and restricted versions

| Project | Positioning | Stars | 90-day commits | Last commit (UTC) | Maintenance score | License |
| --- | --- | --- | --- | --- | --- | --- |
| [Palmier Pro](https://github.com/palmier-io/palmier-pro) · ★User reference · Archived/historical · License caution | AI-oriented video editor whose older sources were released under GPLv3. | 14,819 | 9 | 2026-11-26 | 70.7 | GPL-3.0 (source up to v0.7.6) / later binaries proprietary |

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
