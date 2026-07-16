# ERR-036-015 — Confession Without Countertestimony Collapse

```yaml
ERROR_FINGERPRINT:
  id: ERR-036-015
  name: CONFESSION_WITHOUT_COUNTERTESTIMONY_COLLAPSE
  related_question: RQ-036
  status: SUPPORTED

  collapse: >
    A late participant confession is accepted as a complete and uncontested
    reconstruction of authorship, while conflicting participant accounts,
    hostile contemporary claims and unrecovered records are omitted.

  current_case: >
    Tal LeVesque's November 2015 email strongly self-attests that TEC was a
    creation and describes Hinkle answering as TEC. Hinkle reportedly maintained
    a factual Castello account; Hamilton reportedly claimed biographical records;
    Tilton reportedly called the story fabricated in a 1987 manuscript.

  correct_boundary: >
    Preserve the confession as high-value self-attestation and distinguish it
    from independently corroborated physical evidence. Preserve participant
    disagreements and their source classes separately.

  safe_labels:
    - DIRECT_QUOTE_IN_VERIFIED_SECONDARY
    - SELF_ATTESTED_PERSONA_CREATION
    - SELF_ATTESTED_HINKLE_ROLE_CONTESTED
    - CONFLICTING_PARTICIPANT_ACCOUNTS

  unsafe_labels_without_more_evidence:
    - COMPLETE_UNCONTESTED_CONFESSION
    - EVERY_AUTHORSHIP_LAYER_RESOLVED
    - ALL_PARTICIPANTS_AGREE
    - PHYSICAL_HOAX_OPERATION_PROVEN

  promotion_test:
    - original email facsimile and headers
    - Hinkle direct response to exact claims
    - Hamilton records or estate inventory
    - Tilton manuscript
    - working Q&A papers or correspondence

  generated_session: SESSION_046
  last_reviewed: 2026-07-16
```
