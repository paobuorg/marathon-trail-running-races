---
entityId: route:chicago
locale: en
title: "Chicago Marathon: the 2026 official course in full"
summary: "A full route dossier for the 2026 Bank of America Chicago Marathon: the 26.2-mile city loop, 29 neighbourhoods, 20 official aid stations with mileages, 22 medical locations, a 6:30 cut-off, transport, October weather and escape options, all with official sourcing and a review date."
aliases: ["Chicago Marathon", "Bank of America Chicago Marathon", "Chicago full marathon"]
authors:
  - runmap-editorial
reviewers:
  - runmap-editorial
translationStatus: reviewed
---

## Check status

- Version: `2026-chicago-official-course`, covering the 48th Bank of America Chicago Marathon on Sunday 11 October 2026.
- Review date: 2026-11-06. Every figure below is tied to an official source; where an official page publishes nothing, the cell says "not published". This page does not fill gaps with third-party tracks, marketing language or another year's data.
- Course geometry: **no usable geometry**. The organiser publishes a 2026 course-map PDF but no public, redistributable GPX/KML/GeoJSON. This page does not draw a track or bundle a file; the map shows an editorial overview anchor only. The official map URL is in the source list at the end of the page, and the legend is in section 6.
- The editors have not run this course, so nothing here is described as a first-hand test. Verified and unverified items are separated in section 11.

## What this course is

The Chicago Marathon starts and finishes in Grant Park. The 2026 48th running had more than 54,000 participants; the organiser says the course travels through 29 neighbourhoods, with 1.7 million spectators and 10,000 volunteers along the way. The course page calls it a flat and fast course and says the route has produced seven world records. Those are the organiser's public statements, not a measurement made by this page.

The official 2026 "Anticipated course street closures and openings" table allows a rough reconstruction of the direction: the start is in Grant Park, then Columbus Dr north to Grand Ave, before the Loop sections on Dearborn, Jackson and LaSalle; then Stockton, Fullerton and Cannon lead to the lakefront and North Side, before Sheridan, Inner Lake Shore Dr, Broadway, Clark and Wells bring the course back through downtown; Adams and Jackson then run west, with Damen, Halsted, Taylor, Loomis and 18th St leading into the South Side; Canalport, Cermak, Wentworth, 26th St and Michigan Ave run north, before Roosevelt Rd returns to the finish on Columbus Dr. That order comes from the official street-closure table, not from a third-party track and not from a line drawn by this page.

A same-place start and finish simplifies accommodation, gear check and post-race movement, but the route is a city loop through many neighbourhoods rather than laps of one park. The first half is in the Loop and on the North Side; the second half is on the West and South Sides. Wind, shade, crowd density and road detail change by block. The organiser publishes no per-segment elevation or surface percentages, so this page does not claim which kilometre is steepest or what share of the route is asphalt.

## Official figures

| Source | Distance | Ascent | Descent |
|---|---|---|---|
| Event course page (2026) | 26.2 mi (official wording; 42.195 km is the standard equivalent) | Not published | Not published |
| 2026 participant guide (official PDF) | 26.2 mi | Not published | Not published |
| 2026 official course map (PDF) | Not published (the map carries mile and kilometre markers only) | Not published | Not published |
| 2026 official results page | Not published (the page does not restate the distance) | Not published | Not published |
| World Athletics 2026 race report | Not published (the report does not restate the distance) | Not published | Not published |

None of the five official artefacts gives a cumulative ascent or descent. The entity therefore keeps `elevationGainMeters` as `null` and `elevationMethod` as `null`. The course page uses 26.2 miles; the 42.195 km value in the entity is only the standard metric equivalent, not a second official measurement. Likewise, the course page calls the route flat and fast, but "flat" is not an ascent figure, so this page does not turn marketing language into metres.

The 2026 results page provides a results entry point but does not restate the distance; the World Athletics report also calls the event a marathon without giving 42.195 km or an ascent. Listing these pages side by side shows that the distance wording is consistent and the elevation column is missing, rather than manufacturing four different numbers. If the organiser later publishes an elevation profile or a climb file, that should become a separate source and be added alongside these rows, not used to overwrite them.

One more check: the official press release already gives 10 October 2027 as the next race date, but this page cites only the 2026 participant guide, course map and results pages, so 2027 dates, start times or hotel information are not mixed into the 2026 figures; the 2027 date in section 9 is a published future date, not this page's course version.

