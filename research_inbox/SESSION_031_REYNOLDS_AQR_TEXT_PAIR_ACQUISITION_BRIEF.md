# SESSION 031 — Reynolds / *American Quarterly Review* Text-Pair Acquisition Brief

**Target:** `BRIDGE-032-003A` and `BRIDGE-EDGE-002`  
**Related question:** `RQ-032`  
**Mode:** two-text primary-source acquisition and comparison  
**Status:** OPEN — acquisition only

## Closed question

Do not spend time re-authenticating the bibliographic existence of Reynolds's pamphlet. Session 030 accepted the Library of Congress catalogue record:

```yaml
title: "Remarks on a review of Symmes' theory, which appeared in the American quarterly review"
creator: "Reynolds, J. N. (Jeremiah N.), 1799-1858"
place: Washington
printer: "Gales & Seaton"
year: 1827
loc_item: "06040937"
call_numbers:
  - "AC901 .M5 vol. 797, no. 14"
  - "YA 25425"
```

The open question is the content.

## Objective

Acquire and compare:

1. the anonymous or unresolved 1827 *American Quarterly Review* article reported as `Symmes's theory`, volume 1, beginning at page 235;
2. Reynolds's 1827 pamphlet responding to a review of Symmes's theory.

Determine whether Reynolds's response:

- defends Symmes;
- accepts only part of the theory;
- modifies or corrects it;
- uses it strategically to advocate exploration;
- distances himself from it;
- or rejects it.

## Required source record A — AQR article

Return:

```text
exact article heading from page image
publication title
volume / issue
month or issue date
complete page range
creator or anonymity status
publisher / editor / printer
institution / archive
catalogue ID / shelfmark
stable volume page
stable scan / IIIF / image sequence
```

Confirm that the article beginning at page 235 is the exact review named by Reynolds. Do not infer this solely from matching topic and year.

## Required source record B — Reynolds pamphlet

Return:

```text
exact title-page transcription
creator exactly as printed
city
printer / publisher
date
page extent
institution / collection
call number / shelfmark
stable catalogue page
stable scan / image sequence
```

A catalogue record without page images is not enough for this session's content test.

## Exact content extraction

For each text, transcribe passages with page/image locators concerning:

- hollow Earth or concentric spheres;
- polar openings;
- interior habitability;
- warm or rich polar lands;
- Symmes's evidence and authority;
- proposed expeditions as tests;
- Southern Ocean or South-Pole exploration;
- scientific, commercial, national, or naval rationales;
- ridicule, uncertainty, qualification, or rejection;
- named sources, explorers, maps, or observations.

## Response alignment table

Create a table:

| AQR claim | AQR page | Reynolds response | Reynolds page | Response type |
|---|---:|---|---:|---|

Allowed response types:

- `DIRECT_DEFENSE`
- `PARTIAL_DEFENSE`
- `CORRECTION`
- `QUALIFICATION`
- `COUNTEREVIDENCE`
- `STRATEGIC_REFRAMING`
- `CONCESSION`
- `REJECTION`
- `NO_RESPONSE_LOCATED`

## Chronology comparison

Place the text pair against:

```text
reported Reynolds–Symmes personal break: circa 1825
John Quincy Adams "varied his purpose": 1826-11-04
AQR review and Reynolds response: 1827
Reynolds recognized as South-Pole expedition projector: 1828
Reynolds institutional Address: 1836
```

Determine whether the 1827 text supports:

- `CONTINUITY_SUPPORTED`;
- `PARTIAL_CONTINUITY`;
- `STRATEGIC_REFRAMING`;
- `DISCONTINUITY_SUPPORTED`;
- `MIXED_OR_UNRESOLVED`.

## 1836 comparison

Compare distinctive 1827 wording with the 1836 *Address* for:

- `Symmes`;
- `hollow`;
- `interior`;
- `opening` / `open at the poles`;
- `habitable`;
- `warm and rich land`;
- expedition as proof;
- South Pole / Southern Ocean;
- national, scientific, commercial, and naval rationales.

Broad shared words such as `exploration` or `pole` do not prove lexical continuity.

## Title-error side test

The correct title is:

> *Remarks on a review of Symmes' theory, which appeared in the American quarterly review*

The common mutated title is:

> *Remarks of Symmes' Theory Which Appeared in the American Quarterly Review*

Record only high-value dated occurrences found during the text search. Do not broaden into a general web scrape. Capture:

- exact page title;
- date or archive timestamp;
- wording;
- attribution/source cited;
- whether the page mirrors another source.

This side test feeds `ERR-032-001`; it does not replace the primary text acquisition.

## Failure outcomes

If one or both texts cannot be acquired, return:

- every catalogue searched;
- title variants used;
- collection and call-number restrictions;
- access or viewer failures;
- whether reproduction must be ordered from LOC;
- the narrowest next action needed.

Do not infer the pamphlet's doctrinal position from the catalogue title alone.

## Deliverables

1. Exact source records for both texts, or documented failed-source records.
2. Page/image transcriptions.
3. Claim-by-claim response table.
4. Chronology assessment.
5. 1827-to-1836 phrase comparison.
6. Evidence for and against doctrinal continuity.
7. Title-error side findings.
8. Failed-search log.
9. Recommended classification, not a self-promotion.
10. No canonical edge creation.

## Copy-paste cloud-agent prompt

> Read `RESEARCH_ATLAS.md`, `CROSS_DOMAIN_BRIDGE_ATLAS.md`, `graph/bridges/BRIDGE-032-003-REYNOLDS-PIVOT.md`, `graph/chronologies/REYNOLDS-1827-REMARKS-CATALOG-RECORD.md`, `reports/SESSION_030_REYNOLDS_1827_QC.md`, `graph/transmissions/BRIDGE-EDGE-002-AQR-REYNOLDS-RESPONSE-CANDIDATE.md`, and `data/error_fingerprints/ERR-032-001-REYNOLDS-REMARKS-TITLE.md`. Execute `research_inbox/SESSION_031_REYNOLDS_AQR_TEXT_PAIR_ACQUISITION_BRIEF.md`. Do not re-authenticate the LOC catalogue record and do not write a broad Reynolds biography. Acquire exact page images or trustworthy transcriptions of both the 1827 *American Quarterly Review* article reported as `Symmes's theory`, vol. 1, p. 235 onward, and Reynolds's 1827 *Remarks on a review of Symmes' theory...*. Verify that they are the matching review-and-response pair. Return complete metadata, page ranges, exact quotations, and a claim-by-claim response table showing whether Reynolds defends, qualifies, modifies, strategically reframes, concedes, or rejects the reviewed theory. Compare distinctive language with Reynolds's 1836 *Address*. Return failed searches and access barriers. Do not create a canonical edge.
