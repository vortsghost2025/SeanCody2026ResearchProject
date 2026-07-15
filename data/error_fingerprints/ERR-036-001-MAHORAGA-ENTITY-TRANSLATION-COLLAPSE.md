# ERR-036-001 — Mahoraga Entity / Translation Collapse

```yaml
ERROR_FINGERPRINT:
  id: ERR-036-001
  status: SUPPORTED_DUAL_COLLAPSE_PATTERN
  related_question: RQ-036
  related_motif: SERP-007

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
      The compound is more conservatively glossed as great serpent. The modern English
      word reptilian carries biological, science-fiction, and conspiracy meanings not
      automatically present in the older term.

  copying_or_influence_edge: NOT_ESTABLISHED
  generated_session: SESSION_039
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

Both errors erase chronology.

## Source-type map

| Layer | Correct treatment |
|---|---|
| older Sanskrit and religious term | item-level textual and iconographic acquisition |
| Buddhist reference classification | scholarly secondary until exact primary text is acquired |
| manga/anime character | modern pop-culture reuse |
| Wikipedia `Great Reptilians` gloss | translation lead requiring lexical caution |
| conspiracy or ancient-alien citation | later retroactive-reinterpretation record, if exact source is found |
| David Icke or other named transmitter | direct citation/exposure test required |

## Promotion test

Acquire:

1. exact Sanskrit lexical reference for `uraga` and `mahoraga`;
2. exact Buddhist primary-text occurrence and translation;
3. exact Jain and Hindu occurrences separately;
4. dated iconographic examples;
5. exact modern entertainment naming/translation history;
6. earliest dated conspiracy-site, book, video, or social post using Mahoraga as ancient proof of modern reptilians;
7. any direct use by Icke, Collier, Dulce writers, or another named transmitter.

## Allowed synthesis language

Allowed:

> An AI answer collapsed an older serpent-associated religious term into a modern manga character. A later correction recovered the older entity but also risked importing the modern English category `reptilian` into the historical source.

Not allowed:

> Mahoraga proves that ancient religions knew about modern reptilian elites.
