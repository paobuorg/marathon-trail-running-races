---
entityId: route:shanghai
locale: en
title: "Shanghai Marathon: Bund Bull to Xujiahui Sports Park"
summary: "The 2026 Shanghai Marathon will be held on 6 December, starting in six guns from the Bund Bull and finishing at Xujiahui Sports Park on Zhongshan South 2nd Road, via Nanjing Road, Jing'an Temple, Huaihai Road, Xintiandi, the Site of the First CPC Congress, the Huangpu riverside, Longteng Avenue, Longhua Temple and Longhua Martyrs' Cemetery. The organiser has published a 2026 course map and start/finish diagrams; this page records the 5-40 km cut-offs, two aid-station types and the six-gun time gaps, without treating the images as navigable or redistributable tracks."
aliases: ["Shanghai Marathon: Bund Bull to Xujiahui Sports Park"]
authors:
  - runmap-editorial
reviewers:
  - runmap-editorial
translationStatus: reviewed
---

## Verification status
- Course-change check: `courseChanges` has one 2026 `new-course` entry, sourced to the official course map. The 2025 edition remains as a comparison, but the cut-offs, finish gate wording and aid numbers of the two editions are not mixed.

This page is fixed to **2026-shanghai-official-course**, for the Shanghai Marathon on **Sunday 6 December 2026**; verification date **2026-11-21**. The official course map, start diagram and finish diagram have now been published on the event detail page. The "coming soon" state seen on 2026-11-08 has been overturned; the old state remains in the source verification note and is not current fact.

The 2026 race has **30,000 marathon runners** and **20 wheelchair athletes**; the wheelchair race is not open to public entry. The 2026 competition rules list only these two events, so the 42.195 km, segment, aid and cut-off data on this page describe the marathon only.

The geometry conclusion remains **no usable track**. The organiser published a 5686x7885 course-map JPEG, a 3088x2666 start diagram and a 3088x2666 finish diagram, not GPX, KML or GeoJSON. This page records the URLs, dimensions and visible map facts as sources and external links, but does not treat them as navigable geometry: `geometryAccess` remains `unavailable`, and no route line is traced from the images.

