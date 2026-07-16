# COSCON34 — Branton-Edited Q&A Carrier

> **Related:** `RQ-036`, `DULCE-CAND-012`, Sessions 055–056  
> **Status:** Branton-edited carrier supported; post-March-1994 composite state; exact title/carrier identity unresolved

## Surviving web carriers

```yaml
COSCON34_CARRIERS:
  - url: geocities.ws/hangtime96.geo/coscon34.html
    medium: HTML_RENDERING
  - url: pages.suddenlink.net/anomalousimages/images/text/COSCON34.TXT
    medium: PLAIN_TEXT_RENDERING
```

## Content result

The surviving state contains the mature Castello-attributed Q&A family and Branton editorial parentheticals.

```text
mature Q&A answer text
        +
Branton editorial insertions
        =
Branton-edited or Branton-derived carrier
```

## Internal March 1994 date anchor

The text reportedly cites a March 18, 1994 *Plain Dealer* article.

```yaml
COSCON34_EDITORIALIZED_STATE:
  internal_reference_date: 1994-03-18
  terminus_post_quem: 1994-03-18
  date_effect: COMPOSITE_STATE_CANNOT_PREDATE_REFERENCE
```

This dates the state containing the newspaper reference—not the composition of every embedded source layer.

```text
COSCON34 composite assembled after 1994-03-18
        ≠
underlying mature Q&A existed before 1994-03-18
```

The Q&A may predate the parenthetical, be contemporary with it or have been inserted later. No upper bound for Q&A composition follows from the internal citation alone.

Read:

- `data/error_fingerprints/ERR-036-037-TERMINUS-POST-QUEM-SOURCE-COMPOSITION-COLLAPSE.md`

## Closed hypothesis

```yaml
COSCON34_IS_UNEDITED_PRE_BRANTON_SOURCE:
  status: EXCLUDED
  basis: BRANTON_EDITORIAL_PARENTHEICALS_PRESENT
```

## Carrier-identity dispute

One Session 056 variant proposes:

```text
COSCON34 = COSmic CONflict, chapter 34
```

This is coherent but requires explicit carrier evidence. The supplied report did not preserve a title header, contents page, chapter listing or directory sequence proving the expansion.

```yaml
COSCON34_IDENTITY:
  Cosmic_Conflict_chapter_34: HIGH_VALUE_CANDIDATE
  standalone_BBS_sequence_file: NOT_ESTABLISHED
  generic_BBS_export: NOT_EXCLUDED
  shared_Branton_working_file: NOT_EXCLUDED
  later_excerpt: NOT_EXCLUDED
```

Filename shape alone proves neither interpretation.

Read:

- `data/error_fingerprints/ERR-036-038-FILENAME-STEM-CARRIER-IDENTITY-COLLAPSE.md`

## Current carrier models

```yaml
H1:
  description: COSCON34 is Cosmic Conflict chapter 34
  status: PLAUSIBLE_PENDING_TITLE_OR_CONTENTS_PROOF
H2:
  description: COSCON34 is a standalone Branton text export
  status: PLAUSIBLE
H3:
  description: COSCON34 and a larger compilation descend from a shared Branton-edited file
  status: PLAUSIBLE
H4:
  description: COSCON34 is a later excerpt from The Dulce Book or another Branton compilation
  status: PLAUSIBLE
H5:
  description: COSCON34 is a mixed state combining earlier answers and later Branton notes
  status: PLAUSIBLE
```

## Missing identity evidence

- explicit work title in file/header;
- complete HTML title and navigation frame;
- contents page mapping chapter 34;
- neighboring `COSCON` files and chapter titles;
- original directory or archive listing;
- publisher catalogue;
- original file bytes/timestamp;
- first web capture;
- relation to *The Dulce Book*, *The Dulce Wars* or *Cosmic Conflict*.

## Current stemma placement

```text
UNKNOWN MATURE Q&A SOURCE
        ↓
BRANTON EDITORIAL INTERVENTION
        ↓
POST-1994-03-18 COSCON34 COMPOSITE STATE
        ↓
exact containing work / export channel unresolved
```

The October 1996 self-date belongs to a related Branton carrier tradition. It cannot be used as a COSCON34 terminus ante quem until carrier identity is proved.

## Current decision

```yaml
mature_QA_present: true
Branton_editorial_layer_present: true
pre_Branton_unedited_ancestor: false
internal_state_TPQ: 1994-03-18
underlying_QA_date: UNKNOWN
Cosmic_Conflict_chapter_identity: CANDIDATE_NOT_CONFIRMED
BBS_sequence_identity: NOT_ESTABLISHED
carrier_date_upper_bound: UNKNOWN
canonical_stemma_edge: false
```
