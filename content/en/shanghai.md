---
entityId: route:shanghai
locale: en
title: "Shanghai Marathon: Bund Bull to Xujiahui Sports Park"
summary: "The 2025 Shanghai Marathon was held on 30 November, starting in three waves from the Bund Bull and finishing at Gate 12 of Shanghai Stadium in Xujiahui Sports Park, via Nanjing Road, Jing’an Temple, Huaihai Road, Xintiandi, the Huangpu riverside promenade and Longteng Avenue. The organiser published a route map and kilometre-level aid and cut-off points, but no redistributable GPX."
aliases: ["Shanghai Marathon: Bund Bull to Xujiahui Sports Park"]
authors:
  - runmap-editorial
reviewers:
  - runmap-editorial
translationStatus: reviewed
---

## Check status

This page pins the **2025-shanghai-official-course** version of the Shanghai Marathon, held on **30 November 2025**. It was verified on **2026-11-06**. The 2026 edition has already been announced for **6 December 2026**; its competition rules, entry notes and route map have also been published, with a marathon field of 30,000 and a 5 km fitness run held separately on 5 December and sharing the same finish. The 2026 rules add the Site of the First National Congress of the Communist Party of China, Longhua Temple and the Longhua Martyrs’ Cemetery as route landmarks, and describe the finish as “Zhongshan South Second Road (Xujiahui Sports Park)”, which is not identical to the “Gate 12 of Shanghai Stadium” wording in the 2025 police notice. This page pins the completed 2025 edition, does not mix in 2026 data, and does not copy 2025 figures forward as if they were already valid for 2026.

The 2025 start sequence was: wheelchair marathon at 06:45; marathon and fitness run first wave at 07:00; corral C at 07:10; corrals D and E at 07:20. The marathon started at the Bund Bull (外滩金牛广场) and finished at Xujiahui Sports Park; the police traffic notice specifies Gate 12 of Shanghai Stadium as the finish entrance. The fitness run finished at the Shanghai Exhibition Centre.

The official domain also needs an honest note. The task-specified `shanghai-marathon.com` returned a DNSPod “domain expired” notice at the verification date, not event content; this is an entry check and is not counted among the sources below. The live official entry point is `shang-ma.com`, with event pages served from `static.shang-ma.com`. The 2025 competition-rules page at `static.shang-ma.com/web/matchDetail/index.html?eventId=224` was readable. The event app’s detail and news-list APIs required login or an encrypted request body; this page did not bypass those controls and instead used the readable official rules page, Shanghai municipal government and sports bureau pages, and the Shanghai Public Security Bureau notice. The domain difference does not change the race figures, but it does change the reproduction path for “what the official site said”, so it is recorded separately.

The geometry conclusion is **no usable geometry**. The organiser published a route map image, start and finish area diagrams and a text description; the police notice published an ordered list of street names. This page found no official GPX, KML or GeoJSON download link, and no redistributable coordinate sequence. It therefore draws no course line, adds no points and stitches no old-year track. The map shows only an editorial overview anchor, which is not the start, the finish or any kilometre position.

Neither the author nor this site has run the 2025 course on race day, and no course measurement was performed. Every distance, time, aid and medical figure below comes from the public pages listed at the end. Weather figures come from a reanalysis grid, not from instruments beside the course. Where the organiser published no figure, the page says “not published” rather than inventing an estimate.

## What this course is

The Shanghai Marathon is a **point-to-point urban road marathon**, not a loop. It starts at the Bund Bull in Huangpu District, runs south along Zhongshan East 1st Road and Zhongshan East 2nd Road, turns through Renmin Road, Henan South Road and Henan Middle Road, then joins Nanjing East Road and Nanjing West Road. It later turns onto Huashan Road, Changshu Road and Huaihai Middle Road, passes the Xintiandi area, and continues through Xizang South Road, Gaoxiong Road, Zhizaoju Road, Longhua East Road and Bansongyuan Road. It then links Miaojiang Road, Lujiabang Road, Waima Road and the Huangpu Riverside Promenade, before taking Longhua East Road, Furun Road, Jiangbin Road and Ruining Road into Longteng Avenue. The final section uses Fenggu Road, Longheng East Road, Wanping South Road, Longhua Road, Longhua West Road and Zhongshan South 2nd Road to enter Gate 12 of Shanghai Stadium and the Xujiahui Sports Park finish.