- Official static course map: [2026 official route-map and start/finish plan page](https://static.shang-ma.com/web/matchDetail/index.html?eventId=232&eventTtype=2). This is a JPG/web map, not GPX/KML/GeoJSON; it is linked only and not counted as an official geometry entry.

The event body text used here is on `shang-ma.com`, with the detail page at `static.shang-ma.com/web/matchDetail/index.html?eventId=232`. The page is a single-page app (SPA), so raw HTML returns only a shell. This page was read by rendering it in a browser and clicking the "Competition rules / Course map / Start diagram / Finish diagram" tabs. That reproduction path may break when the site changes, so it is recorded separately.

## What this course is

The Shanghai Marathon is a **point-to-point city road marathon**, not a loop. The 2026 edition starts at the Bund Bull in Huangpu District and finishes on Zhongshan South 2nd Road at Xujiahui Sports Park. The official course description names the Bund, Nanjing Road Pedestrian Street, Jing'an Temple, Huaihai Road, Xintiandi, the Site of the First National Congress of the CPC, the Huangpu riverside, Longteng Avenue, Longhua Temple and Longhua Martyrs' Cemetery. The organiser also keeps the qualification that detailed routing is subject to pre-race publication; the 2026 course map is that pre-race document, but it is an image, not a navigable coordinate sequence.

The course is defined by urban landmarks rather than natural terrain: the Bund waterfront, Nanjing Road, Jing'an Temple, Huaihai Road, Xintiandi and the CPC site, the Huangpu riverside promenade, the river views on Longteng Avenue, Longhua Temple and Longhua Martyrs' Cemetery, and the finish inside Xujiahui Sports Park. There is no trail, mountain pass or forest track; there are dense turns, narrow riverside sections, a split start and finish, and the problem of late waves being compressed by absolute cut-off times. Treating "city streets" as automatically "easy" misses these organisational difficulties.

The difference from 2025 is not only the year. The 2025 police notice described the finish entrance as "Gate 12 of Shanghai Stadium"; the 2026 participant guide describes the finish flow as entering the stadium through **Passage 4**, passing the sponsor area and exiting through **Passage 1**. These are two official texts from two editions; Gate 12 cannot be carried over to the 2026 flow. The course description also adds the Site of the First CPC Congress, Longhua Temple and Longhua Martyrs' Cemetery, so this page does not copy the 2025 street-by-street description unchanged.

The 2026 race uses **six gun starts**, not three:

| Gun | Time | Group |
| --- | --- | --- |
| 1 | 06:45 | Wheelchair marathon |
| 2 | 07:00 | Elite, pre-qualified and corral A |
| 3 | 07:04 | Corral B |
| 4 | 07:10 | Corral C |
| 5 | 07:19 | Corral D |
| 6 | 07:26 | Corral E |

That table directly determines each runner's available time. From the 07:00 gun to the 13:30 finish cut-off is 6:30; corral B has 6:26, C 6:20, D 6:11 and E only 6:04. The 2026 finisher medal line is **6:00**, so corral E has only four minutes between the medal line and the absolute finish cut-off. This is not simply "26 minutes less because you start 26 minutes later"; the medal line arrives first and the finish cut-off later.

On series status, Shanghai passed stage one of the Abbott World Marathon Majors candidate assessment at its second assessment in November 2025 and moved to stage two. The official text says Shanghai must meet all criteria for a second consecutive year at its next marathon on 6 December 2026, and would join the Majors in 2027 if successful. As of 2026-11-21 the assessment is still in progress and no 2026 result has been published. This page therefore neither calls Shanghai an existing Major nor treats "candidate" as "already selected".

## Official figures

The distance figure is consistent in the 2026 competition rules and the official participant guide: **42.195 km**. The rules mark the half-marathon split at 21.0975 km, twice which is the full distance; the guide states 42.195 km directly. No alternative full-marathon distance appeared, so the entity card uses 42,195 m.

The elevation wording needs a correction from the 2025 page. The 2025 page said the official route map was a flat diagram without elevation data. The 2026 official map **does include an altitude profile**: the vertical axis is labelled 5, 10, 15 and 20 m, the horizontal axis 0-42 km. But the image gives no cumulative ascent, cumulative descent, highest point or gradient figures. The profile shows short rises and falls on low-lying urban ground; it cannot be used to compute total ascent. The entity card therefore keeps `elevationGainMeters` as `null`, and `elevationMethod` records "the map has a 5-20 m vertical-axis profile but publishes no cumulative ascent or descent".

| Material | Distance | Ascent / descent | What it can prove |
| --- | --- | --- | --- |
| 2026 competition rules | 42.195 km, with 21.0975 km half split | Not published | Date, events, field, start/finish, cut-offs, aid stations, medal line |
| 2026 official course map | 5-42 km markers and finish | 5-20 m profile, no cumulative values | 5-40 km cut-off times, visible landmarks, start/finish layout |
| 2026 official participant guide | 42.195 km | Not published | Six gun times, corral access, bag trucks, energy supplies, finish flow, forecast |

None of the three gives a measurement date, measurement agency or certificate number. The rules only state technical certification by the Chinese Athletics Association and conduct under World Athletics rules. This page can therefore confirm "the official published distance is 42.195 km", but cannot confirm "this 2026 course was measured to A-grade by a named agency on a named date". The two are not the same claim.

## Segment notes

No street-by-street, metre-by-metre text route has been published; the 2026 map puts street names, kilometre markers and landmarks on one image. The table below only combines the main visible corridors with the official cut-off points. Segment distances come from subtracting adjacent kilometre markers. It is not a survey and does not pin a street name to the metre.

| Segment | Range | Distance | Main visible corridor | Official cut-off |
| --- | --- | --- | --- | --- |
| S1 | Start to 5 km | 5 km | Bund - Renmin Road - Henan Road - Nanjing East Road - Jiujiang Road - Nanjing West Road | 5 km 08:10 |
| S2 | 5-10 km | 5 km | Nanjing West Road - Huashan Road - Changshu Road - Huaihai Middle Road | 10 km 08:50 |
| S3 | 10-15 km | 5 km | Huaihai Middle Road - Xintiandi / First CPC Congress site - Xizang South Road | 15 km 09:35 |
| S4 | 15-20 km | 5 km | Xizang South Road - Zhizaoju Road - Gaoxiong Road - Bansongyuan Road / Waima Road | 20 km 10:20 |
| S5 | 20-25 km | 5 km | Waima Road - Longhua East Road - Jiangbin Road / Ruining Road | 25 km 11:00 |
| S6 | 25-30 km | 5 km | Ruining Road - Longteng Avenue southbound | 30 km 11:45 |
| S7 | 30-35 km | 5 km | Longteng Avenue southern section, turnaround near 35 km | 35 km 12:30 |
| S8 | 35-40 km | 5 km | Longteng Avenue northbound - Longhua East Road - Longhua Road / Longhua Temple | 40 km 13:15 |
| S9 | 40 km to finish | 2.195 km | Longhua West Road - Zhongshan South 2nd Road - Xujiahui Sports Park | Finish 13:30 |

The nine segments add up to 5 x 8 + 2.195 = 42.195 km, closing with the official distance. That closure checks arithmetic, not street assignment. After 15 km the map links the Huangpu riverside, Bansongyuan Road, Waima Road, Longhua East Road, Longteng Avenue and the Longhua area into one continuous southbound corridor; near 35 km the route turns back, then runs north on Longteng Avenue to Longhua East Road and into Longhua Road and Longhua West Road. The exact metre of the turnaround, the gradient of each segment and the width of each road are not individually labelled on the official image, and this page does not infer them.

Read as a rhythm, the first half is the commercial street sequence of the Bund, Nanjing Road, Jing'an Temple and Huaihai Road: many turns, changing road widths, and a start field that has not fully stretched out. The middle turns into the Huangpu riverside and Expo area, with more open views but possible narrow sections on the promenade. The late section runs south on Longteng Avenue and turns back, so runners meet two-way traffic on the same road. The final section passes Longhua Temple and Longhua Martyrs' Cemetery into Xujiahui, where city roads meet the stadium area and the final turns and crowd density need attention.

## Aid stations and cut-offs

The 2026 participant guide gives the most detailed aid description. Drink/water stations begin at 5 km and continue every 5 km through 40 km; water/sponge stations begin at 7.5 km and continue every 5 km, providing drinking water and soaked cooling sponges. Energy supplies are allocated by segment: bananas at 12.5, 15, 32.5 and 37.5 km; small cakes at 17.5 and 35 km; SiS gels at 25 km; daily dark chocolate at 27.5 and 40 km.

Cut-offs have two layers of official text. The 2026 competition rules start their table at 10 km: 10 km 08:50, 15 km 09:35, 20 km 10:20, 25 km 11:00, 30 km 11:45, 35 km 12:30, 40 km 13:15, finish 13:30. The 2026 official course map separately marks **5 km at 08:10**, which the rules do not list. Both are 2026 official sources; this page puts them side by side, neither deleting the 5 km point nor moving 10 km to 08:10.

| Kilometre | Station / supply | Cut-off |
| --- | --- | --- |
| 5 km | Drink / water | 08:10 (map only) |
| 7.5 km | Water / sponge | None |
| 10 km | Drink / water | 08:50 |
| 12.5 km | Water / sponge; banana | None |
| 15 km | Drink / water; banana | 09:35 |
| 17.5 km | Water / sponge; small cake | None |
| 20 km | Drink / water | 10:20 |
| 22.5 km | Water / sponge | None |
| 25 km | Drink / water; SiS gel | 11:00 |
| 27.5 km | Water / sponge; dark chocolate | None |
| 30 km | Drink / water | 11:45 |
| 32.5 km | Water / sponge; banana | None |
| 35 km | Drink / water; small cake | 12:30 |
| 37.5 km | Water / sponge; banana | None |
| 40 km | Drink / water; dark chocolate | 13:15 |
| Finish | Finish services and medical | 13:30 |

Cut-offs are on natural clock time, not extended by an individual's net time. The 2026 medal line is **6:00**; the 2025 line was 6:15, and the two cannot be mixed. From the six-gun table, corral A has 6:30 to 13:30, B 6:26, C 6:20, D 6:11 and E 6:04. For an E-corral runner targeting the medal, the real buffer is four minutes; start queues, bag drop, security, aid stops and wet pavement all eat into it.

On medical cover, the 2026 rules only confirm "fixed medical points at the start, finish and along the course, with ambulances following the runners". They do not publish the 2026 totals for medical stations, ambulances, AEDs or designated hospitals. The 2025 post-race figures of 43 medical stations, 36 ambulances and 275 AEDs are 2025 statistics and are not presented here as 2026 capacity.

![Runners on Wanping South Road at the 2016 Shanghai International Marathon](/media/routes/shanghai/wanping-road-2016.jpg)

## Surface and terrain

The official documents do not publish the proportion of asphalt, concrete, stone or synthetic surface, nor friction, smoothness or construction state, so this page gives no percentages. What can be confirmed is that the route consists of named city roads and a section of Huangpu riverside promenade, passing the Bund, Nanjing Road, Huaihai Road, Xintiandi, the riverside, Longteng Avenue and the Longhua area. The official text does not state the promenade's surfacing or how it connects to adjacent roads, so "promenade" cannot automatically be read as dirt or synthetic track.

On terrain, the 2026 official map gives a 5-20 m vertical-axis altitude profile. The curve stays near the low values for most of the route and shows short spikes in a few places; the image gives no cumulative ascent, cumulative descent or gradient figures. Shanghai sits on the Yangtze delta plain, but that is geographic background, not a measurement of this course. This page can say "the course has short rises and falls on low-lying urban ground", but cannot say "absolutely flat", nor integrate the profile into a "total ascent of 80 m" or similar number.

The difficulty of city roads is not gradient but transition: many right-angle turns from the Bund to Nanjing Road, changing road widths around Huaihai Road and Xintiandi, possible narrow sections on the Huangpu promenade, a turnaround on southern Longteng Avenue, and turns and crowd density where Longhua meets Xujiahui. Race-day surface is subject to pre-race notices and on-site direction; rain further reduces grip at turns, aid stations and the turnaround.

## Risks and exit points

The first risk is the absolute cut-off for late corrals. The 2026 race uses six guns; corral E starts at 07:26 and the finish closes at 13:30, leaving 6:04. The official medal line is 6:00, leaving four minutes. Treating "6:30" as a window that applies to everyone is the most common 2026 misread. Start queues, bag-truck closure, security, aid stops and wet pavement all compress the margin; even a runner targeting only a finish must treat 13:30 as a hard boundary.

The second risk is start and finish organisation. From 05:30 the start area progressively applies crowd control; the check area opens at 05:30 and bag trucks close at 06:45, with the official advice to enter the check area before 06:30. Corrals A-E use different road junctions, and a wrong entrance means a detour. Bag trucks are numbered by corral: A1-A3 on Hankou Road, B1-B5 on Jiujiang Road, C1-C7 on Dianchi Road, D1-D6 on Beijing East Road and E1-E8 on Suzhou South Road. At the finish, runners enter Shanghai Stadium through Passage 4, collect the medal and finish bag, pass the sponsor area and exit through Passage 1. Bag tents A1-A3 and B1-B2 exit via Xujiahui Sports Park Gate 1; the others exit via Gate 2. Spectators should follow the finish diagram and on-site direction and not walk against the course.

The third risk is weather and city traffic. The official guide on 21 November forecast **light rain, 10-15 C**, with the latest forecast prevailing. Rain makes the start wait, turns, turnaround and finish collection colder and more slippery; a disposable poncho, anti-chafe product, dry clothes and a warm layer after the finish are more useful than chasing minimal weight. On city traffic, the 2026 traffic-control notice had not been published as of the verification date; this page cannot carry over the 2025 closure times. On race morning, metro is the more controllable option; driving and taxis must be rechecked against the current notice.

Medical and exit information is limited to what the sources support: fixed medical points at start, finish and along the course, with ambulances following; exiting at a cut-off point, accepting on-site medical care, or using metro after the finish. The official sources do not publish a nearest exit for every kilometre or a list of mid-course metro stations, and this page does not invent them. The Longteng turnaround and narrow riverside sections carry two-way traffic; crossing or leaving against the flow increases collision risk.

## Getting there

**Airports.** Pudong Airport is served by Metro Line 2 (Pudong Airport station, 06:00-22:30) and the Maglev (Pudong Airport-Longyang Road 07:02-21:42; Longyang Road-Pudong Airport 06:45-21:40). Hongqiao Airport is served by Metro Line 2 at Terminal 2 and Line 10 at Terminals 1 and 2, both 06:00-22:30; the city airport line leaves Hongqiao Terminal 2 from 05:45 to 22:00 about every 15 minutes. Airport Line 1 links Hongqiao Transport Hub East with Pudong Airport (06:00-23:00); Line 4 runs to Shanghai Railway Station North Square (07:00-23:00), Line 7 to Shanghai South Railway Station (07:30-23:00), and the overnight service to Hongqiao Transport Hub East (23:00-05:30). These times come from the Shanghai government airport transport notice; check live departures before travel.

**Rail.** Shanghai Railway Station North Square and Shanghai South Railway Station are the terminals of Airport Lines 4 and 7, useful for direct transfers with luggage; Hongqiao Transport Hub East has the overnight service and Airport Line 1. Hongqiao Airport and Hongqiao Railway Station share the Hongqiao hub, connected to the city by Metro Lines 2 and 10. On race morning, metro into the city is preferable to a taxi crossing the Bund-Nanjing Road control area.

**City to the start.** The 2026 official guide advises runners in corrals A, B, C and D to take Metro Line 2 or 10 to East Nanjing Road and walk about 10-15 minutes to the check area; corral E runners should take Line 10 or 12 to Tiantou Road, with a longer walk and more time. The start area applies crowd control from 05:30, the check area opens at 05:30 and bag trucks close at 06:45; the guide advises entering the check area before 06:30. The guide does not give race-day first trains, extra services or station closures, and this page does not fill in operator numbers.

**Start entrances and bag drop.** Corral A enters at Hankou Road/Henan Middle Road, with trucks A1-A3 on Hankou Road; B at Jiujiang Road/Henan Middle Road, with B1-B5 on Jiujiang Road; C via Nanjing East Road/Henan Middle Road then Jiangxi Middle Road and Dianchi Road, with C1-C7 on Dianchi Road; D at Beijing East Road/Henan Middle Road, with D1-D6 on Beijing East Road; E at Henan Middle Road/Suzhou South Road, with E1-E8 on Suzhou South Road. After entering, runners pass security and identity checks, bag drop and corral warm-up. Do not cross into another corral, and do not push into a front corral if late.

**Finish exit.** After finishing, enter Shanghai Stadium through Passage 4, collect the medal and finish bag, pass the sponsor area and exit through Passage 1. Outside, follow the internal road west and collect bags by tent number: A1-A3 and B1-B2 exit via Xujiahui Sports Park Gate 1 and go north on Caoxi North Road to Metro Lines 1 and 4 at Shanghai Indoor Stadium; B3-B5, C1-C7, D1-D6 and E1-E8 exit via Gate 2 and go west on Lingling Road to the same station. Volunteers direct the flow; follow the numbers and do not cut back across the stream.

**Race pack.** The 2026 race pack collection runs 3-5 December, 09:30-19:30, at the Shanghai World Expo Exhibition & Convention Center, 850 Bocheng Road. Bring the original identity document used at registration; packs are collected in person, not mailed, and not available on race day. The 2026 rules do not repeat metro or bus routes; the 2025 collection guide's transport information is only an old-edition reference, and the 2026 collection notice should be checked before travel.

**Driving and race day.** Driving to the start is not recommended. The 2026 traffic-control notice had not been published as of 2026-11-21; the 2025 closure times, bus suspensions and diversions cannot be carried over. The start area will be controlled from early morning and the finish area will also be closed. Parking at a hotel or an outer metro station and continuing by metro is more controllable.

## Season and weather

The 2026 edition is on 6 December, early winter in Shanghai. The official participant guide on 21 November forecast **light rain, 10-15 C**, with the explicit note that the latest pre-race forecast prevails. This is a pre-race forecast, not a post-race measurement; it feels cool before the start, so bring an old jacket or poncho that can be discarded, wear it through warm-up and take it off before the gun.

This page also queried the Open-Meteo historical reanalysis for the same grid point on 6 December. The request used Shanghai coordinates 31.2304N, 121.4737E; the returned grid point was **31.247803N, 121.5E at 5 m elevation**. Across the eleven 6 December days from 2015 to 2025, daily maximum temperature ranged from 10.1 to 18.0 C with a median of 12.6 C; daily minimum ranged from -1.3 to 7.2 C with a median of 4.6 C; two of the eleven days recorded at least 1 mm of precipitation (6.1 mm in 2015 and 23.5 mm in 2018). These numbers place "10-15 C, possibly rainy" inside the historical range rather than outside it.

This must be emphasised: these are **grid-point historical statistics, not course measurements**. The grid point does not represent the microclimate of the Bund, Nanjing Road, the riverside promenade or Xujiahui Sports Park; urban heat, river breeze, building shade and the start hour all create differences. This page did not retrieve humidity, wind speed, apparent temperature or hourly data, so it does not state "the humidity was X" or "the wind came from Y". Check the official update before the race.

## Difficulty rating

**Site rating (not official; not a course certification by the organiser or World Athletics).** On the verified data, this is a medium-difficulty city road marathon: 42.195 km; the official map has a 5-20 m vertical-axis profile but no cumulative ascent or descent, so elevation cannot be quantified; technicality is lower than a trail race, with no mandatory kit or navigation; but six guns, dense turns, narrow riverside sections, the Longteng turnaround and a split start/finish add organisational and pacing cost.

Cut-offs are part of the difficulty. The 2026 medal line is 6:00, tighter than the 2025 line of 6:15; corral E starts at 07:26 and has only 6:04 to 13:30, leaving four minutes to the medal line. For runners under four hours, the cut-off is not a pressure; for runners between 5:30 and 6:00, a late start, queues, aid stops, wet pavement and low temperature all eat the margin. Treating "6:30" as a universal window is the most common 2026 misread.

The official profile shows short rises and falls on low-lying urban ground, but publishes no total ascent; city turns, the turnaround, narrow sections and crowd density do not enter an ascent statistic. **Site rating** therefore does not equate "plain" with "no difficulty": this course is "long, with a tight medal line, low technicality and high organisational dependence".

## Verified and not verified

**Verified (from successfully read official or authoritative pages):**

- The 2026 edition is on 2026-12-06; wheelchair 06:45, marathon 07:00; 30,000 marathon runners and 20 wheelchair athletes.
- Start at the Bund Bull (Zhongshan East 1st Road); finish at Zhongshan South 2nd Road (Xujiahui Sports Park).
- Six guns: 06:45 wheelchair, 07:00 elite/pre-qualified/A, 07:04 B, 07:10 C, 07:19 D, 07:26 E.
- The official course description passes the Bund, Nanjing Road Pedestrian Street, Jing'an Temple, Huaihai Road, Xintiandi, the Site of the First CPC Congress, the Huangpu riverside, Longteng Avenue, Longhua Temple and Longhua Martyrs' Cemetery.
- The 2026 course map marks 5 km 08:10, 10 km 08:50, 15 km 09:35, 20 km 10:20, 25 km 11:00, 30 km 11:45, 35 km 12:30, 40 km 13:15 and finish 13:30.
- Drink/water stations from 5 km every 5 km; water/sponge stations from 7.5 km every 5 km; energy points and products recorded point by point from the official guide.
- Bag trucks close at 06:45; finish flow enters Shanghai Stadium through Passage 4 and exits through Passage 1; bag tents leave via Xujiahui Sports Park Gate 1 or Gate 2 by number.
- The 2026 medal line is 6:00; the 2025 line was 6:15, and the editions differ.
- AbbottWMM candidate assessment is in stage two; the 2026 edition is the second consecutive assessment year, and no result had been published as of the verification date.
- The 2026 official guide forecast light rain, 10-15 C; the 2015-2025 6 December grid point ranged 10.1-18.0 C maximum, -1.3-7.2 C minimum, with 2/11 days at least 1 mm precipitation.

**Not verified or unavailable:**

- Official GPX, KML, GeoJSON or any redistributable coordinate sequence: not found; the official material is a course map and start/finish diagrams only.
- Cumulative ascent, cumulative descent, highest point, gradient: the official map has a 5-20 m vertical-axis profile but no cumulative values; the entity field is `null`.
- Street names matched to every kilometre at metre level: the official image shows main corridors and kilometre points, but no street-by-street text table; this page does not pin street names to the metre.
- 2026 traffic-control notice: not published as of 2026-11-21; the 2025 notice cannot be carried over.
- 2026 totals for medical stations, ambulances, AEDs and designated hospitals: the 2026 rules only state fixed medical points and following ambulances, without totals.
- 2026 surface proportions, smoothness and promenade paving: not published.
- 2026 race-day first trains, extra services and station closures: not given in the participant guide and not retrieved from the operator.
- Actual race-day feel, crowding and aid waiting times: the author did not run it.
- Geometric accuracy and licence of the 2026 official images: readable, but no redistributable licence.

## Images and rights

**One photograph, from Wikimedia Commons; author, licence and date verified.**

2016 Shanghai International Marathon, Wanping South Road section; author: Commons user 中日韩越的汉字; licence: CC BY-SA 4.0; date taken: 2016-10-30 (rechecked against the Commons file page and API on 2026-11-20). The frame shows runners at the 2016 Shanghai International Marathon on Wanping South Road. The 2026 official course map mainly marks Longhua Road, Longhua West Road and Zhongshan South 2nd Road in the late section and does not clearly mark Wanping South Road; this page therefore treats the photograph only as a 2016 historical scene, not as proof of the 2026 course.

The 2026 official course map, start diagram and finish diagram are organiser-copyright images without a redistributable licence. This page records their URLs, dimensions and visible facts, but does not copy the originals into `public/media` and does not embed them. Readers can open the official links. Official race photographs also lack a CC licence and were not used.

The photograph's content was not modified; it was only resized and compressed. The CC BY 4.0 licence for this page's text does not apply to it.

## Sources and reuse

This page uses **11 sources**, including one photograph and one map-anchor method source. They cover the 2026 competition rules, the 2026 official course map and start/finish diagrams, the 2026 official participant guide, the Abbott World Marathon Majors assessment announcement, the Shanghai airport transport notice, the Open-Meteo 2026 climate query, the 2025 competition rules, the 2025 police traffic-control notice, the 2025 post-race medical statistics, and the 2016 Wanping South Road photograph (`photo-shanghai-2016`). The source list appears at the end of the page; each source's `claims` contains only what that page actually supports, with dates, numbers and conflicts left as published.

The two editions are placed side by side rather than reconciled: the 2025 police notice says Shanghai Stadium Gate 12, the 2026 guide says finish flow enters through Passage 4 and exits through Passage 1; the 2025 medal line is 6:15, the 2026 line is 6:00; the 2025 post-race medical count is 43 stations, 36 ambulances and 275 AEDs, while the 2026 rules publish no comparable totals. This page states the differences and does not extrapolate 2025 numbers to 2026 or average the two into a "middle value".

This page offers no GPX, KML, GeoJSON or track download, and no "run the old route" navigation. The copyright in the official course map, start/finish diagrams and traffic-control graphics belongs to the organiser or issuing authority; this page only quotes text and organises facts, and does not redistribute the images. If an official redistributable geometry or clearly licensed route file appears later, its link, licence and edition must be rechecked before changing `geometryAccess` from `unavailable` to `official-link` or `redistributable`; even then, this site will not draw a line or package a track.

Text licence: CC BY 4.0, permitting reuse, adaptation and republication with attribution to "跑起来 / RunUp" and a link back to this page. Reuse must not remove the qualifications "not tested", "not published by the organiser" or "grid point, not course measurement", and must not fill an unpublished ascent with zero. If the organiser requests a correction or removal, the latest organiser notice prevails.
