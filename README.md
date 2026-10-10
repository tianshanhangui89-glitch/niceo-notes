# Niceo 笔记库 · 数据源

这个仓库给「笔记库」App（Android）提供在线数据，App 启动或下拉刷新时自动拉取，**更新内容无需重装**。

- 数据：[`data.json`](data.json)（分类、标签、正文；mermaid 已渲成 PNG data-URI）
- 网页预览（离线单文件）：[`index.html`](index.html)

数据地址（App 会同时尝试，取 `updatedAt`/`generated` 较新的一份）：
- https://raw.githubusercontent.com/tianshanhangui89-glitch/niceo-notes/main/data.json
- https://cdn.jsdelivr.net/gh/tianshanhangui89-glitch/niceo-notes@main/data.json （国内镜像）

由 `/workspace/notes/tools/build_app.py` 扫描笔记生成，`tools/publish_notes.sh` 推送。请勿手工编辑 data.json。
