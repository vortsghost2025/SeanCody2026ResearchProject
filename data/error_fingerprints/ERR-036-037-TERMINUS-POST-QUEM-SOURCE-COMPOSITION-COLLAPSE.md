# ERR-036-037 — Terminus Post Quem → Source Composition Collapse

```yaml
ERROR_FINGERPRINT:
  id: ERR-036-037
  name: TERMINUS_POST_QUEM_SOURCE_COMPOSITION_COLLAPSE
  related_question: RQ-036
  status: SUPPORTED

  collapse: >
    A dated reference inside a composite or editorialized carrier is correctly used
    to show that the carrier state could not have been assembled before that date,
    but is then incorrectly converted into proof that an embedded source text already
    existed by that same date.

  session_056_instance: >
    COSCON34 cites a March 18, 1994 Plain Dealer article. This establishes a terminus
    post quem for the surviving editorialized COSCON34 state. It does not establish
    a terminus ante quem of March 18, 1994 for the mature Q&A source embedded inside it.

  correct_logic: |
    dated reference = 1994-03-18
            ↓
    composite carrier assembled no earlier than 1994-03-18

    composite carrier contains Q&A
            ≠
    Q&A necessarily existed before 1994-03-18

  safe_labels:
    - COSCON34_STATE_TPQ_1994_03_18
    - UNDERLYING_QA_DATE_UNKNOWN
    - EDITORIALIZED_CARRIER_POSTDATES_INTERNAL_REFERENCE

  unsafe_labels:
    - MATURE_QA_EXISTED_BY_MARCH_1994
    - Q_AND_A_COMPOSITION_PRE_MARCH_1994_CONFIRMED
    - 1990_TO_MARCH_1994_COMPOSITION_WINDOW_PROVED

  promotion_test:
    - a carrier dated independently to March 18, 1994 or earlier that already contains the Q&A
    - a manuscript, BBS header, letter or publication predating the cited editorial insertion
    - layer-specific evidence proving the Q&A was copied from an earlier dated object

  generated_session: SESSION_056
  last_reviewed: 2026-07-16
```
