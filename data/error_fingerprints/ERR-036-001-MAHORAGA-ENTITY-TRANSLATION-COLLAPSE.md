# ERR-036-001 — Mahoraga Entity / Translation Collapse

```yaml
ERROR_FINGERPRINT:
  id: ERR-036-001
  status: SUPPORTED_DUAL_COLLAPSE_PATTERN
  related_questions:
    - RQ-036
    - RQ-037
  related_motif: SERP-007
  related_translation_record: TRANS-036-001

  collapse_a:
    label: POP_CULTURE_ENTITY_COLLAPSE
    error: "Mahoraga is only a Jujutsu Kaisen fictional character and has no older serpent association."
    correction: >
      Mahoraga is also an older religious/cosmological term for a serpent-associated
      class of beings or deities; the manga usage is later reuse or translation.

  collapse_b:
    label: MODERN_ONTOLOGY_TRANSLATION_COLLAPSE
    error: "Mahoraga literally proves an ancient category equivalent to modern reptilian aliens or elites."
    correction: >
      Preserve the original lexical form and translation variants. Great serpent,
      great snake, retained Mahoraga, and context-dependent great serpent-being are
      materially plausible ways to handle the term. The modern English word reptilian
      carries biological, science-fiction and conspiracy meanings not automatically
      present in the older term.

  copying_or_influence_edge: NOT_ESTABLISHED
  generated_session: SESSION_039
  updated_session: SESSION_040
  last_reviewed: 2026-07-14
```

## Why this matters

Search engines and model corpora can collapse two different entities under one popular name:

```text
older religious Mahoraga
        ↓ obscured by search prominence
modern manga Mahoraga/Makora
```

A corrective search can then overreact in the opposite direction:

```text
older serpent term
        ↓ loaded English gloss
modern reptilian-conspiracy ontology projected backward
```

Both errors erase chronology, source type and linguistic ambiguity.

## Original-language requirement

Read:

- `docs/ORIGINAL_LANGUAGE_TRANSLATION_PROTOCOL.md`
- `schemas/TRANSLATION_VARIANT.md`
- `data/translation_variants/TRANS-036-001-MAHORAGA.md`

The project must preserve:

```text
महोरग
mahoraga
mahā + uraga
```

before comparing English renderings.

The following are not evidentially equivalent:

```text
Mahoraga
        = retained class-name

great serpent / great snake
        = lexical glosses

great serpent-being
        = context-sensitive religious rendering

Great Reptilians
        = modern loaded public gloss and later transmission object

ancient reptilian aliens
        = later ontology, not translation
```

## Source-type map

| Layer | Correct treatment |
|---|---|
| original Sanskrit lexical form | preserve script, transliteration, segmentation and exact textual location |
| Buddhist reference classification | scholarly secondary until exact primary text is acquired |
| Chinese, Japanese or Tibetan forms | separate translation/transliteration records, not one blended Asian tradition |
| manga/anime character | modern pop-culture reuse |
| Wikipedia `Great Reptilians` gloss | later English translation lead requiring lexical caution |
| conspiracy or ancient-alien citation | retroactive-reinterpretation record, when an exact dated source is found |
| David Icke or another named transmitter | direct citation/exposure test required |

## Promotion test

Acquire:

1. exact Sanskrit lexical and grammatical references for `uraga` and `mahoraga`;
2. exact Sanskrit primary-text occurrences and translations;
3. exact Buddhist Chinese, Tibetan and Japanese witnesses separately;
4. exact Jain and Hindu occurrences separately;
5. dated iconographic examples;
6. exact modern entertainment naming and translation history;
7. earliest dated conspiracy-site, book, video or social post using Mahoraga as ancient proof of modern reptilians;
8. any direct use by Icke, Collier, Dulce writers or another named transmitter;
9. translator dependency where multiple English sites repeat `Great Reptilians`.

## Allowed synthesis language

Allowed:

> An AI answer collapsed an older serpent-associated religious term into a modern manga character. A later correction recovered the older entity but also risked importing the modern English category `reptilian` into the historical source. The original term and translation variants must remain visible.

Not allowed:

> Mahoraga proves that ancient religions knew about modern reptilian elites.
