---
entityId: route:tds
locale: en
title: "TDS 2026: 145 km from Courmayeur to Chamonix, 44 hours 55 minutes"
summary: "A 2026 TDS dossier: the official 145 km / 9,500 m stat block, the official course JSON measuring 150.772 km with +9,322 / −9,509 m, 24 timing points with distance, elevation, cut-off and services, the 12 intermediate cut-offs behind the 44:55 limit, 1,290 official results and podium, public transport to Courmayeur and Chamonix, ten years of race-window weather, and why the official 145 / 154 / 150.772 km figures cannot be averaged; now with three licensed location photographs and two original structural graphics."
aliases: ["TDS", "Sur les Traces des Ducs de Savoie", "TDS 2026", "UTMB TDS", "Dukes of Savoy Trail"]
authors:
  - runmap-editorial
reviewers:
  - runmap-editorial
translationStatus: reviewed
---

## Verification status

- Course-change check: the official TDS page does not publish a year-by-year change log. This page does not turn “not found” into “no change”; the entity keeps `courseChanges` as an empty array.
- Race status: the 2026 edition was held on 24–26 August 2026, and the official UTMB Index already lists 1,290 results. The official page also says the 2027 edition is being prepared.
- Rule basis: the official site currently displays the **2027 Regulations**, not a 2026 archive. This page uses that text only as a current rule reference and flags where 2026 enforcement is not documented.

This page covers the 2026 TDS. Figures come from the official race page, the course JSON embedded in that page, the official GPX, the official UTMB Index result page, the official transport page, Open-Meteo's historical archive and RAVIT's third-party timing analysis. Verification date: 22 November 2026.

[![The town of Courmayeur and the mountain behind it, where TDS starts](/media/routes/tds/courmayeur-view-2015.jpg)](/media/routes/tds/courmayeur-view-2015.jpg)

Photo: Courmayeur and the mountain behind the town, 9 May 2015, Tiia Monto, CC BY-SA 3.0, shown here as a 960×349 thumbnail. It is a location photograph of the start town, not a TDS race photograph, and does not represent race-day weather or road conditions.

## The three distance figures

The easy mistake with TDS is not the climb; it is the distance. The official race page, the official result page and the official course file give three different numbers. Each is internally coherent, but none can replace the others.

| Basis | Distance | Gain / loss | Elevation range | What it is |
| --- | ---: | ---: | ---: | --- |
| Official race stat block | 145 km | +9,500 m | not stated | The headline figure used for entries and race presentation |
| Official UTMB Index result page | 154 km | +9,500 m | not stated | The race-category figure on the results page |
| Official embedded course JSON | 150.772 km | +9,322 / −9,509 m | 721–2,589 m | The measured trace used for timing and checkpoints |
| TrailMath (third party) | c. 148.2 km | c. +9,362 m | not stated | Third-party compilation, not official |
| Another third-party table | c. 147 km | c. +9,738 m | not stated | Third-party compilation, not official |

This page handles it as follows: **the site card uses the official stat block, 145 km / 9,500 m**, because that is the race's public headline; **the point-by-point table uses the official embedded JSON, 150.772 km / +9,322 m / −9,509 m**, because it can be recomputed point by point. The 154 km figure is presented as the official result page's separate basis, not averaged with the others. Averaging 145, 150.772 and 154 into “149.9 km” looks tidy, but it mixes three different measurement objects into a number that exists nowhere.

The official trace bottoms out at 721 m near Seez and tops out at 2,589 m at Col Chavannes. The start in Courmayeur is 1,222 m and the finish in Chamonix is 1,035 m. The profile below connects only the 24 timing points, so its lowest timing point is Bourg-Saint-Maurice at 831 m; the 721 m trace minimum is not a timing point. That profile explains why the climbing is concentrated in the first 100 km while the last 50 km still roll between roughly 1,000 and 2,100 m.

## The course

TDS starts in Courmayeur, climbs toward Mont-Favre and Lac Combal, crosses to Petit Saint-Bernard and descends into Bourg-Saint-Maurice. It then enters the Beaufortain: Fort de la Platte, Passeur de Pralognan, Cormet de Roselend, Col de la Sauce and La Gittaz, before dropping to Beaufort. From there it climbs again over Hauteluce, Barrage de la Girotte and Le Signal, then passes Notre Dame de la Gorge, Les Contamines, Chalets du Truc, Col de Tricot, Bellevue and Les Houches before reaching Chamonix.

