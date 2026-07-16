# ERR-036-016 — Fabrication Assertion Chronology Collapse

```yaml
ERROR_FINGERPRINT:
  id: ERR-036-016
  name: FABRICATION_ASSERTION_CHRONOLOGY_COLLAPSE
  related_question: RQ-036
  status: CANDIDATE_SUPPORTED_PENDING_PRIMARY_MANUSCRIPT

  collapse: >
    The first surviving modern publication of a fabrication allegation is treated
    as the first time the allegation existed, erasing earlier hostile or
    contemporaneous claims.

  current_case: >
    A secondary report states that Christa Tilton's 1987 manuscript The Bennewitz
    Papers described the Thomas Castello story as fabricated. The manuscript has
    not yet been acquired. Gorightly's 2021 publication of LeVesque's 2015 email
    is therefore not automatically the first fabrication assertion.

  correct_boundary: >
    Distinguish first alleged assertion, first recoverable primary artifact,
    first published confession, and first authenticated direct admission.

  safe_labels:
    - TILTON_1987_HOSTILE_ASSERTION_LEAD
    - MANUSCRIPT_UNRECOVERED
    - LEVESQUE_2015_SELF_ATTESTATION
    - GORIGHTLY_2021_FIRST_CURRENTLY_ACQUIRED_PUBLICATION

  unsafe_labels_without_more_evidence:
    - FABRICATION_HYPOTHESIS_BEGAN_IN_2021
    - TILTON_1987_PRIMARY_CONFIRMED
    - LEVESQUE_CONFESSION_WAS_FIRST_DOUBT

  promotion_test:
    - acquire exact 1987 manuscript
    - verify title, date and distribution
    - locate exact Castello passage
    - establish custody and edition

  generated_session: SESSION_046
  last_reviewed: 2026-07-16
```
