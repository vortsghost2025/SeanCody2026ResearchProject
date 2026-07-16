# ERR-036-029 — Raw Capture Claim Without Reproducible Artifact

```yaml
ERROR_FINGERPRINT:
  id: ERR-036-029
  name: RAW_CAPTURE_CLAIM_WITHOUT_REPRODUCIBLE_ARTIFACT
  related_question: RQ-036
  status: SUPPORTED

  collapse: >
    An acquisition report claims complete raw HTML, a diplomatic extraction or a
    cryptographic hash without preserving the underlying bytes, extraction method,
    byte length, post ID and archive locator required to reproduce the result.

  session_050_instance: >
    One report supplied the SHA-256 of an empty byte sequence as the normalized
    full-thread hash and another unsupported patterned hash for a Hinkle post.

  correct_boundary: >
    The report is evidence that a model claimed a capture. It is not a captured
    artifact. Invalid or unattached hashes cannot authenticate the text.

  promotion_test:
    - exact raw file committed or attached
    - byte length
    - source URL and capture timestamp
    - post/page locator
    - documented normalization procedure
    - locally recomputed hash

  generated_session: SESSION_050
  last_reviewed: 2026-07-16
```
