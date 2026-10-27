# No. 1 Canadian Sanitary Section — war diary

## Identity
- **Unit:** No. 1 Canadian Sanitary Section, 1st Canadian Division (LAC record title: "War diaries - 1st Canadian Sanitary Section = Journal de guerre - 1re Section sanitaire canadienne")
- **Diary:** 7 February 1915 – 28 February 1919
- **Archival reference:** RG 9 III-D-3, vol. 5037, file 862, part 1 = 1915/02/07–1917/02/28, part 2 = 1917/03/01–1919/02/28; microfilm reel T-10927; finding aid 9-52
- **LAC Collection Search:** Item ID 2005113 — https://recherche-collection-search.bac-lac.gc.ca/eng/Home/Record?app=fonandcol&IdNumber=2005113
- **Permanent link:** https://central.bac-lac.gc.ca/.redirect?app=fonandcol&id=2005113&lang=eng
- **Page images:** 382 in the LAC viewer (49 monthly volumes: February 1915 – February 1919). Fetched from LAC via the IIIF manifest `https://digitalmanifest.bac-lac.gc.ca/DigitalManifest/1/2005113`; page images saved alongside this file (`page-NNNN-<Month>_<Year>_p._N.jpg`, `manifest.json`).
- **Location / role:** Sanitary Section of the 1st Canadian Division — inspected latrines, incinerators, water supplies, baths and billets; investigated infectious disease (typhoid, diphtheria, measles, meningitis, dysentery); ran a Rest Station and convalescent camp in 1915; served in France and Belgium throughout, then marched to the Rhine with the 13th Canadian Field Ambulance after the Armistice, ending at Huldenberg, Belgium.

## Access (how the pages were fetched — for future runs)
- LAC Collection Search record found via the live browser (search `"1st Canadian Sanitary Section" war diaries` returned 1 result). No human-verification page appeared.
- The viewer is LAC's harmonized viewer. Its IIIF manifest lives at `https://digitalmanifest.bac-lac.gc.ca/DigitalManifest/{sourceCode}/{itemNumber}`; sourceCode `1` = fonandcol. The manifest itself fetches fine with plain curl.
- Each manifest item's body id is a `https://central.bac-lac.gc.ca/.item/?id=<ecopy>&app=fonandcol&op=img` URL, which redirects to a `https://data2.archives.ca/.../*.jpg`. Ecopy numbers are NOT sequential (gaps), so always use the manifest, never guess ecopies.
- `download-pages.sh` downloads all 382 pages from the manifest (sequential, polite pace, resumable — skips files already present).

## Contents
- `manifest.json` — LAC IIIF manifest for the whole diary (382 items, February 1915 p. 1 – February 1919 p. 4).
- `page-NNNN-<Month>_<Year>_p._N.jpg` — diary page images as downloaded from LAC.
- `download-pages.sh` / `download.log` — download script and log.
- `transcript-YYYY-MM.md` — one monthly transcript per month (47 files; see below for the two-month volumes).
- `INDEX-G-part1.md`, `INDEX-G-part2.md`, `INDEX-G-part3.md` — index-building working files (merged into `../../INDEX-G.md`).

## Progress
- Transcription COMPLETE — 2026-10-27, Eighth G, run 5: all 382 pages read and transcribed into 47 monthly transcripts by five parallel subagents, verified on disk (47 files, 601,161 bytes).
- Index entries in `INDEX-G.md`: COMPLETE — 1,440 dated entries (Feb 1915–Feb 1919, 49 month sections), built from the 47 transcripts in three parts and merged; INDEX-G.md now holds 3,202 entries total (242 Mobile Laboratory + 1,520 Mobile Veterinary Section + 1,440 Sanitary Section), verified programmatically (date range, month sections, 25 multi-row dates, 70 within-range dates with no diary entry — reconciles exactly with the 1,483-day calendar span 7 Feb 1915 – 28 Feb 1919).

