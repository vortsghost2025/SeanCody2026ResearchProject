# ERR-036-019 — Primary Distributor Account Collapse

```yaml
ERROR_FINGERPRINT:
  id: ERR-036-019
  name: PRIMARY_DISTRIBUTOR_ACCOUNT_COLLAPSE
  related_question: RQ-036
  status: SUPPORTED

  collapse: >
    LeVesque's 2015 self-attestation to sending approximately one hundred packets
    is treated as proof that he alone originated and distributed the Dulce material,
    while earlier Hinkle participant and interview accounts describing broad
    distribution since 1987 are ignored.

  correct_boundary: >
    LeVesque and Hinkle each have distribution claims. The acquired evidence does
    not establish exclusive primary agency, prove that they describe the same
    mailing operation, or identify one sole originator.

  competing_accounts:
    - HINKLE_PROJECT_AVALON_2010
    - GORIGHTLY_HINKLE_INTERVIEW_2012
    - LEVESQUE_GORIGHTLY_EMAIL_2015

  safe_labels:
    - LEVESQUE_SELF_ATTESTED_PACKET_STRATEGY
    - HINKLE_PARTICIPANT_DISTRIBUTION_ACCOUNT
    - PARALLEL_OR_SHARED_DISTRIBUTION_POSSIBLE
    - EXCLUSIVE_PRIMARY_DISTRIBUTOR_UNRESOLVED

  unsafe_labels:
    - LEVESQUE_CONFIRMED_SOLE_DISTRIBUTOR
    - HINKLE_CONFIRMED_SOLE_DISTRIBUTOR
    - SAME_PACKET_OPERATION_CONFIRMED
    - ONE_PERSON_ORIGIN_CONFIRMED

  promotion_test:
    - original mailing records
    - recipient acknowledgements
    - packet exemplars
    - dated Hinkle and LeVesque correspondence
    - overlapping recipient lists
    - diagnostic shared packet state

  generated_session: SESSION_047
  last_reviewed: 2026-07-16
```
