# No. 1 Railhead Supply Detachment, CASC — war diary

## Identity
- **Unit:** No. 1 Railhead Supply Detachment, Canadian Army Service Corps (LAC record title: "War diaries - No. 1 Railhead Supply Detachment").
- **Diary:** 17 January 1916 – 31 May 1917 (per the LAC guide, "Guide to Sources Relating to Units of the Canadian Expeditionary Force — Canadian Army Service Corps", p. 23).
- **Archival reference:** RG 9 III-D-3, vol. 5021, file 780; microfilm reel T-10906 (from the IIIF manifest metadata).
- **LAC Collection Search:** Item ID 2005016 — https://recherche-collection-search.bac-lac.gc.ca/eng/Home/Record?app=fonandcol&IdNumber=2005016
- **Permanent link:** https://central.bac-lac.gc.ca/.redirect?app=fonandcol&id=2005016&lang=eng
- **Page images:** 69 in the LAC viewer (17 monthly volumes, Jan 1916 – May 1917; 4 pages per month, 5 for March 1916). Fetched from LAC via the IIIF manifest `https://digitalmanifest.bac-lac.gc.ca/DigitalManifest/1/2005016`; page images saved alongside this file (`page-NNNN-<Month>_<Year>_p._N.jpg`, `manifest.json`).
- **Background (LAC guide):** Organized at Valcartier in September 1914 under the command of Captain L. S. Baker. Arrived in England October 1915. Strength: 1 officer, 18 other ranks. Arrived in France 18 January 1916.
- **How the record was found:** the guide gives only vol. 5021 (no folder/item number). The item number was found by probing nearby LAC item IDs through the IIIF manifest endpoint (2004980–2005100): 2005016 is titled "War diaries - No. 1 Railhead Supply Detachment", sitting between the 5th Cavalry Divisional Supply Column (2005015) and No. 2 Railhead Supply Detachment (2005017, 47 pages). The neighbouring No. 2 detachment is QUEUE-G.md item 9 — a separate diary, not part of this one.

## Access (how the pages were fetched — for future runs)
- LAC Collection Search result/record pages are bot-blocked for plain curl and for `browser.open` (403 "Human verification needed"); the record was found by probing the IIIF manifest endpoint directly, which fetches fine with plain curl.
- The viewer is LAC's harmonized viewer. Its IIIF manifest lives at `https://digitalmanifest.bac-lac.gc.ca/DigitalManifest/{sourceCode}/{itemNumber}`; sourceCode `1` = fonandcol. The manifest itself fetches fine with plain curl.
- Each manifest item's body id is a `https://central.bac-lac.gc.ca/.item/?id=<ecopy>&app=fonandcol&op=img` URL, which redirects to a `https://data2.archives.ca/.../*.jpg`. Ecopy numbers are NOT sequential (gaps), so always use the manifest, never guess ecopies.
- `download-pages.sh` downloads all 69 pages from the manifest (sequential, polite pace, resumable — skips files already present).

## Contents
- `manifest.json` — LAC IIIF manifest for the whole diary (69 items, January 1916 p. 1 – May 1917 p. 4).
- `page-NNNN-<Month>_<Year>_p._N.jpg` — diary page images as downloaded from LAC.
- `download-pages.sh` / `download.log` — download script and log.
- `transcript-1916-01.md` … `transcript-1917-05.md` — monthly transcripts (17 files).
- `zoom-*.jpg` — enlarged crops used to verify hard readings (working aids, not part of the diary).

## Progress
- January 1916 – May 1917: COMPLETE (all 69 pages) — 2026-10-28 (Eighth G, run 10). 17 monthly transcripts (`transcript-1916-01.md` … `transcript-1917-05.md`, 1,935 lines), transcribed by three parallel subagents (Jan–Jun 1916, Jul–Dec 1916, Jan–May 1917) plus the parent run (June 1916 diary text, pp. 3–4). One page spot-checked by the parent run (August 1916 p. 3, 9 Aug gas attack) against its transcript — matches.
- Overall: 69 of 69 pages transcribed; index entries being built into `INDEX-G.md` (see below).
- Diary content: handwritten Army Form C. 2118 throughout (January 1916 diary text is typed). The detachment stayed at Reninghelst Siding, France, from 7 April 1916 to the end of the diary; nearly every day reads "Men employed on Railhead Supply Duties" with a weather note. Notable items: move to France (embarked Southampton 17 Jan 1916 on the steamer "Sou'wester Millar", landed Le Havre 18 Jan; Abbeville, then Bailleul 11–12 Feb); move to Reninghelst Siding 7 Apr 1916, issuing to 3rd Canadian Division from 8 Apr, Corps Troops from 12 Apr, 2nd Canadian Division from 15 Apr; 2nd Canadian Division started drawing [supplies] 8 June 1916; gas attack 9 Aug 1916 (alarm 10.50 p.m., fumes reached camp 11.15 p.m., no casualties); gas warnings/alerts 28–30 Apr and 28/30 May 1916. Casualties: Pte. McBride accidentally wounded in the left eye by gunshot 17 Feb 1916 (hospital, operations, discharged 21 Mar); Pte. Hay knee injury 15 Mar 1916 (evacuated to Base Hospital 16 Mar); Pte. Belleau to hospital 26 Apr, re-admitted 14 May, evacuated to Base 30 May 1916 (struck off strength from 23 May). Command: Capt. L. S. Baker (Jan 1916); T/2nd Lt. S. B. H. Coppard temporary command 27 Jan; Capt. C. S. Lougheed from Feb/Mar 1916 (on leave 2–15 June, 2nd Lieut. G. F. L. Circuitt temporarily in command; Circuitt proceeded to Hippenhoek [uncertain] 16 June); Circuitt took over 25 July; Capt. J. H. Sproule assumed command 12 Aug 1916; 2/Lieut. C. F. Tatham signs as acting O.C. in September 1916; Lieut. G. A. [uncertain] signs Feb–Mar 1917.
- Uncertain items: 237 transcript lines carry [uncertain] flags across the 17 transcripts — mostly remarks-column initials (flowing hand, read as "C.S.L." / "G.H.C." / "J.H.S." / "C.F.T." / "G.T.L." with low confidence), the 9 Aug 1916 gas-attack parenthetical place words, the 16 June 1916 destination "Hippenhoek", and several names (Lt. [uncertain] Fry, Lieut. G. A. [uncertain]).
- No appendices in any month; no map coordinates are given in this diary.
