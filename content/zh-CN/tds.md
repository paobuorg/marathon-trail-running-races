---
entityId: route:tds
locale: zh-CN
title: "TDS 2026：从库尔马约尔到霞慕尼的 145 公里，44 小时 55 分的勃朗峰南坡硬线"
summary: "2026 届 TDS 深度资料：官方 145 公里 / 9,500 米爬升的统计口径、官方赛道 JSON 实测 150.772 公里与 +9,322 / −9,509 米、24 个计时点的逐点距离/海拔/关门/服务、12 个中途关门的 44 小时 55 分硬账、2026 年 1,290 条成绩与男女前三、库尔马约尔与霞慕尼的公共交通、赛期历史天气，以及官方 145 / 154 / 150.772 公里三套数字为何不能互相替代；新增 3 张 Wikimedia Commons 许可环境照与 2 张自制结构图。"
aliases: ["TDS", "Sur les Traces des Ducs de Savoie", "TDS 2026", "UTMB TDS", "萨瓦公爵之路"]
authors:
  - runmap-editorial
reviewers:
  - runmap-editorial
translationStatus: reviewed
---

## 核验状态

- 改线核查：官方 TDS 页面没有提供可逐年比对的改线日志；本页没有把“没找到”写成“没有改线”，实体中的 `courseChanges` 为空数组。
- 赛事状态：2026 届已于 2026 年 8 月 24–26 日举行，官方 UTMB Index 已列出 1,290 条成绩；页面同时标注 2027 届正在筹备。
- 规则口径：官网当前展示的是 **2027 Regulations**，不是 2026 版。本页只把这份规则当作“现行规则参照”，涉及 2026 年现场执行时明确标注不确定性。

本条对应 2026 届 TDS。所有数字取自官方赛事页、官方页面内嵌的赛道 JSON、官方 GPX、官方 UTMB Index 成绩页、官方交通页、Open-Meteo 历史天气与第三方 RAVIT 计时分析，核验日为 2026 年 11 月 22 日。

[![库尔马约尔镇与背后的山体，TDS 的起点](/media/routes/tds/courmayeur-view-2015.jpg)](/media/routes/tds/courmayeur-view-2015.jpg)

图：库尔马约尔镇与背后的山体，2015-05-09，Tiia Monto，CC BY-SA 3.0，页内使用 960×349 缩略图。这是起点地点照，不是 TDS 赛事实拍，也不代表比赛当天的天气或路面。

## 三套距离的口径

TDS 最容易被写错的地方不是爬升，而是“到底多少公里”。官方页面、官方成绩页和官方赛道文件给出了三个不同的数，任何一个单独拿出来都能自洽，但不能互相替代。

| 口径 | 距离 | 爬升 / 下降 | 海拔范围 | 性质 |
| --- | ---: | ---: | ---: | --- |
| 官方赛事页统计栏 | 145 km | +9,500 m | 未给 | 报名与赛事介绍使用的整数口径 |
| 官方 UTMB Index 成绩页 | 154 km | +9,500 m | 未给 | 成绩页的比赛分类口径 |
| 官方页面内嵌赛道 JSON | 150.772 km | +9,322 / −9,509 m | 721–2,589 m | 计时与检查点使用的实测轨迹 |
| 第三方 TrailMath | 约 148.2 km | 约 +9,362 m | 未给 | 第三方整理，非官方 |
| 第三方另一套表 | 约 147 km | 约 +9,738 m | 未给 | 第三方整理，非官方 |

本页的处理方式是：**站点卡片用官方统计栏的 145 km / 9,500 m**，因为这是赛事对外报名和介绍的主口径；**逐点表用官方内嵌 JSON 的 150.772 km / +9,322 m / −9,509 m**，因为它能逐点复算；154 km 只作为官方成绩页的另一个口径并列，不与前两者做平均。把 145、150.772、154 三个数平均成“149.9 km”看似整齐，实际是把三套测量对象混成了一个不存在的数。

官方轨迹的最低点在 Seez 附近的 721 m，最高点在 Col Chavannes 的 2,589 m；起点库尔马约尔 1,222 m，终点霞慕尼 1,035 m。下面的剖面只连接 24 个计时点，所以图上的最低计时点是 Bourg-Saint-Maurice 831 m；721 m 是全程轨迹的最低值，不在计时点上。这个海拔剖面解释了为什么 TDS 的爬升集中在比赛前 100 公里，而最后 50 公里仍要在 1,000–2,100 m 之间反复上下。

## 赛道与几何：主线走向

