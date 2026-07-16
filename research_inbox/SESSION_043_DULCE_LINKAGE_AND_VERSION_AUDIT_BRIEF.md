# SESSION 043 — Dulce Linkage and Version Audit Brief

**Target:** `RQ-036`, `BRIDGE-036-001`  
**Mode:** exact-object acquisition, version comparison and same-referent hierarchy test  
**Status:** OPEN — no origin declaration

## Objective

Locate the earliest securely dated artifact that explicitly connects:

```text
identified reptilian / Draconian authority A
        ↓ controls / creates / commands / uses
identified Grey group B
        ↓ inside
underground base / treaty / genetic experiment / secret program C
```

Do not mark an artifact FULL merely because A, B and C occur separately.

## Priority 1 — Bill Hamilton, *Alien Magic*, reported 1989

Acquire the exact artifact.

Return:

```text
full title
creator as printed
publisher / distributor
place
edition / printing
copyright and publication date
title page
copyright page
contents
extent
physical format
library / collector / catalogue record
stable scan or photographs
all TAL / Jason Bishop contributions
exact Draco / Reptilian / Grey / Dulce passages
source list and acknowledgements
```

Determine whether it contains a same-referent A→B→C chain.

Do not rely on a later claim that TAL material appeared in this book.

## Priority 2 — TAL / Jason Bishop III, *The Dulce Base*, reported 1989

Acquire the earliest exact manuscript, photocopy, BBS file, newsletter reprint or printed edition.

Return:

```text
file or document title
byline / pseudonym
exact date and date basis
medium
page count
publisher / address / BBS header
first surviving copy
archive or collector provenance
complete scan or raw text
version differences
exact A→B→C wording
```

Separate:

- original Jason Bishop text;
- later Thomas Castello additions;
- Bill Hamilton edits or republication;
- Branton notes;
- modern web normalization.

## Priority 3 — Patrick O'Connell mailer/newsletter

Target title:

> `The Covert Return of an Alien Species of Reptilian Heritage — The Dulce Base`

One model reported:

```text
Trends and Predictions Analyst
Vol. 6, No. 2
July 1990
```

This is an **unverified bibliographic lead**, not accepted metadata.

Acquire:

```text
newsletter title as printed
volume / issue
mailing date / postmark
masthead and address block
publisher / editor
TAL article byline
page range
complete page images
recipient / collector provenance
advertisements or subscription information
```

Compare the original against the Branton-hosted transcription.

Identify:

- wording actually written by TAL;
- Branton notes;
- whether `Greys are mercenaries being used` explicitly identifies the user as the Reptilian/Draco group;
- whether C is connected in the same passage or only supplied by title/context.

## Priority 4 — *Matrix II* edition comparison

Artifacts:

```text
reported 1990 first edition
Arcturus Book Service, Las Vegas
reported limited 500-copy printing

inspected 1991 third edition with added material
Leading Edge Research Group, Yelm
copyright 1990, 1991
```

Acquire or photograph the 1990 first edition and compare:

- title and copyright pages;
- acknowledgements;
- table of contents;
- page 89 relationship section;
- Grey creation passage;
- Reptilian enemies-of-Greys editor note;
- Jason Bishop material;
- Dulce sections;
- all `Draco`, `work force`, `mercenary`, `subordinate`, `created`, `controlled` occurrences.

Return a line-level or page-level diff.

Test these possibilities:

- hierarchy sentence exists only in 1990 first edition;
- hierarchy sentence added in 1991;
- hierarchy sentence never appears and later citation is wrong;
- source tag shifted from another author;
- enemy relationship and hierarchy relationship coexist in different source layers.

## Priority 5 — *UFO Universe*, Feb–Mar 1991

Target article:

> `The Deep Dark Secret at Dulce` — Bill Hamilton and TAL LeVesque

Acquire:

```text
cover
masthead
publisher and editor
volume / issue
contents page
article pages
byline
captions and illustrations
complete unabridged text
```

Compare against Branton Chapter 10 and later mirrors.

Do not import wording from the separate O'Connell/TAL article.

## Priority 6 — Earliest exact linked wording

Search exact phrases and near variants including:

```text
Greys as mercenaries
Greys being used
Greys as workers / work force / worker caste
Greys created by Draco / Draconians / Reptilians
Greys controlled by Draco / Orion group
Winged Draco above Greys
Reptilian hierarchy over Greys
```

For every match return:

- exact artifact;
- date and date basis;
- page or timestamp;
- full surrounding paragraph;
- author versus editor/quoting layer;
- earlier version;
- later copying;
- source-tag accuracy.

## Required relationship table

| Artifact | Version/date | A entity | B Grey group | Exact A→B wording | A→B status | C wording | AB→C status | Result |
|---|---|---|---|---|---|---|---|---|
|  |  |  |  |  |  |  |  |  |

Allowed A→B statuses:

- `EXPLICIT`
- `IMPLIED`
- `ABSENT`
- `CONTRADICTED`
- `UNKNOWN`

Allowed final results:

- `FULL_LINKED_CHAIN`
- `LINKED_CHAIN_IMPLIED`
- `CO_PRESENT_UNLINKED`
- `PARTIAL-AB`
- `PARTIAL-AC`
- `PARTIAL-BC`
- `PARTIAL-C`
- `OPPOSITIONAL_RELATIONSHIP`
- `PRIMARY_ARTIFACT_NOT_RECOVERED`
- `UNKNOWN`

## Stop rules

Do not:

- return another broad Dulce chronology;
- treat a later mirror as the original artifact;
- treat a table-of-contents heading as passage evidence;
- combine the two TAL articles;
- use an alleged event date as publication date;
- treat Greys and reptilians co-present at a base as a hierarchy;
- assume a parenthetical citation is accurate;
- assign wording from a Branton note to TAL or Bennewitz;
- state the July 1990 O'Connell metadata as confirmed without the issue;
- declare a first source without exact pages and version identity.

## Deliverables

1. Exact object records for every recovered artifact.
2. Complete page images or stable primary locators.
3. Version and source-layer comparison.
4. Same-referent A→B→C table.
5. Citation-error and copied-wording chain.
6. Failed-search and archive-contact log.
7. Recommendation only; curator promotion required.

## Copy-paste agent prompt

> Read `AGENTS.md`, `docs/METHODOLOGY.md`, `research_questions/RQ-036-REPTILIAN-SYNTHESIS-GREY-FUSION.md`, `graph/bridges/BRIDGE-036-001-REPTILIAN-GREY-FUSION.md`, `graph/chronologies/DULCE-HIERARCHY-CANDIDATE-REGISTRY.md`, `reports/SESSION_042_CROSS_VARIANT_QC.md`, and error fingerprints `ERR-036-002`, `ERR-036-003`, and `ERR-036-004`. Execute `research_inbox/SESSION_043_DULCE_LINKAGE_AND_VERSION_AUDIT_BRIEF.md`. Acquire exact primary objects for Bill Hamilton's reported 1989 *Alien Magic*, TAL/Jason Bishop's reported 1989 *The Dulce Base*, the Patrick O'Connell mailer, the Feb–Mar 1991 *UFO Universe* article, and the 1990 first edition of *Matrix II*. Compare versions and source layers. A FULL result requires the same identified reptilian/Draconian authority explicitly or securely implied as controlling, creating, commanding or using identified Greys inside the same Dulce/base/treaty/genetic/secret-program system. Mere A+B+C co-presence is not FULL. Return pages, dates, provenance, exact wording, failed searches and contradictions. Do not declare an origin.
