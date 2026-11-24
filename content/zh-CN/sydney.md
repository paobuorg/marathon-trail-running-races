---
entityId: route:sydney
locale: zh-CN
title: "悉尼马拉松：2026 从北悉尼到歌剧院全解"
summary: "2026 届 TCS Sydney Marathon 的完整路线资料：42.195 公里点对点赛道、2026 course 页的高程表述（+317/−400 米）与 2027 页 +313/−83 米的口径差异、官方 2026 页面链接的 GPX（文件内名仍写 2025）、8 个水站与 10 个中途关门/改道点、交通到达与分区封路、8 月末天气，以及一张 2026 年完赛奖牌照片。"
aliases: ["悉尼马拉松", "TCS Sydney Marathon", "Sydney Marathon", "悉尼城市马拉松", "北悉尼到歌剧院", "42.195 公里城市赛道"]
authors:
  - runmap-editorial
reviewers:
  - runmap-editorial
translationStatus: reviewed
---

## 核验状态

- 版本：`2026-sydney-official-course`，对应 2026 年 8 月 30 日（周日）举行的 TCS Sydney Marathon presented by ASICS。
- 核验日：2026-11-06；2026-11-08 复核时本机直连 Transport for NSW 的 2026 赛事页会被 302 到通用页，改用工具抓取（桌面 UA）读到完整赛事页，交通与票务细节已复核；2026-11-20 又复核了 2026 course 页、Pace Team 页与关门 PDF。封路窗口仍以赛事方三个分区封路页为准。本页每个数字都标出口径；官方页面之间措辞不一致的地方并列写出，不取平均、不做四舍五入包装。
- 起跑与关门：精英轮椅 6:15 起跑，大众组 6:30 起跑。2026 course 页写三个起跑组从 6:31、7:03、7:41 滚动出发，起点窗口 6:30–8:15，总关门 7 小时、按 3:15pm 计；2026 关门 PDF 则写起点线 8:40 关闭、按 3:40pm 计。两个官方 2026 文件不一致，本页并列保留，比赛日以当届手册为准。赛事首页已经把下一届写成 2027 年 8 月 29 日，因此本页固定的是 2026 版，不把 2027 的页面内容混进来。
- 赛道几何：**官方页面链接的 GPX**。2026 course 页在「Elevation Profile」下直接给出「Download Marathon Course GPX File」；文件在官方域名下可下载，页面写明 GPX 内路线 100% 准确、高程不 100% 准确。但文件内部 name 仍写 2025、metadata link 指向 `goandrace.com`，页面也没有再分发许可。因此实体记 `official-link`，只外链、不托管、不画线；它不是可再分发的几何，也不当作独立的 2026 测绘证明。详见下节。
- 本页没有实地跑过这条赛道，因此不提供“实测”结论。已核实与未核实的内容在正文中分开列出。
- 改线核查：往届手册未取得，改线史未核。本页没有可入日志的官方改线、改期或改规则证据，`courseChanges` 为空数组，不写成「没有改线」。

## 这条赛道是什么

悉尼马拉松是一条点对点城市公路赛道：从北悉尼 Miller Street 起跑，跨过悉尼海港大桥，穿过市中心与 Moore Park，绕 Centennial Park 一圈，再经 Mrs Macquarie's Chair 和皇家植物园，最后在悉尼歌剧院结束。官方把起点描述为“庆祝 2000 年悉尼奥运会马拉松遗产”的起点，把沿途重点列为海港大桥、Centennial Park 环线、Mrs Macquarie's Chair 与歌剧院终点。全程 42.195 公里，2026 届标注为 World Athletics Platinum Label Marathon。

这条赛道不是“从桥到歌剧院”的一条直线。官方 course 地图把 North Sydney、McMahons Point、Kirribilli、Pyrmont、Ultimo、Sydney、Darlinghurst、Woolloomooloo、Surry Hills、Paddington、Woollahra、Kensington、Kingsford 与 Royal Randwick 等区域画进路线范围；交通部门的封路说明也把北悉尼、CBD、Pyrmont、Darlinghurst、Moore Park 到 Kingsford 列为主要受影响区域。读路线时要把“起点在桥北、终点在歌剧院”与“中途向南绕行”分开理解，否则会把 42.195 公里误当成一条短距离跨桥路线。

