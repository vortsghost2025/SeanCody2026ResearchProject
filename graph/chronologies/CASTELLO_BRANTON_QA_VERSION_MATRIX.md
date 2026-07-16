# Castello / Branton Q&A Version Matrix

> **Related:** `RQ-036`, `BRIDGE-036-001`, `DULCE-CAND-012`, `013`, `015`, `047`–`053`  
> **Status:** mature text family confirmed; first carrier, first composition and exact work identity unresolved

## Core linked-chain text

The surviving Branton-derived Q&A family contains:

```text
Draco / white Draco authority
        ↓
Grey and other worker groups controlled, created or serving
        ↓
Dulce levels 5–6–7, laboratories and secret programs
```

Result: `FULL_LINKED_CHAIN_AT_TEXT_LEVEL`.

## Version/carrier table

| Matrix ID | Object/state | Date | Date basis | Hierarchy state | Current status |
|---|---|---:|---|---|---|
| `QA-STATE-001` | Original question lists and Hinkle answers | unknown | LeVesque 2015 self-attestation | unknown | `NOT_RECOVERED` |
| `QA-STATE-002` | Hypothetical first assembled Q&A | unknown | none | mature form presumed by descendants | `NOT_RECOVERED` |
| `QA-STATE-003` | Lear letter distributing `Dulce papers` drawings/enclosures | 1987-12-13 | reported primary PDF quotation | no mature hierarchy located | `PRIMARY_DOCUMENT_REPORTED_NOT_ARCHIVED` |
| `QA-STATE-004` | LeVesque/Bishop, *The Dulce Base* | 1989 reported | later text witnesses; first carrier absent | proto-hierarchy | `TEXT_WITNESS_DATE_OPEN` |
| `QA-STATE-005A` | *Matrix II* 1990 first edition | 1990 | dealer item metadata; 458 pp.; 500 numbered copies reported | hierarchy section unknown | `FIRST_EDITION_CONTENT_UNINSPECTED` |
| `QA-STATE-005B` | *Matrix II* 1991 third edition | 1991 | inspected scan; `Pasturing` at p.95 | intermediate plus oppositional framings | `PRIMARY_SCAN_INSPECTED` |
| `QA-STATE-006` | Claimed July 1990 *Trends and Predictions Analyst* article | July 1990 claimed | issue absent | implied mercenary relation | `ITEM_LEVEL_UNVERIFIED` |
| `QA-STATE-007` | Claimed early Branton BBS/manuscript state | early/mid-1990s | later descriptions | mature wording reported | `NOT_ITEM_LEVEL_VERIFIED` |
| `QA-STATE-008` | 1991 source article/reference inside Branton compilation | 1991 | internal quoted-source date | source-layer material | `NOT_A_COMPILATION_DATE` |
| `QA-STATE-009` | Branton compilation tradition | October 1996 self-date | sign-off inside surviving primary-text family | mature wording present | `COMPILATION_SELF_DATE_FIRST_CARRIER_OPEN` |
| `QA-STATE-010` | COSCON34 surviving composite | after 1994-03-18 | internal *Plain Dealer* reference | mature Q&A plus Branton parentheticals | `POST_1994_EDITORIALIZED_CARRIER` |
| `QA-STATE-011` | *The Dulce Wars* title family | 1996 environment and later edition leads | title/retailer/reprint metadata | mature corpus reported | `DISTINCT_TITLE_WORK_RELATION_OPEN` |
| `QA-STATE-012` | Project Avalon Thread 8393 testimony layer | Nov. 2010 | forum timestamps | testimony and source claims | `CONFIRMED_THREAD_DATE` |
| `QA-STATE-013` | Alleged Avalon Q&A body / W or Hinkle post | Nov. 2010 claimed | mutually conflicting acquisition reports | mature hierarchy claimed | `DISPUTED_PENDING_RAW_POST` |
| `QA-STATE-014` | Hinkle/Dorsey Repton corpus | 2010 context | forum/Facebook quotation lead | distinct hierarchy expansion | `SEPARATE_PARTICIPANT_CORPUS` |
| `QA-STATE-015` | Later Branton-derived web mirrors | 2000s–2020s | dated web carriers | mature hierarchy; Q/A label branches | `DERIVATIVE_TEXT_WITNESSES` |
| `QA-STATE-016` | LeVesque email to Gorightly | Nov. 2015 | recipient account/reproduction | production account | `DIRECT_QUOTE_IN_VERIFIED_SECONDARY` |
| `QA-STATE-017` | *Cosmic Conflict* chapter 34 identity for COSCON34 | date unknown | filename/title-family inference | same editorialized carrier claimed | `CARRIER_IDENTITY_CANDIDATE` |
| `QA-STATE-018` | *The Dulce Book* commercial edition lead | 2003 reported | commercial metadata | Branton corpus | `ITEM_LEVEL_UNINSPECTED` |
| `QA-STATE-019` | *The Dulce Wars* commercial edition lead | 2011 reported | commercial metadata; 168 pp. reported | Branton corpus | `ITEM_LEVEL_UNINSPECTED` |

