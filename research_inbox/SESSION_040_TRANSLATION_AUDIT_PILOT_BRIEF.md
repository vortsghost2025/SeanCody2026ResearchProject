# SESSION 040 — Original-Language Translation Audit Pilot

**Target:** `RQ-037`  
**Mode:** cross-domain method validation  
**Status:** OPEN — acquisition and comparison only

## Objective

Test the original-language protocol on three different source classes before retrofitting every legacy record:

1. religious/cosmological term;
2. map label or inscription;
3. translated historical quotation.

The pilot must demonstrate whether translation ambiguity materially changes a proposed motif, bridge, map reading, copied fingerprint, or historical interpretation.

## Pilot A — Mahoraga

Use:

- `SERP-007`;
- `TRANS-036-001`;
- `ERR-036-001`.

Acquire one exact primary Sanskrit or Buddhist textual occurrence of `mahoraga` with:

```text
institutional or critical edition
page/folio/line
original script
full sentence or verse
transliteration
word division
morphology and syntax
published translations
materially plausible alternatives
religious context
```

Then acquire the Chinese, Japanese or Tibetan witness that is most directly linked to the claimed class description. Do not combine traditions without item-level records.

## Pilot B — Terra Australis map language

Select one load-bearing label from RQ-031, preferably from an already authenticated map or the next Ptolemaic item.

Return:

```text
exact image coordinates
original label and script
abbreviations and ligatures
transcription
Latin/Greek/vernacular segmentation
literal and cartographic-context translations
alternate scholarly readings
relationship to neighboring coastlines and legends
whether later catalogues normalized the text
```

Test whether a common English translation creates a stronger southern-continent claim than the original label supports.

## Pilot C — translated polar or exploration quotation

Select one non-English quotation used in Hollow Earth, open-polar-sea or Antarctic lineage arguments.

Return:

```text
original publication and page
original language
exact quotation
all published translations located
translator dependencies
literal and idiomatic alternatives
technical/navigation terminology
later quotation mutations
which version entered later lore
```

Test whether later writers copied the original, one translation, or a mistranslation.

## Required deliverables

For each pilot:

1. one complete `TRANSLATION_RECORD`;
2. source image or exact institutional locator;
3. original script and transliteration;
4. segmentation and lexical table;
5. all materially plausible translation variants;
6. translator/edition dependency graph;
7. contextual preference with reasons;
8. loaded or anachronistic terms;
9. effect on related bridge or motif claims;
10. failed searches and missing expertise.

## Required outcomes

Use one or more:

- `AMBIGUITY_MATERIALLY_CHANGES_CLAIM`
- `MULTIPLE_READINGS_REMAIN_VIABLE`
- `ONE_READING_STRONGLY_SUPPORTED`
- `TRANSLATION_CREATED_FALSE_MATCH`
- `TRANSLATION_HID_ORIGINAL_MATCH`
- `LATER_GLOSS_BECAME_CARRIER`
- `TRANSLATOR_DEPENDENCY_FOUND`
- `TEXT_TOO_DAMAGED`
- `SPECIALIST_REVIEW_REQUIRED`
- `UNKNOWN`

## Stop rules

Do not:

- provide only a polished English translation;
- omit the original script;
- treat etymology as sentence meaning;
- treat every imaginable paraphrase as viable;
- merge different religious or regional traditions;
- use machine translation as sole authority;
- infer transmission from matching English alone;
- declare a modern ontology present in an older term without textual evidence.

## Copy-paste agent prompt

> Read `docs/METHODOLOGY.md`, `docs/ORIGINAL_LANGUAGE_TRANSLATION_PROTOCOL.md`, `schemas/TRANSLATION_VARIANT.md`, `research_questions/RQ-037-TRANSLATION-AMBIGUITY-SEMANTIC-DRIFT.md`, and `research_inbox/SESSION_040_ORIGINAL_LANGUAGE_TRANSLATION_POLICY.md`. Execute `research_inbox/SESSION_040_TRANSLATION_AUDIT_PILOT_BRIEF.md`. Build three translation records: one exact Mahoraga textual witness, one load-bearing Terra Australis map label, and one non-English polar/exploration quotation used in later lore. Preserve source images, original scripts, transliterations, segmentation, grammar, lexical ranges, published translator variants, materially plausible alternatives, translator dependencies, loaded terms and later reinterpretations. Explain how each variant changes or does not change the historical claim. Do not return only a preferred English translation and do not invent unsupported alternatives.
