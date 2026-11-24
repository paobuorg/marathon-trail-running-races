---
entityId: route:berlin
locale: en
title: "Berlin Marathon: the complete 2026 course guide"
summary: "The 2026 Berlin Marathon in full: a 42.195 km city course, 15 aid stations, a 6:15 time limit with a km 33 cut-off, the 73 m climb and 79 m descent reported by Abbott World Marathon Majors, an official 2025 GPX that is explicitly not treated as 2026 geometry, transport, late-September weather, and one CC-licensed race photograph."
aliases: ["Berlin Marathon", "BMW Berlin Marathon", "Generali Berlin Marathon", "Berlin city marathon", "42.195 km city course"]
authors:
  - runmap-editorial
reviewers:
  - runmap-editorial
translationStatus: reviewed
---

## Check status

- Version: `2026-berlin-official-course`, covering the 52nd BMW BERLIN-MARATHON held on 27 September 2026. From 2027 the race becomes the GENERALI BERLIN-MARATHON, with its first edition on 26 September 2027.
- Checked on 2026-11-21. The prose facts were first checked on 2026-11-06 and the geometry file was rechecked on 2026-11-21; every figure below carries its source basis, and where official pages disagree the figures are shown side by side rather than averaged or smoothed.
- Course geometry: **official 2025 GPX link, not 2026 geometry**. SCC's official domain still serves `BM25_Marathon-Strecke.gpx` (HEAD 200, 24,110 bytes, 508 trackpoints, zero elevation values); the current 2026/2027 course page has no 2026 GPX. The file's planar distance is 42.1836 km, 11.4 m short of 42.195 km. This page links it only: it does not draw it, navigate from it or bundle it. The globe anchor remains an editorial Brandenburg Gate overview, not an official start, finish or course coordinate.
- This page has not been run on the ground, so it offers no first-hand testing claims. Verified and unverified material is kept separate.
- Course-change check: no past-edition handbook was obtained, so the course-change history is unverified. This page has no official evidence of a reroute, date change or rule change that qualifies for the log; `courseChanges` is an empty array and is not presented as "no changes".

## What this course is

The Berlin Marathon starts on Straße des 17. Juni in the Tiergarten, between the Brandenburg Gate and the "Kleiner Stern"; the finish is behind the Brandenburg Gate. Start and finish sit in the same central area, so there is no cross-city transfer after the race, but the 42.195 km route crosses several Berlin districts before returning to the centre.

The organiser's course page calls the route the flattest of the Abbott World Marathon Majors: 42.195 km, very little elevation gain, passing Berlin's main sights, with 15 aid stations along the course. The official runners' course map is numbered 1 to 42 and names landmarks and districts along the way, including the Siegessäule, the Federal Chancellery, Berlin Cathedral, the TV Tower, the Konzerthaus am Gendarmenmarkt, Südstern, Schöneberg Town Hall, the Kaiser Wilhelm Memorial Church and Potsdamer Platz, as well as the districts of Mitte, Moabit, Tiergarten, Charlottenburg, Steglitz, Wilmersdorf, Schöneberg, Kreuzberg and Neukölln. The map also marks Reichstag, Großer Stern, Ernst-Reuter-Platz, Zoologischer Garten, Olivaer Platz, Turmstraße, Rosenthaler Platz, Alexanderplatz, Strausberger Platz, Moritzplatz, Kottbusser Tor, Hermannplatz, Hasenheide, Mehringdamm, Platz der Luftbrücke, Kleistpark, Innsbrucker Platz, Breitenbachplatz, Roseneck Platz, Fehrbelliner Platz, Wittenberg Platz, Nollendorfplatz and Potsdamer Platz.

This is a road marathon, not a trail race: the official map shows city streets, squares and parks rather than mountain paths or trail sections, and no usable official elevation figures were obtained. The 2026 runners started from 8:45 am in six waves; handbikers went at 8:20, elite wheelchair athletes at 8:26, and the remaining handbike and wheelchair athletes at 8:29. The 2026 men's winner was Guye Adola in 2:02:50; the women's winner was Tigst Assefa in 2:11:04, taking 49 seconds off her own 2:11:53 course record from 2023. From 1 October 2026 Generali becomes title partner, and the 2027 race moves to 26 September; whether the 2027 course is identical to 2026 must be checked against that edition's official map.

