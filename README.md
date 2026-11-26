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

**111 projects, of which 22 are user-reference projects and 89 were added in this round.** Feature verification: 2026-11-26; metrics snapshot: `2026-11-26T11:17:07+00:00` (UTC).

Within each category, projects are first tiered by maintenance status, then ranked by a blend of stars (40%), 90-day default-branch commits (35%) and recency of the last commit (25%). The maintenance score does not represent final-video quality, model capability, copyright safety or production readiness.

## Active core projects at a glance

Shows only core candidates with a verified open license and commits in the last 90 days; restricted-license projects, base models, research benchmarks and adjacent tools are excluded from this table.

| Project | Positioning | Stars | 90-day commits | Last commit (UTC) | Maintenance score |
| --- | --- | --- | --- | --- | --- |
| [HyperFrames](https://github.com/heygen-com/hyperframes) | HTML/CSS/JS-based code video and agent skill ecosystem, migratable from Remotion with frame-by-frame verification. | 90,470 | 4,087 | 2026-11-26 | 99.7 |
| [Concat](https://github.com/jub0t/Concat) | Local-first cross-platform multitrack editor with subtitles, TTS, background removal, keyframes, effects and 4K export. | 20,936 | 1,680 | 2026-11-26 | 94.5 |
| [OpenMotion](https://github.com/nexu-io/openmotion) | Reference-video cloning and branded motion workbench for local coding agents, with Motion.md, a visual timeline and MP4 export. | 16,551 | 832 | 2026-11-26 | 93.8 |
| [OpenMontage](https://github.com/OpenMontageInc/OpenMontage) | Multi-pipeline video production system for coding agents covering research, scripts, assets, voiceover, subtitles and rendering. | 83,493 | 272 | 2026-11-16 | 93.3 |
| [FFmpeg Skill](https://github.com/kajisho5/ffmpeg-skill) | CLI and MCP giving coding agents local FFmpeg cutting, subtitles, format export and output checks. | 11,317 | 977 | 2026-11-26 | 92.4 |
| [Jellyfish](https://github.com/Forget-C/Jellyfish) | AI short-drama production workbench covering script breakdown, storyboards, character and scene asset management, shot generation and export. | 7,344 | 1,666 | 2026-11-25 | 90.6 |
| [yt-dlp](https://github.com/yt-dlp/yt-dlp) | Feature-rich command-line audio/video downloader supporting a large number of sites. | 210,854 | 79 | 2026-11-24 | 89.2 |
| [OpenFilm](https://github.com/openfilm/openfilm) | Lets coding agents create, inspect, edit and render videos in code, with an editable interface. | 9,474 | 299 | 2026-11-25 | 88.8 |
| [Clypra](https://github.com/AIEraDev/Clypra) | Rust/Tauri/React hardware-accelerated cross-platform video editor. | 3,379 | 1,852 | 2026-11-25 | 87.9 |
| [Claude Code Video Toolkit](https://github.com/digitalsamba/claude-code-video-toolkit) | Skills, templates, commands and tools for Claude Code covering scripts, voiceover, music, image and video generation, QA, rendering and publishing, portable to Codex and Kiro CLI. | 2,776 | 546 | 2026-11-25 | 87.3 |
| [Manim Community](https://github.com/ManimCommunity/manim) | Video engine for programmatic math and explainer animations in Python. | 42,928 | 79 | 2026-11-25 | 86.5 |
| [CozyClay](https://github.com/HaD0Yun/CozyClay) | In-browser scene blocking, character staging, shot cutting and AI video previs tool. | 2,057 | 2,138 | 2026-11-26 | 86.5 |

## Category index

`★User reference` marks projects provided directly by the user. Models, editors, Skills, CLIs and benchmarks are categorized separately.

| Category | Count | Top projects by maintenance rank |
| --- | --- | --- |
| Video editors and production workbenches | 19 | Concat, Jellyfish, Clypra |
| Agent video production and automation | 9 | Hypit, OpenMotion, OpenMontage |
| Knowledge shorts, clipping and explainers | 10 | NeonClipping, Clipmint, ChrisHKAI Video |
| Agent Skills, MCP and editing tools | 18 | FFmpeg Skill, Claude Code Video Toolkit, Video Shotcraft |
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
| [Concat](https://github.com/jub0t/Concat) · ★User reference | Local-first cross-platform multitrack editor with subtitles, TTS, background removal, keyframes, effects and 4K export. | 20,936 | 1,680 | 2026-11-26 | 94.5 | AGPL-3.0 |
| [Jellyfish](https://github.com/Forget-C/Jellyfish) | AI short-drama production workbench covering script breakdown, storyboards, character and scene asset management, shot generation and export. | 7,344 | 1,666 | 2026-11-25 | 90.6 | Apache-2.0 |
| [Clypra](https://github.com/AIEraDev/Clypra) · ★User reference | Rust/Tauri/React hardware-accelerated cross-platform video editor. | 3,379 | 1,852 | 2026-11-25 | 87.9 | MIT |
| [CozyClay](https://github.com/HaD0Yun/CozyClay) · ★User reference | In-browser scene blocking, character staging, shot cutting and AI video previs tool. | 2,057 | 2,138 | 2026-11-26 | 86.5 | AGPL-3.0 |
| [Huobao Drama](https://github.com/chatfire-AI/huobao-drama) · License caution | Web/desktop platform that turns a one-line idea or a pasted novel into rewritten script, images, storyboard videos, voiceover, subtitles and a finished short drama, orchestrated by a Mastra agent backend with UI-editable skills. | 18,018 | 108 | 2026-11-21 | 84.1 | CC BY-NC-SA-4.0 (no commercial use) |
| [OpenChatCut](https://github.com/0xsline/OpenChatCut) · ★User reference | Local-first conversational AI video editor with a multitrack timeline, Agent Skills, MCP and Remotion rendering. | 3,343 | 396 | 2026-11-12 | 83.3 | AGPL-3.0 |
| [OpenDirector](https://github.com/ThinkFlowLab/OpenDirector) | Agent video creation workflow from conversation, canvas and asset organization through timeline export. | 455 | 358 | 2026-11-26 | 79.4 | Apache-2.0 |
| [AID Studio](https://github.com/shijue-aid/aid-studio) | Self-hostable AI workbench for comic dramas, short dramas and film/TV creation covering scripts, characters and scenes, storyboards, image and video generation, voiceover, infinite canvas and 3D previs. | 1,802 | 120 | 2026-11-25 | 77.8 | MIT |
| [CutVoke](https://github.com/frankShan001/CutVoke) | Local-first cross-platform open-source video editor with a built-in MCP server, letting agents such as Claude Code, Codex and Cursor edit alongside humans on one non-destructive multitrack timeline. | 53 | 543 | 2026-11-26 | 73.8 | MIT |
| [OpenReel Video](https://github.com/Augani/openreel-video) · ★User reference | Open-source timeline editor for browser and desktop with cutting, subtitles, mixing and watermark-free export. | 6,522 | 20 | 2026-11-25 | 72.3 | MIT |
| [AI Video Production Editor](https://github.com/LudwigKienle/ai-video-production-editor) · ★User reference | Local workbench covering script, directing, storyboarding and shot generation through editing, grading and export. | 194 | 144 | 2026-11-20 | 69.7 | GPL-3.0 |
| [MakeMyClip Editor](https://github.com/MakeMyClip/editor) | Wraps FFmpeg editing in a local browser timeline, CLI, MCP and Skill. | 48 | 153 | 2026-11-16 | 64.2 | MIT |
| [OpenKatana](https://github.com/rk0neki/OpenKatana) | Agent-driven studio, CLI, MCP and ComfyUI video editing engine. | 89 | 126 | 2026-11-04 | 62.4 | Apache-2.0 |
| [OpenScene](https://github.com/Theorvane/OpenScene) | Local desktop video editor that lets AI agents operate the timeline, generate media and export. | 11 | 114 | 2026-11-25 | 60.1 | MIT |
| [Waoowaoo](https://github.com/waooAI/waoowaoo) · License caution | AI image and video creation workbench that manages reference media, generates content and merges clips via a canvas and an Assistant. | 14,989 | 6 | 2026-09-21 | 56.4 | Elastic License 2.0 |
| [SeeCut](https://github.com/YeJe-cpu/SeeCut) · ★User reference · License caution | Skill workspace where a coding agent understands, cuts, renders and visually QA-checks talking-head shorts. | 491 | 11 | 2026-10-30 | 54.0 | PolyForm Noncommercial-1.0.0 |
| [ScriptCut](https://github.com/FernandoAbishai/ScriptCut) | Edit the transcript to cut locally, package shorts and export for social media. | 23 | 62 | 2026-10-14 | 49.8 | AGPL-3.0 |
| [Cutline](https://github.com/Aepzie/cutline) | Browser timeline editor with a first-class MCP interface for live agent operation. | 1 | 109 | 2026-10-16 | 44.7 | MIT |
| [Moyin Creator](https://github.com/MemeCalculate/moyin-creator) · License caution | Electron desktop tool for AI film/TV production that chains a five-stage pipeline — script → characters → scenes → directing → Seedance 2.0 — to batch-produce short dramas and anime series. | 4,879 | 0 | 2026-08-27 | 38.6 | AGPL-3.0 + commercial dual license |

### Agent video production and automation

| Project | Positioning | Stars | 90-day commits | Last commit (UTC) | Maintenance score | License |
| --- | --- | --- | --- | --- | --- | --- |
| [Hypit](https://github.com/hypit-ai/hypit) · License caution | Lets coding agents clone reference videos into editable, repeatable full workflows and batch-generate content variants. | 31,570 | 739 | 2026-11-25 | 95.7 | Hypit Open Source License (modified Apache-2.0) |
| [OpenMotion](https://github.com/nexu-io/openmotion) | Reference-video cloning and branded motion workbench for local coding agents, with Motion.md, a visual timeline and MP4 export. | 16,551 | 832 | 2026-11-26 | 93.8 | Apache-2.0 |
| [OpenMontage](https://github.com/OpenMontageInc/OpenMontage) | Multi-pipeline video production system for coding agents covering research, scripts, assets, voiceover, subtitles and rendering. | 83,493 | 272 | 2026-11-16 | 93.3 | AGPL-3.0 |
| [OpenFilm](https://github.com/openfilm/openfilm) | Lets coding agents create, inspect, edit and render videos in code, with an editable interface. | 9,474 | 299 | 2026-11-25 | 88.8 | MIT |
| [Rea Video](https://github.com/JuneYaooo/rea-video) · ★User reference | Reverse-analyzes a video's live, AI and code components and outputs a shot-level replication plan and VIDEO.md. | 13,553 | 218 | 2026-11-25 | 88.1 | Apache-2.0 |
| [Video Autopilot Kit](https://github.com/Hao0321/video-autopilot-kit) · ★User reference | Automation framework for video planning, auditing, review and learning from results. | 2,364 | 33 | 2026-11-13 | 68.4 | MIT |
| [Video Director](https://github.com/win4r/video-director) · ★User reference | Guides Claude Code to plan, render and check short films with HTML/Canvas/SVG/Three.js/GSAP/Remotion. | 545 | 20 | 2026-11-26 | 64.0 | MIT |
| [Video Use](https://github.com/browser-use/video-use) | Editing, subtitles, grading, motion overlays and output checks on raw footage via a coding agent plus FFmpeg. | 31,613 | 5 | 2026-10-08 | 60.7 | MIT |
| [WeVisCut](https://github.com/Tencent/WeVisCut) | Turns knowledge articles or narration scripts into multi-minute videos through planning, media retrieval, editing, checking and repair. | 117 | 29 | 2026-10-30 | 54.2 | Apache-2.0 |

### Knowledge shorts, clipping and explainers

| Project | Positioning | Stars | 90-day commits | Last commit (UTC) | Maintenance score | License |
| --- | --- | --- | --- | --- | --- | --- |
| [NeonClipping](https://github.com/iamajmeena/neonclipping) | Paste a link to cut long YouTube/Twitch/Kick videos or your own MP4s locally into 9:16 clips with burned-in subtitles, titles and hooks. | 2,669 | 89 | 2026-11-24 | 77.2 | MIT |
| [Clipmint](https://github.com/kleZ799/clipmint) | Turns podcasts, interviews, tutorials and VODs into subtitled vertical Shorts/Reels/TikToks. | 73 | 614 | 2026-11-24 | 74.4 | MIT |
| [ChrisHKAI Video](https://github.com/ChrisHKAI/ChrisHKAI-Video) · ★User reference | Coding-agent Skill organizing a creator's public materials into 3D toy-style short films. | 165 | 206 | 2026-11-26 | 72.7 | MIT |
| [Lanshu AI Presenter Video](https://github.com/cclank/lanshu-create-ai-presenter-video) · ★User reference | Agent Skill turning a topic or script into a verified digital-human/stylized explainer video. | 3,083 | 16 | 2026-10-11 | 59.0 | MIT |
| [Claude Animated Shorts](https://github.com/mromidev/claude-animated-shorts) · ★User reference | Skill for vertical animated story shorts made with Three.js, Remotion, score and sound effects. | 5,029 | 2 | 2026-11-01 | 54.7 | MIT |
| [Vibe Knowledge](https://github.com/andyhuo520/vibe-knowledge) · ★User reference | Knowledge-short Skill from fact-checking and script writing, voiceover and code-to-video to QA and release packages. | 834 | 3 | 2026-10-28 | 49.3 | MIT |
| [Vox Director](https://github.com/alisa0808/vox-director) | End-to-end agent Skill from topic to Vox-style paper-collage explainer/ad videos. | 3,201 | 1 | 2026-10-05 | 46.0 | MIT |
| [Video to Shorts Skill](https://github.com/social-media-skills/video-to-shorts-skill) | Lets an agent turn long videos or podcasts into vertical shorts with word-level captions and optional publishing. | 4 | 3 | 2026-11-11 | 34.6 | MIT |
| [Pixelle-Video](https://github.com/ATH-MaaS/Pixelle-Video) | Generates copy, images or video, voiceover and composited shorts from a topic, with ComfyUI workflows and media APIs. | 30,545 | 0 | 2026-06-14 | 39.9 | Apache-2.0 |
| [Atlas Explainer](https://github.com/AtlasCloudAI/atlas-explainer) | Skill/CLI generating a voiceover papercraft-style explainer video from one topic. | 3 | 0 | 2026-07-10 | 10.1 | MIT |

### Agent Skills, MCP and editing tools

| Project | Positioning | Stars | 90-day commits | Last commit (UTC) | Maintenance score | License |
| --- | --- | --- | --- | --- | --- | --- |
| [FFmpeg Skill](https://github.com/kajisho5/ffmpeg-skill) | CLI and MCP giving coding agents local FFmpeg cutting, subtitles, format export and output checks. | 11,317 | 977 | 2026-11-26 | 92.4 | MIT |
| [Claude Code Video Toolkit](https://github.com/digitalsamba/claude-code-video-toolkit) | Skills, templates, commands and tools for Claude Code covering scripts, voiceover, music, image and video generation, QA, rendering and publishing, portable to Codex and Kiro CLI. | 2,776 | 546 | 2026-11-25 | 87.3 | MIT |
| [Video Shotcraft](https://github.com/Vincentwei1021/video-shotcraft) · ★User reference | Shot recipes, storyboards, Remotion animation, beat editing and frame-by-frame checks for agents. | 22,696 | 57 | 2026-11-25 | 82.4 | Apache-2.0 |
| [Remocn](https://github.com/Remocn/remocn) | Claude Code plugin, agent skill and MCP server for making Remotion videos from 935 MIT-licensed components: the agent plans a storyboard first, then writes the video. | 1,921 | 197 | 2026-11-25 | 80.8 | MIT |
| [Kinocut](https://github.com/KyaniteLabs/kinocut) | Local video editing MCP/Python/CLI with guardrails, preflight checks, receipts and quality gates. | 283 | 698 | 2026-11-25 | 79.3 | Apache-2.0 |
| [Remotion Agent Skills](https://github.com/remotion-dev/skills) · License caution | Official Skills for coding agents to create, preview and render Remotion videos. | 8,032 | 31 | 2026-11-24 | 75.3 | License unverified |
| [Manju Laoli Skill](https://github.com/lixiaoxiao9888-create/manju-laoli-skill) | OpenClaw skill suite for AI comic dramas and short dramas covering scripts, asset locking, storyboards, fight scenes, Seedance prompting and machine checks. | 3,170 | 47 | 2026-11-26 | 74.8 | MIT |
| [pixelfx](https://github.com/patch-gg/pixelfx) · License caution | Library of 244 code-drawn pixel effects and animations with a Claude Code effect-generation skill plus sprite-sheet and GIF/MP4 export tools. | 9,353 | 10 | 2026-11-12 | 66.6 | MIT (code and effects) + Patch Pixel font excluded |
| [Wallstreet Explainer](https://github.com/HeyChengC/wallstreet-explainer) · License caution | Coding-agent Skill for Wall-Street-style finance/tech explainer shorts with style language, graphic component templates, and footage-finding, screenshot, voiceover, keying, rendering and mixing scripts. | 1,347 | 16 | 2026-11-20 | 64.4 | MIT (code and docs) + third-party sample assets excluded |
| [ReelBench Skills](https://github.com/eternityspring/reelbench-skills) · ★User reference | Video analysis, cloning and production skill set for Claude Code/Codex. | 1,258 | 21 | 2026-11-09 | 62.9 | Apache-2.0 |
| [Video Agent Skills](https://github.com/Melvynx/video-agent-skills) | Organizes scripts, research, editing, translation and publishing for shorts/YouTube via Markdown skills. | 217 | 26 | 2026-11-06 | 57.2 | MIT |
| [Awesome Motion Design Agent Skills](https://github.com/frankxai/awesome-motion-design-agent-skills) | Five installable SKILL.md motion workflows (including remotion-video-agent and web-motion-auditor) plus a curated index of GSAP, Motion, Remotion, Rive, Lottie and 3D tools. | 166 | 19 | 2026-11-12 | 56.0 | CC0-1.0 |
| [HyperFrames Motion Library](https://github.com/nutllwhy/hyperframes-motion-library) · ★User reference | Local motion template and parameterized asset library built on HyperFrames. | 329 | 2 | 2026-10-28 | 44.5 | MIT |
| [Video Editing Skill](https://github.com/social-media-skills/video-editing-skill) | Runs the first editing pass and caption handling for talking heads, courses, interviews and vlogs. | 11 | 3 | 2026-11-11 | 37.7 | MIT |
| [GSAP Skills](https://github.com/greensock/gsap-skills) | Official Agent Skills teaching coding agents the GSAP timeline, motion and plugins. | 19,089 | 0 | 2026-04-21 | 36.5 | MIT |
| [Narrator AI CLI Skill](https://github.com/NarratorAI-Studio/narrator-ai-cli-skill) · ★User reference | Guides an agent to drive narrator-ai-cli for automated film-commentary videos. | 3,324 | 0 | 2026-07-05 | 33.2 | MIT |
| [OpenClip Agent Skills](https://github.com/OpenClip-App/agent-skills) | Agent skills for long-video clipping, transcription, conversion, thumbnails, cutouts and UGC creative. | 2 | 0 | 2026-08-07 | 11.1 | MIT |
| [MCP Video Editing](https://github.com/mfortne/mcp-video-editing) | Wraps FFmpeg, HyperFrames and local reusable pipelines in an MCP, Python library and CLI. | 2 | 0 | 2026-06-04 | 7.4 | Apache-2.0 |

### Code-to-video and motion graphics

| Project | Positioning | Stars | 90-day commits | Last commit (UTC) | Maintenance score | License |
| --- | --- | --- | --- | --- | --- | --- |
| [HyperFrames](https://github.com/heygen-com/hyperframes) | HTML/CSS/JS-based code video and agent skill ecosystem, migratable from Remotion with frame-by-frame verification. | 90,470 | 4,087 | 2026-11-26 | 99.7 | Apache-2.0 |
| [Remotion](https://github.com/remotion-dev/remotion) · License caution | Base framework for creating and rendering video in code with React/TypeScript. | 75,845 | 6,756 | 2026-11-26 | 99.0 | Remotion License |
| [raea](https://github.com/shinyobjectz/raea) · License caution | Engine and desktop agent workbench for writing video, motion, 3D and games in React/TypeScript, rendered on the local GPU. | 5,256 | 1,568 | 2026-11-26 | 89.8 | FSL-1.1-ALv2 |
| [Lemo Opuscar](https://github.com/lemomo-ai/lemo-opuscar) · License caution | Cinematic style, examples and STYLE.md guidance for coding agents making video in code. | 21,365 | 151 | 2026-11-26 | 87.9 | MIT code + CC BY-NC docs (additional license) |
| [Manim Community](https://github.com/ManimCommunity/manim) | Video engine for programmatic math and explainer animations in Python. | 42,928 | 79 | 2026-11-25 | 86.5 | MIT |
| [GiveMotion](https://github.com/givemotion/givemotion) | Code video engine where agents write HTML/CSS, preview, check and render MP4s. | 99 | 243 | 2026-11-19 | 70.0 | MIT |
| [SenseNova Code2Video](https://github.com/OpenSenseNova/SenseNova-6.8-Code2Video) · ★User reference · License caution | Small open model that generates executable code rendered into short videos. | 780 | 3 | 2026-11-26 | 55.9 | Unverified |
| [Manim](https://github.com/3b1b/manim) | Python animation engine for math explainers. | 96,985 | 1 | 2026-09-09 | 54.3 | MIT |
| [Motion Canvas](https://github.com/motion-canvas/motion-canvas) | Creates animations, explainers and motion graphics with TypeScript and generator functions. | 20,252 | 0 | 2026-07-02 | 39.4 | MIT |

### Animation, 3D and coding building blocks

| Project | Positioning | Stars | 90-day commits | Last commit (UTC) | Maintenance score | License |
| --- | --- | --- | --- | --- | --- | --- |
| [three.js](https://github.com/mrdoob/three.js) | JavaScript 3D scene and rendering library that supplies 3D content for code motion. | 119,443 | 884 | 2026-11-26 | 100.0 | MIT |
| [Godot](https://github.com/godotengine/godot) | Open-source game engine for building 2D/3D scenes, interaction and animation. | 120,861 | 1,895 | 2026-11-25 | 99.8 | MIT |
| [Motion](https://github.com/motiondivision/motion) | UI and layout animation library for JavaScript, React and Vue. | 35,572 | 1,390 | 2026-11-24 | 95.9 | MIT |
| [Blender](https://github.com/blender/blender) | 3D creation suite covering modeling, rigging, animation, rendering, compositing and video editing. | 22,568 | 3,323 | 2026-11-26 | 94.8 | GPL-2.0-or-later |
| [Babylon.js](https://github.com/BabylonJS/Babylon.js) | JavaScript 3D scene, game and rendering engine usable as code-motion infrastructure. | 26,456 | 335 | 2026-11-26 | 93.1 | Apache-2.0 |
| [Konva](https://github.com/konvajs/konva) | 2D Canvas scene graph with object interaction, transforms, animation and export. | 15,016 | 219 | 2026-11-25 | 88.5 | MIT |
| [Two.js](https://github.com/jonobr1/two.js) | 2D shapes and animated scenes via WebGL, Canvas or SVG. | 8,770 | 47 | 2026-11-17 | 75.9 | MIT |
| [Shifty](https://github.com/jeremyckahn/shifty) | TypeScript tweening engine with easings and playback control. | 1,602 | 14 | 2026-11-14 | 62.9 | MIT |
| [Ola](https://github.com/franciscop/ola) | Lightweight animation library for real-time numeric smoothing. | 1,876 | 3 | 2026-10-24 | 51.4 | MIT |
| [Anime.js](https://github.com/juliangarnier/anime) | Timeline animation of CSS, SVG, DOM and JavaScript properties. | 75,093 | 0 | 2026-08-09 | 46.5 | MIT |
| [Proton](https://github.com/drawcall/Proton) | JavaScript particle animation library for fire, fireworks, explosions and similar effects. | 2,534 | 0 | 2026-03-06 | 28.6 | MIT |
| [Lottie Web](https://github.com/airbnb/lottie-web) | Parses and renders exported Lottie vector animations in the web. | 32,591 | 0 | 2024-11-19 | 36.1 | MIT |
| [TweenJS](https://github.com/CreateJS/TweenJS) | Tweens and chained playback for JavaScript numbers and CSS properties. | 3,580 | 0 | 2021-03-27 | 28.4 | MIT |
| [LUME](https://github.com/lume/lume) | Builds interactive 2D and 3D graphic scenes using HTML elements. | 1,581 | 0 | 2025-10-14 | 25.9 | MIT |
| [gifenc](https://github.com/mattdesl/gifenc) | Encodes GIFs with animation and transparency in the browser or Node.js. | 386 | 0 | 2024-09-19 | 20.7 | MIT |

### ComfyUI and open-source video generation

| Project | Positioning | Stars | 90-day commits | Last commit (UTC) | Maintenance score | License |
| --- | --- | --- | --- | --- | --- | --- |
| [VRGameDevGirl AI Video Builder](https://github.com/vrgamegirl19/comfyui-vrgamedevgirl) · ★User reference · License caution | ComfyUI workflow suite managing planning, prompts, generation, pacing, review and final assembly per scenario. | 904 | 667 | 2026-11-24 | 83.2 | VRGameDevGirl Community and Commercial License |
| [LTX-Video](https://github.com/Lightricks/LTX-Video) | Open video models and inference tools for text/image-to-video and audio-visual generation. | 11,496 | 2 | 2026-11-02 | 57.9 | Apache-2.0 |
| [HunyuanVideo](https://github.com/Tencent-Hunyuan/HunyuanVideo) · License caution | Tencent's open large video-generation foundation model and inference framework. | 12,833 | 3 | 2026-10-08 | 55.2 | Tencent Hunyuan Community License |
| [Wan2.2](https://github.com/Wan-Video/Wan2.2) | Alibaba's Wan family of open video generation models covering text/image-to-video and related tasks. | 18,940 | 2 | 2026-09-21 | 52.4 | Apache-2.0 |
| [Mochi](https://github.com/genmoai/mochi) | Genmo's open video generation model and inference code. | 3,770 | 2 | 2026-10-22 | 51.8 | Apache-2.0 |
| [Open-Sora](https://github.com/hpcaitech/Open-Sora) | Open-source efficient video generation training and inference framework. | 29,953 | 0 | 2026-04-09 | 37.7 | Apache-2.0 |
| [Bernini](https://github.com/bytedance/Bernini) | Video generation and editing research framework combining a semantic planner and a DiT renderer. | 1,371 | 0 | 2026-08-13 | 32.9 | Apache-2.0 |
| [HunyuanVideo-I2V](https://github.com/Tencent-Hunyuan/HunyuanVideo-I2V) · License caution | Customizable image-to-video framework built on HunyuanVideo. | 1,858 | 0 | 2026-04-07 | 28.0 | Tencent Hunyuan Community License |
| [CogVideo / CogVideoX](https://github.com/zai-org/CogVideo) | Open text/image-to-video models and inference code. | 13,232 | 0 | 2025-11-04 | 33.3 | Apache-2.0 |

### Digital humans, portrait animation and lip sync

| Project | Positioning | Stars | 90-day commits | Last commit (UTC) | Maintenance score | License |
| --- | --- | --- | --- | --- | --- | --- |
| [LiveTalking](https://github.com/lipku/LiveTalking) | Real-time interactive streaming system combining multiple digital-human backends. | 11,321 | 13 | 2026-11-26 | 72.3 | Apache-2.0 |
| [MuseTalk](https://github.com/TMElyralab/MuseTalk) | Audio-driven virtual human model for real-time high-quality lip sync. | 7,046 | 1 | 2026-11-19 | 57.8 | MIT |
| [LivePortrait](https://github.com/KlingAIResearch/LivePortrait) | Efficient portrait animation, retargeting and control framework. | 19,581 | 0 | 2026-06-01 | 37.8 | MIT |
| [SadTalker](https://github.com/OpenTalker/SadTalker) | Generates talking-head video from a single portrait and audio. | 14,223 | 0 | 2023-10-10 | 33.2 | Apache-2.0 |
| [Wav2Lip](https://github.com/Rudrabha/Wav2Lip) · License caution | Classic audio-video lip-sync research implementation. | 13,289 | 0 | 2025-06-22 | 33.1 | Personal/research/non-commercial license |

### Download, capture, transcoding and media CLIs

| Project | Positioning | Stars | 90-day commits | Last commit (UTC) | Maintenance score | License |
| --- | --- | --- | --- | --- | --- | --- |
| [FFmpeg](https://github.com/FFmpeg/FFmpeg) · License caution | Low-level toolchain for transcoding, filtering, muxing, compositing and stream processing. | 68,240 | 3,002 | 2026-11-26 | 98.6 | LGPL-2.1+; GPL-2.0+ once GPL components are enabled |
| [yt-dlp](https://github.com/yt-dlp/yt-dlp) | Feature-rich command-line audio/video downloader supporting a large number of sites. | 210,854 | 79 | 2026-11-24 | 89.2 | Unlicense |
| [Streamlink](https://github.com/streamlink/streamlink) | CLI that resolves online livestreams and pipes them to a local player. | 12,000 | 155 | 2026-11-18 | 84.0 | BSD-2-Clause |
| [Downvid](https://github.com/Downvid/downvid) · ★User reference | Cross-platform video download GUI/WebUI built on yt-dlp and FFmpeg. | 1,683 | 354 | 2026-11-25 | 83.5 | MIT |
| [VidBee](https://github.com/nexmoe/VidBee) | Downloads media, then runs local transcription, speaker labeling, summarization, translation and media chat. | 11,219 | 51 | 2026-11-21 | 78.2 | MIT |
| [cobalt](https://github.com/imputnet/cobalt) · License caution | Ad- and tracker-free media download web app and self-hostable API covering YouTube, TikTok, Instagram and more. | 47,286 | 0 | 2026-04-06 | 39.3 | AGPL-3.0 (api and the rest) + CC-BY-NC-SA-4.0 (web) |
| [Lux](https://github.com/iawia002/lux) | Multi-site video download CLI written in Go. | 31,860 | 0 | 2025-12-29 | 36.6 | MIT |
| [you-get](https://github.com/soimort/you-get) | Python command-line tool downloading media from web pages. | 56,853 | 0 | 2025-04-27 | 38.1 | MIT |

### Benchmarks, research and external indexes

| Project | Positioning | Stars | 90-day commits | Last commit (UTC) | Maintenance score | License |
| --- | --- | --- | --- | --- | --- | --- |
| [Aurora / AgentEdit-Bench](https://github.com/yeates/Aurora) | Unifies video editing through a tool-using agent and ships AgentEdit-Bench. | 470 | 4 | 2026-11-13 | 52.2 | MIT |
| [Awesome AI Video for Creators](https://github.com/sasateguh/awesome-ai-video-for-creators) | Organizes open-source editing, captioning, clipping, voiceover and code-video tools by creator workflow. | 19 | 15 | 2026-11-24 | 50.5 | CC0-1.0 |
| [CutCraft Bench](https://github.com/AlibabaResearch/cut-craft-bench) · License caution | Benchmarks professional editing-technique execution in multi-shot audio-video generation, with agent baselines. | 44 | 5 | 2026-09-14 | 34.4 | Unverified |
| [Awesome Video Editing](https://github.com/devanasolver/awesome-video-editing) | Curates open-source video editing tools, agent skills and usable media. | 6 | 2 | 2026-10-17 | 29.0 | CC0-1.0 |
| [Awesome AI Video](https://github.com/thoxakihiko/awesome-ai-video) | Curates text/image-to-video models, tools and resources. | 3 | 3 | 2026-09-27 | 25.5 | CC0-1.0 |
| [VEFX-Bench](https://github.com/Visko-Platform/VEFX-Bench) | Benchmarks instruction following and quality for general video editing and visual effects. | 177 | 0 | 2026-05-16 | 20.9 | Apache-2.0 |
| [EditVerse](https://github.com/adobe-research/EditVerse) · License caution | Image/video generation and editing research code plus EditVerseBench. | 140 | 0 | 2025-10-09 | 17.4 | Adobe Research License (some files) |
| [Video-Bench](https://github.com/Video-Bench/Video-Bench) | Organizes and runs multi-dimensional evaluations of video generation models. | 82 | 0 | 2025-06-09 | 15.4 | Apache-2.0 |

### Historical and restricted versions

| Project | Positioning | Stars | 90-day commits | Last commit (UTC) | Maintenance score | License |
| --- | --- | --- | --- | --- | --- | --- |
| [Palmier Pro](https://github.com/palmier-io/palmier-pro) · ★User reference · Archived/historical · License caution | AI-oriented video editor whose older sources were released under GPLv3. | 14,811 | 11 | 2026-11-26 | 72.3 | GPL-3.0 (source up to v0.7.6) / later binaries proprietary |

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
