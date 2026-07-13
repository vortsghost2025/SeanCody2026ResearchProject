# SESSION 028 — Jeremiah Reynolds Bridge Verification Brief

**Target:** `BRIDGE-032-003`  
**Related question:** `RQ-032`  
**Mode:** narrow public-source verification  
**Status:** OPEN — return acquisition only

## Objective

Test whether Jeremiah N. Reynolds was merely the same person who moved from Symmes's Hollow Earth lecture circuit into Antarctic exploration advocacy, or whether specific ideas, language, contacts, or institutional pathways moved with him.

The task must allow all outcomes:

- documented influence;
- exposure opportunity only;
- personal contact without conceptual transmission;
- deliberate abandonment/reframing;
- independent exploration advocacy;
- negative evidence.

## Required artifact set

Locate exact, dated, item-level records for as many of these as possible:

1. Symmes Circular No. 1 (1818), preferably an institutional scan.
2. Reynolds/Symmes lecture notices, pamphlets, newspaper reports, or correspondence from the 1820s.
3. Reynolds's memorials, petitions, speeches, or correspondence seeking an Antarctic/South-Seas expedition.
4. Reynolds's 1836 *Address on the Subject of a Surveying and Exploring Expedition to the Pacific Ocean and South Seas*.
5. John Quincy Adams diary entries or correspondence mentioning Reynolds and Symmes's theory.
6. Congressional committee reports, Navy correspondence, or expedition-funding records naming Reynolds.
7. Poe's 1837 review of Reynolds and the relevant 1838 *Pym* passages.

## Required metadata for each source

```text
exact title
creator
publication or document date
edition / issue / volume
publisher / printer / newspaper
institution / archive
catalogue ID / call number / shelfmark
stable scan or transcript URL
page or image number
exact quotation
source type: primary / scholarly secondary / later summary
```

## Core tests

### Test A — Personal-contact record

Document Reynolds's actual relationship with Symmes:

- dates of collaboration;
- lecture locations;
- publications or notices naming both;
- correspondence or contemporary descriptions;
- date and nature of any break.

### Test B — Lexical continuity

Search Reynolds's later exploration texts for exact or near-exact language from the Hollow Earth period:

- open at the poles;
- habitable interior;
- warm/rich land;
- expedition as proof;
- specific percentages, coordinates, mottos, or unusual phrasing.

Do not rely only on keyword absence. Record transcription quality and search limitations.

### Test C — Rhetorical transformation

Compare what Reynolds retains, adds, removes, and reframes:

```text
Symmes/Hollow Earth period
        ↓
commercial/scientific/national exploration advocacy
```

Determine whether the later case rests on:

- commerce and whaling/sealing;
- national prestige;
- navigation and hydrography;
- natural history;
- scientific discovery;
- explicit polar-opening theory;
- or a mixture.

### Test D — Institutional carrier

Identify the people and institutions through which Reynolds's advocacy moved:

- newspapers;
- lecture venues;
- publishers;
- Congress;
- Committee on Naval Affairs;
- Navy Department;
- presidents or cabinet officers;
- scientific societies;
- commercial interests.

An institution recording or hearing Reynolds does not equal endorsement.

### Test E — Reynolds → Poe text reuse

Align exact passages from Reynolds's 1836 *Address* with Poe's review and *Pym*.

Return:

- Reynolds page/image number;
- Poe page/chapter;
- exact overlapping wording;
- length of overlap;
- reliable scholarly source discussing the reuse;
- whether the reused material concerns Antarctic exploration specifically.

This test may produce a separate `DIRECT_CITATION` or `KNOWN_COPY` edge even if the Reynolds Hollow Earth→exploration bridge remains uncertain.

### Test F — Disproof and negative evidence

Actively look for evidence that:

- Reynolds explicitly repudiated Symmes's theory;
- his expedition advocacy began from independent commercial or scientific motives;
- contemporaries distinguished the exploration proposal from Hollow Earth belief;
- no Hollow Earth language appears in reliable later primary texts;
- later historians retroactively overstate the causal role of Symmes.

## Deliverables

1. Five to twelve item-level source records.
2. A dated Reynolds chronology from Symmes collaboration through the 1836 *Address* and expedition lobbying.
3. Exact quotations with page/image locators.
4. A transformation table: retained / added / removed / reframed.
5. A contact and institutional-carrier table.
6. Reynolds→Poe parallel-text table.
7. Evidence for and against causal influence.
8. Failed-search log.
9. Recommended classification for each possible edge.
10. No canonical promotion; curator review required.

## Copy-paste cloud-agent prompt

> Read `RESEARCH_ATLAS.md`, `CROSS_DOMAIN_BRIDGE_ATLAS.md`, `schemas/BRIDGE_CANDIDATE.md`, `research_questions/RQ-032-HIDDEN-CROSS-DOMAIN-BRIDGES.md`, `reports/SESSION_028_BRIDGE_CROSS_VARIANT_QC.md`, and `graph/bridges/RQ-032-ANTARCTICA-HOLLOW-EARTH-CANDIDATES.md`. Execute `research_inbox/SESSION_028_REYNOLDS_BRIDGE_VERIFICATION_BRIEF.md`. Work only on Jeremiah N. Reynolds. Locate item-level primary records for his Symmes collaboration, lecture activity, break from Symmes, Antarctic/South-Seas expedition advocacy, 1836 Address, presidential or congressional contacts, and Poe's review/text reuse. Return exact titles, dates, institutions, catalogue identifiers, stable scans, pages, and quotations. Test both continuity and discontinuity. Distinguish personal contact, exposure opportunity, documented influence, direct citation, known copying, and negative evidence. Do not assume that being the same person proves the earlier theory caused the later expedition program. Do not commit or create canonical edges.