TDS 从库尔马约尔出发，先上到 Mont-Favre 与 Lac Combal 一侧，再翻到 Petit Saint-Bernard，长下坡进入 Bourg-Saint-Maurice。之后进入博福尔坦（Beaufortain）山区：Fort de la Platte、Passeur de Pralognan、Cormet de Roselend、Col de la Sauce、La Gittaz，随后下到 Beaufort，再上 Hauteluce、Barrage de la Girotte、Le Signal，经 Notre Dame de la Gorge、Les Contamines、Chalets du Truc、Col de Tricot、Bellevue、Les Houches，最后进入霞慕尼。

这不是一条“把 UTMB 反过来跑”的路线。UTMB 的主体在霞慕尼—莱孔塔米讷—库尔马约尔之间，TDS 则把博福尔坦和上萨瓦南部的几条山口串起来；两条线路只在霞慕尼终点和少数山谷路段重合。官方介绍特别点名 Beaufortain、Hauteluce、Fort de la Platte、Cormet de Roselend、Passeur de Pralognan 与 Col Chavannes，这几个地名就是读懂赛道的关键。

[![Cormet de Roselend 山口与博福尔坦山坡](/media/routes/tds/cormet-roselend-2005.jpg)](/media/routes/tds/cormet-roselend-2005.jpg)

图：Cormet de Roselend 山口与博福尔坦山坡，2005-10-19，Philipendula，CC BY 2.5，页内使用 960×720 缩略图。这是路线环境照，不是 TDS 赛事实拍；照片里的草坡、碎石与溪流代表的是博福尔坦的地貌，不保证比赛日雪线或水量相同。

几个需要提前在脑子里建模的地方：

- **Lac Combal 之前**：从 1,222 m 上到 2,412 m 的 Mont-Favre，再下到 1,973 m 的 Lac Combal。16.6 公里完成 +1,297 / −546 m，是整场第一个“上得多、下得少”的陡段。
- **Col Chavannes**：2,580 m，是官方轨迹上的最高计时点之一，但不在关门表里；它之后的 16 公里长下坡到 Petit Saint-Bernard，落差超过 1,400 m。
- **Passeur de Pralognan**：2,554 m，官方表在 61.9 公里处给 +4,327 / −2,997 m。到这里已经爬了 4,300 米，但真正的博福尔坦大环还在后面。
- **Cormet de Roselend 到 La Gittaz**：看似只有 7 公里，却要在 1,971 m 与 2,306 m 之间再上再下，随后直落 1,657 m。这一段是整场最容易“以为快到补给、实际还在山口”的地方。
- **Beaufort 之后**：92.4 公里、27 小时 10 分的关门，是全程最关键的“后半程起点”。从这里到 Hauteluce 只有 6.3 公里，却要再爬 493 m；到 Le Signal 还有 16.7 公里和 1,300 米爬升。
- **Les Contamines 之后**：123.2 公里、37 小时 25 分关门，后面还有 Chalets du Truc、Col de Tricot、Bellevue 三个反复上下，最后才是 Les Houches 与霞慕尼。

## 报名与资格

- TDS 属 UTMB World Series 体系；2026 赛页统计栏列出完赛获得 4 颗 Running Stones。
- 个人协助：每名跑者可带一名助手，仅限指定补给站与保留区域；助手包不超过 30 L；除坐位按摩或水泡处理等小护理外，助手不得提供医疗或准医疗服务。
- 资格与报名：已核规则页与赛页未公布 UTMB Index 分数门槛、抽签规则、报名费或年龄下限；本页按未核实处理，不补数字。2026 届 RAVIT 记录 1,285 人起跑（第三方计时分析，与官方成绩表口径可能不同）。
- 退赛与登记：须在关门时刻前离开检查点；无法继续时按组织方指示登记并听从安排。

## 24 个官方计时点

把 24 个点按官方 JSON 的顺序排成 6×4 卡片，先回答“先到哪里、再到哪里”。颜色只用来分组：1–8 是起点到 Petit Saint-Bernard，9–13 是博福尔坦的五段，14–19 是中段，20–24 是收尾。卡片等宽，不代表公里比例，也不是可导航轨迹。

手机阅读：这张宽图在图片容器内横向滚动，点按可打开原图；页面本身不横向溢出。

[![TDS 2026 官方 24 个计时点：库尔马约尔 → Mont-Favre → Col Chavannes → Petit Saint-Bernard → Bourg-Saint-Maurice → 博福尔坦 → Beaufort → Les Contamines → Col de Tricot → 霞慕尼](/media/routes/tds/tds-24-checkpoints.svg)](/media/routes/tds/tds-24-checkpoints.svg)

图内只写点号、地名、累计公里、海拔、关门与“存包/休息/热食/协助”标签；没有画线，也没有把 24 个点连成一条可跑的轨迹。真正的赛道几何仍以官方 GPX 为准，而本站只外链、不转存。