## Official figures

| Basis | Distance | Gain | Loss |
|---|---|---|---|
| SCC Events course page (2026/2027) | 42.195 km | not published ("Elevation tba") | not published |
| Official runners' course map PDF | 42.195 km (map numbered 1–42) | not published (no figures given) | not published |
| 2026 event homepage | 42.195 km | not published | not published |
| Abbott World Marathon Majors official magazine | 42.195 km | about 73 m | about 79 m |

The table shows who said what; it does not combine four figures into one. Distance has a single official figure: 42.195 km, recorded on the SCC Events course page and the 2026 event homepage, with the course map using numbered points 1–42 for the 42 kilometre sections. Gain and loss have a numeric figure only in the Abbott World Marathon Majors official magazine: about 73 m of climbing and 79 m of descent. SCC Events' own course page lists elevation as "tba" and publishes no climb figure. The two are not contradictory: one publisher withholds the number, the other gives 73/79.

The card at the top of this page uses 73 m of gain, and the entity record labels it as the Majors figure rather than an SCC Events figure. Dividing 73 m by 42.195 km gives about 1.7 m of climbing per kilometre; 73 m of gain against 79 m of loss implies roughly 6 m of net descent from start to finish. Both are this site's arithmetic on official totals, not new official numbers.

## Official 2025 GPX check (not 2026 geometry)

On the 2026-11-21 check, the current 2026/2027 course page still had no GPX link. SCC's official domain, however, still serves a 2025 file: `BM25_Marathon-Strecke.gpx`. A HEAD request returned HTTP 200, `application/octet-stream`, 24,110 bytes. The file is GPX 1.1, creator `SCC KML/KMZ/GPX Tools`; it contains 508 trkpt elements, 0 wpt, 0 ele, and no track name, description or timestamp.

| Item | Official 2025 GPX | 2026 official course |
|---|---|---|
| File | `BM25_Marathon-Strecke.gpx` | 2026 course-map PDF / interactive map |
| Edition | filename says 2025, not 2026 | 52nd edition, 2026 |
| Trackpoints | 508 trkpt | no point file published |
| Elevation | 0 ele | 73 m gain / 79 m loss (Majors basis) |
| Planar distance | 42.1836 km | 42.195 km |
| Difference from official | 0.0114 km short (11.4 m) | — |
| Start / finish | 52.515214N, 13.360200E / 52.516013N, 13.372547E | official start/finish area, no point coordinates |
| Rights | no copyright line, no redistribution licence | PDF and graphics not redistributable |

Summing the 508 points with haversine gives 42.1836 km, 11.4 m (0.027%) short of 42.195 km. The gap comes from trackpoint sampling and simplification, not from an official statement that the course is short; this page does not change the official distance. The bounding box is 52.467576–52.529712 N and 13.281231–13.428996 E; the first and last points sit in the start/finish area on either side of the Brandenburg Gate, but the file has not been checked kilometre by kilometre against the 2026 official map.

**It cannot serve as 2026 geometry**: the filename says BM25, the file has no date or track name, and there is no evidence that the 2026 course is metre-for-metre identical. It also has no elevation values, so it cannot yield climb, descent or high point. This page therefore sets `officialGeometryUrl` to the official 2025 file and `geometryAccess=official-link`, but does not describe it as the 2026 track, draw it, navigate from it or bundle it. The 2026 figures remain 42.195 km, 73 m gain and 79 m descent on their separate bases.

## Segments

| Segment | From → to | Distance | Gain / loss |
|---|---|---:|---:|
| 1 | Start → 5 km | 5.000 km | not published / not published |
| 2 | 5 km → 10 km | 5.000 km | not published / not published |
| 3 | 10 km → 20 km | 10.000 km | not published / not published |
| 4 | 20 km → halfway | 1.0975 km | not published / not published |
| 5 | Halfway → 25 km | 3.9025 km | not published / not published |
| 6 | 25 km → 30 km | 5.000 km | not published / not published |
| 7 | 30 km → 35 km | 5.000 km | not published / not published |
| 8 | 35 km → 40 km | 5.000 km | not published / not published |
| 9 | 40 km → finish | 2.195 km | not published / not published |

