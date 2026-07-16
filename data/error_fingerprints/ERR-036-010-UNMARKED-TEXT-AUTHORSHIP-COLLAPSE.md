# ERR-036-010 — Unmarked Text → Authorship Collapse

```yaml
ERROR_FINGERPRINT:
  id: ERR-036-010
  name: UNMARKED_TEXT_AUTHORSHIP_COLLAPSE
  related_question: RQ-036
  status: STRONGLY_SUPPORTED

  collapse: >
    Because some parenthetical notes are explicitly signed `– Branton`, every
    unsigned sentence in the surviving Q&A is assigned to an authenticated
    Thomas Castello source layer or presumed to predate Branton's compilation.

  correct_boundary: >
    The signature identifies explicitly marked Branton notes. Its absence only
    permits assignment to the unmarked Q&A answer layer in that version. It does
    not prove who authored the answer, when it was written, whether it was edited
    before compilation, or whether the named speaker existed as a historical person.

  session_045_escalation: >
    Quoted statements attributed to Tal LeVesque indicate that Thomas Edwin
    Castello was a created persona, that Cherry Hinkle / Ann or Anne West may have
    answered questions in character, and that LeVesque mixed her material with
    corrections and his own research. Exact original correspondence or printed
    pages remain required before direct-confession promotion.

  possible_hidden_layers:
    - CHERRY_HINKLE_ANSWER_OR_STORY_LAYER
    - TAL_LEVESQUE_CORRECTION_AND_ADDITION_LAYER
    - DOCUMENT_PERSONA_PERFORMANCE
    - BRANTON_COMPILER_AND_SIGNED_NOTE_LAYER
    - POSSIBLE_UNSIGNED_BRANTON_EDITING
    - LATER_WEB_NORMALIZATION
    - UNKNOWN_SOURCE

  safe_labels:
    - Q_AND_A_ANSWER_VOICE
    - QUESTIONER_VOICE_UNKNOWN
    - EXPLICIT_BRANTON_NOTE
    - COMPILER_SEQUENCE
    - UNSIGNED_PARENTHETICAL_UNKNOWN
    - DOCUMENT_PERSONA
    - LATER_WEB_NORMALIZATION

  unsafe_labels_without_more_evidence:
    - AUTHENTIC_CASTELLO_TESTIMONY
    - PRE_BRANTON_TEXT
    - TAL_WORDING
    - HINKLE_WORDING
    - BRANTON_WORDING
    - UNEDITED_INTERVIEW_TRANSCRIPT
    - CONFIRMED_WHISTLEBLOWER_ACCOUNT

  promotion_test:
    - earlier pre-compilation witness
    - original typed manuscript
    - recording or raw transcript
    - complete LeVesque correspondence with headers
    - Hinkle or Branton correspondence
    - version diff showing additions
    - exact Gorightly edition and pages

  generated_session: SESSION_044
  updated_session: SESSION_045
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
proven historical speaker
        ≠
proven early date
```