2026 届的成绩：男子冠军 Addisu Gobena 跑出 2:04:42，把 Hailemaryam Kiros 在 2025 年创造的 2:06:06 赛道纪录缩短 1 分 24 秒；女子冠军 Peres Jepchirchir 跑出 2:18:31，距离 Sifan Hassan 在 2025 年的 2:18:22 赛道纪录只差 9 秒。轮椅组也有可核实成绩：Daniel Romanchuk 以 1:26:50 打破 Marcel Hug 在 2025 年的 1:27:15，Manuela Schär 以 1:42:04 打破 Susannah Scaroni 的 1:44:52。女子亚军 Irine Cheptai 跑出 2:22:11、季军 Shure Demise 2:22:33；男子第四 Alphonce Simbu 2:04:57，官方赛后稿称前五名都在 2:05 以内。澳大利亚本土冠军是 Andy Buchanan 2:10:14 与 Ellie Pashley 2:28:28。这些都是赛事方与 World Athletics 公布的比赛结果，不是本页对赛道难度的实测。

参赛规模也需要单独考虑。Transport for NSW 的 2026 赛事页记录 2026 届有 40,000 名参赛者，该页本轮已通过工具抓取复核；它仍是 2026 届页面，数字只作 2026 记录；官方 course 页写大众组 6:30 起跑。起点区域由三个火车站分担人流，赛事方称每个站每小时可向起跑区输送 25,000 人，并建议至少提前 60 分钟到达。

## 官方口径

| 口径 | 距离 | 爬升 | 下降 |
|---|---|---|---|
| 2026 course 页（2026-11-20 复核，sydneymarathon.com） | 42.195 km | +317 m（Net Elevation Gain） | −400 m（Net Elevation Loss） |
| 2026 course 页旧记录（2026-11-06） | 42.195 km | +313 m | −396 m；同段另写 Total −83 m loss |
| 2027 course 页现页数字块 | 42.195 km | +313 m Elevation Gain | −83 m Net Drop |
| 2026 关门 PDF | 42.195 km | 未公布 | 未公布 |
| World Athletics 成绩页 | 42.195 km | 未公布 | 未公布 |

这张表要表达的是“谁说了什么”，不是把几套数字合成一个。距离只有一套官方数字：42.195 公里；course 页明确写出这个数字，关门 PDF 按赛道全程处理，World Athletics 成绩页列的是马拉松项目。爬升与下降有三套官方页面口径：2026-11-20 复核的 2026 course 页写 +317 米与 −400 米；同一页 2026-11-06 的旧记录写 +313 米与 −396 米；2027 版现页只写 +313 米与 −83 米净下降。317−400 与 313−396 都等于 −83，净值一致，但绝对值相差 4 米。官方没有解释这 4 米差异，本页不把两套数字平均，也不把 317 偷换成 313：2026 届卡片用 2026 course 页的 317，2027 届用 313，旧 396 只作为 2026 旧记录保留。GPX 的高程不被官方视为 100% 准确，因此本站不用 GPX 反推另一套爬升。

本页顶部卡片使用 317 米爬升，因为这是 2026 course 页 2026-11-20 复核到的数字；2027 版现页写 313 米，两届不要混用。它不是“净爬升”：2026 course 页同时给出 400 米下降，净值为 −83 米；2027 页只保留 −83 米净下降。

官方没有公布每个 5 公里分段的爬升与下降，也没有公布赛道最高点与最低点的海拔。因此本页不写“最高点多少米”，也不把 317 米和 400 米按公里数平均分摊到各段。

## 官方 GPX 对照（文件内名仍写 2025）

2026 course 页在「Elevation Profile」下直接给出「Download Marathon Course GPX File」；链接指向官方域名 `filesusr.com`，`dn` 参数为 `TCS_Sydney_Marathon_2026_Course.gpx`。2026-11-21 直接下载并检查：

| 项目 | 值 |
|---|---|
| HTTP / 类型 / 字节 | 200 / `application/gpx+xml` / **52,384** |
| 文件格式 | GPX 1.1，`creator="Garmin Connect"` |
| 点数 | **650** 个 `trkpt`、0 个 `wpt`、**650** 个 `<ele>` |
| metadata name | `TCS Sydney Marathon 2025 - 42.195 km`（出现 2 次） |
| metadata time | `2026-08-03T10:03:42` |
| metadata link | `https://www.goandrace.com` |
| 逐点平面距离 | **42.2424 km**，比 42.195 km 长 **47.4 m（0.112%）** |
| 起点 / 终点 | `-33.833204, 151.208004` / `-33.858142, 151.214300` |
| 坐标范围 | `33.833204–33.931257°S` / `151.191888–151.241047°E` |

