# ERR-036-033 — Source-Article Date → Compilation-Date Collapse

```yaml
ERROR_FINGERPRINT:
  id: ERR-036-033
  name: SOURCE_ARTICLE_DATE_COMPILATION_DATE_COLLAPSE
  related_question: RQ-036
  status: SUPPORTED

  collapse: >
    A date attached to an article, quotation or source used inside a compilation is
    transferred to the compilation itself or to every chapter carried by it.

  instance: >
    A 1991 reference inside Branton material was repeatedly treated as a 1991 date
    for The Dulce Book or Chapter 11. The surviving compilation tradition instead
    contains an October 1996 Branton sign-off, while the 1991 language refers to
    source material quoted or discussed inside the compilation.

  correct_boundary: >
    Source-event date, quoted-article date, chapter-composition date, compilation date,
    carrier date and later upload date must remain separate.

  safe_labels:
    - 1991_SOURCE_ARTICLE_DATE
    - OCTOBER_1996_COMPILATION_SELF_DATE
    - CHAPTER_11_FIRST_CARRIER_UNRESOLVED

  unsafe_labels:
    - 1991_DULCE_BOOK_CONFIRMED
    - 1991_CHAPTER_11_CARRIER_CONFIRMED
    - INTERNAL_DATE_EQUALS_PUBLICATION_DATE

  promotion_test:
    - original title and copyright pages
    - BBS header or upload record
    - dated manuscript
    - contemporary catalogue
    - collector provenance
    - complete date-bearing context

  generated_session: SESSION_055
  last_reviewed: 2026-07-16
```
