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

## 7. Default continuation — do not stop for rhetorical permission

When a brief already defines the target, search lanes, stop rules, evidence requirements, or next unresolved acquisition:

```text
continue gathering relevant data
        ↓
use remaining search/tool budget
        ↓
record failures and barriers
        ↓
return the strongest bounded result
```

Do **not** stop to ask:

- whether Sean wants more data;
- whether to continue to the next listed target;
- whether to follow a lead already authorized by the brief;
- whether to inspect another edition, carrier, archive, language witness, or source family needed to resolve the stated question.

Treat the answer as **YES** unless one of these applies:

1. the next action would be destructive, paid, irreversible, credential-sensitive, or outside the authorized repository/workspace;
2. two materially different goals cannot both be pursued and the choice would change the result;
3. personal, legal, medical, or other high-stakes information requires clarification;
4. the brief explicitly requires curator selection before proceeding;
5. tool or policy limits make continuation impossible.

When blocked, artifact the blockage and continue with every other available target. Do not replace research with a rhetorical permission question.

Read:

- `docs/AGENT_CONTINUATION_POLICY.md`
