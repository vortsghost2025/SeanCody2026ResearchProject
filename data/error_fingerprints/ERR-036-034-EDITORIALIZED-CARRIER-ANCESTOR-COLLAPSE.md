# ERR-036-034 — Editorialized Carrier → Source Ancestor Collapse

```yaml
ERROR_FINGERPRINT:
  id: ERR-036-034
  name: EDITORIALIZED_CARRIER_ANCESTOR_COLLAPSE
  related_question: RQ-036
  status: SUPPORTED

  collapse: >
    A carrier with an old-looking filename, plain-text format or BBS-style naming
    convention is treated as the unedited ancestor of a text family even though it
    contains identifiable later editor material.

  instance: >
    COSCON34 was considered as a possible pre-Branton source. The surviving text
    contains Branton editorial parentheticals, excluding it as an unedited source
    anterior to Branton's intervention.

  correct_boundary: >
    File naming and format can suggest a distribution environment. Editorial content
    establishes that the surviving state is Branton-edited or Branton-derived. Its
    exact date and relation to other Branton carriers remain open.

  safe_labels:
    - BRANTON_EDITED_CARRIER
    - BBS_STYLE_FILENAME_LEAD
    - CARRIER_DATE_UNKNOWN
    - CONTEMPORARY_OR_DERIVATIVE

  unsafe_labels:
    - PRE_BRANTON_SOURCE_CONFIRMED
    - EARLY_BBS_FILENAME_PROVES_DATE
    - COSCON34_IS_ORIGINAL_INTERVIEW

  promotion_test:
    - original file bytes and timestamp
    - BBS file list or catalogue
    - sysop/uploader record
    - conference identity
    - dated capture
    - comparison with Branton working and compilation states

  generated_session: SESSION_055
  last_reviewed: 2026-07-16
```
