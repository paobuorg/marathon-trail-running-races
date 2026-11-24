---
entityId: route:canyons
locale: zh-CN
title: "Canyons Endurance Runs by UTMB：100 公里穿越 Western States Trail 到 Auburn"
summary: "2027 届 Canyons 100K 的官方数据：100 公里、3,750 米爬升、20 小时关门，2027 年 4 月 24 日 05:00 从 China Wall Trailhead 出发，沿 Western States Trail 到 Auburn 市区。英文页头显示 62.1 miles / 12,303 ft+，2026 版补给表累计 3,698 米；2027 页明确说 GPX 与补给表仍是 2026 版、会变。2026 届 100K 因赛前天气改线，男子冠军 Adam Peterman 8:18:47，女子冠军 Riley Brady 9:41:09，中国跑者罗灿华第四。赛事是 2027 年 UTMB 美洲 Major，不是 Finals 组别；100K 同时是 UTMB Finals 与 Western States 的资格赛。"
aliases: ["Canyons Endurance Runs", "Canyons by UTMB", "Canyons 100K", "HOKA Canyons Endurance Runs by UTMB"]
authors:
  - runmap-editorial
reviewers:
  - runmap-editorial
translationStatus: reviewed
---

## 核验状态

- 版本：`2027-canyons-100k`，2027 届，比赛日为 2027 年 4 月 23–26 日（赛事页）或 4 月 22–25 日（报名页），两处日期不一致，本页并列。100K 在 4 月 24 日（周六）05:00 从 China Wall Trailhead 起跑，20 小时关门。2027 届尚未举行，`courseStatus` 记为 `current`；2027 成绩尚未公布，2026 届成绩见下文。
- 定位：Canyons Endurance Runs by UTMB 在加州 Auburn 举办，赛道使用 Western States Trail 的一段。2027 届设 100M、100K、50K、25K 四个距离；100M 与 100K 从 China Wall Trailhead 出发，50K 与 25K 在 Auburn 市区起终点。
- 身份差分：**UTMB World Series Major**：UTMB 官方 Majors 页把 Canyons 列为 2027 年美洲 Major，与 Kodiak 并列。**UTMB World Series Finals**：Canyons 本身不是 Finals 组别；官方 Finals 奖金表只列 UTMB、CCC、OCC 三场。**Major 的 Finals 名额**：Major 的 100M、100K、50K 组别前 10 名男女可获 Finals 自动资格；这是名额通道，不是把 Canyons 算作 Finals。**Western States 资格赛**：赛事主页写 Canyons 是 UTMB Finals 与 Western States 的双资格赛；100K 是 Western States 的 Super Golden Ticket 赛。**World Trail Majors**：不在 WTM 2026 名单，官方也未声明 WTM 身份，按 unknown 记。**国家级协会认证**：官方没有声明美国田协认证，按 unknown 记。
- 证据等级：**A**（2027 100K、100M、50K、25K 赛事页、races 页、报名页、2026 主页、2026 版 100K 与 100M 公制补给表、2026 官方成绩页与 UTMB Live、2026 日程页、UTMB Majors 页）＋ **B**（iRunFar 2026 赛后报道用于天气改线与 Golden Ticket 递补；Open-Meteo 地理编码只用于地图锚点）。距离、爬升、起跑时刻、关门、补给站与报名条件以组委会页面或 PDF 为准；第三方只补官方页没有展开的赛日事实，并明确标注。
- 赛道几何：`geometryAccess` 记为 `official-link`，只外链组委会的 GPX，不转存、不画线。2027 100K 页明确写「这是 2026 GPX，2027 会变」；文件修订记录还写有「Added 2026 100k Alternate GPX File」。该直链在 2026-11-20 返回 HTTP 200、333,185 字节，已下载做本地测量：去重后 3,904 点，haversine 98.427 km，1,529→387 m，原始 +4,160/−5,302 m。文件没有许可声明，测量结果只用于核验，不作为 2027 赛道。
- 改线核查：2027 100K 页的 GPX 与补给表都是 2026 版，页面写明 `Course maps subject to change`，补给表页脚标 `Revision 4/22/26` 并注明赛道可能因许可调整；2027 独立材料尚未发布。iRunFar 报道 2026 届在赛前一周因恶劣天气改线，2026 跑者从 China Wall 到 Michigan Bluff 走了不同线路；2027 页仍挂 2026 Alternate GPX，不能把这份文件当成赛日完整记录。`courseChanges` 已补 2026 `route-refined` 记录。
- 本页没有人实地跑过这条赛道；GPX 只在本地逐点测量，没有转存、重绘或再分发。
- 来源：21 个，分别是 2027 100K、100M、50K、25K 赛事页，2027 races 页，2027 报名页，2026 主页，2026 版 100K 与 100M 公制补给表，2026 官方成绩页，2026 UTMB Live，2026 官方日程页，2026 官方 GPX，iRunFar 2026 赛后报道，UTMB Majors 页，Open-Meteo 与地点地理编码等；另有 3 个 Wikimedia Commons 照片来源。
- 照片核验：2026-11-23 经 Commons `action=query` 核对 No Hands Bridge、Michigan Bluff 与 Auburn 市区的作者、日期、许可、原图尺寸与画面；三张均为地点照，不是赛事实拍。