## Segments

Official timing checkpoints sit at the start line, every 5K, the halfway point at 13.1 miles, miles 20 to 25, mile 25.2 and the finish line. The table below cuts the course at those official points. "Segment distance" is obtained by subtracting adjacent official checkpoint distances (the 13.1-mile halfway point is converted at 1 mi = 1.609344 km, and the finish uses the standard 42.195 km marathon distance); ascent and descent are not published, so the whole column says "not published".

| Segment | Interval | Segment distance | Segment ascent / descent |
|---|---|---:|---:|
| 1 | Start → 5K | 5.0 km | Not published / not published |
| 2 | 5K → 10K | 5.0 km | Not published / not published |
| 3 | 10K → 15K | 5.0 km | Not published / not published |
| 4 | 15K → 20K | 5.0 km | Not published / not published |
| 5 | 20K → halfway 13.1 mi | 1.0824 km | Not published / not published |
| 6 | Halfway → 25K | 3.9176 km | Not published / not published |
| 7 | 25K → 30K | 5.0 km | Not published / not published |
| 8 | 30K → 35K | 5.0 km | Not published / not published |
| 9 | 35K → 40K | 5.0 km | Not published / not published |
| 10 | 40K → finish 26.2 mi | 2.195 km | Not published / not published |

Segment notes (the locations come from the official aid-station table and the street-closure table, not from a test run):

- **Start → 5K**: from the north end of Grant Park, the course uses Columbus, Grand, Dearborn, Jackson and LaSalle to enter the Loop, then LaSalle north. Official aid station 1 is at 1.6 miles (Dearborn St between Washington and Monroe), station 2 at 3.25 miles (LaSalle St between Ohio and Huron), and station 3 at 5.05 miles (Stockton Ave north of LaSalle St). This section separates the downtown high-rise blocks from the start crowd, and the early turns and spectators can pull the pace too fast.
- **5K → 10K**: Stockton, Fullerton and Cannon lead to the lakefront and North Side, then Sheridan. Official station 4 is at 5.75 miles (Cannon Ave north of Fullerton Pkwy), station 5 at 7.3 miles (Inner Lake Shore Dr between Cornelia and Addison), station 6 at 8.8 miles (Broadway between Aldine and Belmont), and station 7 at 10.1 miles (Clark St between Belden and Webster). Lakefront wind and continuous neighbourhood blocks begin here, with aid roughly every 1.3 to 1.6 miles.
- **10K → 15K**: Sheridan, Broadway, Clark and Wells return the course to the west side of the Loop. Official station 8 is at 11.5 miles (Wells St between North and Burton), station 9 at 12.6 miles (Wells St between Grand and Hubbard), station 10 at 13.6 miles (Adams St between Canal and Desplaines), and station 11 at 14.6 miles (Adams St between Racine and Throop). This is the North Side turn-back into downtown, where crowd density rises again.
- **15K → 20K**: Adams and Jackson run west through Damen and Halsted into the West Side. Official station 12 is at 15.7 miles (Jackson Blvd between Damen and Ogden), station 13 at 16.9 miles (Jackson Blvd between Sangamon and Green), station 14 at 18 miles (Taylor St between Racine and Loomis), and station 15 at 19.2 miles (18th St between Blue Island and Throop). This is the middle of the race; the surface is still city street, and the organiser publishes no gradient data.
- **20K → halfway**: Canalport and Cermak lead into the South Side and the Chinatown area. Official station 16 is at 20.2 miles (Canalport Ave between Halsted and Cermak), and the halfway checkpoint is at 13.1 miles. A Culligan refill point precedes station 16, and stations 16 to 18 offer bananas.
- **Halfway → 25K**: Wentworth, 26th St and Michigan Ave run north. Official station 17 is at 22.3 miles (Michigan Ave between 26th and 28th), station 18 at 23.04 miles (Michigan Ave between 33rd and 35th), station 19 at 24.5 miles (Michigan Ave between 26th and 25th), and station 20 at 25.2 miles (Michigan Ave between 18th and 16th). This is a long South Side sequence before the return to downtown.
- **25K → 30K**: after halfway the course continues on Michigan Ave and around 31st and 35th. The 25K checkpoint is near 15.5 miles and 30K near 18.6 miles; aid stations 13, 14 and 15 fall at 16.9, 18 and 19.2 miles, so station 15 sits just after 30K.
- **30K → 35K**: 31st, Indiana and Michigan continue north. Station 15 is at 19.2 miles, station 16 at 20.2 miles and station 17 at 22.3 miles; the 35K checkpoint is near 21.7 miles. This section crosses the usual late-race rough patch, but the organiser publishes no gradient or surface change there.
- **35K → 40K**: Michigan, 26th and 31st continue north. Station 17 is at 22.3 miles, station 18 at 23.04 miles and station 19 at 24.5 miles; the 40K checkpoint is near 24.8 miles. Stations 18 to 20 all sit on the Michigan Avenue corridor, where spectators and volunteers are dense.
- **40K → finish**: the final 2.195 km uses Michigan, Roosevelt and Columbus to return to Grant Park. Station 20 is at 25.2 miles and the finish at 26.2 miles. The official schedule expects Michigan Ave at mile 26 to reopen at 4:30 p.m. and Roosevelt Rd at 6:00 p.m.; the reopening time for the Columbus Dr finish stretch is not published.