## Date-layer correction

```text
1991 source article/reference
        ≠
1991 Dulce Book compilation
```

The surviving compilation tradition contains an October 1996 Branton sign-off. This is a compilation self-date, not yet a physically inspected first-publication record.

## COSCON34 chronology result

COSCON34 contains mature Q&A material, Branton editorial parentheticals and a reported March 18, 1994 news reference.

```yaml
COSCON34:
  unedited_pre_Branton_source: EXCLUDED
  Branton_edited_carrier: SUPPORTED
  surviving_state_TPQ: 1994-03-18
  underlying_QA_date: UNKNOWN
  Cosmic_Conflict_chapter_34_identity: CANDIDATE_NOT_CONFIRMED
  relation_to_October_1996_compilation: UNRESOLVED
```

```text
post-March-1994 carrier state
        ≠
pre-March-1994 Q&A composition proof
```

Read:

- `graph/textual_stemma/COSCON34_BRANTON_CARRIER.md`
- `data/error_fingerprints/ERR-036-037-TERMINUS-POST-QUEM-SOURCE-COMPOSITION-COLLAPSE.md`
- `data/error_fingerprints/ERR-036-038-FILENAME-STEM-CARRIER-IDENTITY-COLLAPSE.md`

## Matrix II edition result

```yaml
MATRIX_II:
  1990_first:
    page_count_reported: 458
    evidence: DEALER_ITEM_METADATA
    Pasturing_presence: UNKNOWN
  1991_third:
    page_count_reported: 661_PLUS
    evidence: INSPECTED_PRIMARY_SCAN
    Pasturing_page: 95
    Bishop_III_acknowledgement: SUPPORTED
    intermediate_hierarchy: PRESENT
  first_intermediate_date: 1990_OR_1991_UNRESOLVED
```

Read: `graph/chronologies/MATRIX_II_EDITION_MATRIX.md`.

## Branton multi-title boundary

Distinct title names and later commercial-edition leads are supported for:

- *The Dulce Book*;
- *The Dulce Wars*;
- possibly *Cosmic Conflict* as the containing work for COSCON34.

```text
multiple titles and editions by one compiler
        ≠
multiple independent hierarchy witnesses
```

Exact work, retitling, abridgement and chapter-reuse relations remain open.

Read:

- `graph/artifact_families/DULCE_BOOK_VS_DULCE_WARS.md`
- `data/error_fingerprints/ERR-036-039-MULTI-COMPILATION-INDEPENDENCE-COLLAPSE.md`

## Avalon rollback remains

```yaml
THREAD_8393:
  date: CONFIRMED_NOVEMBER_2010
  Hinkle_testimony: CONFIRMED
  QandA_body: DISPUTED_ACQUISITION_REPORTS
  mature_hierarchy_in_thread: NOT_CONFIRMED
```

## Secure mirror content

Later Branton-derived carriers securely contain:

- Draco as masters of levels 5–6–7;
- Karsh/Khaarshfashst;
- working-caste language;
- `They work for, and are controlled by the Draco`.

Both `Q—` and `A—` labels survive for the control sentence. Structural coherence favors `A—`, but the earliest branch state is unresolved.

## Hierarchy-development candidate

```text
1987-12-13 Lear packet:
drawings / alleged photos / Bennewitz-related enclosures; no mature hierarchy located
        ↓
1989 reported LeVesque/Bishop:
Grey mercenary agency for Draco + alliance/tension
        ↓
1990 or 1991 Matrix II intermediate layer:
Draco elite/castes + Grey mercenaries
        ↓
unknown-date mature Q&A:
explicit control + Karsh + level assignments
        ↓
after 1994-03-18:
COSCON34 editorialized composite
        ↓
October 1996 self-dated related Branton compilation tradition
```

This is a development-of-ideas model, not a proven direct textual chain.

## Current decision

```yaml
exact_full_text_locus: DULCE-CAND-012
first_composition: UNKNOWN
first_mature_carrier: UNKNOWN
October_1996_compilation_self_date: SUPPORTED
COSCON34_pre_Branton_ancestor: EXCLUDED
COSCON34_state_TPQ: 1994-03-18
COSCON34_underlying_QA_date: UNKNOWN
COSCON34_Cosmic_Conflict_identity: CANDIDATE
Matrix_II_intermediate_date: 1990_OR_1991
Dulce_Book_Wars_identity: OPEN
Branton_multi_title_independent_count: ONE_EDITORIAL_FAMILY
November_2010_QA_carrier: DISPUTED
controlled_by_sentence_in_Branton_family: CONFIRMED
Castello_source_class: DOCUMENT_PERSONA_OR_CONTESTED_ATTRIBUTED_SPEAKER
collaborative_multi_actor_model: STRONGEST_NEUTRAL_MODEL
physical_artifacts_recovered: 0
canonical_authorship_edge: false
canonical_first_carrier_edge: false
canonical_work_identity_edge: false
canonical_stemma_edge: false
```