## 这场比赛是什么

Canyons 是 Auburn 的 Western States Trail 主题越野赛。100K 从 China Wall 出发，先下 Eldorado Canyon，再上 Western States Trail 到 Deadwood，经 Swinging Bridge 与 Devil's Thumb 二次进 Deadwood，之后下到 Eldorado Bridge、上 Michigan Bluff，穿 Volcano Canyon 到 Foresthill，沿 Cal Street 与 American River 到 Drivers Flat、Mammoth Bar，走 Confluence Trail 到 No Hands Bridge，最后上 Robie Point，过 Ann Trason's White Bridge，进 Auburn 市区终点。

官方核心数据如下：

| 项目 | 官方值（2027） |
|---|---|
| 距离 | 100 km |
| 累计爬升 | 3,750 m+（页头）；路线描述另写约 13,000 ft |
| 起点 | China Wall Trailhead，2027-04-24 05:00 |
| 终点 | Downtown Auburn |
| 形式 | 点对点 |
| 总时限 | 20 小时 |
| Running Stones | 6 |
| 报名费 | all-in $437.37 |
| 最低年龄 | 18 岁 |

其余三个距离：

| 组别 | 距离 | 爬升 | 起跑 | 时限 | Stones |
|---|---:|---:|---|---:|---:|
| 100M | 100 miles | 18,208 ft+ | 2027-04-23 12:00，China Wall | 35 小时 | 4 |
| 50K | 50 km | 1,700 m+ | 2027-04-24 07:00，Downtown Auburn | 10 小时 | 2 |
| 25K | 25 km | 850 m+ | 2027-04-23 16:00，Downtown Auburn | 5 小时 | 2（2026 主页写 1） |

身份要分开写：Major 是赛季分站，Finals 是总决赛，资格赛是名额通道。Canyons 的 2027 身份是美洲 Major；它不是 Finals 组别，也不在 Finals 奖金表里。赛事主页写它是 UTMB Finals 与 Western States 的双资格赛；100K 的 Western States 名额属于 Super Golden Ticket 通道。WTM 与国家级协会认证都没有官方声明，按 unknown 记。

## 赛道

官方路线描述按顺序给出这些段落：

- **China Wall（0 km）**：起点在 China Wall Trailhead。先走 Mitchell Mine Rd，下降进入 Eldorado Canyon。
- **Deadwood（18.0 km）**：回到 Western States Trail，经 The Pump 到 Swinging Bridge（21.7 km），再上 Devil's Thumb；之后左转 Loop 6，第二次进 Deadwood（25.4 km）。
- **Michigan Bluff（36.4 km）**：下到 Eldorado Bridge，再爬上 Michigan Bluff，穿 Volcano Canyon 到 Foresthill（45.9 km）。
- **Cal Street 与 American River（45.9–74.0 km）**：沿 Cal Street 与 Western States Trail 跑 American River 段，到 Drivers Flat（74.0 km）。
- **Mammoth Bar 与 Confluence（86.7–92.7 km）**：上 Mammoth Bar，走 Confluence Trail 到 No Hands Bridge。
- **Robie Point 与终点（99.1 km）**：过 No Hands Bridge 后上 Robie Point，过 Ann Trason's White Bridge，进 downtown Auburn。

地形是加州山麓的橡树林、河谷与暴露路段，比赛在 4 月下旬，官方没有逐段给出技术难度分级或路面比例，按 unknown 记。100K 的爬升集中在 Eldorado Canyon、Devil's Thumb、Michigan Bluff 与 Mammoth Bar 几段；官方没有公布逐段爬升表，本页不根据总爬升推算分段。