This is not “UTMB run backwards”. UTMB's main body links Chamonix, Les Contamines and Courmayeur; TDS strings together the Beaufortain and the southern Haute-Savoie passes. The two courses share the Chamonix finish and a few valley sections, not the main route. The official description names Beaufortain, Hauteluce, Fort de la Platte, Cormet de Roselend, Passeur de Pralognan and Col Chavannes; those are the places to model before race day.

[![Cormet de Roselend and the Beaufortain slopes](/media/routes/tds/cormet-roselend-2005.jpg)](/media/routes/tds/cormet-roselend-2005.jpg)

Photo: Cormet de Roselend and the Beaufortain slopes, 19 October 2005, Philipendula, CC BY 2.5, shown here as a 960×720 thumbnail. It is a route-environment photograph, not a TDS race photograph; the grass, scree and stream show the Beaufortain terrain, not race-day snowline or water levels.

Key sections to know:

- **Before Lac Combal:** from 1,222 m up to 2,412 m at Mont-Favre, then down to 1,973 m. The first 16.6 km gain 1,297 m and lose only 546 m.
- **Col Chavannes:** 2,580 m, one of the highest timing points but not a cut-off. The next 16 km to Petit Saint-Bernard lose more than 1,400 m.
- **Passeur de Pralognan:** 2,554 m at km 61.9, with +4,327 / −2,997 m already accumulated. The big Beaufortain loop is still ahead.
- **Cormet de Roselend to La Gittaz:** only 7 km, but it goes up to 2,306 m and then drops to 1,657 m. This is where “almost at the aid station” can be false.
- **After Beaufort:** km 92.4 and a 27:10 cut-off. It is the real start of the second half. Hauteluce is only 6.3 km away but adds 493 m; Le Signal is another 16.7 km and about 1,300 m of climbing.
- **After Les Contamines:** km 123.2 and a 37:25 cut-off. Chalets du Truc, Col de Tricot and Bellevue still stand between you and Les Houches.

## The 24 official timing points

The 24 points are arranged here in a 6×4 card grid in official JSON order, to answer “what comes next”. Colour only groups the course: 1–8 from the start to Petit Saint-Bernard, 9–13 the five Beaufortain steps, 14–19 the middle, and 20–24 the finish. The cards are equal width, do not represent distance proportion and are not a navigable trace.

Mobile reading: this wide graphic scrolls horizontally inside its image container; tap to open the full file. The page itself does not overflow horizontally.

[![TDS 2026 official 24 timing points: Courmayeur → Mont-Favre → Col Chavannes → Petit Saint-Bernard → Bourg-Saint-Maurice → Beaufortain → Beaufort → Les Contamines → Col de Tricot → Chamonix](/media/routes/tds/tds-24-checkpoints.svg)](/media/routes/tds/tds-24-checkpoints.svg)

The graphic gives only the point number, place, cumulative distance, elevation, cut-off and “bag / rest / hot food / crew” tags. It draws no line and does not turn the 24 points into a runnable trace. The real geometry remains the official GPX, which this site links to and does not re-host.

Distances, cumulative gain/loss, elevation, cut-offs and service flags below come from the official 2026 course JSON embedded in the race page. Distances are shown to the nearest metre and gain/loss as the JSON integers. Cut-offs are local times as displayed by the official page.

The service column only lists what the official JSON explicitly marks: `water` = drink, `food` = food, `hot` = hotFood, `bag` = hasBag, `rest` = hasRest, `crew` = isAssistance. A missing item means the field is not marked, not that the service is guaranteed absent.

