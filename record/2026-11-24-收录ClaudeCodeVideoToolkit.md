# 2026-11-24 收录 Claude Code Video Toolkit

- 项目：<https://github.com/digitalsamba/claude-code-video-toolkit>
- 分类：Agent Skills、MCP 与剪辑工具
- 定位：为 Claude Code 提供脚本、配音、音乐、图像与视频生成、质检、渲染和发布的 Skills、模板、命令与工具，并可迁移到 Codex、Kiro CLI
- 许可：MIT（版权 Digital Samba）

仓库把「让 coding agent 出片」拆成四类构件：`templates/`（sprint review、产品演示、release notes、教程、竖屏讲解、黑板讲解人）、`.claude/skills/`（remotion、remotion-official、ffmpeg、moviepy、qwen-edit、elevenlabs、acestep、ideogram4、ltx2、blender、runpod、playwright-recording、synthetic-ui-demo、parody-short、video-design、youtube-stats）、`tools/`（配音、音乐、图像、字幕、响度与画面检查、竖屏剪辑、YouTube 发布）和 `brands/`（颜色、字体、声音跨片复用）。工作流为 `/video → Script → Assets → Scene Review → Design → Audio → Preview → Render → Publish`，场景在 Remotion Studio 里核对，`qc.py` 在渲染前后检查。

`docs/agent-video-jobs.md` 另提供 `video_job.py` 的 submit/status/result、MCP server 和 `skills/video-toolkit/`，供 OpenClaw、Codex、Hermes 等非 Claude 宿主调用；`scripts/migrate_to_codex.py` 与 `scripts/migrate_to_kiro.py` 迁移 skills 与 slash 命令。

归入 Skills 而非 Agent 生产：交付物是给宿主 Agent 使用的技能、模板与确定性脚本，渲染由 Remotion 完成，出片决策仍在宿主 Agent 与用户。与 Video Shotcraft、FFmpeg Skill 同类。

成本与依赖：需要 Node.js 22+（推荐 24 LTS）与 Claude Code，推荐 uv 管理 Python 3.10+ 依赖，FFmpeg 与 Blender 可选。语音（Qwen3-TTS）、图像（FLUX.2 / Ideogram 4）、音乐（ACE-Step）等开源模型部署在用户自己的 Modal（Starter 每月 30 美元免费额度）或 RunPod 账户按算力计费，文件走 Cloudflare R2；README 的「90 秒片子 $0.33（measured）」与示例片均为作者自测，本次未部署、未渲染。Blender 路线额外需要本地机器资源。

功能判断固定到默认分支提交 `b3437fcd462c23b3c46cfd28f8cb61b71039269b`（最新标签 v0.30.0）的官方 README 与目录树。

许可：仓库根 LICENSE 为 MIT；调用或依赖的模型权重、ElevenLabs 等外部服务、Remotion 渲染器本身、以及 README 列出的社区插件（VOICEPEAK 商业授权、arkiv 为 PolyForm Perimeter 源码可见、Upload-Post 与 CommentKeyword 为托管服务）各有独立许可与条款。克隆声音、第三方素材与品牌资产、生成内容的再分发授权需使用者自行核验。设计来源可选 taste-skill（MIT）或 Anthropic frontend-design。