下表的距离、累计爬升/下降、海拔、关门时间与服务标志，全部来自官方页面内嵌的 2026 TDS 赛道 JSON。距离按米制保留到个位，累计爬升/下降按官方 JSON 的整数米；关门时间按官方页面显示的当地日期与时刻。

服务列只写官方 JSON 明示的项目：`水` 表示 drink，`补给` 表示 food，`热食` 表示 hotFood，`存包` 表示 hasBag，`休息` 表示 hasRest，`协助` 表示 isAssistance。没有列出的项目不等于现场绝对没有，只表示官方字段没有标。

| # | 累计 km | 累计 + / − m | 海拔 m | 地点 | 关门（当地） | 服务 |
| ---: | ---: | ---: | ---: | --- | --- | --- |
| 1 | 0.000 | 0 / 0 | 1,222 | Courmayeur | — | 存包、协助 |
| 2 | 7.774 | +811 / −77 | 1,957 | Checrouit – Maison Vieille | — | 水 |
| 3 | 12.270 | +1,273 / −85 | 2,412 | Arête du Mont-Favre | — | — |
| 4 | 16.565 | +1,297 / −546 | 1,973 | Lac Combal | 周二 03:30 | 补给 |
| 5 | 20.629 | +1,904 / −546 | 2,580 | Col Chavannes | — | — |
| 6 | 36.847 | +2,397 / −1,431 | 2,187 | La Thuile – Petit Saint-Bernard | 周二 08:30 | 补给 |
| 7 | 47.748 | +2,403 / −2,732 | 892 | Seez | — | 水 |
| 8 | 51.078 | +2,428 / −2,820 | 831 | Bourg-Saint-Maurice | 周二 11:00 | 补给、协助 |
| 9 | 55.928 | +3,588 / −2,820 | 1,990 | Fort de la Platte | 周二 13:45 | — |
| 10 | 61.938 | +4,327 / −2,997 | 2,554 | Passeur de Pralognan | — | — |
| 11 | 66.166 | +4,330 / −3,581 | 1,971 | Cormet de Roselend | 周二 17:15 | 补给 |
| 12 | 69.056 | +4,669 / −3,585 | 2,306 | Col de la Sauce | — | — |
| 13 | 73.750 | +4,697 / −4,262 | 1,657 | La Gittaz | 周二 19:30 | 补给 |
| 14 | 92.421 | +5,666 / −6,150 | 739 | Beaufort | 周三 03:00 | 热食、存包、休息、协助 |
| 15 | 98.733 | +6,159 / −6,209 | 1,174 | Hauteluce | 周三 05:30 | 补给 |
| 16 | 107.410 | +7,047 / −6,494 | 1,777 | Barrage de la Girotte | — | — |
| 17 | 115.478 | +7,480 / −6,824 | 1,876 | Le Signal | 周三 11:15 | 补给 |
| 18 | 119.248 | +7,480 / −7,494 | 1,208 | Notre Dame de la Gorge | — | — |
| 19 | 123.197 | +7,500 / −7,565 | 1,157 | Les Contamines | 周三 13:15 | 补给、协助 |
| 20 | 126.699 | +8,056 / −7,565 | 1,714 | Chalets du Truc | — | 协助 |
| 21 | 130.350 | +8,644 / −7,749 | 2,117 | Col de Tricot | — | — |
| 22 | 137.034 | +9,044 / −8,470 | 1,796 | Bellevue | 周三 18:15 | — |
| 23 | 141.583 | +9,044 / −9,257 | 1,008 | Les Houches | 周三 19:15 | 补给 |
| 24 | 150.772 | +9,322 / −9,509 | 1,035 | Chamonix | 周三 20:45 | 热食、存包、休息、协助 |

这张表最重要的不是“有几个补给点”，而是 **存包只在起点、Beaufort 和终点**，**休息区只在 Beaufort、Les Contamines、Chalets du Truc 和终点**，**亲友协助只在库尔马约尔、Bourg-Saint-Maurice、Beaufort、Les Contamines、Chalets du Truc 和霞慕尼**。如果你把备用鞋、干衣或夜段装备放进“以为会出现”的中途包，到了现场会发现根本没有这个包。

## 海拔剖面：六段起伏

[![TDS 2026 官方 24 个计时点的海拔剖面：起点 1,222 m，最高计时点 Col Chavannes 2,580 m，最低计时点 Bourg-Saint-Maurice 831 m，终点霞慕尼 1,035 m；全程轨迹最低 721 m 不在计时点上](/media/routes/tds/tds-elevation-profile.svg)](/media/routes/tds/tds-elevation-profile.svg)

图：按官方 2026 TDS 赛道 JSON 的 24 个计时点重绘。折线只连接计时点，不是完整 GPX 的逐米采样；官方整条轨迹最高点另写 2,589 m，与计时点 Col Chavannes 的 2,580 m 不是同一个读数，本页不把两者混用。

