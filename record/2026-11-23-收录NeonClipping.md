# 2026-11-23 收录 NeonClipping

来源：[用户提供的帖子](https://x.com/wanerfu/status/2124711294263865816)（2026-11-23）。帖子只提到一个项目 NeonClipping，短链指向 <https://github.com/iamajmeena/neonclipping>。

- 项目：<https://github.com/iamajmeena/neonclipping>
- 分类：知识类短视频、切片与讲解
- 定位：粘贴 YouTube/Twitch/Kick 链接或本地 MP4，在本地生成带烧录字幕的 9:16 片段，并配标题和钩子
- 许可：MIT

Fast 模式先只下载音频，用 YouTube 自带的词级字幕拿转录，再按响度突跳、2–4 kHz 人声抬升和静转响打分选段，交给本地 Ollama 模型读转录并写标题、钩子，最后只下载选中片段并按声音对齐裁剪、渲染 1080×1920。Deep 模式下载整片，另加 OpenCV 光流运动和剪辑密度信号。直播切片用 Streamlink 录制并以聊天速率突增（>2.5σ 且 2.5× 五分钟基线）触发；反馈评分存在本地 `data/feedback.jsonl`，达到八条不同片段的样本后调整本地排序权重。

依赖与边界：Python 3.10–3.13、FFmpeg（requirements 用 static-ffmpeg）、yt-dlp、faster-whisper、Streamlink、pytchat、av、OpenCV；AI 标题与打分需要自备 Ollama 及 `llama3.2:3b`（或 Gemma 4 本地判定），无 LLM 时只按音频/运动信号选段。无 YouTube 字幕的来源需本地识别或导入 SRT/ASS，字幕质量会下降；作者已移除 "Accurate (turbo)" 模型并说明其效果更差。README 的「85 分钟 97 秒」和 `tests/REPORT.md` 的 187 项通过均为作者自测，本次未安装、未实机切片。手机远程默认不启用，启用后服务监听 127.0.0.1 并需 PIN。

许可：仓库根 LICENSE 为 MIT（版权 Ajay K Meena 与贡献者）。requirements 依赖、Ollama 模型权重、系统字体与被切片内容另计；下载受各平台条款约束，人物、音乐和赛事素材的授权需自行核验。Windows `.bat` 与 `install.sh` 会安装 Python/FFmpeg，`install.sh` 按 README 自述尚未在真机上验证。仓库创建于 2026-11-19、最新标签 v1.1.0，成熟度需按版本复核。
