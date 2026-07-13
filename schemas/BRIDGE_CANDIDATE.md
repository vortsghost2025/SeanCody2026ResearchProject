# Canonical Schema: Bridge Candidate

**Purpose:** Record a suspected connection between different systems, domains, motifs, institutions, media, or timelines before a transmission edge is proven.

A bridge candidate is **not evidence of influence**. It is a testable hypothesis with explicit supporting clues, alternative explanations, disconfirming evidence, and a promotion gate.

```yaml
BRIDGE_CANDIDATE:
  id: BRIDGE-001
  title: "Antarctic blank-space geography → hidden-base narrative"
  status: OPEN                 # OPEN | TESTING | SUPPORTED | REJECTED | SPLIT | MERGED

  endpoints:
    - object_type: SYSTEM      # SYSTEM | MOTIF | ENTITY | PUBLICATION | CLAIM | CHRONOLOGY | PROPAGATION
      object_id: SYS-TBD
      role: SOURCE_SIDE
    - object_type: SYSTEM
      object_id: SYS-TBD
      role: DESTINATION_SIDE

  suspected_bridge_type:
    - SHARED_INFRASTRUCTURE    # publisher, archive, military unit, society, platform, conference, distributor
    - EXPOSURE_PATH            # documented opportunity for one side to encounter the other
    - LEXICAL_MIGRATION         # distinctive wording, phrase, label, mistranslation, spelling, or naming chain
    - SHARED_ERROR              # copied mistake, misprint, misplaced label, distorted image, wrong date
    - ICONOGRAPHIC_MIGRATION    # recurring image, diagram, map, cover, photograph, costume, or visual template
    - MATERIAL_REUSE            # same plate, printing block, photograph, stock image, diagram, file, or template
    - EDITORIAL_SYNTHESIS       # editor, compiler, anthologist, broadcaster, or influencer combines streams
    - INSTITUTIONAL_LAUNDERING  # speculative material gains authority through institutional framing
    - TECHNOLOGIZATION          # supernatural or mythic element reframed as machinery/science
    - EXTRATERRESTRIALIZATION   # terrestrial, spiritual, or subterranean being reframed as alien
    - INTERDIMENSIONALIZATION   # physical place/being reframed as dimensional or portal-based
    - SECULARIZATION            # religious/occult language reframed as scientific or historical
    - RETROACTIVE_FUSION        # later author combines previously separate traditions
    - INDEPENDENT_PARALLEL      # similarity without demonstrated contact
    - UNKNOWN

  initial_clues:
    repeated_phrases: []
    repeated_names_or_aliases: []
    shared_people: []
    shared_publications: []
    shared_publishers_or_institutions: []
    shared_locations: []
    shared_images_or_diagrams: []
    shared_errors: []
    chronological_overlap: []
    exposure_opportunities: []

  hidden_carrier_candidates:
    people: []
    publications: []
    institutions: []
    archives_or_collections: []
    clubs_societies_conferences: []
    radio_film_television: []
    postal_catalog_distribution: []
    internet_platforms: []
    military_or_intelligence_channels: []
    translation_or_reprint_channels: []

  transformation_hypothesis:
    elements_retained: []
    elements_added: []
    elements_removed: []
    elements_reframed: []

  competing_explanations:
    - INDEPENDENT_INVENTION
    - COMMON_OLDER_SOURCE
    - GENRE_CONVENTION
    - COINCIDENCE
    - RETROSPECTIVE_PATTERN_MATCHING
    - UNSOURCED_MODEL_INFERENCE

  evidence_for: []
  evidence_against: []
  negative_searches: []
  contradictions: []

  tests_required:
    - exact primary-source comparison
    - first-attestation chronology
    - contact or exposure evidence
    - publication or distribution trail
    - phrase/image/error comparison
    - alternative-explanation test

  promotion_gate:
    minimum_requirement: >
      Promote to a transmission or propagation edge only when evidence documents movement,
      copying, citation, adaptation, contact, shared material, or another specific mechanism.
    allowed_promotions:
      - TRANSMISSION_EDGE
      - PROPAGATION_TRANSITION
      - DOCUMENTED_INFLUENCE
      - KNOWN_COPY
      - DIRECT_CITATION
      - SHARED_PUBLISHER
      - SHARED_MOTIF
      - INDEPENDENT_PARALLEL
      - NEGATIVE_EVIDENCE

  current_assessment:
    evidence_class: C
    confidence: LOW
    curator_note: "Interesting pattern; mechanism not yet demonstrated."

  generated_session: SESSION_027
  last_reviewed: 2026-07-13
```

## Rules

1. A bridge candidate may connect objects from entirely different research systems.
2. Similarity creates a search target, not a historical lineage.
3. Distinctive shared errors, rare phrases, reused images, and shared material artifacts are stronger leads than generic thematic resemblance.
4. Editors, printers, publishers, translators, archivists, broadcasters, collectors, clubs, conferences, distributors, and platforms must be tested as hidden carriers.
5. An exposure path is not proof that influence occurred; it establishes opportunity only.
6. Record what disappeared or changed, not merely what stayed similar.
7. Negative evidence and independent parallel development are valid outcomes.
8. Model-generated connections must remain `UNSOURCED_MODEL_INFERENCE` until checked against external records.
9. A bridge can be split when one apparent connection is actually several different processes.
10. Curator approval is required before any bridge candidate becomes a canonical edge.