The official competition rules summarise the route as passing the Bund, Nanjing Road Pedestrian Street, Jing’an Temple, Huaihai Road, Xintiandi, Longteng Avenue and Longhua Road, and state that the detailed route is subject to publication before the race. The Shanghai Public Security Bureau traffic notice gives the full street order and identifies three turnarounds: Bansongyuan Road at Huayuangang Road, Longteng Avenue at Jinmugang Road, and Fenggu Road at Yunjin Road. Read together, the two documents put the course along the west bank of the Huangpu River: first north into the traditional commercial districts, then south back to the riverside and into the stadium cluster. The streets listed lie in the Huangpu, Jing’an and Xuhui districts, but that district reading is editorial — the notice does not label districts street by street.

The 2025 field was 23,000 marathon runners, 15,000 fitness-run runners and about 20 wheelchair athletes; the pre-race press material gives 19 wheelchair athletes. Both numbers are official, so both are retained here rather than collapsed into one. The marathon and fitness run shared the 07:00 first gun, but the fitness run turns towards the Shanghai Exhibition Centre and does not enter the Xujiahui finish. The distance, segment and aid tables on this page therefore describe the marathon only.

The identity of this course comes from civic landmarks rather than natural terrain: the Bund waterfront, Nanjing Road Pedestrian Street, Jing’an Temple, Huaihai Road, Xintiandi, the Huangpu Riverside Promenade, the river views along Longteng Avenue and the Xujiahui Sports Park. There is no trail section, no mountain pass and no forest track. There are, however, dense turns, three out-and-backs, narrow stretches on the riverside promenade, and the logistics of a split start and finish. Treating “city streets” as automatically easy ignores those organisational difficulties.

The 2025 race marked the 29th year of the event. It is the only Abbott World Marathon Majors candidate race in China, and the event carried World Athletics Platinum Label status. That context matters for the density of the field and the level of officiating, but it does not turn the course into a closed-loop or remove public-road constraints.

## Official figures

The distance is consistent across three public documents at 42.195 km. The 2025 competition rules mark the halfway point at 21.0975 km, so the full distance is twice that (21.0975 × 2); the official pre-race guide says “42.195 km”; the Shanghai Administration of Sport post-race notice describes a service network covering 42.195 km. No competing full-marathon distance appears, so the entity card uses 42,195 metres and there is no conflict to adjudicate.

Elevation is different. The competition rules, the pre-race guide, the post-race notice and the World Athletics report publish no cumulative ascent, cumulative descent, highest point or elevation profile. The official route map is a flat schematic and carries no height data. The entity’s `elevationGainMeters` and `elevationMethod` therefore remain `null`, and the table says “not published”. Here `null` means “the organiser published no figure”, not “the climb is zero”. Filling in zero because Shanghai is on a plain would substitute geographic general knowledge for race data.

| Source | Distance | Ascent | Descent | Highest point |
| --- | --- | --- | --- | --- |
| 2025 competition rules (published June) | 42.195 km (rules mark 21.0975 km halfway; full distance is twice that) | Not published | Not published | Not published |
| Republished official pre-race guide (29 November) | 42.195 km | Not published | Not published | Not published |
| Shanghai Administration of Sport post-race notice (1 December) | 42.195 km (“service network covering 42.195 km”) | Not published | Not published | Not published |

None of the three documents gives a measurement date, a surveying body or a certificate number. They state that the race is technically certified by the Chinese Athletics Association and conducted under World Athletics rules. This page can therefore confirm that the official public distance is 42.195 km, but it cannot confirm that the 2025 course was measured to a particular grade by a named body on a particular date. Those are separate claims.

## Segments

The only official kilometre points usable for segmentation are aid stations and cut-off points: drink stations from 5 km every 5 km, water stations from 7.5 km every 5 km through 40 km, and cut-off points that begin at 5 km in the November guide or 10 km in the June rules. The organiser published no street-by-street kilometre table and no elevation at each station. The table below therefore uses official kilometre points only; segment distances are obtained by subtracting adjacent cumulative points, not by guessing kilometre positions from street names.

