# ERR-036-010 — Unmarked Text → Authorship Collapse

```yaml
ERROR_FINGERPRINT:
  id: ERR-036-010
  name: UNMARKED_TEXT_AUTHORSHIP_COLLAPSE
  related_question: RQ-036
  status: SUPPORTED

  collapse: >
    Because some parenthetical notes are explicitly signed `– Branton`, every
    unsigned sentence in the surviving Q&A is assigned to an authenticated
    Thomas Castello source layer or presumed to predate Branton's compilation.

  correct_boundary: >
    The signature identifies explicitly marked Branton notes. Its absence only
    permits assignment to the unmarked Q&A answer layer in that version. It does
    not prove who authored the answer, when it was written, or whether it was
    edited before compilation.

  safe_labels:
    - Q_AND_A_ANSWER_VOICE
    - QUESTIONER_VOICE_UNKNOWN
    - EXPLICIT_BRANTON_NOTE
    - COMPILER_SEQUENCE
    - UNSIGNED_PARENTHEICAL_UNKNOWN
    - LATER_WEB_NORMALIZATION

  unsafe_labels_without_more_evidence:
    - AUTHENTIC_CASTELLO_TESTIMONY
    - PRE_BRANTON_TEXT
    - TAL_WORDING
    - BRANTON_WORDING
    - UNEDITED_INTERVIEW_TRANSCRIPT

  promotion_test:
    - earlier pre-compilation witness
    - original typed manuscript
    - recording or raw transcript
    - author correspondence
    - version diff showing additions

  generated_session: SESSION_044
  last_reviewed: 2026-07-16
```

## Guardrail

```text
not signed `– Branton`
        ≠
proven non-Branton authorship
        ≠
proven Castello authorship
        ≠
proven early date
```