The timing points come from the 2026 official timing as listed in the World Athletics race report: 5 km, 10 km, 20 km, halfway, 25 km, 30 km, 35 km, 40 km and the finish. Segment distances are the differences between adjacent official timing points; the nine segments add up to 42.195 km. The official pages publish no gain or loss for individual segments, so the column says "not published" throughout. This page does not divide the 73/79 totals across the segments and does not guess gradients from the map.

The 2026 women's splits show what those timing points mean in practice: Assefa reached 5 km in 15:30, 10 km in 30:48, 20 km in 1:01:34, halfway in 1:04:57, 25 km in 1:17:00, 30 km in 1:32:15, 35 km in 1:47:32 and 40 km in 2:03:00 before finishing in 2:11:04. The men's winner Adola reached 10 km in 28:58, halfway in 1:01:01 and 30 km in 1:26:57 before finishing in 2:02:50. The official map places the Siegessäule, Federal Chancellery, Berlin Cathedral, TV Tower, Konzerthaus am Gendarmenmarkt, Südstern, Schöneberg Town Hall, Kaiser Wilhelm Memorial Church and Potsdamer Platz on the course, but its extracted text does not give a metre-by-metre landmark sequence; this page does not force a landmark onto a particular kilometre, and it does not reverse-engineer gradients from elite pace.

## Aid stations and cut-offs

| Place | Distance · elevation · cumulative gain | Services / cut-off |
|---|---|---|
| km 5 | 5.0 km · not published · not published | water (cups) |
| km 9 | 9.0 km · not published · not published | water, fruit, tea, Maurten Drink Mix 160 |
| km 12 | 12.0 km · not published · not published | water (cups) |
| km 15 | 15.0 km · not published · not published | water, fruit, tea, Maurten Drink Mix 160 |
| km 17.5 | 17.5 km · not published · not published | water (cups) |
| km 20 | 20.0 km · not published · not published | water, fruit, tea, Maurten Drink Mix 160 |
| km 22.5 | 22.5 km · not published · not published | water (cups) |
| km 25 | 25.0 km · not published · not published | water, fruit, tea, Maurten Drink Mix 160 |
| km 27.5 | 27.5 km · not published · not published | water, Maurten Gel 100 |
| km 30 | 30.0 km · not published · not published | water, fruit, tea, Maurten Drink Mix 160 |
| km 32.5 | 32.5 km · not published · not published | water (cups) |
| km 34.5 | 34.5 km · not published · not published | water (cups) |
| km 36 | 36.0 km · not published · not published | water, fruit, tea, Maurten Drink Mix 160 |
| km 38 | 38.0 km · not published · not published | water (cups) |
| km 40 | 40.0 km · not published · not published | water (cups) |
| km 33 cut-off | 33.0 km · not published · not published | cut-off 3:40 pm (2026) / 3:50 pm (2027); not an aid station |
| Finish | 42.195 km · not published · not published | finish refreshments, medal, massage; finish closes 5:00 pm (2026) / 5:15 pm (2027) |

The table follows the official refreshment list point by point. Nine water points are at 5, 12, 17.5, 22.5, 27.5, 32.5, 34.5, 38 and 40 km. Six points serving water, fruit, tea and Maurten Drink Mix 160 are at 9, 15, 20, 25, 30 and 36 km. Maurten Gel 100 is available at 27.5 km. The course page says there are 15 aid stations, which is the nine water points plus the six full refreshment points; 27.5 km is not counted twice.

Cut-offs must be read by edition. The 2026 race briefing (Status: July 2026) and the 2027 race-day page give two separate sets. For 2026: time limit 6:15 hours; km 33 cut-off at 3:40 pm; official finish time 5:00 pm, after which no one may cross the line. For 2027: km 33 cut-off at 3:50 pm and finish at 5:15 pm. The 2026 figures have now been checked against the 2026 briefing rather than the replaced page record. A 2026 runner must plan for 3:40 and 5:00; a 2027 runner must use that edition's page. Do not carry the 2027 3:50 cut-off into a 2026 plan.