把剖面拆成六段，比记单个爬升总数更有用：

1. **0–20.629 km，起点到 Col Chavannes**：从 1,222 m 爬到 2,580 m，累计 +1,904 / −546 m。Mont-Favre 2,412 m 与 Col Chavannes 2,580 m 是两个连续高点，中间只下降 439 m；这一段在夜里完成，不能用“刚出发还有力气”估算。
2. **20.629–51.078 km，长下坡到 Bourg-Saint-Maurice**：从 2,580 m 降到 831 m，累计只再 +524 / −2,274 m。Petit Saint-Bernard 2,187 m 之后是整场最长的连续下降之一；下到 Seez 892 m 时，膝盖和大腿前侧已经开始承担多数人没有训练过的离心负荷。
3. **51.078–73.750 km，博福尔坦五段**：从 831 m 再爬到 Passeur de Pralognan 2,554 m，累计 +2,269 / −1,442 m，途中经过 Fort de la Platte 1,990 m、Cormet de Roselend 1,971 m、Col de la Sauce 2,306 m，最后落到 La Gittaz 1,657 m。这不是一个“大上大下”，而是五次反复；每一次都足以把配速打回徒步。
4. **73.750–92.421 km，下到 Beaufort**：累计 +969 / −1,888 m，海拔从 1,657 m 降到 739 m。Beaufort 是全程唯一“存包 + 休息 + 热食 + 协助”四项齐全的中点，也是 27 小时 10 分关门的关键节点。
5. **92.421–123.197 km，中段再爬升**：从 739 m 经 Hauteluce 1,174 m、Barrage de la Girotte 1,777 m、Le Signal 1,876 m 到 Les Contamines 1,157 m，累计 +1,834 / −1,415 m。这一段没有存包，头灯、备用电池与保暖层必须从 Bourg 一直背到这里。
6. **123.197–150.772 km，最后 27.6 km**：累计 +1,822 / −1,944 m，经 Chalets du Truc 1,714 m、Col de Tricot 2,117 m、Bellevue 1,796 m、Les Houches 1,008 m，最后回到霞慕尼 1,035 m。最后一段仍有 2,117 m 的 Col de Tricot，不能把“只剩一个马拉松”当成平路收尾。

六段累计相加为官方 JSON 的 **+9,322 / −9,509 m**。这只是 24 个计时点之间的累计值，不等于完整 GPX 逐点重算；两者不能混用，也不能拿来互相“纠正”。

## 44 小时 55 分的硬账：每个关门点要求的最低平均速度

把官方 12 个中途关门与终点放在同一条时间轴上，可以看到一个反直觉的事实：**前面并不宽松，后面也没有“熬到就行”**。从 23:50 起跑算起，到 Lac Combal 只有 3 小时 40 分，却已经走了 16.6 公里、爬了 1,297 米；到 Petit Saint-Bernard 的 8 小时 40 分，已经完成 36.8 公里和 2,397 米爬升。

| 关门点 | 累计 km | 已用时 | 距起点平均配速 | 备注 |
| --- | ---: | ---: | ---: | --- |
| Lac Combal | 16.565 | 3:40 | 13:16 /km | 第一个硬关门 |
| Petit Saint-Bernard | 36.847 | 8:40 | 14:07 /km | 长下坡前的最后高点 |
| Bourg-Saint-Maurice | 51.078 | 11:10 | 13:07 /km | 第一次可亲友协助 |
| Fort de la Platte | 55.928 | 13:55 | 14:53 /km | 博福尔坦第一爬 |
| Cormet de Roselend | 66.166 | 17:25 | 15:47 /km | 进入傍晚 |
| La Gittaz | 73.750 | 19:40 | 16:00 /km | 天黑前后 |
| Beaufort | 92.421 | 27:10 | 17:37 /km | 存包、休息、热食 |
| Hauteluce | 98.733 | 29:40 | 18:01 /km | 后半夜爬升 |
| Le Signal | 115.478 | 35:25 | 18:22 /km | 第二天上午 |
| Les Contamines | 123.197 | 37:25 | 18:13 /km | 第二次休息/协助 |
| Bellevue | 137.034 | 42:25 | 18:33 /km | 最后的山口 |
| Les Houches | 141.583 | 43:25 | 18:22 /km | 进霞慕尼谷底 |
| Chamonix | 150.772 | 44:55 | 17:52 /km | 终点 |

这张表是把“已用时 / 累计距离”直接相除，得到的是**从起点到该点的整体最低平均配速**，不是该段的分段配速。实际比赛里，前面陡上会远慢于 13 分钟/公里，后面下坡可以抢回一些；如果你在 Lac Combal 之前已经明显慢于 13 分钟/公里，后面必须用更快的下坡补回来，而 TDS 的下坡并不都是可跑的。

