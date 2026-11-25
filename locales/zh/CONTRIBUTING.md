# 贡献指南

欢迎新增项目、纠正分类、功能边界或许可证。

1. 修改 `data/projects.json`，不要直接编辑生成表格。
2. 提供 canonical GitHub 仓库、一个主分类、用途、限制和固定提交的 README 证据。
3. 明确它是工作台、Agent 系统、Skill/MCP、代码动效、生成模型、数字人、CLI 还是 benchmark。
4. 不把 roadmap、样片和作者 benchmark 写成独立实测结论。
5. 分开核验代码、模型权重、素材、字体、第三方 API 和输出内容许可。
6. 下载/采集项目必须保留平台条款与内容授权边界。
7. 新增项目后运行：

```sh
python scripts/refresh_metrics.py
python scripts/build.py
python -m unittest discover -s tests -v
python scripts/build.py --check
```

不要提交 API key、私有视频、未授权素材、内部内容工厂地址或个人数据。变更记录放在 `record/YYYY-MM-DD-中文主题.md`。

## 多语言文件

- `data/projects.json` 是中文规范审核数据：事实只在这里改一次。
- 其它语言的文案来自 `locales/<lang>/entries.json`（`description`、`boundary`、`license_label`、`license_note`，规范名含汉字的项目另给无汉字的 `name`）与 `locales/<lang>/ui.json`；`zh` 直接回落 `data/projects.json`，因此没有 `locales/zh/entries.json`。
- 新增项目或改写定位、边界、许可结论时，同一个 PR 内补齐 en/es/hi/fr 四个 locale，否则 `python scripts/build.py --check` 与 `python -m unittest discover -s tests -v` 会失败。
- 静态文档：英文在根目录 `docs/` 与 `CONTRIBUTING.md`，其它语言在 `locales/<lang>/` 下同名相对路径。镜像里的相对链接按该文件所在目录解析：`locales/<lang>/docs/research.md` 指向仓库根要写 `../../../research/…`，`locales/<lang>/CONTRIBUTING.md` 写 `../../…`；`docs/readme-intro.md` 例外，它嵌入 README，按语言根目录解析。
- 生成物（`README.md`、`docs/projects.md`、`docs/rankings.md`、`data/rankings.csv` 与各语言镜像同名文件）不要手改，由 `python scripts/build.py` 产出。