这张表的关键不是“42.2424 比 42.195 长 47 米”，而是文件身份：URL 的 `dn` 写 2026，官方 2026 页也把它作为 Course GPX；文件内部 name 仍写 2025，metadata link 指向 `goandrace.com`，metadata time 是 2026-08-03。官方没有解释这组矛盾，也没有给再分发许可。因此本页：

- 记 `geometryAccess=official-link`，只外链官方页面链接的文件，不复制、不打包、不画线；
- 不把它当作“官方测绘原文件”或“2026 赛道逐米更新的证明”；
- 不用它反推官方爬升/下降。

文件含 650 个 `<ele>`；按原始点列直接累加为 **+283 / −357 m**，最低 **3.8 m**、最高 **80.4 m**，首点 79.2 m、末点 5.2 m。这与官方 2026 页的 +313/−396（以及同页 Course Information 的 +317/−400）不同；官方明确说 `.gpx` 高程不 100% 准确，所以这些原始值只作文件体检，不替换官方口径。

## 分段说明

| 段 | 区间 | 本段距离 | 本段爬升 / 下降 |
|---|---|---:|---:|
| 1 | 起点 Miller St → 5 km | 5.000 km | 未公布 / 未公布 |
| 2 | 5 km → 10 km | 5.000 km | 未公布 / 未公布 |
| 3 | 10 km → 15 km | 5.000 km | 未公布 / 未公布 |
| 4 | 15 km → 20 km | 5.000 km | 未公布 / 未公布 |
| 5 | 20 km → 25 km | 5.000 km | 未公布 / 未公布 |
| 6 | 25 km → 30 km | 5.000 km | 未公布 / 未公布 |
| 7 | 30 km → 35 km | 5.000 km | 未公布 / 未公布 |
| 8 | 35 km → 40 km | 5.000 km | 未公布 / 未公布 |
| 9 | 40 km → 终点 Opera House | 2.195 km | 未公布 / 未公布 |

表中的分段边界来自官方 course 地图的“每 5 公里一个公里标记”，以及 2026 course 页公布的 5、10、15、20、25、30、35、40 公里水站；2026-11-20 已在 `sydneymarathon.com/marathon/` 重新读到这份清单。九段相加为 42.195 公里；这是用官方点位做减法得到的距离，不是官方另发的一张分段表。这一列全部写“未公布”，不用 317/400 去分摊，也不根据地图坡度猜数字。

官方 course 页把海港大桥、Centennial Park 环线、Mrs Macquarie's Chair 与歌剧院终点列为路线亮点。本页不把“海港大桥”强行写成 3 公里或 4 公里，也不把“Centennial Park”写成某个精确的半程位置。Course 地图的可提取文字列出 North Sydney、McMahons Point、Kirribilli、Pyrmont、Ultimo、Sydney、Darlinghurst、Woolloomooloo、Surry Hills、Paddington、Woollahra、Kensington、Kingsford、Royal Randwick 等区域，但官方未给出“区域—公里”的一一对应；这些地名只能说明赛道经过哪些片区，不能当成逐段导航。

关门 PDF 里的 17.8、21.2、22.0、28.3、29.1、30.26、33.4、35.1、37.6、38.75 公里是关门或改道控制点，不是官方分段边界。这些控制点适合用来做“我必须在几点前到哪里”的时间表，不是逐段爬升数据。

本页不做“冠军每 5 公里配速”的分析，也不根据终点时间反推某段坡度。需要配速换算时，用页面关联的配速工具；本页不提供海拔曲线。

## 补给点与关门