![No Hands Bridge（正式名 Mountain Quarries Bridge）横跨 American River，混凝土拱桥、绿色河水、岩壁与山坡；桥面上的人是游客](/media/routes/canyons/no-hands-bridge-2018.jpg)

照片：No Hands Bridge（正式名 Mountain Quarries Bridge），Commons 文件页日期 2018-09-01，T71024，CC BY-SA 4.0。这是赛道后段的地点照，不是 Canyons 赛事实拍；桥上的人是普通游客，不是选手，也不是赛事服务。100K 在 Confluence 之后经过这一带，再上 Robie Point 进 Auburn。

## 轨迹与本地测量

官方 2026 100K GPX 文件名是 `100k Course Alternate`，333,185 字节，含 4,205 个 `trkpt`。本页在 2026-11-20 下载后做了本地测量，没有转存、重绘或再分发。

- 去重后 3,904 点；haversine 累计 **98.427 km**，比 2026 补给表的 99.1 km 短约 0.7 km，比 2027 页头的 100 km 短约 1.6 km。
- 起点海拔 1,529 m，终点 387 m，最低点 164 m。
- 原始逐点累计 **+4,160 / −5,302 m**；加 1 m 阈值后 **+3,973 / −5,077 m**。官方 2026 补给表用分段 CalTopo 校正，给 **+3,698 / −4,746 m**。单文件逐点累计会把高程噪声放大，所以正文以官方表为准，本地测量只用于核对量级。
- 文件没有许可或再分发声明；`geometryAccess` 仍是 `official-link`，不画线。

这条 GPX 不能当成 2027 赛道：2027 页明确说它还是 2026 文件且会变；它也不等于 2026 赛日路线，因为 2026 赛前一周因天气改过线。

## 补给站与关门

2027 100K 页挂的是 2026 版公制补给表。表内累计里程、爬升与已公布关门如下；2027 会变，官方已注明。

| 站点 | 累计 km | 累计爬升 / 下降 | 官方关门（2026 表） | 存包 / Crew |
|---|---:|---:|---|---|
| Start（China Wall） | 0.0 | 0 / 0 m | 05:00 起跑 | 无 |
| Deadwood-1 | 18.0 | +671 / −883 m | 未公布 | 无 |
| Swinging Bridge | 21.7 | +1,248 / −1,367 m | 未公布 | 无补给点（表内 N/A） |
| Deadwood-2 | 25.4 | +1,795 / −2,171 m | 11:30 | Crew |
| Michigan Bluff | 36.4 | +2,153 / −2,588 m | 12:45 | Crew |
| Foresthill | 45.9 | +2,374 / −3,292 m | 14:30 | 存包 + Crew |
| Cal 2 | 59.1 | +2,899 / −3,819 m | 未公布 | 无 |
| Drivers Flat | 74.0 | +3,199 / −4,443 m | 19:45 | 存包 |
| Mammoth Bar | 86.7 | +3,406 / −4,662 m | 22:15 | 无 |
| Confluence | 92.7 | +3,698 / −4,746 m | 未公布 | 无 |
| Finish（Downtown Auburn） | 99.1 | 表内未再单列 | 周日 01:00 | 终点 |

这张 2026 表的累计爬升/下降是 +3,698 / −4,746 m。页头 2027 写 +3,750 m，路线描述写约 13,000 ft（约 3,962 m）；三个数不一致，本页并列，不取平均，也不把补给表的 3,698 m 当成 2027 的官方爬升。

100K 的存包点只有 **Foresthill（45.9 km）与 Drivers Flat（74.0 km）**；可进 crew 的点是 **Deadwood-2（25.4 km）、Michigan Bluff（36.4 km）、Foresthill（45.9 km）**。Swinging Bridge 在表里标 `N/A`，不是补给站；不要把它当成有补给的检查点。

[![Canyons 100K 2026 官方补给表的 11 个站点顺序：China Wall、Deadwood-1、Swinging Bridge、Deadwood-2、Michigan Bluff、Foresthill、Cal 2、Drivers Flat、Mammoth Bar、Confluence、Auburn 终点](/media/routes/canyons/canyons-11-stations.svg)](/media/routes/canyons/canyons-11-stations.svg)

