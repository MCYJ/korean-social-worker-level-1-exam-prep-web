# KOR-0257 marketing site context

## Scope

- Independent public marketing and study site for released app `KOR-0257` only.
- App source is read-only: `/Users/youngjunma/Documents/various test prep apps project/services/kor/02/kor-0257`.
- Android package and iOS bundle identifier: `app.mcyj.examprep.kor0257`.
- Production target: `https://mcyj.github.io/korean-social-worker-level-1-exam-prep-web/`.

## Verified Store state — 2026-09-19

- Google Play resolves publicly for the exact package.
- Apple lookup resolves the exact bundle to track ID `6797318263` in KR, US and GB.
- Both official Store badges are active and use the same 194 × 75 px outer frame without distorting artwork.

## Content and official facts

- Korean and English routes with 10 substantive guides per locale.
- Official qualification: 사회복지사 1급 (`jmCd=9738`).
- Three subjects and eight domains: 사회복지기초 2, 사회복지실천 3, 사회복지정책과 제도 3.
- The written exam has 200 five-choice items over three sessions and 200 minutes: 50/50, 75/75 and 75/75.
- Provisional passage requires at least 40% in every subject and 60% of the total score.
- A provisional passer must submit eligibility documents on time and pass the Korea Association of Social Workers review for final passage.
- The 24th exam was January 17, 2026; provisional results began February 19 and final results began March 25.
- Canonical sources:
  - `https://www.q-net.or.kr/man001.do?gId=52&gSite=L&id=man00102`
  - `https://www.q-net.or.kr/crf005.do?gId=&gSite=Q&id=crf00503s02&jmCd=9738&jmInfoDivCcd=B0`
  - `https://www.q-net.or.kr/man004.do?ARTL_SEQ=5246527&BOARD_ID=Q001&gId=52&gSite=L&id=man00402`

## Design and implementation

- Visual thesis: a soft-rose care map that connects people, practice and systems with restrained pathway markers.
- Global Korean-safe wrapping uses `word-break: keep-all` and `overflow-wrap: break-word`.
- Dependency-free static generator; GitHub Actions builds, checks and deploys `dist/` to Pages.

## Verification log

- 2026-09-19: project initialized from the proven static-site system and retargeted to KOR-0257 content, assets and Store identities.
- 2026-09-19: local build generated 34 indexable routes and 36 HTML files; the checker passed metadata, links, both exact Store identities, `keep-all`, equal marketplace frames and stale-content rejection.
- 2026-09-19: local HTTP QA returned 200 for all 34 sitemap routes and five key assets; an unknown route returned 404.
- 2026-09-19: live Store recheck returned Google Play 200 and Apple bundle `app.mcyj.examprep.kor0257`, track ID `6797318263` in KR, US and GB.
- 2026-09-19: GitHub Pages workflow run `35366124175` completed successfully.
- 2026-09-19: production QA returned 200 for all 34 sitemap routes and five key assets; an unknown route returned 404.
- 2026-09-19: production CSS contains global `word-break: keep-all` and the shared 194 × 75 px marketplace frame; the Korean home contains both exact public Store links.

## 2026-10-23 — SEO technical improvements

- Added dependency-free post-build SEO validation and enhancement: valid reciprocal language alternates, page-preserving language switching, source-backed Article identities/citations, BreadcrumbList, social text metadata, noindex on the utility 404, and priority for existing above-fold app imagery.
- Removed unverified structured-data offers where present. Preserved existing official-source verification dates, visible study content, app artwork, keep-all and equal marketplace badge frames.
- Public repository instructions were treated only as methodology; no external skill, tool, tracking, account connection, or scheduled action was installed.