| Segment | Interval | Segment distance | Ascent / descent |
| --- | --- | --- | --- |
| S1 | Start → 10 km cut-off | 10 km | Not published / not published |
| S2 | 10 km → 20 km cut-off | 10 km | Not published / not published |
| S3 | 20 km → 30 km cut-off | 10 km | Not published / not published |
| S4 | 30 km → 35 km cut-off | 5 km | Not published / not published |
| S5 | 35 km → 40 km cut-off | 5 km | Not published / not published |
| S6 | 40 km → finish | 2.195 km | Not published / not published |

The six segments sum to 10 + 10 + 10 + 5 + 5 + 2.195 = 42.195 km, closing the official distance. That check validates arithmetic, not street assignment: “S3 is 20 to 30 km” does not mean the Bansongyuan Road turnaround necessarily falls between 20 and 30 km, because the organiser published no kilometre for that turnaround.

The street order reveals the rhythm of the course but not precise mileage. The early section runs south along the Bund, then west through the Renmin Road, Henan Road and Nanjing Road system, before turning through Nanjing West Road, Huashan Road, Changshu Road and Huaihai Middle Road. This part has many turns and changing road widths, while the start crowd has not yet fully spread out. The middle section uses Madang Road, Xingye Road, Huangpi South Road, Zizhong Road, Jinan Road and Hubin Road back to Huaihai Middle Road, then Xizang South Road, Gaoxiong Road, Zhizaoju Road and Longhua East Road into the Bansongyuan Road turnaround, followed by Miaojiang Road, Lujiabang Road, Waima Road and the Huangpu Riverside Promenade. The late section uses Longhua East Road, Furun Road, Jiangbin Road and Ruining Road into Longteng Avenue, turns at Jinmugang Road, then uses Fenggu Road with a turnaround at Yunjin Road, before Longheng East Road, Wanping South Road, Longhua Road, Longhua West Road and Zhongshan South 2nd Road lead into the stadium. All three turnarounds fall in the second half, so runners meet others travelling in the opposite direction on the same streets — a feature that separates this city course from a single-loop race.

## Aid stations and cut-offs

Aid is the most detailed part of the public record. Drink/water stations begin at 5 km and continue every 5 km through 40 km; water/refreshment stations begin at 7.5 km and continue every 5 km through 37.5 km. Energy supplies begin at 12.5 km and total nine stations; the organiser publishes the first location and the product types (bananas, chocolate, small cakes and SiS gels), but not the kilometre positions of the other eight. The course also has six ice stations and eight spray stations, again without published positions. On the medical side, the post-race notice lists 43 medical stations, a comprehensive medical station at the finish, four medical points in key post-race areas, 36 monitoring ambulances, 275 AEDs, nine designated hospitals, 100 cycling first-aiders, more than 500 fixed first-aid volunteers and 200 first-aid runners.

There are two official cut-off tables, and both must be shown. The June competition rules begin at 10 km: 10 km 08:30, 15 km 09:10, 20 km 09:50, 25 km 10:30, 30 km 11:15, 35 km 12:05, 40 km 12:50, finish 13:15. The guide updated on 23 November gives: 5 km 08:05, 10 km 08:50, 15 km 09:35, 20 km 10:20, 25 km 11:00, 30 km 11:45, 35 km 12:30, 40 km 13:15, finish 13:30. The latter matches the press announcement that the overall cut-off was extended by 15 minutes to 13:30 because of the three-wave start. The table below therefore uses the 23 November guide as the primary column and keeps the June rules in parentheses. It neither averages nor chooses between them. From 10 km onward the two tables differ point by point by 15–30 minutes (20 minutes at 10 km, 25–30 minutes at 15–35 km, 15 minutes at the finish); that is a change between publication stages, not a typographical error.

