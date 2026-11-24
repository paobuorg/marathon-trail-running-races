---
entityId: route:tokyo
locale: en
title: "Tokyo Marathon 2026: the full course guide"
summary: "The 2026 Tokyo Marathon in full: the official 42.195 km point-to-point course, nine cut-off checkpoints and 15 aid stations, 13 medical stations, access, early-March weather, risks and escape points. This page obtained no redistributable geometry, so it draws no track."
aliases: ["Tokyo Marathon", "Tokyo Marathon 2026", "Tokyo Marathon course"]
authors:
  - runmap-editorial
reviewers:
  - runmap-editorial
translationStatus: reviewed
---

## Check status

- Version: `2026-tokyo-official-course`, the 2026 edition, starting at 09:10 on 1 March 2026 from the Tokyo Metropolitan Government Building.
- Checked on 2026-11-08. Race figures come from an official page or official PDF that was successfully retrieved; weather figures come from the Open-Meteo archive API. Where the organiser publishes nothing, the page says "not published" rather than filling the gap with a third-party estimate.
- Course geometry: **this page obtained no redistributable geometry**. The official course page offers a course-map PDF and a web course map, with no GPX download link and no licence permitting redistribution. This page therefore draws no line and packages no track. The map shows only the editorial overview anchor at the Shinjuku start.
- Official static course map: [official course-map page](https://www.marathon.tokyo/en/about/course/). This is a JPG/PDF/web map, not GPX/KML/GeoJSON; it is linked only and not counted as an official geometry entry.
- This page is not based on running the course. It gives no "tested on the ground" conclusions. Verified and unverified material is separated below.
- Edition warning: the official website now defaults to the 2027 edition, and the 2027 race outline has been published: Sunday 7 March 2027, 09:10 start, a seven-hour marathon limit and a 2 h 30 wheelchair limit, a 40,000 field, the same course as 2026, and only the Marathon and Wheelchair Marathon events (the 2026 edition also had a 10.7 km event). This page pins the 2026 edition, using the 2026 race outline, the 2026 official program guidebook, the 2026 aid-station notice and the 2026 results page. The 2027 cut-off checkpoints, aid-station locations and supplies have not been checked item by item, so this page does not present the 2026 checkpoint data as 2027 data.
- Course-change check: no past-edition handbook was obtained, so the course-change history is unverified. This page has no official evidence of a reroute, date change or rule change that qualifies for the log; `courseChanges` is an empty array and is not presented as "no changes".

## What this course is

The Tokyo Marathon is a point-to-point road course through central Tokyo. It starts at the Tokyo Metropolitan Government Building in Shinjuku and finishes in front of Tokyo Station on Gyoko-dori, by the Wadakura-Gate intersection. The official 2026 race outline gives the order as Tokyo Metropolitan Government Building → Suidobashi → Ueno-hirokoji → Kanda → Nihombashi → Asakusa Kaminarimon Gate → Ryogoku → Monzen-nakacho → Ginza → Tamachi → Hibiya → Tokyo Station/Gyoko-dori Avenue.

It links Shinjuku, Akihabara, Asakusa, Ryogoku, Ginza, Tamachi and Marunouchi in one continuous city route. There are three turnarounds: Ueno-hirokoji, Tomioka Hachimangu and Tamachi. The start and finish are separate.

The official 2026 distance is 42.195 km. The course is certified by the Japan Association of Athletics Federations (JAAF) and recognised by World Athletics and AIMS. The 2026 race outline also states that the edition held World Athletics Elite Platinum Label status. The 2026 field was 39,000: 38,500 in the marathon and 500 in the 10.7 km race. The results page records 38,472 marathon starters and 37,268 marathon finishers, a 96.9% finish rate.

A 10.7 km race is held on the same day, from the same start, finishing at Nihombashi. The organiser states that records for that race are not certified. The official results group 2026 marathon finishers into five time bands at 3, 4, 5, 6 and 7 hours: 2,070 (5.6%), 9,951 (26.7%), 11,389 (30.6%), 8,858 (23.8%) and 4,967 (13.3%).

## How the official sources state the distance

| Basis | Distance | Ascent | Descent |
|---|---|---|---|
| 2026 race outline (official TMF PDF) | Distance not stated (marathon; JAAF-certified, WA/AIMS-recognised) | Not published | Not published |
| 2026 official course map PDF | No figure stated (5–40 km markers and Halfway Point) | Not published | Not published |
| 2026 official program guidebook, p.24 course map | 42.195 km (nine cut-off points, finish at 16:10) | Not published | Not published |
| Official course-page elevation profile (2026 figure) | 42.195 km | Not published (vertical axis runs to about 40 m) | Not published (start about 40 m, near 0 m before 5 km) |

The official course page and the official program guidebook p.24 both give 42.195 km. Ascent and descent are different: the official course page gives only a graphical elevation profile, and the official pages and PDFs state no cumulative ascent, cumulative descent, exact high point or exact low point.

The official profile supports only a description of shape. The start area sits near the top of the vertical axis, at roughly 40 m; the first 5 km trend downhill; the middle of the course stays at low altitude with small undulations; the finish returns to the Tokyo Station area. That is a reading of the official image, not a cumulative ascent figure. Cumulative-ascent and cumulative-descent figures do not appear in the official files retrieved for this page, so they are not used here. The page's `elevationGainMeters` field stays `null`.

## Nine segments

The table cuts the course at the nine official cut-off points. Segment distances are the differences between adjacent official kilometre points, not separately published official split distances. Ascent and descent are not stated in the official material, so every segment says so.

| Segment | Section | Segment distance | Ascent / descent |
|---|---|---:|---|
| 1 | Start → Ichigaya-Mitsuke crossing (4.9 km) | 4.90 km | Not published / not published |
| 2 | Ichigaya-Mitsuke → Sudacho crossing (9.2 km) | 4.30 km | Not published / not published |
| 3 | Sudacho → Hisamatsucho crossing (15.4 km) | 6.20 km | Not published / not published |
| 4 | Hisamatsucho → Midori 1-chome crossing (20.9 km) | 5.50 km | Not published / not published |
| 5 | Midori 1-chome → Fukagawa 1-chome crossing (24.7 km) | 3.80 km | Not published / not published |
| 6 | Fukagawa 1-chome → Asakusabashi crossing (29.2 km) | 4.50 km | Not published / not published |
| 7 | Asakusabashi → Sukiyabashi crossing (33.5 km) | 4.30 km | Not published / not published |
| 8 | Sukiyabashi → Shibakoen Ground-mae crossing (38.5 km) | 5.00 km | Not published / not published |
| 9 | Shibakoen Ground-mae → Tokyo Station/Gyoko-dori (42.195 km) | 3.695 km | Not published / not published |

Segment notes. All times come from the 2026 official program guidebook p.24 and are measured from the 09:10 gun:

- **Segment 1 (0 → 4.9 km).** The route leaves the Tokyo Metropolitan Government Building and heads towards Ichigaya. The official profile shows a net descent through this opening. The 4.9 km cut-off is at 10:25, or 75 minutes, which averages about 15:18/km, the loosest checkpoint by cut-off arithmetic.
- **Segment 2 (4.9 → 9.2 km).** Cut-off 11:10, 45 minutes for 4.30 km, about 10:28/km. The route enters the Kanda and Akihabara area.
- **Segment 3 (9.2 → 15.4 km).** Cut-off 11:55, 45 minutes for 6.20 km, about 7:15/km. This is one of the tightest segments when the official cut-off times are converted to pace.
- **Segment 4 (15.4 → 20.9 km).** Cut-off 12:45, 50 minutes for 5.50 km, about 9:05/km. This passes the Asakusa Kaminarimon and Ryogoku side of the course.
- **Segment 5 (20.9 → 24.7 km).** Cut-off 13:20, 35 minutes for 3.80 km, about 9:13/km. Just after halfway, the route turns around at Tomioka Hachimangu.
- **Segment 6 (24.7 → 29.2 km).** Cut-off 14:00, 40 minutes for 4.50 km, about 8:53/km. After the turnaround the course heads back towards Asakusabashi.
- **Segment 7 (29.2 → 33.5 km).** Cut-off 14:35, 35 minutes for 4.30 km, about 8:08/km. Approaching Ginza, this is one of the tightest segments by cut-off arithmetic.
- **Segment 8 (33.5 → 38.5 km).** Cut-off 15:15, 40 minutes for 5.00 km, about 8:00/km. Ginza, Hibiya and the Tamachi turnaround all sit in this section.
- **Segment 9 (38.5 → 42.195 km).** Cut-off 16:10, 55 minutes for 3.695 km, about 14:53/km. The final run back to Tokyo Station is looser by cut-off arithmetic than the earlier segments.

These minute-per-kilometre figures are arithmetic derived from official cut-off times divided by official kilometre differences. They are not official pacing advice and not measured on the course.

## 15 mid-course aid stations and cut-offs

The table lists the 15 mid-course aid stations from the 2026 aid-station notice and its PDF. Kilometre positions come from the same official PDF. "Water" means drinking water, "Pocari" means Pocari Sweat, and solid food follows the official table. This table only states categories that can be confirmed cell by cell in the aid-station notice and its PDF. Cut-off times come from the 2026 official guidebook p.24 and are gun times after the 09:10 start.

| Station | Distance | Service / nearest cut-off |
|---|---:|---|
| Aid station 1 | 5 km | Water, Pocari; 4.9 km cut-off 10:25 (already passed) |
| Aid station 2 | 7 km | Water; next cut-off 9.2 km 11:10 |
| Aid station 3 | 10 km | Water, Pocari; next cut-off 15.4 km 11:55 |
| Aid station 4 | 12 km | Water; next cut-off 15.4 km 11:55 |
| Aid station 5 | 15 km | Water, Pocari; next cut-off 20.9 km 12:45 |
| Aid station 6 | 17 km | Water; next cut-off 20.9 km 12:45 |
| Aid station 7 | 20 km | Water, Pocari, sponge cake; 20.9 km cut-off 12:45 |
| Aid station 8 | 22 km | Water, pickled plum, cream bread; next cut-off 24.7 km 13:20 |
| Aid station 9 | 25 km | Water, Pocari, sponge cake; 24.7 km cut-off 13:20 (already passed), next 29.2 km 14:00 |
| Aid station 10 | 27 km | Water, pickled plum, chocolate, ningyo-yaki; next cut-off 29.2 km 14:00 |
| Aid station 11 | 30 km | Water, Pocari, sponge cake; 29.2 km cut-off 14:00 (already passed), next 33.5 km 14:35 |
| Aid station 12 | 32 km | Water; next cut-off 33.5 km 14:35 |
| Aid station 13 | 35 km | Water; 33.5 km cut-off 14:35 (already passed), next 38.5 km 15:15 |
| Aid station 14 | 38 km | Water, pickled plum, chocolate; 38.5 km cut-off 15:15 |
| Aid station 15 | 40 km | Water, Pocari; finish 42.195 km 16:10 |

The complete list of nine cut-off checkpoints, from the 2026 official guidebook p.24:

- 4.9 km, Ichigaya-Mitsuke crossing: 10:25
- 9.2 km, Sudacho crossing: 11:10
- 15.4 km, Hisamatsucho crossing: 11:55
- 20.9 km, Midori 1-chome crossing: 12:45
- 24.7 km, Fukagawa 1-chome crossing: 13:20
- 29.2 km, Asakusabashi crossing: 14:00
- 33.5 km, Sukiyabashi crossing: 14:35
- 38.5 km, Shibakoen Ground-mae crossing: 15:15
- 42.195 km, Tokyo Station/Gyoko-dori Avenue: 16:10

Aid rules, from the official guidebook p.29 (PDF p.31) and the aid-station notice:

- All 15 stations provide drinking water. Pocari Sweat is placed at 5, 10, 15, 20, 25, 30, 35 and 40 km.
- Solid food is not available at every station. Sponge cake is listed at 20, 25 and 30 km; pickled plum at 22, 27 and 38 km; cream bread at 22 km; chocolate and ningyo-yaki at 27 km; chocolate at 38 km.
- Advance notice boards are placed 150–300 m before each station. The organiser asks runners to take water from the rear tables to reduce crowding at the front.
- Paper cups are collected separately. The bins at an aid station are only for waste produced at that station; runners may not deposit their own roadside rubbish there.
- The organiser states that it accepts no responsibility for water or food taken outside the official aid stations. Personal drinks stations are available only to elite athletes.
- The official aid-station notice states that allergen information is displayed for specified raw materials.

There are 13 medical stations on the course, plus medical stations at the start, in the finish area (Marunouchi, Babasaki Gate and Gyoko-dori) and at the 10.7 km finish. The official p.24 kilometre points are 5.1, 11.3, 15.5, 20.9, 23.2, 24.7, 27.0, 29.2, 31.4, 33.5, 35.9, 37.9 and 40.5 km; the venue names are on the official map and are not transcribed point by point here.

![Runners in the rain at the 2019 Tokyo Marathon](/media/routes/tokyo/runners-2019.jpg)

## Surface composition

The official material gives no surface split. What can be confirmed is that this is a city road course: the route uses ordinary streets in central Tokyo, crosses several bridges and junctions, and finishes on Gyoko-dori in front of Tokyo Station. Any "asphalt percentage" or "stone percentage" without an official source is left out.

The surface details supported by the official route and profile are:

- **Bridges and expansion joints.** The course crosses bridges including the Suidobashi and Ryogoku stretches.
- **Junctions and turnarounds.** The route turns around at Ueno-hirokoji, Tomioka Hachimangu and Tamachi; Ginza, Hibiya and Tamachi all lie on the course.
- **Elevation.** The official profile shows a start at about 40 m, a descent to near 0 m before 5 km, then small undulations at low altitude. The official profile is graphical only; the official material gives no cumulative ascent.

This page gives no official difficulty grade; the official route and profile support only the description "city road, low altitude". This page makes no shoe recommendation from surface information.

## Risks and escape points

- **Uneven cut-off rhythm.** The nine checkpoints run from 10:25 to 16:10. Converted to pace, segment 3 (9.2 → 15.4 km) is about 7:15/km, segment 7 (29.2 → 33.5 km) about 8:08/km and segment 8 (33.5 → 38.5 km) about 8:00/km — clearly tighter than the overall average.
- **Heat and humidity.** The 2026 race started at 09:10. Early March in Tokyo can still be cold, but it can also produce a daily maximum above 20°C. The weather window in this page reaches a modelled 22.8°C maximum, but that is a grid value, not a course measurement.
- **Cold rain.** The same window has a daily minimum of 2.2°C and a single day with 49.5 mm of precipitation.
- **Crowds.** 38,472 marathon runners started in 2026. The 4.9 km and 9.2 km checkpoints both fall inside the first 10 km.
- **Medical and withdrawal.** The organiser places 13 medical stations on the course, plus medical cover at the start, in the finish area (Marunouchi, Babasaki Gate and Gyoko-dori) and at the 10.7 km finish. To withdraw, the official instruction is to notify a race official, remove the barcode from the bib and hand it to the official, then proceed to the nearest checkpoint.
- **Sweep bus.** Runners who are cut off or who withdraw are taken by sweep bus to the finish area, or may return home from the nearest station. If baggage was checked in, the official instruction is that the runner must board the sweep bus to recover it at the finish; going straight to a station is not an option.
- **Off-course risk.** As re-verified on 8 November 2026 from the official traffic page, roads are closed for long periods, and pedestrians, bicycles and e-scooters may not cross the course; use footbridges or subway entrances instead. **Verification status:** a direct request still redirects to the event homepage, but a tool fetch with a desktop user agent returned the full traffic page, so the details above have been re-verified; the page is the 2026 edition.
- **Rule boundaries.** Personal drinks stations are for elite athletes only. The organiser accepts no responsibility for water or food taken outside official aid stations. Rubbish belongs in the bins at aid stations.
- **Two events on the early course.** The 10.7 km race starts from the same point and finishes at Nihombashi.

## Getting there

The access information below comes from the organiser and transport operators. All times are operator estimates, not measurements made by this page.

- **Nearest station to the start.** Tochomae Station on the Toei Oedo Line, Exit A4, about one minute on foot to the Tokyo Metropolitan Government Building start area (GO TOKYO official tourism page). This is the nearest station named by the official tourism page; the 2026 field was 39,000.
- **Finish.** Tokyo Station/Gyoko-dori Avenue. Tokyo Station is served by JR conventional lines and Shinkansen, and by the Tokyo Metro Marunouchi Line; the Tozai Line serves Otemachi, a short walk away (Tokyo Station City official access page).
- **Narita Airport → Tokyo Station.** About 60 minutes by Narita Express, about 90 minutes by Express Airport Narita, or about 80–110 minutes by airport limousine bus to the Tokyo/Nihombashi area (Tokyo Station City official page).
- **Haneda Airport → Tokyo Station.** Tokyo Monorail to Hamamatsucho, then about 35 minutes by Keihin-Tohoku or Yamanote Line; about 40 minutes by limousine bus to Tokyo Station Yaesu South Exit (same official page).
- **Packet pick-up.** Tokyo Big Sight South Exhibition Halls, 26–28 February 2026. The organiser does not allow race-day packet pick-up.
- **Race-day city transport.** As re-verified on 8 November 2026 from the official traffic page, the course and nearby roads are closed for long periods. Pedestrians must use footbridges or subway entrances to cross. The same page links a separate page for shuttle buses serving the Akihabara and Ueno areas (2026 edition).
- **Driving.** This page gives no driving recommendation. As re-verified on 8 November 2026 from the official traffic page, some Metropolitan Expressway entrances and exits are regulated and detours must follow police and staff instructions; the page is the 2026 edition.
- **After the finish.** The finish is in front of Tokyo Station, which is the main rail hub near the finish.

## Early-March season and weather

The 2026 race started at 09:10 on 1 March. To describe the same time window, this page queried the Open-Meteo historical archive for the Tokyo grid point at 35.6766N / 139.6911E (timezone Asia/Tokyo) from 2026-02-22 to 2026-03-02, nine days:

- Daily maximum: 12.1°C to 22.8°C, median 16.7°C.
- Daily minimum: 2.2°C to 11.8°C, median 7.8°C.
- One of the nine days had precipitation ≥1 mm and one had ≥5 mm; the largest daily total was 49.5 mm on 2026-02-25.
- On 2026-03-01 itself: maximum 16.7°C, minimum 6.9°C, precipitation 0.0 mm.

These four lines are **modelled historical values for a Tokyo grid point, not course measurements and not a race-day forecast**. This is a single grid-point value; the fields queried for this page are daily maximum temperature, daily minimum temperature and precipitation only.

Within the same week the archive contains a 2.2°C daily minimum and a 22.8°C daily maximum.

## Difficulty

The official documents publish no official difficulty grade, and this page gives none. **This site's rating**: a low-altitude, fast urban road marathon. The verifiable dimensions:

- Distance 42.195 km (official course page and official program guidebook p.24).
- The official profile shows a start at about 40 m, a drop to near 0 m before 5 km, then small undulations at low altitude.
- Official limit seven hours, with nine checkpoints from 4.9 km to the finish.
- 38,472 marathon starters in 2026.
- Three turnarounds and multiple bridges and junctions, on a city-road surface.
- A wide early-March weather window, with both cold rain and warming possible.

These conditions come from official pages and Open-Meteo data. The checkpoints at 9.2, 15.4, 29.2 and 33.5 km are the tighter ones when the official times are converted to pace.

The official material has no mandatory kit list; the course is a city road. Use the site's pace calculator for target-pace arithmetic and the marathon-distance entry for the training context.

## Verified and unverified

This page has not been run on the ground, so the two categories are kept separate.

**Verified, from official sources or the 8 November 2026 re-check:** the 2026 date and 09:10 start; seven-hour marathon limit and 16:10 finish; 42.195 km and the route order; JAAF certification and WA/AIMS recognition; the kilometre positions and times of nine cut-off checkpoints; the kilometre positions and water/Pocari/solid-food categories of 15 aid stations; the locations of 13 medical stations; start, finish and 10.7 km finish; the 39,000 field and entry fees; packet-pick-up dates and venue; 2026 starter/finisher numbers and champion times; airport-to-Tokyo-Station times, the nearest start station, and the traffic restrictions re-verified on 8 November 2026; the 2026-02-22 to 2026-03-02 Tokyo grid-point temperature and precipitation statistics; and the 2027 outline's date, start times, limits, field size, course and events (checked on 2026-11-08).

**Unverified, so no conclusion is offered:** official cumulative ascent and descent (not stated in the official material); surface percentages; measured race-day temperature, humidity and wind; actual queue times at aid stations; how often staff stop runners outside the formal checkpoints; the 2027 cut-off checkpoints, aid-station locations and supplies (the 2027 guidebook has not been checked); navigable course geometry; and any subjective judgement of how the course "feels" to run.

## Images and rights

**One photograph is recorded from a Wikimedia Commons file page (capture-round record, 6 November 2026).**

File-page record: runners in the rain at the 2019 Tokyo Marathon; author: nakashi; licence: CC BY-SA 2.0; date: 2019-03-03 (verified against the Commons file page and API on 2026-11-20). This page does not infer the street.

Channels used for the 6 November 2026 capture: the Wikimedia Commons `action=query&generator=search` API, `Special:MediaSearch`, `commons.wikimedia.org/w/index.php?search=` and direct `upload.wikimedia.org` URLs were all reachable. The filter is still three checks: readable licence, file page proving this event, and image matching the caption. Anything failing one is not used. Organiser photographs were not used. 

The file is unmodified apart from size and weight compression, and is not covered by this page's CC BY 4.0.

## Sources and reuse

The text was written independently by the RunUp editorial team from Tokyo Marathon Foundation public material and Open-Meteo data, and is licensed CC BY 4.0. Event names, official marks, official route text and official PDFs remain the property of the organiser. This page links to official files rather than redistributing course maps, guidebooks or any track.

This page cites 12 sources: the 2026 race-outline PDF, the official course page, the 2026 official program guidebook course map, the 2026 official program guidebook race-day pages, the 2026 aid-station notice and PDF, the 2026 results page, the GO TOKYO start-access page, the Tokyo Station City access page, the official traffic-control page, Open-Meteo historical weather, the 2027 race-outline page and `photo-tokyo-2019` (the 2019 rain photograph). The map anchor additionally cites the RunUp editorial method note. Supporting claims and check dates appear in the source list at the foot of the page. Open-Meteo data is used under CC BY 4.0 and credited here; the image licence is as recorded on its Commons file page.
