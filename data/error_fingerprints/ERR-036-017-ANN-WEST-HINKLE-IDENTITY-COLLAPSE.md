# ERR-036-017 — Ann West / Cherry Hinkle Identity Collapse

```yaml
ERROR_FINGERPRINT:
  id: ERR-036-017
  name: ANN_WEST_HINKLE_IDENTITY_COLLAPSE
  related_question: RQ-036
  status: SUPPORTED_AS_GUARDRAIL

  collapse: >
    Ann or Anne West and Cherry Hinkle are treated as a confirmed single
    historical identity because LeVesque used the names together in a later
    confession account.

  current_evidence: >
    The reproduced November 2015 email identifies Ann West as Cherry Hinkle.
    Independent identity documentation or direct Hinkle confirmation has not
    been acquired. Earlier drawings, reports and network roles may therefore
    be misassigned when the names are silently merged.

  correct_boundary: >
    Preserve both name forms, the source making the identification, and the
    possibility of alias, misidentification or conflation until independently
    resolved.

  safe_labels:
    - ANN_WEST
    - ANNE_WEST
    - CHERRY_HINKLE
    - LEVESQUE_ASSERTED_ALIAS
    - IDENTITY_NOT_INDEPENDENTLY_RESOLVED

  unsafe_labels_without_more_evidence:
    - CONFIRMED_SAME_PERSON
    - ALL_ANN_WEST_ARTIFACTS_AUTHORED_BY_HINKLE
    - ALL_HINKLE_STATEMENTS_APPLY_TO_ANN_WEST

  promotion_test:
    - direct Hinkle statement
    - contemporaneous correspondence using both names
    - matching handwriting or custody
    - legal or archival identity record where appropriate
    - participant corroboration independent of LeVesque

  generated_session: SESSION_046
  last_reviewed: 2026-07-16
```
