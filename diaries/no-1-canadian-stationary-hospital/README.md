# No. 1 Canadian Stationary Hospital — war diary

## Identity
- **Unit:** No. 1 Canadian Stationary Hospital (LAC record title: "War diaries - 1st Canadian Stationary Hospital = Journal de guerre - 1er Hôpital fixe canadien")
- **Diary:** 15 September 1914 – 28 September 1917
- **Archival reference:** RG 9 III-D-3, vol. 5033, file 842; microfilm reel T-10922; finding aid 9-52
- **LAC Collection Search:** Item ID 2005086 — https://recherche-collection-search.bac-lac.gc.ca/eng/Home/Record?app=fonandcol&IdNumber=2005086
- **Permanent link:** https://central.bac-lac.gc.ca/.redirect?app=fonandcol&id=2005086&lang=eng
- **Page images:** 73 in the LAC viewer (17 monthly volumes, September 1914 – September 1917). Fetched from LAC via the IIIF manifest `https://digitalmanifest.bac-lac.gc.ca/DigitalManifest/1/2005086`; page images saved alongside this file (`page-NNNN-<Month>_<Year>_p._N.jpg`, `manifest-2005086.json`).
- **Location / role:** a 300–400-bed stationary hospital of the Canadian Army Medical Corps — mobilized at Valcartier, served at Hampstead, then in France (Wimereux), then in the Mediterranean (Lemnos, Salonica), and returned to England in September 1917, where it became No. 13 Canadian General Hospital at Hastings.

## Access (how the pages were fetched — for future runs)
- LAC Collection Search record found via the live browser. LAC's site repeatedly blocked navigation with Cloudflare browser validation and a 403 "Human verification needed" page; the block was eventually cleared via the 403 page's "I am a human" link, after which every record page for files 840–847 was opened and verified.
- **Files 840–847 are NOT folders of this diary.** Each file in RG 9 III-D-3, vol. 5033 is a separate LAC item for a different medical unit: file 840 = 3rd Canadian Casualty Clearing Station (Item 2005084), file 841 = 4th Canadian Casualty Clearing Station (2005085), file 842 = this diary (2005086), file 843 = 2nd Canadian Stationary Hospital (2005087), file 844 = 3rd Canadian Stationary Hospital (2005088), file 845 = 4th Canadian Stationary Hospital (2005089), file 846 = 5th Canadian Stationary Hospital (2005090), file 847 = 7th Canadian Stationary Hospital (2005091). Item 2005086 is the ONLY LAC record for the 1st Canadian Stationary Hospital diary.
- The viewer is LAC's harmonized viewer. Its IIIF manifest lives at `https://digitalmanifest.bac-lac.gc.ca/DigitalManifest/{sourceCode}/{itemNumber}`; sourceCode `1` = fonandcol. The manifest itself fetches fine with plain curl.
- Each manifest item's body id is a `https://central.bac-lac.gc.ca/.item/?id=<ecopy>&app=fonandcol&op=img` URL, which redirects to a `https://data2.archives.ca/.../*.jpg`. Ecopy numbers are NOT sequential (gaps), so always use the manifest, never guess ecopies.
- `download-pages.sh` downloads all 73 pages from the manifest (sequential, polite pace, resumable — skips files already present). The script was copied from the No. 1 Canadian Sanitary Section diary and pointed at `manifest-2005086.json`.

## Contents
- `manifest-2005086.json` — LAC IIIF manifest for the whole diary (73 items, September 1914 p. 1 – September 1917 p. 2).
- `page-NNNN-<Month>_<Year>_p._N.jpg` — diary page images as downloaded from LAC.
- `download-pages.sh` / `download-2005086.log` — download script and log.
- `transcript-YYYY-MM.md` — one monthly transcript per month (21 files; see below for the multi-month volumes).
- `INDEX-G-part4.md`, `INDEX-G-part5.md` — index-building working files (merged into `../../INDEX-G.md`).

