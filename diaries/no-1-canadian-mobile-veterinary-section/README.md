# No. 1 Canadian Mobile Veterinary Section — war diary

## Identity
- **Unit:** No. 1 Canadian Mobile Veterinary Section (LAC record title: "War diaries - No. 1 Canadian Mobile Veterinary Section = Journal de guerre - Section vétérinaire mobile canadienne no 1")
- **Diary:** 1 March 1915 – 31 March 1919
- **Archival reference:** RG 9 III-D-3, vol. 5043, file 890, part 1 = 1915/03/01–1917/04/30, part 2 = 1917/05/01–1919/03/31; microfilm reel T-10935
- **LAC Collection Search:** Item ID 2005170 — https://recherche-collection-search.bac-lac.gc.ca/eng/Home/Record?app=fonandcol&IdNumber=2005170
- **Permanent link:** https://central.bac-lac.gc.ca/.redirect?app=fonandcol&id=2005170&lang=eng
- **Page images:** 613 in the LAC viewer (49 monthly volumes: March 1915 – March 1919). Fetched from LAC via the IIIF manifest `https://digitalmanifest.bac-lac.gc.ca/DigitalManifest/1/2005170`; page images saved alongside this file (`page-NNNN-<Month>_<Year>_p._N.jpg`, `manifest.json`).
- **Location / role:** Mobile Veterinary Section of the 1st Canadian Division — received sick and wounded animals evacuated from all four divisions and attached units of the Canadian Corps. Stationed a few miles west of Vimy Ridge in April 1917 (per McEwen, "The Sacrifice of Horses", JMSS vol. 18 no. 2, citing this diary 9–21 April 1917).

## Access (how the pages were fetched — for future runs)
- LAC Collection Search record found via the live browser (exact-phrase search for "1st Canadian Mobile Veterinary Section" returned 0 results; broadened search "Mobile Veterinary Section war diaries" found it, result 3 of 26). No human-verification page appeared.
- The viewer is LAC's harmonized viewer. Its IIIF manifest lives at `https://digitalmanifest.bac-lac.gc.ca/DigitalManifest/{sourceCode}/{itemNumber}`; sourceCode `1` = fonandcol. The manifest itself fetches fine with plain curl.
- Each manifest item's body id is a `https://central.bac-lac.gc.ca/.item/?id=<ecopy>&app=fonandcol&op=img` URL, which redirects to a `https://data2.archives.ca/.../*.jpg`. Ecopy numbers are NOT sequential (gaps), so always use the manifest, never guess ecopies.
- `download-pages.sh` downloads all 613 pages from the manifest (sequential, polite pace, resumable — skips files already present).

## Contents
- `manifest.json` — LAC IIIF manifest for the whole diary (613 items, March 1915 p. 1 – March 1919 p. 8).
- `page-NNNN-<Month>_<Year>_p._N.jpg` — diary page images as downloaded from LAC.
- `download-pages.sh` / `download.log` — download script and log.
- `transcript-YYYY-MM.md` — one monthly transcript per month (49 files), written by parallel subagents and verified on disk.
- `zoom-*.jpg` — enlarged crops used to verify hard readings (working aids, not part of the diary).

## Progress
- Transcription COMPLETE — 2026-10-26, Eighth G, run 4: all 613 pages read and transcribed into 49 monthly transcripts (`transcript-1915-03.md` … `transcript-1919-03.md`), by seven parallel subagents (one per period) and verified on disk (49 files, 805,125 bytes, all flagged COMPLETE, no missing months).
- Index entries in `INDEX-G.md`: COMPLETE — 1,520 dated entries (Mar 1915–Mar 1919, 49 month sections), built from the 49 transcripts in three parts and merged; INDEX-G.md now holds 1,762 entries total (242 Mobile Laboratory + 1,520 Mobile Veterinary Section), verified programmatically (date range, month sections, duplicate-date check). 26 dates have no diary entry (listed in the INDEX-G.md footer); 54 dates have two entries (separate diary rows for the same date).
- Overall: 613 of 613 pages transcribed; 1,520 index entries. Diary DONE.

## Glossary (expansions, not in the diary)
- M.V.S. = Mobile Veterinary Section. D.D.V.S. = Deputy Director of Veterinary Services. O.C. = Officer Commanding. S.O.S. = struck off strength.
