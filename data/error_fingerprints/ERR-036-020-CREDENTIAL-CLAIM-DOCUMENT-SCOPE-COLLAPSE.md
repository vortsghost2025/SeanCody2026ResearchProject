# ERR-036-020 — Credential Claim / Document Scope Collapse

```yaml
ERROR_FINGERPRINT:
  id: ERR-036-020
  name: CREDENTIAL_CLAIM_DOCUMENT_SCOPE_COLLAPSE
  related_question: RQ-036
  status: SUPPORTED

  collapse: >
    A reported death-certificate occupation field is treated as a complete lifetime
    employment history that conclusively disproves every earlier LeVesque credential
    claim, or conversely LeVesque's unsupported classified-work claims are accepted
    because they appear inside a confession-of-fabrication narrative.

  current_evidence: >
    A 2026 Gorightly podcast reportedly says a death certificate lists private
    security in the hospitality industry. The death certificate itself, exact fields,
    jurisdictional form and complete occupational wording have not been acquired.

  correct_boundary: >
    The reported occupation weakens and fails to corroborate LeVesque's expansive
    classified-work claims. It does not by itself establish his entire employment
    history. The credential claims remain unverified and must be separated from the
    independently important persona-creation self-attestation.

  safe_labels:
    - SECONDARY_REPORT_OF_PRIMARY_DOCUMENT
    - CLASSIFIED_CREDENTIALS_UNCORROBORATED
    - REPORTED_RECENT_OCCUPATION_HOSPITALITY_SECURITY
    - COMPLETE_CAREER_HISTORY_UNKNOWN

  unsafe_labels:
    - DEATH_CERTIFICATE_PROVES_NO_CLASSIFIED_WORK_EVER
    - LEVESQUE_CLASSIFIED_CREDENTIALS_CONFIRMED
    - EVERY_CONFESSION_DETAIL_FALSE
    - EVERY_CONFESSION_DETAIL_TRUE

  promotion_test:
    - death certificate image or archival record
    - exact occupation and industry fields
    - jurisdictional field definitions
    - independent employment records
    - military or contractor records
    - full podcast transcript and provenance

  generated_session: SESSION_047
  last_reviewed: 2026-07-16
```