| Location | Distance · elevation · cumulative ascent | Service · cut-off |
| --- | --- | --- |
| 5 km drink/water station | 5 km · not published · not published | Drinks and water; cut-off 08:05 (June rules list no 5 km point) |
| 7.5 km water/refreshment station | 7.5 km · not published · not published | Water and refreshment; no cut-off |
| 10 km drink/water station | 10 km · not published · not published | Drinks and water; cut-off 08:50 (June rules 08:30) |
| 12.5 km water/refreshment station | 12.5 km · not published · not published | Water and refreshment; first energy station; no cut-off |
| 15 km drink/water station | 15 km · not published · not published | Drinks and water; cut-off 09:35 (June rules 09:10) |
| 17.5 km water/refreshment station | 17.5 km · not published · not published | Water and refreshment; no cut-off |
| 20 km drink/water station | 20 km · not published · not published | Drinks and water; cut-off 10:20 (June rules 09:50) |
| 22.5 km water/refreshment station | 22.5 km · not published · not published | Water and refreshment; no cut-off |
| 25 km drink/water station | 25 km · not published · not published | Drinks and water; cut-off 11:00 (June rules 10:30) |
| 27.5 km water/refreshment station | 27.5 km · not published · not published | Water and refreshment; no cut-off |
| 30 km drink/water station | 30 km · not published · not published | Drinks and water; cut-off 11:45 (June rules 11:15) |
| 32.5 km water/refreshment station | 32.5 km · not published · not published | Water and refreshment; no cut-off |
| 35 km drink/water station | 35 km · not published · not published | Drinks and water; cut-off 12:30 (June rules 12:05) |
| 37.5 km water/refreshment station | 37.5 km · not published · not published | Water and refreshment; no cut-off |
| 40 km drink/water station | 40 km · not published · not published | Drinks and water; cut-off 13:15 (June rules 12:50) |
| Finish, Xujiahui Sports Park / Gate 12 | 42.195 km · not published · not published | Finish services and medical; cut-off 13:30 (June rules 13:15) |

Cut-offs are absolute clock times, not personal net-time allowances. From the 07:00 first gun to 13:30 is 6 hours 30 minutes; from the 07:20 last gun to 13:30 is 6 hours 10 minutes. The separate rule that a finisher medal is awarded within 6 hours 15 minutes refers to the race result; cut-offs are calculated on natural clock time, so the two are different measures and must not be mixed with a personal net time. A runner judged over the limit at a cut-off must stop and follow the on-site officials’ directions; after withdrawing, public transport can be used to leave the area.

![Wanping South Road during the 2016 Shanghai International Marathon](/media/routes/shanghai/wanping-road-2016.jpg)

## Surface and terrain

The organiser publishes no proportion of asphalt, concrete, stone or rubberised surface, and no friction, flatness or construction-state data. This page therefore gives no percentages. What can be confirmed is that the route consists of named city roads plus a named “Huangpu Riverside Promenade”, passing the Bund, Nanjing Road, Huaihai Road, Xintiandi, the riverside and Longteng Avenue. The organiser does not describe the promenade surface or its connections to adjacent roads, so “promenade” must not be read automatically as dirt or rubber.

On terrain, there is no official elevation profile and no cumulative ascent. Shanghai sits on the Yangtze River Delta plain, but that is geographic background, not a measurement of this course. The official material does not list bridge decks, ramps, sunken sections or short gradients street by street, and this page does not annotate gradients from a city map. Runners can treat the course as “mainly urban road, no mountain terrain”, but not as “absolutely flat” or “zero climb”.

The difficulty of an urban road comes from transitions rather than gradient: the Bund–Nanjing Road section has many right-angle turns; road widths change around Huaihai Road and Xintiandi; the three out-and-backs on Bansongyuan Road, Longteng Avenue and Fenggu Road require runners to handle two-way traffic on the same stretch; the riverside promenade may narrow. The organiser publishes no turning radius, road width or expected passage time, and no construction or temporary re-routing information. Race-day surface conditions are governed by the pre-race publication and on-site instructions.

## Risks and escape points

The first risk is the cut-off. Official points are absolute clock times, so the later D and E corrals have less usable time; queueing, bag drop or security delays before the start reduce that margin further. The first cut-off at 5 km or 10 km arrives early, and a half-marathon pace cannot be used as a trial. Cut-off points are governed by on-site officials and official notices; this table does not replace on-site direction.

The second risk is start and finish organisation. Start-area traffic control begins at 05:30, bag trucks close at 06:45, and bag collection at the finish runs until 14:30. Arriving late, entering the wrong gate or using the wrong truck affects both the start and the post-race retrieval. Use the organiser’s bag with the small bib matching your number inserted or attached to it; a private bag is not a substitute. The finish is on the Gate 12 side of Shanghai Stadium, and friends or family should follow the official finish diagram and on-site instructions rather than walking against the flow on the course.

