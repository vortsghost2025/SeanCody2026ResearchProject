# ERR-036-022 — Participant Possession Claim → Artifact Collapse

```yaml
ERROR_FINGERPRINT:
  id: ERR-036-022
  name: PARTICIPANT_POSSESSION_ARTIFACT_COLLAPSE
  related_question: RQ-036
  status: SUPPORTED

  collapse: >
    A participant's statement that they possess an original transcript, dated letter,
    recording, photograph or other artifact is treated as equivalent to acquiring,
    authenticating and dating that artifact.

  session_047_examples:
    - Hinkle claimed an original Q&A transcript without later writer comments
    - Hinkle claimed a 1987 Castello-attributed letter
    - Hinkle claimed original Japanese television VCR recordings
    - Gorightly reportedly holds a LeVesque death certificate

  correct_boundary: >
    The statement is primary evidence that the participant made a possession claim.
    It is not primary evidence of the claimed object's content, age, custody or
    authenticity until the object itself is inspected.

  safe_labels:
    - PARTICIPANT_POSSESSION_CLAIM
    - HIGHEST_VALUE_UNRECOVERED_OBJECT
    - OBJECT_AUTHENTICITY_UNKNOWN
    - DATE_AND_CUSTODY_UNRESOLVED

  unsafe_labels:
    - PRE_BRANTON_TRANSCRIPT_CONFIRMED
    - 1987_CASTELLO_LETTER_CONFIRMED
    - JAPANESE_TV_MASTER_CONFIRMED
    - DEATH_CERTIFICATE_CONTENT_CONFIRMED_IN_FULL

  promotion_test:
    - complete image, raw file or recording
    - artifact metadata
    - chain of custody
    - exact date basis
    - comparison against later versions
    - independent archive or holder confirmation

  generated_session: SESSION_047
  last_reviewed: 2026-07-16
```