2026 年男子冠军 Rémy Brassac 用 19:28:43 完成官方 150.772 公里轨迹，折合全程约 7.75 km/h、7:45 /km；这个速度与 44:55 的关门线之间差了 25 小时以上。对绝大多数人，真正要管理的是“每个关门点前留出 30–60 分钟余量”，而不是照冠军配速做计划。

## 目标完赛与平均配速

官方终点关门是 **44:55**。用 150.772 km 的计时点距离做匀速换算，可以得到下面这组“移动平均”参考；它不包含爬升、补给、排队与停留，也不能直接当成比赛执行配速。

| 目标完赛 | 平均配速 | 平均速度 |
| --- | ---: | ---: |
| 24:00 | 9:33 /km | 6.28 km/h |
| 28:00 | 11:09 /km | 5.38 km/h |
| 32:00 | 12:44 /km | 4.71 km/h |
| 36:00 | 14:20 /km | 4.19 km/h |
| 40:00 | 15:55 /km | 3.77 km/h |
| 44:55 | 17:52 /km | 3.36 km/h |

这六行只回答“如果整场保持同一速度，需要多快”。TDS 的真实速度曲线会在前 20 公里的爬升、Petit Saint-Bernard 之后的长下坡、博福尔坦五次反复和最后 Col de Tricot 之间大幅波动；把 9:33 /km 当成每公里都要跑到的配速，会在第一个补给点之前就透支。

## 补给、存包与亲友：把“以为有”变成“确认有”

TDS 的补给结构是典型的 UTMB 半自给：官方只在检查点提供饮水与现场食用食物，部分点有热食；离开补给点时，你要自己带够到下一个点的水和食物。官方规则明确，TDS 允许在指定补给站接受一名亲友协助，协助范围只是一个不超过 30 升的包，医疗协助被严格限制；这不是“全程有人跟跑”的比赛。

| 能力 | 官方位置 | 实战含义 |
| --- | --- | --- |
| 存包 | 库尔马约尔、Beaufort、霞慕尼 | 只能在这三处取放；不要把中途换装放进不存在的包 |
| 休息 | Beaufort、Les Contamines、Chalets du Truc、霞慕尼 | 有休息区不等于有床位；后半夜仍要自己控时间 |
| 亲友协助 | 库尔马约尔、Bourg-Saint-Maurice、Beaufort、Les Contamines、Chalets du Truc、霞慕尼 | 只能在指定区域；别指望在任意山口接应 |
| 热食 | Beaufort、霞慕尼 | 官方 JSON 只标这两处 hotFood；其他点以现场为准 |
| 饮水 | Checrouit、Seez、Lac Combal、Petit Saint-Bernard、Bourg、Cormet、La Gittaz、Hauteluce、Le Signal、Les Contamines、Les Houches、终点 | 多数点只给水/饮料，食物要自备一段 |

一个实用的分段策略是：

- **库尔马约尔 → Lac Combal**：带 1.0–1.5 升水，按天气加到 2 升；这一段没有官方 food，只有 Lac Combal 的 food。
- **Lac Combal → Petit Saint-Bernard**：官方在 Lac Combal 给 food，但到 Petit Saint-Bernard 还有 20 公里和 1,100 米爬升；不要在这里把包吃空。
- **Bourg → Beaufort**：Bourg 有 food 与协助，但到 Beaufort 还有 41 公里、+3,238 / −5,419 m；这是全程最长的一段“没有存包”区间，备用电池、头灯、保暖层都要随身。
- **Beaufort → Les Contamines**：Beaufort 是全程唯一“存包 + 休息 + 热食 + 协助”四项齐全的中点；在这里换鞋、补睡、吃热食都要算进 27:10 的关门余量。
- **Les Contamines → 霞慕尼**：还有 27.6 公里和 +1,822 / −1,944 m，Col de Tricot 2,117 m 是最后的硬爬；不要因为“只剩一个马拉松”就少带水。

## 装备与规则

规则要求全程携带强制装备；起点、途中与终点可组织抽查，缺少关键安全装备可被取消资格。已核规则页没有展开逐项清单，本站不列未核实条目。

| 项目 | 规则口径 | 依据 |
| --- | --- | --- |
| 强制装备 | 全程携带；抽查；缺关键安全装备可取消资格 | 2027 规则第 3 条 |
| 登山杖 | 若使用须从起点携带；赛中不能拾取，不能放入存包袋 | 2027 规则第 4 条 |
| 助手包 | 不超过 30 L；仅限指定区域 | 2027 规则第 2 条 |
| 检查点 | 所有官方补给点同时是检查点；未打卡可被取消资格 | UTMB 体系规则口径 |