| 地点 | 距离 · 海拔 · 累计爬升 | 服务 / 关门 |
|---|---|---|
| 5 km 水站 | 5.0 km · 未公布 · 未公布 | 水、Powerade Mountain Blast；附近有流动厕所 |
| 10 km 水站 | 10.0 km · 未公布 · 未公布 | 水、Powerade Mountain Blast；附近有流动厕所 |
| 15 km 水站 | 15.0 km · 未公布 · 未公布 | 水、Powerade Mountain Blast；附近有流动厕所 |
| 20 km 水站 | 20.0 km · 未公布 · 未公布 | 水、Powerade Mountain Blast、GU Energy Gel（限量）；附近有流动厕所 |
| 25 km 水站 | 25.0 km · 未公布 · 未公布 | 水、Powerade Mountain Blast；附近有流动厕所 |
| 30 km 水站 | 30.0 km · 未公布 · 未公布 | 水、Powerade Mountain Blast、GU Energy Gel（限量）；附近有流动厕所 |
| 35 km 水站 | 35.0 km · 未公布 · 未公布 | 水、Powerade Mountain Blast；附近有流动厕所 |
| 40 km 水站 | 40.0 km · 未公布 · 未公布 | 水、Powerade Mountain Blast；附近有流动厕所 |
| 终点 | 42.195 km · 未公布 · 未公布 | 完赛恢复区供应 Powerade；沿 Royal Botanic Garden 退场路线设 refreshment station |
| 起点线（关门点） | 0 km · 未公布 · 未公布 | 2026 关门 PDF：8:40 关闭，起跑窗口 130 分钟（6:30–8:40）；2026 course 页：窗口 6:30–8:15 |
| Anzac Pde at Dacey Ave（改道点） | 约 17.8 km · 未公布 · 未公布 | 跳过约 1.00 km；11:37 前通过 |
| 半程 +100 m（Baker St，主要改道点） | 约 21.2 km · 未公布 · 未公布 | 掉头回 Anzac Pde，跳过约 4.00 km；12:11 前通过 |
| Anzac Pde at Sturt St（主要改道点） | 约 22.0 km · 未公布 · 未公布 | 长掉头回 Anzac Pde，跳过约 2.00 km；12:19 前通过 |
| Anzac Pde 进入 Bus Lane 掉头（软改道点） | 约 28.3 km · 未公布 · 未公布 | 可退赛并沿 FOP 走回终点；1:22pm 前通过 |
| Moore Park at Driver Ave（软改道点） | 约 29.1 km · 未公布 · 未公布 | 可走回终点，或离场乘 SAG 车回终点附近；1:30pm 前通过 |
| Robertson Rd Gate（Centennial Park，主要改道点） | 约 30.26 km · 未公布 · 未公布 | 掉头绕过 Centennial Park 环线；1:42pm 前通过 |
| Centennial Park Medical Tent（Jervois Ave，SAG 接驳点） | 约 33.4 km · 未公布 · 未公布 | 医疗帐篷与 SAG 接驳；2:14pm 前通过 |
| Driver Ave at Moore Park Rd（硬关门与 SAG 点） | 约 35.1 km · 未公布 · 未公布 | 硬关门，乘 SAG 跳过余下 Driver Ave；2:32pm 前通过 |
| St Marys（硬改道点） | 约 37.6 km · 未公布 · 未公布 | 改走 Prince Albert Rd 与 Macquarie St，跳过皇家植物园；2:55pm 前通过 |
| Mrs Macquarie's Rd（改道点） | 约 38.75 km · 未公布 · 未公布 | 从分流点绕开 Mrs Macquarie's point 环线；3:07pm 前通过 |

先看补给。以下 2026 届细节已在 2026-11-20 从 `sydneymarathon.com/marathon/` 的 2026 course 页重新核对：8 个水站是 5、10、15、20、25、30、35、40 公里；所有水站都有水，所有 8 个水站与终点恢复区都有 Powerade Mountain Blast。GU Energy Gel 只在 20 公里与 30 公里水站提供，官方明确说数量有限、不保证供应，并强烈建议需要能量胶的跑者自带。每个水站都有流动厕所；终点之后在 Marathon Recovery Zone 另设马拉松专用 refreshment station。

2026 官网 Pace Team 页列出从 2:30 到 7:00 的多个目标档位，另设一名“up to 7 hrs”的 sweeper；配速员按 chip time 均匀配速，半程误差控制在 ±30 秒内，穿红色 TCS Sydney Marathon Pace Team 背心，并手持写有目标完赛时间的旗子。这个信息对选组有用，但它不是官方配速要求，跑者仍要按自己的计划执行。40 公里水站之后只剩 2.195 公里到终点，这个距离是用 42.195 减 40 得到的算术。

再看关门。2026 届有两份官方文件给出不同的起点窗口：2026 course 页写 6:30–8:15，2026 关门 PDF 写 6:30–8:40，并按 8:40 关闭计算后续时刻。赛道总时限 7 小时，按 10 分钟/公里的平均速度计算；PDF 的关门与改道时刻从 8:40 起算，所以表里的“11:37”“12:11”等是“赛事按时起跑”的日钟时间，不是从个人跨线时刻倒推。官方同时写明，如果起点窗口因交通、安保或运营原因延迟关闭，所有关门时间会按扫尾跑者实际跨线时间重新计算。拿到比赛日手册后，应以当届公告为准，不能把这张 2026 表直接套到 2027。

关门点分三种处理方式。第一种是退赛：可以进入 SAG 车，或沿 FOP（field of play）内/外走回终点。第二种是改道：跳过一段赛道后仍可沿 FOP 跑到终点，但号码会被记录并取消资格，不算官方完赛。第三种是被尾随的 SAG 车接走。官方还设一名 Tail Control Pacer／Sweep，在赛道上对落后跑者发出两次警告，之后才按上述方式处理。表中 29.1、33.4 与 35.1 公里明确写到 SAG 接驳；33.4 公里是 Centennial Park 医疗帐篷，35.1 公里是 Driver Ave 的硬关门点。