这张图把 2026 公制补给表的 11 个站点按官方顺序排成等宽行：每行给出累计公里、本段公里、累计爬升 / 下降、已公布关门与存包 / crew 权限。它不是地图，不是按距离比例画的剖面，不可导航；它也不是 2027 表。2027 页面明确写这张表仍是 2026 版、会变。

![Michigan Bluff 历史区的纪念牌与公告栏；这里是 100K 36.4 公里处的 crew 点](/media/routes/canyons/michigan-bluff-2018.jpg)

照片：Michigan Bluff 历史区，2018-09-30，T71024，CC BY-SA 4.0。这是地点照，不是赛事实拍；画面里的纪念牌与公告栏不是赛事指示牌，也不能当作补给站布置或 crew 区域的证据。100K 在 36.4 公里处到达 Michigan Bluff，官方表把它列为可进 crew 的站点。

100M 的 2026 表给出更多站点：Start 0.0、Deadwood-1 18.0、Swinging Bridge 21.7、Deadwood-2 25.4（18:30）、Michigan Bluff 36.4（19:45）、Foresthill 45.9（21:30）、Cal 2 59.1、Drivers Flat 74.0（周日 03:00）、Mammoth Bar 86.7（05:30）、Confluence 92.7、No Hands-1 93.8、Cool-1 98.6（08:00）、Coffer Dam-1 101.4、Coffer Dam-2 108.8、Cool-2 118.3（12:00）、Browns Bar-1 125.0、ALT 133.7（15:30）、Browns Bar-2 145.9、No Hands-2 155.8、Finish 161.4（周六 23:00）。表内累计 +5,499 / −6,546 m，页头 100M 写 18,208 ft+（约 5,550 m）。存包点在 Foresthill、Cool-1、Cool-2；可进 crew 的点是 Michigan Bluff、Foresthill、Drivers Flat、Cool-1、Cool-2。

关门规则按官方表执行：跑者必须在公布时刻前离开站点；表内没有公布时刻的站点不推算。2027 的补给表尚未发布，因此本页不把 2026 的站点间隔当成 2027 的配速计划。

但 2026 表本身有一处不合理的组合：Deadwood-2 关门 11:30，Michigan Bluff 关门 12:45，两站之间 11.0 km、+358 / −417 m，等于要求 8.8 km/h。这不是中游跑者能稳定执行的配速，更像表内时刻错位或仅对前队有效。把这两个时刻当作行政关门，赛前必须用 2027 表重新核对，不要拿它做训练目标。

## 官方页内不一致与外部口径

官方站点内部有这些对不上，全部并列保留：

| 项目 | 一处写法 | 另一处写法 |
|---|---|---|
| 2027 赛事日期 | races 页：4 月 23–26 日 | 报名页：4 月 22–25 日 |
| 100K 爬升 | 页头：3,750 m+（约 12,303 ft） | 路线描述：约 13,000 ft；2026 补给表累计：3,698 m |
| 100K 距离 | 页头：100 KM（英文环境 62.1 miles） | 2026 补给表终点：99.1 km；2026 GPX 本地测量：98.427 km |
| 100K 补给表累计 | Confluence 行已写 3,698 / −4,746 m | 终点行不再单列累计，最后 6.4 km 的爬升没有独立数字 |
| 100K 2026 关门 | Deadwood-2 11:30 → Michigan Bluff 12:45 | 同表这段 11.0 km、+358 / −417 m，折合 8.8 km/h，不像中游跑者可执行的关门 |
| 100M 爬升 | 页头：18,208 ft+ | 路线描述：约 18,000 ft；2026 补给表累计：5,499 m |
| 100K Western States 名额 | 赛事主页与报名页：前 3 名男女 | UTMB Majors 页：前 2 名男女 |
| 25K Running Stones | 2027 25K 页：2 | 2026 主页：1 |
| 2027 赛道文件 | 2027 页：GPX 与补给表为 2026 版、会变 | 同时提供下载并在修订记录里写「Added 2026 100k Alternate GPX File」 |
| 25K 旧文案 | 2027 页头：2027-04-23 起跑 | 同页仍留「New for 2026: April 24, 2026」 |

外部口径方面：

- **UTMB Majors**：把 Canyons 列为 2027 美洲 Major，与 Kodiak 并列；Finals 奖金表只列 UTMB、CCC、OCC。
- **Western States**：赛事主页与报名页把 100K 写成 Super Golden Ticket，前 3 名男女直通 2027 Western States；UTMB Majors 页写前 2。两个官方页面互相矛盾，本页不替任何一方圆场。

