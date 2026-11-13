# awesome_ai_video_creation

**开源 AI 视频生成、剪辑、知识短视频、数字人、Agent Skills、ComfyUI 与媒体 CLI 合集。**

Curated open-source AI video generation, editing, agentic production, code-to-video, digital presenters, ComfyUI workflows, media CLIs, and benchmarks — with evidence-linked descriptions and reproducible GitHub maintenance rankings.

本目录覆盖从合法素材获取、脚本与镜头规划、图像/视频生成、数字人、时间线剪辑、字幕配音、动效、质检到导出的完整链路。模型、工作台、Skill、CLI 和 benchmark 分开分类。

[分类目录](#分类目录) · [项目详表](docs/projects.md) · [CLI 对比](docs/cli-comparison.md) · [排序](docs/rankings.md) · [检索记录](docs/research.md) · [贡献](CONTRIBUTING.md)

```mermaid
flowchart LR
    A[主题 / 脚本 / 素材] --> B[镜头规划 / 故事板]
    B --> C[实拍 / 生成模型 / 代码动效]
    C --> D[时间线 / 字幕 / 配音 / 音乐]
    D --> E[审片 / 质检 / 修复]
    E --> D
    E --> F[导出 / 发布包]
```

首版提供可复核的生态地图，不声称穷尽所有视频模型、商业 API 或传统 NLE 插件。

## 当前收录

**73 个项目，其中 22 个为用户参考项目，51 个为本轮新增。** 功能核验：2026-11-13；指标快照：`2026-11-13T09:13:20+00:00`（UTC）。

每个分类先按维护状态分层，再综合 star（40%）、90 天默认分支提交（35%）和最近提交（25%）排序。维护分不代表成片质量、模型能力、版权安全或生产成熟度。

## 活跃核心项目速览

仅展示核心候选、开放许可证已核验且近 90 天有提交的项目；受限许可、基础模型、研究基准和相邻工具不进入此表。

| 项目 | 定位 | Stars | 90天提交 | 最近提交 UTC | 维护分 |
| --- | --- | --- | --- | --- | --- |
| [HyperFrames](https://github.com/heygen-com/hyperframes) | 基于 HTML/CSS/JS 的代码视频与 Agent Skill 生态，可从 Remotion 等迁移并逐帧验证。 | 83,619 | 3,210 | 2026-11-13 | 99.4 |
| [OpenMontage](https://github.com/OpenMontageInc/OpenMontage) | 面向 coding agent 的多管线视频生产系统，覆盖研究、脚本、素材、配音、字幕和渲染。 | 80,122 | 303 | 2026-11-09 | 95.3 |
| [Concat](https://github.com/jub0t/Concat) | 本地跨平台多轨编辑器，含字幕、TTS、抠图、关键帧、特效和 4K 导出。 | 17,244 | 1,499 | 2026-11-12 | 93.8 |
| [Clypra](https://github.com/AIEraDev/Clypra) | Rust/Tauri/React 构建的硬件加速跨平台视频编辑器。 | 3,360 | 2,602 | 2026-11-13 | 88.1 |
| [yt-dlp](https://github.com/yt-dlp/yt-dlp) | 支持大量站点的功能丰富命令行音视频下载器。 | 207,409 | 89 | 2026-11-04 | 87.9 |
| [OpenChatCut](https://github.com/0xsline/OpenChatCut) | 本地优先的对话式 AI 视频编辑器，含多轨时间线、Agent Skills、MCP 与 Remotion 渲染。 | 3,095 | 520 | 2026-11-12 | 87.7 |
| [OpenFilm](https://github.com/openfilm/openfilm) | 让 coding agent 以代码创建、检查、编辑和渲染视频，并提供可编辑界面。 | 6,092 | 271 | 2026-11-12 | 86.6 |
| [CozyClay](https://github.com/HaD0Yun/CozyClay) | 浏览器内的场景搭建、角色走位、镜头剪切与 AI 视频预演工具。 | 1,785 | 2,445 | 2026-11-13 | 86.0 |
| [Streamlink](https://github.com/streamlink/streamlink) | 把在线直播流解析并管道传给本地播放器的 CLI。 | 11,920 | 157 | 2026-11-11 | 85.6 |
| [Downvid](https://github.com/Downvid/downvid) | 基于 yt-dlp 与 FFmpeg 的跨平台视频下载 GUI/WebUI。 | 1,520 | 429 | 2026-11-11 | 84.2 |
| [Video Shotcraft](https://github.com/Vincentwei1021/video-shotcraft) | 为 Agent 提供镜头配方、故事板、Remotion 动画、节拍剪辑与逐帧检查。 | 19,081 | 42 | 2026-11-11 | 80.0 |
| [VidBee](https://github.com/nexmoe/VidBee) | 下载媒体，并在本地执行转录、说话人标注、摘要、翻译和媒体对话。 | 11,137 | 63 | 2026-11-08 | 79.5 |

## 分类目录

`★用户参考` 表示用户直接提供的项目。模型、编辑器、Skill、CLI 与 benchmark 分开分类。

| 分类 | 数量 | 维护排序靠前的项目 |
| --- | --- | --- |
| 视频编辑器与制作工作台 | 13 | Concat、Clypra、OpenChatCut |
| Agent 视频生产与自动化 | 7 | Hypit、OpenMontage、OpenFilm |
| 知识类短视频、切片与讲解 | 8 | Clipmint、ChrisHKAI Video、Lanshu AI Presenter Video |
| Agent Skills、MCP 与剪辑工具 | 9 | Video Shotcraft、Kinocut、ReelBench Skills |
| Code-to-video 与动效 | 6 | HyperFrames、Remotion、GiveMotion |
| ComfyUI 与开源视频生成 | 9 | VRGameDevGirl AI Video Builder、LTX-Video、HunyuanVideo |
| 数字人、肖像动画与唇同步 | 5 | LiveTalking、LivePortrait、SadTalker |
| 下载、采集、转码与素材 CLI | 7 | FFmpeg、yt-dlp、Streamlink |
| 评测、研究与外部索引 | 8 | Awesome AI Video for Creators、CutCraft Bench、Awesome Video Editing |
| 历史与受限版本 | 1 | Palmier Pro |

### 视频编辑器与制作工作台

| 项目 | 定位 | Stars | 90天提交 | 最近提交 UTC | 维护分 | 许可 |
| --- | --- | --- | --- | --- | --- | --- |
| [Concat](https://github.com/jub0t/Concat) · ★用户参考 | 本地跨平台多轨编辑器，含字幕、TTS、抠图、关键帧、特效和 4K 导出。 | 17,244 | 1,499 | 2026-11-12 | 93.8 | AGPL-3.0 |
| [Clypra](https://github.com/AIEraDev/Clypra) · ★用户参考 | Rust/Tauri/React 构建的硬件加速跨平台视频编辑器。 | 3,360 | 2,602 | 2026-11-13 | 88.1 | MIT |
| [OpenChatCut](https://github.com/0xsline/OpenChatCut) · ★用户参考 | 本地优先的对话式 AI 视频编辑器，含多轨时间线、Agent Skills、MCP 与 Remotion 渲染。 | 3,095 | 520 | 2026-11-12 | 87.7 | AGPL-3.0 |
| [CozyClay](https://github.com/HaD0Yun/CozyClay) · ★用户参考 | 浏览器内的场景搭建、角色走位、镜头剪切与 AI 视频预演工具。 | 1,785 | 2,445 | 2026-11-13 | 86.0 | AGPL-3.0 |
| [OpenDirector](https://github.com/ThinkFlowLab/OpenDirector) | 从对话、画布、素材组织到时间线导出的 Agent 视频创作工作流。 | 344 | 274 | 2026-11-13 | 76.9 | Apache-2.0 |
| [AI Video Production Editor](https://github.com/LudwigKienle/ai-video-production-editor) · ★用户参考 | 从脚本、导演处理、故事板、生成镜头到剪辑、调色和导出的本地工作台。 | 178 | 137 | 2026-10-28 | 66.7 | GPL-3.0 |
| [OpenKatana](https://github.com/rk0neki/OpenKatana) | 由 Agent 驱动的 Studio、CLI、MCP 与 ComfyUI 视频编辑引擎。 | 73 | 126 | 2026-11-04 | 64.8 | Apache-2.0 |
| [OpenReel Video](https://github.com/Augani/openreel-video) · ★用户参考 | 浏览器与桌面端开源时间线编辑器，支持剪切、字幕、混音和无水印导出。 | 5,657 | 15 | 2026-10-17 | 64.1 | MIT |
| [MakeMyClip Editor](https://github.com/MakeMyClip/editor) | 用本地浏览器时间线、CLI、MCP 和 Skill 封装 FFmpeg 剪辑能力。 | 9 | 88 | 2026-11-13 | 58.2 | MIT |
| [OpenScene](https://github.com/Theorvane/OpenScene) | 本地桌面视频编辑器，允许 AI Agent 操作时间线、生成媒体并导出。 | 11 | 169 | 2026-10-20 | 56.8 | MIT |
| [SeeCut](https://github.com/YeJe-cpu/SeeCut) · ★用户参考 · 许可注意 | 让 coding agent 自动理解、剪辑、渲染并视觉质检口播短视频的 Skill 工作区。 | 455 | 11 | 2026-10-30 | 56.7 | PolyForm Noncommercial-1.0.0 |
| [ScriptCut](https://github.com/FernandoAbishai/ScriptCut) | 通过编辑转录文本完成本地剪辑、短视频打包和社交媒体导出。 | 16 | 114 | 2026-10-14 | 54.4 | AGPL-3.0 |
| [Cutline](https://github.com/Aepzie/cutline) | 浏览器时间线编辑器，提供一等 MCP 接口让 Agent 实时操作。 | 1 | 109 | 2026-10-16 | 47.2 | MIT |

### Agent 视频生产与自动化

| 项目 | 定位 | Stars | 90天提交 | 最近提交 UTC | 维护分 | 许可 |
| --- | --- | --- | --- | --- | --- | --- |
| [Hypit](https://github.com/hypit-ai/hypit) · 许可注意 | 让 coding agent 把参考视频复刻为可编辑、可重复运行的完整工作流，并批量生成内容变体。 | 29,608 | 1,166 | 2026-11-13 | 95.8 | Hypit Open Source License（修改版 Apache-2.0） |
| [OpenMontage](https://github.com/OpenMontageInc/OpenMontage) | 面向 coding agent 的多管线视频生产系统，覆盖研究、脚本、素材、配音、字幕和渲染。 | 80,122 | 303 | 2026-11-09 | 95.3 | AGPL-3.0 |
| [OpenFilm](https://github.com/openfilm/openfilm) | 让 coding agent 以代码创建、检查、编辑和渲染视频，并提供可编辑界面。 | 6,092 | 271 | 2026-11-12 | 86.6 | MIT |
| [Rea Video](https://github.com/JuneYaooo/rea-video) · ★用户参考 | 逆向拆解视频的实拍、AI 与代码成分，输出分镜级复刻方案和 VIDEO.md。 | 7,676 | 118 | 2026-11-13 | 83.0 | Apache-2.0 |
| [Video Autopilot Kit](https://github.com/Hao0321/video-autopilot-kit) · ★用户参考 | 负责视频计划、审计、审片和效果学习的自动化框架。 | 2,311 | 56 | 2026-11-13 | 74.6 | MIT |
| [Video Director](https://github.com/win4r/video-director) · ★用户参考 | 指导 Claude Code 用 HTML/Canvas/SVG/Three.js/GSAP/Remotion 计划、渲染和检查短片。 | 461 | 19 | 2026-11-07 | 61.6 | MIT |
| [WeVisCut](https://github.com/Tencent/WeVisCut) | 将知识文章或解说稿通过规划、素材检索、剪辑、检查和修复生成多分钟视频。 | 90 | 29 | 2026-10-30 | 56.1 | Apache-2.0 |

### 知识类短视频、切片与讲解

| 项目 | 定位 | Stars | 90天提交 | 最近提交 UTC | 维护分 | 许可 |
| --- | --- | --- | --- | --- | --- | --- |
| [Clipmint](https://github.com/kleZ799/clipmint) | 把播客、访谈、教程和 VOD 变成带字幕的竖屏 Shorts/Reels/TikTok。 | 39 | 536 | 2026-11-09 | 71.8 | MIT |
| [ChrisHKAI Video](https://github.com/ChrisHKAI/ChrisHKAI-Video) · ★用户参考 | 把创作者公开资料组织为 3D 玩具风短片的 coding-agent Skill。 | 149 | 153 | 2026-11-13 | 70.8 | MIT |
| [Lanshu AI Presenter Video](https://github.com/cclank/lanshu-create-ai-presenter-video) · ★用户参考 | 把主题或脚本制作成经核验的数字人/风格化讲解视频的 Agent Skill。 | 2,974 | 17 | 2026-10-11 | 61.5 | MIT |
| [Claude Animated Shorts](https://github.com/mromidev/claude-animated-shorts) · ★用户参考 | 用 Three.js、Remotion、配乐与音效制作竖屏动画故事短片的 Skill。 | 3,162 | 2 | 2026-11-01 | 56.0 | MIT |
| [Vibe Knowledge](https://github.com/andyhuo520/vibe-knowledge) · ★用户参考 | 从知识点查证、写稿、配音、代码成片到质检和发布包的知识短片 Skill。 | 647 | 3 | 2026-10-28 | 51.3 | MIT |
| [Vox Director](https://github.com/alisa0808/vox-director) | 从主题到 Vox 风纸张拼贴讲解/广告视频的端到端 Agent Skill。 | 2,807 | 1 | 2026-10-05 | 47.8 | MIT |
| [Video to Shorts Skill](https://github.com/social-media-skills/video-to-shorts-skill) | 让 Agent 把长视频或播客变成逐词字幕竖屏短片并可选发布。 | 0 | 3 | 2026-11-11 | 32.4 | MIT |
| [Atlas Explainer](https://github.com/AtlasCloudAI/atlas-explainer) | 从一个主题生成配音、纸艺风知识讲解视频的 Skill/CLI。 | 3 | 0 | 2026-07-10 | 11.0 | MIT |

### Agent Skills、MCP 与剪辑工具

| 项目 | 定位 | Stars | 90天提交 | 最近提交 UTC | 维护分 | 许可 |
| --- | --- | --- | --- | --- | --- | --- |
| [Video Shotcraft](https://github.com/Vincentwei1021/video-shotcraft) · ★用户参考 | 为 Agent 提供镜头配方、故事板、Remotion 动画、节拍剪辑与逐帧检查。 | 19,081 | 42 | 2026-11-11 | 80.0 | Apache-2.0 |
| [Kinocut](https://github.com/KyaniteLabs/kinocut) | 带防护、预检、收据和质量门的本地视频编辑 MCP/Python/CLI。 | 268 | 566 | 2026-11-12 | 79.2 | Apache-2.0 |
| [ReelBench Skills](https://github.com/eternityspring/reelbench-skills) · ★用户参考 | 面向 Claude Code/Codex 的视频分析、复刻和制作 Skill 集合。 | 1,221 | 21 | 2026-11-09 | 66.1 | Apache-2.0 |
| [Video Agent Skills](https://github.com/Melvynx/video-agent-skills) | 用 Markdown Skills 组织短视频/YouTube 的脚本、研究、剪辑、翻译和发布。 | 156 | 26 | 2026-11-06 | 59.2 | MIT |
| [HyperFrames Motion Library](https://github.com/nutllwhy/hyperframes-motion-library) · ★用户参考 | 以 HyperFrames 为内核的本地动效模板与参数化资产库。 | 307 | 4 | 2026-10-28 | 50.0 | MIT |
| [Video Editing Skill](https://github.com/social-media-skills/video-editing-skill) | 让 Agent 对口播、课程、访谈和 vlog 执行第一遍剪辑与字幕处理。 | 3 | 3 | 2026-11-11 | 37.2 | MIT |
| [Narrator AI CLI Skill](https://github.com/NarratorAI-Studio/narrator-ai-cli-skill) · ★用户参考 | 指导 Agent 调用 narrator-ai-cli 自动制作影视解说视频。 | 3,195 | 0 | 2026-07-05 | 33.9 | MIT |
| [OpenClip Agent Skills](https://github.com/OpenClip-App/agent-skills) | 为 Agent 提供长视频切片、转录、转换、缩略图、抠图和 UGC 创意 Skill。 | 1 | 0 | 2026-08-07 | 10.8 | MIT |
| [MCP Video Editing](https://github.com/mfortne/mcp-video-editing) | 以 MCP、Python 库和 CLI 封装 FFmpeg、HyperFrames 与本地复用流程。 | 2 | 0 | 2026-06-04 | 8.0 | Apache-2.0 |

### Code-to-video 与动效

| 项目 | 定位 | Stars | 90天提交 | 最近提交 UTC | 维护分 | 许可 |
| --- | --- | --- | --- | --- | --- | --- |
| [HyperFrames](https://github.com/heygen-com/hyperframes) | 基于 HTML/CSS/JS 的代码视频与 Agent Skill 生态，可从 Remotion 等迁移并逐帧验证。 | 83,619 | 3,210 | 2026-11-13 | 99.4 | Apache-2.0 |
| [Remotion](https://github.com/remotion-dev/remotion) · 许可注意 | 用 React/TypeScript 以代码创建和渲染视频的基础框架。 | 72,882 | 6,738 | 2026-11-13 | 98.9 | Remotion License |
| [GiveMotion](https://github.com/givemotion/givemotion) | 让 Agent 编写 HTML/CSS、预览检查并渲染 MP4 的代码视频引擎。 | 40 | 238 | 2026-11-10 | 67.8 | MIT |
| [Manim](https://github.com/3b1b/manim) | 面向数学讲解的 Python 动画引擎。 | 96,471 | 15 | 2026-09-09 | 67.7 | MIT |
| [SenseNova Code2Video](https://github.com/OpenSenseNova/SenseNova-6.8-Code2Video) · ★用户参考 · 许可注意 | 用小型开放模型生成可执行代码并渲染短视频。 | 638 | 2 | 2026-10-27 | 49.4 | 待核验 |
| [Motion Canvas](https://github.com/motion-canvas/motion-canvas) | 用 TypeScript 和生成器函数创建动画、讲解和动态图形。 | 19,792 | 0 | 2026-07-02 | 40.0 | MIT |

### ComfyUI 与开源视频生成

| 项目 | 定位 | Stars | 90天提交 | 最近提交 UTC | 维护分 | 许可 |
| --- | --- | --- | --- | --- | --- | --- |
| [VRGameDevGirl AI Video Builder](https://github.com/vrgamegirl19/comfyui-vrgamedevgirl) · ★用户参考 · 许可注意 | 在 ComfyUI 中按场景管理规划、提示、生成、节奏、审阅和最终拼接。 | 887 | 741 | 2026-11-12 | 83.5 | VRGameDevGirl Community and Commercial License |
| [LTX-Video](https://github.com/Lightricks/LTX-Video) | 面向文本/图像到视频及音画生成的开放视频模型与推理工具。 | 11,375 | 2 | 2026-11-02 | 60.9 | Apache-2.0 |
| [HunyuanVideo](https://github.com/Tencent-Hunyuan/HunyuanVideo) · 许可注意 | 腾讯开源的大型视频生成基础模型与推理框架。 | 12,767 | 3 | 2026-10-08 | 57.4 | Tencent Hunyuan Community License |
| [Mochi](https://github.com/genmoai/mochi) | Genmo 的开源视频生成模型与推理代码。 | 3,767 | 2 | 2026-10-22 | 54.5 | Apache-2.0 |
| [Wan2.2](https://github.com/Wan-Video/Wan2.2) | 阿里 Wan 系列开放视频生成模型，覆盖文本/图像到视频等任务。 | 18,612 | 2 | 2026-09-21 | 54.2 | Apache-2.0 |
| [Open-Sora](https://github.com/hpcaitech/Open-Sora) | 开源高效视频生成训练与推理框架。 | 29,928 | 0 | 2026-04-09 | 38.0 | Apache-2.0 |
| [Bernini](https://github.com/bytedance/Bernini) | 结合语义规划器和 DiT 渲染器的视频生成与编辑研究框架。 | 1,362 | 0 | 2026-08-13 | 34.1 | Apache-2.0 |
| [HunyuanVideo-I2V](https://github.com/Tencent-Hunyuan/HunyuanVideo-I2V) · 许可注意 | 基于 HunyuanVideo 的可定制图生视频框架。 | 1,855 | 0 | 2026-04-07 | 28.3 | Tencent Hunyuan Community License |
| [CogVideo / CogVideoX](https://github.com/zai-org/CogVideo) | 开源文本/图像到视频模型与推理代码。 | 13,198 | 0 | 2025-11-04 | 33.4 | Apache-2.0 |

### 数字人、肖像动画与唇同步

| 项目 | 定位 | Stars | 90天提交 | 最近提交 UTC | 维护分 | 许可 |
| --- | --- | --- | --- | --- | --- | --- |
| [LiveTalking](https://github.com/lipku/LiveTalking) | 结合多种数字人后端的实时交互式流媒体系统。 | 10,389 | 12 | 2026-10-20 | 65.7 | Apache-2.0 |
| [LivePortrait](https://github.com/KlingAIResearch/LivePortrait) | 高效肖像动画、拼接和重定向控制框架。 | 19,469 | 0 | 2026-06-01 | 38.3 | MIT |
| [SadTalker](https://github.com/OpenTalker/SadTalker) | 从单张人像和音频生成说话头像视频。 | 14,199 | 0 | 2023-10-10 | 33.2 | Apache-2.0 |
| [Wav2Lip](https://github.com/Rudrabha/Wav2Lip) · 许可注意 | 经典音视频唇同步研究实现。 | 13,273 | 0 | 2025-06-22 | 33.1 | 个人/研究/非商业许可 |
| [MuseTalk](https://github.com/TMElyralab/MuseTalk) | 面向实时高质量唇同步的音频驱动虚拟人模型。 | 6,938 | 0 | 2025-09-26 | 31.0 | MIT |

### 下载、采集、转码与素材 CLI

| 项目 | 定位 | Stars | 90天提交 | 最近提交 UTC | 维护分 | 许可 |
| --- | --- | --- | --- | --- | --- | --- |
| [FFmpeg](https://github.com/FFmpeg/FFmpeg) · 许可注意 | 视频转码、滤镜、封装、合成和流处理的底层工具链。 | 67,174 | 2,722 | 2026-11-13 | 98.6 | LGPL-2.1+；启用 GPL 组件后为 GPL-2.0+ |
| [yt-dlp](https://github.com/yt-dlp/yt-dlp) | 支持大量站点的功能丰富命令行音视频下载器。 | 207,409 | 89 | 2026-11-04 | 87.9 | Unlicense |
| [Streamlink](https://github.com/streamlink/streamlink) | 把在线直播流解析并管道传给本地播放器的 CLI。 | 11,920 | 157 | 2026-11-11 | 85.6 | BSD-2-Clause |
| [Downvid](https://github.com/Downvid/downvid) · ★用户参考 | 基于 yt-dlp 与 FFmpeg 的跨平台视频下载 GUI/WebUI。 | 1,520 | 429 | 2026-11-11 | 84.2 | MIT |
| [VidBee](https://github.com/nexmoe/VidBee) | 下载媒体，并在本地执行转录、说话人标注、摘要、翻译和媒体对话。 | 11,137 | 63 | 2026-11-08 | 79.5 | MIT |
| [Lux](https://github.com/iawia002/lux) | Go 编写的多站点视频下载 CLI。 | 31,839 | 0 | 2025-12-29 | 36.7 | MIT |
| [you-get](https://github.com/soimort/you-get) | 从网页下载媒体内容的 Python 命令行工具。 | 56,853 | 0 | 2025-04-27 | 38.1 | MIT |

### 评测、研究与外部索引

| 项目 | 定位 | Stars | 90天提交 | 最近提交 UTC | 维护分 | 许可 |
| --- | --- | --- | --- | --- | --- | --- |
| [Awesome AI Video for Creators](https://github.com/sasateguh/awesome-ai-video-for-creators) | 按创作者工作流整理开源剪辑、字幕、切片、配音和代码视频工具。 | 15 | 11 | 2026-11-10 | 47.8 | CC0-1.0 |
| [CutCraft Bench](https://github.com/AlibabaResearch/cut-craft-bench) · 许可注意 | 评测多镜头音视频生成中的专业剪辑技法执行，并提供 Agent baseline。 | 42 | 5 | 2026-09-14 | 36.0 | 待核验 |
| [Awesome Video Editing](https://github.com/devanasolver/awesome-video-editing) | 整理开源视频编辑工具、Agent Skills 与可用素材。 | 3 | 2 | 2026-10-17 | 29.6 | CC0-1.0 |
| [Awesome AI Video](https://github.com/thoxakihiko/awesome-ai-video) | 整理文本/图像到视频模型、工具和资源。 | 2 | 3 | 2026-09-27 | 26.5 | CC0-1.0 |
| [Aurora / AgentEdit-Bench](https://github.com/yeates/Aurora) | 用工具使用型 Agent 统一视频编辑，并提供 AgentEdit-Bench。 | 430 | 0 | 2026-06-16 | 25.8 | MIT |
| [VEFX-Bench](https://github.com/Visko-Platform/VEFX-Bench) | 评测通用视频编辑和视觉特效的指令遵循与质量。 | 177 | 0 | 2026-05-16 | 21.4 | Apache-2.0 |
| [EditVerse](https://github.com/adobe-research/EditVerse) · 许可注意 | 图像/视频生成与编辑研究代码及 EditVerseBench。 | 140 | 0 | 2025-10-09 | 17.5 | Adobe Research License（部分文件） |
| [Video-Bench](https://github.com/Video-Bench/Video-Bench) | 整理和运行视频生成模型的多维评测。 | 82 | 0 | 2025-06-09 | 15.4 | Apache-2.0 |

### 历史与受限版本

| 项目 | 定位 | Stars | 90天提交 | 最近提交 UTC | 维护分 | 许可 |
| --- | --- | --- | --- | --- | --- | --- |
| [Palmier Pro](https://github.com/palmier-io/palmier-pro) · ★用户参考 · 归档/历史 · 许可注意 | 面向 AI 的视频编辑器，旧版本源码曾以 GPLv3 发布。 | 14,741 | 32 | 2026-11-02 | 75.2 | GPL-3.0（至 v0.7.6 源码）/ 后续二进制专有 |

## 如何选择

- 有素材、需要剪片：看编辑器/工作台或 Skills/MCP。
- 从主题、脚本到成片：看 Agent 生产与知识短视频。
- 做动效、产品演示和数据故事：看 Code-to-video。
- 本地扩散生成：看 ComfyUI 与开源模型。
- 做数字人/口播：看肖像动画与唇同步，并优先检查人物授权。
- 获取合法授权的素材：看 [CLI 对比](docs/cli-comparison.md)。

完整边界见 [项目详表](docs/projects.md)，分类口径见 [范围与分类](docs/taxonomy.md)。

## 数据与维护

- [综合、Star、活跃度、最近提交排序](docs/rankings.md)
- [Downvid 与下载/媒体 CLI 对比](docs/cli-comparison.md)
- [排序方法与限制](docs/methodology.md)
- [检索关键词、来源与覆盖](docs/research.md)
- [贡献指南](CONTRIBUTING.md)

```sh
python scripts/refresh_metrics.py
python scripts/build.py
python -m unittest discover -s tests -v
python scripts/build.py --check
```

## 许可与致谢

本目录原创整理与脚本采用 [MIT](LICENSE)，链接项目、模型、权重、素材和字体遵循各自许可。Source-available、非商业、社区模型和条件许可均保留原边界。

项目发现参考 [Awesome Video Editing](https://github.com/devanasolver/awesome-video-editing) 等外部索引，最终条目回到官方仓库核验。