夜间起跑与高海拔山口的装备要求在“天气”一节并列：防水壳、保暖中层、头灯与备用电池都要随身；具体逐项清单以当届 Runner Guide 为准。

## 天气：山谷与山口是两套系统

用 Open-Meteo 的 ERA5 再分析资料，把 2015–2025 年每年 8 月 24–26 日这三天筛出来，三个山谷站点各有 33 个日记录。下面是日最高/最低气温的范围与中位数，以及≥1 mm、≥5 mm 的降水日数：

| 地点 | 日最高范围 / 中位 | 日最低范围 / 中位 | ≥1 mm | ≥5 mm |
| --- | --- | --- | ---: | ---: |
| Courmayeur（1,222 m 起点） | 17.1–32.1 °C / 24.4 °C | 6.0–16.8 °C / 10.6 °C | 10 / 33 | 5 / 33 |
| Beaufort（739 m 中点） | 15.3–34.7 °C / 25.0 °C | 9.0–18.6 °C / 13.4 °C | 10 / 33 | 6 / 33 |
| Chamonix（1,035 m 终点） | 12.8–33.5 °C / 23.8 °C | 7.1–18.9 °C / 11.7 °C | 12 / 33 | 5 / 33 |

这组数字只代表山谷。TDS 的最高点 2,589 m，按一般山地递减率会比山谷低 10–15 °C；如果遇到降雨和大风，体感还会再低。2026 年的实际比赛报告提到起跑时暴雨、后段转热，这类“先冷后热”的组合在 8 月的勃朗峰南坡并不罕见。装备上要同时准备**防水壳、保暖中层、头灯与备用电池**，不能只按霞慕尼镇上的温度打包。

## 交通：库尔马约尔不是霞慕尼的步行郊外

TDS 的起点在意大利库尔马约尔，终点在法国霞慕尼。两地直线距离只有 15 公里左右，但中间隔着勃朗峰，实际要绕行隧道或坐巴士。官方交通页给的建议很明确：**不要开私家车进库尔马约尔**，镇中心停车位在赛事期间基本饱和。

| 出发地 | 官方建议 | 大致距离/时间 |
| --- | --- | --- |
| 霞慕尼 | Flixbus 或 Arriva 的公共巴士，双向运行 | 过勃朗峰隧道，约 30–60 分钟（视边境与班次） |
| 日内瓦机场（GVA） | Flixbus 直达库尔马约尔 | 约 115 公里 |
| 都灵机场（TRN） | 火车到 Aosta，再转 Arriva 巴士 | 约 150 公里；都灵到 Aosta 火车 <120 分钟 |
| 米兰马尔彭萨（MXP） | 火车到 Aosta（Chivasso 换乘），再转巴士 | 约 212 公里；米兰到 Aosta 约 180 分钟 |

一个容易踩的坑：官方页面明确写到 **2026 年 12 月 13 日之前，Ivrea–Aosta 铁路因电气化施工停运，由巴士替代**。TDS 在 8 月举行，正好落在这个窗口内；如果你按“火车直达 Aosta”做计划，到了 Ivrea 会被要求换巴士。把这段巴士时间算进去，都灵/米兰方向的行程要留出额外余量。

终点霞慕尼的返程，官方没有为 TDS 发布专门的赛后接驳表；最稳的做法是提前订好霞慕尼的住宿，第二天再坐巴士回库尔马约尔取车或取行李。不要把“终点在霞慕尼”理解成“赛后立刻能回库尔马约尔”。

## 难度与风险

RAVIT 的第三方计时分析记录 2026 年 TDS 有 1,285 人出发、44.4% 未完赛，23 个计时点，中位停赛点在 66.09 公里；Beaufort 有 137 人停赛，Cormet de Roselend 103 人，Bourg-Saint-Maurice 76 人，La Gittaz 56 人，Fort de la Platte 36 人，Lac Combal 34 人，Petit-Saint-Bernard 25 人，Hauteluce 22 人。这是第三方统计，不是官方完赛率，但它和官方 1,290 条成绩并不矛盾：官方成绩页列的是有成绩的记录，第三方统计的是出发与退赛。

TDS 的主要风险不是“某一段特别难”，而是四件事叠加：

1. **夜间起跑**：23:50 出发，前 8 小时几乎全在黑夜里，头灯、备用电池、防雨是硬需求。
2. **高海拔山口**：Col Chavannes 2,580 m、Passeur de Pralognan 2,554 m、Col de la Sauce 2,306 m、Col de Tricot 2,117 m；夏季也可能遇到 5–10 °C 加风雨。
3. **长距离无存包区间**：Bourg 到 Beaufort 的 41 公里没有存包，装备必须一次带够。
4. **后程反复上下**：Beaufort 之后还有 58 公里和 +3,656 / −3,359 m，不是“下坡收尾”。

