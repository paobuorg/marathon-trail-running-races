---
entityId: route:new-york
locale: en
title: "New York City Marathon: the complete 2026 five-borough course guide"
summary: "The 2026 New York City Marathon in full: the official pages give 26.2 miles and course facilities but no cumulative climb; five waves, per-mile fluid stations, Maurten gel depots, the 10 p.m. finisher cut-off, ferry and bus access, early-November weather, each figure labelled with its official basis and checked date."
aliases: ["New York City Marathon", "TCS New York City Marathon", "NYC Marathon", "five-borough marathon", "26.2 mile city marathon"]
authors:
  - runmap-editorial
reviewers:
  - runmap-editorial
translationStatus: reviewed
---

## Check status

- Version: `2026-new-york-city-marathon-official-course`. The 2026 edition was held on Sunday 1 November 2026. The official start timeline begins at 08:00 with the men's professional wheelchair division; the five mass waves run from 09:10 to 11:30.
- Checked on 2026-11-08. Every figure below carries its official basis; where the organiser publishes nothing, the page says "not published" rather than filling the gap with a third-party number.
- Course geometry: **no usable geometry**. As of the checked date, the NYRR course page consulted for this page offers one 2026 course PDF map and an interactive Google map; on those pages no GPX, KML or GeoJSON download was found, and no licence statement permitting redistribution of a track was seen. `geometryAccess` is therefore fixed at `unavailable`, `officialGeometryUrl` is `null`, and this page draws no line, bundles no file and adds no manual points; the globe shows only an editorial overview anchor.
- Official static course map: [official course page with 2026 PDF map and interactive map](https://www.nyrr.org/tcsnycmarathon/the-course). This is a JPG/PDF/web map, not GPX/KML/GeoJSON; it is linked only and not counted as an official geometry entry.
- This page has not been run on the ground, so it offers no first-hand testing claims. Verified and unverified material is kept separate below.
- Course-change check: no past-edition handbook was obtained, so the course-change history is unverified. This page has no official evidence of a reroute, date change or rule change that qualifies for the log; `courseChanges` is an empty array and is not presented as "no changes".

## What this course is

The New York City Marathon is a point-to-point city road marathon: it starts at Fort Wadsworth on Staten Island, crosses all five boroughs and finishes on West Drive at 67th Street in Central Park, Manhattan. The official course page states it plainly — 26.2 miles through the five boroughs of NYC. It is not a loop: a bridge and an entire city separate the start from the finish, so the organiser publishes transport, bag check and wave assignment as separate pages.

Two dates matter for the 2026 edition. First, it is the 50th anniversary of the five-borough route: the organiser says the course was first run on 24 October 1976. Second, 2026 finally changes the Bronx section — the organiser calls it the first course change in 15 years. The new line is: after the Willis Avenue Bridge, turn left onto East 135th Street, right onto Alexander Avenue and continue straight; then, instead of turning left onto East 138th Street, turn left onto East 141st Street, left onto Third Avenue and right onto East 138th Street before crossing the Madison Avenue Bridge. Anyone working from an older track should treat this official wording as the current course.

The size of the 2026 field is another checkable dimension. The official post-race release reports 61,146 finishers from 61,529 starters, the third consecutive year the race has broken the world record for the largest marathon; the field represented 153 countries, including 15,745 international finishers. The official pages also record more than 1,600 toilets in the start villages and corrals, timed ferry and bus slots, and five waves from 09:10 to 11:30.

There are two checkable performance anchors as well. Andreas Almgren of Sweden won the 2026 men's race in 2:06:01 and Sheila Chepkirui of Kenya won the women's race in 2:24:36.

An NYRR coach, quoted on the organiser's own site, says the highest point of the race is in the first two miles at about 260 ft (1 ft = 0.3048 m, so about 79 m) above sea level. The later climbs matter less for their height than for their timing: the Queensboro Bridge at miles 15 to 16 and Fifth Avenue at miles 22 to 23 — a second NYRR page puts Fifth Avenue at miles 23 to 24, and both wordings are official, so this page shows both instead of picking one.

## Official figures

Start with what the organiser actually publishes. NYRR's 2026 course page and World Athletics' post-race report give the distance as 26.2 miles; the 2026 race page and the 2019 course Q&A, as recorded here, state no distance. None of the four official pages gives cumulative gain or loss. The only elevation figure in those official pages is in the NYRR 2019 course Q&A, where a coach says the highest point is about 260 ft in the first two miles. That is a high point, not total ascent, and not total descent.

The table therefore lists only the four official bases that exist, and refuses to import the cumulative-climb figures that third-party sites often present as "official". The entity card at the top of the page uses the standard marathon distance of 42.195 km (26.2 miles is the rounded mile form of that distance, with 1 mile = 1.609344 km); that is a project definition, not a new official measurement. The gain field stays `null`.

| Basis | Distance | Gain | Loss | Highest point |
|---|---|---|---|---|
| NYRR 2026 course page | 26.2 mi | not published | not published | not published |
| NYRR 2026 race page | not listed | not published | not published | not published |
| NYRR 2019 course Q&A | not listed | not published (the article gives only a high point) | not published | about 260 ft (about 79 m) in the first 2 miles |
| World Athletics 2026 race report | 26.2 miles | not published | not published | not published |

(Metric conversions use 1 ft = 0.3048 m; "not listed" means the points recorded for this page from that source state no distance.)

The conclusion is not "there is no data" but "the official pages carry no cumulative elevation, and distance is stated explicitly only on the course page and the World Athletics report". This page gives no official climb figure for the New York City Marathon because none was found on the official pages.

## Segments

The organiser defines the course by markings, not by an elevation profile: mile markers every mile, kilometre signs every 5 km, and timing mats at the start, at every mile from 3M, at every 5K from 5K, at halfway (13.1M), at 25.2M and at the finish. All course clocks are set to wave 1. The table below therefore splits the course at the official 5K timing mats rather than at points taken from a third-party track; the official pages publish no per-segment gain or loss, so those cells say so.

| Segment | From → to | Distance | Gain / loss |
|---|---|---:|---:|
| 1 | Start → 5K (Staten Island · Verrazzano Bridge · Brooklyn) | 5.00 km | not published / not published |
| 2 | 5K → 10K (Fourth Avenue, Brooklyn) | 5.00 km | not published / not published |
| 3 | 10K → 15K (Brooklyn, heading towards Williamsburg) | 5.00 km | not published / not published |
| 4 | 15K → 20K (Brooklyn, approaching Williamsburg and the Pulaski Bridge) | 5.00 km | not published / not published |
| 5 | 20K → 25K (Brooklyn → Pulaski Bridge → Queens → Queensboro Bridge) | 5.00 km | not published / not published |
| 6 | 25K → 30K (Queensboro Bridge → First Avenue and East Harlem, Manhattan) | 5.00 km | not published / not published |
| 7 | 30K → 35K (Manhattan → Willis Avenue Bridge → Bronx → Madison Avenue Bridge → Manhattan) | 5.00 km | not published / not published |
| 8 | 35K → 40K (Fifth Avenue, Manhattan → Central Park) | 5.00 km | not published / not published |
| 9 | 40K → finish (67th Street, Central Park) | 2.195 km (standard marathon distance) | not published / not published |

(Each 5.00 km segment follows the official 5K timing mats; the final 2.195 km is the standard marathon distance of 42.195 km minus 40 km. 42.195 km is a project definition value; NYRR publishes 26.2 miles only.)

What can be confirmed segment by segment, all from NYRR pages:

- **Segment 1 (0 → 5 km)**: the start village is at Fort Wadsworth; miles 1 to 2 are the Verrazzano-Narrows Bridge, which is also where the course high point sits. The official spectator page states there is no viewing at the start or on the bridge. After the bridge the course enters Fourth Avenue in Brooklyn.
- **Segment 2 (5 → 10 km)**: Fourth Avenue, Brooklyn; the official spectator page places miles 2 to 4 on Fourth Avenue.
- **Segment 3 (10 → 15 km)**: still in Brooklyn, heading towards Williamsburg; mile 8 sits at Fourth Avenue and Flatbush Avenue and is also a Culligan refill station.
- **Segment 4 (15 → 20 km)**: Williamsburg and Greenpoint, which the official spectator page places at miles 10 to 13; the segment ends approaching the Pulaski Bridge.
- **Segment 5 (20 → 25 km)**: the Pulaski Bridge at mile 13.1 carries runners from Brooklyn into Queens and is closed to spectators; the Queensboro Bridge follows, which the NYRR 2019 article places at miles 15 to 16, and this segment ends on the bridge deck.
- **Segment 6 (25 → 30 km)**: the Queensboro Bridge is completed and the course enters Manhattan; the official spectator page places miles 16 to 18 on First Avenue and miles 18 to 20 in East Harlem.
- **Segment 7 (30 → 35 km)**: East Harlem → mile 20 enters the Bronx → the course leaves just after mile 21 → back into Manhattan. This is the core of the 2026 reroute: after the Willis Avenue Bridge, left onto East 135th Street, right onto Alexander Avenue, left onto East 141st Street, left onto Third Avenue, right onto East 138th Street, then across the Madison Avenue Bridge.
- **Segment 8 (35 → 40 km)**: Fifth Avenue. The official spectator page puts East 90th to East 105th Streets at miles 23 to 24; the NYRR 2019 article puts Fifth Avenue at miles 22 to 23. Both are official; the two official pages differ, and this page does not choose between them; the segment ends entering Central Park.
- **Segment 9 (40 km → finish)**: inside Central Park, finishing on West Drive at 67th Street. The official spectator page states that the park north of the grandstands is closed to spectators.

## Aid stations and cut-offs

The organiser publishes aid as a per-mile rule rather than a checkpoint table with elevation: purified water and Gatorade are available at official fluid stations every mile from mile 3 to mile 25, except miles 5, 7 and 9. In warmer weather there are misting stations at every fluid station; cups are compostable and tables sit on both sides of the course. Culligan filtered self-serve refill stations are placed one per borough at miles 8, 14, 17, 20 and 23. Maurten gels are handed out at Gel Depots at miles 12 and 18, and bananas are available at mile 21. The organiser repeatedly warns that gel supplies are limited and not guaranteed, strongly advises carrying your own fuel, and recommends taking one gel per depot.

Portable toilets, including wheelchair-accessible units, are located at every mile beginning at mile 3; the start villages and corrals hold more than 1,600 toilets. Medical aid stations are located approximately every mile starting at mile 3 and at the finish, staffed with volunteers and supplies; AEDs are carried in the start and course medical tents, in ambulances along the course and at the post-finish medical tents. The official emergency number is 866-705-6626, and friends and family can call the Medical Information Hotline on 855-697-7786. Lactation spaces are provided at miles 8, 17 and 22, plus one in the start village.

The cut-off has two layers. The first is official finishing status: regardless of start time, runners who cross the finish by 22:00 ET are official finishers, receive a medal, an official result at results.nyrr.org and 9+1 credit toward the 2027 race. The organiser states that runners crossing after 22:00 ET will not be recorded as official finishers and will not receive an official result, although they still receive a finisher medal. The second layer is course support: the schedule is designed to let runners holding a 16-minute-per-mile pace, based on the wave 5 start, complete the course on the streets; those who cannot may find fluid stations and amenities unavailable, may be asked to move to the sidewalks or board a sweep bus. Boarding a sweep bus means you cannot cross the finish and will not be recorded as an official finisher. NYRR's general Time Cutoff Policy explicitly exempts the TCS New York City Marathon and directs readers to the race page's own timeline, so this page does not apply the generic 20-minute-per-mile finish table.

| Place | Distance · elevation · cumulative gain | Services / cut-off |
|---|---|---|
| Mile 3 fluid station | 3 mi · elevation not published · cumulative gain not published | water · Gatorade · medical · toilets; segment cut-off not published |
| Mile 8 | 8 mi · elevation not published · cumulative gain not published | water · Gatorade · Culligan refill · lactation space; segment cut-off not published |
| Mile 12 gel depot | 12 mi · elevation not published · cumulative gain not published | water · Gatorade · Maurten gels (limited); segment cut-off not published |
| Mile 14 | 14 mi · elevation not published · cumulative gain not published | water · Gatorade · Culligan refill; segment cut-off not published |
| Mile 18 gel depot | 18 mi · elevation not published · cumulative gain not published | water · Gatorade · Maurten gels; segment cut-off not published |
| Mile 21 | 21 mi · elevation not published · cumulative gain not published | water · Gatorade · bananas; segment cut-off not published |
| Mile 23 | 23 mi · elevation not published · cumulative gain not published | water · Gatorade · Culligan refill; segment cut-off not published |
| Mile 25 | 25 mi · elevation not published · cumulative gain not published | water · Gatorade (last official per-mile station); segment cut-off not published |
| Finish (67th Street, Central Park) | 26.2 mi · elevation not published · cumulative gain not published | medical · medal · official result; official finishing status until 22:00 ET |

The empty elevation and cumulative-gain cells are not a layout shortcut: the NYRR official pages publish no point-by-point elevation. Putting a third-party profile into this table would imply it was official, and this page does not do that.

![The elite men’s leaders at the 2024 New York City Marathon](/media/routes/new-york/elite-men-2024.jpg)

## Surface and terrain

The NYRR official pages publish no surface breakdown, so this page gives no percentages. What can be confirmed is that the course runs on city streets closed by the NYPD on race day, crosses five boroughs, includes several bridges and finishes on West Drive in Central Park. The bridges named across NYRR pages are the Verrazzano-Narrows Bridge at miles 1 to 2, the Pulaski Bridge at mile 13.1, the Queensboro Bridge at miles 15 to 16, the Willis Avenue Bridge into the Bronx at mile 20, and the Madison Avenue Bridge at the end of the Bronx section. This page lists them because the official text names them; it does not turn "five bridges" into an official climb total.

Three terrain facts are solid. The high point is in the first two miles, about 260 ft; the NYRR coach's wording is that "you do not even feel it". The later climbs matter for timing: the Queensboro Bridge at miles 15 to 16 and Fifth Avenue somewhere between miles 22 and 24, depending on which official page you read. And the course finishes on West Drive in Central Park.

The official pages carry no surface ratio or technicality rating, so this page gives neither. This is a certified road course — NYRR's rules page states that its courses are certified by USATF and/or World Athletics — not a trail route, and it should not be prepared with mountain-trail equipment logic.

## Risks and escape points

- **Cold and wind**: the 2026 edition was held on 1 November. In the 2026 pre-race window recorded here, the daily minimum fell to 4.4°C; the start village is on Staten Island. The official start page advises extra layers and provides labelled clothing-donation bins for discarded items.
- **Sweep and cut-off**: the organiser runs sweep buses at a 16-minute-per-mile pace based on the final wave, and finishing after 22:00 ET means no official result. The bus will take you to the post-finish area, but boarding it means you cannot cross the finish. Under the official wording, a runner who boards a sweep bus is not recorded in the results.
- **Medical**: aid stations run roughly every mile from mile 3; the official instruction is to stop at the nearest station if ill or injured. Emergency number 866-705-6626; family hotline 855-697-7786.
- **Dropping out**: the official wording is direct — seek medical help at an aid station; if you have not completed the course, do not go through the finish or you will be disqualified and barred from future New York City Marathons. To claim a checked bag, enter Central Park West at 62nd Street; after 19:00 unclaimed bags move to the NYRR RUNCENTER and can be collected on Marathon Monday, 2 November, from 09:00 to 20:00.
- **Course rules**: you must complete the entire course; after leaving it you may only rejoin at the point where you exited, and rejoining elsewhere may lead to disqualification; missing or irregular split times are reviewed. Receiving assistance from an unregistered person, or pacing by an unofficial pacer, can lead to disqualification.
- **Carrying fluid**: NYRR rules allow containers of one litre or less in a hydration belt, in the front pockets of a hydration vest, or by hand — not in a backpack or a bladder on your back.
- **Unauthorised vehicles and activities**: NYPD closes the streets on race day, and the organiser prohibits unsanctioned bicycles and any unauthorised activity on the closed course, including during setup and while runners are on the road. Offenders are diverted and removed.
- **Spectator limits**: there is no viewing at the start or on the Verrazzano Bridge; spectators are not allowed on any course bridge; the park north of the Central Park grandstands is closed. These limits affect where family can meet you.
- **Transport non-compliance**: the official transport page requires everyone to arrive in their assigned time slot using their selected mode. Using the Staten Island Ferry, the NYPL bus or the New Jersey bus without that assignment can lead to a warning, disqualification, cancellation of purchased entries or suspension.

## Getting there

The official transport page covers race-day travel to the start only; it does not publish airport transfers, and this page does not invent them. Within New York, the official routes are as follows.

- **Staten Island Ferry**: departs Whitehall Terminal in Manhattan; the organiser estimates 90 minutes total. Whitehall is served by the 1 train at South Ferry and the R and W at Whitehall Street–South Ferry, plus the M15, M20 and M55 buses. The ferry is free and carries runners to St. George Terminal on Staten Island, where free buses take them to Fort Wadsworth. The organiser recommends the ferry to runners expecting a finish time of four hours or more, because it gets them to the start closer to their wave.
- **Midtown bus (NYPL)**: departs the New York Public Library at Fifth Avenue and 40th Street; estimated 90 minutes, with a requirement to arrive 15 minutes before departure. Buses go directly to Fort Wadsworth.
- **New Jersey bus**: departs MetLife Stadium Parking Lot K; estimated 60 minutes, arrive 15 minutes early; direct to Fort Wadsworth.
- **Private car, taxi or rideshare**: the only drop-off is McClean Avenue and Ocean Avenue on Staten Island; private buses drop near McClean Avenue and Lily Pond Avenue. The organiser states there is no parking at the start and the walk from the drop-off area to the start villages is about half a mile.
- **Bridge closure**: the Verrazzano-Narrows Bridge closes to all traffic at 07:00, so private vehicles must reach the start before then. Before 07:00, vehicles from New Jersey may use Exit 14 (Narrows Road North / Hylan Boulevard); after 07:00, closures force the Clove Road exit.
- **Use the assigned option**: transport selection opened on 25 August and closed on 8 September at 23:59; from 2026 NYRR assigns departure times based on registered or best pace. Arriving outside the assigned slot or using a different mode risks penalties.
- **Special channels**: ITO runners may use official NYRR transport, including the ITO Westside Midtown Ferry or charter coaches from hotels to Fort Wadsworth; Team for Climate runners are assigned the 06:15 ferry by default; charity partners have dedicated buses (Fred's Team from West 48th Street and Broadway at 05:45, Silver-level charity partners from 59th Street/Central Park South and Seventh Avenue at 05:45).
- **Spectators**: the organiser recommends the subway and checking mta.info for service changes. Spectators cannot enter the start, the Verrazzano Bridge or any course bridge.

## Early-November season and weather

The 2026 edition was held on 1 November. This page queried the Open-Meteo historical archive for 26 October to 2 November 2026 — eight days — at the New York City grid point 40.738 N / 74.043 W, elevation 32 m:

- Daily maximum: 15.9°C to 21.8°C, median 18.0°C.
- Daily minimum: 4.4°C to 10.9°C, median 7.3°C.
- One of the eight days had measurable precipitation (0.4 mm on 28 October); no day reached 1 mm.
- Race day, 1 November: maximum 16.1°C, minimum 4.4°C, precipitation 0.0 mm.

These are **modelled or reanalysis values for a grid point, not course measurements, and not measurements at the start village or on the bridge decks**. An eight-day window describes the shape of one race week, not a climate normal; another New York November can be colder, wetter or windier. Grid-point temperature is not the temperature at the bridge deck or the start village; the start village waits from early morning, and layering is the practical response.

## Difficulty

The official pages carry no "difficulty grade", and this page does not invent an official one. The verifiable dimensions are listed below; this page gives no difficulty grade:

- 26.2 miles on a certified road course.
- The only elevation figure in the official pages is a high point of about 260 ft in the first two miles; those pages carry no cumulative gain.
- Five named bridges (Verrazzano, Pulaski, Queensboro, Willis Avenue and Madison Avenue); separately, the Fifth Avenue climb sits somewhere between miles 22 and 24.
- Official finishing status until 22:00, course support at a 16-minute-per-mile pace, and sweep buses following the course.
- 61,529 starters and 61,146 finishers in 2026; the start releases runners in five waves from 09:10 to 11:30.
- Point-to-point, an island start, and a mandatory transport mode and time slot.

This page does not judge individual difficulty; the verifiable logistics and timing are the wave assignment, the ferry slot, and the positions of the Queensboro Bridge and Fifth Avenue climbs.

## Verified and unverified

This page has not been run on the ground, so the two are kept strictly apart:

**Verified from official sources**: the 1 November 2026 race date; 26.2 miles across five boroughs; Fort Wadsworth start and the Central Park finish on West Drive at 67th Street; the 2026 Bronx reroute; the five mass waves and the 08:00 to 11:30 start timeline; the per-mile fluid-station rule and the miles 5, 7 and 9 exceptions; Culligan at miles 8, 14, 17, 20 and 23; Maurten gel depots at miles 12 and 18; bananas at mile 21; lactation spaces at miles 8, 17 and 22; toilets and medical aid every mile from mile 3; the 22:00 finishing rule and sweep-bus policy; transport modes, time slots and the 07:00 bridge closure; 61,146 finishers; the 2026 open and wheelchair champions; and the 26 October – 2 November grid-point weather statistics.

**Unverified — no conclusions drawn here**: actual surface ratios and runnability by segment; cumulative gain and loss by segment; real queueing times at fluid stations; how the bridge grating feels underfoot; mobile coverage; the precise time each borough boundary is crossed; race-day weather (this page has historical/reanalysis values only); and the contents of the official PDF maps, which this page did not parse.

## Images and rights

**One photograph, recorded from Wikimedia Commons at capture time.**

The elite men’s leaders at the 2024 New York City Marathon; author: Nrbelex; licence: CC BY-SA 4.0; date: 2024-11-03 (verified against the Commons file page and API on 2026-11-20). The image shows the 2024 New York City Marathon elite men’s leaders, and the file description names winner Abdi Nageeye; the file page does not name the street, and this page does not infer one.

Channels used in the 2026-11-07 capture round: the Wikimedia Commons `action=query&generator=search` API, `Special:MediaSearch`, `commons.wikimedia.org/w/index.php?search=` and direct `upload.wikimedia.org` URLs were reachable at that time. The filter is still three checks: readable licence, file page proving this event, and image matching the caption. Anything failing one is not used. Organiser photographs were not used, and their licence was not checked this round. 

The file is unmodified apart from size and weight compression, and is not covered by this page's CC BY 4.0.

## Sources and reuse

This page was written independently by the RunUp editorial team from NYRR's public pages, World Athletics' post-race report and Open-Meteo data, and is licensed CC BY 4.0. Event names, official marks, official route text, the official PDF maps and the interactive map remain the property of NYRR; this site redistributes no course file and does not convert the official map into a track.

The page cites twelve new sources across eight types: race and course facts (the 2026 race page, course page and 2019 course Q&A), start and corrals (the start page), transport (the transport page), rules and cut-offs (the rules page and the general time-cutoff policy), spectators and course geography (the spectator page), results (the official finisher release and the World Athletics report), weather (Open-Meteo), and the 2024 elite men's leaders photograph (`photo-new-york-2024`). Two further references are the existing event entry source and the editorial anchor method. Each source's supported claims and access date appear in the source list at the bottom of the page. Open-Meteo data are used under CC BY 4.0 with attribution; Each image's author and licence are stated with its caption; they are not covered by this page's CC BY 4.0.
