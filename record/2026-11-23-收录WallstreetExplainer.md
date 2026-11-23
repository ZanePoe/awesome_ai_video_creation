# 2026-11-23 收录 Wallstreet Explainer

- 项目：<https://github.com/HeyChengC/wallstreet-explainer>
- 分类：Agent Skills、MCP 与剪辑工具
- 定位：华尔街式财经/科技解读短片的 coding agent Skill，含风格语言、图形组件模板与找片、截图、配音、抠像、渲染、混音脚本
- 许可：MIT（代码与文档）+ 样片第三方素材除外；GitHub 识别为 NOASSERTION

Skill 的入口是 `SKILL.md`，配套 `references/`（方法与规矩）、`kit/`（横屏 31 个场景、竖屏 29 个 `v-` 场景和 20 个 vpro 组件）、`starter/`、`scripts/`（下片、截图、配音、抠像、渲染、混音与 `--check` 自检）和 `examples/`。给一个选题，Agent 自己写文案、找素材、配音、出片；横屏 16:9 与竖屏 9:16 各分真人口播与无人出镜四种模式，同一份镜头表可切换实拍与图片+TTS。

依赖外部工具：ffmpeg 需在 PATH，Python 侧 yt-dlp、edge-tts、numpy、OpenCV、Pillow（可选 faster-whisper 逐字对齐、onnxruntime/rembg 抠像），Node 侧 Playwright Chromium；MiSans、阿里妈妈数黑体、Bebas Neue、Montserrat、Noto Sans SC 需自行下载放入 `fonts/`。

归入 Skills 而非工作台：交付形态是给 coding agent 调用的规则库、模板与脚本，成片由宿主 Agent 编排 yt-dlp、edge-tts 和渲染脚本完成。

功能判断固定到默认分支提交 `b79bc0573455cb5fe335e78f653012e658fa9758`（v2.7.1）的官方 README 与 LICENSE，未安装或实机出片。README 的 GIF 为作者样片且无声，不代表本地可复现的成片质量。

`LICENSE` 是 MIT 正文加附加条款，明确 `examples/` 的视频帧、新闻截图、logo 和照片不在许可内，因此 GitHub 报 NOASSERTION。README 声明素材只用于评论和解读、每条片需在简介写清出处（如 `examples/ai-burn-money/CREDITS.md`）。新闻截图、实拍引用、人物肖像、被抠像当事人、字体和第三方音乐的授权与平台条款需使用者自行核验；yt-dlp 与 edge-tts 需保持更新，否则可能遇到站点 403。
