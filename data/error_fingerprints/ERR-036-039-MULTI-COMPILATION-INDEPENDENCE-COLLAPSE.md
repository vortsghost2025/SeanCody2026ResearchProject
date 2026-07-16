# ERR-036-039 — Multi-Compilation Independence Collapse

```yaml
ERROR_FINGERPRINT:
  id: ERR-036-039
  name: MULTI_COMPILATION_INDEPENDENCE_COLLAPSE
  related_question: RQ-036
  status: SUPPORTED

  collapse: >
    Repetition of the same source text across several books, chapter exports or
    commercial editions by the same compiler and publisher ecosystem is counted as
    multiple independent confirmations.

  session_056_instance: >
    The mature Q&A appears or is reported across The Dulce Book, The Dulce Wars,
    COSCON34 and possibly Cosmic Conflict. These may be distinct works or editions,
    but all remain inside one Branton editorial and Beckley/Inner Light/Global
    Communications distribution family.

  correct_boundary: >
    Distinct titles and editions are separate artifacts and should be compared.
    They are not independent witnesses to the underlying hierarchy unless they
    preserve independently sourced material with separate provenance.

  safe_labels:
    - DISTINCT_CARRIER_OR_EDITION
    - ONE_BRANTON_EDITORIAL_FAMILY
    - WORK_IDENTITY_OPEN
    - INDEPENDENT_SOURCE_COUNT_ONE

  unsafe_labels:
    - MULTIPLE_INDEPENDENT_CONFIRMATIONS
    - EACH_TITLE_IS_AN_INDEPENDENT_SOURCE
    - CROSS_TITLE_REPETITION_PROVES_HISTORICAL_EVENT

  promotion_test:
    - independent manuscript provenance
    - different source acknowledgements and custody
    - pre-Branton carrier for one branch
    - diagnostic text showing separate acquisition rather than reuse
    - correspondence documenting independent receipt

  generated_session: SESSION_056
  last_reviewed: 2026-07-16
```