## Monthly volumes — coverage notes
- **February 1915 (Volume 1, pp. 1–15) covers 7 Feb – 31 Mar 1915** — March 1915 entries are on pp. 10–15, transcribed in `transcript-1915-02.md`. There is no separate March 1915 volume in the LAC manifest.
- **April 1915 (Volume 2, pp. 16–29) covers 1 Apr – 31 May 1915** — May 1915 entries are on pp. 8–14, transcribed in `transcript-1915-04.md`. There is no separate May 1915 volume in the LAC manifest.
- **March 1916 (pp. 150–153) covers 12–31 March only** — the diary itself begins 12 March (cover corrected from "1st" to "12th" on the change of command from Major Amyot to Capt. Lawton). No 1–11 March entries exist; no entry for 13 March.
- All other months cover the full calendar month. The diary is handwritten Army Form C.2118 throughout (a few typed covers/contents pages); 488 `[uncertain]` flags across the transcripts.

## Commanding officers
- Major T. A. Starkey — organised the section at Valcartier as 1st Canadian Divisional Sanitary Section (per the LAC guide).
- Major R. E. Wodehouse ("Woodhouse" in the diary) — took command at the January 1915 reorganisation at Lark Hill, Salisbury Plain; O.C. until 16 Sep 1915.
- Major J. A. Amyot — O.C. from 16 Sep 1915 (took over from Major Woodhouse) to 14 Mar 1916.
- Capt. W. C. Lawson (spelled "Lawton" in the March 1916 diary and in later signatures — the two spellings both appear; transcribed as written) — O.C. 14 Mar 1916 – 1 Aug 1917, when he left to become Corps Sanitary Officer, Canadian Corps.
- Capt. A. J. Lomas — O.C. 1 Aug 1917 – 20 Jan 1918 (Capt. A. B. Chapman relieved him 30 Sep – 11 Oct 1917 while he was on leave).
- Major A. B. Chapman — O.C. from 20 Jan 1918 to the end of the diary (28 Feb 1919).

## Notable content
- **Second Battle of Ypres (23–26 Apr 1915):** the section dressed wounded and evacuated them for No. 3 Field Ambulance, its lorry carrying 21–26 slightly wounded and up to 20 gas cases per trip, active 24 hours; then ran a Rest Station (167 patients admitted by 31 May).
- **23 November 1917 — the section's heaviest casualty event:** its billets at Hersin were struck by shell — 8 men killed, 30 wounded (no names given in the diary); survivors evacuated to No. 4 Canadian Field Ambulance, Grand Servins.
- **Vimy Ridge, 9 Apr 1917:** Lawson spent the day at Ambulance Corner and Aux Rutz assisting the walking wounded and sent a Staff Sergeant and 12 men to assist the 2nd 7th Ambulance (the battle is not named in the diary).
- **Armistice, 11 Nov 1918:** "Peace day — news received very calmly." President Poincaré visited Valenciennes the day before.
- **Disease work throughout:** typhoid/enteric and para-typhoid enquiries (house-to-house surveys, suspicious houses out of bounds), measles, cerebro-spinal meningitis, scarlet fever, diphtheria (including a Jan 1916 outbreak at the Convent orphanage, St-Jans Cappel — whole convent of 100 immunized by 22 Jan), mumps, dysentery, foot-and-mouth disease at a farm (26 Dec 1915 — 14 cows sick, 2 died, 12 pigs died, 2 humans affected), influenza sweeping the unit 29 Jun 1918.
- **Sanitary engineering:** the Divisional Sanitary Exhibit at Aldershot Camp (Aug 1915, with drawn ground plan and appendix drawings of a field incinerator and a fly-proof odourless latrine); the louse plague (Cresol soaks, boiling, steam disinfectors — a third disinfector at Bulford Camp doing 60–80 blankets/hour at 220°F); the "fire-less cooker" tested Nov–Dec 1915; a Foden lorry bath-shower attachment in operation 30 Sep 1916 (50 men of Div Train bathed).
- **Named visitors:** the Prince of Wales (took the officers' billet at Hinges, 19 May 1915); H.R.H. the Duke of Connaught (visited HQ, 30 Oct 1916); King Albert of Belgium and Field Marshal Haig (17 May 1917); King George V (inspected a battalion near the lines, 11 July 1917).
- **No other section casualties** are recorded as killed or wounded; the section acted as burial squads (22 May 1915) and its Nieppe billets were shelled 24 Jul 1915 with no casualties recorded.

## Glossary (expansions, not in the diary)
- S.O.S. = struck off strength. C.A.M.C. = Canadian Army Medical Corps. O.C. = Officer Commanding. A.D.M.S. = Assistant Director of Medical Services. D.D.M.S. = Deputy Director of Medical Services. D.D.V.S. = Deputy Director of Veterinary Services.
