# ERR-036-030 — Q/A Label Transposition in a Mirror

```yaml
ERROR_FINGERPRINT:
  id: ERR-036-030
  name: QA_LABEL_TRANSPOSITION
  related_question: RQ-036
  status: SUPPORTED_MINOR_VARIANT

  collapse: >
    A later mirror's isolated `Q—` or `A—` label is treated as proof that the
    underlying interview structure differed radically, without checking the
    surrounding question-answer sequence and earlier carriers.

  session_050_instance: >
    One later mirror labels `They work for, and are controlled by the Draco` as
    `Q—`; other mirrors label it `A—`. The surrounding prompt makes `A—` the
    more coherent state.

  current_result:
    dominant_label: A
    minority_label: Q
    likely_cause: TRANSCRIPTION_OR_COPYING_ERROR
    stemmatic_value: LOW

  promotion_test:
    - earlier raw carrier with same label
    - complete surrounding sequence
    - copied-error descendants
    - exact capture chronology

  generated_session: SESSION_050
  last_reviewed: 2026-07-16
```
