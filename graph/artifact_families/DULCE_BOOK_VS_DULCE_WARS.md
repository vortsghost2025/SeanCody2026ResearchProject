# The Dulce Book versus The Dulce Wars

> **Related:** `RQ-036`, `DULCE-CAND-013`, `DULCE-CAND-015`, Sessions 055–056  
> **Status:** distinct title traditions supported; exact work and edition relation unresolved

## Title traditions

```yaml
TITLE_A:
  title: The Dulce Book
  attributed_author: Branton
  early_environment: 1996_SELF_DATE_AND_LATER_DIGITAL_STATES
  commercial_edition_lead:
    publisher: GLOBAL_COMMUNICATIONS
    year: 2003_REPORTED
    status: ITEM_LEVEL_NOT_INSPECTED

TITLE_B:
  title: The Dulce Wars: Underground Alien Bases and the Battle for Planet Earth
  attributed_author: Branton
  early_environment: 1996_CLAIMS_AND_LATER_REPRINTS
  commercial_edition_lead:
    publisher: INNER_LIGHT_PUBLICATIONS
    year: 2011_REPORTED
    pages: 168_REPORTED
    status: ITEM_LEVEL_NOT_INSPECTED
```

The publisher names belong to the same Beckley-associated commercial ecosystem and should not be treated as independent provenance by themselves.

## Shared features

- same compiler/author attribution;
- overlapping Dulce and underground-base corpus;
- reported reuse of the mature Castello Q&A;
- common Branton editorial voice;
- shared Inner Light / Global Communications distribution environment;
- later electronic and re-typeset reuse.

## Session 056 naming evidence

A secondary source reportedly refers to Branton as writing `two major books`, *The Dulce Book* and *The Dulce Wars*.

This supports distinct title recognition. It does not establish exact chapter, edition or source-history differences.

```yaml
NAMING_RESULT:
  distinct_title_names: CONFIRMED
  secondary_treatment_as_two_books: SUPPORTED
  item_level_work_identity: OPEN
```

## Competing models

```yaml
H1:
  description: one underlying compilation circulated under multiple title wrappers
  status: PLAUSIBLE
H2:
  description: The Dulce Wars is a retitled and abridged edition of The Dulce Book
  status: PLAUSIBLE
H3:
  description: The Dulce Wars is an independently arranged selection from the same Branton source corpus
  status: PLAUSIBLE
H4:
  description: two distinct compilations sharing substantial chapters and source material
  status: NOT_EXCLUDED
```

The reported page-count difference, if confirmed, would argue against a simple identical reprint but would remain compatible with abridgement or re-selection.

## Cosmic Conflict relation

A Session 056 variant proposes that COSCON34 is chapter 34 of *Cosmic Conflict: The Love Song of the Overcomers*.

Current result:

```yaml
COSMIC_CONFLICT:
  Branton_title_family_membership: SUPPORTED_AS_COMMERCIAL_OR_COMPILATION_LEAD
  COSCON34_chapter_34_identity: CANDIDATE_NOT_CONFIRMED
  independent_source_status: NO
```

Even if confirmed, cross-title reuse remains internal to one Branton editorial family.

## Required item-level comparison

For each physical or digital edition acquire:

- title page;
- copyright page;
- publisher and imprint;
- exact publication date;
- ISBN or catalogue identifier;
- edition statement;
- page count;
- complete contents;
- chapter titles and order;
- introduction and sign-off;
- Q&A chapter wording;
- March 1994 COSCON paragraph;
- October 1996 self-date;
- added or omitted chapters;
- cover/title changes;
- file metadata and provenance.

## Independence boundary

```text
The Dulce Book
        +
The Dulce Wars
        +
Cosmic Conflict / COSCON34 candidate
        = distinct carrier and title leads
        ≠ independent hierarchy witnesses
```

Read:

- `data/error_fingerprints/ERR-036-039-MULTI-COMPILATION-INDEPENDENCE-COLLAPSE.md`

## Current decision

```yaml
shared_compilation_corpus: HIGH_CONFIDENCE
distinct_title_names: SUPPORTED
distinct_commercial_edition_leads: SUPPORTED
same_work: NOT_PROVED
retitled_or_abridged_relation: PLAUSIBLE
separate_compilations: NOT_EXCLUDED
Cosmic_Conflict_relation: OPEN
independent_source_count: ONE_BRANTON_EDITORIAL_FAMILY
canonical_work_identity_edge: false
```
