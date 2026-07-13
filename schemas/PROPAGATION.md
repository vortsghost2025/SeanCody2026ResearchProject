# Canonical Schema: Propagation Object

**Version:** 1.0  
**Status:** Frozen with Repository Architecture v2.0  
**Purpose:** Represent how a claim, motif, publication, or system moves through geography, language, culture, institutions, and media—and what changes during each movement.

## Core rule

A location answers **where** something appears. A propagation record answers **how it moved, through whom, by which medium, and how it changed**.

Movement must not be assumed merely because two cultures share a motif. A propagation path requires evidence for the transition itself.

## Object schema

```yaml
PROPAGATION:
  id: PROP-001
  canonical_name: "Underground Civilization System — Cultural and Geographic Movement"

  scope:
    object_type: SYSTEM          # SYSTEM | MOTIF | CLAIM | PUBLICATION
    object_id: SYS-001

  nodes:
    - id: PROP-001-N001
      location_ids:
        - LOC-TBD
      culture: TBD
      religion_or_tradition: TBD
      language: TBD
      date_range:
        start: UNKNOWN
        end: UNKNOWN
        precision: UNKNOWN

      medium:
        type: ORAL              # ORAL | MANUSCRIPT | PRINT | RADIO | FILM | TELEVISION | INTERNET | INSTITUTIONAL | OTHER
        publication_or_channel: TBD
        gatekeeper_entities: []

      attested_elements: []
      absent_elements: []
      uncertain_elements: []

      source_support: []
      confidence: UNKNOWN
      research_status: OPEN

  transitions:
    - id: PROP-001-T001
      from_node: PROP-001-N001
      to_node: PROP-001-N002

      transition_type: UNKNOWN  # DOCUMENTED_TRANSMISSION | TRANSLATION | ADAPTATION | MIGRATION | EDITORIAL_SYNTHESIS | MASS_MEDIA_DIFFUSION | INTERNET_DIFFUSION | INDEPENDENT_PARALLEL | UNKNOWN
      transmission_edge_id: EDGE-TBD

      carrier_entities: []
      carrier_publications: []
      institutions: []
      languages_crossed: []

      transformation:
        elements_retained: []
        elements_added: []
        elements_removed: []
        elements_reframed: []
        proposed_processes: []   # e.g. SECULARIZATION, TECHNOLOGIZATION, EXTRATERRESTRIALIZATION

      evidence:
        direct_sources: []
        secondary_sources: []
        negative_records: []
        competing_explanations: []

      edge_type: UNKNOWN
      evidence_class: C
      confidence: UNKNOWN
      notes: "Similarity between nodes does not establish this transition."

  unresolved_paths: []
  generated_session: SESSION_022
  last_reviewed: 2026-07-13
```

## Validation rules

1. Each transition needs evidence about the movement, not only evidence that both endpoints exist.
2. `INDEPENDENT_PARALLEL` is valid and should be preferred when similarity predates demonstrated contact.
3. Geographic movement, language translation, and conceptual transformation may occur at different times; record them separately.
4. Internet diffusion may remove geographic constraints but still has platforms, communities, reposting chains, and dates.
5. Gatekeepers and institutions are part of propagation: editors, publishers, religious bodies, governments, clubs, archives, broadcasters, and platforms.
6. Record both elements added and elements lost. Propagation is not presumed to preserve a story unchanged.
7. When the path is speculative, use `UNKNOWN` or `SPECULATIVE_SIMILARITY`; do not manufacture a continuous lineage.
8. Every proposed transformation label is an analytical interpretation and must carry evidence and confidence.