Other official details: all drinks are served in cups; every aid station has a refill point, and runners can refill bottles, belts or vests at the last water table; the 2026 race briefing permits hydration systems with a maximum total volume of 3 litres and says toilets are provided at the end of each refreshment station. Own refreshments can be delivered to 5, 9, 15, 20, 25, 30, 36 and 40 km, in non-glass containers labelled with name, bib number and refreshment point. There are three official drop-off times: the course page says 07:00–07:45, the race-day page says by 07:45, and the race briefing says 06:30–07:30, all at Annemarie-Renger-Str. / Otto-von-Bismarck-Allee outside the fenced area. The 2026 race-day page also says massage stations run from km 25 every 5 km, with free massage at the finish.

![The Brandenburg Gate at the 2022 Berlin Marathon finish](/media/routes/berlin/brandenburg-finish-2022.jpg)

## Surface and terrain

The official pages fetched here publish no distributable surface breakdown, and this page invents no percentages such as "asphalt versus stone". What can be confirmed is that the official course map follows city streets, squares and parks, making this a road course; the organiser calls it the flattest of the Abbott World Marathon Majors, with very little elevation gain. The Abbott World Marathon Majors official magazine adds two terrain facts: about 73 m of climbing and 79 m of descent across the route, and long straight sections with relatively few sharp changes of direction. Those facts explain why the course suits even pacing, but they do not mean there are no turns or no surface changes.

The course page gives elevation as "tba", and this page did not obtain usable official elevation figures or profile data. The runners' PDF's extracted text gives kilometre numbers, landmarks, street names and aid points but no elevation figures. This page therefore does not treat any third-party profile as official geometry and does not state a "high point" in metres. The only height figures that can be confirmed are the Majors totals of about 73 m up and 79 m down, plus the roughly 6 m net descent obtained by subtracting them.

The surface warning remains unverified: the 2026 race briefing does not mention tram tracks at km 8 or km 38. The earlier race-day page record did, but it rolled over to the 2027 edition. This page therefore does not repeat the tram warning and does not infer a surface breakdown from it.

## Risks and escape points

- **Time limits.** The 2026 limit is 6:15, with km 33 closing at 3:40 pm and the finish at 5:00 pm, now checked against the 2026 race briefing. Anyone outside those times must leave the course and is taken to the finish in the sweep bus, and the organiser states that continuing is not permitted. The 2027 figures are 3:50 pm and 5:15 pm and must not be mixed with 2026.
- **The official pages publish no mid-course escape list.** The official race-day page describes the sweep bus but did not list aid stations with buses or a set of official withdrawal points, as a trail race might. The U-Bahn and S-Bahn stops listed by the organiser are for the start and finish area; they are not a mid-course evacuation plan.
- **Medical staff can end your race.** The entry page says the medical team and paramedics are authorised and obliged to remove runners who are injured or overexerting. Medical teams, cycle doctors, medical aid organisations and Berlin Fire Brigade patrols are listed on the course and in the start/finish area; this is the official medical setup, not a promise of a fixed medical station at every point.
- **Weather does not cancel the race by itself.** The official page says the race takes place regardless of weather unless the German Weather Service issues a warning; schedule and course may still change. Heat, cold, rain and wind are therefore race-day conditions the runner must prepare for.
- **Heat has precedent.** The Abbott World Marathon Majors official magazine says the previous year's race took place in unseasonably warm conditions and that organisers are encouraging runners to carry their own bottles rather than rely only on the 15 refreshment stations. That is the organiser's public statement, not this site's measurement of 27 September 2026.
- **The course can change.** The race-day page states "Schedule and course are subject to change"; this page pins the 2026 version and does not promise that 2027 will match it metre by metre.
- **Wheeled athletes.** The 2026 race briefing says wheelchair athletes and handbikers are directed to their starting positions from 8 am and that helmets are mandatory. Access to the start/finish area is limited to people with a bib and athlete wristband. The earlier page's km 8/km 38 tram warning is not repeated in the 2026 briefing and is therefore not repeated here. Road runners should not treat those arrangements as their own escape plan.

## Getting there