| # | Cumulative km | Cumulative + / − m | Elev. m | Place | Cut-off (local) | Services |
| ---: | ---: | ---: | ---: | --- | --- | --- |
| 1 | 0.000 | 0 / 0 | 1,222 | Courmayeur | — | bag, crew |
| 2 | 7.774 | +811 / −77 | 1,957 | Checrouit – Maison Vieille | — | water |
| 3 | 12.270 | +1,273 / −85 | 2,412 | Arête du Mont-Favre | — | — |
| 4 | 16.565 | +1,297 / −546 | 1,973 | Lac Combal | Tue 03:30 | food |
| 5 | 20.629 | +1,904 / −546 | 2,580 | Col Chavannes | — | — |
| 6 | 36.847 | +2,397 / −1,431 | 2,187 | La Thuile – Petit Saint-Bernard | Tue 08:30 | food |
| 7 | 47.748 | +2,403 / −2,732 | 892 | Seez | — | water |
| 8 | 51.078 | +2,428 / −2,820 | 831 | Bourg-Saint-Maurice | Tue 11:00 | food, crew |
| 9 | 55.928 | +3,588 / −2,820 | 1,990 | Fort de la Platte | Tue 13:45 | — |
| 10 | 61.938 | +4,327 / −2,997 | 2,554 | Passeur de Pralognan | — | — |
| 11 | 66.166 | +4,330 / −3,581 | 1,971 | Cormet de Roselend | Tue 17:15 | food |
| 12 | 69.056 | +4,669 / −3,585 | 2,306 | Col de la Sauce | — | — |
| 13 | 73.750 | +4,697 / −4,262 | 1,657 | La Gittaz | Tue 19:30 | food |
| 14 | 92.421 | +5,666 / −6,150 | 739 | Beaufort | Wed 03:00 | hot food, bag, rest, crew |
| 15 | 98.733 | +6,159 / −6,209 | 1,174 | Hauteluce | Wed 05:30 | food |
| 16 | 107.410 | +7,047 / −6,494 | 1,777 | Barrage de la Girotte | — | — |
| 17 | 115.478 | +7,480 / −6,824 | 1,876 | Le Signal | Wed 11:15 | food |
| 18 | 119.248 | +7,480 / −7,494 | 1,208 | Notre Dame de la Gorge | — | — |
| 19 | 123.197 | +7,500 / −7,565 | 1,157 | Les Contamines | Wed 13:15 | food, crew |
| 20 | 126.699 | +8,056 / −7,565 | 1,714 | Chalets du Truc | — | crew |
| 21 | 130.350 | +8,644 / −7,749 | 2,117 | Col de Tricot | — | — |
| 22 | 137.034 | +9,044 / −8,470 | 1,796 | Bellevue | Wed 18:15 | — |
| 23 | 141.583 | +9,044 / −9,257 | 1,008 | Les Houches | Wed 19:15 | food |
| 24 | 150.772 | +9,322 / −9,509 | 1,035 | Chamonix | Wed 20:45 | hot food, bag, rest, crew |

The crucial detail is not the number of aid stations. It is that **drop bags exist only at the start, Beaufort and the finish**; **rest areas only at Beaufort, Les Contamines, Chalets du Truc and the finish**; and **crew access only at Courmayeur, Bourg-Saint-Maurice, Beaufort, Les Contamines, Chalets du Truc and Chamonix**. If spare shoes, dry clothes or night gear are packed for a “mid-course bag” that does not exist, race day will be unpleasant.

## Elevation profile: six steps

[![TDS 2026 elevation profile through the official 24 timing points: 1,222 m at the start, 2,580 m at Col Chavannes, 831 m at Bourg-Saint-Maurice, 1,035 m at the Chamonix finish; the 721 m trace minimum is not a timing point](/media/routes/tds/tds-elevation-profile.svg)](/media/routes/tds/tds-elevation-profile.svg)

Graphic: redrawn from the 24 timing points in the official 2026 TDS course JSON. The line only connects timing points; it is not a per-metre sample of the full GPX. The official full trace separately gives a 2,589 m high point, which is not the same reading as the 2,580 m Col Chavannes timing point; this page does not mix the two.

Six segments are more useful than one total:

