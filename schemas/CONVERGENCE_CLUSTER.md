# Canonical Schema: Convergence Cluster

**Purpose:** Compare two or more observation reports that may describe the same event, the same class of event, a shared cultural template, a shared environmental cause, or independent parallel experiences.

A convergence cluster is **not a truth score**. It is a structured comparison of specificity, independence, contamination, timing, geography, and ordinary explanations.

```yaml
CONVERGENCE_CLUSTER:
  id: CONV-001
  title: ""
  status: OPEN                 # OPEN | TESTING | SUPPORTED_PATTERN | EXPLAINED | SPLIT | REJECTED | UNKNOWN

  member_reports:
    - observation_id: OBS-001
      role: PRIMARY
    - observation_id: OBS-002
      role: COMPARISON

  cluster_scope:
    same_event_candidate: UNKNOWN
    same_event_class_candidate: UNKNOWN
    same_motif_candidate: UNKNOWN
    date_window: ""
    geographic_window: ""
    inclusion_rule: ""
    exclusion_rule: ""

  feature_matrix:
    shared_features: []
    conflicting_features: []
    missing_features: []
    rare_or_high-specificity_combinations: []
    generic_features: []
    researcher_normalization_risk: []

  timing_and_geography:
    temporal_overlap: UNKNOWN
    spatial_overlap: UNKNOWN
    travel_or_visibility_geometry: ""
    could_observers_have_seen_same_object_or_event: UNKNOWN
    could_one_environmental_event_explain_all: UNKNOWN

  independence_graph:
    direct_contacts: []
    shared_investigators: []
    shared_publications_or_platforms: []
    shared_local_community: []
    shared_media_or_folklore_exposure: []
    statements_locked_before_cross_exposure: []
    hidden_common_source_candidates: []
    independence_assessment: UNKNOWN

  ordinary_common_cause_tests:
    aircraft_spacecraft_or_traffic: []
    astronomical: []
    meteorological_or_optical: []
    geological_or_oceanographic: []
    biological: []
    technological_or_military: []
    hoax_or_prank: []
    reporting_or_data_processing_error: []
    shared_perceptual_or_linguistic_pattern: []

  contamination_tests:
    leading_questions: []
    investigator_vocabulary_migration: []
    media_sequence: []
    rumor_sequence: []
    later_story_harmonization: []
    translation_or_editorial_standardization: []

  convergence_profile:
    source_quality: 0          # 0–4; never report without justification
    feature_specificity: 0
    temporal_fit: 0
    geographic_fit: 0
    independence_support: 0
    pre_exposure_statement_lock: 0
    sensor_or_physical_support: 0
    ordinary_common_cause_strength: 0  # 0 = none found; 4 = strong
    contamination_risk: 0             # 0 = low documented risk; 4 = high
    internal_consistency: 0
    uncertainty_notes: ""

  interpretation_classes:
    - SAME_EVENT_ORDINARY_CAUSE
    - SAME_EVENT_UNRESOLVED
    - INDEPENDENT_OBSERVATIONS_SAME_PHENOMENON
    - SHARED_ENVIRONMENTAL_TRIGGER
    - COMMON_PERCEPTUAL_ERROR
    - CULTURAL_OR_MEDIA_TRANSMISSION
    - INVESTIGATOR_CONTAMINATION
    - LATER_NARRATIVE_HARMONIZATION
    - INDEPENDENT_PARALLEL
    - DATA_INSUFFICIENT
    - UNKNOWN

  evidence_for_pattern: []
  evidence_against_pattern: []
  negative_searches: []
  contradictions: []

  decisive_tests:
    - ""

  current_assessment:
    classification: UNKNOWN
    confidence: LOW
    curator_note: ""

  related_motifs: []
  related_bridge_candidates: []
  related_research_questions: []
  generated_session: SESSION-XXX
  last_reviewed: YYYY-MM-DD
```

## Scoring rules

1. Component values are an audit aid, not a probability calculation.
2. Never publish one summed `convergence score` without the component profile and source notes.
3. High feature overlap with high contamination is not strong independent convergence.
4. High independence with only generic features is also weak.
5. A strong ordinary common cause may explain a highly independent cluster.
6. `No explanation found` is not equivalent to `extraordinary explanation supported`.
7. A cluster can split into several events, several report chains, or several mechanisms.

## Priority bands

### A — high-value comparison

- contemporaneous or near-contemporaneous sources;
- statements preserved before cross-exposure;
- specific feature overlap;
- low documented contamination;
- precise time/location;
- sensor or environmental records available.

### B — interesting but contaminated or incomplete

- meaningful overlap;
- uncertain independence;
- later reporting;
- shared investigator, media, or community;
- incomplete environmental controls.

### C — folklore or narrative drift

- weak time and location control;
- repeated retelling;
- high exposure and harmonization risk;
- generic motifs;
- no primary statement chain.

These bands prioritize research. They do not determine whether a reported phenomenon was real, ordinary, extraordinary, or misperceived.
