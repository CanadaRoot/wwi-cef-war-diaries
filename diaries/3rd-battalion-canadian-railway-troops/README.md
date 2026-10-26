# 3rd Battalion, Canadian Railway Troops — war diary

## Identity
- **Unit:** 3rd Battalion, Canadian Railway Troops (239th Battalion, May 1916 → redesignated 3 Feb 1917)
- **Diary:** 7 March 1917 – 31 December 1918
- **Archival reference:** RG 9 III-D-3, vol. 5012, folder 733; microfilm reels T-10861–T-10862
- **LAC Collection Search:** Item ID 2004961 — https://recherche-collection-search.bac-lac.gc.ca/eng/Home/Record?app=fonandcol&IdNumber=2004961
- **Permanent link:** https://central.bac-lac.gc.ca/.redirect?app=fonandcol&id=2004961&lang=eng
- **Page images:** 400 (LAC viewer count; record title says 441 digital objects — not reconciled)
- **Commanding officer, March 1917:** Lt. Col. J.B.L. Macdonald

## Access (how the pages were fetched — for future runs)
- LAC Collection Search record pages are bot-blocked for plain curl (403); the record HTML itself fetches fine.
- The viewer is LAC's harmonized viewer. Its IIIF manifest lives at `https://digitalmanifest.bac-lac.gc.ca/DigitalManifest/{sourceCode}/{itemNumber}`.
- The sourceCode for the fonandcol reference system is `1` (from `https://colabapi.bac-lac.gc.ca/api/Colab/GetReferenceSystem?code=fonandcol`).
- So this diary's manifest is `https://digitalmanifest.bac-lac.gc.ca/DigitalManifest/1/2004961` — saved here as `manifest.json`.
- Each manifest item's body id is a `https://central.bac-lac.gc.ca/.item/?id=<ecopy>&app=fonandcol&op=img` URL, which redirects to a `https://data2.archives.ca/.../*.jpg`. Ecopy numbers are NOT sequential (gaps), so always use the manifest, never guess ecopies.
- `download-pages.sh` downloads all 400 pages from the manifest (sequential, polite pace, resumable — skips files already present).

## Contents
- `manifest.json` — LAC IIIF manifest for the whole diary (400 items, March 1917 p. 1 – December 1918 p. 17).
- `page-NNNN-<Month>_<Year>_p._N.jpg` — diary page images as downloaded from LAC.
- `download-pages.sh` / `download.log` — download script and log.
- `transcript-1917-03.md` — March 1917 transcript (COMPLETE: pages 1–21).
- `transcript-1917-04.md` — April 1917 transcript (COMPLETE: pages 22–41).
- `transcript-1917-05.md` — May 1917 transcript (COMPLETE: pages 42–89).
- `transcript-1917-06.md` — June 1917 transcript (COMPLETE: pages 90–111).
- `transcript-1917-07.md` — July 1917 transcript (COMPLETE: pages 112–134).
- `transcript-1917-08.md` — August 1917 transcript (COMPLETE: pages 135–150).
- `transcript-1917-09.md` — September 1917 transcript (COMPLETE: pages 151–165).
- `zoom-p*.jpg` — enlarged crops used to verify hard handwriting (working aids, not part of the diary).
- `zoom-sep-*.jpg` — enlarged crops of the September diary-text pages (pp. 6–10, 14–15).

## Progress
- March 1917: COMPLETE (21 pages) — 2026-10-26, Eighth A run 1.
- April 1917: COMPLETE (20 pages) — 2026-10-26, Eighth A run 1.
- May 1917: COMPLETE (48 pages; 50 numbered, pp. 43–44 absent from LAC manifest) — 2026-10-26, Eighth A run 1.
- June 1917: COMPLETE (22 pages) — 2026-10-26, Eighth A run 1.
- July 1917: COMPLETE (23 pages) — 2026-10-26, Eighth A run 1.
- August 1917: COMPLETE (16 pages; 19 numbered, pp. 4–5 and p. 7 absent from LAC manifest; no appendices; handwriting much harder to read — many words flagged [uncertain] in the transcript) — 2026-10-26, Eighth A run 1.
- September 1917: COMPLETE (15 pages; 17 numbered, pp. 4–5 absent from LAC manifest; no appendices; same cramped hand as August — many words flagged [uncertain] in the transcript) — 2026-10-26, Eighth A run 2.
- October 1917: next. Page 166 is October 1917, p. 1.
- Overall: 165 of 400 pages transcribed (March–September 1917); 208 index entries in `INDEX-A.md`.
