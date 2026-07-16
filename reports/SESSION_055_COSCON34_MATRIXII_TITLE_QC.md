# SESSION 055 — COSCON34, Matrix II and Branton Title Cross-QC

> ## TOP-LEVEL RESULT
>
> ```text
> COSCON34 mature Q&A text: CONFIRMED
> COSCON34 Branton editorial layer: CONFIRMED
> COSCON34 as unedited pre-Branton ancestor: EXCLUDED
> COSCON34 original BBS date/header: NOT RECOVERED
> Matrix II 1990 first-edition physical metadata: DEALER-REPORTED ITEM RECORD
> Matrix II first edition inspected by project: NO
> Pasturing and Use present in 1990 first edition: UNRESOLVED
> Dulce Book / Dulce Wars work identity: UNRESOLVED, PROBABLY RELATED
> First mature hierarchy carrier: UNRESOLVED
> Canonical edges created: NO
> ```

## 1. COSCON34

Two surviving carriers are reported:

- `geocities.ws/hangtime96.geo/coscon34.html`
- `pages.suddenlink.net/anomalousimages/images/text/COSCON34.TXT`

The text introduces the mature Castello-attributed Q&A and contains Branton-style editorial parentheticals. The presence of those parentheticals is decisive for one narrow question:

```text
COSCON34
        ≠ unedited source state anterior to Branton's intervention
```

It may be:

- a BBS distribution of Branton-edited material;
- a contemporary Branton working/export state;
- a later file derived from the compilation;
- a mixed carrier preserving source answers plus Branton additions.

The filename `COSCON34` and plain-text form suggest a BBS-era or conference-file distribution environment, but the filename alone does not establish:

- the BBS name;
- conference number or meaning;
- sysop;
- upload date;
- file creation date;
- whether `34` is sequential;
- whether the current web files preserve original bytes.

Current classification:

```yaml
COSCON34:
  mature_QA: CONFIRMED
  Branton_editorial_voice: CONFIRMED
  unedited_pre_Branton_ancestor: EXCLUDED
  pre_web_distribution: PLAUSIBLE_NOT_DATED
  original_BBS_metadata: NOT_RECOVERED
  stemma_position: BRANTON_CONTEMPORARY_OR_DERIVATIVE
```

## 2. Matrix II first-edition metadata

A rare-book dealer record reportedly describes:

```text
Valdamar Valerian, Matrix II
Las Vegas: Arcturus Book Service, 1990
first edition
limited to 500 numbered copies
reported copy number 152
458 pages
perfect-bound quarto in pictorial wrappers
```

This is the first item-level description of the 1990 first edition in the acquired record. It is valuable but remains dealer-supplied metadata until title, copyright and colophon pages are acquired.

Use:

```text
DEALER_ITEM_METADATA_WITH_COLOPHON_DESCRIPTION
```

not:

```text
PROJECT_INSPECTED_PRIMARY_FIRST_EDITION
```

The inspected 1991 third edition is described as substantially longer, approximately 661 or more pages. The 203-plus-page expansion means no passage found in the third edition can be transferred automatically into the first.

## 3. Pasturing and Use edition assignment

The intermediate hierarchy passage attributed to `Pasturing and Use of Surface Earth Humans` may occur in:

- the 1990 first edition;
- an expanded second edition;
- the 1991 third edition only;
- more than one edition with revisions.

Until the 458-page first edition is inspected:

```yaml
PASTURING_AND_USE:
  content_in_1991_third: SUPPORTED
  content_in_1990_first: UNKNOWN
  first_hierarchy_date: 1990_OR_1991_UNRESOLVED
  use_as_1990_intermediate: PROVISIONAL
```

The chronology therefore remains:

```text
1989 reported proto-hierarchy
        ↓
1990 or 1991 intermediate layer, edition unresolved
        ↓
unknown-date mature Q&A
        ↓
October 1996 self-dated Branton compilation tradition
```

## 4. Dulce Book versus Dulce Wars

The title traditions are:

- *The Dulce Book*
- *The Dulce Wars: Underground Alien Bases and the Battle for Planet Earth*

Both are associated with Branton and 1996-era bibliographic claims. Reported chapter structures substantially overlap or match.

Possible models:

```text
H1: one compilation circulated under two titles
H2: Dulce Wars is a retitled edition of Dulce Book
H3: one is a subset or expansion of the other
H4: separate compilations sharing a chapter corpus
```

No hypothesis is promoted without item-level title pages, copyright pages, contents and chapter alignment.

Current classification:

```yaml
DULCE_BOOK_DULCE_WARS:
  shared_author_attribution: BRANTON
  shared_1996_environment: SUPPORTED
  chapter_overlap: STRONG
  identical_work: NOT_PROVED
  distinct_work: NOT_EXCLUDED
  result: TITLE_AND_EDITION_IDENTITY_OPEN
```

## 5. Effect on first-carrier search

COSCON34 does not solve the first-carrier problem because its Branton editorial content places it after or inside Branton's intervention, while its own date is missing.

The Matrix II metadata does not solve the intermediate-stage date because the relevant section has not been assigned to the 458-page first edition.

The title distinction does not create a second independent 1996 witness until work identity is established.

## 6. Curator decision

```yaml
SESSION_055:
  COSCON34_pre_Branton_candidate: CLOSED_NEGATIVE
  COSCON34_Branton_carrier: SUPPORTED
  COSCON34_date: UNKNOWN
  Matrix_II_first_edition_metadata: PROMOTED_AS_DEALER_ITEM_RECORD
  Matrix_II_first_edition_content: UNINSPECTED
  Pasturing_and_Use_first_edition_presence: UNRESOLVED
  Dulce_Book_vs_Dulce_Wars: IDENTITY_OPEN
  hierarchy_progression: 1989_PROTO_TO_1990_OR_1991_INTERMEDIATE_TO_MATURE
  first_mature_carrier: UNRESOLVED
  canonical_authorship_edge: false
  canonical_first_carrier_edge: false
  canonical_stemma_edge: false
```