## 起点、终点与后勤

- 100K 与 100M 的起点是 China Wall Trailhead；50K 与 25K 在 Downtown Auburn 起终点。2026 日程页列出 100K 接驳：首班 02:45、末班 03:45，从 Gold Country Fairgrounds Parking 到 China Wall；2027 日程页尚未发布，不能把 2026 时刻当成 2027 安排。
- 2026 日程页明确写：100K 比赛日 **不在 China Wall 领物，也不在 China Wall 收存包**；领物在 Auburn 市区 E. Placer 与 High St 路口。2027 是否沿用这一动线，等官方日程更新。
- 报名费 all-in：100K $437.37、100M $568.76、50K $311.76、25K $177.67。
- 不退不转；可一次性延期到下一届，延期申请截止 2027-03-24；无 waiting list；赛前博览会可现场报名未售罄组别，比赛日不报名。
- 最低年龄：100M、100K、50K 为 18 岁；25K 为 16 岁。
- 100K 存包只有 Foresthill 与 Drivers Flat 两处；crew 可进 Deadwood-2、Michigan Bluff、Foresthill。终点在 Auburn 市区，完赛后取包与离场比点对点远端简单。

![Auburn 市区的淘金者雕像、街口、树木与车辆；100K 终点在 Downtown Auburn](/media/routes/canyons/auburn-downtown-2015.jpg)

照片：Auburn 市区，2015-08-22，Noah_Loverbear，CC BY-SA 3.0。这是终点城市的地点照，不是终点线、不是赛事实拍；画面里的雕像、车辆与店铺只是市区环境，不能当作终点布置或赛事规模。100K 的终点是 Downtown Auburn，具体终点拱门与冲刺通道以赛日官方布置为准。

## 报名与资格

2027 报名页给出的价格为 all-in 价；报名不退不转，可一次性延期到下一届，截止 2027-03-24。100M 与 100K 是 2028 Western States 的资格赛：100M 需在 35 小时内完赛，100K 需在 20 小时内完赛。100K 的 Super Golden Ticket 给前 3 名男女直通 2027 Western States；若名额获得者已经取得资格或放弃，名额向下递补，但不低于第 5 名。所有完赛者获得 Running Stones；2027 100K 页头写 **6 颗**，100M 为 4 颗、50K 为 2 颗、25K 为 2 颗（2026 主页对 25K 写 1 颗，官方两版不一致）。Finals 抽签需要至少 1 个 stone 与有效 UTMB Index。

## 成绩

2027 届尚未举行。2026 届 100K 在 4 月 25 日 05:00 从 China Wall 起跑，官方记录 **678 出发、138 退赛、540 完赛**，完赛率 79.6%。

| 2026 男子前三 | 时间 | 2026 女子前三 | 时间 |
|---|---:|---|---:|
| Adam Peterman | 8:18:47 | Riley Brady | 9:41:09 |
| Zach Miller | 8:21:05 | Careth Arnold | 9:56:36 |
| Hayden Hawks | 8:23:28 | Sarah Allaben | 10:14:58 |

中国跑者 **罗灿华（Canhua Luo）** 以 8:25:17 排男子第四，距领奖台 1 分 49 秒。男子前三直接拿走 Western States Golden Ticket；女子方面 Arnold 与 Allaben 放弃名额，按规则递补给第四 Sarah Humble（10:18:43）与第五 Ellaney Matarese（10:29:16）。

2026 赛前一周因恶劣天气改线，跑者仍面对约 12,300 ft 爬升与 17,000 ft 下降；这也是本页不把 2026 GPX 当成赛日完整轨迹的原因。

## 目标配速与关门压力

2027 官方口径是 100 km、20 小时。下表把 100 km 平均除以目标完赛时间，只给算术基准；它不含爬升、技术路面、补给停留、夜间降速，也不是官方分段计划。

| 目标完赛 | 平均配速 /km | 平均速度 km/h |
|---:|---:|---:|
| 8 小时 | 4:48 | 12.50 |
| 10 小时 | 6:00 | 10.00 |
| 12 小时 | 7:12 | 8.33 |
| 14 小时 | 8:24 | 7.14 |
| 16 小时 | 9:36 | 6.25 |
| 18 小时 | 10:48 | 5.56 |
| 20 小时 | 12:00 | 5.00 |

