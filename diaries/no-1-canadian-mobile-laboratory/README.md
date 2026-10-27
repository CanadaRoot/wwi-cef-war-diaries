# No. 1 Canadian Mobile Laboratory — war diary

## Identity
- **Unit:** No. 1 Canadian Mobile Laboratory, Witley (LAC record title: "War diaries - 1st Canadian Mobile Laboratory, Witley"). Organised as Central Laboratory 15 to handle work from Hastings; moved to Witley 25 August 1917; became No. 1 Canadian Mobile Laboratory 4 October 1917; redesignated The Canadian General Laboratory 6 July 1918. Performed pathological, bacteriological, serological and biological work.
- **Diary:** 1 December 1917 – 31 July 1918
- **Archival reference:** RG 9 III-D-3, vol. 5038, file 870, part 3; microfilm reel T-10929
- **LAC Collection Search:** Item ID 2005125 — https://recherche-collection-search.bac-lac.gc.ca/eng/Home/Record?app=fonandcol&IdNumber=2005125
- **Permanent link:** https://central.bac-lac.gc.ca/.redirect?app=fonandcol&id=2005125&lang=eng
- **Page images:** 35 in the LAC viewer (8 monthly volumes: Dec 1917, 5 pp.; Jan 1918, 6 pp.; Feb 1918, 6 pp.; Mar 1918, 4 pp.; Apr 1918, 4 pp.; May 1918, 4 pp.; Jun 1918, 3 pp.; Jul 1918, 3 pp.). Fetched from LAC via the IIIF manifest `https://digitalmanifest.bac-lac.gc.ca/DigitalManifest/1/2005125`; page images saved alongside this file (`page-NNNN-<Month>_<Year>_p._N.jpg`, `manifest.json`).
- **Commanding officer:** Capt. Thos. P. Little, O.C. (signs the January monthly summary "Thos. P. Little Capt."; the diary's remarks column is initialled "T.P.L." throughout December–June). The July typed entries spell his initials "T.R. Little" — a typist's error, flagged in the July transcript; the July diary is signed off by Capt. P. T. McIlroy [uncertain] while Little is on leave from 31 July.
- **Location throughout:** Witley Camp, Surrey, England. No moves. No map coordinates are given in the diary.

## Access (how the pages were fetched — for future runs)
- LAC Collection Search result/record pages are bot-blocked for plain curl and for `browser.open` (403 "Human verification needed"); the record was found via the live browser, which clicked through the human-verification link.
- The viewer is LAC's harmonized viewer. Its IIIF manifest lives at `https://digitalmanifest.bac-lac.gc.ca/DigitalManifest/{sourceCode}/{itemNumber}`; sourceCode `1` = fonandcol. The manifest itself fetches fine with plain curl.
- Each manifest item's body id is a `https://central.bac-lac.gc.ca/.item/?id=<ecopy>&app=fonandcol&op=img` URL, which redirects to a `https://data2.archives.ca/.../*.jpg`. Ecopy numbers are NOT sequential (gaps), so always use the manifest, never guess ecopies.
- `download-pages.sh` downloads all 35 pages from the manifest (sequential, polite pace, resumable — skips files already present).

## Contents
- `manifest.json` — LAC IIIF manifest for the whole diary (35 items, December 1917 p. 1 – July 1918 p. 3).
- `page-NNNN-<Month>_<Year>_p._N.jpg` — diary page images as downloaded from LAC.
- `download-pages.sh` / `download.log` — download script and log.
- `transcript-1917-12.md` — December 1917 transcript (COMPLETE: pages 1–5).
- `transcript-1918-01.md` — January 1918 transcript (COMPLETE: pages 6–11).
- `transcript-1918-02.md` — February 1918 transcript (COMPLETE: pages 12–17).
- `transcript-1918-03.md` — March 1918 transcript (COMPLETE: pages 18–21).
- `transcript-1918-04.md` — April 1918 transcript (COMPLETE: pages 22–25).
- `transcript-1918-05.md` — May 1918 transcript (COMPLETE: pages 26–29).
- `transcript-1918-06.md` — June 1918 transcript (COMPLETE: pages 30–32).
- `transcript-1918-07.md` — July 1918 transcript (COMPLETE: pages 33–35).
- `zoom-*.jpg` — enlarged crops used to verify hard readings (working aids, not part of the diary).

## Progress
- December 1917–July 1918: COMPLETE (all 35 pages) — 2026-10-26, Eighth G, run 3.
- Overall: 35 of 35 pages transcribed; 242 dated index entries in `INDEX-G.md`. Diary DONE.
- The successor diary (War diary, Canadian General Laboratory, Witley, 1 Aug. 1918 – 31 Mar. 1919, RG 9 III-D-3, vol. 5038) is a separate LAC record and is NOT part of this diary; it would be a separate queue entry if the queue lists it.

## Glossary (expansions, not in the diary)
- S.O.S. = struck off strength. C.A.M.C. = Canadian Army Medical Corps. O.C. = Officer Commanding. A.D.M.S. = Assistant Director of Medical Services. "Routine work" = the laboratory's daily pathological/bacteriological/serological testing.
