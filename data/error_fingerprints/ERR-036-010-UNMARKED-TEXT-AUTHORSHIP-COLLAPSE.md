# ERR-036-010 — Unmarked Text → Authorship Collapse

```yaml
ERROR_FINGERPRINT:
  id: ERR-036-010
  name: UNMARKED_TEXT_AUTHORSHIP_COLLAPSE
  related_question: RQ-036
  status: STRONGLY_SUPPORTED_AND_PROVENANCE_ESCALATED

  collapse: >
    Because some parenthetical notes are explicitly signed `– Branton`, every
    unsigned sentence in the surviving Q&A is assigned to authenticated Thomas
    Castello testimony or presumed to predate Branton's compilation.

  correct_boundary: >
    A signature identifies explicitly marked Branton notes. Its absence permits
    assignment only to the unmarked Q&A answer layer in that version. It does not
    prove who authored the answer, when it was written, whether it was edited, or
    whether the named speaker existed as a historical witness.

  session_046_evidence: >
    A November 2015 LeVesque email reproduced by verified secondary sources says
    TEC was a creation, the interview was creative writing, questions were sent
    to Cherry Hinkle / Ann West twice, and she answered as if she were TEC.
    LeVesque also self-attests to correcting, adding and mixing source material.

  source_boundary: >
    The reproduced email is DIRECT_QUOTE_IN_VERIFIED_SECONDARY. The original email
    facsimile and headers are not publicly acquired. The source strongly escalates
    the hidden-layer problem but does not allocate every Q&A sentence to one author.

  possible_hidden_layers:
    - CHERRY_HINKLE_OR_ANN_WEST_PERSONA_ANSWER_LAYER
    - TAL_LEVESQUE_QUESTION_ROUTING_LAYER
    - TAL_LEVESQUE_CORRECTION_ADDITION_AND_ASSEMBLY_LAYER
    - THOMAS_CASTELLO_DOCUMENT_PERSONA
    - BRANTON_COMPILER_AND_SIGNED_NOTE_LAYER
    - POSSIBLE_UNSIGNED_BRANTON_EDITING
    - LATER_WEB_NORMALIZATION
    - UNKNOWN_EARLIER_SOURCE

  safe_labels:
    - Q_AND_A_ANSWER_VOICE
    - QUESTIONER_VOICE_UNKNOWN
    - EXPLICIT_BRANTON_NOTE
    - COMPILER_SEQUENCE
    - UNSIGNED_PARENTHETICAL_UNKNOWN
    - DOCUMENT_PERSONA
    - LEVESQUE_SELF_ATTESTED_PRODUCTION_MECHANISM
    - LATER_WEB_NORMALIZATION

  unsafe_labels_without_more_evidence:
    - AUTHENTIC_CASTELLO_TESTIMONY
    - PRE_BRANTON_TEXT
    - EVERY_ANSWER_WRITTEN_BY_HINKLE
    - EVERY_ANSWER_WRITTEN_BY_LEVESQUE
    - EVERY_UNSIGNED_EDIT_BY_BRANTON
    - UNEDITED_INTERVIEW_TRANSCRIPT
    - CONFIRMED_WHISTLEBLOWER_ACCOUNT

  promotion_test:
    - original question sheets
    - Hinkle answer sheets or correspondence
    - original LeVesque email with headers
    - working manuscript or BBS file
    - Branton correspondence
    - sentence-level version diff
    - exact Gorightly pages and provenance statement

  generated_session: SESSION_044
  updated_session: SESSION_046
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
proven Hinkle or LeVesque authorship for that sentence
        ≠
proven early date
```
