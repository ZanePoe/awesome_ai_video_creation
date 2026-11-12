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
