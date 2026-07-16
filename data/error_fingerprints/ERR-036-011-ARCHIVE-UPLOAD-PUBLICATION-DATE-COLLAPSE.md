# ERR-036-011 — Archive Upload → Publication Date Collapse

```yaml
ERROR_FINGERPRINT:
  id: ERR-036-011
  name: ARCHIVE_UPLOAD_PUBLICATION_DATE_COLLAPSE
  related_question: RQ-036
  status: SUPPORTED

  collapse: >
    A later Archive.org identifier, upload year-month, filename, scan date or
    mirror metadata is treated as the original composition or publication date
    of The Dulce Book or the Castello Q&A.

  correct_boundary: >
    Upload and scan metadata date the repository event only. Publication or
    composition requires an original header, BBS post, copyright page, colophon,
    contemporaneous catalogue, dated correspondence or another item-level witness.

  unsafe_inference:
    - ARCHIVE_UPLOAD_DATE_EQUALS_PUBLICATION_DATE
    - FILE_LABEL_EQUALS_ORIGINAL_VERSION_DATE
    - LATER_MIRROR_METADATA_EQUALS_FIRST_CARRIER

  promotion_test:
    - original file or BBS header
    - physical copyright or title page
    - contemporaneous catalogue or advertisement
    - collector provenance
    - dated citation to exact version

  generated_session: SESSION_045
  last_reviewed: 2026-07-16
```

## Guardrail

```text
uploaded in 2016
        ≠
written in 2016
        ≠
first circulated in 1991
        ≠
first published in 1996
```