退赛与下撤：官方规则要求在所有检查点遵守关门时间，退赛要按组织方指示登记；TDS 的亲友协助只在指定站，医疗协助由官方医疗团队负责。Beaufort、Les Contamines、Chalets du Truc、霞慕尼有休息/协助标志，但“有休息区”不等于“有随时可用的下撤车辆”。真正需要下撤时，先到最近检查点找站长，不要离开标记路线自己去找路。

## 训练转化

TDS 是近 145–151 km、约 9,300–9,500 m 爬升的博福尔坦山地长距离，准备重点是山地耐久、跨夜与长段无存包区间。下表只映射已核实事实，不提供个人训练处方。

| 已核实事实 | 训练转化方向 | 本站参考页 |
| --- | --- | --- |
| 145 km（赛页）/ 150.772 km（官方轨迹）、+9,500 m（赛页）/ +9,322 m（轨迹） | 长距离山地耐久与爬升储备 | [超马基础](/knowledge/ultra-running-basics/)、[山地步道基础](/knowledge/hill-and-mountain-path-basics/) |
| Beaufort、Cormet de Roselend、Bourg-Saint-Maurice 为主要退赛点 | 长距离疲劳分段与下坡耐受 | [下坡跑法](/knowledge/downhill-running-technique/)、[训练量与进阶](/knowledge/training-volume-and-progression/) |
| 23:50 夜间起跑，前 8 小时在黑夜中 | 夜跑练习与照明习惯 | [夜跑与路况](/knowledge/night-running-and-traffic/) |
| Bourg → Beaufort 41 km 无存包 | 长段自理补给与随身装备 | [长距离补给](/knowledge/long-run-fueling/) |
| 助手仅限指定站 | crew 分工与接应点提前排好 | [crew 与 pacer 计划](/knowledge/crew-and-pacer-planning/) |

决策分支：

| 如果准备状态是 | 那么对应判断 |
| --- | --- |
| 没有完成过百公里级山地赛 | 先补长距离耐久与爬升量，不按 44:55 时限倒推配速 |
| 夜间长练不足 | 先补夜跑经验，再规划起跑夜段的照明与补给 |
| 没练过 40 km 级无补给区间 | 先练长段自理，再评估 Bourg→Beaufort 段的随身装备 |
| 计划指定站接应 | 按官方六个协助点安排，不在任意山口等接应 |

## 比赛日执行卡

下表只列已核实节点与角色；未公布的关门分秒不补写。

| 节点 | 已核实动作 | 关键约束 |
| --- | --- | --- |
| Courmayeur 起点 1,222 m | 2026-08-24 23:50 出发；存包 #1 | 装备检查通过；助手登记在指定站 |
| Lac Combal / Petit Saint-Bernard | 关门点，饮水与 food 点 | 须在关门时刻前离开 |
| Bourg-Saint-Maurice | 补给与协助点 | 无存包；此后 41 km 到 Beaufort |
| Fort de la Platte / Cormet de Roselend | 主要退赛点之一 | 体力与装备在此段评估 |
| Beaufort 92.4 km | 存包、休息、热食、协助四项齐全的中点 | 27:10 关门余量要算进换装与休息 |
| Les Contamines | 休息区、协助点 | 后段还有反复上下 |
| Les Houches → Chamonix 终点 1,035 m | 收官段 | 总时限 44:55；退赛按组织方指示 |

## 2026 成绩

官方 UTMB Index 的 TDS 2026 页面列出 1,290 条成绩，比赛日期 2026 年 8 月 24 日，城市库尔马约尔。男子前三与女子前三如下：

| 男子 | 成绩 | 女子 | 成绩 |
| --- | ---: | --- | ---: |
| Rémy Brassac（FR） | 19:28:43 | Sarah Vieuille（FR） | 22:08:16 |
| Pierre-Adrien Hivert（FR） | 20:14:26 | Alice Meignié（FR） | 22:30:29 |
| Nicolas Court（FR） | 20:56:52 | Alyssa Clark（US） | 22:54:19 |

[![霞慕尼山谷与勃朗峰，从 la Flégère 俯瞰](/media/routes/tds/chamonix-valley-2010.jpg)](/media/routes/tds/chamonix-valley-2010.jpg)

图：霞慕尼山谷与勃朗峰，从 la Flégère 俯瞰，2010-07-31，Ximonic, Simo Räsänen，CC BY-SA 3.0，页内使用 960×640 缩略图。照片展示的是终点山谷的地形关系，不是 2026 年 TDS 的终点实拍。

如果把女子冠军 22:08:16 放回 44:55 的关门线，她仍有 22 小时以上的余量；这也说明 TDS 的关门不是“为精英设的”，而是为大量业余跑者留出了完整的徒步+慢跑空间。真正会把人挡在门外的是前面几个关门的“累计时间”，不是终点那一条线。

