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
- `transcript-1918-02.md` — February 1918 transcript (COMPLETE: pages 222–231). Working parts: `transcript-1918-02-part1.md` (pp. 1–3, 6–8, 1–12 Feb) and `transcript-1918-02-part2.md` (pp. 9–12, 13–28 Feb).
- `transcript-1918-03.md` — March 1918 transcript (COMPLETE: pages 232–258). Working parts: `transcript-1918-03-part1.md` (pp. 1–3, 6–9, 1–16 Mar), `transcript-1918-03-part2.md` (pp. 10–19, 17–31 Mar + map sheets pp. 14–19) and `transcript-1918-03-part3.md` (pp. 20–29, Appendix A map, sheets 3–6). Index draft: `index-1918-03.md`.
- `transcript-1918-04.md` — April 1918 transcript (COMPLETE: pages 259–269). Working parts: `transcript-1918-04-part1.md` (pp. 6–9, 1–16 Apr) and `transcript-1918-04-part2.md` (pp. 10–13, 17–30 Apr). Index draft: `index-1918-04.md`.
- `zoom-feb-*.jpg` — enlarged crops used to verify February handwriting (working aids, not part of the diary).
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
- February 1918: COMPLETE (10 pages; 12 numbered, pp. 4–5 absent from LAC manifest; contents page lists "Diary Text 7 Pages" — diary text is pp. 6–12, 7 pages, no appendices, so the contents page is exact; same cramped hand — 30 [uncertain] flags in the transcript; gallantry awards for 11–12 Jan announced 2–4 Feb — M.C. Lieut. M. Helyer, D.C.M. Cpl. Dors J., M.M.s to Sprs. Brabant, Smith, Watts and Sowler, completing the 12 Jan recommendation of one officer and five OR; Major Baker posted to command 8th Bn CRT 5 Feb, Macdonald returned from leave 8 Feb and signed the month; German propaganda balloon ("Gazette des Ardennes") picked up near Bethune 14 Feb, Irish-revolt appeal dropped 22 Feb; medical board reclassifying men 16–17 Feb; strength 40 officers / 963 OR 18 Feb; Cape to Cairo down to 1/2 mile of ballasting by 28 Feb; month's only casualty Sapper F. Hulme wounded by shrapnel 12 Feb) — 2026-10-27, Eighth A run 7.
- March 1918: COMPLETE (27 pages; 29 numbered, pp. 4–5 absent from LAC manifest; contents page lists "Diary Text 8 Pages" — diary text is pp. 6–13, 8 pages, so exact; Appendix A is the War Records Map, pp. 14–29, in two photograph runs; same cramped hand — 120 [uncertain] flags in the merged transcript; German spring offensive opens 21 Mar — nine-hour bombardment, over 500' of track to replace, leave cancelled 23 Mar, A Coy withdraws two forward detachments 25 Mar; Cape to Cairo line practically completed 23 Mar; grading begins on the new "Savy North Line" 26 Mar; casualties 22 Mar (1 attached Labour O.R. killed, 1 A Coy O.R. and 1 attached Labour O.R. wounded), 30 Mar (1 B Coy O.R. killed, 1 wounded), 31 Mar (1 O.R. attached to A Coy wounded, afterwards died), plus unnumbered casualties 25 Mar; month signed by Lt.-Col. J. B. L. Macdonald; transcribed 2026-10-27 in three working parts by Eighth A run 8, merged and indexed 2026-10-28 by run 9 — run 8's PROGRESS.md entry was never written) — 2026-10-28, Eighth A run 9.
- April 1918: COMPLETE (11 pages; 13 numbered, pp. 4–5 absent from LAC manifest; contents page lists "Diary Text 8 Pages" — diary text is pp. 6–13, 8 pages, so exact; no appendices; same cramped hand — 22 [uncertain] occurrences in the merged transcript, 10 of them inline in the diary text; German spring offensive continues — heavy shelling and dozens of blowouts daily in the Vimy area, Barlin itself shelled repeatedly 22–28 Apr; battalion ordered to draw rifles and arm 6 Apr, rifle drill begun; tanks repeatedly crossing and damaging tracks without warning 7–8 Apr; "B" Coy tie-plate experiment on a 30-metre curve failed and every train derailed 29 Apr; casualties 1 Apr (Spr C. Arkwright #229542 buried in Aux Rietz Cemetery), 9 Apr (several O.R. slightly gassed, 3 admitted to hospital), 11 Apr (10 casualties to attached labour, D Coy HQ shelled); D.C.M. to Sergt J. A. McPhail for 28 Mar gallantry, commissioned 29 Apr; C.S.M. C. B. Croasdale, Sergt W. T. Fraser and Corpl T. F. Francis also commissioned; 65-acre farm plot allotted at Ecoures [uncertain] 19 Apr; "Beuvry" written clearly 20 & 24 Apr confirms March's "Bessy [uncertain]" was Beuvry; month signed by Lt.-Col. J. B. L. Macdonald; transcribed 2026-10-28 in two working parts by Eighth A run 10, merged and indexed by run 10) — 2026-10-28, Eighth A run 10.
- May 1918: next. Page 270 is May 1918, p. 1.
- Overall: 269 of 400 pages transcribed (March 1917–April 1918); 420 index entries in `INDEX-A.md`.
