# Matrix II — Edition Matrix

> **Related:** `RQ-036`, `DULCE-CAND-009`, `DULCE-CAND-041`, Sessions 055–056  
> **Status:** 1990 first-edition item metadata bounded; 1991 section page confirmed; first-to-third content comparison open

## Edition table

| State | Date | Publisher/distributor | Physical description | Evidence status | Hierarchy-section status |
|---|---:|---|---|---|---|
| First edition | 1990 | Arcturus Book Service, Las Vegas | 458 pp.; perfect-bound quarto; 500 numbered copies reported; dealer copy #152 | `DEALER_ITEM_METADATA_WITH_COLOPHON_DESCRIPTION` | `PASTURING_AND_USE_PRESENCE_UNKNOWN` |
| Third edition with added material | 1991 | Leading Edge Research Group | 661+ pp. reported; large-format/velo-bound state | `PRIMARY_SCAN_INSPECTED` | `PASTURING_AND_USE_PRESENT_AT_PAGE_95` |

## First-edition promotion boundary

The dealer record is item-level evidence that a described physical copy existed with those bibliographic characteristics. The project has not inspected the copy or its title, copyright, colophon, contents or hierarchy pages.

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

## Inspected 1991 section placement

The inspected 1991 third-edition scan places:

```text
PASTURING AND USE OF SURFACE EARTH HUMANS — The Reptilians
```

at page 95 in the table of contents, following the Grey/Reptilian anatomy and relationship block.

The inspected edition also acknowledges Jason Bishop III as a contributor.

```yaml
MATRIX_II_1991_THIRD:
  Pasturing_section_present: true
  contents_page_assignment: 95
  Bishop_III_acknowledgement: SUPPORTED
  hierarchy_effect: INTERMEDIATE_PLUS_OPPOSITIONAL_COMPILATION
```

## Expansion boundary

```text
1990 first edition: 458 pages
1991 third edition: 661+ pages
        ↓
203+ pages of expansion
```

The expansion is too large to assume that every third-edition section appeared in the first.

## Page-position inference boundary

The section's placement near page 95 makes first-edition presence plausible, because it occurs in an early thematic block rather than near the end of the enlarged volume.

However:

```text
page 95 in a later expanded edition
        ≠
page 95 or any presence in the shorter first edition
```

Later editions can insert and renumber material near the front. Early placement is therefore a weak inference, not edition proof.

## Hierarchy passage question

The critical section contains or is reported to contain:

- Draco as reptilian leader elite;
- reptilian caste language;
- Grey mercenary or influence-chain language;
- underground/genetic-program context;
- oppositional passages elsewhere in the compilation.

```yaml
PASTURING_AND_USE:
  in_1991_third: CONFIRMED_AT_PAGE_95
  in_1990_first: UNKNOWN
  first_wording_state: UNKNOWN
  first_date_for_intermediate_hierarchy: 1990_OR_1991_UNRESOLVED
  first_edition_presence_inference: PLAUSIBLE_NOT_EVIDENCE
```

## Minimum decisive first-edition acquisition

Acquire from a numbered 458-page copy:

1. title page;
2. copyright/edition page;
3. colophon;
4. contents pages around entries 88–100;
5. page 95;
6. index entries for `Pasturing`, `Draco`, `Greys`, `Dulce`, `Bishop` and `LeVesque`;
7. section opening/closing pages if present.

## Chronology effect

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
Pasturing_1991_page: 95
Bishop_III_acknowledgement_1991: SUPPORTED
edition_expansion: SUBSTANTIAL
Pasturing_first_edition_presence: UNKNOWN
intermediate_hierarchy_year: 1990_OR_1991
canonical_chronology_edge: false
```
