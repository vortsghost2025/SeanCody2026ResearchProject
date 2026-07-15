# TRANS-036-001 — `mahoraga / mahā-uraga`

```yaml
TRANSLATION_RECORD:
  id: TRANS-036-001
  status: PARTIAL

  source_object:
    related_record_id: SERP-007
    object_type: RELIGIOUS_TERM
    title_or_label: "Mahoraga / mahoraga"
    exact_primary_textual_witness: NOT_YET_SELECTED
    source_scope: >
      Sanskrit term and later Buddhist-language transmission; one exact canonical or
      commentarial occurrence must still be acquired before sentence-level translation.

  language_witness:
    language: Sanskrit
    script: Devanagari representation
    diplomatic_transcription: "महोरग"
    normalized_text: "महोरग"
    transcription_confidence: HIGH_FOR_LEXICAL_FORM

  transliteration:
    system: IAST
    text: "mahoraga"
    alternate_transliterations:
      - "mahā-uraga"  # analytic compound representation
      - "maha-uraga"  # diacritic-free search form
    confidence: HIGH

  segmentation:
    units:
      - surface_form: "mahā"
        lexical_range:
          - great
          - large
          - mighty
          - eminent
      - surface_form: "uraga"
        lexical_range:
          - serpent
          - snake
          - serpent-being
          - a member of a mythic serpent class in context
    syntactic_structure: "descriptive compound or lexicalized class-name"
    segmentation_alternatives:
      - "treat mahoraga as a lexicalized proper/class name without translating the components"
    confidence: MEDIUM_HIGH_PENDING_EXACT_TEXT

  translation_variants:
    - variant_id: TRANS-036-001-V1
      text: "Mahoraga"
      classes:
        - PROPER_NAME_READING
        - TRANSLITERATION_RETAINED
      assumptions:
        grammar: []
        lexical_choices:
          - preserve the historical term rather than force an English ontology
      plausibility: HIGH
      contextual_fit: HIGH_FOR_CLASS_NAME
      anachronism_or_loaded_term_risk: LOW

    - variant_id: TRANS-036-001-V2
      text: "great serpent"
      classes:
        - MORPHEME_LITERAL
        - FORMAL_EQUIVALENCE
      assumptions:
        lexical_choices:
          - mahā rendered as great
          - uraga rendered as serpent
      plausibility: HIGH
      contextual_fit: HIGH_AS_LEXICAL_GLOSS
      anachronism_or_loaded_term_risk: LOW

    - variant_id: TRANS-036-001-V3
      text: "great snake"
      classes:
        - MORPHEME_LITERAL
        - FORMAL_EQUIVALENCE
      assumptions:
        lexical_choices:
          - uraga rendered with the ordinary zoological English word snake
      plausibility: HIGH
      contextual_fit: MEDIUM
      anachronism_or_loaded_term_risk: LOW

    - variant_id: TRANS-036-001-V4
      text: "great serpent-being"
      classes:
        - GENRE_CONTEXTUAL
        - RELIGIOUS_DOCTRINAL
      assumptions:
        lexical_choices:
          - add being to indicate a mythic or cosmological class rather than an ordinary animal
        genre_or_context:
          - religious class-name context
      plausibility: MEDIUM_HIGH
      contextual_fit: HIGH_WHERE_PERSONHOOD_OR_DEITY_CLASS_IS_EXPLICIT
      anachronism_or_loaded_term_risk: LOW

    - variant_id: TRANS-036-001-V5
      text: "great reptile"
      classes:
        - MODERNIZING
        - LOADED_OR_ANACHRONISTIC
      assumptions:
        lexical_choices:
          - broaden serpent into the modern zoological class reptile
      evidence_against:
        - loses the specifically serpent/snake lexical content
        - imports a later biological category
      plausibility: LOW_AS_LITERAL_TRANSLATION
      contextual_fit: LOW
      anachronism_or_loaded_term_risk: HIGH

    - variant_id: TRANS-036-001-V6
      text: "Great Reptilians"
      classes:
        - MODERNIZING
        - LOADED_OR_ANACHRONISTIC
        - LATER_PUBLIC_GLOSS
      assumptions:
        lexical_choices:
          - renders uraga as reptilian rather than serpent
          - pluralizes or treats the term as a race/class label
      evidence_for:
        - occurs as a modern English web gloss and therefore matters as a later transmission object
      evidence_against:
        - modern conspiracy and science-fiction associations are not inherent in the Sanskrit components
        - can falsely imply biological or alien-species continuity
      plausibility: LOW_AS_NEUTRAL_ORIGINAL_TRANSLATION
      contextual_fit: POSSIBLE_AS_MODERN_INTERPRETIVE_GLOSS_ONLY
      anachronism_or_loaded_term_risk: VERY_HIGH

  preferred_contextual_readings:
    - "Mahoraga" when preserving the class-name
    - "great serpent" as a concise lexical gloss
    - "great serpent-being" when the exact religious context clearly describes a class of beings

  rejected_readings:
    - text: "ancient reptilian alien"
      reason: "not a translation of the Sanskrit term; later ontological reinterpretation"
    - text: "modern shapeshifting reptilian elite"
      reason: "not present in the lexical form and requires a separate modern source"

  ambiguity_profile:
    lexical:
      - serpent versus snake in English register
      - untranslated class-name versus translated descriptive phrase
    genre_or_context:
      - ordinary large serpent versus mythic/religious class of beings
    semantic_change:
      - modern reptile/reptilian terminology carries biological, science-fiction and conspiracy meanings
    proper_name_or_common_noun:
      - Mahoraga as lexicalized name/class versus compositional great serpent

  later_reinterpretations:
    - date: MODERN
      source: "English-language web glosses"
      wording: "Great Reptilians"
      interpretation_type: MODERN_ONTOLOGY_TRANSLATION
      relationship_to_original: >
        broadens serpent into reptilian and may create false continuity with modern alien or conspiracy categories
    - date: MODERN
      source: "Jujutsu Kaisen English-language reception"
      wording: "Mahoraga"
      interpretation_type: POP_CULTURE_REUSE_OR_NAME_COLLAPSE
      relationship_to_original: >
        modern entertainment use can dominate search results and obscure the older term; exact Japanese naming history remains open

  transmission_tests:
    original_language_phrase_matches: []
    translation_only_matches:
      - "Great Reptilians must not be matched to modern reptilian lore without locating the later source that chose this gloss"
    false_equivalence_risks:
      - "serpent-class religious term = modern biological reptilian species"
      - "shared English word reptilian = direct historical lineage"

  completeness:
    status: PARTIAL_VARIANT_SET
    missing_languages_editions_or_experts:
      - exact Sanskrit primary passage and grammatical context
      - Buddhist Chinese transliteration and any semantic glosses
      - Japanese textual and iconographic usage
      - Tibetan translation and literal analysis
      - Jain and Hindu attestations separately
      - specialist Sanskrit and Buddhist-studies review

  confidence_profile:
    transcription: HIGH_FOR_LEXICAL_FORM
    language_identification: HIGH
    segmentation: MEDIUM_HIGH
    lexical_analysis: MEDIUM_HIGH
    syntax: UNKNOWN_WITHOUT_SENTENCE
    contextual_translation: MEDIUM
    later_transmission: LOW

  related_records:
    - SERP-007
    - RQ-036
    - RQ-037
  related_error_fingerprints:
    - ERR-036-001
  generated_session: SESSION_040
  last_reviewed: 2026-07-14
```

## Curator boundary

This record preserves multiple plausible English renderings of the lexical term. It does not yet translate one exact canonical passage.

A sentence-level record may change which English rendering fits best because number, syntax, neighboring words and doctrinal context can constrain the meaning.

## Current conclusion

```text
mahoraga
        can be preserved as the class-name
        or glossed as great serpent / great snake
        or contextually as great serpent-being

“Great Reptilians”
        is historically relevant as a modern English rendering
        but is high-risk and anachronistic as a neutral translation
```
