# No. 1 Canadian Veterinary Hospital — war diary

## Identity
- **Unit:** No. 1 Canadian Veterinary Hospital (LAC record title: "War diaries - No. 1 Canadian Veterinary Hospital = Journal de guerre - Hôpital vétérinaire canadien no 1")
- **Diary:** April 1915 – March 1919
- **Archival reference:** RG 9 III-D-3, vol. 5044, file 894; microfilm reel T-10936; finding aid 9-52
- **LAC Collection Search:** Item ID 2005175 — https://recherche-collection-search.bac-lac.gc.ca/eng/Home/Record?app=fonandcol&IdNumber=2005175
- **Permanent link:** https://central.bac-lac.gc.ca/.redirect?app=fonandcol&id=2005175&lang=eng
- **Page images:** 241 in the LAC viewer (48 monthly volumes, April 1915 – March 1919). Fetched from LAC via the IIIF manifest `https://digitalmanifest.bac-lac.gc.ca/DigitalManifest/1/2005175`; page images saved alongside this file (`page-NNNN-<Month>_<Year>_p._N.jpg`, `manifest-2005175.json`).
- **Location / role:** one of eighteen Imperial veterinary hospitals on the lines of communication; supported not just Canadian equines but all horses of the Imperial Army. At its peak it had stabling for 1,364 horses, at one point with over 2,000 horses under care (per Canadian Military Journal, vol. 12 no. 2, Spring 2012).

## Access (how the pages were fetched — for future runs)
- LAC Collection Search record found by probing the IIIF manifest endpoint for item numbers adjacent to the No. 1 Canadian Mobile Veterinary Section (Item 2005170, vol. 5043, file 890): the veterinary units are grouped consecutively — 2005164 Assistant Director of Veterinary Services (Canadian Corps), 2005165–2005168 Deputy Assistant Directors of Veterinary Services (1st–4th Divisions), 2005169 "A" Mobile Veterinary Section, 2005170 No. 1 Mobile Veterinary Section, 2005171–2005172 No. 2, 2005173 No. 3, 2005174 No. 4, **2005175 No. 1 Veterinary Hospital**, 2005176 No. 2 Veterinary Hospital, 2005177 Canadian Corps Veterinary Evacuating Station, 2005178 5th CFA Brigade CAVC Section, 2005179 Canadian Remount Depot, 2005180 No. 100 Canadian Remount Squadron. Manifest labels carry the unit title, so the item was confirmed before downloading.
- The viewer is LAC's harmonized viewer. Its IIIF manifest lives at `https://digitalmanifest.bac-lac.gc.ca/DigitalManifest/{sourceCode}/{itemNumber}`; sourceCode `1` = fonandcol. The manifest itself fetches fine with plain curl.
- Each manifest item's body id is a `https://central.bac-lac.gc.ca/.item/?id=<ecopy>&app=fonandcol&op=img` URL, which redirects to a `https://data2.archives.ca/.../*.jpg`. Ecopy numbers are NOT sequential (gaps), so always use the manifest, never guess ecopies.
- `download-pages.sh` downloads all 241 pages from the manifest (sequential, polite pace, resumable — skips files already present). The script was copied from the No. 1 Canadian Stationary Hospital diary and pointed at `manifest-2005175.json`.

## Contents
- `manifest-2005175.json` — LAC IIIF manifest for the whole diary (241 items, April 1915 p. 1 – March 1919 p. 4).
- `page-NNNN-<Month>_<Year>_p._N.jpg` — diary page images as downloaded from LAC.
- `download-pages.sh` / `download-2005175.log` — download script and log.
- `transcript-YYYY-MM.md` — one monthly transcript per month (48 files), written by four parallel subagents (one per year) and verified on disk.

## Progress
- Transcription COMPLETE — 2026-10-27, Eighth G, run 7: all 241 pages read and transcribed into 47 monthly transcripts (`transcript-1915-04.md` … `transcript-1919-03.md`) by four parallel subagents (one per year), verified on disk (48 files including the May 1915 pointer note), plus a spot-check of transcript-1915-04.md p. 3 against its page image (faithful).
- Index entries in `INDEX-G.md`: COMPLETE — 1,267 dated entries (Apr 1915–Apr 1919, 48 month sections), built from the transcripts in two parts (`INDEX-G-VH-part1.md`, 696 entries; `INDEX-G-VH-part2.md`, 571 entries) and merged; INDEX-G.md now holds 4,675 entries total (242 Mobile Laboratory + 1,520 Mobile Veterinary Section + 1,440 Sanitary Section + 206 Stationary Hospital + 1,267 Veterinary Hospital), verified programmatically (date range, month sections, duplicate-date check).
- 268 `[uncertain]` flags across the transcripts.

## Monthly volumes — coverage notes
- **Volume 1 (April 1915, pp. 1–13) covers 1 April – 10 June 1915** — May 1915 entries and 1–10 June 1915 are inside this volume; there is no separate May 1915 volume. `transcript-1915-05.md` is a pointer note only. A second June volume (Volume 2, Capt. V. C. Leckie, 1–30 June) overlaps 1–10 June, so 1, 2, 8, 9, 10 June have two diary rows (Evans and Leckie accounts, both indexed and labelled).
- **No diary pages for 1–14 August 1915** — Volume 4 starts 15 August. Also no entries for 16 & 18 June 1915, 16 & 27 August 1915, 15–16 April 1915, 3–4 May 1915, and 21 March 1918 (blank).
- **September 1915 (pp. 45–46) are duplicate photographs of the same sheet.**
- **August 1915 under-treatment figure discrepancy:** 1 August figure (539) vs 31 July remaining (544) — 5 animals unreconciled, noted in the transcript.
- **September 1918 manifest label is French** ("Septembre 1918"); transcript filed as `transcript-1918-09.md`.
- **February 1918:** contents page claims "Diary Text 2 Pages" but only one diary-text page is present; entries run 3–28 February and the page is signed, so no text appears missing. The "22nd" date label appears twice (one corrected).
- **June 1917 appendices:** typed laboratory report (13,290 vaccine doses stated; 4,800 + 7,600 + 690 = 13,090 — discrepancy is in the original) and "Notes on Mange" (2,337 mange cases). Not dated diary entries; not indexed.
- **Volume-number discrepancy in every month from mid-1916 on:** covers say one volume number, diary-text title pages another (e.g. covers Vol. 24–35 vs title pages Vol. 17-4 to 18-3) — both transcribed as written.
- **The diary closes with "Embarked for England", dated 4 April 1919**, written below the signature on the March 1919 page; indexed as 1919-04-04.
- **Human casualties in the whole diary:** 13 Aug 1918 — one unnamed man killed in action by enemy aircraft; 27 Oct 1918 — one unnamed man died, no cause given. One man struck off as a deserter, 9 Dec 1918. No other human casualties; all other casualty figures are animal deaths, shootings or sales to the butcher.
- **Commanding officers:** Capt. T. C. Evans (Apr–Jun 1915, Aug–Dec 1915), Capt. V. C. Leckie (Jun–Aug 1915), Capt./Maj. C. G. Saunders (Dec 1915 – Aug 1917), Capt./Maj. S. C. Richards (Aug 1917 – Mar 1919).
- **Location:** Netheravon, England → Southampton → Havre (Le Havre), France, from 4 April 1915; remained at Havre throughout.
