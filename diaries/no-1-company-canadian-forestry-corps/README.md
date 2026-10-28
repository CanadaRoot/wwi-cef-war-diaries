# No. 1 Company, Canadian Forestry Corps — war diary

## Identity
- **Unit:** No. 1 Company, Canadian Forestry Corps (LAC record title: "War diaries - No. 1 Company - Canadian Forestry Corps = Journal de guerre - Compagnie no 1 - Corps forestier canadien")
- **Diary:** September 1915; October 1917 – March 1918; September – December 1918
- **Archival reference:** RG 9 III-D-3, finding aid 9-52
  - Part 1: vol. 5017, file 761, file part 2; microfilm reel T-10901; LAC Item **2004997** — https://recherche-collection-search.bac-lac.gc.ca/eng/Home/Record?app=fonandcol&IdNumber=2004997 — dates 1915/09–1918/03
  - Part 2: vol. 5018, file 762, file part 2; microfilm reel T-10901; LAC Item **2004999** — https://recherche-collection-search.bac-lac.gc.ca/eng/Home/Record?app=fonandcol&IdNumber=2004999 — dates 1918/09/01–1918/12/31
- **Page images:** 72 in the LAC viewer. Fetched from LAC via the IIIF manifests `https://digitalmanifest.bac-lac.gc.ca/DigitalManifest/1/2004997` (64 pp.) and `https://digitalmanifest.bac-lac.gc.ca/DigitalManifest/1/2004999` (8 pp.); page images saved alongside this file (`page-NNNN-<Month>_<Year>_p._N.jpg`, `manifest-2004997.json`, `manifest-2004999.json`). Part-2 pages are numbered continuously as 0065–0072.

## Access (how the pages were fetched — for future runs)
- LAC Collection Search Title-field search (`SearchIn_1=Title&SearchInText_1=War diaries - No. 1 Company, Canadian Forestry Corps`, with the search form's `ST=STAD&DataSource=Archives|FonAndCol` parameters plus a Referer header) returned both records at once. Note the record title uses a hyphen, not a comma: "No. 1 Company - Canadian Forestry Corps".
- The two part records are NOT adjacent item IDs in the usual sense — 2004998 between them is a different unit (Director of Timber Operations, Canadian Forestry Corps). Do not assume neighbouring IDs are the same unit's other parts.
- The viewer is LAC's harmonized viewer. Its IIIF manifest lives at `https://digitalmanifest.bac-lac.gc.ca/DigitalManifest/{sourceCode}/{itemNumber}`; sourceCode `1` = fonandcol. The manifest itself fetches fine with plain curl.
- Each manifest item's body id is a `https://central.bac-lac.gc.ca/.item/?id=<ecopy>&app=fonandcol&op=img` URL, which redirects to a `https://data2.archives.ca/.../*.jpg`. Ecopy numbers are NOT sequential (gaps), so always use the manifest, never guess ecopies.
- `download-pages.sh` downloads all 72 pages from both manifests (sequential, polite pace, resumable — skips files already present).

## Contents
- `manifest-2004997.json`, `manifest-2004999.json` — LAC IIIF manifests for the whole diary.
- `page-NNNN-<Month>_<Year>_p._N.jpg` — diary page images as downloaded from LAC.
- `download-pages.sh` / `download.log` — download script and log.
- `transcript-YYYY-MM.md` — one monthly transcript per month, written by four parallel subagents (one per period) and verified on disk.

## Progress
- Transcription COMPLETE — 2026-10-27, Eighth G, run 8: all 72 pages read and transcribed into 11 monthly transcripts (`transcript-1915-09.md`, `transcript-1917-10.md` … `transcript-1918-12.md`) by four parallel subagents (one per period), verified on disk by the parent run.
- Index entries in `INDEX-G.md`: COMPLETE — 159 dated entries (Apr 1915–Nov 1918, 11 month sections), built from the transcripts in two parts (`INDEX-G-CFC-part1.md`, 124 entries; `INDEX-G-CFC-part2.md`, 35 entries) and merged; INDEX-G.md now holds 4,834 entries total, verified programmatically (4,675 before + 159 = 4,834).
- 51 `[uncertain]` flags across the transcripts (verified on disk by grep; subagent handoff counts did not reconcile, so the on-disk figure governs).

## Monthly volumes — coverage notes
- **Large gap in the record as filed:** the diary as digitised covers September 1915, then jumps to October 1917. No pages for October 1915 – September 1917, nor for April – August 1918, exist in either LAC record. This is a gap in the filed record, not a download failure.
- **September 1918 manifest labels are French** ("Septembre 1918"); transcript filed as `transcript-1918-09.md`.
- **The "September 1915" pages are not a September 1915 diary:** pp. 4–19 are a retrospective narrative history (April 1915–September 1917, signed Capt. H. Hellmuth, stamped 20 October 1917); the only day-by-day entries in that group are 15–30 September 1917 (pp. 23–25, Crecy Forest). Narrative milestones are indexed under their event dates, marked "(from the retrospective narrative history)"; the two milestones with no exact day are dated to the month only (1915-04, 1916-04).
- **January–March 1918 are weekly summaries** (Army Form C. 2118), indexed once on the first day of each week; **September and October 1918 are single monthly summaries**, indexed on the 1st of the month; **November 1918 has daily entries** (16 dated entries, two on 14 Nov — the second date flagged [uncertain]).
- **December 1918 is cover only** — no diary content, no entries.
- **Dates with no diary entry:** 27 Sep 1917; 8 Nov 1917; November 1918: 2, 4, 8, 10, 15, 16, 17, 19, 20, 22, 25, 26, 28, 29.
- **No human casualties** among the company's own men in the whole diary; only sickness noted is influenza in the attached 10th P.O.W. Company, October 1918.
- **Commanding officers:** Capt. (later Maj.) H. Hellmuth (to Mar 1918); Capt. W. Hutchison (Sep–Nov 1918). Lieut. M. C. Haight signs February 1918 for the O.C.
