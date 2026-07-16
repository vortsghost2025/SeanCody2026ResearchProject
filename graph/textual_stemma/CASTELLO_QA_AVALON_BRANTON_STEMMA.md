# Castello Q&A — Avalon / Branton Textual Stemma

> **Related:** `RQ-036`, `BRIDGE-036-001`, `DULCE-CAND-012`, `013`, `047`  
> **Status:** Branton-edited carrier family expanded; unedited source ancestor and derivation direction unresolved

## Carrier nodes

```yaml
CARRIER_NODES:
  - id: QA-SOURCE-UNKNOWN
    date: UNKNOWN
    carrier: UNRECOVERED_QA_SOURCE
    content: MATURE_HIERARCHY_PRESUMED_FROM_DESCENDANTS

  - id: QA-COSCON34
    date: UNKNOWN
    carrier:
      - COSCON34.TXT
      - COSCON34_HTML_RENDERING
    mature_hierarchy: PRESENT
    Branton_editorial_parentheticals: PRESENT
    classification: BRANTON_EDITED_CARRIER
    unedited_pre_Branton_source: false

  - id: QA-BRANTON-1996-FAMILY
    date: OCTOBER_1996_SELF_DATE_ENVIRONMENT
    carrier: DULCE_BOOK_DULCE_WARS_FAMILY
    mature_hierarchy: PRESENT
    signed_editorial_notes: PRESENT
    exact_first_publication: NOT_ACQUIRED
    title_identity: OPEN

  - id: QA-AVALON-2010-THREAD
    date: NOVEMBER_2010
    carrier: THREAD_8393
    participant_testimony: CONFIRMED
    QandA_body: DISPUTED_ACQUISITION_REPORTS
    exact_decisive_post_ID: UNKNOWN
    raw_HTML_in_repository: false

  - id: QA-LATER-MIRROR-FAMILY
    date: MULTIPLE_LATER_DATED_WEB_CARRIERS
    mature_hierarchy: CONFIRMED
    QA_label_branches:
      - Q
      - A
```

## COSCON34 closure

The surviving COSCON34 state contains Branton editorial material.

```text
old-looking plain-text carrier
        +
Branton editorial parentheticals
        ↓
Branton-edited or Branton-derived state
```

Therefore:

```yaml
COSCON34_IS_UNEDITED_PRE_BRANTON_ANCESTOR: EXCLUDED
```

This does not determine whether COSCON34 preceded the October 1996 compilation, was exported from a contemporary working file, or was extracted later.

Read: `graph/textual_stemma/COSCON34_BRANTON_CARRIER.md`.

## Revised stemma

```text
UNKNOWN MATURE Q&A SOURCE STATE
        ↓
BRANTON EDITORIAL INTERVENTION
        ↓
        |-------------------------------|
        |                               |
COSCON34 carrier                 Dulce Book / Dulce Wars family
unknown date                     October 1996 self-date environment
        |                               |
        |-------------------------------|
                        ↓
              later derivative mirrors
```

The relation between COSCON34 and any specific 1996 edition is unresolved.

## Avalon status

```yaml
AVALON_QA_STATE:
  thread_date: CONFIRMED
  participant_testimony: CONFIRMED
  QandA_presence: DISPUTED
  poster: UNKNOWN
  hierarchy_text: NOT_CONFIRMED
  stemmatic_use: BLOCKED
```

No raw decisive post has been stored.

## Date-layer boundary

```text
1991 quoted/source-material date
        ≠
1991 compilation carrier date
```

The surviving Branton family supports an October 1996 compilation self-date. The first public carrier may be earlier, but no item-level BBS or manuscript record establishes it.

## Q/A-label branches

Both `Q—` and `A—` survive for the control sentence in later carriers.

```yaml
QA_LABEL:
  Q_branch: MULTIPLE_DERIVATIVES_REPORTED
  A_branch: MULTIPLE_DERIVATIVES_REPORTED
  structural_reading: A_MORE_COHERENT
  earliest_state: UNKNOWN
  stemmatic_weight: LOW_WITHOUT_DATED_CARRIER
```

## Matrix II contextual branch

The 1990 first edition is reported as 458 pages, while the inspected 1991 third edition is substantially longer. The intermediate hierarchy passage cannot be assigned to 1990 until the first edition is inspected.

```text
1989 proto-hierarchy
        ↓
1990 or 1991 intermediate hierarchy
        ↓
unknown mature Q&A source
```

This is conceptual development, not the Q&A carrier stemma itself.

## Hypothesis matrix

```yaml
H1_COSCON34_FROM_1996_COMPILATION:
  status: PLAUSIBLE

H2_1996_COMPILATION_FROM_COSCON34:
  status: PLAUSIBLE_ONLY_IF_COSCON34_IS_EARLIER_BRANTON_WORKING_EXPORT

H3_COSCON34_AND_1996_FROM_SHARED_BRANTON_FILE:
  status: PLAUSIBLE

H4_COSCON34_PRE_BRANTON_UNEDITED_SOURCE:
  status: EXCLUDED

H5_AVALON_FROM_BRANTON:
  status: UNTESTABLE_UNTIL_AVALON_QA_ACQUIRED

H6_COMMON_PRE_BRANTON_QA_ANCESTOR:
  status: POSSIBLE_NOT_ACQUIRED
```

## Promotion requirements

1. recover original COSCON34 file bytes and BBS metadata;
2. identify file timestamp, archive path, sysop/uploader and neighboring files;
3. acquire the exact October 1996 carrier containing the Branton sign-off;
4. compare *The Dulce Book* and *The Dulce Wars* item by item;
5. acquire any earlier mature Q&A without Branton editorial content;
6. acquire complete raw Thread 8393 if Avalon remains relevant;
7. run diplomatic and normalized diffs.

## Current decision

```yaml
mature_QA_family: CONFIRMED
COSCON34_Branton_edited: CONFIRMED
COSCON34_pre_Branton_ancestor: false
COSCON34_date: UNKNOWN
October_1996_compilation_self_date: SUPPORTED
Dulce_Book_Wars_identity: OPEN
Avalon_QA_presence: DISPUTED
first_unedited_QA_source: UNKNOWN
first_mature_carrier: UNKNOWN
derivation_direction: UNRESOLVED
canonical_stemma_edge: false
```