**Airport.** Berlin Brandenburg Airport (BER) has its railway station directly under Terminal 1 on level U2. The Airport Express (FEX) links Berlin Hauptbahnhof, Potsdamer Platz, Südkreuz and BER every 15 minutes from 4 a.m. to 1 a.m.; the journey is about 23 minutes from Hauptbahnhof, 19 minutes from Potsdamer Platz and 14 minutes from Südkreuz. Regional trains RE20, RB22, RB24 and RB32 also serve BER; S-Bahn lines S9 and S85 run every 20 minutes; express bus X7 runs every 5–10 minutes from U Rudow. All of this comes from BER Airport's official public-transport page.

**Rail.** The organiser lists S-Bahn stops at Brandenburger Tor, Berlin Hauptbahnhof and Potsdamer Platz, and regional trains at Hauptbahnhof and Potsdamer Platz. From BER, take the FEX or a regional train to Hauptbahnhof / Potsdamer Platz, then change to S-Bahn or walk into the start/finish area. The organiser asks runners to use public transport and does not encourage driving.

**Local movement.** Near the start and finish, the U-Bahn stops are Unter den Linden, Bundestag, Brandenburger Tor and Potsdamer Platz; the S-Bahn stops are Brandenburger Tor, Hauptbahnhof and Potsdamer Platz. There are two runner entrances: Platz der Republik, opposite the Reichstag, for all runners; and Bremer Weg, only for runners with a purple bib, a poncho symbol and no place in block K. The 2026 race briefing lists start-block admission at 7:00 for A/B/C, 7:30 for D/E, 8:00 for F/G, 8:30 for H/J and 9:00 for K.

**Bib as ticket.** The 2026 race briefing says the bib number is valid as a ticket in fare zones A, B and C from midnight on 24 September to 3 am on 28 September 2026; the 2027 page says 23–26 September. Use the start card or briefing for your own edition. The entry fee includes a 4-day ABC public transport pass. The earlier 24–27 September record came from a replaced page and is no longer treated as a 2026 conclusion.

**Expo.** The 2026 expo is at Tempelhof Airport, Platz der Luftbrücke 5, reached by U6 to Platz der Luftbrücke plus about a 10-minute walk, or by bus M43 / 248. The organiser explicitly says there is no parking at the expo and asks visitors to use public transport.

**Driving.** The organiser asks runners to use public transport; entry to the start/finish area is limited to participants with a bib and wristband. Accessible parking is limited to vehicles with an official special permit, on Altonaer Str. in the direction from Großer Stern toward Hansaplatz. Leaving the car at accommodation and taking the U-Bahn or S-Bahn is the arrangement official guidance points to.

## Late-September season and weather

The 2026 race was held on 27 September; the 2027 race moves to 26 September. To look at the same week, this page queried Open-Meteo's historical reanalysis for the Berlin grid point 52.5483 N / 13.4078 E over 20–28 September 2026, nine days in total:

- Daily maximum: 15.3 °C to 24.6 °C, median 19.2 °C.
- Daily minimum: 6.3 °C to 13.0 °C, median 11.2 °C.
- Four of the nine days had at least 1 mm of precipitation; none had at least 5 mm.
- On 27 September itself: maximum 22.9 °C, minimum 12.0 °C, precipitation 0.0 mm.

These are **modelled reanalysis values for a grid point, not measurements on the course**, and not a forecast for 2027. Different Berlin streets, tree cover and bridges will feel different; a late-September morning can be 6–13 °C while midday can exceed 20 °C, so warm layers are needed before the start and after the finish. The 2026 race-day page adds the official rule that the race goes ahead unless the German Weather Service issues a warning, so "bad weather" is not a reason to plan for a cancellation; prepare for the forecast of your edition.

## Difficulty

The official documents publish no single "difficulty grade", and this page does not invent one. **This site's rating**: a low-climb, fast road course, on these verifiable dimensions:

- 42.195 km, the only official distance figure.
- About 73 m of gain and 79 m of loss on the Abbott World Marathon Majors basis, roughly 1.7 m of climbing per kilometre and about 6 m of net descent.
- 6:15 time limit; in 2026 km 33 closes at 3:40 pm and the finish at 5:00 pm, while 2027 uses 3:50 pm and 5:15 pm.
- 15 aid stations, about 1.5–4 km apart on the official point list, with Maurten Gel 100 at 27.5 km.
- City streets, long straights and relatively few sharp turns; no official surface percentages.

