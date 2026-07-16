# ERR-036-028 — Carrier Date / Composition Date Collapse

```yaml
ERROR_FINGERPRINT:
  id: ERR-036-028
  name: CARRIER_DATE_COMPOSITION_DATE_COLLAPSE
  related_question: RQ-036
  status: SUPPORTED

  collapse: >
    The date when a text was publicly posted, uploaded, compiled or reprinted is
    treated as the date when its underlying wording was composed.

  session_049_examples:
    - November 2010 Avalon post treated as proof of a pre-1996 Hinkle source
    - soft 1996 Dulce Book metadata treated as a hard composition date
    - later Archive.org upload metadata treated as a 1991 text date

  correct_boundary: >
    Carrier date, copy date, upload date, compilation date, alleged interview date
    and composition date are separate fields. A later carrier may preserve older
    text, but the age of that text requires an earlier object or a secure dependency
    argument.

  safe_labels:
    - NOVEMBER_2010_PUBLIC_CARRIER
    - SOFT_1996_COMPILATION_LEAD
    - UNDERLYING_COMPOSITION_UNKNOWN
    - PRE_1996_SOURCE_POSSIBLE_NOT_ACQUIRED

  unsafe_labels:
    - AVALON_TEXT_PROVES_PRE_1996_COMPOSITION
    - 1996_HEADER_DATES_EVERY_CHAPTER
    - ARCHIVE_UPLOAD_PROVES_ORIGINAL_PUBLICATION_YEAR

  promotion_test:
    - earlier physical or electronic object
    - file header or postmark
    - contemporary citation
    - custody chain
    - edition comparison
    - diagnostic copied error linking dated states

  generated_session: SESSION_049
  last_reviewed: 2026-07-16
```