## Aid stations and cut-offs

The organiser publishes 20 aid stations approximately one to two miles apart. In order, each station provides a medical tent with access to a runner-transport vehicle, standard and ADA portable toilets, Gatorade Endurance Formula (lemon-lime), a public-address announcer and water.

| Location | Distance · elevation · cumulative ascent | Services / cut-off |
|---|---|---|
| 1 · Dearborn St between Washington and Monroe | 1.6 mi · elevation not published · cumulative ascent not published | G/W; medical, toilets, runner transport; no station cut-off |
| 2 · LaSalle St between Ohio and Huron | 3.25 mi · elevation not published · cumulative ascent not published | G/W; medical, toilets, runner transport; no station cut-off |
| 3 · Stockton Ave north of LaSalle St | 5.05 mi · elevation not published · cumulative ascent not published | G/W; medical, toilets, runner transport; no station cut-off |
| 4 · Cannon Ave north of Fullerton Pkwy | 5.75 mi · elevation not published · cumulative ascent not published | G/W; medical, toilets, runner transport; Culligan refill; no station cut-off |
| 5 · Inner Lake Shore Dr between Cornelia and Addison | 7.3 mi · elevation not published · cumulative ascent not published | G/W; medical, toilets, runner transport; no station cut-off |
| 6 · Broadway between Aldine and Belmont | 8.8 mi · elevation not published · cumulative ascent not published | G/W; medical, toilets, runner transport; no station cut-off |
| 7 · Clark St between Belden and Webster | 10.1 mi · elevation not published · cumulative ascent not published | G/W; medical, toilets, runner transport; Culligan refill; no station cut-off |
| 8 · Wells St between North and Burton | 11.5 mi · elevation not published · cumulative ascent not published | G/W; medical, toilets, runner transport; no station cut-off |
| 9 · Wells St between Grand and Hubbard | 12.6 mi · elevation not published · cumulative ascent not published | G/W; medical, toilets, runner transport; Maurten Gel 100; no station cut-off |
| 10 · Adams St between Canal and Desplaines | 13.6 mi · elevation not published · cumulative ascent not published | G/W; medical, toilets, runner transport; no station cut-off |
| 11 · Adams St between Racine and Throop | 14.6 mi · elevation not published · cumulative ascent not published | G/W; medical, toilets, runner transport; no station cut-off |
| 12 · Jackson Blvd between Damen and Ogden | 15.7 mi · elevation not published · cumulative ascent not published | G/W; medical, toilets, runner transport; Culligan refill; no station cut-off |
| 13 · Jackson Blvd between Sangamon and Green | 16.9 mi · elevation not published · cumulative ascent not published | G/W; medical, toilets, runner transport; no station cut-off |
| 14 · Taylor St between Racine and Loomis | 18 mi · elevation not published · cumulative ascent not published | G/W; medical, toilets, runner transport; Maurten Gel 100; no station cut-off |
| 15 · 18th St between Blue Island and Throop | 19.2 mi · elevation not published · cumulative ascent not published | G/W; medical, toilets, runner transport; no station cut-off |
| 16 · Canalport Ave between Halsted and Cermak | 20.2 mi · elevation not published · cumulative ascent not published | G/W; medical, toilets, runner transport; Culligan refill; banana; no station cut-off |
| 17 · Michigan Ave between 26th and 28th | 22.3 mi · elevation not published · cumulative ascent not published | G/W; medical, toilets, runner transport; banana; no station cut-off |
| 18 · Michigan Ave between 33rd and 35th | 23.04 mi · elevation not published · cumulative ascent not published | G/W; medical, toilets, runner transport; banana; no station cut-off |
| 19 · Michigan Ave between 26th and 25th | 24.5 mi · elevation not published · cumulative ascent not published | G/W; medical, toilets, runner transport; no station cut-off |
| 20 · Michigan Ave between 18th and 16th | 25.2 mi · elevation not published · cumulative ascent not published | G/W; medical, toilets, runner transport; no station cut-off |

