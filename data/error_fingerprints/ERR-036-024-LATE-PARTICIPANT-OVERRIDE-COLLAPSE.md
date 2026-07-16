# ERR-036-024 — Late Participant Account Override Collapse

```yaml
ERROR_FINGERPRINT:
  id: ERR-036-024
  name: LATE_PARTICIPANT_ACCOUNT_OVERRIDE_COLLAPSE
  related_question: RQ-036
  status: SUPPORTED

  collapse: >
    One later first-person participant account is treated as an authoritative override
    of all earlier participant accounts, rather than as another interested reconstruction.

  session_048_conflict:
    - Hinkle 2010/2013: Castello was real; original transcript held; death in April 1991; later impersonation
    - Lear 2008: treats Castello and recovery expeditions as real; describes his own editing role
    - LeVesque 2015: TEC was a creation and the interview was creative writing

  correct_boundary: >
    These accounts are evidence about what named participants said at specific dates.
    They conflict and must be tested against original files, identity records, version
    histories and material artifacts. The LeVesque confession remains highly important
    self-attestation but is not a universal override.

  safe_labels:
    - CONFLICTING_PARTICIPANT_ACCOUNTS
    - LATE_SELF_ATTESTATION
    - COLLABORATIVE_OR_DECEPTIVE_NETWORK_POSSIBLE
    - CASTELLO_AUTHENTICATION_NOT_ESTABLISHED

  unsafe_labels:
    - LEVESQUE_CONFESSION_SETTLES_ALL_HISTORY
    - LEAR_ACCOUNT_AUTHENTICATES_CASTELLO
    - HINKLE_ACCOUNT_AUTHENTICATES_CASTELLO
    - ALL_PARTICIPANTS_INDEPENDENTLY_CONFIRM_ONE_REAL_WITNESS

  promotion_test:
    - independent identity records
    - original correspondence
    - dated working files
    - recipient acknowledgements
    - authenticated physical artifacts
    - contemporaneous version captures

  generated_session: SESSION_048
  last_reviewed: 2026-07-16
```