The third risk is city traffic and medical capacity. The police notice puts closures along the course from 06:45 to 13:30, with some bus routes suspended, shortened or diverted; the police may advance, delay or widen the closures. Runners must not cross cordons or cross the course where no official instruction allows it. Medically, 43 stations, 36 ambulances, 275 AEDs and nine designated hospitals form an on-site, transport and hospital chain; chest tightness, altered consciousness, severe cramping or signs of cold exposure should prompt a request for help at a medical station or from an first-aid runner, including accepting a recommendation to withdraw.

Escape options are limited to what the material supports: leaving at a cut-off, receiving on-site medical treatment, or using public transport after the race. The organiser publishes no “nearest escape line” for each kilometre and no list of mid-course metro stations, so this page invents none. With three out-and-backs and two-way sections, crossing or leaving the course on your own increases the risk of colliding with oncoming runners.

Weather is another variable. The organiser says it will issue race-day weather information before the race; the 2025 pre-race guide forecast sunny weather at 10–22°C. The grid data below shows a race-day maximum of 22.8°C and a minimum of 8.6°C, a wide diurnal range. The organiser places energy supplies from 12.5 km and provides six ice stations and eight spray stations, which shows that cooling is treated as a separate support item. Runners should plan fluids, electrolytes and cooling rather than looking only at the overall cut-off.

## Getting there

**Airports.** Pudong Airport has Metro Line 2 (Pudong Airport station, 06:00–22:30) and the Maglev (Pudong Airport–Longyang Road, 07:02–21:42; Longyang Road–Pudong Airport, 06:45–21:40). Airport buses include Line 4 to Shanghai Railway Station North Square (07:00–23:00), Line 7 to Shanghai South Railway Station (07:30–23:00), and the overnight service to Hongqiao Transport Hub East (23:00–05:30). Hongqiao Airport has Metro Line 2 (Hongqiao Terminal 2) and Line 10 (Terminals 1 and 2), both 06:00–22:30; the city airport line runs from Hongqiao Terminal 2 at 05:45–22:00 about every 15 minutes; airport Line 1 connects Hongqiao Transport Hub East with Pudong Airport (06:00–23:00). These times come from the Shanghai municipal government’s airport transport notice and remain subject to on-site departure times.

**Rail.** Shanghai Railway Station North Square and Shanghai South Railway Station are the termini of airport Lines 4 and 7 respectively, which makes them useful for luggage transfers; Hongqiao Transport Hub East has the overnight airport service and airport Line 1. Hongqiao Airport and Hongqiao Railway Station share the Hongqiao hub, and Metro Lines 2 and 10 connect the airport terminals with the city. Runners arriving by rail during the race period should use the metro into the city rather than take a taxi through the Bund–Nanjing Road control zone on race morning.

**City to the start.** The official pre-race guide advises runners in corrals A, B, C and D to take Metro Line 2 or 10 to Nanjing East Road and walk about 15 minutes; runners in corral E are advised to take Line 10 or 12 to Tiantong Road and walk about 25 minutes. Start-area traffic control begins at 05:30, so security, bag drop and walking time should be counted backwards from the gun. That guide does not give first-train times, and this page does not supply them on the metro operator’s behalf; race-day extra services or station closures must be checked against the operator’s notice.

**Race pack collection.** Collection runs 27–29 November, 09:30–19:30, at the north plaza of the Shanghai World Expo Exhibition & Convention Center, 850 Bocheng Road. The official guide gives these public transport options: Metro Line 8 China Art Museum Exit 3, about 430 m on foot; Line 13 Shibo Avenue Exit 1, about 690 m; Line 7 Yaohua Road Exit 4, about 1.1 km. Buses 83 and 1049 stop at Bocheng Road–Zhoujiadu Road about 64 m away; buses 1118 and Pudong 98 stop at Shibo Avenue–SWEECC Road about 258 m away; tourist bus Line 3 stops at China Art Museum about 377 m away. Drivers can use the P2 underground car park via Gate E2 on Zhoujiadu Road, or the Expo Place and River Mall underground car parks. Bring the original identity document used at registration when collecting.