Abbreviations: G = Gatorade Endurance Formula (lemon-lime), W = water, MG = Maurten Gel 100. The official aid-station table has no elevation or cumulative-ascent column, so the table does not invent numbers; 1 mile is about 1.609 km, but this page does not convert every row, so that a derived kilometre value is not mistaken for an official one.

Points that must be stated:

- **No per-station cut-off is published**. The only official cut-off is the 6-hour 30-minute course limit, a 15-minute-per-mile pace. "No station cut-off" in the table therefore does not mean the stations are free of time pressure.
- **Runner transport covers all 20 aid stations**. If a runner cannot finish, the organiser provides non-emergency transport from every aid station back to Grant Park; each medical tent has a runner-transport sign and a volunteer in a green vest.
- **Maurten Gel 100 appears at two places**: near station 9 (12.4 miles) and station 14 (18.1 miles), with 25 g of carbohydrate per sachet.
- **Bananas are only at stations 16 to 18** (20.2 to 23 miles). **Culligan refill points** sit before stations 4, 7, 12 and 16 (5.7, 10.1, 15.7 and 20.3 miles); they refill approved self-carried hydration gear only, and backpacks or running vests with hydration bladders are not permitted.
- **The Biofreeze Pain Relief Zone** is at 21.2 miles (Cermak Rd at Archer Ave), with spray; it is not an aid station.
- **Street reopening is not an aid-station cut-off**. The official schedule expects Clark St at mile 10 to reopen at 12:45 p.m.; Wells St at mile 13 at 1:30 p.m. and Wacker Dr at 1:45 p.m.; 18th St and Halsted at mile 20 at 3:15 p.m.; 31st St at mile 25 at 4:15 p.m.; Michigan Ave at mile 26 at 4:30 p.m.; and Roosevelt Rd at 6:00 p.m. Those times are traffic management, not per-station timing gates.
- **Under the official 15-minute-per-mile limit, the one-to-two-mile gaps between aid stations correspond to roughly 15–30 minutes**. This is only a rough planning aid; official data give no per-station cut-off and no elevation per station, so aid-station spacing should not be used to infer gradient.

![Runners at the 2019 Chicago Marathon](/media/routes/chicago/chicago-street-2019.jpg)

## Surface and terrain

The organiser publishes no surface percentages. What can be confirmed is that the course uses Chicago city streets and that the course page calls it flat and fast. The official course map marks mile and kilometre markers, aid stations, medical points, Culligan refill points, Maurten gel, the Biofreeze zone, Bank of America cheer zones and charity block parties, but it publishes no elevation-profile figures. This page therefore does not give an asphalt, concrete or cement split, and it does not turn "flat" into "zero metres of climbing".

The street-closure table confirms that the course runs continuously through the Loop, the lakefront, the North Side, the West Side and the South Side, with city roads as the surface. The organiser also says the course map is subject to change, so construction, road maintenance or safety arrangements can alter a local section. For runners, that means an old map should not be used to infer this year's turns, aid stations or closures; the current official map and event notices are the authority.

## Risks and escape points

