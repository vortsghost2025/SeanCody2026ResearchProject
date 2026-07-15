# Research Methodology

## Purpose

Track the genealogy of ideas without assuming that repetition proves literal truth.

The project separates:

1. the original account or artifact;
2. the date the account allegedly occurred;
3. the earliest surviving documentation;
4. original-language wording and textual variants;
5. materially plausible translations;
6. later interpretations and modern reinterpretations;
7. evidence supporting or contradicting the claim;
8. possible routes of cultural transmission.

## Required fields

Every research record should answer as many of these as possible:

- Record ID
- Claim or motif
- Original wording or description
- Person, culture, organization, or publication
- Claimed event date
- Earliest traceable documentation date
- Publication or discovery date
- Country and geographic region
- Original language and script
- Diplomatic transcription or exact image locator
- Transliteration system and text
- Materially plausible translation variants
- Translator, edition and page provenance
- Source type
- Primary-source location
- Later reinterpretations
- Connected motifs
- Possible transmission route
- Evidence class
- Confidence and uncertainty notes

## Date discipline

Never collapse different dates into one. Record separately:

- when an event allegedly happened;
- when it was first written or recorded;
- the age of the earliest surviving copy;
- when each translation or edition appeared;
- when it entered UFO, occult, conspiracy, or internet culture;
- when a later source made it popular.

## Source hierarchy

Prefer, in order:

1. original manuscripts, artifacts, recordings, maps, logs, inscriptions and government archives;
2. museum, university, scholarly, critical or institutional editions;
3. peer-reviewed research and specialist histories;
4. contemporaneous journalism;
5. later books and documentaries;
6. witness testimony and interviews;
7. forums, videos, social media and anonymous reposts.

A low-level source may still be historically important as evidence that a narrative existed. It is not automatically evidence that its underlying claim is true.

## Original-language and translation rule

Read:

- `docs/ORIGINAL_LANGUAGE_TRANSLATION_PROTOCOL.md`
- `schemas/TRANSLATION_VARIANT.md`

For every inscription, quotation, title, map label, manuscript passage, religious term, technical phrase or translated testimony:

```text
original script or image
        ↓
diplomatic transcription
        ↓
normalized text
        ↓
transliteration
        ↓
segmentation and lexical range
        ↓
all materially plausible translations
        ↓
contextual evaluation
        ↓
later reinterpretation
```

Required boundaries:

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
later ideological or cultural reuse
```

Where grammar, lexicon, script, word division, textual damage, manuscript variation, proper-name status, historical semantic range or genre context allows more than one materially plausible reading, preserve all supported variants.

Do not generate arbitrary English paraphrases unsupported by the source language.

A preferred translation may be identified, but viable alternatives may not be deleted or hidden.

No ambiguous translated phrase may serve as a load-bearing bridge, motif match, map reading, quotation fingerprint, copied error or lineage claim unless the original-language witness and variant set are preserved.

## Independence test

Ten thousand repetitions may originate from one book or one anonymous post. Each apparent occurrence should be checked for:

- direct copying;
- shared authors or publishers;
- translation chains and translator dependency;
- trade, migration, conquest, religion and media contact;
- film, television, fiction and internet exposure;
- later details projected backward into older material.

Two English translations are not independent evidence when one copied the other.

## Similarity test

Broad similarities receive low weight. Specific combinations receive greater research priority.

Example:

- serpent symbol — weak similarity;
- intelligent serpent guardian — stronger;
- intelligent subterranean serpent guardian controlling a gate and teaching forbidden knowledge — highly specific.

High specificity still does not prove a common real-world cause. It identifies a pattern requiring better provenance analysis.

Translation can manufacture or hide similarity. Compare the original terms wherever possible before declaring a lexical or motif match.

## Observation-convergence extension

When two or more witnesses, instruments, logs or reports appear to describe the same unusual structure, use:

- `schemas/OBSERVATION_REPORT.md` for each original report;
- `schemas/CONVERGENCE_CLUSTER.md` for the comparison;
- `docs/INDEPENDENT_CONVERGENCE_METHOD.md` for the workflow.

Required separations:

```text
raw observation
        ≠
observer interpretation
        ≠
researcher explanation
```

Required tests:

- whether original statements were preserved before cross-exposure;
- whether reports share a hidden source, investigator, platform, rumor or media influence;
- whether feature overlap is specific or generic;
- whether one ordinary object or environmental event could explain all reports;
- whether later retellings or translations harmonized originally conflicting details;
- whether sensor evidence has its own source chain;
- what evidence would split, explain or reject the cluster.

Independence and convergence are separate dimensions:

```text
high independence + generic similarity
        = weak pattern

high specificity + high contamination
        = weak independent convergence

high specificity + documented pre-exposure independence
        = high research priority, not proof
```

Component profiles may be scored for audit, but the project does not use a single numerical convergence score as a probability of truth or extraordinary origin.

## Machine-translation boundary

Machine translation may generate search leads and candidate variants. It cannot be the sole authority for a load-bearing interpretation.

Record model/tool, version, date, output, source input and comparison with dictionaries or human translations. Preserve machine errors as possible contamination or copied-error fingerprints where historically relevant.

## Research principle

**Preserve what, who, when, where, why, how and every supported meaning before deciding what it means.**