2026 男子冠军 Adam Peterman 跑出 8:18:47。按 100 km 算约 **4:59/km、12.03 km/h**；按 2026 补给表的 99.1 km 算约 **5:02/km、11.92 km/h**。两种都只是算术换算；2026 还改过线，不能把冠军配速直接当成 2027 的目标。

真正可核的是官方表已公布的关门。把相邻两个已公布时刻与段距离相除，会得到六个隐含平均速度：Start→Deadwood-2 25.4 km / 6.5 h = **3.91 km/h**；Deadwood-2→Michigan Bluff 11.0 km / 1.25 h = **8.80 km/h**；Michigan Bluff→Foresthill 9.5 km / 1.75 h = **5.43 km/h**；Foresthill→Drivers Flat 28.1 km / 5.25 h = **5.35 km/h**；Drivers Flat→Mammoth Bar 12.7 km / 2.5 h = **5.08 km/h**；Mammoth Bar→终点 12.4 km / 2.75 h = **4.51 km/h**。

8.80 km/h 明显不是中游跑者能在 11.0 km、+358 / −417 m 上稳定执行的速度；本页在补给站一节已经把它标成行政关门或表内错位。其余五段在 3.91–5.43 km/h 之间，20 小时全程正好是 5.00 km/h。这说明 2026 表不能被当成一套连贯的配速计划，2027 表发布后必须整表重核。

[![Canyons 100K 2026 六个已公布关门之间的隐含平均速度，Deadwood-2 到 Michigan Bluff 的 8.80 km/h 被单独标红](/media/routes/canyons/canyons-cutoff-pressure.svg)](/media/routes/canyons/canyons-cutoff-pressure.svg)

图：六个已公布关门之间的隐含平均速度。红色 8.80 km/h 是 11.0 km、1.25 小时那一段；它不是官方目标配速，也不代表 2027 赛道。图只用 2026 表已公布时刻做除法，未公布关门的站点不进入计算。

## 分段表：2026 补给表的累计里程

2027 官方没有独立分段表，下面把 2026 版 100K 补给表的累计里程拆成段距离。它只用于理解节奏，不是 2027 的官方分段；2027 表发布后应整表替换。

| 区段 | 本段距离 | 累计里程 | 到达时累计爬升 / 下降 | 备注 |
|---|---:|---:|---:|---|
| Start → Deadwood-1 | 18.0 km | 18.0 km | +671 / −883 m | 下 Eldorado Canyon 后回 Western States Trail |
| Deadwood-1 → Swinging Bridge | 3.7 km | 21.7 km | +1,248 / −1,367 m | 短段，含桥；无补给 |
| Swinging Bridge → Deadwood-2 | 3.7 km | 25.4 km | +1,795 / −2,171 m | 上 Devil's Thumb 后二次进站 |
| Deadwood-2 → Michigan Bluff | 11.0 km | 36.4 km | +2,153 / −2,588 m | 下到 Eldorado Bridge 再爬升 |
| Michigan Bluff → Foresthill | 9.5 km | 45.9 km | +2,374 / −3,292 m | 穿 Volcano Canyon |
| Foresthill → Cal 2 | 13.2 km | 59.1 km | +2,899 / −3,819 m | Cal Street 段 |
| Cal 2 → Drivers Flat | 14.9 km | 74.0 km | +3,199 / −4,443 m | American River 段 |
| Drivers Flat → Mammoth Bar | 12.7 km | 86.7 km | +3,406 / −4,662 m | 上 Mammoth Bar |
| Mammoth Bar → Confluence | 6.0 km | 92.7 km | +3,698 / −4,746 m | Confluence Trail |
| Confluence → Finish | 6.4 km | 99.1 km | 表内未再单列 | No Hands Bridge、Robie Point、Auburn |

官方表在 Confluence 行已经给出终点累计 3,698 / −4,746 m，最后 6.4 km 没有独立累计行；这是表格本身的闭合方式，不是本页漏算。2026 表也没有逐段爬升，只有到达各站的累计值；本页不把总爬升平摊到每段。

## 交通与住宿