On the official figures, this is a course with little climbing and long straight sections; even so, 42.195 km, late-September temperature swings, six start waves of crowded running and a 6:15 limit still need preparation matched to the individual. That judgement comes from official figures and rules, not from personal experience, and it is not an official rating.

## Verified and unverified

This page has not been run on the ground, so the two are kept strictly apart.

**Verified from official sources**: the 52nd edition on 27 September 2026; the start on Straße des 17. Juni and finish behind the Brandenburg Gate; 42.195 km; the 15 aid stations and their services; the 6:15 limit, km 33 cut-off and finish closure (both 2026 and 2027 versions); the bib-as-ticket windows; start/finish transport stops and runner entrances; the expo location and access; the 2027 lottery, 215 euro fee, eligibility and qualifying times; the 2026 winners and splits; the 73 m / 79 m Majors figures; the 20–28 September 2026 grid-point weather statistics; BER Airport's FEX, S-Bahn and express-bus information; and the SCC official 2025 GPX's HTTP 200, 24,110 bytes, 508 trackpoints, zero elevation values and 42.1836 km planar distance (a 2025 file, not 2026 geometry).

**Unverified — no conclusions drawn here**: elevation and cumulative gain at each aid station; the proportion of asphalt, stone and track; actual queue times at aid stations on race day; whether the 2027 course is identical metre by metre to 2026; the exact mapping between the official map's numbered points and each kilometre; whether the 2025 GPX points match the 2026 official map section by section; mobile coverage, toilet queues and crowd density on the course; and the real waiting time for the sweep bus after km 33. Only the organiser's current notices or runners on the ground can confirm those, and this page does not present desk research as measurement.

## Images and rights

**One photograph, recorded from Wikimedia Commons at capture time.**

The Brandenburg Gate at the 2022 Berlin Marathon finish; author: Lear 21; licence: CC BY-SA 4.0; date: 2022-09-25 (verified against the Commons file page and API on 2026-11-20). The image shows runners passing the Brandenburg Gate; the file description names the 2022 Berlin Marathon finish, and the gate stands near km 42.

Channels at the time of image capture on 2026-11-06: the Wikimedia Commons `action=query&generator=search` API, `Special:MediaSearch`, `commons.wikimedia.org/w/index.php?search=` and direct `upload.wikimedia.org` URLs were all reachable. The filter is still three checks: readable licence, file page proving this event, and image matching the caption. Anything failing one is not used. Organiser photographs carry no redistributable CC licence and were not used. 

The file is unmodified apart from size and weight compression, and is not covered by this page's CC BY 4.0.

## Sources and reuse

This page was written independently by the RunUp editorial team from SCC Events' public pages, the official course-map PDF, the official 2025 GPX, the 2026 race briefing, the entry page, the results page, the Abbott World Marathon Majors official magazine, the World Athletics race report, Open-Meteo data and BER Airport's official public-transport page. The text is licensed CC BY 4.0.

The page cites 14 factual sources plus one editorial map-anchor source: the course page, the official runners' course-map PDF, the official 2025 GPX file, the 2026 race-day page, the 2027 race-day page, the 2026 race-briefing PDF, the 2027 entry page, the 2026 event homepage, the results page, the Abbott World Marathon Majors magazine, the World Athletics report, Open-Meteo historical weather, the BER Airport public-transport page, `photo-berlin-finish-2022` (the 2022 finish photograph), and `route-anchor-editorial`, which records that the map anchor is an editorial overview only. Each source's supported claims and access date appear in the source list at the bottom of the page.

Event names, official marks, official route text, the official course-map PDF and official results remain the property of SCC Events and the respective rights holders. This page links to official files and does not redistribute the PDF or any course geometry. The 2026-11-21 check found an official 2025 GPX but no redistribution licence; this page links it only, does not bundle or redraw it, and does not treat it as 2026 geometry. Text in the Abbott World Marathon Majors magazine and the World Athletics report remains with those rights holders and is cited for facts only. Open-Meteo data are used under CC BY 4.0 with attribution. The results list is protected by copyright and may be used only for private informational purposes; this page does not reproduce the full results table. Each image's author and licence are stated with its caption; they are not covered by this page's CC BY 4.0; check the Commons file page before reuse, and it is not covered by this page's CC BY 4.0.
