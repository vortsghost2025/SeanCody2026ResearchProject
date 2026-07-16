# ERR-036-014 — Compilation Header → First Edition Collapse

```yaml
ERROR_FINGERPRINT:
  id: ERR-036-014
  name: COMPILATION_HEADER_FIRST_EDITION_COLLAPSE
  related_question: RQ-036
  status: SUPPORTED

  collapse: >
    A later digital edition displaying `The Dulce Book by Branton (1996)` is
    treated as an inspected original first edition and as proof that every
    chapter, including the Castello Q&A, was first composed or circulated in 1996.

  correct_boundary: >
    The header supports a 1996 compilation attribution in that digital family.
    It does not identify the original publisher, copyright state, print run,
    first carrier of the Q&A or composition date of its answer layer.

  safe_result:
    - SOFT_BIBLIOGRAPHIC_CARRIER_LEAD
    - COMPILATION_HEADER_DATE
    - Q_AND_A_MAY_PREDATE_COMPILATION

  unsafe_result:
    - PHYSICAL_FIRST_EDITION_CONFIRMED
    - Q_AND_A_COMPOSED_IN_1996
    - FIRST_CARRIER_CONFIRMED
    - ORIGINAL_COPYRIGHT_PAGE_INSPECTED

  promotion_test:
    - physical or faithful first-edition title page
    - copyright page and colophon
    - publisher and printer record
    - ISBN or catalogue number
    - contemporary advertisement or review
    - chapter comparison with earlier electronic state

  generated_session: SESSION_045
  last_reviewed: 2026-07-16
```

## Guardrail

```text
1996 compilation header
        = evidence for that compilation state
        ≠ first-edition inspection
        ≠ Q&A composition date
        ≠ first circulation date
```