**Driving and race day.** Driving to the start is not advisable. The police notice closes many roads around the Bund from 23:00 on 29 November, bans vehicles on Zhongshan East 1st Road and other roads from 04:30 on 30 November, and controls the course in sections from 06:45 to 13:30; bus routes sharing the course are suspended, shortened or diverted. No public parking plan for the start area is published, and the finish area is also closed for the event. Leaving the car at the exhibition centre or hotel and using the metro is more controllable. The 2026 edition moves to 6 December, and its traffic control scope and times must come from the new 2026 notice rather than being copied from this page.

## Season and weather

The 2025 edition was held on 30 November, early winter in Shanghai. The official pre-race guide cites the meteorological department’s forecast: sunny, 10–22°C, with a marked diurnal range. For that range, a light long-sleeve top with shorts and a disposable poncho before the start is a reasonable preparation (this site’s suggestion). That is a forecast, not a post-race measurement; the organiser also says it will issue updated weather information before the race.

This page uses Open-Meteo historical reanalysis for the window from seven days before to one day after the race: 23 November to 1 December 2025, nine days, at Shanghai coordinates (requested 31.2304°N, 121.4737°E). The returned grid point is **31.2478°N, 121.5°E at 5 m elevation**. Across the nine days, daily maximum temperature ranged from 13.5 to 22.8°C with a median of 18.2°C; daily minimum ranged from 1.9 to 12.1°C with a median of 7.5°C; none of the nine days recorded daily precipitation of at least 1 mm. For race day, 30 November, the grid gives a maximum of 22.8°C, a minimum of 8.6°C and 0.0 mm precipitation, broadly consistent with the official 10–22°C forecast but with a lower minimum.

This must be read as a **grid-point historical statistic, not a course measurement**. The grid point does not represent the microclimate of the Bund, Nanjing Road, the riverside promenade or Xujiahui Sports Park; urban heat, river breeze, building shade and start-hour conditions all create differences. This page did not retrieve humidity, wind speed, apparent temperature or hourly values, so it makes no claims about humidity or wind direction. The 2026 edition is on 6 December, six days later than 2025, and this window cannot be used as a 2026 forecast; the official pre-race update remains the authority.

## Difficulty rating

**This is a RunUp rating, not an official course or World Athletics difficulty certification.** On the verified data, it is a medium-difficulty urban road marathon: 42.195 km; ascent and descent unpublished and therefore unquantified; technically below a trail race, with no mandatory kit or navigation; but dense turns, three out-and-backs, narrow riverside sections and a split start and finish add organisational and pacing costs.

The cut-off is a major part of the difficulty. From the 07:00 first gun to 13:30 gives 6 hours 30 minutes; from the 07:20 last gun to 13:30 gives 6 hours 10 minutes. The official medal line is 6 hours 15 minutes. For runners under four hours the cut-off is not a constraint; for runners between 5:30 and 6:00, a late start, queueing, aid stops and heat can consume the margin. Treating “6 hours 30 minutes” as the same window for everyone is a common misreading.

Terrain difficulty should not be scored as zero just because “Shanghai is flat”. With no official elevation profile, the total of bridge decks, ramps or short gradients cannot be assessed; urban turns, out-and-backs, narrow sections and crowd density also do not appear in an ascent statistic. In this site’s rating language, the course is “long distance, medium-to-tight cut-off, low technicality, high organisational dependence”. It suits runners treating the race as a city tour with steady pacing; it does not suit a first marathoner placed in a late corral without a sub-6-hour capability.

## Verified and unverified

**Verified from successfully fetched official or authoritative pages:**

- The 2025 edition was on 30 November 2025; wheelchair 06:45, marathon and fitness run 07:00, corral C 07:10, corrals D and E 07:20.
- Start at the Bund Bull; marathon finish at Xujiahui Sports Park, with the police notice naming Gate 12 of Shanghai Stadium; fitness run finish at the Shanghai Exhibition Centre.
- The official description lists the Bund, Nanjing Road Pedestrian Street, Jing’an Temple, Huaihai Road, Xintiandi, Longteng Avenue and Longhua Road.
- The police notice gives the full street order and three turnarounds at Bansongyuan Road (Huayuangang Road), Longteng Avenue (Jinmugang Road) and Fenggu Road (Yunjin Road).
- Drink stations from 5 km every 5 km; water stations from 7.5 km every 5 km; nine energy stations from 12.5 km.
- Two cut-off tables, from the June rules and the 23 November guide, are recorded; they differ by 15–30 minutes point by point, and the latter is the primary column.
- Finisher medal within 6 hours 15 minutes; bag drop closes 06:45; finish bag collection until 14:30.
- Post-race notice gives 43 medical stations, 36 ambulances, 275 AEDs and nine designated hospitals.
- 2025 men’s winner 2:06:25 and women’s winner 2:16:36; domestic men 2:08:36 and domestic women 2:25:13.
- Race-day grid maximum 22.8°C, minimum 8.6°C, 0.0 mm precipitation; zero precipitation days in the window.

