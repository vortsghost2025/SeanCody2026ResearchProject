# ERR-036-025 — Claimed Material Artifact → Produced Evidence Collapse

```yaml
ERROR_FINGERPRINT:
  id: ERR-036-025
  name: CLAIMED_MATERIAL_ARTIFACT_PRODUCTION_COLLAPSE
  related_question: RQ-036
  status: SUPPORTED

  collapse: >
    Repeated claims that a letter, box, recording, packet, photograph, treaty,
    device or identity document exists are summarized as physical corroboration
    even though no authenticated object has been produced in the acquired record.

  session_048_claimed_objects:
    - Castello hidden box or boxes
    - 1987 or 1988 Castello-attributed letters
    - Japanese television master recordings
    - original vat sketches with custody
    - Reagan-signed treaty
    - flash gun
    - LeVesque source packets
    - Hamilton identity documents

  current_result:
    authenticated_material_objects_recovered: 0
    participant_possession_claims: MULTIPLE
    recovery_attempts_reported: MULTIPLE
    evidentiary_class: CLAIMS_EXCEED_PRODUCTIONS

  correct_boundary: >
    Possession and recovery claims are historical data about the narrative and its
    participants. They are not physical corroboration until an object is inspected,
    dated, authenticated and placed in a custody chain.

  safe_labels:
    - PARTICIPANT_POSSESSION_CLAIM
    - DOCUMENTED_RECOVERY_ATTEMPT
    - OBJECT_NOT_PRODUCED
    - MATERIAL_CORROBORATION_ZERO_IN_ACQUIRED_SET

  unsafe_labels:
    - PHYSICAL_EVIDENCE_CONFIRMED
    - HIDDEN_BOX_VERIFIED
    - LETTER_VERIFIED_FROM_DATE_CLAIM
    - PACKET_OPERATION_PHYSICALLY_CONFIRMED

  promotion_test:
    - object image or raw file
    - material or file metadata
    - date basis
    - chain of custody
    - independent holder confirmation
    - forensic/version comparison

  generated_session: SESSION_048
  last_reviewed: 2026-07-16
```