![2026 年 TCS Sydney Marathon 完赛奖牌，缎带可见“TCS SYDNEY MARATHON”“2026”](/media/routes/sydney/medal-2026.jpg)

## 路面构成与地形

官方未公布可分路面比例，本页不写“沥青占多少、桥面占多少、公园跑道占多少”这类没有来源的百分比。能确认的是：官方 course 地图画的是城市街道、海港大桥、Centennial Park 环线与皇家植物园一带；官方封路说明列出的受影响区域包括 Sydney CBD、The Rocks、Walsh Bay、Dawes Point、Millers Point、Barangaroo、Darling Harbour、Pyrmont 与东部城区。这说明赛道主体是城市道路与公园道路，不是山径或越野路线，但不能据此编造路面配比。

Abbott World Marathon Majors 的赛后报道提供了几个定性地形线索：男子领先集团在 37 公里附近进入皇家植物园后才真正拉开；最后阶段有一段下坡；轮椅选手 David Weir 在海港大桥的“incline”上取得领先；Daniel Romanchuk 在 10 公里后通过“elevation into Oxford Street”建立优势。本页只把它们当作“桥面有上升、Oxford Street 一带海拔抬升、终点前有下坡”的定性依据，不换算成具体爬升。

官方高程剖面只给总数，不给公里点海拔；2026 页仍保留“GPX 高程不 100% 准确”的说明，且官方在同一页并列 +313/−396 与 +317/−400 两套数字。因此本页不写最高点、最低点，也不写“第几公里最陡”。如果你需要做坡度训练，应该用官方 course 页那张高程剖面 PDF 做视觉参考，再用自己的 GPS 设备在允许的训练路线上校准；不要把本页或任何第三方海拔曲线当成赛道实测。

官方 course 页另有一段 2025 年车载 360 度相机拍摄的 Course Preview 视频，用来展示跑者视角；它属于宣传资料，不是可再分发的几何文件。

官方 course 地图画出 Centennial Park 环线，三个分区封路页也把 Moore Park 到 Kingsford 一带列入大面积封路范围，并写明 Centennial Parklands 封闭；这支持“赛道包含公园内部环线”的判断，但不等于公园内每一段都是草地或土路。海港大桥、CBD 街道、Oxford Street、Anzac Parade、Driver Ave 与皇家植物园的道路构成，官方地图未标路面材质。

## 风险与撤退点

- **时间风险是硬的**：2026 届有两份官方文件给出不同的起点窗口与终点关门：course 页写 6:30–8:15、3:15pm；关门 PDF 写 6:30–8:40、3:40pm。7 小时总关门与 10 分钟/公里平均速度一致；如果起点延迟关闭，所有中途关门时间会重算。把“7 小时”当成“从自己跨线起算的 7 小时”是错的：PDF 明确从起点线关闭时刻起算。比赛日以当届手册为准。
- **中途控制点多且分软硬**：官方 PDF 列了起点线加 10 个中途关门/改道点，从 17.8 公里的 Dacey Ave 一直到 38.75 公里的 Mrs Macquarie's Rd。28.3 与 29.1 公里是软改道点，30.26 公里是主要改道点；33.4 公里的 Centennial Park 医疗帐篷与 35.1 公里的 Driver Ave 是明确的 SAG 接驳点；35.1 还是硬关门。
- **改道不等于继续比赛**：选择 skip 的跑者会被记录号码并取消资格，虽仍可跨过终点线，但不被当作官方完赛。
- **医疗与收容**：官方 PDF 说明尾随的 participant tail support vehicle 与 tail control pacer 负责控制关门，落后跑者会先收到两次警告；33.4 公里有 Centennial Park 医疗帐篷。除此之外，官方 PDF 未逐点列出医疗站清单，本页不假设每个水站都有医生。
- **道路必须按时重开**：官方 PDF 要求赛事按公布时间重开州与地方道路以及海港大桥。这一段可核实的官方内容只有上述一条。
- **天气与暴露**：赛道包含海港大桥桥面、Centennial Park 环线与皇家植物园的开阔路段，官方地图与路线亮点能确认这些地形。本页引用的 Open-Meteo 2026 年 8 月 23–31 日网格点记录是日最低 8.7–14.1°C、比赛日最高 19.1°C，跑者要按当届预报准备。
- **人流与起跑**：2026 赛事页记录 40,000 名参赛者，本轮已用工具抓取复核；6:15 与 6:30 两波起跑。起点区域三个火车站每小时可输送 25,000 人，赛事方建议提前 60 分钟到达；晚到会直接撞上起点关闭窗口。
- **不能靠自驾撤退**：官方明确说比赛日道路大面积封闭、起终点零停车，公共交通是唯一出行方式。中途受伤时，官方给的机制是走到最近的关门/接驳点或等 SAG 车；起终点零停车、赛道大面积封闭，亲友无法开车进赛道接人。

