# SESSION 032 — `A Citizen of the United States` / *National Intelligencer* Bridge Brief

**Targets:** `ERR-032-002`, `BRIDGE-032-003`  
**Related question:** `RQ-032`  
**Mode:** narrow attribution and publishing-infrastructure test  
**Status:** OPEN — acquisition only

## Objective

Determine whether the shared attribution:

> `A Citizen of the United States`

on James McBride's 1826 Symmes treatise and Jeremiah N. Reynolds's 1827 response is:

- a deliberate echo;
- a shared Symmes-circle identity marker;
- a printer/editor convention;
- a generic period anonymity formula;
- or an apparent match created by later cataloguing.

At the same time, reconstruct the short publication chain described by Reynolds:

```text
American Quarterly Review criticism
        ↓
Reynolds response numbers in the National Intelligencer
        ↓
Gales & Seaton pamphlet, 1827
```

## Required source A — McBride 1826

Locate one exact institutional copy of:

```text
Symmes's Theory of Concentric Spheres:
Demonstrating that the Earth Is Hollow, Habitable Within,
and Widely Open about the Poles
```

Return:

```text
exact title-page transcription
printed creator/byline
city
publisher / printer
publication date
edition / state
extent
institution / archive
catalogue ID / call number
stable item page
stable scan / image sequence
```

Do not rely on a modern citation saying `By a Citizen of the United States`; inspect the title page.

## Required source B — Reynolds 1827 title page

Use the Internet Archive / LOC-derived item:

```text
identifier: remarksonreviewo00reyn
ARK: ark:/13960/t1tf1gd11
LCCN: 06040937
```

Return the exact title-page image number and transcription, including punctuation and whether the printed phrase is:

- `A Citizen of the United States`;
- `By a Citizen of the United States`;
- or another form.

## Required source C — *National Intelligencer* serialization

Reynolds's preface says the three numbers were first published in the *National Intelligencer*.

Locate each number and return:

```text
newspaper title
issue date
page / column
article heading
signature or byline
opening and closing lines
printer / publisher
stable scan or archive record
```

Determine whether the shared citizen attribution appears in the newspaper serialization or only on the collected pamphlet.

## Network test

Map the roles of:

- Gales & Seaton;
- the *National Intelligencer*;
- McBride;
- Reynolds;
- John Cleves Symmes;
- the anonymous AQR reviewer;
- any advertisements or reprint notices.

A shared printer or newspaper is `SHARED_INFRASTRUCTURE`, not automatically conceptual influence.

## Frequency control

Search a bounded comparison set of 1820–1830 American pamphlets for the exact phrase `A Citizen of the United States`.

Return:

- five to fifteen exact occurrences;
- date, title, topic, printer, and city;
- whether the phrase was common, uncommon, or concentrated in one network.

Do not run an unbounded web scrape. Prefer library catalogues, scans, and bibliographies.

## Decision table

| Test | Evidence | Outcome |
|---|---|---|
| Exact McBride title-page phrase |  |  |
| Exact Reynolds title-page phrase |  |  |
| Phrase in *National Intelligencer* serialization |  |  |
| Shared printer/editor/network |  |  |
| Phrase frequency outside Symmes material |  |  |
| Direct acknowledgement of McBride |  |  |

Allowed outcomes:

- `DELIBERATE_ECHO_SUPPORTED`
- `SHARED_CIRCLE_SIGNAL_PLAUSIBLE`
- `SHARED_INFRASTRUCTURE_ONLY`
- `GENERIC_PERIOD_CONVENTION`
- `CATALOGUE_NORMALIZATION`
- `INDEPENDENT_PARALLEL`
- `UNKNOWN`

## Deliverables

1. Exact title-page records for both works.
2. The three *National Intelligencer* serialization records or a documented failed-search log.
3. Bounded phrase-frequency comparison.
4. Publisher/printer/editor carrier table.
5. Evidence for and against deliberate echo.
6. Recommended classification only; no canonical copying edge.

## Copy-paste cloud-agent prompt

> Read `RESEARCH_ATLAS.md`, `CROSS_DOMAIN_BRIDGE_ATLAS.md`, `reports/SESSION_031_REYNOLDS_AQR_QC.md`, `graph/chronologies/REYNOLDS-1827-REMARKS-CATALOG-RECORD.md`, and `data/error_fingerprints/ERR-032-002-CITIZEN-OF-US-BYLINE.md`. Execute `research_inbox/SESSION_032_CITIZEN_BYLINE_INTELLIGENCER_BRIDGE_BRIEF.md`. Work only on the shared `A Citizen of the United States` attribution and the Reynolds publication path through the *National Intelligencer*. Obtain exact title-page images for McBride 1826 and Reynolds 1827, exact newspaper dates/pages/bylines for Reynolds's three serialized numbers, and a bounded 1820–1830 frequency control for the phrase. Distinguish deliberate echo, shared-circle signaling, shared publishing infrastructure, generic anonymity convention, catalogue normalization, and independent parallel use. Return exact scans, catalogue identifiers, quotations, failed searches, and a recommendation. Do not create a canonical copying edge.