- **Course limit and sweep vehicle**: the official limit is 6 hours 30 minutes, a 15-minute-per-mile pace. An event vehicle follows the last starter at that pace and signals to event and traffic-safety staff when roads can reopen. Once the sweep vehicle passes a runner, the runner must move to the sidewalk; a runner who finishes outside the limit may not be recorded or published as an official finisher and may lose full aid-station and traffic-safety support.
- **Medical density**: the organiser says there are 22 medical locations. All 20 aid stations have medical tents, with additional tents between miles 14 and 15 and in the final mile. The specific medical tents beyond the finish line are set out in the current official guide.
- **Event Alert System**: the organiser uses a green, yellow, red and black EAS scale for weather and race conditions. Information is distributed by email, the website, public address at the expo, and public address and colour-coded flags at the start, finish and all 20 aid stations. This is the official risk-communication channel, not a rating invented by this page.
- **Urban weather risk**: the course has no mountains and no technical terrain. The main risk is autumn Chicago wind, rain, heat or cold, plus local differences created by high-rises and the lakefront. The organiser advises runners to watch the forecast but publishes no on-course measured temperature; the grid-point statistics in section 9 are not race-day measurements.
- **Escape options**: the official runner-transport vehicles from all 20 aid stations back to Grant Park are the most direct in-race escape. Medical tents can call an ambulance. Spectators can use CTA rail to move along the course, but the organiser does not say runners may leave the race at any CTA station; spectator movement should not be treated as a runner escape plan.
- **After the finish**: the finish is inside Grant Park; the exact finish area, medal and gear-check arrangements and opening times are set out in the current official guide and are not verified on this page.
- **Course rules**: the organiser prohibits unregistered wheelchairs, baby joggers, strollers, skateboards, bicycles, motorised devices, selfie-sticks, camera mounts, drones, and backpacks or running vests with hydration bladders. Running vests with front pocket carry, fuel belts, handheld bottles and soft flasks are allowed. Headphones are allowed, but runners must stay alert; High Performance Program athletes may not use them.

## Getting there

- **O'Hare airport (ORD)**: the CTA Blue Line serves the airport directly from the lower-level station, connected to Terminals 1, 2 and 3; Terminal 5 connects by a free airport shuttle train to the station. Blue Line trains run 24 hours a day and take about 40–45 minutes to downtown; the fare from O'Hare is $5 or less.
- **Midway airport (MDW)**: the CTA Orange Line serves the airport directly, with the station just east of the terminal and an enclosed walkway. The ride to downtown takes about 20–25 minutes and costs $2.50 or less; the Orange Line does not run overnight, when the N62 Archer bus is the alternative.
- **CTA within the city**: the official participant guide recommends CTA for getting around. City fares, passes and transfer rules should be checked against the current CTA publication.
- **Metra**: the official participant guide promotes Metra; current pass prices and valid days should be checked with Metra. The expo is at McCormick Place (Abbott Health & Fitness Expo).
- **South Shore Line**: the official participant guide lists the South Shore Line as a recommended option; current route, stations and timetable should be checked with the operator.
- **Bikes**: the official participant guide lists Divvy and free World Bicycle Relief bike valet; current locations, opening times and rules are set out in the guide.
- **Driving and parking**: the organiser discourages driving because race-day closures run from 6 a.m. to 4 p.m.; if driving is unavoidable, allow for congestion. The closest parking to Grant Park is the official Millennium Garages group. Streets in the Loop are expected to be open by 9 a.m.
- **Hotels and start/finish flow**: the Hilton Chicago is the official headquarters hotel, facing Grant Park and Lake Michigan, with 1,544 rooms and walking distance to the start and finish. Maritz is the official housing partner. The start is at the north end of Grant Park and the finish is in Grant Park; gear check is assigned by the colour on the bib. On race day Grant Park opens to runners at 5:30 a.m. and to spectators at 9:30 a.m.

## Season and weather

The 2026 race is on Sunday 11 October. The official FAQ says the Chicago Marathon takes place on the second Sunday of October; the 2027 date is currently published as 10 October. For the same time window, this page queried the Open-Meteo historical archive at Chicago coordinates 41.8781N / 87.6298W for 4–12 October 2026, a nine-day window. Open-Meteo returned a grid point at 41.862915N / 87.64877W, elevation 241 m, timezone America/Chicago.

- Daily maximum temperature: 18.6°C to 28.9°C, median 22.1°C.
- Daily minimum temperature: 10.6°C to 16.6°C, median 11.9°C.
- Two of the nine days recorded 0.4 mm of precipitation (9 and 12 October); no day reached 1 mm.
- Race day, 11 October: maximum 22.1°C, minimum 13.6°C, precipitation 0.0 mm, maximum wind 11.3 km/h.
- Across the nine days, daily maximum wind ranged from 11.3 to 21.8 km/h, median 14.5 km/h.

These are **grid-point historical statistics, not measurements on the course**. Chicago's urban heat island, lakefront breeze, high-rise canyons and shade differences by neighbourhood all change the felt temperature; the grid-point 22.1°C cannot replace the temperature in Grant Park at the start, nor the wind on the lakefront or in the South Side in the second half. Open-Meteo data are used under CC BY 4.0 with attribution.

