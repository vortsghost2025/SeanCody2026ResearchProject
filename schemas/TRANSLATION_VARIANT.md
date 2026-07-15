# Canonical Schema: Translation Variant

**Purpose:** Preserve original-language evidence, materially plausible readings and translation provenance without letting one English rendering replace the source.

```yaml
TRANSLATION_RECORD:
  id: TRANS-001
  status: OPEN                # OPEN | PARTIAL | REVIEWED | DISPUTED | SINGLE_READING | UNRESOLVED

  source_object:
    related_record_id: ""
    object_type: INSCRIPTION  # MANUSCRIPT | BOOK | MAP | INSCRIPTION | TITLE | QUOTATION | TESTIMONY | AUDIO | OTHER
    title_or_label: ""
    creator_or_culture: ""
    claimed_date: ""
    surviving_copy_date: ""
    edition_manuscript_plate_or_state: ""
    institution_or_archive: ""
    catalogue_or_call_number: ""
    stable_source: ""
    image_folio_page_frame_or_coordinates: ""

  language_witness:
    language: ""
    dialect_or_stage: ""
    script: ""
    writing_direction: ""
    diplomatic_transcription: ""
    normalized_text: ""
    uncertain_characters: []
    supplied_or_restored_text: []
    lineation_notes: ""
    transcription_authority: ""
    transcription_confidence: UNKNOWN

  transliteration:
    system: ""
    text: ""
    alternate_transliterations: []
    confidence: UNKNOWN

  segmentation:
    units:
      - surface_form: ""
        lemma_or_root: ""
        morphology: ""
        lexical_range: []
        dictionary_sources: []
        uncertainty: ""
    syntactic_structure: ""
    segmentation_alternatives: []
    confidence: UNKNOWN

  translation_variants:
    - variant_id: TRANS-001-V1
      text: ""
      classes: []             # MORPHEME_LITERAL | WORD_FOR_WORD | FORMAL_EQUIVALENCE | IDIOMATIC | etc.
      translator_or_proposer: ""
      edition_or_output: ""
      publication_date: ""
      page_or_locator: ""
      source_text_used: ""
      assumptions:
        grammar: []
        lexical_choices: []
        supplied_referents: []
        genre_or_context: []
      evidence_for: []
      evidence_against: []
      plausibility: UNKNOWN   # HIGH | MEDIUM | LOW | REJECTED | UNKNOWN
      contextual_fit: UNKNOWN
      anachronism_or_loaded_term_risk: UNKNOWN
      copied_from_or_dependent_on: []

  preferred_contextual_readings: []
  rejected_readings:
    - text: ""
      reason: ""

  ambiguity_profile:
    lexical: []
    grammatical: []
    syntactic: []
    referential: []
    textual_damage: []
    manuscript_or_edition: []
    genre_or_context: []
    semantic_change: []
    proper_name_or_common_noun: []

  later_reinterpretations:
    - date: ""
      source: ""
      wording: ""
      interpretation_type: ""
      relationship_to_original: ""
      source_locator: ""

  transmission_tests:
    original_language_phrase_matches: []
    translation_only_matches: []
    translator_dependency_chain: []
    copied_error_candidates: []
    false_equivalence_risks: []

  machine_translation_runs:
    - tool_model_version: ""
      date: ""
      prompt_or_settings: ""
      output: ""
      errors_or_useful_variants: []

  completeness:
    status: UNASSESSED       # UNASSESSED | PARTIAL_VARIANT_SET | MAJOR_VARIANTS_CAPTURED | SCHOLARLY_DISPUTE_CAPTURED | SINGLE_READING_STRONGLY_SUPPORTED | TEXT_TOO_DAMAGED | LANGUAGE_OR_SCRIPT_UNRESOLVED
    missing_languages_editions_or_experts: []

  confidence_profile:
    transcription: UNKNOWN
    language_identification: UNKNOWN
    segmentation: UNKNOWN
    lexical_analysis: UNKNOWN
    syntax: UNKNOWN
    contextual_translation: UNKNOWN
    later_transmission: UNKNOWN

  related_records: []
  related_bridges: []
  related_error_fingerprints: []
  generated_session: SESSION-XXX
  last_reviewed: YYYY-MM-DD
```

## Rules

1. Original script is mandatory when recoverable; transliteration never replaces it.
2. Preserve exact image or page location.
3. Keep diplomatic transcription separate from normalized text.
4. Record all materially plausible translations, including competing grammatical or lexical readings.
5. Do not manufacture variants unsupported by the source language.
6. A curator preference does not delete alternatives.
7. Record translator and edition provenance; translations may copy one another.
8. Label loaded or anachronistic English terms.
9. Compare load-bearing phrases in the original language where possible.
10. A translation record establishes linguistic possibilities, not the truth of the underlying religious, historical or anomalous claim.
