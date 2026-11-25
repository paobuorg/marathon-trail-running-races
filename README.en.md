# RUNUP · Global marathon and trail-running race archive

[中文](README.md) · English

This repository holds the race records, bilingual articles, sources and review data used by the RunUp main site. It is a content-only repository: there is no site runtime code, `package.json`, `node_modules` or build output.

## What is here

- **52 races** across 24 countries and territories, from 31 km to 330 km.
- 34 trail ultras, 11 road marathons, 4 mountain trail races and 3 road ultras.
- Every race has independent Chinese and English articles, plus source-by-source review records.
- Pages are written against a fixed edition: course version, event date, distance, cumulative ascent, high point, cut-offs and categories. We do not maintain registration links, live results or prices.

The public path stays `https://paobu.org/routes/`; renaming the repository does not change the site URL.

## Who it is for

- Runners who want the practical shape of a race: how hard it is, where it goes, when it happens and what the entry conditions are.
- Editors who need to check course facts, official sources and redistribution boundaries.
- Anyone who wants race facts without treating marketing copy as data.

## Layout

```text
data/entities/{slug}.json          Shared facts, edition, source refs and geometry rights
data/sources/{sourceId}.json       Sources, locations and the claims they support
data/contributors/{personId}.json  Public author and reviewer identities
data/reviews/{slug}.{locale}.json  Content digest and decision after review
content/zh-CN/{slug}.md            Chinese article and frontmatter
content/en/{slug}.md               English article and frontmatter
assets/                            Redistributable tracks and small assets
```

Entity IDs look like `route:boston`; slugs use lowercase English hyphens. The two languages are paired by `entityId`, and shared facts live only in `data/entities/`.

## Data rules

- Distance and elevation need a locatable source. When elevation is not trustworthy, `elevationGainMeters` stays `null`; it is never set to `0`.
- `mapAnchor` is a globe anchor, not a start point or a full track.
- `geometryAccess` is `redistributable`, `official-link` or `unavailable`. Only `redistributable` geometry may be stored and offered as a download, and it requires a licence, attribution and source.
- A visible race page does not imply permission to redistribute its track. Official pages support fact-checking but do not grant rights to images, logos, GPX files or databases.
- When a source changes, both language versions must be checked again. `reviewedAt` is filled only after a substantive review.

## Review status

All 52 race pages have completed AI-assisted editorial review and are published (`published`, with bilingual `approve` records and matching digests). The reviewer is `runmap-editorial`, explicitly AI-assisted, not independent or professional review. This repository does not claim professional review.

## Local use

The content is read by `site-www` at build time. When the six projects sit in the same parent directory, the build finds this repository automatically; `ROUTES_CONTENT_DIR` can override the path. This repository has no install or build command of its own.

See [site-www](../site-www/README.md) for preview commands. The build validates bilingual pairing, sources, licences, review dates and content digests; a failure blocks publication.

## Licence and corrections

- New article text: CC BY 4.0, attributed to “RunUp 跑起来”.
- Tracks, images and third-party assets: under each source's terms, recorded per entity or source. Material without confirmed rights does not enter the repository.
- Site code: MIT, in the three `site-*` repositories and `paobu-core`.

Report factual or source problems through an issue or pull request that names the paragraph, source and proposed change. See [CONTRIBUTING.md](CONTRIBUTING.md), whose second half is in English.

Last checked: 2026-11-25.
