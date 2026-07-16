# ERR-036-035 — Edition Page-Count → Content Transfer

```yaml
ERROR_FINGERPRINT:
  id: ERR-036-035
  name: EDITION_PAGE_COUNT_CONTENT_TRANSFER
  related_question: RQ-036
  status: SUPPORTED

  collapse: >
    A passage found in a substantially expanded later edition is assigned to an
    earlier edition solely because both share the same work title and nominal year.

  instance: >
    Matrix II's reported 1990 first edition contains 458 pages, while the inspected
    1991 third edition contains approximately 661 or more pages and added material.
    The Pasturing and Use hierarchy section cannot be assigned to the first edition
    until the 458-page state is inspected.

  correct_boundary: >
    Bibliographic identity does not establish content identity across editions.
    The first-edition table of contents, index and section pages are required.

  safe_labels:
    - 1990_FIRST_EDITION_METADATA_CONFIRMED_BY_DEALER_RECORD
    - 1991_THIRD_EDITION_PASSAGE_CONFIRMED
    - FIRST_EDITION_PASSAGE_PRESENCE_UNKNOWN
    - INTERMEDIATE_HIERARCHY_DATE_1990_OR_1991

  unsafe_labels:
    - PASTURING_CONFIRMED_IN_1990_FIRST
    - THIRD_EDITION_WORDING_BACKDATED_TO_FIRST
    - SAME_TITLE_EQUALS_SAME_CONTENT

  promotion_test:
    - 458-page first-edition scans
    - title/copyright/colophon pages
    - contents and index
    - exact section pages
    - first-to-third page-level diff

  generated_session: SESSION_055
  last_reviewed: 2026-07-16
```
