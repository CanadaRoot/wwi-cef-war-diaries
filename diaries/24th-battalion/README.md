# 24th Battalion (Victoria Rifles of Canada) — war diary

## Identity
- **Unit:** 24th Battalion, Canadian Expeditionary Force (Victoria Rifles of Canada; mobilized Montreal, Oct 1914, Lt-Col J. A. Gunn; embarked Montreal 11 May 1915 aboard CAMERONIA; landed England 20 May 1915; arrived France 15 Sep 1915, 2nd Cdn Div, 5th Cdn Inf Bde)
- **Diary:** 8 Dec 1914 – 9 May 1919 (per LAC guide, RG 9 III-D-3, vols. 4931–4932, folders 414–416)
- **Archival reference:** RG 9 III-D-3, vols. 4931–4932, files 414–416; microfilm reels T-10733–T-10735
- **LAC Collection Search:** five file records (no single record covers the whole diary):
  - Item 1883240 — "War diaries - 24th Canadian Infantry Battalion (incomplete)" — vol. 4931, file 414 — 1914/12/18–1915/12/31 — 94 digital objects — https://recherche-collection-search.bac-lac.gc.ca/eng/Home/Record?app=fonandcol&IdNumber=1883240
  - Item 1883241 — vol. 4932, file 414 — 1916/01/01–1917/08/31 — 610 digital objects — IdNumber=1883241
  - Item 2005919 — vol. 4932, file 415 part 1 — 1917/09/01–1917/12/31 — 318 digital objects — IdNumber=2005919
  - Item 2006061 — vol. 4932, file 415 part 2 — 1918/01/01–1918/05/31 — 281 digital objects — IdNumber=2006061
  - Item 2005920 — vol. 4932, file 416 — 1918/06/01–1919/05/09 — 729 digital objects — IdNumber=2005920
- **Page images (IIIF manifest counts):** 1883240: 94; 1883241: 610; 2005919: 511; 2006061: 560; 2005920: 1,409 — total 3,184 manifest items (manifest counts exceed the record-page "digital objects" counts; not reconciled — same discrepancy as the 3rd CRT diary, 400 vs 441)
- **Commanding officer, Dec 1914:** Lt-Col J. A. Gunn

## Access (how the pages were fetched — for future runs)
- LAC Collection Search record pages are bot-blocked for plain curl (403); the record HTML itself fetches fine.
- IIIF manifests at `https://digitalmanifest.bac-lac.gc.ca/DigitalManifest/1/{itemNumber}` (sourceCode 1 = fonandcol). Saved here as `manifest-{itemid}.json`.
- `download-pages.sh manifest-<itemid>.json [prefix]` downloads that item's pages (sequential, polite pace, resumable).

## Contents
- `manifest-1883240.json`, `manifest-1883241.json`, `manifest-2005919.json`, `manifest-2006061.json`, `manifest-2005920.json` — LAC IIIF manifests for the five diary files.
- `1914-1915-page-NNNN-<Month>_<Year>_p._N.jpg` — pages of item 1883240 (Dec 1914 – Dec 1915).
- `download-pages.sh` / `download-1883240.log` — download script and log.
- `transcript-1914-12.md` … — monthly transcripts (to be added as completed).

## Manifest label order — item 1883240 (94 pages)
Labels as they appear in the manifest (not chronological): Dec 1914 pp. 1–31 (manifest pages 1–31), Oct 1914 pp. 1–9 (pages 32–40), Aug 1915 pp. 1–5 (pages 41–45), Sep 1915 pp. 1–9 (pages 46–54), Oct 1915 pp. 1–14 (pages 55–68), Nov 1915 pp. 1–5 (pages 69–73), Dec 1915 pp. 1–21 (pages 74–94). No Jan–Jul 1915 pages in this file; record title says "(incomplete)". Transcribe in manifest order and note the order.