- **最近的大型机场**：萨克拉门托国际机场（SMF），官方旅游页写约 35 英里、45 分钟，走 I-80 East。
- **其他机场**：旧金山国际（SFO）约 140 英里、2.5 小时；奥克兰（OAK）约 120 英里、2 小时。三者都有租车服务。
- **市内**：Auburn 市中心可以步行，但 China Wall 起点在城外山路，官方旅游页明确建议租车。2026 日程页有 100K 接驳（02:45 首班、03:45 末班，从 Gold Country Fairgrounds Parking 出发）；2027 日程页尚未发布，不能把 2026 时刻当成 2027 安排。
- **住宿**：Auburn 市区与 I-80 沿线都有酒店；100K 05:00 起跑，住 Auburn 能少一段凌晨山路驾驶。终点在 Downtown Auburn，存包与终点动线比点对点赛事简单。

## 天气与季节

Open-Meteo 的 Auburn 镇历史数据（2015–2025 年 4 月 24–25 日，共 22 天）显示：

- 日最高温 13.1–28.6 °C，中位数 18.8 °C；日最低温 5.9–14.0 °C，中位数 8.6 °C。
- 22 天中有 5 天降水量至少 1 mm，3 天至少 5 mm。

这是 Auburn 镇网格，不是 China Wall、Eldorado Canyon 或 American River 谷底的实测。4 月下旬的峡谷可以明显更热，午后暴露路段与夜间河谷降温是两套体感；起跑 05:00 需要薄外套与头灯，午后需要防晒和盐。

## 撤退与风险

- **可撤退的 crew 点**：100K 是 Deadwood-2、Michigan Bluff、Foresthill；100M 另有 Drivers Flat、Cool-1、Cool-2。不要把 100M 的点位直接套到 100K。
- **存包**：100K 只在 Foresthill 与 Drivers Flat 收包；起终点是否另设终点包，官方表未标，按 unknown 记。
- **风险**：Eldorado Canyon 与 Devil's Thumb 的陡升陡降、American River 段的暴露、夜间 Cal Street 的技术路面，以及 4 月可能的雨後湿滑。官方没有给逐段技术分级，本页按“峡谷反复上下 + 夜间 + 高温”描述，不写成官方评级。
- **退赛**：在补给站向站长报到，按官方指示交号码布/芯片；不要自行离开赛道搭车。100K 的收容与返程安排本次未读到，按 unknown 记。

## 图片与权利

本页使用 3 张 Wikimedia Commons 地点照和 2 张自制 SVG。

- **No Hands Bridge**：`no-hands-bridge-2018.jpg`，正式名 Mountain Quarries Bridge，桥面、绿色河水、岩壁与山坡，Commons 文件页日期 2018-09-01，T71024，CC BY-SA 4.0；960×720，336,358 字节。不是赛事实拍，桥上的人是游客。
- **Michigan Bluff**：`michigan-bluff-2018.jpg`，历史区纪念牌与公告栏，2018-09-30，T71024，CC BY-SA 4.0；960×540，251,723 字节。不是赛事实拍，纪念牌不是赛事指示。
- **Auburn 市区**：`auburn-downtown-2015.jpg`，淘金者雕像与街口，2015-08-22，Noah_Loverbear，CC BY-SA 3.0；960×643，184,652 字节。不是终点线或赛事实拍。
- **11 站顺序图**：`canyons-11-stations.svg`，720×1,560，编辑部自制；等宽行、官方顺序、非距离比例、不是地图、不可导航。
- **关门压力图**：`canyons-cutoff-pressure.svg`，720×820，编辑部自制；只对 2026 表已公布关门做除法，8.80 km/h 单独标红，不是 2027 配速计划。

三张照片均来自 Wikimedia Commons 的 960 px 缩略图，已核对作者、日期、许可、原图尺寸与画面；使用时保留作者署名与对应 CC BY-SA 许可，修改或再发布需同许可共享。No Hands Bridge 的文件名写 2017-04-01，Commons `DateTimeOriginal` 记 2018-09-01，本页以后者为准。两张 SVG 不复制官方 GPX 或地图几何，不画赛道轨迹，不声称官方身份。

官方 2027 100K 页提供的 GPX 与补给表仍是 2026 版，页面写明 `Course maps subject to change`；官方没有给可再分发的图片许可。2026 GPX 已在本地测量，但没有转存、重绘、托管或再分发；本页只链接官方页面并描述路线。

相关页面：[Kodiak Ultra Marathons by UTMB](/routes/kodiak/)、[Western States](/routes/western-states/)、[UTMB](/routes/utmb/)。