## Difficulty rating

The organiser publishes no single difficulty grade, and this page does not invent an official one. On the verifiable dimensions, this is a road marathon:

- Official distance is 26.2 miles; no official ascent or descent is published, so it cannot be described as "zero metres of climbing" or compared with other courses by cumulative gain.
- The organiser describes the course as flat and fast; it runs through 29 neighbourhoods on city roads, with no mountain trail or technical terrain.
- The official limit is 6 hours 30 minutes, a 15-minute-per-mile pace; there are 20 aid stations and 22 medical points, so aid and medical density is high.
- In 2026 there were more than 54,000 participants, 1.7 million spectators and 10,000 volunteers, so start and early-race crowding are real variables.
- World Athletics gives the event a Platinum Label, which reflects organisational, course-measurement, safety and medical standards, not difficulty.

Taken together, this page's "moderate" label is an **unofficial editorial judgement**: it is not a trail or high-altitude race, and the main difficulties are training volume, pace control, autumn weather and the repetitive impact of 42 km on city roads. On climbing alone it is lower than a mountain race, but the official data do not support any "flattest course" ranking.

## Verified and unverified

**Verified (with official sources)**: the 48th running on 11 October 2026; more than 54,000 participants, 29 neighbourhoods, 1.7 million spectators and 10,000 volunteers; 26.2 miles; start and finish in Grant Park; the street and mileage of all 20 aid stations; 22 medical locations; the 6:30 limit and 15-minute-per-mile pace; timing-point positions; the locations of Maurten, bananas, Culligan and Biofreeze; runner transport from all 20 aid stations; the four-level EAS; CTA, Metra, South Shore Line, Divvy, bike valet and Millennium Garages; Open-Meteo grid statistics for the 2026 race window; the 2026 men's and women's winners and selected times; the World Athletics Platinum Label; the existence and legend of the official course-map PDF.

**Unverified (this page draws no conclusion)**: cumulative ascent and descent; surface percentages by segment; per-station cut-off times; actual race-day temperature, humidity and wind; potholes, construction and temporary rerouting; the exact start-line coordinate; whether the 2027 course is identical to 2026; real aid-station queue times; spectator density and mobile coverage; wheelchair, handcycle and elite-specific course details. The official press release gives two different men's wheelchair course-record times (1:21:34 in the summary and 1:21:24 in the body); this page does not pick one for the organiser and does not use either figure for a course conclusion.

## Images and rights

**One photograph, from Wikimedia Commons, with a file page that names this event.**

Runners at the 2019 Chicago Marathon, Kenneth C. Zirkel, CC BY 4.0. The image shows runners on the 2019 Chicago Marathon course; the file page does not name the street, and this page does not infer one.

Channels used this round: the Wikimedia Commons `action=query&generator=search` API, `Special:MediaSearch`, `commons.wikimedia.org/w/index.php?search=` and direct `upload.wikimedia.org` URLs were all reachable. The filter is still three checks: readable licence, file page proving this event, and image matching the caption. Anything failing one is not used. Organiser photographs carry no redistributable CC licence and were not used. (2026-11-07 recheck: the Wikimedia Commons hosts were unreachable from this network; file pages and licences are kept from the capture round and were not re-verified.)

The file is unmodified apart from size and weight compression, and is not covered by this page's CC BY 4.0.

## Sources and reuse

This text was written independently by the RunUp editorial team from the organiser's public pages, the official participant guide, the official course map, the official street-closure table, the official results page, the official press release, the CTA airport page, the World Athletics race report and Open-Meteo data. It is licensed CC BY 4.0. Event names, official marks, official route text, the official course map and official PDFs remain the property of the organiser; this page links to the official PDFs and does not redistribute the course map, a GPX or any other official file.

This page cites 13 external sources: the event course page, the 2026 participant guide PDF, the event participant-information page, the 2026 official course-map PDF, the official street-closure page, the official results page, the 2026 official press release, the 2026 FAQ, the spectator CTA route page, the CTA airport transit page, the World Athletics race report, Open-Meteo historical weather and `photo-chicago-2019` (the 2019 course photograph); there is also one editorial anchor note, making 14 `sourceRefs` in total. Open-Meteo data are attributed under CC BY 4.0. The image is credited separately under its Commons file-page CC BY 4.0 licence and is not covered by this page's CC BY 4.0. The supporting claim and access date for each source appear in the source list at the bottom of the page.