## Progress
- 2026-10-26, Eighth C run 3: LAC records found (5 items), all five manifests fetched. **Item 1883240 COMPLETE — all 94 pages transcribed** (Dec 1914 – Dec 1915): transcripts `transcript-1914-10.md` (typed summary + July 1915 training programme), `transcript-1914-12.md` (Medical Officer's diary, Dec 1914 – Dec 1915), `transcript-1915-08.md`, `transcript-1915-09.md`, `transcript-1915-10.md`, `transcript-1915-11.md`, `transcript-1915-12.md`. **218 dated index entries in `INDEX-C.md`.**
- Diary NOT done — continues next run with item 1883241 (Jan 1916 – Aug 1917, 610 manifest pages). Overall: 94 of 3,184 manifest pages transcribed.
- 2026-10-26, Eighth C run 4: **Item 1883241 page download COMPLETE — all 610/610 pages on disk** (`1916-1917-page-0001`–`page-0610`, 0 failures; download restarted once after a SIGTERM at 349 pages, resumable script picked up at page 350). **Jan–Mar 1916 transcribed (78 pages):** `transcript-1916-01.md` (25 pp., diary text 1–29 Jan; Apps 1–11; sole casualty Lieut. R.H.B. Buchanan killed 18 Jan), `transcript-1916-02.md` (27 pp., diary text 3–27 Feb), `transcript-1916-03.md` (26 pp., diary text 1–29 Mar). Index entries for Jan–Mar 1916 appended to `INDEX-C.md` (see PROGRESS.md for counts). Overall: 172 of 3,184 manifest pages transcribed.
- Diary NOT done — continues next run with item 1883241, April 1916 (manifest pages 79–101).
- 2026-10-27, Eighth C run 5: **Item 1883241, April 1916 COMPLETE (23 pages, manifest pages 79–101):** `transcript-1916-04.md` (748 lines; merged from two parallel part transcriptions, spot-checked by the parent run against April pp. 3 and 17). Cover, contents, diary text 2–30 April (7 pp.), 5th Bde. Orders 50, 51, 53, 54, signal message B.M.200, Special Work Officer report night 16/17 April, Intelligence Report 17 April, B.M.L.48 working parties night 21/22 April, Defence Scheme Centre Sector 26 April. **27 dated index entries added to `INDEX-C.md`** (292 total). Overall: 195 of 3,184 manifest pages transcribed.
- 2026-10-27, Eighth C run 6: **Item 1883241, May 1916 COMPLETE (37 pages, manifest pages 102–138):** `transcript-1916-05.md` (1,016 lines; merged from two parallel part transcriptions, spot-checked by the parent run against May p. 3). Cover, contents, diary text 1–30 May (22 dated entries; no entries for 2, 3, 8, 13, 24, 25, 28, 29, 31 May), 5th Bde. Orders 55–57, 24th Bn. Orders 33–35, training syllabus 3–14 May, scout/work reports and intelligence summaries 15–23 May, 5th Bde. Relief Tables and Operation Order No. 69 (29 May). **22 dated index entries added to `INDEX-C.md`** (314 total). Month totals from the diary text: 9 O.R. killed, 29 O.R. wounded, 1 officer wounded (Lieut. G. V. Walsh, 4 May); heaviest loss 23 May — 8 killed, 16 wounded by direct hits on dugouts in trenches 18 and [uncertain]. Command churn: Gunn acting brigadier 5 May; Ross, C. A./C. D. Parr [uncertain], Alexander acting O.C. in turn. Diary hand changes again (p. 3 "P.J.A." [uncertain], pp. 4–5 "C.J.B." [uncertain]). Note: the earlier README line said May was manifest pages 102–124 — corrected: May is pp. 1–37 = manifest pages 102–138; June starts at manifest page 139. Overall: 232 of 3,184 manifest pages transcribed.
- Diary NOT done — continues next run with item 1883241, June 1916 (manifest pages 139–154).