1. **0–20.629 km, start to Col Chavannes:** 1,222 m up to 2,580 m, with +1,904 / −546 m cumulative. Mont-Favre at 2,412 m and Col Chavannes at 2,580 m are consecutive high points with only 439 m of descent between them. This happens at night; “fresh legs at the start” is not a pace plan.
2. **20.629–51.078 km, long descent to Bourg-Saint-Maurice:** 2,580 m down to 831 m, adding only +524 / −2,274 m. After Petit Saint-Bernard at 2,187 m comes one of the longest continuous descents of the race; by Seez at 892 m, the quads have already taken a load most runners did not train for.
3. **51.078–73.750 km, five Beaufortain steps:** from 831 m back up to Passeur de Pralognan at 2,554 m, with +2,269 / −1,442 m, passing Fort de la Platte 1,990 m, Cormet de Roselend 1,971 m, Col de la Sauce 2,306 m and down to La Gittaz 1,657 m. This is not one big climb and one big descent; it is five repetitions, each capable of forcing a walk.
4. **73.750–92.421 km, down to Beaufort:** +969 / −1,888 m, from 1,657 m to 739 m. Beaufort is the only point with bag + rest + hot food + crew, and the 27:10 cut-off makes it the key mid-race gate.
5. **92.421–123.197 km, climbing again:** from 739 m through Hauteluce 1,174 m, Barrage de la Girotte 1,777 m and Le Signal 1,876 m to Les Contamines 1,157 m, with +1,834 / −1,415 m. There is no drop bag here; headlamp, spare batteries and insulation stay with you from Bourg.
6. **123.197–150.772 km, the last 27.6 km:** +1,822 / −1,944 m through Chalets du Truc 1,714 m, Col de Tricot 2,117 m, Bellevue 1,796 m and Les Houches 1,008 m, then back to Chamonix 1,035 m. Col de Tricot is still ahead: “only a marathon left” is not a flat finish.

The six segments add up to the official JSON's **+9,322 / −9,509 m**. That is a cumulative value between 24 timing points, not a full per-point GPX recomputation; the two cannot be mixed or used to “correct” each other.

## The 44:55 arithmetic

Put the 12 intermediate cut-offs and the finish on one clock and a counter-intuitive fact appears: the start is not generous and the finish is not “just survive”. From the 23:50 start, Lac Combal arrives after only 3 hours 40 minutes, at km 16.6 with 1,297 m of climbing already done. Petit Saint-Bernard comes at 8:40, after 36.8 km and 2,397 m of gain.

| Cut-off | Cumulative km | Elapsed | Minimum overall pace | Note |
| --- | ---: | ---: | ---: | --- |
| Lac Combal | 16.565 | 3:40 | 13:16 /km | First hard cut-off |
| Petit Saint-Bernard | 36.847 | 8:40 | 14:07 /km | Last high point before the long descent |
| Bourg-Saint-Maurice | 51.078 | 11:10 | 13:07 /km | First crew access |
| Fort de la Platte | 55.928 | 13:55 | 14:53 /km | First Beaufortain climb |
| Cormet de Roselend | 66.166 | 17:25 | 15:47 /km | Into the evening |
| La Gittaz | 73.750 | 19:40 | 16:00 /km | Around nightfall |
| Beaufort | 92.421 | 27:10 | 17:37 /km | Bag, rest, hot food |
| Hauteluce | 98.733 | 29:40 | 18:01 /km | Early-morning climb |
| Le Signal | 115.478 | 35:25 | 18:22 /km | Second morning |
| Les Contamines | 123.197 | 37:25 | 18:13 /km | Second rest/crew point |
| Bellevue | 137.034 | 42:25 | 18:33 /km | Last pass |
| Les Houches | 141.583 | 43:25 | 18:22 /km | Into the Chamonix valley |
| Chamonix | 150.772 | 44:55 | 17:52 /km | Finish |

This is **elapsed time divided by cumulative distance**, not a segment pace. The steep climbs will be much slower than 13:16 /km and the runnable descents can claw some back. If you are already slower than 13:16 /km at Lac Combal, the rest of the course has to be faster than the table, and TDS descents are not all runnable.

The 2026 men's winner, Rémy Brassac, covered the official 150.772 km trace in 19:28:43, about 7.75 km/h or 7:45 /km. That is more than 25 hours inside the 44:55 limit. For most runners, the job is to arrive at each cut-off with 30–60 minutes of margin, not to plan around the winner's pace.

## Target finish and average pace

The official finish cut-off is **44:55**. Dividing the 150.772 km checkpoint distance by a series of finish times gives the following “moving average” references. They exclude climbing, aid, queues and stops, and are not a race-day execution pace.

