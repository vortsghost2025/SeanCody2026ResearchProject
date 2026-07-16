# ERR-036-007 — Q&A Interviewer Inference Collapse

```yaml
ERROR_FINGERPRINT:
  id: ERR-036-007
  name: Q_AND_A_INTERVIEWER_INFERENCE_COLLAPSE
  related_question: RQ-036
  status: SUPPORTED_BY_DOCUMENT_SILENCE

  collapse: >
    A Q&A appears inside a Branton compilation, so the unidentified questioner
    is reported as Branton without preserving that this is an external inference.

  unsafe_form: "Branton asked Castello..."

  safe_form: >
    The surviving Q&A contains an unidentified questioner. Branton compiled
    and annotated the surviving chapter; some analysts infer that he was also
    the interviewer, but the text does not internally establish that identity.

  promotion_test:
    - signed introduction naming the interviewer
    - correspondence discussing the interview
    - original recording or transcript header
    - Branton statement claiming the questions
    - pre-compilation copy with attribution

  generated_session: SESSION_044
  last_reviewed: 2026-07-16
```

## Guardrail

```text
compiled by Branton
        ≠
questions written by Branton
        ≠
interview conducted by Branton
```
