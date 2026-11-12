# 检索方法、关键词与覆盖记录

调研日期：2026-11-12。目标是从 22 个用户参考项目归纳 AI 视频生成与剪辑生态，而不是把生成模型、传统 NLE、下载器和 Skill 混在一张榜单里。

## 关键词

| 方向 | 英文关键词 | 中文关键词 |
| --- | --- | --- |
| Agent 剪辑 | agent video editor, video MCP, editing skill | Agent 剪辑、视频 Skill、剪辑 MCP |
| 完整制作 | agentic video production, script-to-video, timeline | 视频生产 Agent、脚本成片、时间线 |
| 知识短视频 | explainer video, knowledge article to video, shorts | 知识类短视频、讲解视频、长视频切片 |
| Code-to-video | Remotion, HyperFrames, HTML video, motion graphics | 代码成片、动效、数据故事 |
| 数字人 | digital presenter, talking avatar, lip sync | 数字人、口播、肖像动画、唇同步 |
| 生成模型 | text-to-video, image-to-video, video diffusion | 文生视频、图生视频、视频扩散模型 |
| 媒体 CLI | video downloader CLI, FFmpeg, yt-dlp, Streamlink | 视频下载 CLI、转码、直播流 |
| 评测 | video editing benchmark, VFX benchmark, agent editing | 视频编辑评测、多镜头剪辑、AgentEdit |

## 三轮过程

| 轮次 | 批次 | 结果 | 新来源 | 新来源率 |
| --- | ---: | ---: | ---: | ---: |
| 1 | 14 | 394 | 377 | 95.7% |
| 2 | 7 | 130 | 101 | 77.7% |
| 3 | 7 | 270 | 208 | 77.0% |

第一轮覆盖用户项目、GitHub 搜索、CLI 对比、风险、benchmark 和 Awesome Video Editing 外部索引。

第二轮补查 OpenFilm、OpenKatana、Kinocut、OpenMontage、OpenClip、MakeMyClip、WeVisCut、VidBee、GiveMotion，以及 VEFX/CutCraft/AgentEdit 等新实体。

第三轮补齐开源视频模型、数字人、知识讲解、Code-to-video 基础和下载 CLI，并批量登记全部最终项目的一手 README 和 GitHub 指标。

停止原因是预设的三轮上限，不是搜索空间已经饱和。第三轮仍有较高的新来源率，项目应持续增量维护。

## 内容工厂

通过 `content-factory-search-api` 的 curl 路径调用 `/search/api/query`。查询包括：

- `AI 视频剪辑 OR 视频生成 OR 知识类短视频`
- `SeeCut OR OpenChatCut OR Clypra OR ReelBench`
- `Downvid OR yt-dlp OR 视频下载 CLI`
- `OpenFilm OR OpenKatana OR Kinocut OR WeVisCut`

查询按最近 30 天起步，稀疏时按技能规则逐步扩展到 90/180/365 天。规范化后内容工厂贡献 69 个来源，帮助发现 Clypra、GeekReel、VidBee、WeVisCut、OpenFilm、OpenMontage 以及 Agent 视频 Skill 生态。宽泛 AI 视频查询也产生大量模型评测和无关内容，最终项目判断回到官方仓库。

没有将私有服务地址、密钥和内部文章正文提交到公开仓库。

## 分类上的关键纠偏

- **Downvid 不是 yt-dlp 的同级解析器。** 它是跨平台 GUI/WebUI，解析来自 yt-dlp，合并与转码来自 FFmpeg。
- **VidBee 是下载后的媒体理解产品。** 除下载外还有本地转录、说话人标注、摘要、翻译和媒体对话。
- **SeeCut 是 Agent Skill 工作区，不是独立 NLE。**
- **Video Autopilot Kit 负责计划和审计，Editkin 负责真正渲染。**
- **CozyClay 是预演与镜头调度工具。** 最终生成由外部视频模型完成。
- **Rea Video 做逆向拆解和复刻规划。** 它不是最终剪辑器。
- **OpenFilm/GiveMotion/HyperFrames 属于代码到视频。** 不能拿传统时间线能力直接比较。
- **生成模型仓库和创作应用分开。** Wan、Hunyuan、LTX、CogVideo、Mochi 等提供模型与推理代码，不提供完整生产管理。

## Downvid 与 CLI

当前可用的 OpenViking 与本地历史入口无法唯一定位用户所说的“以前用过的 CLI”，因此没有猜测。最终 [CLI 对比](cli-comparison.md) 覆盖：

- Downvid：GUI/WebUI，依赖 yt-dlp + FFmpeg。
- VidBee：桌面 + CLI，下载后继续做本地转录与媒体理解。
- yt-dlp：多站点解析与下载的底层主力 CLI。
- you-get / Lux：更轻的 Python / Go CLI 路线。
- Streamlink：直播流到播放器/录制管线。
- FFmpeg：转码、滤镜、合并与封装，不负责站点解析。

后续如能确认历史 CLI 名称，可作为增量条目加入该对比。

## 许可证纠偏

- SeeCut：PolyForm Noncommercial。
- Remotion：个人/小组织免费，公司规模达到条件时需要商业许可。
- VRGameDevGirl：source-available；生成内容可商业化，但商业化软件本身需授权。
- HunyuanVideo / I2V：腾讯社区许可，含地域排除和使用政策。
- Wav2Lip：个人、研究、非商业用途。
- Palmier：v0.7.6 以前源码 GPL，后续二进制专有且无对应公开源码。
- EditVerse：Adobe Research License 只覆盖明确列出的部分文件。
- FFmpeg：默认 LGPL，启用特定 GPL 组件后整体许可变化。
- SenseNova Code2Video、CutCraft：未找到明确根目录许可证。

许可证描述不替代法律意见；素材、字体、音乐、人物肖像、训练数据和模型输出仍有独立权利边界。

## 覆盖

用户基线的 22 个 GitHub URL 全部进入研究台账，URL 覆盖率 100%。唯一未命中的 `CLI-oriented` 是基线说明中的普通短语，不是项目。

外部 `devanasolver/awesome-video-editing` 覆盖率 53.3%。其范围还包括传统 NLE、音频工具、字幕、录屏、图标、字体、HDRI、免费音乐/视频网站和大量徽章 URL。本目录刻意不复制全部素材站和传统工具，因此该缺口属于范围差异；外部索引中与 AI/Agent 视频直接相关的项目已作为发现线索使用。

## 本轮没有做什么

没有安装和运行 72 个项目，没有下载大型模型权重，没有调用付费生成 API，没有对用户素材执行下载、去水印、剪辑或发布，也没有统一复现 benchmark。

GitHub star 和提交量只用于维护排序。真正比较应固定素材、脚本、模型、硬件、API 预算和输出格式，记录成片成功率、人工修改量、镜头一致性、字幕与口型、渲染时间、显存、费用及许可。

## 可复核文件

- [检索日志](../research/search-log.json)
- [收录决策与固定证据](../research/decisions.json)
- [用户项目覆盖](../research/coverage-user.json)
- [外部索引覆盖](../research/coverage-external.json)
- [初始指标快照](../research/initial-metrics.json)
- [调研状态](../research/status.json)
- [完整性验证](../research/verification.json)

研究台账包含 686 个来源、144 条判断和 216 条 GitHub 指标。完整网页文本和本机工具日志留在本地。
