# Agent Instructions — Sean & Cody Research Project

These rules are mandatory for every agent working in this repository.

## 1. Original-language rule

For every inscription, quotation, map label, title, name, manuscript passage, religious phrase, technical term, or translated testimony:

```text
preserve the original script or source image
        ↓
create a diplomatic transcription
        ↓
record transliteration separately
        ↓
segment words and morphology
        ↓
record lexical ranges
        ↓
record every materially plausible translation
        ↓
state assumptions and translator provenance
        ↓
separate later reinterpretation
```

Read:

- `docs/ORIGINAL_LANGUAGE_TRANSLATION_PROTOCOL.md`
- `schemas/TRANSLATION_VARIANT.md`
- `research_questions/RQ-037-TRANSLATION-AMBIGUITY-SEMANTIC-DRIFT.md`

Do not return only one polished English translation when the original permits multiple supported readings.

“Every possible translation” means every materially plausible reading supported by grammar, lexicon, script, textual variation, historical usage, genre context, or documented scholarship. Do not invent arbitrary paraphrases.

No ambiguous translated phrase may establish a bridge, motif identity, map reading, copied fingerprint, quotation lineage, or documented influence without an original-language comparison record.

## 2. Translation layers must remain separate

```text
original writing
        ≠
transliteration
        ≠
literal gloss
        ≠
possible translation
        ≠
preferred contextual translation
        ≠
later ideological, doctrinal, conspiracy, or pop-cultural reuse
```

Preserve viable alternatives even when recommending one contextual reading.

## 3. Source and evidence discipline

- Prefer primary images, manuscripts, scans, logs, maps, recordings, and institutional editions.
- Preserve exact page, folio, frame, timestamp, map coordinates, catalogue ID, shelfmark, edition, and stable source.
- Separate artifact existence from the truth of a claim contained in it.
- Similarity is not transmission.
- Shared publisher or byline is not influence by itself.
- Repeated summaries may derive from one hidden source.
- Record failed searches, contradictions, inaccessible archives, and negative evidence.
- Never mark a result canonical, complete, resolved, or first-source without curator review.

## 4. Translation dependency

Two English translations are not independent when one copied or normalized the other.

For each translation capture:

- translator;
- edition and date;
- page;
- source manuscript or edition;
- declared method where available;
- later sources copying it;
- loaded, modernizing, or anachronistic terminology.

Machine translation may generate leads and variants but cannot be the sole authority for a load-bearing interpretation.

## 5. Maps and inscriptions

Do not detach translated wording from spatial or visual context.

Preserve:

- exact placement;
- orientation;
- neighboring labels and symbols;
- abbreviations, ligatures, damage, and supplied characters;
- edition or map-state differences;
- whether a modern catalogue expanded or normalized the original.

## 6. Human curator boundary

Sean supplies research direction and puzzle pieces. Agents acquire, compare, challenge, and preserve variants. Final promotion, entity resolution, and canonical synthesis require curator review.
