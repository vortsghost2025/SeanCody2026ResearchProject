# ERR-036-008 — Soft Date → Hard Date Collapse

```yaml
ERROR_FINGERPRINT:
  id: ERR-036-008
  name: SOFT_DATE_HARD_DATE_COLLAPSE
  related_question: RQ-036
  status: SUPPORTED_BY_SESSION_044_VARIANT_CONFLICT

  collapse: >
    A retailer listing, re-typeset PDF header, internal retrospective note,
    upload date or repeated secondary metadata is converted into a securely
    authenticated first-publication date.

  current_cases:
    claimed_1991_dulce_book:
      status: UNVERIFIED_DATE_ASSERTION
      missing:
        - original file header or BBS timestamp
        - physical copyright page
        - contemporaneous catalogue or advertisement
        - archive custody

    attested_1996_dulce_book:
      status: SOFT_BIBLIOGRAPHIC_CARRIER_LEAD
      missing:
        - physical first-edition title and copyright pages
        - printer or distributor evidence
        - edition identity
        - page-level comparison

    archive_2016_upload:
      status: UPLOAD_DATE_ONLY
      rule: cannot date composition or first circulation

  safe_vocabulary:
    - REPORTED_DATE
    - SOFT_BIBLIOGRAPHIC_DATE
    - INTERNAL_RETROSPECTIVE_DATE
    - UPLOAD_DATE
    - PHYSICAL_ITEM_DATE
    - SECURE_CARRIER_DATE

  generated_session: SESSION_044
  last_reviewed: 2026-07-16
```

## Guardrail

```text
repeated metadata
        ≠
independent confirmation
        ≠
physical first-edition verification
```