**Unverified or unavailable:**

- Official GPX, KML, GeoJSON or any redistributable coordinate sequence: not found.
- Street-to-kilometre mapping: not published, and not inferred here.
- Cumulative ascent, descent, elevation profile, gradient: not published; entity fields are `null`.
- Surface material proportions, flatness, promenade paving: not published.
- Kilometre positions of the nine energy stations, six ice stations and eight spray stations: only the first energy station at 12.5 km is confirmed.
- Exact locations of each medical station, AED and ambulance: only totals and deployment principles are confirmed.
- Race-day metro first trains, extra services or station closures: not given in the pre-race guide and not fetched from the operator.
- 2026 traffic control notice and pre-race transport arrangements: not fetched for this page; the 2026 rules and route map have been published but are not part of the pinned 2025 data here.
- First-hand course feel, crowding and actual aid waiting times: not measured by the author.
- Geometric accuracy and copyright licence of the official route map: an image only, with no redistributable licence.

## Images and rights

**One photograph, from Wikimedia Commons, with a file page that names this event.**

Wanping South Road during the 2016 Shanghai International Marathon, 中日韩越的汉字, CC BY-SA 4.0. The image shows the runners on Wanping South Road at the 2016 Shanghai International Marathon; whether the 2026 course still uses that road must be checked against the current course map, and this page does not treat the 2016 image as proof of the 2026 route.

Channels used this round: the Wikimedia Commons `action=query&generator=search` API, `Special:MediaSearch`, `commons.wikimedia.org/w/index.php?search=` and direct `upload.wikimedia.org` URLs were all reachable. The filter is still three checks: readable licence, file page proving this event, and image matching the caption. Anything failing one is not used. Organiser photographs carry no redistributable CC licence and were not used. (2026-11-07 recheck: the Wikimedia Commons hosts were unreachable from this network; file pages and licences are kept from the capture round and were not re-verified.)

The file is unmodified apart from size and weight compression, and is not covered by this page's CC BY 4.0.

## Sources and reuse

This page uses **14 event, transport and weather sources**, plus one map-anchor method source. The types cover the official event portal, the 2025 competition rules, the official pre-race guide, the police traffic control notice, the sports bureau press-release article, the municipal government event article, the sports bureau post-race notice, the World Athletics report, the airport transport notice, a republished pre-race guide, Open-Meteo historical weather, a 2026 preview, the 2026 competition rules and a 2016 Wanping South Road photograph (`photo-shanghai-2016`). The source list appears at the foot of the page; each source’s `claims` contain only statements that page actually supports, and dates, figures and conflicts are preserved as published.

Official conflicts are retained rather than reconciled: wheelchair field “about 20” alongside “19”; the June and 23 November cut-off tables side by side, with the latter as the primary column because it matches the three-wave start, and the former in parentheses; the distance consistent across three documents, so 42.195 km is used directly; no official ascent figure anywhere, so the entity and tables use `null` or “not published”. This page does not average versions into a middle value, and it does not carry 2025 figures into 2026.

The page provides no GPX, KML, GeoJSON or track download, and no “run the old route” navigation. The official route map, start and finish diagrams and traffic control diagrams remain the copyright of the organiser or issuing authority; this page makes textual references and factual summaries only, and does not redistribute the original images. If the organiser later publishes a redistributable geometry file with a clear licence, the link, licence and year must be re-verified before changing `geometryAccess` from `unavailable` to `official-link`; even then, this site does not draw the line or package the track.

The text is CC BY 4.0 and may be reproduced, adapted and republished with attribution to “RunUp / 跑起来” and a link back to this page. Reproductions must not remove the “not measured”, “not published by the organiser” or “grid point, not course measurement” qualifiers, and must not fill an unpublished ascent with zero. If the organiser requests a correction or withdrawal, the organiser’s latest notice prevails.
