# ERR-036-021 — Shared Publisher → Independence Collapse

```yaml
ERROR_FINGERPRINT:
  id: ERR-036-021
  name: SHARED_PUBLISHER_INDEPENDENCE_COLLAPSE
  related_question: RQ-036
  status: SUPPORTED

  collapse: >
    Books attributed to different Dulce actors are counted as independent source
    confirmation even when they share the same publisher, distributor, editor,
    catalogue network or reprint infrastructure.

  current_lead: >
    Commercial editions associated with Christa Tilton, Branton and William Hamilton
    are reported through Inner Light / Global Communications / Timothy Green Beckley
    publishing infrastructure. Exact editions and text states require item inspection.

  correct_boundary: >
    Shared publishing infrastructure establishes a distribution and editorial contact
    environment. It reduces independence but does not prove direct copying, coordinated
    seeding or identical authorship.

  safe_labels:
    - SHARED_PUBLISHER_INFRASTRUCTURE
    - POTENTIAL_EDITORIAL_CONTACT
    - INDEPENDENCE_REDUCED
    - TEXT_DEPENDENCY_UNRESOLVED

  unsafe_labels:
    - THREE_INDEPENDENT_PUBLISHED_CONFIRMATIONS
    - COORDINATED_HOAX_PROVED_BY_ISBN
    - IDENTICAL_SOURCE_PROVED
    - PUBLISHER_NEUTRALITY_ASSUMED

  promotion_test:
    - physical title and copyright pages
    - edition dates
    - publisher catalogues
    - editor and typesetter records
    - manuscript submission correspondence
    - sentence-level copying fingerprints
    - shared errors or source lists

  generated_session: SESSION_047
  last_reviewed: 2026-07-16
```
