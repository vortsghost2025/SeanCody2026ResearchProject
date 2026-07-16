# ERR-036-032 — Dulce Papers Drawings / Q&A Collapse

```yaml
ERROR_FINGERPRINT:
  id: ERR-036-032
  name: DULCE_PAPERS_DRAWINGS_QA_COLLAPSE
  related_question: RQ-036
  status: SUPPORTED

  collapse: >
    Every object called `The Dulce Papers` is treated as one stable artifact,
    allowing a 1987 distribution date for drawings or enclosures to backdate the
    later Castello interview Q&A and its mature hierarchy wording.

  current_evidence: >
    The reported December 13, 1987 Lear letter describes ink drawings, alleged
    interior photographs, vats and related enclosures. The supplied quotation does
    not contain the mature Draco/Grey Q&A chain.

  correct_boundary: >
    The 1987 drawing/enclosure packet and the later interview Q&A must be tracked as
    separate artifact families until a dated inventory proves they circulated together.

  safe_labels:
    - DULCE_PAPERS_DRAWINGS_FAMILY
    - CASTELLO_QA_FAMILY
    - SHARED_NARRATIVE_ENVIRONMENT
    - BUNDLING_DATE_UNKNOWN

  unsafe_labels:
    - FULL_QA_DISTRIBUTED_IN_1987
    - DRACO_HIERARCHY_PROVED_BY_1987_LETTER
    - ALL_DULCE_PAPERS_VERSIONS_IDENTICAL

  promotion_test:
    - complete Lear letter and enclosures
    - item-level packet inventory
    - earliest Q&A carrier
    - evidence of bundling date
    - sentence and diagram comparison

  generated_session: SESSION_050
  last_reviewed: 2026-07-16
```
