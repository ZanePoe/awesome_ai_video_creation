# 项目说明与证据

每项定位来自固定提交的官方 README，未安装运行全部项目。指标刷新不会自动重审功能和许可证。


## [Concat](https://github.com/jub0t/Concat)

本地跨平台多轨编辑器，含字幕、TTS、抠图、关键帧、特效和 4K 导出。

- 分类：视频编辑器与制作工作台；核心候选。
- 适用边界：离线模型需首次下载；产品内 AI 与完整生成式工作流不是同一范围。
- 维护状态：近90天有提交；30 天提交 479 次，90 天提交 1616 次。
- 许可：[AGPL-3.0](https://api.github.com/repos/jub0t/Concat/license)；开放许可证已核验。GitHub licenseInfo 识别；模型权重、素材、字体、第三方依赖和托管服务许可另计
- 功能核验：2026-11-12；[来源1](https://github.com/jub0t/Concat/blob/504a814ebe61d4f47bba4cd7949dc2580ecc405c/README.md#L6)。

## [Jellyfish](https://github.com/Forget-C/Jellyfish)

AI 短剧生产工作台，覆盖剧本拆解、分镜、角色与场景资产管理、镜头生成和导出。

- 分类：视频编辑器与制作工作台；核心候选。
- 适用边界：资产复用可帮助保持一致性，但不保证生成质量；模型服务、成本和部署要求需按配置核验。
- 维护状态：近90天有提交；30 天提交 1336 次，90 天提交 1955 次。
- 许可：[Apache-2.0](https://github.com/Forget-C/Jellyfish/blob/a9678194ddf2d9be3ccbe78d4287d87d5089e123/LICENSE)；开放许可证已核验。根目录 LICENSE 为 Apache-2.0；模型、素材和第三方服务条款另计。
- 功能核验：2026-11-20；[来源1](https://github.com/Forget-C/Jellyfish/blob/a9678194ddf2d9be3ccbe78d4287d87d5089e123/README.md#L30)。

## [Clypra](https://github.com/AIEraDev/Clypra)

Rust/Tauri/React 构建的硬件加速跨平台视频编辑器。

- 分类：视频编辑器与制作工作台；核心候选。
- 适用边界：通用编辑器为主；AI 功能范围和移动端成熟度需按版本验证。
- 维护状态：近90天有提交；30 天提交 333 次，90 天提交 1643 次。
- 许可：[MIT](https://api.github.com/repos/AIEraDev/Clypra/license)；开放许可证已核验。GitHub licenseInfo 识别；模型权重、素材、字体、第三方依赖和托管服务许可另计
- 功能核验：2026-11-12；[来源1](https://github.com/AIEraDev/Clypra/blob/aa6b9c619cf98f7a1dfab6446345ec5f5660b93c/README.md#L9)。

## [CozyClay](https://github.com/HaD0Yun/CozyClay)

浏览器内的场景搭建、角色走位、镜头剪切与 AI 视频预演工具。

- 分类：视频编辑器与制作工作台；核心候选。
- 适用边界：输出主要是 previs 和镜头参考，最终生成质量取决于外部视频模型。
- 维护状态：近90天有提交；30 天提交 186 次，90 天提交 2104 次。
- 许可：[AGPL-3.0](https://api.github.com/repos/HaD0Yun/CozyClay/license)；开放许可证已核验。GitHub licenseInfo 识别；模型权重、素材、字体、第三方依赖和托管服务许可另计
- 功能核验：2026-11-12；[来源1](https://github.com/HaD0Yun/CozyClay/blob/297dd2a8a077613b329962d68e2a9bb4355be091/README.md#L6)。

## [Editroom](https://github.com/robbietilton/Editroom)

macOS 原生 Swift 视频编辑器：4K 实时剪辑不建代理，内置调色、变速曲线、转场、混音与响度目标导出，还能用自然语言让 Claude、ChatGPT 或端侧模型下刀。

- 分类：视频编辑器与制作工作台；核心候选。
- 适用边界：仅支持 macOS 14 及以上的 Apple Silicon；Magic 的 Local 模式还需 macOS 26 的 Apple Intelligence，Claude 与 ChatGPT 模式需已登录对应客户端。「7.5 MB」「无代理、无缓冲」为官方 README 自述，未实机安装验证；帖子所称 23MB 与 README 及 v1.0.11 的 DMG 实际大小 12,238,527 字节都不一致。Claude/ChatGPT 经 MCP 直接改动当前打开的工程，Magic 编辑可撤销，但素材上传范围与隐私边界需按所选模式自行核验。
- 维护状态：近90天有提交；30 天提交 457 次，90 天提交 457 次。
- 许可：[MIT（应用）+ 内置 FFmpeg LGPL-2.1+、Sparkle MIT](https://github.com/robbietilton/Editroom/blob/6390ae7f3847d924126b2d4f7a964b9fee4e71a2/LICENSE)；复合/条件许可。仓库根 LICENSE 为 MIT；应用内附 FFmpeg 9.1（LGPL-2.1+，未启用 GPL 或非自由部件，由 scripts/build-ffmpeg.sh 从 ffmpeg.org 源码构建，仅作独立进程转封装 macOS 打不开格式），更新组件 Sparkle 为 MIT；再分发需按 LGPL 提供 FFmpeg 源码与 configure 选项，Vendor/ffmpeg/README.md 已说明来源与构建方式
- 功能核验：2026-11-27；[来源1](https://github.com/robbietilton/Editroom/blob/6390ae7f3847d924126b2d4f7a964b9fee4e71a2/README.md#L5) · [来源2](https://github.com/robbietilton/Editroom/blob/6390ae7f3847d924126b2d4f7a964b9fee4e71a2/README.md#L7) · [来源3](https://github.com/robbietilton/Editroom/blob/6390ae7f3847d924126b2d4f7a964b9fee4e71a2/README.md#L50) · [来源4](https://github.com/robbietilton/Editroom/blob/6390ae7f3847d924126b2d4f7a964b9fee4e71a2/README.md#L59) · [来源5](https://github.com/robbietilton/Editroom/blob/6390ae7f3847d924126b2d4f7a964b9fee4e71a2/README.md#L87)。

## [火宝短剧 Huobao Drama](https://github.com/chatfire-AI/huobao-drama)

一句话或粘贴小说即可自动改写剧本、出图、生成分镜视频、配音、上字幕并合成整部短剧的 Web/桌面平台，后端由 Mastra Agent 编排且技能可在界面编辑。

- 分类：视频编辑器与制作工作台；核心候选。
- 适用边界：许可为 CC BY-NC-SA-4.0，明确禁止商用（含付费服务、商业部署与转售）；文本、图片与视频能力都需自行配置模型服务 API Key，README 引导使用作者的 FireMux 密钥；Seedance 引用本地参考资源需要 PUBLIC_BASE_URL 公网地址，桌面版无公网入口会直接报错；SQLite 与 data 目录存储，迁移需手动拷贝媒体文件。
- 维护状态：近90天有提交；30 天提交 18 次，90 天提交 102 次。
- 许可：[CC BY-NC-SA-4.0（禁止商用）](https://github.com/chatfire-AI/huobao-drama/blob/24d4c17612e71cf10c8eeb1a8b6439afa73e2c07/LICENSE)；源码可见但非 OSI 开源。LICENSE 为 CC BY-NC-SA 4.0 全文，README 许可证一节明确禁止商用，商业用途需作者书面许可；GitHub licenseInfo 因此识别为 NOASSERTION；所调用模型服务、素材与配音版权另计
- 功能核验：2026-11-25；[来源1](https://github.com/chatfire-AI/huobao-drama/blob/24d4c17612e71cf10c8eeb1a8b6439afa73e2c07/README.md#L33) · [来源2](https://github.com/chatfire-AI/huobao-drama/blob/24d4c17612e71cf10c8eeb1a8b6439afa73e2c07/README.md#L55) · [来源3](https://github.com/chatfire-AI/huobao-drama/blob/24d4c17612e71cf10c8eeb1a8b6439afa73e2c07/README.md#L131)。

## [OpenChatCut](https://github.com/0xsline/OpenChatCut)

本地优先的对话式 AI 视频编辑器，含多轨时间线、Agent Skills、MCP 与 Remotion 渲染。

- 分类：视频编辑器与制作工作台；核心候选。
- 适用边界：内置 Agent、桌面版和外部 coding agent 的能力边界需分开验证。
- 维护状态：近90天有提交；30 天提交 22 次，90 天提交 379 次。
- 许可：[AGPL-3.0](https://api.github.com/repos/0xsline/OpenChatCut/license)；开放许可证已核验。GitHub licenseInfo 识别；模型权重、素材、字体、第三方依赖和托管服务许可另计
- 功能核验：2026-11-12；[来源1](https://github.com/0xsline/OpenChatCut/blob/9242a95aea248ff3a8dab495514384e858320d47/README.md#L12)。

## [OpenDirector](https://github.com/ThinkFlowLab/OpenDirector)

从对话、画布、素材组织到时间线导出的 Agent 视频创作工作流。

- 分类：视频编辑器与制作工作台；核心候选。
- 适用边界：首版项目；完整生产稳定性和模型成本需实测。
- 维护状态：近90天有提交；30 天提交 349 次，90 天提交 373 次。
- 许可：[Apache-2.0](https://api.github.com/repos/ThinkFlowLab/OpenDirector/license)；开放许可证已核验。GitHub licenseInfo 识别；模型权重、素材、字体、第三方依赖和托管服务许可另计
- 功能核验：2026-11-12；[来源1](https://github.com/ThinkFlowLab/OpenDirector/blob/39288dfdf4f816798e5479c53363258fceeb6e11/README.md#L18)。

## [AID Studio](https://github.com/shijue-aid/aid-studio)

可自托管的 AI 漫剧、短剧与影视创作工作台，覆盖剧本、角色场景、分镜、图片与视频生成、配音、无限画布和 3D 预演。

- 分类：视频编辑器与制作工作台；核心候选。
- 适用边界：模型调用、存储和计算资源可能另行收费；官方示例图片、音频和视频资产包随版本单独分发；部署需要 MySQL、Redis、Docker 等依赖，生成内容与剧本、人物、素材的授权须自行核验。
- 维护状态：近90天有提交；30 天提交 46 次，90 天提交 114 次。
- 许可：[MIT](https://github.com/shijue-aid/aid-studio/blob/9b78452d047b577d31d301c8998287139c93a312/LICENSE)；开放许可证已核验。仓库根 LICENSE 为 MIT，NOTICE 保留 RuoYi-Vue 等第三方归属；官方示例资产包单独分发，模型供应商、存储和计算资源条款另计
- 功能核验：2026-11-23；[来源1](https://github.com/shijue-aid/aid-studio/blob/9b78452d047b577d31d301c8998287139c93a312/README.md#L13) · [来源2](https://github.com/shijue-aid/aid-studio/blob/9b78452d047b577d31d301c8998287139c93a312/README.md#L43) · [来源3](https://github.com/shijue-aid/aid-studio/blob/9b78452d047b577d31d301c8998287139c93a312/README.md#L46)。

## [CutVoke](https://github.com/frankShan001/CutVoke)

本地优先的跨平台开源视频剪辑器，内置 MCP server，让 Claude Code、Codex、Cursor 等 Agent 与人在同一条非破坏性多轨时间线上剪辑。

- 分类：视频编辑器与制作工作台；核心候选。
- 适用边界：桌面包内置 FFmpeg（GPLv3）等第三方组件；字幕用可选的本地 faster-whisper，模型需首次下载；所连接的 Agent 多为云服务，账号、费用与数据政策另计；v0.3.6 为冻结预览且与 main 不同步，官方列出导出窗口复用、试听超时、竖屏长字幕裁切等已知问题，macOS 包仅 ad-hoc 签名未公证；项目 2026-09 创建，成熟度低。
- 维护状态：近90天有提交；30 天提交 415 次，90 天提交 557 次。
- 许可：[MIT](https://github.com/frankShan001/CutVoke/blob/a4920ad493c6317774141a9bccbd55eafe439b7c/LICENSE)；开放许可证已核验。仓库根 LICENSE 为 MIT；桌面包附带 FFmpeg（GPLv3）等自有许可的第三方组件，社区特效配方、faster-whisper 模型与所连 AI 服务条款另计
- 功能核验：2026-11-25；[来源1](https://github.com/frankShan001/CutVoke/blob/a4920ad493c6317774141a9bccbd55eafe439b7c/README.md#L28) · [来源2](https://github.com/frankShan001/CutVoke/blob/a4920ad493c6317774141a9bccbd55eafe439b7c/README.md#L121) · [来源3](https://github.com/frankShan001/CutVoke/blob/a4920ad493c6317774141a9bccbd55eafe439b7c/README.md#L159)。

## [OpenReel Video](https://github.com/Augani/openreel-video)

浏览器与桌面端开源时间线编辑器，支持剪切、字幕、混音和无水印导出。

- 分类：视频编辑器与制作工作台；核心候选。
- 适用边界：通用编辑能力为主，不将其自动视为生成式 AI Agent。
- 维护状态：近90天有提交；30 天提交 10 次，90 天提交 16 次。
- 许可：[MIT](https://api.github.com/repos/Augani/openreel-video/license)；开放许可证已核验。GitHub licenseInfo 识别；模型权重、素材、字体、第三方依赖和托管服务许可另计
- 功能核验：2026-11-12；[来源1](https://github.com/Augani/openreel-video/blob/367d7e90b61b5181f9861b852bb8b9d7a7d2954a/README.md#L7)。

## [AI Video Production Editor](https://github.com/LudwigKienle/ai-video-production-editor)

从脚本、导演处理、故事板、生成镜头到剪辑、调色和导出的本地工作台。

- 分类：视频编辑器与制作工作台；核心候选。
- 适用边界：BYOK 仍会把请求发送至配置的模型服务；部分托管/计费能力需自备外部项目。
- 维护状态：近90天有提交；30 天提交 7 次，90 天提交 144 次。
- 许可：[GPL-3.0](https://api.github.com/repos/LudwigKienle/ai-video-production-editor/license)；开放许可证已核验。GitHub licenseInfo 识别；模型权重、素材、字体、第三方依赖和托管服务许可另计
- 功能核验：2026-11-12；[来源1](https://github.com/LudwigKienle/ai-video-production-editor/blob/a368af45b6cfd35e22bd3b5e101db198e1ac89a9/README.md#L4)。

## [MakeMyClip Editor](https://github.com/MakeMyClip/editor)

用本地浏览器时间线、CLI、MCP 和 Skill 封装 FFmpeg 剪辑能力。

- 分类：视频编辑器与制作工作台；核心候选。
- 适用边界：本地编辑不需要其云 API；浏览器 UI、CLI 与 Agent 工具是同一项目的不同入口。
- 维护状态：近90天有提交；30 天提交 145 次，90 天提交 153 次。
- 许可：[MIT](https://api.github.com/repos/MakeMyClip/editor/license)；开放许可证已核验。GitHub licenseInfo 识别；模型权重、素材、字体、第三方依赖和托管服务许可另计
- 功能核验：2026-11-12；[来源1](https://github.com/MakeMyClip/editor/blob/f6f05206c1d2234d74134da27d322caebb260e6d/README.md#L7)。

## [OpenKatana](https://github.com/rk0neki/OpenKatana)

由 Agent 驱动的 Studio、CLI、MCP 与 ComfyUI 视频编辑引擎。

- 分类：视频编辑器与制作工作台；核心候选。
- 适用边界：更偏代码化编辑引擎，实际生成模型和 ComfyUI 应用需另行配置。
- 维护状态：近90天有提交；30 天提交 61 次，90 天提交 126 次。
- 许可：[Apache-2.0](https://api.github.com/repos/rk0neki/OpenKatana/license)；开放许可证已核验。GitHub licenseInfo 识别；模型权重、素材、字体、第三方依赖和托管服务许可另计
- 功能核验：2026-11-12；[来源1](https://github.com/rk0neki/OpenKatana/blob/b9282bf0740a7df5b5a8862b5e289ef4cd642641/README.md#L7)。

## [OpenScene](https://github.com/Theorvane/OpenScene)

本地桌面视频编辑器，允许 AI Agent 操作时间线、生成媒体并导出。

- 分类：视频编辑器与制作工作台；核心候选。
- 适用边界：默认分支为开发分支；移动端和生成能力需按当前实现验证。
- 维护状态：近90天有提交；30 天提交 47 次，90 天提交 112 次。
- 许可：[MIT](https://api.github.com/repos/Theorvane/OpenScene/license)；开放许可证已核验。GitHub licenseInfo 识别；模型权重、素材、字体、第三方依赖和托管服务许可另计
- 功能核验：2026-11-12；[来源1](https://github.com/Theorvane/OpenScene/blob/4bd3d3c4c15fb27dd0b521065643b3a2d516be08/README.md#L8)。

## [ScriptCut](https://github.com/FernandoAbishai/ScriptCut)

通过编辑转录文本完成本地剪辑、短视频打包和社交媒体导出。

- 分类：视频编辑器与制作工作台；核心候选。
- 适用边界：聚焦文本式粗剪，不等于完整视觉特效与生成工作台。
- 维护状态：近90天有提交；30 天提交 4 次，90 天提交 66 次。
- 许可：[AGPL-3.0](https://api.github.com/repos/FernandoAbishai/ScriptCut/license)；开放许可证已核验。GitHub licenseInfo 识别；模型权重、素材、字体、第三方依赖和托管服务许可另计
- 功能核验：2026-11-12；[来源1](https://github.com/FernandoAbishai/ScriptCut/blob/12c6fe495939da344e6af3e942a45dfdfb2132fa/README.md#L7)。

## [Waoowaoo](https://github.com/waooAI/waoowaoo)

AI 图片与视频创作工作台，通过画布和 Assistant 管理参考素材、生成内容并合并视频片段。

- 分类：视频编辑器与制作工作台；受限许可。
- 适用边界：当前为测试版，图像与视频能力取决于模型；OpenRouter 等外部模型调用可能收费。
- 维护状态：近90天有提交；30 天提交 0 次，90 天提交 6 次。
- 许可：[Elastic License 2.0](https://github.com/waooAI/waoowaoo/blob/dfec20e32298ed675050329e4a41477024148399/LICENSE)；源码可见但非 OSI 开源。自 v0.5.0-beta.1 起采用 ELv2，禁止未经许可向第三方提供主要功能的托管服务；不是 OSI 开源许可，旧版本许可可能不同。
- 功能核验：2026-11-20；[来源1](https://github.com/waooAI/waoowaoo/blob/dfec20e32298ed675050329e4a41477024148399/README_zh.md#L24)。

## [SeeCut](https://github.com/YeJe-cpu/SeeCut)

让 coding agent 自动理解、剪辑、渲染并视觉质检口播短视频的 Skill 工作区。

- 分类：视频编辑器与制作工作台；受限许可。
- 适用边界：它是 Skill/流程，不是独立桌面 NLE；剪映草稿仅为可选后续微调。
- 维护状态：近90天有提交；30 天提交 1 次，90 天提交 11 次。
- 许可：[PolyForm Noncommercial-1.0.0](https://github.com/YeJe-cpu/SeeCut/blob/b05d7ed27404a064060e0d370402f562b0c0c02e/LICENSE)；源码可见但非 OSI 开源。仅非商业用途，不是 OSI 开源许可
- 功能核验：2026-11-12；[来源1](https://github.com/YeJe-cpu/SeeCut/blob/b05d7ed27404a064060e0d370402f562b0c0c02e/README.md#L5)。

## [Cutline](https://github.com/Aepzie/cutline)

浏览器时间线编辑器，提供一等 MCP 接口让 Agent 实时操作。

- 分类：视频编辑器与制作工作台；核心候选。
- 适用边界：大素材代理文件和浏览器编码路径仍需按部署方式评估。
- 维护状态：近90天有提交；30 天提交 0 次，90 天提交 109 次。
- 许可：[MIT](https://api.github.com/repos/Aepzie/cutline/license)；开放许可证已核验。GitHub licenseInfo 识别；模型权重、素材、字体、第三方依赖和托管服务许可另计
- 功能核验：2026-11-12；[来源1](https://github.com/Aepzie/cutline/blob/ab71520285881d8dfa78f5ebca00f8a166e84962/README.md#L8)。

## [魔因漫创 Moyin Creator](https://github.com/MemeCalculate/moyin-creator)

AI 影视生产级 Electron 桌面工具，按剧本→角色→场景→导演→Seedance 2.0 五段流水线上自动衔接，批量产出短剧与动漫番剧。

- 分类：视频编辑器与制作工作台；核心候选。
- 适用边界：需自备 AI 服务商 API Key（支持多供应商调度与 Key 轮询），生成按供应商计费；采用 AGPL-3.0 与商业许可双许可，闭源修改、集成进商业产品或做 SaaS 需购买商业许可；角色一致性依赖角色圣经与参考图，跨镜一致性和成片质量需按所用模型核验；默认分支自 2026-08-27 后仅有 README 改动，最新发布为赞助商标注的定制版标签，README 网盘包版本与 Releases 也不一致。
- 维护状态：91–365天未提交；30 天提交 0 次，90 天提交 0 次。
- 许可：[AGPL-3.0 + 商业双重许可](https://github.com/MemeCalculate/moyin-creator/blob/7e5c5655de94d49885e13c369f0a71212893a0aa/COMMERCIAL_LICENSE.md)；复合/条件许可。LICENSE 为 AGPL-3.0 正文，README 与 COMMERCIAL_LICENSE.md 声明双重许可：闭源修改、集成商业产品或 SaaS 不开源需取得商业许可；内部使用 `@opencut/ai-core` 等依赖及模型服务条款另计
- 功能核验：2026-11-25；[来源1](https://github.com/MemeCalculate/moyin-creator/blob/7e5c5655de94d49885e13c369f0a71212893a0aa/README.md#L70) · [来源2](https://github.com/MemeCalculate/moyin-creator/blob/7e5c5655de94d49885e13c369f0a71212893a0aa/README.md#L105) · [来源3](https://github.com/MemeCalculate/moyin-creator/blob/7e5c5655de94d49885e13c369f0a71212893a0aa/README.md#L122)。

## [Hypit](https://github.com/hypit-ai/hypit)

让 coding agent 把参考视频复刻为可编辑、可重复运行的完整工作流，并批量生成内容变体。

- 分类：Agent 视频生产与自动化；受限许可。
- 适用边界：热门视频复刻涉及原视频、人物、音乐、素材和品牌授权；生成模型与 API 为可选外部服务，费用和数据路径依各提供商。
- 维护状态：近90天有提交；30 天提交 15 次，90 天提交 662 次。
- 许可：[Hypit Open Source License（修改版 Apache-2.0）](https://github.com/hypit-ai/hypit/blob/6bacce093695ccc2bde5aa5d7de230e9682ffa79/LICENSE)；源码可见但非 OSI 开源。限制多租户托管、商业再分发及移除品牌/版权信息；需要这些用途时须取得商业许可，不是标准 Apache-2.0
- 功能核验：2026-11-13；[来源1](https://github.com/hypit-ai/hypit/blob/6bacce093695ccc2bde5aa5d7de230e9682ffa79/README.md#L51) · [来源2](https://github.com/hypit-ai/hypit/blob/6bacce093695ccc2bde5aa5d7de230e9682ffa79/README.md#L164) · [来源3](https://github.com/hypit-ai/hypit/blob/6bacce093695ccc2bde5aa5d7de230e9682ffa79/README.md#L338)。

## [OpenMotion](https://github.com/nexu-io/openmotion)

面向本地 coding agent 的参考视频复刻与品牌化动效工作台，支持 Motion.md、可视化时间线和 MP4 导出。

- 分类：Agent 视频生产与自动化；核心候选。
- 适用边界：参考视频、人物、音乐、品牌和素材须另行取得授权；媒体生成依赖自备 API/订阅，内置模板与第三方组件遵循各自 LICENSE/NOTICE。
- 维护状态：近90天有提交；30 天提交 852 次，90 天提交 857 次。
- 许可：[Apache-2.0](https://github.com/nexu-io/openmotion/blob/fcbaa2b0296167b0f14f47aa6c414f5bdd41316f/LICENSE)；开放许可证已核验。仓库根 LICENSE 为标准 Apache-2.0；内置模板、模型图标和 vendor 组件含各自 LICENSE/NOTICE，分发或复用时需分别保留并核验
- 功能核验：2026-11-17；[来源1](https://github.com/nexu-io/openmotion/blob/fcbaa2b0296167b0f14f47aa6c414f5bdd41316f/README.md#L40) · [来源2](https://github.com/nexu-io/openmotion/blob/fcbaa2b0296167b0f14f47aa6c414f5bdd41316f/README.md#L308) · [来源3](https://github.com/nexu-io/openmotion/blob/fcbaa2b0296167b0f14f47aa6c414f5bdd41316f/README.md#L386)。

## [OpenMontage](https://github.com/OpenMontageInc/OpenMontage)

面向 coding agent 的多管线视频生产系统，覆盖研究、脚本、素材、配音、字幕和渲染。

- 分类：Agent 视频生产与自动化；核心候选。
- 适用边界：部分生成与语音提供商为付费服务；大量 Skill 文件不等于全部流程已统一实测。
- 维护状态：近90天有提交；30 天提交 143 次，90 天提交 267 次。
- 许可：[AGPL-3.0](https://api.github.com/repos/OpenMontageInc/OpenMontage/license)；开放许可证已核验。GitHub licenseInfo 识别；模型权重、素材、字体、第三方依赖和托管服务许可另计
- 功能核验：2026-11-12；[来源1](https://github.com/OpenMontageInc/OpenMontage/blob/fecb9a1e3cc23ef84de30b272059457a427f16f8/README.md#L14)。

## [OpenFilm](https://github.com/openfilm/openfilm)

让 coding agent 以代码创建、检查、编辑和渲染视频，并提供可编辑界面。

- 分类：Agent 视频生产与自动化；核心候选。
- 适用边界：代码化镜头与传统素材时间线不同；素材和声音库许可需按资产核验。
- 维护状态：近90天有提交；30 天提交 115 次，90 天提交 307 次。
- 许可：[MIT](https://api.github.com/repos/openfilm/openfilm/license)；开放许可证已核验。GitHub licenseInfo 识别；模型权重、素材、字体、第三方依赖和托管服务许可另计
- 功能核验：2026-11-12；[来源1](https://github.com/openfilm/openfilm/blob/f59cd4e0973feaf6917dcf3229b178b6baf9ad3f/README.md#L7)。

## [Rea Video](https://github.com/JuneYaooo/rea-video)

逆向拆解视频的实拍、AI 与代码成分，输出分镜级复刻方案和 VIDEO.md。

- 分类：Agent 视频生产与自动化；相邻基础设施。
- 适用边界：主要做分析与复刻规划，不直接等同最终剪辑或生成器。
- 维护状态：近90天有提交；30 天提交 222 次，90 天提交 222 次。
- 许可：[Apache-2.0](https://api.github.com/repos/JuneYaooo/rea-video/license)；开放许可证已核验。GitHub licenseInfo 识别；模型权重、素材、字体、第三方依赖和托管服务许可另计
- 功能核验：2026-11-12；[来源1](https://github.com/JuneYaooo/rea-video/blob/4111ad9adb4936d92f6d57657000b414fee9f01f/README.md#L8)。

## [Video Autopilot Kit](https://github.com/Hao0321/video-autopilot-kit)

负责视频计划、审计、审片和效果学习的自动化框架。

- 分类：Agent 视频生产与自动化；核心候选。
- 适用边界：实际剪辑和渲染依赖 Editkin；单独安装本仓库不能完成成片。
- 维护状态：近90天有提交；30 天提交 9 次，90 天提交 33 次。
- 许可：[MIT](https://api.github.com/repos/Hao0321/video-autopilot-kit/license)；开放许可证已核验。GitHub licenseInfo 识别；模型权重、素材、字体、第三方依赖和托管服务许可另计
- 功能核验：2026-11-12；[来源1](https://github.com/Hao0321/video-autopilot-kit/blob/b48c7d9a624ebceaa3a99f3f4aad6006e2be53fb/README.md#L1)。

## [Video Director](https://github.com/win4r/video-director)

指导 Claude Code 用 HTML/Canvas/SVG/Three.js/GSAP/Remotion 计划、渲染和检查短片。

- 分类：Agent 视频生产与自动化；核心候选。
- 适用边界：主要针对特定 Claude 模型调优；其他 Agent 的质量未自动继承。
- 维护状态：近90天有提交；30 天提交 14 次，90 天提交 20 次。
- 许可：[MIT](https://api.github.com/repos/win4r/video-director/license)；开放许可证已核验。GitHub licenseInfo 识别；模型权重、素材、字体、第三方依赖和托管服务许可另计
- 功能核验：2026-11-12；[来源1](https://github.com/win4r/video-director/blob/02d1912ab251bf5235b45e8e7aad81b4bc786b15/README.md#L11)。

## [Video Use](https://github.com/browser-use/video-use)

通过 coding agent 与 FFmpeg 对原始素材进行剪辑、字幕、调色、动效叠加和输出检查。

- 分类：Agent 视频生产与自动化；核心候选。
- 适用边界：不是浏览器自动化视频操作工具；具体依赖和云服务路径按项目配置核验。
- 维护状态：近90天有提交；30 天提交 0 次，90 天提交 2 次。
- 许可：[MIT](https://github.com/browser-use/video-use/blob/43cfc566833548093455c9d4a46bd69913b7e552/LICENSE)；开放许可证已核验。根 LICENSE 为 MIT；模型服务、素材和外部依赖许可另计。
- 功能核验：2026-11-21；[来源1](https://github.com/browser-use/video-use/blob/43cfc566833548093455c9d4a46bd69913b7e552/README.md#L7)。

## [WeVisCut](https://github.com/Tencent/WeVisCut)

将知识文章或解说稿通过规划、素材检索、剪辑、检查和修复生成多分钟视频。

- 分类：Agent 视频生产与自动化；核心候选。
- 适用边界：9B 策略模型、工具运行时与 Studio 需要按官方环境部署；作者结果不作为跨项目排名。
- 维护状态：近90天有提交；30 天提交 2 次，90 天提交 27 次。
- 许可：[Apache-2.0](https://github.com/Tencent/WeVisCut/blob/94dc8a7fe43a5e0da21e97d5aaf470a39329db3a/LICENSE)；开放许可证已核验。根目录 LICENSE 明确代码、参数和公开权重采用 Apache-2.0；第三方组件另计
- 功能核验：2026-11-12；[来源1](https://github.com/Tencent/WeVisCut/blob/94dc8a7fe43a5e0da21e97d5aaf470a39329db3a/README.md#L7)。

## [NeonClipping](https://github.com/iamajmeena/neonclipping)

粘贴链接就在本地把 YouTube/Twitch/Kick 长视频或自有 MP4 切成带烧录字幕的 9:16 片段，并生成标题与钩子。

- 分类：知识类短视频、切片与讲解；核心候选。
- 适用边界：剪辑依赖 yt-dlp、Streamlink、faster-whisper、FFmpeg 与可选本地 Ollama 模型；无 YouTube 字幕的素材需本地识别或导入字幕，质量会下降；README 的速度与 187 项检查为作者自测，非独立基准；下载与再分发受平台条款和素材授权约束。
- 维护状态：近90天有提交；30 天提交 89 次，90 天提交 89 次。
- 许可：[MIT](https://github.com/iamajmeena/neonclipping/blob/052500437bc8d44ed5c8311e8ce686373e098086/LICENSE)；开放许可证已核验。仓库根 LICENSE 为 MIT；requirements 中的 yt-dlp、faster-whisper、Streamlink、av、static-ffmpeg 等依赖，以及 Ollama 拉取的模型权重与系统字体许可另计
- 功能核验：2026-11-23；[来源1](https://github.com/iamajmeena/neonclipping/blob/052500437bc8d44ed5c8311e8ce686373e098086/README.md#L5) · [来源2](https://github.com/iamajmeena/neonclipping/blob/052500437bc8d44ed5c8311e8ce686373e098086/README.md#L45) · [来源3](https://github.com/iamajmeena/neonclipping/blob/052500437bc8d44ed5c8311e8ce686373e098086/README.md#L114)。

## [Clipmint](https://github.com/kleZ799/clipmint)

把播客、访谈、教程和 VOD 变成带字幕的竖屏 Shorts/Reels/TikTok。

- 分类：知识类短视频、切片与讲解；核心候选。
- 适用边界：亮点识别、裁切和上传依赖本地模型及平台配置。
- 维护状态：近90天有提交；30 天提交 185 次，90 天提交 615 次。
- 许可：[MIT](https://api.github.com/repos/kleZ799/clipmint/license)；开放许可证已核验。GitHub licenseInfo 识别；模型权重、素材、字体、第三方依赖和托管服务许可另计
- 功能核验：2026-11-12；[来源1](https://github.com/kleZ799/clipmint/blob/f2f7ed16871a390d0fd5274fb28b157f22ac57e3/README.md#L7)。

## [ChrisHKAI Video](https://github.com/ChrisHKAI/ChrisHKAI-Video)

把创作者公开资料组织为 3D 玩具风短片的 coding-agent Skill。

- 分类：知识类短视频、切片与讲解；核心候选。
- 适用边界：Codex 完整成片质量尚未验证；公开资料使用和肖像授权需由用户负责。
- 维护状态：近90天有提交；30 天提交 159 次，90 天提交 208 次。
- 许可：[MIT](https://api.github.com/repos/ChrisHKAI/ChrisHKAI-Video/license)；开放许可证已核验。GitHub licenseInfo 识别；模型权重、素材、字体、第三方依赖和托管服务许可另计
- 功能核验：2026-11-12；[来源1](https://github.com/ChrisHKAI/ChrisHKAI-Video/blob/15b66ee613e621f82ba781d27547a67e76c55f50/README.md#L7)。

## [Lanshu AI Presenter Video](https://github.com/cclank/lanshu-create-ai-presenter-video)

把主题或脚本制作成经核验的数字人/风格化讲解视频的 Agent Skill。

- 分类：知识类短视频、切片与讲解；核心候选。
- 适用边界：数字人、声音、唇同步和识别由运行时选择的外部提供商决定。
- 维护状态：近90天有提交；30 天提交 1 次，90 天提交 17 次。
- 许可：[MIT](https://api.github.com/repos/cclank/lanshu-create-ai-presenter-video/license)；开放许可证已核验。GitHub licenseInfo 识别；模型权重、素材、字体、第三方依赖和托管服务许可另计
- 功能核验：2026-11-12；[来源1](https://github.com/cclank/lanshu-create-ai-presenter-video/blob/762d3ee42623b75a4ec63ad6aa61ace69d78ce6e/README.md#L23)。

## [Claude Animated Shorts](https://github.com/mromidev/claude-animated-shorts)

用 Three.js、Remotion、配乐与音效制作竖屏动画故事短片的 Skill。

- 分类：知识类短视频、切片与讲解；核心候选。
- 适用边界：基于一个已完成样片的方法包，题材和视觉泛化需实测。
- 维护状态：近90天有提交；30 天提交 2 次，90 天提交 2 次。
- 许可：[MIT](https://api.github.com/repos/mromidev/claude-animated-shorts/license)；开放许可证已核验。GitHub licenseInfo 识别；模型权重、素材、字体、第三方依赖和托管服务许可另计
- 功能核验：2026-11-12；[来源1](https://github.com/mromidev/claude-animated-shorts/blob/e3b817b6afc6cd413466d43f11ba31209e034bbf/README.md#L5)。

## [Vibe Knowledge](https://github.com/andyhuo520/vibe-knowledge)

从知识点查证、写稿、配音、代码成片到质检和发布包的知识短片 Skill。

- 分类：知识类短视频、切片与讲解；核心候选。
- 适用边界：增强镜头可能调用外部生成平台；基础代码插画与增强档应分开比较。
- 维护状态：近90天有提交；30 天提交 0 次，90 天提交 3 次。
- 许可：[MIT](https://api.github.com/repos/andyhuo520/vibe-knowledge/license)；开放许可证已核验。GitHub licenseInfo 识别；模型权重、素材、字体、第三方依赖和托管服务许可另计
- 功能核验：2026-11-12；[来源1](https://github.com/andyhuo520/vibe-knowledge/blob/c3a13a85f7cc560e5d396f063baecea4b2748e1e/README.md#L5)。

## [Vox Director](https://github.com/alisa0808/vox-director)

从主题到 Vox 风纸张拼贴讲解/广告视频的端到端 Agent Skill。

- 分类：知识类短视频、切片与讲解；核心候选。
- 适用边界：素材生成依赖 Atlas Cloud 与 FFmpeg；风格模仿需注意品牌和版权边界。
- 维护状态：近90天有提交；30 天提交 0 次，90 天提交 1 次。
- 许可：[MIT](https://api.github.com/repos/alisa0808/vox-director/license)；开放许可证已核验。GitHub licenseInfo 识别；模型权重、素材、字体、第三方依赖和托管服务许可另计
- 功能核验：2026-11-12；[来源1](https://github.com/alisa0808/vox-director/blob/6a85a7c341610442a6a5b1885e6e0217ab82a11f/README.md#L5)。

## [Video to Shorts Skill](https://github.com/social-media-skills/video-to-shorts-skill)

让 Agent 把长视频或播客变成逐词字幕竖屏短片并可选发布。

- 分类：知识类短视频、切片与讲解；核心候选。
- 适用边界：自动发布涉及平台凭证；下载源视频时应遵守平台条款和授权。
- 维护状态：近90天有提交；30 天提交 3 次，90 天提交 3 次。
- 许可：[MIT](https://api.github.com/repos/social-media-skills/video-to-shorts-skill/license)；开放许可证已核验。GitHub licenseInfo 识别；模型权重、素材、字体、第三方依赖和托管服务许可另计
- 功能核验：2026-11-12；[来源1](https://github.com/social-media-skills/video-to-shorts-skill/blob/2e20fb008b584f3927798f36f580401d75318600/README.md#L3)。

## [Pixelle-Video](https://github.com/ATH-MaaS/Pixelle-Video)

输入主题后生成文案、配图或视频、配音并合成短视频，支持 ComfyUI 工作流与媒体 API。

- 分类：知识类短视频、切片与讲解；核心候选。
- 适用边界：原 AIDC-AI 地址已迁移；本地 ComfyUI、RunningHub 或模型 API 的配置、费用和素材许可需分别核验。
- 维护状态：91–365天未提交；30 天提交 0 次，90 天提交 0 次。
- 许可：[Apache-2.0](https://github.com/ATH-MaaS/Pixelle-Video/blob/848b054e4fae40dabc62ec58e960b573e83793ac/LICENSE)；开放许可证已核验。根目录 LICENSE 为 Apache-2.0；NOTICE 列出第三方依赖及相应许可。
- 功能核验：2026-11-20；[来源1](https://github.com/ATH-MaaS/Pixelle-Video/blob/848b054e4fae40dabc62ec58e960b573e83793ac/README.md#L52)。

## [Atlas Explainer](https://github.com/AtlasCloudAI/atlas-explainer)

从一个主题生成配音、纸艺风知识讲解视频的 Skill/CLI。

- 分类：知识类短视频、切片与讲解；核心候选。
- 适用边界：图像、语音等生成依赖 Atlas Cloud API，不是完全本地生产链。
- 维护状态：91–365天未提交；30 天提交 0 次，90 天提交 0 次。
- 许可：[MIT](https://api.github.com/repos/AtlasCloudAI/atlas-explainer/license)；开放许可证已核验。GitHub licenseInfo 识别；模型权重、素材、字体、第三方依赖和托管服务许可另计
- 功能核验：2026-11-12；[来源1](https://github.com/AtlasCloudAI/atlas-explainer/blob/02f0d82392191a1c980a8a40348eb686b9e157dd/README.md#L3)。

## [FFmpeg Skill](https://github.com/kajisho5/ffmpeg-skill)

为 coding agent 提供本地 FFmpeg 剪辑、字幕、格式导出和输出检查的 CLI 与 MCP。

- 分类：Agent Skills、MCP 与剪辑工具；核心候选。
- 适用边界：需要本机 FFmpeg 和 Python；技能、FFmpeg 构建及素材遵循各自许可，具体效果未实测。
- 维护状态：近90天有提交；30 天提交 614 次，90 天提交 1044 次。
- 许可：[MIT](https://github.com/kajisho5/ffmpeg-skill/blob/45df6b9ab0740cecc15d0169165e8cfbcefdfb0b/LICENSE)；开放许可证已核验。技能仓库根 LICENSE 为 MIT；FFmpeg 及编码器许可需按具体构建核验。
- 功能核验：2026-11-21；[来源1](https://github.com/kajisho5/ffmpeg-skill/blob/45df6b9ab0740cecc15d0169165e8cfbcefdfb0b/README.md#L67)。

## [Claude Code Video Toolkit](https://github.com/digitalsamba/claude-code-video-toolkit)

为 Claude Code 提供脚本、配音、音乐、图像与视频生成、质检、渲染和发布的 Skills、模板、命令与工具，并可迁移到 Codex、Kiro CLI。

- 分类：Agent Skills、MCP 与剪辑工具；核心候选。
- 适用边界：需要 Node 22+ 与 Claude Code，AI 模型部署在你自己的 Modal/RunPod 云 GPU 账户按成本计费；README 的 $0.33 成本与示例片为作者自测；社区插件、第三方设计 Skill 与托管发布服务各有许可与条款；生成内容、克隆声音和素材授权需自行核验。
- 维护状态：近90天有提交；30 天提交 416 次，90 天提交 550 次。
- 许可：[MIT](https://github.com/digitalsamba/claude-code-video-toolkit/blob/b3437fcd462c23b3c46cfd28f8cb61b71039269b/LICENSE)；开放许可证已核验。仓库根 LICENSE 为 MIT（版权 Digital Samba）；调用的 Qwen3-TTS、FLUX.2、Ideogram 4、ACE-Step、LTX-Video 等模型权重、ElevenLabs 等外部服务、Remotion 渲染器与社区插件（如 PolyForm Perimeter 的 arkiv）许可各自独立
- 功能核验：2026-11-24；[来源1](https://github.com/digitalsamba/claude-code-video-toolkit/blob/b3437fcd462c23b3c46cfd28f8cb61b71039269b/README.md#L9) · [来源2](https://github.com/digitalsamba/claude-code-video-toolkit/blob/b3437fcd462c23b3c46cfd28f8cb61b71039269b/README.md#L12) · [来源3](https://github.com/digitalsamba/claude-code-video-toolkit/blob/b3437fcd462c23b3c46cfd28f8cb61b71039269b/README.md#L66)。

## [Video Shotcraft](https://github.com/Vincentwei1021/video-shotcraft)

为 Agent 提供镜头配方、故事板、Remotion 动画、节拍剪辑与逐帧检查。

- 分类：Agent Skills、MCP 与剪辑工具；核心候选。
- 适用边界：镜头库是创作方法和代码资产，不能替代通用时间线编辑器。
- 维护状态：近90天有提交；30 天提交 36 次，90 天提交 56 次。
- 许可：[Apache-2.0](https://api.github.com/repos/Vincentwei1021/video-shotcraft/license)；开放许可证已核验。GitHub licenseInfo 识别；模型权重、素材、字体、第三方依赖和托管服务许可另计
- 功能核验：2026-11-12；[来源1](https://github.com/Vincentwei1021/video-shotcraft/blob/6700db2ba80572ebc777b99d72049679fed9840c/README.md#L26)。

## [Remocn](https://github.com/Remocn/remocn)

面向 Remotion 出片的 Claude Code 插件、Agent Skill 与 MCP server，用 935 个 MIT 组件先出分镜再写视频代码。

- 分类：Agent Skills、MCP 与剪辑工具；核心候选。
- 适用边界：前置依赖 Remotion 与 shadcn CLI 安装组件；`scene-reviewer` 只检查静态帧的裁字、空帧与低对比，成片质量与渲染耗时未实测；组件、字体与托管 MCP 各自另有条款，Remotion 本身按其自有许可需单独确认。
- 维护状态：近90天有提交；30 天提交 151 次，90 天提交 189 次。
- 许可：[MIT](https://github.com/Remocn/remocn/blob/ac1e4081edcc70757db4dc4af32b079cb9ae5490/LICENSE)；开放许可证已核验。仓库根 LICENSE 为 MIT；README 称组件本身 MIT，但 Remotion 渲染器、字体与托管 MCP 服务按各自条款另行核验
- 功能核验：2026-11-26；[来源1](https://github.com/Remocn/remocn/blob/ac1e4081edcc70757db4dc4af32b079cb9ae5490/README.md#L9) · [来源2](https://github.com/Remocn/remocn/blob/ac1e4081edcc70757db4dc4af32b079cb9ae5490/README.md#L37) · [来源3](https://github.com/Remocn/remocn/blob/ac1e4081edcc70757db4dc4af32b079cb9ae5490/README.md#L73)。

## [Kinocut](https://github.com/KyaniteLabs/kinocut)

带防护、预检、收据和质量门的本地视频编辑 MCP/Python/CLI。

- 分类：Agent Skills、MCP 与剪辑工具；核心候选。
- 适用边界：包装 FFmpeg 和可选 Whisper/HyperFrames；类型化工具不保证剪辑审美。
- 维护状态：近90天有提交；30 天提交 371 次，90 天提交 698 次。
- 许可：[Apache-2.0](https://api.github.com/repos/KyaniteLabs/kinocut/license)；开放许可证已核验。GitHub licenseInfo 识别；模型权重、素材、字体、第三方依赖和托管服务许可另计
- 功能核验：2026-11-12；[来源1](https://github.com/KyaniteLabs/kinocut/blob/4ad02dba114cf12163663e7cd39da92d4f735212/README.md#L13)。

## [漫剧老李 Skill](https://github.com/lixiaoxiao9888-create/manju-laoli-skill)

面向 AI 漫剧与短剧的 OpenClaw Skill 套装，覆盖剧本、资产锁定、分镜、打戏、Seedance 投喂提示词与机检。

- 分类：Agent Skills、MCP 与剪辑工具；核心候选。
- 适用边界：面向 OpenClaw、Coze、Dify 等 Agent 平台，包内唯一视频模型线为 Seedance 2.5/2.0；作者标注为测试版且整合开源内容，外部规则与素材来源未逐项列明；包内不持有图片，素材需在外部平台生成并自行取得授权。
- 维护状态：近90天有提交；30 天提交 10 次，90 天提交 53 次。
- 许可：[MIT](https://github.com/lixiaoxiao9888-create/manju-laoli-skill/blob/a01e647ac10134918a5de1b18bfe9317e5541a44/LICENSE)；开放许可证已核验。仓库根与 short-drama-director 均为 MIT；作者标注为测试版并整合开源内容，未提供逐项第三方 NOTICE，规则库文本与示例的再分发需自行核验
- 功能核验：2026-11-23；[来源1](https://github.com/lixiaoxiao9888-create/manju-laoli-skill/blob/a01e647ac10134918a5de1b18bfe9317e5541a44/README.md#L60) · [来源2](https://github.com/lixiaoxiao9888-create/manju-laoli-skill/blob/a01e647ac10134918a5de1b18bfe9317e5541a44/README.md#L72) · [来源3](https://github.com/lixiaoxiao9888-create/manju-laoli-skill/blob/a01e647ac10134918a5de1b18bfe9317e5541a44/README.md#L137)。

## [Remotion Agent Skills](https://github.com/remotion-dev/skills)

供 coding agent 创建、预览和渲染 Remotion 视频的官方 Skills。

- 分类：Agent Skills、MCP 与剪辑工具；核心候选。
- 适用边界：需 Remotion 与支持 Agent Skills 的宿主；本仓库根目录未发现许可证，Remotion 本身有独立许可条款。
- 维护状态：近90天有提交；30 天提交 9 次，90 天提交 31 次。
- 许可：[许可待核验](https://github.com/remotion-dev/skills/tree/6f55706d1069e512430582ad86e4e57dc07afe1b)；许可待核验。仓库根目录和文件树未发现 LICENSE；Remotion 产品及各包许可须单独核对。
- 功能核验：2026-11-20；[来源1](https://github.com/remotion-dev/skills/blob/6f55706d1069e512430582ad86e4e57dc07afe1b/README.md#L5)。

## [pixelfx](https://github.com/patch-gg/pixelfx)

244 个以代码绘制的像素特效与动画库，附 Claude Code 特效生成 Skill 和精灵表、GIF/MP4 导出工具。

- 分类：Agent Skills、MCP 与剪辑工具；核心候选。
- 适用边界：是特效与动作素材库，不含脚本、剪辑与发布流程；`gallery/fonts` 的 Patch Pixel 字体为 Patch 自有版权、不在 MIT 内；部分代码改编自 Sprite Fusion 与 Hollow Crown（均 MIT），需按 NOTICE 保留归属；导出素材用于视频时仍需自行确认画面中的第三方内容授权。
- 维护状态：近90天有提交；30 天提交 10 次，90 天提交 10 次。
- 许可：[MIT（代码与特效）+ Patch Pixel 字体除外](https://github.com/patch-gg/pixelfx/blob/5294518ce7c72e48b6100a744596e0acf57f2826/NOTICE.md)；复合/条件许可。README 声明代码与特效 MIT、可商用；NOTICE 列出改编自 Hugo Duprez 的 Sprite Fusion 特效与 Hollow Crown（均 MIT）需保留归属，`gallery/fonts/PatchPixel-Regular.woff2` 为 Patch 保留所有权利、不在 MIT 范围内
- 功能核验：2026-11-24；[来源1](https://github.com/patch-gg/pixelfx/blob/5294518ce7c72e48b6100a744596e0acf57f2826/README.md#L7) · [来源2](https://github.com/patch-gg/pixelfx/blob/5294518ce7c72e48b6100a744596e0acf57f2826/README.md#L89) · [来源3](https://github.com/patch-gg/pixelfx/blob/5294518ce7c72e48b6100a744596e0acf57f2826/README.md#L156)。

## [Wallstreet Explainer](https://github.com/HeyChengC/wallstreet-explainer)

华尔街式财经/科技解读短片的 coding agent Skill，含风格语言、图形组件模板与找片、截图、配音、抠像、渲染、混音脚本。

- 分类：Agent Skills、MCP 与剪辑工具；核心候选。
- 适用边界：需要 Claude Code 等宿主，另装 ffmpeg、Python/Node 依赖、Playwright 并自行下载五种字体；素材靠 yt-dlp 下载和新闻网页截图，按评论解读引用，出处与再分发授权需自行核验；样片中的第三方画面、截图、logo 和人物不在 MIT 范围内。
- 维护状态：近90天有提交；30 天提交 10 次，90 天提交 16 次。
- 许可：[MIT（代码与文档）+ 样片第三方素材除外](https://github.com/HeyChengC/wallstreet-explainer/blob/b79bc0573455cb5fe335e78f653012e658fa9758/LICENSE)；复合/条件许可。LICENSE 为 MIT 正文加附加条款，明确 examples/ 的视频帧、新闻截图、logo 和照片不在许可内；GitHub 因此识别为 NOASSERTION。字体需自行下载，遵循各自字体许可
- 功能核验：2026-11-23；[来源1](https://github.com/HeyChengC/wallstreet-explainer/blob/b79bc0573455cb5fe335e78f653012e658fa9758/README.md#L3) · [来源2](https://github.com/HeyChengC/wallstreet-explainer/blob/b79bc0573455cb5fe335e78f653012e658fa9758/README.md#L37) · [来源3](https://github.com/HeyChengC/wallstreet-explainer/blob/b79bc0573455cb5fe335e78f653012e658fa9758/README.md#L92)。

## [Awesome Motion Design Agent Skills](https://github.com/frankxai/awesome-motion-design-agent-skills)

五个可安装的 SKILL.md 动效工作流（含 remotion-video-agent、web-motion-auditor）加 GSAP、Motion、Remotion、Rive、Lottie 与 3D 工具索引。

- 分类：Agent Skills、MCP 与剪辑工具；核心候选。
- 适用边界：索引条目指向第三方仓库，其许可与可用性需各自核验；技能只提供方法、检查清单与路由，实际动效与视频质量取决于宿主 Agent 与所选库；README 建议先用 SkillSpector 扫描第三方技能包再装入真实环境。
- 维护状态：近90天有提交；30 天提交 14 次，90 天提交 24 次。
- 许可：[CC0-1.0](https://github.com/frankxai/awesome-motion-design-agent-skills/blob/e7dc6e2e728c918ffcea5edb2d7c94e2a6f7785d/LICENSE)；开放许可证已核验。仓库根 LICENSE 为 CC0 1.0 Universal；索引与技能所指向的第三方项目、字体与素材仍受各自许可约束
- 功能核验：2026-11-26；[来源1](https://github.com/frankxai/awesome-motion-design-agent-skills/blob/e7dc6e2e728c918ffcea5edb2d7c94e2a6f7785d/README.md#L15) · [来源2](https://github.com/frankxai/awesome-motion-design-agent-skills/blob/e7dc6e2e728c918ffcea5edb2d7c94e2a6f7785d/README.md#L51) · [来源3](https://github.com/frankxai/awesome-motion-design-agent-skills/blob/e7dc6e2e728c918ffcea5edb2d7c94e2a6f7785d/README.md#L57)。

## [ReelBench Skills](https://github.com/eternityspring/reelbench-skills)

面向 Claude Code/Codex 的视频分析、复刻和制作 Skill 集合。

- 分类：Agent Skills、MCP 与剪辑工具；核心候选。
- 适用边界：部分关联产品和素材服务为付费或外部提供，需按具体 Skill 核验。
- 维护状态：近90天有提交；30 天提交 1 次，90 天提交 21 次。
- 许可：[Apache-2.0](https://api.github.com/repos/eternityspring/reelbench-skills/license)；开放许可证已核验。GitHub licenseInfo 识别；模型权重、素材、字体、第三方依赖和托管服务许可另计
- 功能核验：2026-11-12；[来源1](https://github.com/eternityspring/reelbench-skills/blob/8d8444894524c9beedbf8815dab517afb3ce3cbe/README.md#L5)。

## [Video Agent Skills](https://github.com/Melvynx/video-agent-skills)

用 Markdown Skills 组织短视频/YouTube 的脚本、研究、剪辑、翻译和发布。

- 分类：Agent Skills、MCP 与剪辑工具；核心候选。
- 适用边界：Skill 本身不包含所有模型与渲染器，需要宿主和本地工具。
- 维护状态：近90天有提交；30 天提交 2 次，90 天提交 27 次。
- 许可：[MIT](https://api.github.com/repos/Melvynx/video-agent-skills/license)；开放许可证已核验。GitHub licenseInfo 识别；模型权重、素材、字体、第三方依赖和托管服务许可另计
- 功能核验：2026-11-12；[来源1](https://github.com/Melvynx/video-agent-skills/blob/f4542923f7f796a1fa0e544cbfc1109d5eec87d8/README.md#L3)。

## [AI Filmmaking Camera Control (Seedance 2.5)](https://github.com/sirioberati/ai-filmmaking-camera-control-seedance-2-5)

137 套电影级运镜模板与 previs 管线：用 three.js + Remotion 渲染「条纹胶囊」参考视频，配现成提示词交给 Seedance 2.5 生成，含 Tein MCP/API 接入与 cinematic-previs 技能。

- 分类：Agent Skills、MCP 与剪辑工具；核心候选。
- 适用边界：成片必须走 Tein（tein.ai）托管的 Seedance 2.5，需自备密钥（仓库不存密钥，但首页与仓库描述直接导流该服务），draft 为 480p 更便宜；渲染需 Node 22.12+、ffmpeg 与首次联网下载 headless Chrome，仓库内 pill.mp4 多为 960 宽缩略副本，完整结果视频在 v0.1.0 release 的 zip 而非 git；137 条方法问答中 4 条被作者标为 UNPROVEN；NOTICE.md 记录 33 条相机预设蒸馏自 E.T. 数据集（源片段为受版权电影，仓库只发曲线）、示例含作者真人面孔与声音、部分产品照带可见品牌标记，均不在 MIT 范围；Remotion 对个人、≤3 人营利组织与非营利免费，更大营利团队需公司许可；仓库 2026-11-07 创建并于同日最后一次推送，运镜效果与成片质量未实机复现。
- 维护状态：近90天有提交；30 天提交 5 次，90 天提交 5 次。
- 许可：[MIT（代码/提示词/笔记/pill 片段）+ Remotion 自有许可、Quaternius CC0、第三方素材除外](https://github.com/sirioberati/ai-filmmaking-camera-control-seedance-2-5/blob/602aa2348b0ae67589ce533fff571adced724811/NOTICE.md)；复合/条件许可。仓库根 LICENSE 为 MIT，但只覆盖代码、提示词、笔记与自制的 pill 片段；NOTICE.md 另列 Quaternius 动画 rig（CC0，附原文与校验和）、Remotion 4.0.522（个人、≤3 人营利组织与非营利免费，更大营利团队需公司许可）、three.js/React/three-gpu-pathtracer（MIT）与 Rapier（Apache-2.0）；示例中的真人面孔与声音、带品牌标记的产品照、以及蒸馏自受版权电影的 33 条相机曲线均不在 MIT 授权范围，商用前需自行核验数据集与服务条款
- 功能核验：2026-11-27；[来源1](https://github.com/sirioberati/ai-filmmaking-camera-control-seedance-2-5/blob/602aa2348b0ae67589ce533fff571adced724811/README.md#L3) · [来源2](https://github.com/sirioberati/ai-filmmaking-camera-control-seedance-2-5/blob/602aa2348b0ae67589ce533fff571adced724811/README.md#L8) · [来源3](https://github.com/sirioberati/ai-filmmaking-camera-control-seedance-2-5/blob/602aa2348b0ae67589ce533fff571adced724811/README.md#L84) · [来源4](https://github.com/sirioberati/ai-filmmaking-camera-control-seedance-2-5/blob/602aa2348b0ae67589ce533fff571adced724811/NOTICE.md#L9) · [来源5](https://github.com/sirioberati/ai-filmmaking-camera-control-seedance-2-5/blob/602aa2348b0ae67589ce533fff571adced724811/NOTICE.md#L14)。

## [HyperFrames Motion Library](https://github.com/nutllwhy/hyperframes-motion-library)

以 HyperFrames 为内核的本地动效模板与参数化资产库。

- 分类：Agent Skills、MCP 与剪辑工具；核心候选。
- 适用边界：是动效资产库，不包含完整脚本、素材生成和发布流程。
- 维护状态：近90天有提交；30 天提交 0 次，90 天提交 2 次。
- 许可：[MIT](https://api.github.com/repos/nutllwhy/hyperframes-motion-library/license)；开放许可证已核验。GitHub licenseInfo 识别；模型权重、素材、字体、第三方依赖和托管服务许可另计
- 功能核验：2026-11-12；[来源1](https://github.com/nutllwhy/hyperframes-motion-library/blob/98c40ca18f23d7dc021a5d84308ab10599482cff/README.md#L3)。

## [Video Editing Skill](https://github.com/social-media-skills/video-editing-skill)

让 Agent 对口播、课程、访谈和 vlog 执行第一遍剪辑与字幕处理。

- 分类：Agent Skills、MCP 与剪辑工具；核心候选。
- 适用边界：针对第一遍粗剪，不代替人工终审、调色和复杂包装。
- 维护状态：近90天有提交；30 天提交 3 次，90 天提交 3 次。
- 许可：[MIT](https://api.github.com/repos/social-media-skills/video-editing-skill/license)；开放许可证已核验。GitHub licenseInfo 识别；模型权重、素材、字体、第三方依赖和托管服务许可另计
- 功能核验：2026-11-12；[来源1](https://github.com/social-media-skills/video-editing-skill/blob/f94d0517d717de281ee23569094aac616d32f4ef/README.md#L1)。

## [GSAP Skills](https://github.com/greensock/gsap-skills)

官方 Agent Skills，指导 coding agent 使用 GSAP 时间线、动效和插件。

- 分类：Agent Skills、MCP 与剪辑工具；核心候选。
- 适用边界：网页动画 Skill，需要宿主 Agent；渲染成视频需配合视频工具，GSAP 产品许可另核。
- 维护状态：91–365天未提交；30 天提交 0 次，90 天提交 0 次。
- 许可：[MIT](https://github.com/greensock/gsap-skills/blob/aed9cfd3277740755f6bfc1155c7aa645403b760/LICENSE)；开放许可证已核验。Skills 仓库根 LICENSE 为 MIT；GSAP 库和第三方素材按各自条款。
- 功能核验：2026-11-21；[来源1](https://github.com/greensock/gsap-skills/blob/aed9cfd3277740755f6bfc1155c7aa645403b760/README.md#L23)。

## [Narrator AI CLI Skill](https://github.com/NarratorAI-Studio/narrator-ai-cli-skill)

指导 Agent 调用 narrator-ai-cli 自动制作影视解说视频。

- 分类：Agent Skills、MCP 与剪辑工具；核心候选。
- 适用边界：是 CLI 的机器可读 Skill，不是独立渲染引擎；后端服务和模板另计。
- 维护状态：91–365天未提交；30 天提交 0 次，90 天提交 0 次。
- 许可：[MIT](https://api.github.com/repos/NarratorAI-Studio/narrator-ai-cli-skill/license)；开放许可证已核验。GitHub licenseInfo 识别；模型权重、素材、字体、第三方依赖和托管服务许可另计
- 功能核验：2026-11-12；[来源1](https://github.com/NarratorAI-Studio/narrator-ai-cli-skill/blob/4b17c6f2175bd532c92db778a847f8fb6bdd3177/README.md#L9)。

## [OpenClip Agent Skills](https://github.com/OpenClip-App/agent-skills)

为 Agent 提供长视频切片、转录、转换、缩略图、抠图和 UGC 创意 Skill。

- 分类：Agent Skills、MCP 与剪辑工具；核心候选。
- 适用边界：Skill 驱动托管 OpenClip MCP；视频和凭证会经过外部服务。
- 维护状态：91–365天未提交；30 天提交 0 次，90 天提交 0 次。
- 许可：[MIT](https://api.github.com/repos/OpenClip-App/agent-skills/license)；开放许可证已核验。GitHub licenseInfo 识别；模型权重、素材、字体、第三方依赖和托管服务许可另计
- 功能核验：2026-11-12；[来源1](https://github.com/OpenClip-App/agent-skills/blob/ea02c98db69c437616df1db4a4400cde1f4a0832/README.md#L1)。

## [MCP Video Editing](https://github.com/mfortne/mcp-video-editing)

以 MCP、Python 库和 CLI 封装 FFmpeg、HyperFrames 与本地复用流程。

- 分类：Agent Skills、MCP 与剪辑工具；核心候选。
- 适用边界：实际效果依赖外部工具版本；项目与 Kinocut 同类但并非同一仓库。
- 维护状态：91–365天未提交；30 天提交 0 次，90 天提交 0 次。
- 许可：[Apache-2.0](https://api.github.com/repos/mfortne/mcp-video-editing/license)；开放许可证已核验。GitHub licenseInfo 识别；模型权重、素材、字体、第三方依赖和托管服务许可另计
- 功能核验：2026-11-12；[来源1](https://github.com/mfortne/mcp-video-editing/blob/97ecab83d26c24bfe77be663784399b203b1fa55/README.md#L3)。

## [HyperFrames](https://github.com/heygen-com/hyperframes)

基于 HTML/CSS/JS 的代码视频与 Agent Skill 生态，可从 Remotion 等迁移并逐帧验证。

- 分类：Code-to-video 与动效；核心候选。
- 适用边界：项目与 HeyGen 托管生成服务是不同层级；具体模板和外部素材许可另计。
- 维护状态：近90天有提交；30 天提交 1823 次，90 天提交 4168 次。
- 许可：[Apache-2.0](https://api.github.com/repos/heygen-com/hyperframes/license)；开放许可证已核验。GitHub licenseInfo 识别；模型权重、素材、字体、第三方依赖和托管服务许可另计
- 功能核验：2026-11-12；[来源1](https://github.com/heygen-com/hyperframes/blob/234fb1aeef13f8d86b4f7f4cb1af624db3a81ec2/README.md#L5)。

## [Remotion](https://github.com/remotion-dev/remotion)

用 React/TypeScript 以代码创建和渲染视频的基础框架。

- 分类：Code-to-video 与动效；受限许可。
- 适用边界：是通用代码视频基础设施，不自带 Agent 规划或生成模型。
- 维护状态：近90天有提交；30 天提交 2487 次，90 天提交 6839 次。
- 许可：[Remotion License](https://github.com/remotion-dev/remotion/blob/51fd2b4a06a2b2ff0d4eb058dfe4db2b7275bac3/LICENSE.md)；源码可见但非 OSI 开源。个人、非营利及小型组织可免费使用；达到条件的营利组织需要公司许可，不是常规 OSI 开源
- 功能核验：2026-11-12；[来源1](https://github.com/remotion-dev/remotion/blob/51fd2b4a06a2b2ff0d4eb058dfe4db2b7275bac3/README.md#L2)。

## [raea](https://github.com/shinyobjectz/raea)

用 React/TypeScript 编写视频、动效、3D 与游戏，并在本地 GPU 渲染的引擎与桌面 Agent 工作台。

- 分类：Code-to-video 与动效；核心候选。
- 适用边界：引擎、CLI 和桌面应用可免费使用，云存储、跨机搜索与发布属于 Pro/Team；FSL-1.1-ALv2 禁止竞争性产品，各版本发布两年后转为 Apache-2.0；示例片源、模型、二进制运行时、第三方组件和账户内素材的许可另计。
- 维护状态：近90天有提交；30 天提交 1612 次，90 天提交 1615 次。
- 许可：[FSL-1.1-ALv2](https://github.com/shinyobjectz/raea/blob/0c9fc255f2287f0530fc773b895cb5d1877a6f54/LICENSE)；源码可见但非 OSI 开源。仓库根 LICENSE 为 Functional Source License 1.1（ALv2 Future License），禁止将软件用于替代 raea 或其现有产品的商业产品/服务，各版本发布两年后转 Apache-2.0；NOTICE 与 LICENSES 另列 HyperFrames 移植、Bevy、FFmpeg、QuickJS 等第三方许可
- 功能核验：2026-11-22；[来源1](https://github.com/shinyobjectz/raea/blob/0c9fc255f2287f0530fc773b895cb5d1877a6f54/README.md#L13) · [来源2](https://github.com/shinyobjectz/raea/blob/0c9fc255f2287f0530fc773b895cb5d1877a6f54/README.md#L42) · [来源3](https://github.com/shinyobjectz/raea/blob/0c9fc255f2287f0530fc773b895cb5d1877a6f54/README.md#L111)。

## [Lemo Opuscar](https://github.com/lemomo-ai/lemo-opuscar)

提供电影风格、示例与 STYLE.md 指引，供 coding agent 用代码制作视频。

- 分类：Code-to-video 与动效；受限许可。
- 适用边界：项目建议使用 Claude 并提高推理强度；复用演示中的素材、人物、品牌与声音需分别核验。
- 维护状态：近90天有提交；30 天提交 77 次，90 天提交 151 次。
- 许可：[MIT 代码 + CC BY-NC 文档（附加许可）](https://github.com/lemomo-ai/lemo-opuscar/blob/f9e204293930952b61ba921cd8944d05f121beee/LICENSE)；复合/条件许可。代码为 MIT；Markdown 文档为 CC BY-NC 4.0，另允许为自制或客户影片阅读、修改并随项目文件交付；超出该范围的商业使用需要许可。示例素材及部分配音另有限制。
- 功能核验：2026-11-21；[来源1](https://github.com/lemomo-ai/lemo-opuscar/blob/f9e204293930952b61ba921cd8944d05f121beee/README.md#L7)。

## [Manim Community](https://github.com/ManimCommunity/manim)

用 Python 编程制作数学与知识讲解动画的视频引擎。

- 分类：Code-to-video 与动效；核心候选。
- 适用边界：适合代码化讲解；不是自动生成内容的 AI Agent，渲染依赖和字体等另计。
- 维护状态：近90天有提交；30 天提交 29 次，90 天提交 80 次。
- 许可：[MIT](https://github.com/ManimCommunity/manim/blob/ab7f9527fa2b37893aacc367e21b723845f44ef0/LICENSE)；开放许可证已核验。已核验项目许可文件；第三方组件、素材与托管服务另计。
- 功能核验：2026-11-20；[来源1](https://github.com/ManimCommunity/manim/blob/ab7f9527fa2b37893aacc367e21b723845f44ef0/README.md#L20)。

## [GiveMotion](https://github.com/givemotion/givemotion)

让 Agent 编写 HTML/CSS、预览检查并渲染 MP4 的代码视频引擎。

- 分类：Code-to-video 与动效；核心候选。
- 适用边界：代码动画适合动效和讲解，不等同真实素材剪辑或扩散视频生成。
- 维护状态：近90天有提交；30 天提交 76 次，90 天提交 255 次。
- 许可：[MIT](https://api.github.com/repos/givemotion/givemotion/license)；开放许可证已核验。GitHub licenseInfo 识别；模型权重、素材、字体、第三方依赖和托管服务许可另计
- 功能核验：2026-11-12；[来源1](https://github.com/givemotion/givemotion/blob/8a7949e685bbfaec8bde20fad9aa8734cdfa6038/README.md#L6)。

## [SenseNova Code2Video](https://github.com/OpenSenseNova/SenseNova-6.8-Code2Video)

用小型开放模型生成可执行代码并渲染短视频。

- 分类：Code-to-video 与动效；核心候选。
- 适用边界：当前聚焦纯代码短视频；模型权重、推理环境和生成工具许可需分别核验。
- 维护状态：近90天有提交；30 天提交 1 次，90 天提交 3 次。
- 许可：[待核验](https://github.com/OpenSenseNova/SenseNova-6.8-Code2Video/blob/776ae79824e338ba5d63fef66167455edc94ad26/README.md)；许可待核验。未找到根目录许可证；模型权重和代码复用条件需另行确认
- 功能核验：2026-11-12；[来源1](https://github.com/OpenSenseNova/SenseNova-6.8-Code2Video/blob/776ae79824e338ba5d63fef66167455edc94ad26/README.md#L3)。

## [Manim](https://github.com/3b1b/manim)

面向数学讲解的 Python 动画引擎。

- 分类：Code-to-video 与动效；相邻基础设施。
- 适用边界：是通用动画工具且该仓库为 3Blue1Brown 版本，不是完整 AI 视频 Agent。
- 维护状态：近90天有提交；30 天提交 0 次，90 天提交 1 次。
- 许可：[MIT](https://api.github.com/repos/3b1b/manim/license)；开放许可证已核验。GitHub licenseInfo 识别；模型权重、素材、字体、第三方依赖和托管服务许可另计
- 功能核验：2026-11-12；[来源1](https://github.com/3b1b/manim/blob/fafa083a4fb274bba9cabde0b6e2f50ba6da0622/README.md#L2)。

## [Motion Canvas](https://github.com/motion-canvas/motion-canvas)

用 TypeScript 和生成器函数创建动画、讲解和动态图形。

- 分类：Code-to-video 与动效；相邻基础设施。
- 适用边界：通用动画框架，Agent 能力来自上层 Skill 或宿主。
- 维护状态：91–365天未提交；30 天提交 0 次，90 天提交 0 次。
- 许可：[MIT](https://api.github.com/repos/motion-canvas/motion-canvas/license)；开放许可证已核验。GitHub licenseInfo 识别；模型权重、素材、字体、第三方依赖和托管服务许可另计
- 功能核验：2026-11-12；[来源1](https://github.com/motion-canvas/motion-canvas/blob/7b91435c301d530351dcf5ebb91dd139c002e405/README.md#L6)。

## [three.js](https://github.com/mrdoob/three.js)

JavaScript 三维场景和渲染库，可为代码动效提供 3D 内容。

- 分类：动画、3D 与编码基础组件；相邻基础设施。
- 适用边界：通用渲染库，不自动输出视频；素材和 WebGL/WebGPU 环境需自行处理。
- 维护状态：近90天有提交；30 天提交 316 次，90 天提交 894 次。
- 许可：[MIT](https://github.com/mrdoob/three.js/blob/8b92052852735b67cfa8393f78e707b3f07a0eec/LICENSE)；开放许可证已核验。已核验项目许可文件；第三方组件、素材与托管服务另计。
- 功能核验：2026-11-20；[来源1](https://github.com/mrdoob/three.js/blob/8b92052852735b67cfa8393f78e707b3f07a0eec/README.md#L11)。

## [Godot](https://github.com/godotengine/godot)

用于构建二维和三维场景、交互及动画的开源游戏引擎。

- 分类：动画、3D 与编码基础组件；相邻基础设施。
- 适用边界：游戏引擎与视频自动生成系统不同，成片录制或导出需设计额外流程。
- 维护状态：近90天有提交；30 天提交 517 次，90 天提交 1873 次。
- 许可：[MIT](https://github.com/godotengine/godot/blob/73ca6be2cebd5192d8b279979d04f29ea45c266e/LICENSE.txt)；开放许可证已核验。已核验项目许可文件；第三方组件、素材与托管服务另计。
- 功能核验：2026-11-20；[来源1](https://github.com/godotengine/godot/blob/73ca6be2cebd5192d8b279979d04f29ea45c266e/README.md#L11)。

## [Motion](https://github.com/motiondivision/motion)

面向 JavaScript、React 和 Vue 的界面与布局动画库。

- 分类：动画、3D 与编码基础组件；相邻基础设施。
- 适用边界：通用动效组件；与视频渲染器配合使用，不直接提供视频 Agent。
- 维护状态：近90天有提交；30 天提交 450 次，90 天提交 1396 次。
- 许可：[MIT](https://github.com/motiondivision/motion/blob/cd009de7a4314e065d4d9df683057124792d5b34/LICENSE.md)；开放许可证已核验。已核验项目许可文件；第三方组件、素材与托管服务另计。
- 功能核验：2026-11-20；[来源1](https://github.com/motiondivision/motion/blob/cd009de7a4314e065d4d9df683057124792d5b34/README.md#L3)。

## [Blender](https://github.com/blender/blender)

覆盖建模、角色绑定、动画、渲染、合成和视频剪辑的 3D 创作套件。

- 分类：动画、3D 与编码基础组件；相邻基础设施。
- 适用边界：GitHub 仓库是官方镜像；第三方插件、模型和素材遵循各自许可。
- 维护状态：近90天有提交；30 天提交 1124 次，90 天提交 3362 次。
- 许可：[GPL-2.0-or-later](https://github.com/blender/blender/blob/611d97903ad34434934f4cb1e586155c03eddd66/COPYING)；开放许可证已核验。COPYING 指向 GPL 许可正文；第三方资产和组件另计。
- 功能核验：2026-11-20；[来源1](https://github.com/blender/blender/blob/611d97903ad34434934f4cb1e586155c03eddd66/.github/README.md#L14)。

## [Babylon.js](https://github.com/BabylonJS/Babylon.js)

JavaScript 3D 场景、游戏与渲染引擎，可作为代码动效基础。

- 分类：动画、3D 与编码基础组件；相邻基础设施。
- 适用边界：默认是实时 3D 渲染引擎；视频编码需另接工具，官方提示演示 CDN 不用于生产。
- 维护状态：近90天有提交；30 天提交 146 次，90 天提交 343 次。
- 许可：[Apache-2.0](https://github.com/BabylonJS/Babylon.js/blob/6226e393cef4295d8509b8a83e82572b2af4c9c9/license.md)；开放许可证已核验。已核验项目许可文件；第三方组件、素材与托管服务另计。
- 功能核验：2026-11-20；[来源1](https://github.com/BabylonJS/Babylon.js/blob/6226e393cef4295d8509b8a83e82572b2af4c9c9/readme.md#L1)。

## [Konva](https://github.com/konvajs/konva)

二维 Canvas 场景图库，支持对象交互、变换、动画和导出。

- 分类：动画、3D 与编码基础组件；相邻基础设施。
- 适用边界：通用画布组件；视频或音频导出需搭配其他工具。
- 维护状态：近90天有提交；30 天提交 32 次，90 天提交 219 次。
- 许可：[MIT](https://github.com/konvajs/konva/blob/bf1927c1cfec7f47eb608a470aff6ca99dd09aa9/LICENSE)；开放许可证已核验。已核验项目许可文件；第三方组件、素材与托管服务另计。
- 功能核验：2026-11-20；[来源1](https://github.com/konvajs/konva/blob/bf1927c1cfec7f47eb608a470aff6ca99dd09aa9/README.md#L16)。

## [Two.js](https://github.com/jonobr1/two.js)

通过 WebGL、Canvas 或 SVG 创建二维图形和动画场景。

- 分类：动画、3D 与编码基础组件；相邻基础设施。
- 适用边界：二维绘图基础库；生成音视频文件需要另接渲染与编码。
- 维护状态：近90天有提交；30 天提交 15 次，90 天提交 44 次。
- 许可：[MIT](https://github.com/jonobr1/two.js/blob/bd48e27ff8f3333ef442fb3d032cb6b5391f26dc/LICENSE)；开放许可证已核验。已核验项目许可文件；第三方组件、素材与托管服务另计。
- 功能核验：2026-11-20；[来源1](https://github.com/jonobr1/two.js/blob/bd48e27ff8f3333ef442fb3d032cb6b5391f26dc/README.md#L8)。

## [Shifty](https://github.com/jeremyckahn/shifty)

TypeScript 补间动画引擎，提供缓动与播放控制。

- 分类：动画、3D 与编码基础组件；相邻基础设施。
- 适用边界：底层补间库，不自带视频生成或导出工作流。
- 维护状态：近90天有提交；30 天提交 8 次，90 天提交 14 次。
- 许可：[MIT](https://github.com/jeremyckahn/shifty/blob/ee4c8ed53503d5a6bf658ccdbba5af58674e3245/LICENSE-MIT)；开放许可证已核验。已核验项目许可文件；第三方组件、素材与托管服务另计。
- 功能核验：2026-11-20；[来源1](https://github.com/jeremyckahn/shifty/blob/ee4c8ed53503d5a6bf658ccdbba5af58674e3245/README.md#L7)。

## [Ola](https://github.com/franciscop/ola)

用于实时数值平滑插值的轻量动画库。

- 分类：动画、3D 与编码基础组件；相邻基础设施。
- 适用边界：仅处理数值插值，需自行提供场景、时间线与导出。
- 维护状态：近90天有提交；30 天提交 0 次，90 天提交 3 次。
- 许可：[MIT](https://github.com/franciscop/ola/blob/b269059c570405421acfcc55c84b3347cbeb0674/LICENSE)；开放许可证已核验。已核验项目许可文件；第三方组件、素材与托管服务另计。
- 功能核验：2026-11-20；[来源1](https://github.com/franciscop/ola/blob/b269059c570405421acfcc55c84b3347cbeb0674/readme.md#L3)。

## [Anime.js](https://github.com/juliangarnier/anime)

对 CSS、SVG、DOM 和 JavaScript 属性制作时间线动画。

- 分类：动画、3D 与编码基础组件；相邻基础设施。
- 适用边界：通用网页动效引擎；视频渲染和音频同步需额外工具。
- 维护状态：91–365天未提交；30 天提交 0 次，90 天提交 0 次。
- 许可：[MIT](https://github.com/juliangarnier/anime/blob/01b81be1df6843ccfe0a71c0699a746bf740dd77/LICENSE.md)；开放许可证已核验。已核验项目许可文件；第三方组件、素材与托管服务另计。
- 功能核验：2026-11-20；[来源1](https://github.com/juliangarnier/anime/blob/01b81be1df6843ccfe0a71c0699a746bf740dd77/README.md#L13)。

## [Proton](https://github.com/drawcall/Proton)

JavaScript 粒子动画库，可制作火焰、烟花和爆炸等粒子效果。

- 分类：动画、3D 与编码基础组件；相邻基础设施。
- 适用边界：特效基础库，不是独立视频渲染或剪辑工具。
- 维护状态：91–365天未提交；30 天提交 0 次，90 天提交 0 次。
- 许可：[MIT](https://github.com/drawcall/Proton/blob/b4fdef5e5416d70a788978bec0fb4a1be26514b4/LICENSE)；开放许可证已核验。已核验项目许可文件；第三方组件、素材与托管服务另计。
- 功能核验：2026-11-20；[来源1](https://github.com/drawcall/Proton/blob/b4fdef5e5416d70a788978bec0fb4a1be26514b4/README.md#L26)。

## [Lottie Web](https://github.com/airbnb/lottie-web)

在网页中解析和渲染导出的 Lottie 矢量动画。

- 分类：动画、3D 与编码基础组件；相邻基础设施。
- 适用边界：播放器不等于视频编辑器；动画资源及生成方式的许可另计。
- 维护状态：超过365天未提交；30 天提交 0 次，90 天提交 0 次。
- 许可：[MIT](https://github.com/airbnb/lottie-web/blob/bede03d25d232826e0c9dca1733d542d8a7754fb/LICENSE.md)；开放许可证已核验。已核验项目许可文件；第三方组件、素材与托管服务另计。
- 功能核验：2026-11-20；[来源1](https://github.com/airbnb/lottie-web/blob/bede03d25d232826e0c9dca1733d542d8a7754fb/README.md#L3)。

## [TweenJS](https://github.com/CreateJS/TweenJS)

为 JavaScript 数值和 CSS 属性提供补间及链式播放。

- 分类：动画、3D 与编码基础组件；相邻基础设施。
- 适用边界：补间库需要搭配渲染器和导出工具。
- 维护状态：超过365天未提交；30 天提交 0 次，90 天提交 0 次。
- 许可：[MIT](https://github.com/CreateJS/TweenJS/blob/6df2b9ce7e68d3d824cc490b67cab2bc3204810a/LICENSE.txt)；开放许可证已核验。已核验项目许可文件；第三方组件、素材与托管服务另计。
- 功能核验：2026-11-20；[来源1](https://github.com/CreateJS/TweenJS/blob/6df2b9ce7e68d3d824cc490b67cab2bc3204810a/README.md#L3)。

## [LUME](https://github.com/lume/lume)

使用 HTML 元素构建交互式二维和三维图形场景。

- 分类：动画、3D 与编码基础组件；相邻基础设施。
- 适用边界：通用 3D/图形组件，不提供完整的视频生产流程。
- 维护状态：超过365天未提交；30 天提交 0 次，90 天提交 0 次。
- 许可：[MIT](https://github.com/lume/lume/blob/6336e365f1c02af6316017bcd6d7f79bd2efe13b/LICENSE)；开放许可证已核验。已核验项目许可文件；第三方组件、素材与托管服务另计。
- 功能核验：2026-11-20；[来源1](https://github.com/lume/lume/blob/6336e365f1c02af6316017bcd6d7f79bd2efe13b/README.md#L23)。

## [gifenc](https://github.com/mattdesl/gifenc)

在浏览器或 Node.js 中编码支持动画和透明度的 GIF。

- 分类：动画、3D 与编码基础组件；相邻基础设施。
- 适用边界：输出 GIF，不直接提供 MP4 导出、视频编辑或 AI 生成。
- 维护状态：超过365天未提交；30 天提交 0 次，90 天提交 0 次。
- 许可：[MIT](https://github.com/mattdesl/gifenc/blob/27db5b982dba701ca440b55ea36fad3999040973/LICENSE.md)；开放许可证已核验。已核验项目许可文件；第三方组件、素材与托管服务另计。
- 功能核验：2026-11-20；[来源1](https://github.com/mattdesl/gifenc/blob/27db5b982dba701ca440b55ea36fad3999040973/README.md#L5)。

## [VRGameDevGirl AI Video Builder](https://github.com/vrgamegirl19/comfyui-vrgamedevgirl)

在 ComfyUI 中按场景管理规划、提示、生成、节奏、审阅和最终拼接。

- 分类：ComfyUI 与开源视频生成；受限许可。
- 适用边界：部分自定义节点已拆到独立包；模型、显存和安装兼容性需按工作流核验。
- 维护状态：近90天有提交；30 天提交 111 次，90 天提交 661 次。
- 许可：[VRGameDevGirl Community and Commercial License](https://github.com/vrgamegirl19/comfyui-vrgamedevgirl/blob/b419bb5c2468432704e0339035844620f1b3ec18/LICENSE)；源码可见但非 OSI 开源。可商业化生成内容；销售/托管/商业集成软件本身需要书面商业许可
- 功能核验：2026-11-12；[来源1](https://github.com/vrgamegirl19/comfyui-vrgamedevgirl/blob/b419bb5c2468432704e0339035844620f1b3ec18/README.md#L1)。

## [LTX-Video](https://github.com/Lightricks/LTX-Video)

面向文本/图像到视频及音画生成的开放视频模型与推理工具。

- 分类：ComfyUI 与开源视频生成；核心候选。
- 适用边界：不同 LTX 版本硬件、权重和音频能力差异明显。
- 维护状态：近90天有提交；30 天提交 2 次，90 天提交 2 次。
- 许可：[Apache-2.0](https://api.github.com/repos/Lightricks/LTX-Video/license)；开放许可证已核验。GitHub licenseInfo 识别；模型权重、素材、字体、第三方依赖和托管服务许可另计
- 功能核验：2026-11-12；[来源1](https://github.com/Lightricks/LTX-Video/blob/50f0aef1297574a4b29acbdb874e3a363a6d5f2e/README.md#L4)。

## [HunyuanVideo](https://github.com/Tencent-Hunyuan/HunyuanVideo)

腾讯开源的大型视频生成基础模型与推理框架。

- 分类：ComfyUI 与开源视频生成；受限许可。
- 适用边界：高硬件要求；代码许可与模型权重/输出政策需分别核验。
- 维护状态：近90天有提交；30 天提交 0 次，90 天提交 3 次。
- 许可：[Tencent Hunyuan Community License](https://github.com/Tencent-Hunyuan/HunyuanVideo/blob/4eda9cb44c3be82a6b9c4261897cb6bd3cfb084e/LICENSE.txt)；源码可见但非 OSI 开源。存在地域排除、使用政策和模型衍生条款，不是标准 OSI 开源许可
- 功能核验：2026-11-12；[来源1](https://github.com/Tencent-Hunyuan/HunyuanVideo/blob/4eda9cb44c3be82a6b9c4261897cb6bd3cfb084e/README.md#L1)。

## [Wan2.2](https://github.com/Wan-Video/Wan2.2)

阿里 Wan 系列开放视频生成模型，覆盖文本/图像到视频等任务。

- 分类：ComfyUI 与开源视频生成；核心候选。
- 适用边界：不同模型尺寸、活跃参数与许可条件需按具体 checkpoint 核对。
- 维护状态：近90天有提交；30 天提交 0 次，90 天提交 2 次。
- 许可：[Apache-2.0](https://api.github.com/repos/Wan-Video/Wan2.2/license)；开放许可证已核验。GitHub licenseInfo 识别；模型权重、素材、字体、第三方依赖和托管服务许可另计
- 功能核验：2026-11-12；[来源1](https://github.com/Wan-Video/Wan2.2/blob/1ea34ff48f87168174e12956e200b1d908b1c5ff/README.md#L1)。

## [Mochi](https://github.com/genmoai/mochi)

Genmo 的开源视频生成模型与推理代码。

- 分类：ComfyUI 与开源视频生成；核心候选。
- 适用边界：模型权重、显存、时长与分辨率限制需按版本验证。
- 维护状态：近90天有提交；30 天提交 0 次，90 天提交 2 次。
- 许可：[Apache-2.0](https://api.github.com/repos/genmoai/mochi/license)；开放许可证已核验。GitHub licenseInfo 识别；模型权重、素材、字体、第三方依赖和托管服务许可另计
- 功能核验：2026-11-12；[来源1](https://github.com/genmoai/mochi/blob/15c9bad662df1fa3e7b53136423695b286484c08/README.md#L1)。

## [Open-Sora](https://github.com/hpcaitech/Open-Sora)

开源高效视频生成训练与推理框架。

- 分类：ComfyUI 与开源视频生成；核心候选。
- 适用边界：研究框架和模型 checkpoint 不等于桌面成片工具。
- 维护状态：91–365天未提交；30 天提交 0 次，90 天提交 0 次。
- 许可：[Apache-2.0](https://api.github.com/repos/hpcaitech/Open-Sora/license)；开放许可证已核验。GitHub licenseInfo 识别；模型权重、素材、字体、第三方依赖和托管服务许可另计
- 功能核验：2026-11-12；[来源1](https://github.com/hpcaitech/Open-Sora/blob/7ad6a96a135feb81f755c84fb391818718f6beb2/README.md#L2)。

## [Bernini](https://github.com/bytedance/Bernini)

结合语义规划器和 DiT 渲染器的视频生成与编辑研究框架。

- 分类：ComfyUI 与开源视频生成；研究/评测。
- 适用边界：论文 benchmark 不与产品编辑器维护分混为能力结论。
- 维护状态：91–365天未提交；30 天提交 0 次，90 天提交 0 次。
- 许可：[Apache-2.0](https://api.github.com/repos/bytedance/Bernini/license)；开放许可证已核验。GitHub licenseInfo 识别；模型权重、素材、字体、第三方依赖和托管服务许可另计
- 功能核验：2026-11-12；[来源1](https://github.com/bytedance/Bernini/blob/e6c2cf11843470b08491745947abcba9c3c6b079/README.md#L3)。

## [HunyuanVideo-I2V](https://github.com/Tencent-Hunyuan/HunyuanVideo-I2V)

基于 HunyuanVideo 的可定制图生视频框架。

- 分类：ComfyUI 与开源视频生成；受限许可。
- 适用边界：与基础 T2V 项目分开；输入参考和权重许可需核对。
- 维护状态：91–365天未提交；30 天提交 0 次，90 天提交 0 次。
- 许可：[Tencent Hunyuan Community License](https://github.com/Tencent-Hunyuan/HunyuanVideo-I2V/blob/c8bba70b9517f08d770a9a2a3d1e93cc6d5b7949/LICENSE.txt)；源码可见但非 OSI 开源。存在地域排除、使用政策和模型衍生条款，不是标准 OSI 开源许可
- 功能核验：2026-11-12；[来源1](https://github.com/Tencent-Hunyuan/HunyuanVideo-I2V/blob/c8bba70b9517f08d770a9a2a3d1e93cc6d5b7949/README.md#L9)。

## [CogVideo / CogVideoX](https://github.com/zai-org/CogVideo)

开源文本/图像到视频模型与推理代码。

- 分类：ComfyUI 与开源视频生成；核心候选。
- 适用边界：模型生成器不是编辑工作台；权重、显存、分辨率和模型许可需按版本核对。
- 维护状态：超过365天未提交；30 天提交 0 次，90 天提交 0 次。
- 许可：[Apache-2.0](https://api.github.com/repos/zai-org/CogVideo/license)；开放许可证已核验。GitHub licenseInfo 识别；模型权重、素材、字体、第三方依赖和托管服务许可另计
- 功能核验：2026-11-12；[来源1](https://github.com/zai-org/CogVideo/blob/7a1af7154511e0ce4e4be8d62faa8c5e5a3532d2/README.md#L1)。

## [LiveTalking](https://github.com/lipku/LiveTalking)

结合多种数字人后端的实时交互式流媒体系统。

- 分类：数字人、肖像动画与唇同步；核心候选。
- 适用边界：不同后端的许可、硬件、延迟和效果差异很大。
- 维护状态：近90天有提交；30 天提交 6 次，90 天提交 12 次。
- 许可：[Apache-2.0](https://api.github.com/repos/lipku/LiveTalking/license)；开放许可证已核验。GitHub licenseInfo 识别；模型权重、素材、字体、第三方依赖和托管服务许可另计
- 功能核验：2026-11-12；[来源1](https://github.com/lipku/LiveTalking/blob/c7269433a2b6ecebcd9342445d2ecc882c98b0da/README.md#L250)。

## [MuseTalk](https://github.com/TMElyralab/MuseTalk)

面向实时高质量唇同步的音频驱动虚拟人模型。

- 分类：数字人、肖像动画与唇同步；核心候选。
- 适用边界：代码、模型权重、输入肖像与商业使用边界需分别核验。
- 维护状态：近90天有提交；30 天提交 1 次，90 天提交 1 次。
- 许可：[MIT](https://github.com/TMElyralab/MuseTalk/blob/0a89dec45a0192b824e3cf4daf96c239440c5ed8/LICENSE)；开放许可证已核验。根目录 LICENSE 人工核验；模型、数据和人物素材权利另计
- 功能核验：2026-11-12；[来源1](https://github.com/TMElyralab/MuseTalk/blob/0a89dec45a0192b824e3cf4daf96c239440c5ed8/README.md#L1)。

## [LivePortrait](https://github.com/KlingAIResearch/LivePortrait)

高效肖像动画、拼接和重定向控制框架。

- 分类：数字人、肖像动画与唇同步；核心候选。
- 适用边界：仓库已转移到 KlingAIResearch；驱动素材与人物授权由用户负责。
- 维护状态：91–365天未提交；30 天提交 0 次，90 天提交 0 次。
- 许可：[MIT](https://github.com/KlingAIResearch/LivePortrait/blob/9b294b3d0536135442ea73cb01e6cb3ca7029dd3/LICENSE)；开放许可证已核验。根目录 LICENSE 人工核验；模型、数据和肖像权另计
- 功能核验：2026-11-12；[来源1](https://github.com/KlingAIResearch/LivePortrait/blob/9b294b3d0536135442ea73cb01e6cb3ca7029dd3/readme.md#L1)。

## [SadTalker](https://github.com/OpenTalker/SadTalker)

从单张人像和音频生成说话头像视频。

- 分类：数字人、肖像动画与唇同步；核心候选。
- 适用边界：生成肖像涉及人物授权；模型与依赖许可需按当前仓库说明。
- 维护状态：超过365天未提交；30 天提交 0 次，90 天提交 0 次。
- 许可：[Apache-2.0](https://github.com/OpenTalker/SadTalker/blob/cd4c0465ae0b54a6f85af57f5c65fec9fe23e7f8/LICENSE)；开放许可证已核验。根目录 LICENSE 人工核验；第三方组件另计
- 功能核验：2026-11-12；[来源1](https://github.com/OpenTalker/SadTalker/blob/cd4c0465ae0b54a6f85af57f5c65fec9fe23e7f8/README.md#L6)。

## [Wav2Lip](https://github.com/Rudrabha/Wav2Lip)

经典音视频唇同步研究实现。

- 分类：数字人、肖像动画与唇同步；受限许可。
- 适用边界：开放代码/权重主要限个人、研究和非商业用途，不列入普通商用开源推荐。
- 维护状态：超过365天未提交；30 天提交 0 次，90 天提交 0 次。
- 许可：[个人/研究/非商业许可](https://github.com/Rudrabha/Wav2Lip/blob/bac9a81e63ecc153202353372e5724b83d9e6322/README.md#L207)；源码可见但非 OSI 开源。README 明确禁止开源模型的商业使用
- 功能核验：2026-11-12；[来源1](https://github.com/Rudrabha/Wav2Lip/blob/bac9a81e63ecc153202353372e5724b83d9e6322/README.md#L1)。

## [FFmpeg](https://github.com/FFmpeg/FFmpeg)

视频转码、滤镜、封装、合成和流处理的底层工具链。

- 分类：下载、采集、转码与素材 CLI；相邻基础设施。
- 适用边界：许可证随构建选项可能为 LGPL/GPL；大量上层项目只是对其封装。
- 维护状态：近90天有提交；30 天提交 432 次，90 天提交 3014 次。
- 许可：[LGPL-2.1+；启用 GPL 组件后为 GPL-2.0+](https://github.com/FFmpeg/FFmpeg/blob/23c454005319dee4a5bcae5c370f75fdeb325230/LICENSE.md)；复合/条件许可。最终许可取决于编译选项和链接组件
- 功能核验：2026-11-12；[来源1](https://github.com/FFmpeg/FFmpeg/blob/23c454005319dee4a5bcae5c370f75fdeb325230/README.md#L1)。

## [yt-dlp](https://github.com/yt-dlp/yt-dlp)

支持大量站点的功能丰富命令行音视频下载器。

- 分类：下载、采集、转码与素材 CLI；核心候选。
- 适用边界：它是 Downvid/VidBee 等产品的底层解析 CLI，不提供完整编辑工作台。
- 维护状态：近90天有提交；30 天提交 38 次，90 天提交 75 次。
- 许可：[Unlicense](https://api.github.com/repos/yt-dlp/yt-dlp/license)；开放许可证已核验。GitHub licenseInfo 识别；模型权重、素材、字体、第三方依赖和托管服务许可另计
- 功能核验：2026-11-12；[来源1](https://github.com/yt-dlp/yt-dlp/blob/412e7f0a4b0588fe884a02b344ac66a06538475b/README.md#L16)。

## [Streamlink](https://github.com/streamlink/streamlink)

把在线直播流解析并管道传给本地播放器的 CLI。

- 分类：下载、采集、转码与素材 CLI；核心候选。
- 适用边界：主要面向流播放/录制，不等同通用点播下载或编辑器。
- 维护状态：近90天有提交；30 天提交 27 次，90 天提交 156 次。
- 许可：[BSD-2-Clause](https://api.github.com/repos/streamlink/streamlink/license)；开放许可证已核验。GitHub licenseInfo 识别；模型权重、素材、字体、第三方依赖和托管服务许可另计
- 功能核验：2026-11-12；[来源1](https://github.com/streamlink/streamlink/blob/993f9f1b63bd7a87292e05eda98d461ddc1f62c9/README.md#L13)。

## [Downvid](https://github.com/Downvid/downvid)

基于 yt-dlp 与 FFmpeg 的跨平台视频下载 GUI/WebUI。

- 分类：下载、采集、转码与素材 CLI；核心候选。
- 适用边界：主要是产品层封装；站点解析能力来自 yt-dlp，使用需遵守平台条款和内容授权。
- 维护状态：近90天有提交；30 天提交 40 次，90 天提交 361 次。
- 许可：[MIT](https://api.github.com/repos/Downvid/downvid/license)；开放许可证已核验。GitHub licenseInfo 识别；模型权重、素材、字体、第三方依赖和托管服务许可另计
- 功能核验：2026-11-12；[来源1](https://github.com/Downvid/downvid/blob/770bd3e3bf6157f1a2dd0ccb67ea6ce2a4b31807/README.md#L7)。

## [VidBee](https://github.com/nexmoe/VidBee)

下载媒体，并在本地执行转录、说话人标注、摘要、翻译和媒体对话。

- 分类：下载、采集、转码与素材 CLI；核心候选。
- 适用边界：下载由 yt-dlp 生态提供；AI 摘要可能调用用户选择的远程模型。
- 维护状态：近90天有提交；30 天提交 11 次，90 天提交 51 次。
- 许可：[MIT](https://api.github.com/repos/nexmoe/VidBee/license)；开放许可证已核验。GitHub licenseInfo 识别；模型权重、素材、字体、第三方依赖和托管服务许可另计
- 功能核验：2026-11-12；[来源1](https://github.com/nexmoe/VidBee/blob/6082e2604f0c37d942cdb896040aa0c88b5c527f/README.md#L2)。

## [cobalt](https://github.com/imputnet/cobalt)

无广告和追踪的媒体下载 Web 应用与可自托管 API，覆盖 YouTube、TikTok、Instagram 等站点。

- 分类：下载、采集、转码与素材 CLI；核心候选。
- 适用边界：monorepo 含 api、web 与文档，没有公开预托管 API，需自行部署实例；只处理公开可访问内容，下载与再分发授权由用户负责；品牌与吉祥物为版权所有，不随代码许可。
- 维护状态：91–365天未提交；30 天提交 0 次，90 天提交 0 次。
- 许可：[AGPL-3.0（api 与其余部分）+ CC-BY-NC-SA-4.0（web）](https://github.com/imputnet/cobalt/blob/a636575b09de1fc55d9b8cd98cac88f5f2f16b42/README.md#L59)；复合/条件许可。api 与仓库其余部分为 AGPL-3.0，web 代码为禁止商用的 CC-BY-NC-SA-4.0；品牌和吉祥物单独版权，仅允许非商业托管未修改实例；ffmpeg/libav.js 等组件许可另计
- 功能核验：2026-11-23；[来源1](https://github.com/imputnet/cobalt/blob/a636575b09de1fc55d9b8cd98cac88f5f2f16b42/README.md#L28) · [来源2](https://github.com/imputnet/cobalt/blob/a636575b09de1fc55d9b8cd98cac88f5f2f16b42/README.md#L33) · [来源3](https://github.com/imputnet/cobalt/blob/a636575b09de1fc55d9b8cd98cac88f5f2f16b42/README.md#L45)。

## [Lux](https://github.com/iawia002/lux)

Go 编写的多站点视频下载 CLI。

- 分类：下载、采集、转码与素材 CLI；核心候选。
- 适用边界：解析覆盖与站点更新频率是主要维护风险。
- 维护状态：91–365天未提交；30 天提交 0 次，90 天提交 0 次。
- 许可：[MIT](https://api.github.com/repos/iawia002/lux/license)；开放许可证已核验。GitHub licenseInfo 识别；模型权重、素材、字体、第三方依赖和托管服务许可另计
- 功能核验：2026-11-12；[来源1](https://github.com/iawia002/lux/blob/dd00f6d258d80b6684a0b9402d7124e5c18ef42f/README.md#L1)。

## [you-get](https://github.com/soimort/you-get)

从网页下载媒体内容的 Python 命令行工具。

- 分类：下载、采集、转码与素材 CLI；核心候选。
- 适用边界：站点支持与维护活跃度需和 yt-dlp 分开比较。
- 维护状态：超过365天未提交；30 天提交 0 次，90 天提交 0 次。
- 许可：[MIT](https://github.com/soimort/you-get/blob/049548f3f3f35e67ba8d3181c71fdc71d11cf260/LICENSE.txt)；开放许可证已核验。根目录 LICENSE.txt 人工核验
- 功能核验：2026-11-12；[来源1](https://github.com/soimort/you-get/blob/049548f3f3f35e67ba8d3181c71fdc71d11cf260/README.md#L1)。

## [Aurora / AgentEdit-Bench](https://github.com/yeates/Aurora)

用工具使用型 Agent 统一视频编辑，并提供 AgentEdit-Bench。

- 分类：评测、研究与外部索引；研究/评测。
- 适用边界：AgentEdit-Bench 与 VEFX/EditVerse 指标不可直接横比。
- 维护状态：近90天有提交；30 天提交 4 次，90 天提交 4 次。
- 许可：[MIT](https://api.github.com/repos/yeates/Aurora/license)；开放许可证已核验。GitHub licenseInfo 识别；模型权重、素材、字体、第三方依赖和托管服务许可另计
- 功能核验：2026-11-12；[来源1](https://github.com/yeates/Aurora/blob/2599b748c56b29b67b9be352dc091b8ddf72ae8f/README.md#L3)。

## [Awesome AI Video for Creators](https://github.com/sasateguh/awesome-ai-video-for-creators)

按创作者工作流整理开源剪辑、字幕、切片、配音和代码视频工具。

- 分类：评测、研究与外部索引；相邻基础设施。
- 适用边界：外部 star 快照会变化，最终数据回到官方仓库。
- 维护状态：近90天有提交；30 天提交 9 次，90 天提交 15 次。
- 许可：[CC0-1.0](https://api.github.com/repos/sasateguh/awesome-ai-video-for-creators/license)；开放许可证已核验。GitHub licenseInfo 识别；模型权重、素材、字体、第三方依赖和托管服务许可另计
- 功能核验：2026-11-12；[来源1](https://github.com/sasateguh/awesome-ai-video-for-creators/blob/3b88db72b425a89b751b6ea279532e3ae0a3d6f9/README.md#L1)。

## [CutCraft Bench](https://github.com/AlibabaResearch/cut-craft-bench)

评测多镜头音视频生成中的专业剪辑技法执行，并提供 Agent baseline。

- 分类：评测、研究与外部索引；研究/评测。
- 适用边界：生成连贯性与可编辑性是不同指标，不能只取综合分。
- 维护状态：近90天有提交；30 天提交 0 次，90 天提交 5 次。
- 许可：[待核验](https://github.com/AlibabaResearch/cut-craft-bench/blob/df2b35d63822d0832679fe675a274c33c51f7f75/README.md)；许可待核验。未找到根目录许可证
- 功能核验：2026-11-12；[来源1](https://github.com/AlibabaResearch/cut-craft-bench/blob/df2b35d63822d0832679fe675a274c33c51f7f75/README.md#L6)。

## [Awesome Video Editing](https://github.com/devanasolver/awesome-video-editing)

整理开源视频编辑工具、Agent Skills 与可用素材。

- 分类：评测、研究与外部索引；相邻基础设施。
- 适用边界：作为发现和覆盖基线，不参与能力判断。
- 维护状态：近90天有提交；30 天提交 0 次，90 天提交 2 次。
- 许可：[CC0-1.0](https://github.com/devanasolver/awesome-video-editing/blob/637c0b63835cccaca2c5362baa7e564fee89a6dc/LICENSE)；开放许可证已核验。目录内容采用 CC0
- 功能核验：2026-11-12；[来源1](https://github.com/devanasolver/awesome-video-editing/blob/637c0b63835cccaca2c5362baa7e564fee89a6dc/README.md#L1)。

## [Awesome AI Video](https://github.com/thoxakihiko/awesome-ai-video)

整理文本/图像到视频模型、工具和资源。

- 分类：评测、研究与外部索引；相邻基础设施。
- 适用边界：包含商业产品和模型，不能直接视为开源工具清单。
- 维护状态：近90天有提交；30 天提交 0 次，90 天提交 3 次。
- 许可：[CC0-1.0](https://api.github.com/repos/thoxakihiko/awesome-ai-video/license)；开放许可证已核验。GitHub licenseInfo 识别；模型权重、素材、字体、第三方依赖和托管服务许可另计
- 功能核验：2026-11-12；[来源1](https://github.com/thoxakihiko/awesome-ai-video/blob/45e9e2bfb3e1e1193e4725ce94bba45d0f342c5a/README.md#L1)。

## [VEFX-Bench](https://github.com/Visko-Platform/VEFX-Bench)

评测通用视频编辑和视觉特效的指令遵循与质量。

- 分类：评测、研究与外部索引；研究/评测。
- 适用边界：模型、数据、reward 和商业 API 版本必须固定后才可比较。
- 维护状态：91–365天未提交；30 天提交 0 次，90 天提交 0 次。
- 许可：[Apache-2.0](https://api.github.com/repos/Visko-Platform/VEFX-Bench/license)；开放许可证已核验。GitHub licenseInfo 识别；模型权重、素材、字体、第三方依赖和托管服务许可另计
- 功能核验：2026-11-12；[来源1](https://github.com/Visko-Platform/VEFX-Bench/blob/a82437764d1e2a2068e5e183075f437d5bd0568b/README.md#L9)。

## [EditVerse](https://github.com/adobe-research/EditVerse)

图像/视频生成与编辑研究代码及 EditVerseBench。

- 分类：评测、研究与外部索引；受限许可。
- 适用边界：研究代码与数据下载依赖外部源，结果需按论文设置复现。
- 维护状态：超过365天未提交；30 天提交 0 次，90 天提交 0 次。
- 许可：[Adobe Research License（部分文件）](https://github.com/adobe-research/EditVerse/blob/eeca9ce9f99db2d5c90e775853735025523c9334/LICENSE.md)；源码可见但非 OSI 开源。LICENSE 仅覆盖明确列出的文件，其余文件不在该许可范围内
- 功能核验：2026-11-12；[来源1](https://github.com/adobe-research/EditVerse/blob/eeca9ce9f99db2d5c90e775853735025523c9334/README.md#L1)。

## [Video-Bench](https://github.com/Video-Bench/Video-Bench)

整理和运行视频生成模型的多维评测。

- 分类：评测、研究与外部索引；研究/评测。
- 适用边界：生成 benchmark 不等于时间线编辑器或生产系统质量。
- 维护状态：超过365天未提交；30 天提交 0 次，90 天提交 0 次。
- 许可：[Apache-2.0](https://api.github.com/repos/Video-Bench/Video-Bench/license)；开放许可证已核验。GitHub licenseInfo 识别；模型权重、素材、字体、第三方依赖和托管服务许可另计
- 功能核验：2026-11-12；[来源1](https://github.com/Video-Bench/Video-Bench/blob/d40b917c4238011aea27d24f85b1e3bf996715bd/README.md#L1)。

## [Palmier Pro](https://github.com/palmier-io/palmier-pro)

面向 AI 的视频编辑器，旧版本源码曾以 GPLv3 发布。

- 分类：历史与受限版本；历史参考。
- 适用边界：v0.7.6 后二进制为专有，当前对应源码未公开；仅把 last-gpl-source 视为历史开源版本。
- 维护状态：归档 / 历史；30 天提交 5 次，90 天提交 9 次。
- 许可：[GPL-3.0（至 v0.7.6 源码）/ 后续二进制专有](https://github.com/palmier-io/palmier-pro/blob/dfc810b561f1692947eb81bbb689e078923ebb59/README.md#L112)；复合/条件许可。last-gpl-source 及 v0.7.6 前源码为 GPLv3；后续二进制无对应公开源码
- 功能核验：2026-11-12；[来源1](https://github.com/palmier-io/palmier-pro/blob/dfc810b561f1692947eb81bbb689e078923ebb59/README.md#L2)。
