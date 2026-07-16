# Castello Q&A — Avalon / Branton Textual Stemma

> **Related:** `RQ-036`, `BRIDGE-036-001`, `DULCE-CAND-012`, `DULCE-CAND-028`  
> **Status:** distinct-state candidate; direction unresolved pending raw hashed corpus

## Carrier nodes

```yaml
CARRIER_NODES:
  - id: QA-AVALON-2010-THREAD
    date: NOVEMBER_2010
    date_basis: PROJECT_AVALON_THREAD_TIMESTAMPS
    carrier: THREAD_8393
    direct_Hinkle_posts: PERSONAL_TESTIMONY_REPORTED
    relay_QA_post: REPORTED_BY_POSTER_W
    exact_post_ID: UNKNOWN
    raw_HTML_in_repository: false

  - id: QA-BRANTON-CH11
    date: SOFT_1996_OR_LATER_CARRIER_FAMILY
    date_basis: COMPILATION_HEADER_AND_LATER_METADATA
    carrier: DULCE_BOOK_CHAPTER_11_FAMILY
    signed_editorial_notes: PRESENT
    earliest_raw_state_in_repository: false
```

## Poster-layer model

```text
Cherry Hinkle / Mystery direct posts
        = participant testimony and source claims

`W` relay post
        = Q&A text attributed to Cherry/Hinkle

Bill Ryan / moderator material
        = forum framing and endorsement

later mirrors
        = derivative carrier family
```

Do not collapse all thread content into `Hinkle wrote this post`.

## Reported shared passage family

The acquisition returns report shared substance including:

- Draco as master(s) of levels 5–6–7;
- worker-caste language;
- Karsh/Khaarshfashst;
- Dulce laboratory and level descriptions;
- Grey groups working for or controlled by Draco.

The exact `controlled by the Draco` sentence is reported present in the Avalon relay state but has not yet been stored with raw HTML, post ID and hash.

## Reported differences

| Feature | Avalon relay state reported | Branton state reported | Current interpretation |
|---|---|---|---|
| number agreement | `Draco is ... master` | `Draco are ... masters` | possible editorial normalization or variant copy |
| Nordic parenthetical | absent | present and signed `– Branton` | confirmed Branton layer where present |
| emphasis | lowercase `argue` | uppercase `ARGUE` | possible editor/format layer |
| pronunciation delimiters | round brackets | square brackets | weak stemmatic signal |
| quotation marks | fewer | more | weak stemmatic signal |

## Hypothesis matrix

```yaml
H1_AVALON_FROM_BRANTON:
  support:
    - 2010 postdates the softly attested Branton carrier family
    - a relay poster could remove comments or normalize a copied text
  counterevidence:
    - reported omission of signed Branton material
    - systematic simpler rendering reported
  status: PLAUSIBLE_NOT_EXCLUDED

H2_BRANTON_FROM_AVALON_LIKE_SOURCE:
  support:
    - signed Branton addition in one state
    - reported editorial normalization and stylistic additions
  limitation:
    - Avalon 2010 itself postdates Branton carrier claims
    - no earlier Avalon-like object acquired
  status: PLAUSIBLE_DIRECTIONALLY_SUPPORTED

H3_COMMON_ANCESTOR:
  support:
    - explains shared wording plus divergent editorial states
  limitation:
    - ancestor not acquired
  status: PLAUSIBLE

H4_RENDERING_ONLY:
  support:
    - punctuation, brackets and capitalization can change in web copying
  counterevidence:
    - signed Branton parenthetical is an actual content layer
  status: INSUFFICIENT_AS_COMPLETE_EXPLANATION
```

## Current stemma

```text
UNKNOWN Q&A SOURCE STATE
        |
        |------------------------------|
        |                              |
Avalon-associated relay state      Branton Chapter 11 state
publicly carried Nov. 2010         soft date / carrier conflict
        |                              |
possible simplified or source-like     signed notes + editorial markup
rendering                             
```

Arrow direction between the two branches is not established.

## Hierarchy-development context

A separate conceptual progression is preserved:

```text
LeVesque/Bishop 1989 reported:
Grey mercenary agency for Draco + Grey/Reptoid alliance/tension
        ↓
LeVesque `Pasturing and Use...` / Matrix II 1990 reported:
Draco elite + reptilian castes + Grey mercenaries
        ↓
unknown-date mature Q&A:
explicit control + Karsh + level assignments + undisputed mastery
```

This is a development-of-ideas model, not a proven direct textual chain.

## Promotion requirements

1. complete raw Thread 8393 HTML and archive captures;
2. exact `W` post ID, timestamp and identity evidence;
3. diplomatic extraction of the complete relay Q&A;
4. raw earliest Branton carriers;
5. cryptographic hashes;
6. deterministic raw, normalized and sentence-order diffs;
7. copied-error analysis;
8. carrier chronology independent of compilation claims.

## Current decision

```yaml
distinct_textual_state: STRONG_CANDIDATE
Branton_signed_editorial_layer: CONFIRMED_WHERE_PRESENT
controlled_by_sentence_in_Avalon: REPORTED_PENDING_RAW_CAPTURE
derivation_direction: UNRESOLVED
common_ancestor: PLAUSIBLE
first_composition: UNKNOWN
canonical_stemma_edge: false
```
