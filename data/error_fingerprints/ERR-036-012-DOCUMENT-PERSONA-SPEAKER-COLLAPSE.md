# ERR-036-012 — Document Persona → Historical Speaker Collapse

```yaml
ERROR_FINGERPRINT:
  id: ERR-036-012
  name: DOCUMENT_PERSONA_SPEAKER_COLLAPSE
  related_question: RQ-036
  status: STRONGLY_SUPPORTED_PENDING_EXACT_CONFESSION_ARTIFACT

  collapse: >
    Because a Q&A answer is presented under the name Thomas Edwin Castello,
    the answer voice is treated as authenticated testimony from a real former
    security technician.

  evidence_change: >
    Session 045 supplied direct-quote leads attributed to Tal LeVesque stating
    that TEC was a creation and that another participant answered questions as
    if she were TEC. The exact original email, recording or printed page remains
    to be acquired.

  correct_boundary: >
    Thomas Castello is currently a document persona and attributed speaker.
    The historical person, employment, eyewitness status and authorship of the
    answers are not independently established.

  safe_labels:
    - DOCUMENT_PERSONA
    - ATTRIBUTED_SPEAKER
    - Q_AND_A_ANSWER_VOICE
    - HISTORICAL_PERSON_NOT_ESTABLISHED

  unsafe_labels:
    - CONFIRMED_WHISTLEBLOWER
    - AUTHENTIC_SECURITY_TECHNICIAN
    - EYEWITNESS_TESTIMONY
    - VERIFIED_INTERVIEWEE

  promotion_test:
    - original confession email or recording
    - complete correspondence context and headers
    - independent identity and employment records
    - original interview medium
    - participant accounts and version comparison

  generated_session: SESSION_045
  last_reviewed: 2026-07-16
```

## Guardrail

```text
voice presented as Castello
        ≠
real person named Castello
        ≠
authenticated witness
        ≠
truth of narrative claims
```