| Target finish | Average pace | Average speed |
| --- | ---: | ---: |
| 24:00 | 9:33 /km | 6.28 km/h |
| 28:00 | 11:09 /km | 5.38 km/h |
| 32:00 | 12:44 /km | 4.71 km/h |
| 36:00 | 14:20 /km | 4.19 km/h |
| 40:00 | 15:55 /km | 3.77 km/h |
| 44:55 | 17:52 /km | 3.36 km/h |

These six lines answer only “how fast if the whole race were one speed”. The real TDS speed curve swings widely across the first 20 km of climbing, the long descent after Petit Saint-Bernard, the five Beaufortain repetitions and the final Col de Tricot. Treating 9:33 /km as a pace to hit every kilometre will empty the tank before the first aid station.

## Aid, bags and crew: confirm, do not assume

TDS uses the usual UTMB semi-autonomy model: aid stations provide drinks and food to eat on site, some have hot food, and runners must carry enough water and food to the next point. The current regulation allows one personal assistant at designated TDS aid stations, in a reserved area, with a bag of no more than 30 litres; medical help from crew is heavily restricted. It is not a race where a friend can follow all day.

| Capability | Official location | Practical meaning |
| --- | --- | --- |
| Drop bag | Courmayeur, Beaufort, Chamonix | Only these three; do not pack for a mid-course bag that does not exist |
| Rest | Beaufort, Les Contamines, Chalets du Truc, Chamonix | A rest area is not a bed; keep your own clock |
| Crew | Courmayeur, Bourg-Saint-Maurice, Beaufort, Les Contamines, Chalets du Truc, Chamonix | Designated zones only; no roadside support on the passes |
| Hot food | Beaufort, Chamonix | Only these two are marked hotFood in the official JSON |
| Water | Checrouit, Seez, Lac Combal, Petit Saint-Bernard, Bourg, Cormet, La Gittaz, Hauteluce, Le Signal, Les Contamines, Les Houches, finish | Mostly water/sports drink; carry food for the next leg |

A workable plan:

- **Courmayeur → Lac Combal:** 1.0–1.5 L of water, up to 2 L in heat. No official food before Lac Combal.
- **Lac Combal → Petit Saint-Bernard:** food at Lac Combal, but another 20 km and 1,100 m of climbing to Petit Saint-Bernard. Do not leave with an empty pack.
- **Bourg → Beaufort:** food and crew at Bourg, then 41 km with +3,238 / −5,419 m and no drop bag. Batteries, headlamp and insulation stay with you.
- **Beaufort → Les Contamines:** Beaufort is the only point with bag + rest + hot food + crew. Shoe change, sleep and a hot meal all have to fit inside the 27:10 margin.
- **Les Contamines → Chamonix:** still 27.6 km and +1,822 / −1,944 m, with Col de Tricot at 2,117 m. “Only a marathon left” is not a reason to carry less water.

## Weather: valleys and passes are two systems

Using Open-Meteo's ERA5 archive, filtering 24–26 August for each year from 2015 to 2025 gives 33 daily records per valley station. The table shows daily maximum and minimum ranges with medians, plus days with at least 1 mm and at least 5 mm of precipitation.

| Place | Daily max range / median | Daily min range / median | ≥1 mm | ≥5 mm |
| --- | --- | --- | ---: | ---: |
| Courmayeur (1,222 m start) | 17.1–32.1 °C / 24.4 °C | 6.0–16.8 °C / 10.6 °C | 10 / 33 | 5 / 33 |
| Beaufort (739 m mid-point) | 15.3–34.7 °C / 25.0 °C | 9.0–18.6 °C / 13.4 °C | 10 / 33 | 6 / 33 |
| Chamonix (1,035 m finish) | 12.8–33.5 °C / 23.8 °C | 7.1–18.9 °C / 11.7 °C | 12 / 33 | 5 / 33 |

These are valley figures. The 2,589 m high point will typically be 10–15 °C cooler, and rain plus wind lowers the felt temperature further. The 2026 race reports describe heavy rain at the start and heat later; that “cold then hot” pattern is normal for late August in the Mont Blanc south side. Pack a waterproof shell, an insulating mid-layer, a headlamp and spare batteries; do not dress only for Chamonix town.

