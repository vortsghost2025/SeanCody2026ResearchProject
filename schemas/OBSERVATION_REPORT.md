# Canonical Schema: Observation Report

**Purpose:** Preserve one observer's or instrument's report before it is merged into a story, event cluster, motif, or explanation.

An observation report records **what was reported**, **when it was recorded**, and **what may have shaped it**. It does not certify that the observation was accurate or that the observer's interpretation was correct.

```yaml
OBSERVATION_REPORT:
  id: OBS-001
  status: RAW                 # RAW | PARTIAL | VERIFIED_SOURCE | CORROBORATED | REJECTED | DUPLICATE

  source_record:
    source_type: INTERVIEW    # LOG | DIARY | LETTER | INTERVIEW | NEWSPAPER | FORM | AUDIO | VIDEO | SENSOR | OTHER
    creator_or_observer: ""
    recorder_or_investigator: ""
    original_title_or_heading: ""
    institution_or_archive: ""
    catalogue_or_case_id: ""
    stable_source_url: ""
    page_image_timestamp_or_frame: ""
    original_language: ""
    transcription_status: UNVERIFIED

  time:
    claimed_event_start: ""
    claimed_event_end: ""
    timezone_as_reported: ""
    normalized_utc_start: ""
    normalized_utc_end: ""
    report_created_at: ""
    first_publication_at: ""
    time_precision: UNKNOWN   # EXACT | MINUTE | HOUR | DAY | APPROXIMATE | UNKNOWN

  location:
    reported_place: ""
    observer_coordinates: null
    viewing_direction: ""
    estimated_object_bearing: ""
    estimated_distance_or_altitude: ""
    coordinate_precision: UNKNOWN

  report_chain:
    firsthand: UNKNOWN
    retelling_depth: 0
    statement_recorded_before_cross_exposure: UNKNOWN
    intermediaries: []
    known_edits_or_summaries: []
    translation_chain: []

  original_wording:
    full_excerpt: ""
    source_locator: ""
    researcher_paraphrase: ""

  observation_features:
    object_count: null
    shape_terms_raw: []
    shape_normalized: []
    color_terms_raw: []
    luminosity: UNKNOWN
    apparent_size: ""
    motion_raw: []
    motion_normalized: []
    direction_of_travel: ""
    sound_raw: []
    sound_normalized: []
    duration_reported: ""
    disappearance_or_ending: ""
    environmental_effects: []
    physiological_effects: []
    instrument_effects: []
    other_distinctive_features: []

  observer_context:
    number_of_observers: null
    observers_interviewed_separately: UNKNOWN
    relevant_expertise: []
    visual_or_hearing_conditions: []
    fatigue_stress_intoxication_or_medication: UNKNOWN
    expectation_or_prior_belief: UNKNOWN
    confidence_expressed_by_observer: ""

  environment:
    weather: ""
    visibility: ""
    cloud_cover: ""
    astronomical_conditions: ""
    known_air_sea_or_ground_traffic: ""
    terrain_or_horizon: ""
    other_shared_triggers: []

  corroboration:
    photographs_or_video: []
    radar_sonar_or_sensor: []
    physical_trace: []
    independent_reports: []
    later_confirmed_environmental_event: []

  contamination:
    direct_contact_with_other_reporters: UNKNOWN
    shared_investigator: UNKNOWN
    shared_prompt_or_questionnaire: UNKNOWN
    local_rumor_before_report: UNKNOWN
    news_or_social_media_exposure: UNKNOWN
    fiction_or_folklore_exposure: UNKNOWN
    publication_after_other_reports: UNKNOWN
    contamination_notes: []

  observer_interpretation:
    labels_used_by_observer: []
    causal_claims: []

  researcher_hypotheses:
    ordinary_candidates: []
    extraordinary_candidates: []
    unresolved: []

  quality_profile:
    source_proximity: 0       # 0–4, with written justification
    temporal_proximity: 0
    feature_detail: 0
    location_time_precision: 0
    independence_support: 0
    sensor_support: 0
    contamination_risk: 0     # 0 = low documented risk; 4 = high documented risk
    notes: ""

  related_clusters: []
  related_motifs: []
  related_bridge_candidates: []
  added_session: SESSION-XXX
  last_reviewed: YYYY-MM-DD
```

## Rules

1. Preserve raw wording before normalization.
2. Keep observation, observer interpretation, and researcher hypothesis in separate fields.
3. Do not infer observer independence from distance alone.
4. A later recollection is not equivalent to a contemporaneous log.
5. A report copied by ten publications remains one report chain.
6. Missing mundane identification does not increase the probability of a preferred extraordinary explanation by itself.
7. Feature normalization must retain the original term and the researcher's normalized term.
8. Sensor data must be stored as its own source record and linked, not described vaguely as `radar confirmed`.
9. Witness credibility is not a single character judgment; record the particular source, timing, conditions, and competencies.
10. Privacy-sensitive living-witness information must not be published without consent or lawful public-source basis.
