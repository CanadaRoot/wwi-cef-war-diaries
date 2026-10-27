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
- `transcript-1917-10.md` — October 1917 transcript (COMPLETE: pages 166–178).
- `transcript-1917-11.md` — November 1917 transcript (COMPLETE: pages 179–191).
- `transcript-1917-12.md` — December 1917 transcript (COMPLETE: pages 192–208). Working parts: `transcript-1917-12-diarytext.md` (pp. 6–12, 1–19 Dec) and `transcript-1917-12-appendices.md` (pp. 13–19, 20–31 Dec + Appendices 1–3).
- `transcript-1918-01.md` — January 1918 transcript (COMPLETE: pages 209–221). Working parts: `transcript-1918-01-part1.md` (pp. 1–3, 6–9, 1–13 Jan) and `transcript-1918-01-part2.md` (pp. 10–15, 14–31 Jan + Appendix 1).
- `zoom-jan-*.jpg` — enlarged crops used to verify January handwriting (working aids, not part of the diary).
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
- October 1917: COMPLETE (13 pages; 15 numbered, pp. 4–5 absent from LAC manifest; no appendices; same cramped hand as August–September — many words flagged [uncertain] in the transcript) — 2026-10-26, Eighth A run 3.
- November 1917: COMPLETE (13 pages; 15 numbered, pp. 4–5 absent from LAC manifest; no appendices; same cramped hand — many words flagged [uncertain] in the transcript; C & D Coys move south to Lebuquiere, 3rd Army North, 6 Nov; O.C. changes — month signed by W. Stewart [uncertain], Lt. Col., not J. B. Macdonald) — 2026-10-26, Eighth A run 4.
- December 1917: COMPLETE (17 pages; 19 numbered, pp. 4–5 absent from LAC manifest; contents page undercounts diary text as "7 Pages" — diary text is in fact 11 pages, pp. 6–16, 1–31 Dec; Appendices 1–3 are pp. 17–19, congratulatory messages 28 Nov–24 Dec 1917; same cramped hand — many words flagged [uncertain] in the transcript; Sgt Cooney casualty rank/number differs between the 16 Dec and 30 Dec entries and is NOT reconciled — see transcript reconciliation notes) — 2026-10-27, Eighth A run 5.
- January 1918: COMPLETE (13 pages; 15 numbered, pp. 4–5 absent from LAC manifest; contents page lists "Diary Text 9 Pages" — diary text is pp. 6–14, 9 pages, and p. 15 is Appendix 1, so the contents page is exact; same cramped hand — many words flagged [uncertain] in the transcript; 300 Chinese labourers start on the Cape to Cairo line 3 Jan; Lt-Col Macdonald awarded D.S.O. and Sergt Glisson D.C.M. 10 Jan; Macdonald on leave from 22 Jan, month signed by J. [uncertain] Stewart, Major; Appendix 1 is a typed letter dated 18 Jan 1918 proposing standardisation of light-railway rules; 1 Jan confirms Spr J. W. Cooney No 279834 killed 16 Dec 1917, but the 30 Dec "Sgt Cooney J. D., No 22983" still conflicts — NOT reconciled, see transcript reconciliation notes) — 2026-10-27, Eighth A run 6.
- February 1918: next. Page 222 is February 1918, p. 1.
- Overall: 221 of 400 pages transcribed (March 1917–January 1918); 331 index entries in `INDEX-A.md`.