## Transport: Courmayeur is not a walk from Chamonix

The start is in Courmayeur, Italy; the finish is in Chamonix, France. The straight-line distance is only about 15 km, but Mont Blanc is in the way. The official transport page is blunt: **do not drive a private car into Courmayeur**; town-centre parking is saturated during the event.

| From | Official suggestion | Approximate distance/time |
| --- | --- | --- |
| Chamonix | Public Flixbus or Arriva bus, both directions | Through the Mont Blanc tunnel, roughly 30–60 min depending on border and timetable |
| Geneva airport (GVA) | Direct Flixbus to Courmayeur | About 115 km |
| Turin airport (TRN) | Train to Aosta, then Arriva bus | About 150 km; Turin–Aosta train under 120 min |
| Milan Malpensa (MXP) | Train to Aosta via Chivasso, then bus | About 212 km; Milan–Aosta about 180 min |

One trap: the official page states that **until 13 December 2026 the Ivrea–Aosta railway is suspended for electrification works and replaced by buses**. TDS is in August, inside that window. A plan that assumes a through train to Aosta will hit a bus transfer at Ivrea. Add that bus time to any Turin or Milan itinerary.

For the return, the official TDS material does not publish a dedicated post-race shuttle. The safe plan is to book Chamonix accommodation and take the bus back to Courmayeur the next day for a car or luggage. “Finish in Chamonix” does not mean “instant transfer back to Courmayeur”.

## Difficulty and risk

RAVIT's third-party timing analysis records 1,285 starters and a 44.4% DNF rate for the 2026 TDS, with 23 timing points and a median dropout at km 66.09. Beaufort accounts for 137 dropouts, Cormet de Roselend 103, Bourg-Saint-Maurice 76, La Gittaz 56, Fort de la Platte 36, Lac Combal 34, Petit-Saint-Bernard 25 and Hauteluce 22. This is third-party data, not an official finish rate, and it does not contradict the official 1,290-result list: the official list counts records, while RAVIT counts starters and dropouts.

The risk is not one especially hard section. It is the combination of four things:

1. **Night start:** 23:50 means the first eight hours are almost entirely in darkness. Headlamp, spare batteries and rain protection are mandatory in practice.
2. **High passes:** Col Chavannes 2,580 m, Passeur de Pralognan 2,554 m, Col de la Sauce 2,306 m and Col de Tricot 2,117 m. Even in summer, 5–10 °C with wind and rain is possible.
3. **Long unsupported stretch:** 41 km from Bourg to Beaufort with no drop bag. Gear has to last.
4. **Late rolling terrain:** after Beaufort there are still 58 km and +3,656 / −3,359 m. It is not a downhill finish.

Drop-outs and evacuation: the current regulation requires runners to leave checkpoints before cut-off and to follow the organisation's instructions when withdrawing. TDS crew access is limited to designated stations; medical care is the official team's job. Beaufort, Les Contamines, Chalets du Truc and Chamonix have rest/crew flags, but a rest area is not a guaranteed vehicle. If you need to withdraw, go to the nearest checkpoint and speak to the station chief; do not leave the marked route to find your own way down.

## 2026 results

The official UTMB Index TDS 2026 page lists 1,290 results, dated 24 August 2026, city Courmayeur. The leading men and women are:

| Men | Time | Women | Time |
| --- | ---: | --- | ---: |
| Rémy Brassac (FRA) | 19:28:43 | Sarah Vieuille (FRA) | 22:08:16 |
| Pierre-Adrien Hivert (FRA) | 20:14:26 | Alice Meignié (FRA) | 22:30:29 |
| Nicolas Court (FRA) | 20:56:52 | Alyssa Clark (USA) | 22:54:19 |

[![The Chamonix valley and Mont Blanc from la Flégère](/media/routes/tds/chamonix-valley-2010.jpg)](/media/routes/tds/chamonix-valley-2010.jpg)

Photo: the Chamonix valley and Mont Blanc from la Flégère, 31 July 2010, Ximonic, Simo Räsänen, CC BY-SA 3.0, shown here as a 960×640 thumbnail. It shows the finish valley's terrain, not the 2026 TDS finish line.

