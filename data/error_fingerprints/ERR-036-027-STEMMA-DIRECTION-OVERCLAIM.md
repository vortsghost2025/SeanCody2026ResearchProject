# ERR-036-027 — Textual-Stemma Direction Overclaim

```yaml
ERROR_FINGERPRINT:
  id: ERR-036-027
  name: STEMMA_DIRECTION_OVERCLAIM
  related_question: RQ-036
  status: SUPPORTED

  collapse: >
    A simpler-looking later text with fewer notes, quotation marks or capitalization
    is automatically declared ancestral to a more edited-looking text, without raw
    files, hashes, intermediate carriers or independent chronology.

  session_049_example: >
    Avalon-versus-Branton differences are used to declare H1 rejected and H2 proven.
    The evidence supports a distinct-state candidate and a signed Branton editorial
    layer, but not a completed direction of descent.

  alternative_explanations:
    - Branton edited an earlier source
    - Hinkle or relay poster removed Branton comments
    - both copied a common ancestor
    - web formatting normalized punctuation or emphasis
    - an intermediate copy introduced the differences

  safe_labels:
    - DISTINCT_TEXTUAL_STATE_CANDIDATE
    - BRANTON_SIGNED_EDITORIAL_LAYER
    - DIRECTION_PLAUSIBLE_NOT_PROVED
    - COMMON_ANCESTOR_POSSIBLE

  unsafe_labels:
    - AVALON_CANNOT_DERIVE_FROM_BRANTON
    - BRANTON_DEMONSTRABLY_EDITED_HINKLE_ORIGINAL
    - SIMPLE_PUNCTUATION_EQUALS_EARLIER_TEXT
    - STEMMA_RESOLVED_WITHOUT_RAW_CORPUS

  promotion_test:
    - complete raw carrier captures
    - hashes
    - post IDs and timestamps
    - earliest Branton states
    - deterministic diff
    - shared-error analysis
    - intermediate witness search

  generated_session: SESSION_049
  last_reviewed: 2026-07-16
```