## 图片与权利

三张照片都是路线环境照，不是 TDS 赛事实拍，也不代表 2026 届比赛当天的天气、雪线、路面或补给布置：

- **库尔马约尔**：`File:Courmayeur view.jpg`，作者 Tiia Monto，CC BY-SA 3.0，拍摄日期 2015-05-09；原图 8,445×3,073，页内使用 960×349 缩略图。画面是起点镇区、道路与背后山体。
- **Cormet de Roselend**：`File:Cormet de Roselend F.jpg`，作者 Philipendula，CC BY 2.5，Commons 上传日期 2005-10-19；原图 2,560×1,920，页内使用 960×720 缩略图。画面是博福尔坦山口草坡、碎石与溪流。
- **霞慕尼山谷**：`File:Chamonix valley from la Flégère,2010 07.JPG`，作者 Ximonic, Simo Räsänen，CC BY-SA 3.0，拍摄日期 2010-07-31；原图 3,750×2,500，页内使用 960×640 缩略图。画面是终点山谷与勃朗峰山体。

两张自制 SVG 由跑起来编辑部制作：`tds-24-checkpoints.svg`（24 个官方计时点，6×4 等宽卡片）与 `tds-elevation-profile.svg`（24 个计时点的海拔折线）。它们不是官方地图、不是完整 GPX 剖面、不是导航轨迹，也不能替代官方 GPX；最高计时点与官方整条轨迹最高点的 9 米差异已在正文并列。

官方页面与官方社交账号有赛事照片，但没有给出可再分发的许可；官方 GPX 的元数据把版权标给 LiveTrail®，也没有开放许可。因此本页不嵌入官方照片或赛道图，只链接官方页面与 GPX。赛道几何用官方计时点表、自制顺序图与自制剖面表达，不用未经许可的截图替代。

## 来源与核查

- 官方赛事页：`https://montblanc.utmb.world/en/races/tds`（统计栏、日期、起跑时间、44:55、2027 筹备提示）。
- 官方赛道 JSON：同上页面内嵌的 `points` 数组（24 个计时点、150.772 km、+9,322 / −9,509 m、服务与关门）。
- 官方 GPX：`https://pdf.utmb.world/raw/upload/v1786442970/montblanc/Races/GPX/2026/TDS_2026_098e06c78e.gpx`（LiveTrail 版权，未给再分发许可）。
- 官方成绩：`https://utmb.world/utmb-index/races/646.hokautmbmont-blanctds.2026`（1,290 条、男女前三、154 km 口径）。
- 官方规则：`https://montblanc.utmb.world/races-runners/other-information/regulation`（当前为 2027 版，作为规则参照）。
- 官方交通：`https://montblanc.utmb.world/discover/transportation/courmayeur`（霞慕尼巴士、日内瓦/都灵/米兰机场、Ivrea–Aosta 巴士替代）。
- 历史天气：Open-Meteo ERA5 archive，2015–2025 年 8 月 24–26 日，Courmayeur / Beaufort / Chamonix 三点。
- 第三方计时：`https://ravit.live/trail/mont-blanc-tds/analyse`（1,285 出发、44.4% 未完赛、停赛分布；仅作第三方参照）。
- 照片：`https://commons.wikimedia.org/wiki/File:Courmayeur_view.jpg`（Tiia Monto，CC BY-SA 3.0，2015-05-09；960×349 缩略图）。
- 照片：`https://commons.wikimedia.org/wiki/File:Cormet_de_Roselend_F.jpg`（Philipendula，CC BY 2.5，Commons 上传日期 2005-10-19；960×720 缩略图）。
- 照片：`https://commons.wikimedia.org/wiki/File:Chamonix_valley_from_la_Fl%C3%A9g%C3%A8re,2010_07.JPG`（Ximonic, Simo Räsänen，CC BY-SA 3.0，2010-07-31；960×640 缩略图）。
- 第三方检查点：TrailMath 的 TDS 页面只用于交叉核对，未作为官方口径写入表格。

未核到的内容：2026 届 TDS 的官方逐站关门 PDF 路书没有单独取得；本页的逐点关门来自官方页面内嵌 JSON，而不是 PDF。官方 2026 与 2027 的规则差异没有逐条比对；本页只把 2027 规则作为现行参照。官方没有发布 2026 届的官方完赛率，44.4% 是 RAVIT 的第三方统计。

<!-- related-ring -->
## 相关条目

- [UTCT 开普敦越野赛 2026：100 公里与 100 英里官方成绩](/routes/utct/)
- [UTMB 环勃朗峰：2026 赛道全解](/routes/utmb/)
- [西部各州 100 英里：2026 赛道全解](/routes/western-states/)
