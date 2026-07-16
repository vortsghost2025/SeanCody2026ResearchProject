# ERR-036-023 — Textual Variant → Derivation Collapse

```yaml
ERROR_FINGERPRINT:
  id: ERR-036-023
  name: TEXTUAL_VARIANT_DERIVATION_COLLAPSE
  related_question: RQ-036
  status: SUPPORTED

  collapse: >
    Minor differences between the Hinkle 2010 Avalon Q&A rendering and a Branton
    chapter rendering are treated as conclusive proof that one directly edited the
    other in a particular direction.

  current_evidence: >
    Session 048 variants disagree between near-identity/derivative and distinct-state
    readings. Reported differences include number agreement, brackets, capitalization,
    quotation marks and an explicit signed Branton gloss.

  correct_boundary: >
    The 2010 public carrier and mature hierarchy wording are established. A distinct
    textual-state candidate is strong, but direction of derivation requires complete
    raw captures, extraction provenance, hashes and a reproducible diff. Both may
    descend from a common source.

  safe_labels:
    - HINKLE_2010_DATED_QA_CARRIER
    - DISTINCT_TEXTUAL_STATE_CANDIDATE
    - COMMON_ANCESTOR_POSSIBLE
    - DIRECTION_OF_DERIVATION_UNRESOLVED

  unsafe_labels:
    - BRANTON_DEFINITIVELY_EDITED_HINKLE_TEXT
    - HINKLE_DEFINITIVELY_STRIPPED_BRANTON_TEXT
    - IDENTICAL_TEXT_PROVED_WITHOUT_RAW_DIFF
    - PRE_1996_HINKLE_TEXT_CONFIRMED

  promotion_test:
    - complete raw HTML captures
    - exact post IDs and timestamps
    - normalized and diplomatic transcriptions
    - cryptographic hashes
    - deterministic sentence and character diff
    - earliest Branton-state capture
    - formatting-versus-wording separation

  generated_session: SESSION_048
  last_reviewed: 2026-07-16
```
