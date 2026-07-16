# SESSION 055 — Result Manifest

> **Target:** COSCON34 carrier identity, *Matrix II* first-edition metadata, and *Dulce Book* / *Dulce Wars* title identity  
> **Related:** `RQ-036`, `BRIDGE-036-001`  
> **Status:** processed with bounded promotions; no first-carrier, authorship, stemma-direction or canonical origin edge

## Input findings

```yaml
SESSION:
  id: SESSION_055
  date: 2026-07-16

  findings:
    - id: S055-COSCON34
      objects:
        - geocities.ws/hangtime96.geo/coscon34.html
        - pages.suddenlink.net/anomalousimages/images/text/COSCON34.TXT
      result: >
        Mature Castello Q&A text and Branton editorial parentheticals are present.
        COSCON34 cannot be an unedited pre-Branton source state. Original BBS
        metadata, upload date and conference identity remain absent.

    - id: S055-MATRIX-II-FIRST
      object: Matrix II first-edition dealer record
      result: >
        Dealer item metadata reports Arcturus Book Service, Las Vegas, 1990;
        first edition; limited to 500 numbered copies; 458 pages; described copy
        numbered 152. The 1991 third-edition scan is substantially longer.
        The presence of Pasturing and Use in the first edition remains unverified.

    - id: S055-DULCE-TITLES
      objects:
        - The Dulce Book
        - The Dulce Wars: Underground Alien Bases and the Battle for Planet Earth
      result: >
        Both title traditions are associated with Branton and 1996-era metadata.
        Reported matching chapter structures suggest one underlying compilation or
        closely related editions, but work identity is not resolved item by item.
```

## Curator result

```yaml
SESSION_055:
  COSCON34_mature_QA: CONFIRMED_AS_TEXT_WITNESS
  COSCON34_Branton_editorial_layer: CONFIRMED
  COSCON34_pre_Branton_unedited_ancestor: EXCLUDED
  COSCON34_date: UNKNOWN
  COSCON34_BBS_origin: FILENAME_AND_FORMAT_LEAD_ONLY

  Matrix_II_1990_first_edition:
    status: DEALER_ITEM_METADATA_WITH_COLOPHON_DESCRIPTION
    publisher_reported: ARCTURUS_BOOK_SERVICE_LAS_VEGAS
    page_count_reported: 458
    print_run_reported: 500_NUMBERED_COPIES
    inspected_by_project: false

  Matrix_II_1991_third_edition:
    status: PRIMARY_SCAN_INSPECTED
    page_count: 661_PLUS_REPORTED

  Pasturing_and_Use_in_1990_first: UNRESOLVED
  intermediate_hierarchy_date: 1990_OR_1991_UNRESOLVED

  Dulce_Book_vs_Dulce_Wars:
    title_identity: PROBABLE_RELATED_OR_RETITLED_WORK
    same_work: NOT_PROVED
    distinct_works: NOT_EXCLUDED

  first_mature_carrier: UNRESOLVED
  canonical_authorship_edge: false
  canonical_first_carrier_edge: false
  canonical_stemma_edge: false
  next_session: SESSION_056
```

## Outputs

- `reports/SESSION_055_COSCON34_MATRIXII_TITLE_QC.md`
- `graph/textual_stemma/COSCON34_BRANTON_CARRIER.md`
- `graph/chronologies/MATRIX_II_EDITION_MATRIX.md`
- `graph/artifact_families/DULCE_BOOK_VS_DULCE_WARS.md`
- `data/error_fingerprints/ERR-036-033-SOURCE-ARTICLE-DATE-COMPILATION-DATE-COLLAPSE.md`
- `data/error_fingerprints/ERR-036-034-EDITORIALIZED-CARRIER-ANCESTOR-COLLAPSE.md`
- `data/error_fingerprints/ERR-036-035-EDITION-PAGE-COUNT-CONTENT-TRANSFER.md`
- `data/error_fingerprints/ERR-036-036-TITLE-VARIANT-WORK-IDENTITY-COLLAPSE.md`
- `research_inbox/SESSION_056_MATRIXII_PHYSICAL_DIFF_AND_COSCON_PROVENANCE_BRIEF.md`
