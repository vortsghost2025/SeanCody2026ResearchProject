# Original-Language and Translation-Variant Protocol

## Purpose

Prevent one English rendering from becoming the artifact.

The project preserves the original-language witness first, then records translation as a set of argued possibilities rather than a single invisible replacement.

```text
artifact image or diplomatic transcription
        ↓
original script
        ↓
transliteration
        ↓
segmentation and morphology
        ↓
literal lexical range
        ↓
materially plausible translations
        ↓
contextual evaluation
        ↓
later reinterpretations and reuse
```

## 1. Mandatory original-language capture

For every language-bearing source, preserve when available:

- page, folio, inscription, frame or map image;
- original script exactly as printed, written or carved;
- capitalization, punctuation, abbreviations and line breaks;
- damaged, erased, uncertain or supplied characters;
- edition, manuscript, plate, state or map impression;
- source date and copy date separately;
- language, dialect and script;
- hand, typeface or engraving notes where relevant.

Never replace the original with a transliteration.

## 2. Required representation layers

### A. Diplomatic transcription

Reproduce what is visibly present with minimal normalization.

### B. Normalized text

Expand conventional abbreviations or normalize orthography only in a separate field.

### C. Transliteration

Convert script into a declared romanization or transliteration system. Preserve diacritics.

### D. Segmentation and morphology

Identify compounds, roots, affixes, case, number, gender, tense, voice and syntactic relationships where applicable.

### E. Interlinear or lexical gloss

Record the ordinary historical lexical range of each component without forcing polished English.

### F. Translation variants

Record every materially plausible whole-text translation and its assumptions.

### G. Contextual preference

A curator may identify one or more better-supported contextual translations, but may not delete viable alternatives.

### H. Later reinterpretation

Record doctrinal, political, occult, scientific, conspiratorial, literary or pop-cultural reuse separately.

## 3. Material-plausibility rule

A translation variant is retained when supported by:

- grammar or syntax;
- attested historical lexical range;
- uncertainty in script or word division;
- manuscript or edition variation;
- damaged text or editorial restoration;
- proper-name/common-noun ambiguity;
- literal versus idiomatic construction;
- historical semantic change;
- genre, ritual, legal, cartographic or technical convention;
- specialist published translation;
- a documented scholarly dispute.

An unsupported imaginative paraphrase is not a translation variant.

## 4. Variant completeness

Use one status:

- `UNASSESSED`
- `PARTIAL_VARIANT_SET`
- `MAJOR_VARIANTS_CAPTURED`
- `SCHOLARLY_DISPUTE_CAPTURED`
- `SINGLE_READING_STRONGLY_SUPPORTED`
- `TEXT_TOO_DAMAGED`
- `LANGUAGE_OR_SCRIPT_UNRESOLVED`

`MAJOR_VARIANTS_CAPTURED` means all presently located materially distinct readings are represented. It does not claim no future reading is possible.

## 5. Translation classes

Each translation receives one or more labels:

- `MORPHEME_LITERAL`
- `WORD_FOR_WORD`
- `FORMAL_EQUIVALENCE`
- `IDIOMATIC`
- `GENRE_CONTEXTUAL`
- `HISTORICAL_TECHNICAL`
- `RELIGIOUS_DOCTRINAL`
- `CARTOGRAPHIC_CONVENTION`
- `PROPER_NAME_READING`
- `COMMON_NOUN_READING`
- `EDITORIAL_RECONSTRUCTION`
- `MODERNIZING`
- `LOADED_OR_ANACHRONISTIC`

A loaded or anachronistic rendering may be historically important as a later carrier while remaining weak as a translation of the original.

## 6. Translator provenance

For every published translation record:

- translator;
- edition;
- publication date;
- page;
- source text or manuscript used;
- declared method where available;
- publisher or institution;
- later sources copying that translation;
- possible ideological, doctrinal or disciplinary framing.

Do not call two translations independent when one silently copies the other.

## 7. Map and inscription rules

For map labels, legends and inscriptions, also preserve:

- exact spatial placement;
- relation to nearby coastlines, borders, symbols and illustrations;
- orientation and reading direction;
- abbreviations and ligatures;
- whether text is a place-name, descriptive label, dedication, warning, quotation or printer's note;
- alternate label readings across editions or states;
- whether a modern catalogue translated, expanded or normalized the wording.

A translated map label cannot be detached from its location and treated as a free-standing statement.

## 8. Quotation rules

When quoting a translated source in synthesis, show:

1. original-language text;
2. transliteration when useful;
3. the translation used;
4. materially different alternatives;
5. source and translator;
6. uncertainty note.

A concise synthesis may move the full apparatus into a linked translation record, but it must not hide that ambiguity exists.

## 9. Bridge and fingerprint rule

No ambiguous translated phrase may establish:

- `DIRECT_CITATION`;
- `KNOWN_COPY`;
- `LEXICAL_MIGRATION`;
- `SHARED_ERROR`;
- `DOCUMENTED_INFLUENCE`;
- a motif identity;
- a historical lineage;

until the comparison is performed in the original language where possible.

Two English phrases may look identical because translators standardized different originals. Two English phrases may look different while translating the same original wording.

## 10. Machine-translation boundary

Machine translation can generate search leads and candidate variants. It cannot serve as the sole authority for a load-bearing interpretation.

Record:

- model/tool and version;
- date;
- prompt or settings where relevant;
- output;
- comparison with dictionaries and human translations;
- errors, omissions and normalization.

## 11. Confidence dimensions

Keep separate:

- transcription confidence;
- language identification confidence;
- segmentation confidence;
- lexical confidence;
- syntactic confidence;
- translation plausibility;
- contextual fit;
- historical-transmission confidence.

A clear transcription can still have an ambiguous meaning. A confident translation can still have no documented later influence.

## 12. Core principle

> Preserve the source's possible meanings before deciding which later story used it.
