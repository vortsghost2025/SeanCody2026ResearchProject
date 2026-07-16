# ERR-036-036 — Title Variant → Work Identity Collapse

```yaml
ERROR_FINGERPRINT:
  id: ERR-036-036
  name: TITLE_VARIANT_WORK_IDENTITY_COLLAPSE
  related_question: RQ-036
  status: SUPPORTED

  collapse: >
    Two titles sharing an author, date environment and chapter corpus are automatically
    treated either as one identical work or as two independent publications without
    item-level edition comparison.

  instance: >
    The Dulce Book and The Dulce Wars are both associated with Branton and 1996-era
    metadata and appear to share substantial chapter structure. Their exact identity,
    retitling, expansion and publication sequence remain unresolved.

  correct_boundary: >
    Treat them as one compilation family pending title-page, contents and chapter diff.
    Do not count them as independent hierarchy witnesses.

  safe_labels:
    - SHARED_COMPILATION_FAMILY
    - RETITLED_EDITION_PROBABLE
    - WORK_IDENTITY_OPEN
    - INDEPENDENT_SOURCE_COUNT_ONE_PENDING_DIFF

  unsafe_labels:
    - IDENTICAL_WORK_CONFIRMED
    - TWO_INDEPENDENT_1996_SOURCES
    - TITLE_DIFFERENCE_PROVES_DISTINCT_CONTENT

  promotion_test:
    - physical or raw digital title pages
    - copyright pages
    - ISBN/catalogue records
    - complete tables of contents
    - page counts
    - chapter-level diff
    - edition and publisher statements

  generated_session: SESSION_055
  last_reviewed: 2026-07-16
```