Put the women's winning 22:08:16 against the 44:55 limit and she still had more than 22 hours of margin. That says the cut-offs are not an elite-only filter; they leave room for a long walk/run. What stops most people is the cumulative clock at the earlier checkpoints, not the final line.

## Images and rights

All three photographs are route-environment images, not TDS race photographs, and do not represent race-day weather, snowline, surface or aid-station layout:

- **Courmayeur:** `File:Courmayeur view.jpg`, by Tiia Monto, CC BY-SA 3.0, dated 9 May 2015; original 8,445×3,073, page uses a 960×349 thumbnail. It shows the start town, road and mountain behind it.
- **Cormet de Roselend:** `File:Cormet de Roselend F.jpg`, by Philipendula, CC BY 2.5, Commons upload date 19 October 2005; original 2,560×1,920, page uses a 960×720 thumbnail. It shows the Beaufortain pass's grass, scree and stream.
- **Chamonix valley:** `File:Chamonix valley from la Flégère,2010 07.JPG`, by Ximonic, Simo Räsänen, CC BY-SA 3.0, dated 31 July 2010; original 3,750×2,500, page uses a 960×640 thumbnail. It shows the finish valley and the Mont Blanc massif.

Two original SVGs by RunUp Editorial: `tds-24-checkpoints.svg` (the 24 official timing points in equal-width cards) and `tds-elevation-profile.svg` (the elevation line through those points). They are not official maps, not a full GPX profile and not a navigable trace, and cannot replace the official GPX. The 9 m difference between the highest timing point and the official full-trace high point is stated in the text.

The official race page and social channels publish race photographs, but provide no redistribution licence; the official GPX metadata assigns copyright to LiveTrail® and carries no open licence. This page therefore embeds neither official photographs nor an official course map. It links to the official page and GPX and describes the geometry through the official checkpoint table plus the two original graphics.

## Sources and checks

- Official race page: `https://montblanc.utmb.world/en/races/tds` (stat block, date, start time, 44:55, 2027 notice).
- Official course JSON: the `points` array embedded in the same page (24 timing points, 150.772 km, +9,322 / −9,509 m, services and cut-offs).
- Official GPX: `https://pdf.utmb.world/raw/upload/v1786442970/montblanc/Races/GPX/2026/TDS_2026_098e06c78e.gpx` (LiveTrail copyright, no redistribution licence).
- Official results: `https://utmb.world/utmb-index/races/646.hokautmbmont-blanctds.2026` (1,290 results, podium, 154 km basis).
- Official regulation: `https://montblanc.utmb.world/races-runners/other-information/regulation` (currently the 2027 edition, used as a rule reference).
- Official transport: `https://montblanc.utmb.world/discover/transportation/courmayeur` (Chamonix bus, Geneva/Turin/Milan airports, Ivrea–Aosta bus replacement).
- Historical weather: Open-Meteo ERA5 archive, 24–26 August 2015–2025, Courmayeur / Beaufort / Chamonix.
- Third-party timing: `https://ravit.live/trail/mont-blanc-tds/analyse` (1,285 starters, 44.4% DNF, dropout distribution; third-party context only).
- Photo: `https://commons.wikimedia.org/wiki/File:Courmayeur_view.jpg` (Tiia Monto, CC BY-SA 3.0, 2015-05-09; 960×349 thumbnail).
- Photo: `https://commons.wikimedia.org/wiki/File:Cormet_de_Roselend_F.jpg` (Philipendula, CC BY 2.5, Commons upload date 2005-10-19; 960×720 thumbnail).
- Photo: `https://commons.wikimedia.org/wiki/File:Chamonix_valley_from_la_Fl%C3%A9g%C3%A8re,2010_07.JPG` (Ximonic, Simo Räsänen, CC BY-SA 3.0, 2010-07-31; 960×640 thumbnail).
- Third-party checkpoints: TrailMath's TDS page was used only for cross-checking and is not written into the official table.

Not verified: a separate official 2026 TDS roadbook PDF with per-station cut-offs was not obtained; the cut-offs here come from the official embedded JSON, not a PDF. The 2026 and 2027 rule texts were not compared clause by clause; the 2027 regulation is only a current reference. The organiser has not published a 2026 finish rate; 44.4% is RAVIT's third-party figure.