## Progress
- Transcription COMPLETE — 2026-10-27, Eighth G, run 6: all 73 pages read and transcribed into 21 monthly transcripts by three parallel subagents, verified on disk (21 files).
- Index entries in `INDEX-G.md`: COMPLETE — 206 dated entries (Sep 1914–Sep 1917, 24 month sections), built from the 21 transcripts in two parts and merged; INDEX-G.md now holds 3,408 entries total (242 Mobile Laboratory + 1,520 Mobile Veterinary Section + 1,440 Sanitary Section + 206 Stationary Hospital), verified programmatically (date range, month sections, 12 multi-entry dates, sorted order).

## Monthly volumes — coverage notes
- **Volume I (September 1914, pp. 1–4) covers 15 September – 12 November 1914** — October and November 1914 entries are on pp. 3–4 of the September-labelled set, transcribed in `transcript-1914-10.md` and `transcript-1914-11.md`. There are no separate October or November 1914 volumes.
- **No diary pages at all for December 1914, January 1915, February–May 1916, or January–July 1917.** The LAC item's 73 pages are fully accounted for by the other volumes.
- **February 1915 (pp. 5–7) covers 1–24 February**; the 31 March entry sits on p. 2 of the April set and is transcribed in `transcript-1915-03.md`.
- **March 1915 (pp. 8–9) covers 13–24 March** plus the 31 March entry from the April set (Volume 2's cover date was corrected from 24th to 31st March).
- **July 1915 volume (pp. 28–40) covers 1 July – 30 August 1915** — the cover says "To 31st August" with "31st" corrected to "30th"; August entries (pp. 6–13) are transcribed in `transcript-1915-08.md`.
- **December 1915 volume (pp. 54–59) covers 1 December 1915 – 31 January 1916** — January 1916 entries (pp. 5–6) are transcribed in `transcript-1916-01.md`.
- **June 1916 volume (pp. 60–62) covers 3 June – 31 August 1916** — July and August 1916 entries are transcribed in `transcript-1916-06.md`.
- **September 1916 volume (pp. 63–64) covers 1 September – 31 October 1916** — October 1916 entries are transcribed in `transcript-1916-09.md`.
- **September 1917 (pp. 72–73) covers 4–28 September 1917**; the 3 September entry stands at the foot of p. 71 (August 1917, p. 3) and is transcribed in `transcript-1917-09.md`.
- The diary is handwritten Army Form C.2118 through 1915 (a few typewritten pages from June 1916 on); from June 1916 it is kept as weekly summaries rather than daily entries. 70 `[uncertain]` flags across the transcripts (counted in the files; the two index builders' per-part tallies differ slightly from this file count because of repeated boilerplate convention lines).

## Commanding officers
- Lieut-Col. Lorne Drum — organised the hospital at Valcartier, September 1914 (per the LAC guide).
- Major E. J. Williams — assumed temporary command October 1915; Officer Commanding November 1915; Lieut-Col. E. J. Williams, D.S.O., signs the September 1917 diary (stamp: Officer Commanding No. 13 Canadian General Hospital, Hastings).
- Major C. H. Morris — signs the November and December 1916 pages; became O.C. during Lt-Col. Williams' absence in December 1916.

## Notable content
- **Mobilization and France:** mobilized at Valcartier 15 September 1914, sailed from Quebec on the Athenia 30 September; Hampstead November 1914 – February 1915; sailed from Southampton on the troop transport Huanchaco 1–3 February 1915, disembarked at Le Havre and camped at Camp No. 6; moved to Boulogne 23–24 February; established a 300-bed tented hospital at Honeault/Honveault Camp, Wimereux, in March; first thirty cases received 3 April 1915.
- **Gas cases (Second Battle of Ypres):** first gas case received 3 May 1915, with a detailed symptom list (intense dyspnoea and cyanosis to slight bronchitis, severe conjunctivitis, severe headache, mental dulness, broncho-pneumonia with diarrhoea); one death from gas poisoning; a further 30 gas cases by 20 May. Gas cases had already been admitted in April. May admissions totalled 2,450 cases.
- **Clinical reporting:** the May 1915 diary is a clinical report — a 22-case trial of boracic paste wound treatment (helps only superficial wounds; seals in infection in deep wounds), operations chiefly removal of foreign bodies with Wright's solution after-treatment, one case of epidemic cerebro-spinal meningitis, no tetanus.
- **The move to the Mediterranean:** ordered 22 July 1915 to stop receiving patients and pack for Abbeville; 28 July a War Office wire orders equipment stored at Boulogne and the unit embarked for the Mediterranean; 30 July the personnel sail from Boulogne on the hospital ship St Patrick to Dover, entrain for Shorncliffe. 1 August they entrain for Southampton and embark on the hospital ship Asturias with Nos. 3 and 5 Canadian Stationary Hospitals; via Gibraltar, Malta and Alexandria they reach Lemnos 16 August and disembark at West Mudros, building a 600-bed camp of eastern-pattern marquees.
- **Lemnos — dysentery and trench feet:** dysentery dominates September–October 1915 (5,000 Australians arrive from the Peninsula mid-September, many with dysentery; 18 deaths in October, 90% dysentery; 4 deaths in September). A heavy electric storm floods the tents 15 September. November brings frostbite: hundreds of frozen-feet cases admitted 29 November (623 patients in hospital 30 November, 157 frostbite); 1 December 800 trench-feet cases treated in a day, 200 in hospital 6 December, 2 cases of tetanus following frostbite, one fatal. The hospital expands to 1,000 beds by 15 December.
- **Salonica — malaria:** at Salonica from 3 March 1916; malaria dominates the 1916 diary (39 N.C.O.s and men, 2 officers and 3 sisters developed malaria in August 1916 alone; capacity raised to 600 beds 15 July 1916; heat averaging 102°F in the shade at noon, rising to 106°F). German Taubes fly over the camp 4 and 6 November 1916 — the first air-raid mentions; frequent Taubes visits in December 1916, one anti-aircraft shell falling in the Officers' ward on a day whose date is not legible.
- **Unit deaths:** Cpl. Hoare, died 29 June 1916 after four days' illness (paratyphoid); Pte Furlong, died 21 August 1916 of status lymphaticus. Hospital deaths (patients) are given only as weekly totals.
- **The Great Fire of Salonica, 18 August 1917:** the town catches fire in the Turkish Quarters at 2 p.m.; by midnight half the city is burnt, over 100,000 people homeless; the fire is still burning 19 August; headquarters burnt out but all papers saved; streets under martial law, policed by French troops.
- **The voyage home and the end of the diary:** 3 September 1917 orders are received to embark next day; 4 September the officers and men embark on the Italian transport Regina Elena, in convoy with two other transports and three Italian torpedo boat destroyers; the convoy calls at Skyros, Milos, Navarino and Corfu, reaching Taranto 11 September. 27 September the officers and men are sent to Hastings and the nursing sisters to Basingstoke; 28 September the unit is ordered to take over the Canadian Military Hospital Hastings from No. 8 Canadian Stationary Hospital, the name to become No. 13 Canadian General Hospital. This is the last entry of the diary.
- **Named visitors:** Sir Robert Borden inspected the camp 20 July 1915 (with Generals Sawyer and Col Evans); Admiral Guepratte, French Mediterranean Fleet, visited the hospital 15 September 1915; General Birdwood visited 14 November 1915; Lord Kitchener inspected troops (but not the hospital) 11 November 1915; General Munro, who succeeded Sir Ian Hamilton, inspected troops and hospitals 27 October 1915.

## Glossary (expansions, not in the diary)
- C.A.M.C. = Canadian Army Medical Corps. O.C. = Officer Commanding. A.D.M.S. = Assistant Director of Medical Services. D.M.S. = Director of Medical Services. R.A.M.C. = Royal Army Medical Corps. S.O.S. = struck off strength. P.U.O. = pyrexia of unknown origin. Taube = German monoplane (literally "dove"), used here for enemy aircraft generally.