## 交通到达

以下交通细节分两层：赛事方 Traffic & Transport 页与三个分区封路页在 2026-11-08 可读，作为本轮核对依据；铁路加开班次、机场站附加费、两日票务与 Expo 条目来自 Transport for NSW 的 2026 赛事页，本轮用工具抓取（桌面 UA）读到完整正文，下列细节已复核；该页仍是 2026 届，不作为 2027 承诺。

**机场。** 悉尼金斯福德·史密斯机场的国内与国际航站楼有火车站。Transport for NSW 的 2026 赛事页曾写：机场站进出要另付 station access fee，不包含在马拉松报名或赛事免费交通权益里；该页本轮抓取可读，这段已复核，仍是 2026 记录。赛事方交通页确认号码布可在赛事日乘坐 Sydney Trains、Metro、巴士与渡轮，但没有写机场附加费的豁免。落地后的动线是本站按两条来源拼接：机场 → Central 或市区 → 换 T1／T9 去 North Sydney，或换 Metro 去 Victoria Cross／Crows Nest；具体航班与行李安排不在赛事方页面范围，本页不展开。

**铁路。** 赛事方交通页按起跑组分流：Purple 与 Orange 组坐火车到 North Sydney，Green 组转 Metro 到 Crows Nest；North Sydney 是起点最近的火车站。Transport for NSW 的 2026 赛事页补充了 T1 North Shore Line 与 T9 Northern Line、6 点前后的出站走法，以及 Berowra 2:59、Penrith 3:30、Hornsby 3:10／3:40、Ashfield 3:58、Liverpool 3:45、Bankstown 3:25／3:50、Cronulla 2:47／3:17、Revesby 3:10 等加开班次；该页本轮抓取可读，这些班次细节已复核。

**地铁。** 起点附近最近的两个地铁站是 Victoria Cross 与 Crows Nest：Purple／Orange 组走 Victoria Cross，从 Denison St 出口出来右转 Berry St、再左转 Walker St；Green 组走 Crows Nest，从 Clarke St 出口经 Willoughby Rd、Burlington St、West St 与 Falcon St 到 North Sydney Oval 与 St Leonards Park。Transport for NSW 的 2026 赛事页另写 M1 线在 Tallawong、Chatswood 与 Sydenham 之间运行，3:30 左右起从 Tallawong、4 点起从 Sydenham 加开，8 点前每 4 分钟一班、15:00 前每 5 分钟一班；该页本轮抓取可读，这些班次细节已复核。终点一侧 Martin Place 是地铁站，最近的火车站是 Circular Quay，Wynyard 与 Martin Place 均在步行距离内（同为 2026 记录）。

**巴士与轻轨。** 赛事方交通页写明：巴士受封路影响明显，起点附近最近的车站在 Crows Nest，只有少量巴士停靠 Falcon St 的 St Leonards Park 一带。Transport for NSW 的 2026 赛事页另写：平时跨悉尼海港大桥的巴士改在 Crows Nest、St Leonards 或 Macquarie Park 结束行程（桥封闭的 3:00–11:00 期间则在市区结束）；市区与东区之间的巴士因 Park St 封闭，在 Kings Cross／Woolloomooloo 一带起终，直到午后；这些改线细节本轮已复核。轻轨所有线路 3:45 起有早班，包括 L1 Dulwich Hill、L2 Randwick 与 L3 Kingsford；L3 从 Kingsford 发出的服务在 5:47 后停止。

**自驾与落客。** 官方立场很明确：比赛日大面积封路、起终点零停车，公共交通是唯一方式。如果只从本地出发，官方设了一个落客点：ANZAC Public School，位于 Anzac Ave 的 Ernest St 旁；需要无障碍落客的跑者用 North Sydney Boys High School 在 Falcon St 的停车场。不要把“落客”当成“停车”：车放下人就得走，赛道周边没有给参赛者的停车位。关键封路窗口是 5:30–10:30 的 course lock-down；海港大桥、Cahill Expressway 与 Western Distributor 在 3:00–11:00 关闭，Macquarie St 4:00–16:30、Oxford St 4:00–16:00 关闭，Anzac Pde 在 5:00–14:00 关闭，Moore Park 的 Driver Ave 一带到 15:30。Cross City Tunnel 在 5:00–16:30 免通行费；CBD、The Rocks 与 Circular Quay 的 managed exit 到 5:30，4:00 起禁止驶入。

