# 跑起来 · 全球马拉松与越野跑赛事档案

[English](README.en.md) · 中文

本仓库保存跑起来主站使用的全球马拉松、越野跑与超马赛事档案、双语正文、来源和审阅数据。它是纯内容仓库，不包含网站运行代码、`package.json`、`node_modules` 或构建产物。

## 这里有什么

- **52 条赛事**，覆盖 24 个国家/地区，距离从 31 km 到 330 km。
- 其中 34 条越野超马、11 条公路马拉松、4 条山地越野、3 条公路超马。
- 每条赛事都有中文和英文独立正文，以及逐条对应的来源与审阅记录。
- 内容按固定版本写，例如赛道版本、当届日期、距离、累计爬升、最高点、关门时间与组别；不维护报名入口、实时成绩或商品价格。

主站路径保持 `https://paobu.org/routes/`，仓库改名不影响公开网址。

## 适合谁

- 想快速了解一场比赛“到底多难、在哪里、什么时候、有什么门槛”的跑者。
- 需要核对赛道数据、官方来源和许可边界的内容编辑。
- 想引用赛事事实，但不想把营销文案当成数据的人。

## 目录

```text
data/entities/{slug}.json          共享事实、赛事版本、来源引用与几何许可
data/sources/{sourceId}.json       来源、定位与支持的结论
data/contributors/{personId}.json  公开作者与审阅者身份
data/reviews/{slug}.{locale}.json  通过审阅后的内容摘要与决定
content/zh-CN/{slug}.md            中文正文与 frontmatter
content/en/{slug}.md               英文正文与 frontmatter
assets/                            可再分发的轨迹与小型素材
```

`entityId` 形如 `route:boston`，`slug` 使用英文短横线。中英文通过 `entityId` 配对，事实数值只保存在 `data/entities/` 一处。

## 数据口径

- 距离与爬升必须有可定位来源；没有可信爬升时 `elevationGainMeters` 为 `null`，不能填 `0`。
- `mapAnchor` 只是地球定位点，不冒充起点或完整轨迹。
- `geometryAccess` 取 `redistributable`、`official-link` 或 `unavailable`。只有 `redistributable` 才能把轨迹纳入仓库并提供下载，且必须记录许可、署名与来源。
- 赛道页面可见不代表轨迹可以转载。官方页面可支持事实核验，但不自动授予图片、Logo、GPX 或数据库的复制权。
- 来源更新后，中英文正文都要重新核对；只有经过实质审阅才能填写 `reviewedAt`。

## 当前审阅状态

52 条路线均已完成 AI 辅助编辑审阅并发布（`published`，双语 `approve` 记录与匹配 digest）。审阅者是 `runmap-editorial`，明确标注为 AI 辅助，不是独立或专业审阅。这个仓库不声称已经过专业审阅。

## 本地使用

本站内容由 `site-www` 构建时读取。六个工程放在同一父目录时，默认路径会自动指向本仓库；也可以在网站仓库中通过 `ROUTES_CONTENT_DIR` 指定路径。本仓库本身没有安装或构建命令。

预览方式见 [site-www](../site-www/README.md)。构建会校验双语配对、来源、许可、审阅日期与内容摘要，校验失败会阻止发布。

## 许可与纠错

- 新写正文：CC BY 4.0，署名「跑起来 RunUp」。
- 轨迹几何、图片与第三方素材：按各来源条件，逐项记录在实体或来源文件中；没有确认权利的内容不进入仓库。
- 网站代码：MIT，位于三个 `site-*` 仓库和 `paobu-core`。

发现事实或来源问题时，请通过 Issue 或 Pull Request 说明具体段落、来源与建议修改。贡献流程见 [CONTRIBUTING.md](CONTRIBUTING.md)。

最后核对日期：2026-11-25。
