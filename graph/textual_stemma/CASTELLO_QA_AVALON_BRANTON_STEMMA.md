# Castello Q&A — Avalon / Branton Textual Stemma

> **Related:** `RQ-036`, `BRIDGE-036-001`, `DULCE-CAND-012`, `028`, `039`, `040`  
> **Status:** direct Avalon Q&A state not reproducibly acquired; derivation unresolved

## Carrier nodes

```yaml
CARRIER_NODES:
  - id: QA-AVALON-2010-THREAD
    date: NOVEMBER_2010
    date_basis: PROJECT_AVALON_THREAD_TIMESTAMPS
    carrier: THREAD_8393
    participant_testimony: CONFIRMED
    QandA_body: DISPUTED_ACQUISITION_REPORTS
    direct_Hinkle_QA: DISPUTED
    W_relay_QA: DISPUTED
    exact_decisive_post_ID: UNKNOWN
    raw_HTML_in_repository: false

  - id: QA-BRANTON-MIRROR-FAMILY
    date: MULTIPLE_LATER_DATED_MIRRORS
    date_basis: WEB_CARRIER_DATES
    carrier: DULCE_BOOK_CHAPTER_11_DERIVATIVES
    mature_hierarchy: CONFIRMED
    signed_editorial_notes: PRESENT_IN_SOME_STATES
    earliest_raw_source_state: NOT_ACQUIRED

  - id: QA-BRANTON-EARLY-CARRIER-CLAIMS
    date: 1991_CLAIMED_1996_SOFT
    date_basis: INTERNAL_REFERENCE_HEADER_RETAILER_METADATA
    carrier: UNKNOWN_OR_UNINSPECTED
    status: NOT_ITEM_LEVEL_VERIFIED
```

## Session 050 contradiction

```text
Acquisition A:
no Q&A body found in the acquired Thread 8393 state

Acquisition B:
Q&A body directly posted by Mystery/Hinkle

Earlier acquisitions:
Q&A body relayed by unidentified W
```

No decisive raw file, exact post ID or valid attached hash accompanies these claims.

```yaml
AVALON_QA_STATE:
  presence: DISPUTED
  poster: UNKNOWN
  hierarchy_text: NOT_CONFIRMED
  stemmatic_use: BLOCKED
```

## Secure Branton-derived passage family

Later mirrors securely preserve:

- Draco as masters of levels 5–6–7;
- Karsh/Khaarshfashst;
- working-caste language;
- `They work for, and are controlled by the Draco`;
- Dulce laboratory and command structure.

One later mirror labels the control sentence `Q—` while the dominant mirror state labels it `A—`. This is tracked as a probable transcription/copying error.

## Previously reported Avalon differences

Earlier acquisitions reported:

| Feature | Alleged Avalon state | Branton-derived state |
|---|---|---|
| number agreement | `Draco is ... master` | `Draco are ... masters` |
| Nordic parenthetical | absent | present and signed `– Branton` |
| emphasis | lowercase | uppercase |
| pronunciation delimiters | round brackets | square brackets |
| quotation marks | fewer | more |

Because the alleged Avalon body is not reproducibly stored, these remain **reported candidate differences**, not a validated stemmatic matrix.

## Hypothesis matrix

```yaml
H1_AVALON_FROM_BRANTON:
  status: UNTESTABLE_UNTIL_AVALON_QA_ACQUIRED

H2_BRANTON_FROM_AVALON_LIKE_SOURCE:
  status: UNTESTABLE_UNTIL_AVALON_QA_ACQUIRED

H3_COMMON_ANCESTOR:
  status: POSSIBLE_BUT_UNTESTED

H4_RENDERING_ONLY:
  status: UNTESTABLE_FOR_AVALON_COMPARISON
```

The signed Branton parenthetical proves a Branton editorial layer where it appears. It does not identify the source state or date the underlying answer text.

## Related artifact-family context

```text
1987 Dulce Papers drawings/enclosures
        ≠
later mature interview Q&A
```

Read: `graph/artifact_families/DULCE_PAPERS_VS_CASTELLO_QA.md`.

## Conceptual development context

```text
1989 reported LeVesque/Bishop:
Grey mercenary agency for Draco + Grey/Reptoid alliance/tension
        ↓
1990 reported intermediate layer:
Draco elite/castes + Grey mercenaries
        ↓
unknown-date mature Q&A:
explicit control + Karsh + level assignments
```

This is an idea-development candidate, not a textual stemma.

## Promotion requirements

1. complete raw Thread 8393 capture across all pages/views;
2. exact Q&A post ID, poster, timestamp and HTML;
3. valid hashes tied to committed raw bytes;
4. raw earliest Branton carriers;
5. diplomatic and normalized transcriptions;
6. deterministic character, sentence and order diffs;
7. capture chronology independent of claimed publication dates.

## Current decision

```yaml
Avalon_thread_date: CONFIRMED
Avalon_QA_presence: DISPUTED
Avalon_QA_poster: UNKNOWN
controlled_by_sentence_in_Avalon: NOT_CONFIRMED
mature_Branton_mirror_family: CONFIRMED
Branton_signed_editorial_layer: CONFIRMED_WHERE_PRESENT
Q_A_label_variant: PROBABLE_COPYING_ERROR
derivation_direction: UNRESOLVED
common_ancestor: POSSIBLE
first_composition: UNKNOWN
canonical_stemma_edge: false
```
