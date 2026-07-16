# ERR-036-038 — Filename Stem → Carrier Identity Collapse

```yaml
ERROR_FINGERPRINT:
  id: ERR-036-038
  name: FILENAME_STEM_CARRIER_IDENTITY_COLLAPSE
  related_question: RQ-036
  status: SUPPORTED

  collapse: >
    A short filename is expanded into a title, distribution channel, sequence number
    or publication identity without an explicit header, contents page, archive path
    or neighboring-file context.

  session_056_instance: >
    COSCON34 may plausibly mean Cosmic Conflict chapter 34. Earlier work also treated
    it as a possible BBS conference file numbered 34. Neither expansion is proved by
    filename shape alone.

  correct_boundary: >
    The filename and textual content are carrier-identity leads. The surviving state
    is securely Branton-edited. Whether it is Cosmic Conflict chapter 34, a standalone
    export, a shared working file or a later excerpt requires explicit carrier context.

  safe_labels:
    - COSMIC_CONFLICT_CHAPTER_34_CANDIDATE
    - BBS_SEQUENCE_FILE_NOT_ESTABLISHED
    - CARRIER_IDENTITY_OPEN
    - BRANTON_EDITED_TEXT_WITNESS

  unsafe_labels:
    - COSCON34_CONFIRMED_COSMIC_CONFLICT_CHAPTER_34
    - COSCON34_CONFIRMED_BBS_FILE_NUMBER_34
    - COSCON34_FILENAME_PROVES_DATE_OR_CHANNEL

  promotion_test:
    - title or running header naming Cosmic Conflict
    - contents page mapping chapter 34 to the exact text
    - neighboring chapter files with verified sequence
    - original directory listing or archive catalogue
    - file header/footer or publisher record

  generated_session: SESSION_056
  last_reviewed: 2026-07-16
```