**票务与博览会。** 赛事方交通页写，参赛者在赛事日可凭官方号码布乘坐 Sydney Trains、Metro、巴士与渡轮。Transport for NSW 的 2026 赛事页补充：8 月 29 日（周六）与 8 月 30 日（周日）可凭号码布、完赛奖牌或志愿者 T 恤乘坐 Sydney Trains、NSW TrainLink Intercity、Metro、常规巴士、轻轨与渡轮，权益有效到次日 4:00；Running Expo 在 8 月 27–29 日于 Sydney Olympic Park 举行。该页本轮抓取可读，两日票务与 Expo 细节已复核，仍为 2026 记录。

## 季节与天气

2026 届在 8 月 30 日举行；8 月末的悉尼是南半球冬末。为看同一时间窗口，本页用 Open-Meteo 历史再分析数据查了悉尼网格点（请求坐标 33.8688S / 151.2093E，返回网格点 33.848858S / 151.19551E，海拔 86 米）2026 年 8 月 23–31 日共 9 天的日最高、日最低与降水：

- 日最高气温：16.7°C 至 20.5°C，中位 18.6°C。
- 日最低气温：8.7°C 至 14.1°C，中位 10.7°C。
- 9 天中有 3 天降水 ≥1 mm，2 天 ≥5 mm。
- 8 月 30 日当天：最高 19.1°C，最低 8.9°C，降水 0.0 mm。

这些是**网格点的模拟历史值，不是赛道实测**，也不是 2027 年的预报。悉尼市区不同街区、桥面风、公园遮阴与皇家植物园的开阔地会有体感差异；8 月末的悉尼日最低温在 8.7–14.1°C、日最高温在 16.7–20.5°C 之间。2026 年比赛日的网格点记录是低温 8.9°C、白天 19.1°C、无降水，但这只能说明“这个网格点在那一天的历史再分析结果”，不能保证 2027 年同一日期复现。

## 难度分级

官方未公布单一的“难度等级”。以下是本站评级，不是赛事方评级；评级只按可核实维度陈述：

- 距离 42.195 公里；本页核对到的官方文件口径一致。
- 爬升 +317 米（2026 course 页，2026-11-20 复核）、下降 −400 米（同页）、净 −83 米；平均每公里约 7.5 米爬升，净下降约 2 米/公里。旧 2026 记录写 +313／−396，2027 页写 +313／−83；三套并列保留，不平均。两个换算是本站用官方总数做的算术，不是新的官方数字。
- 总关门 7 小时，按 10 分钟/公里；起点窗口 6:30–8:15（course 页）或 6:30–8:40（关门 PDF），两套并列。
- 2026 届为 8 个水站，间隔 5 公里；GU 胶只在 20 与 30 公里，且限量。
- 中途有起点线加 10 个关门/改道点，35.1 公里为硬关门与 SAG 点。
- 赛道包含海港大桥、Centennial Park 环线与皇家植物园；2026 男子冠军 2:04:42 创赛道纪录。

本站评级：42.195 公里城市公路马拉松，爬升 +317 米、下降 −400 米（2026 course 页）、净 −83 米，总关门 7 小时、最低平均速度 10 分钟/公里，中途有起点线加 10 个关门/改道点，其中 35.1 公里为硬关门。以上是可核实的维度；本站不把它与越野赛或山地路线作高低比较，也不把这个评级写成赛事方评级。

## 已核实与未核实

本页没有实地跑过赛道，以下内容严格分开。

**本轮可复核（有官方来源）**：2026 年 8 月 30 日、42.195 公里、World Athletics Platinum Label；6:15 轮椅与 6:30 大众起跑；2026 course 页的 6:30–8:15 / 3:15pm 与关门 PDF 的 6:30–8:40 / 3:40pm 两套窗口、7 小时总关门；起点 Miller St、终点 Opera House；2026 course 页 +317 米与 −400 米（2027 页 +313／−83）；10 分钟/公里平均速度、起点线加 10 个中途关门/改道点的距离与日钟时间、退赛／改道／SAG 规则；course 地图的 5 公里标记与区域地名；赛事方交通页的起终点零停车、落客点、轻轨早班、巴士受影响与 25,000 人/小时；三个分区封路页的桥、CBD 与东区封路窗口；Transport for NSW 2026 赛事页的 40,000 人、加开列车班次、机场站附加费、两日票务与 Expo；2026 年男女冠军与赛道纪录；2026 年 8 月 23–31 日网格点天气统计；8 个水站、20／30 公里 GU 胶、流动厕所、终点恢复区、配速员 2:30–7:00 与 sweeper。**2026 旧记录，现页已不显示**：−396 米下降与 +313 米爬升的旧组合。

