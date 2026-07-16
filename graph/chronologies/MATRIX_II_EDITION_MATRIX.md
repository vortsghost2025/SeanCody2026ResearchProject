# Matrix II — Edition Matrix

> **Related:** `RQ-036`, `DULCE-CAND-009`, `DULCE-CAND-041`, Session 055  
> **Status:** 1990 first-edition item metadata bounded; content comparison open

## Edition table

| State | Date | Publisher/distributor | Physical description | Evidence status | Hierarchy-section status |
|---|---:|---|---|---|---|
| First edition | 1990 | Arcturus Book Service, Las Vegas | 458 pp.; perfect-bound quarto; 500 numbered copies reported; dealer copy #152 | `DEALER_ITEM_METADATA_WITH_COLOPHON_DESCRIPTION` | `PASTURING_AND_USE_PRESENCE_UNKNOWN` |
| Third edition with added material | 1991 | Leading Edge Research Group | 661+ pp. reported; large-format/velo-bound state | `PRIMARY_SCAN_INSPECTED` | hierarchy and oppositional passages present |

## First-edition promotion boundary

The dealer record is item-level evidence that a described physical copy existed with those bibliographic characteristics. The project has not inspected the copy or its title/copyright/colophon pages.

```yaml
MATRIX_II_1990_FIRST:
  bibliographic_record: SUPPORTED
  project_physical_inspection: false
  publisher_reported: ARCTURUS_BOOK_SERVICE
  place_reported: LAS_VEGAS
  page_count_reported: 458
  print_run_reported: 500
  numbered_copy_reported: 152
```

## Expansion boundary

```text
1990 first edition: 458 pages
1991 third edition: 661+ pages
        ↓
203+ pages of expansion
```

The expansion is too large to assume that every third-edition section appeared in the first.

## Hierarchy passage question

The critical unresolved object is `Pasturing and Use of Surface Earth Humans`, which contains or is reported to contain:

- Draco as leader elite;
- reptilian caste language;
- Grey mercenary or influence-chain language;
- underground/genetic-program context.

```yaml
PASTURING_AND_USE:
  in_1991_third: SUPPORTED_BY_INSPECTED_SCAN
  in_1990_first: UNKNOWN
  first_page_range: UNKNOWN
  first_wording_state: UNKNOWN
  first_date_for_intermediate_hierarchy: 1990_OR_1991_UNRESOLVED
```

## Comparison requirements

Acquire from both editions:

1. title page;
2. copyright page;
3. edition statement;
4. colophon;
5. complete table of contents;
6. index entries for `Pasturing`, `Draco`, `Greys`, `Dulce`, `Bishop` and `LeVesque`;
7. section opening and closing pages;
8. all hierarchy passages;
9. page-level diff;
10. evidence of additions, deletions and renumbering.

## Chronology effect

Before inspection:

```text
1989 reported proto-hierarchy
        ↓
1990 or 1991 intermediate hierarchy
        ↓
unknown-date mature Q&A
```

Only if the section is present in the numbered 458-page state may the intermediate stage be securely assigned to the first edition's 1990 bibliographic state.

## Current decision

```yaml
first_edition_physical_metadata: SUPPORTED_BY_DEALER_RECORD
first_edition_primary_pages_acquired: false
third_edition_primary_scan_acquired: true
edition_expansion: SUBSTANTIAL
Pasturing_first_edition_presence: UNKNOWN
intermediate_hierarchy_year: 1990_OR_1991
canonical_chronology_edge: false
```
