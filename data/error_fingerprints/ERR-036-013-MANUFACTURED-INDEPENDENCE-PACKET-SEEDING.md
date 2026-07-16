# ERR-036-013 — Packet Seeding → Manufactured Independence

```yaml
ERROR_FINGERPRINT:
  id: ERR-036-013
  name: MANUFACTURED_INDEPENDENCE_PACKET_SEEDING
  related_question: RQ-036
  related_method: RQ-034
  status: DIRECT_QUOTE_LEAD_PENDING_EXACT_SOURCE

  mechanism: >
    One compiler distributes substantially the same assembled packet to many
    authors, lecturers or researchers. Their later talks, articles, books and
    newsletters are then miscounted as independent convergence.

  session_045_lead: >
    A quotation attributed to Tal LeVesque states that he prepared roughly one
    hundred large packets with underground-base, genetic-research and related
    material and sent them to authors and lecturers so later appearances would
    look as though they came from more than one source.

  evidentiary_boundary: >
    The quote is load-bearing but the exact original email, recording, book page,
    packet, mailing list or recipient acknowledgement was not supplied. Preserve
    as a candidate until item-level authentication.

  predicted_signature:
    - many downstream sources with similar claim bundles
    - shared rare wording or errors
    - different public speakers with common hidden packet source
    - recipients citing one another after receiving the same packet
    - appearance of convergence without observational independence

  required_independence_fields:
    - recipient_identity
    - packet_receipt_date
    - packet_contents
    - later_publication_date
    - copied_wording
    - direct_observation_claim
    - source_disclosure

  promotion_test:
    - original LeVesque statement with provenance
    - surviving packet or cover letter
    - recipient confirmation
    - mailing list or envelope/postmark
    - source-text comparison across recipients

  generated_session: SESSION_045
  last_reviewed: 2026-07-16
```

## Guardrail

```text
many authors repeat claim
        ≠
many independent sources

one packet sent to many recipients
        =
shared hidden dependency
```