**未核实（本页不写结论）**：每个 5 公里分段的爬升与下降；赛道最高点与最低点海拔；路面沥青、混凝土、公园道路各占多少；桥面伸缩缝、石板区与施工路段的具体位置；各水站的实际排队时间与补给耗尽速度；每个关门点是否都配医疗人员；SAG 车的实际等待时间；手机信号覆盖；2027 年赛道是否与 2026 年逐米一致。以上只能由赛事方当届公告或现场跑者确认，本页不把资料整理说成实测。

## 图片与权利

**一张照片，取图时记录为 Wikimedia Commons 上的赛事照片。**

2026 年 TCS Sydney Marathon 完赛奖牌；作者：Tameem Mahmud 007；许可：CC BY-SA 4.0；拍摄日期：2026-08-30（2026-11-20 经 Commons 文件页与 API 复核）。文件页记录的拍摄时间为 2026 年 8 月 30 日（比赛日），缎带读“TCS SYDNEY MARATHON presented by asics”，奖牌边缘含“2026”。引用时按 CC BY-SA 4.0 署名。

本轮复核：2026-11-20 经本机 7890 代理读取 Commons 文件页、API 与缩略图，作者、许可、拍摄日期与画面均已确认；此前 2026-11-07 与 2026-11-08 的直连失败只说明本机网络不可达。

图片未修改内容，仅做尺寸与体积压缩，并按横向版式裁去上下留白；不适用本页的 CC BY 4.0。

## 资料与再发布

本页文字由跑起来编辑部根据 TCS Sydney Marathon 的 course 页、2026 关门与改道 PDF、2026 course 地图 PDF、Traffic/Transport 页、三个分区封路页、Transport for NSW 赛事页（2026 记录）、官方赛后稿、World Athletics 成绩页、Abbott World Marathon Majors 赛后报道、Open-Meteo 数据独立撰写，采用 CC BY 4.0。

本页引用 13 个事实来源，另有 1 个编辑地图锚点来源：`route-sydney`（2026 course 页）、`route-sydney-gpx-2026`（官方 2026 页面链接的 GPX 文件）、`route-sydney-cutoff-2026`（关门与改道 PDF）、`route-sydney-course-map-2026`（course 地图 PDF）、`route-sydney-transport-2026`（赛事交通页）、`route-sydney-road-closures-2026`（三个分区封路页）、`route-sydney-transportnsw-2026`（Transport for NSW 赛事页，2026-11-07 记录，2026-11-08 复核已重定向）、`route-sydney-results-2026`（官方赛后稿）、`route-sydney-world-athletics-2026`（World Athletics 成绩页）、`route-sydney-wmm-2026`（Abbott World Marathon Majors 赛后报道）、`route-sydney-pace-team-2026`（2026 Pace Team 页）、`route-sydney-openmeteo-2026`（Open-Meteo 历史天气）、`photo-sydney-medal-2026`（2026 完赛奖牌照片），以及说明地图锚点只是编辑概览的 `route-anchor-editorial`。每条来源的支撑结论与查阅日见页面底部来源列表。

赛事名称、官方标识、官方路线文字、官方 course 地图 PDF、关门 PDF 与官方成绩归 TCS Sydney Marathon 及相应权利人所有；本页只链接官方文件，不在本站重新分发 PDF 或任何赛道几何。核验日未见官方 GPX 的再分发许可，本页不打包、不画线；官方 2026 页面链接的 GPX 只作外链与文件体检，文件内部仍写 2025，不能据此证明 2026 赛道逐米更新。World Athletics 与 Abbott World Marathon Majors 的文字归各自权利人所有，本页只引用其事实。Open-Meteo 数据按 CC BY 4.0 使用并在此署名。成绩列表受版权保护，仅可作私人信息用途；本页不复制完整成绩表。奖牌照片作者 Tameem Mahmud 007，许可 CC BY-SA 4.0，拍摄于 2026-08-30；2026-11-20 经 Commons 文件页与 API 复核，它不适用本页的 CC BY 4.0。
