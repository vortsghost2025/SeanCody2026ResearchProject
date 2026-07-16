# Castello Q&A Authorship and Provenance Candidate

> **Related:** `RQ-036`, `BRIDGE-036-001`, Sessions 046–048  
> **Status:** document-persona and collaborative production candidate; November 2010 public carrier confirmed; first composition unresolved

## Document fact

The Castello-attributed Q&A contains the mature linked hierarchy:

```text
Draco / white Draco authority
        ↓ controls or creates
Grey and other worker castes
        ↓ inside
Dulce levels, laboratories and secret programs
```

This establishes content, not speaker identity.

## Confirmed dated public carrier

Session 048 establishes that the November 2010 Project Avalon thread contains actual Q&A body text and mature hierarchy wording.

```yaml
HINKLE_AVALON_2010:
  QandA_body_present: true
  mature_hierarchy_present: true
  dated_public_carrier: CONFIRMED
  first_composition: NOT_ESTABLISHED
  pre_1996_status: NOT_ESTABLISHED
```

## Competing participant accounts

### Lear 2008

Lear reportedly treats Castello as real and describes his own role retyping and redrawing Dulce Papers material, plus failed recovery expeditions involving a wider network.

### Hinkle 2010/2013

Hinkle treats Castello as real, publicly carries Q&A text, claims letters/recordings/box knowledge, and later claims an April 1991 death followed by impersonation.

### LeVesque 2015

LeVesque says TEC was a creation, the interview was creative writing, Hinkle answered questions in persona, and he mixed material and distributed packets.

```yaml
participant_accounts:
  relation: MUTUALLY_INCOMPATIBLE_IN_STRONG_FORM
  source_class: PARTICIPANT_SELF_ATTESTATIONS
  Castello_authentication: NOT_ESTABLISHED
  universal_override: NONE
```

## Leading reconstruction models

### A — LeVesque-led

```text
questions → Hinkle answers as TEC → LeVesque edits → Branton compiles
```

Status: `STRONGLY_SELF_ATTESTED_LATE_RECONSTRUCTION`.

### B — Hinkle-led

```text
Hinkle holds/creates Castello material → distributes broadly →
LeVesque and Branton edit/reuse → public 2010 carrier
```

Status: `PARTICIPANT_SOURCE_MODEL_STRENGTHENED_NOT_PROVEN`.

### C — collaborative multi-actor

```text
Bennewitz C-core + Hinkle/West material + Lear editorial layer +
LeVesque articles/editing + Hamilton/Valerian circulation + Branton compilation
```

Status: `STRONGEST_NEUTRAL_WORKING_MODEL_NOT_CANONICAL`.

Read:

- `graph/transmissions/HINKLE_LEVESQUE_DISTRIBUTION_MODELS.md`
- `reports/SESSION_048_AVALON_QA_TEXTUAL_STATE_CROSS_QC.md`

## Textual-stemma boundary

The Session 048 reports disagree over whether the 2010 Avalon and Branton states are derivative/near-identical or distinct with systematic editorial differences.

```yaml
textual_state_relation:
  Avalon_2010_carrier: CONFIRMED
  distinct_state_candidate: STRONG_BUT_DISPUTED
  identical_derivative_candidate: DISPUTED
  common_ancestor: POSSIBLE
  direction_of_derivation: UNRESOLVED
```

Required:

- full raw captures;
- post IDs and timestamps;
- diplomatic transcriptions;
- normalization rules;
- hashes;
- reproducible diff.

## Separate Hinkle corpus

A second Avalon exchange reportedly uses `Repton`, `Dracon`, `Kaarsh`, Telos/Mt. Shasta and a `King of This World` above the Dracons.

```yaml
Hinkle_second_corpus:
  relation_to_original_QA: SEPARATE_PARTICIPANT_EXPANSION
  hierarchy_model: DRACONS_SUBORDINATE_TO_HIGHER_POWER
  pre_1996_status: NOT_ESTABLISHED
```

This indicates multiple hierarchy models in the wider Hinkle-associated material.

## Branton role

```yaml
Branton:
  compiler_role: SUPPORTED
  signed_notes: SUPPORTED
  unsigned_hierarchy_authorship: POSSIBLE_NOT_PROVEN
  direct_derivation_from_Hinkle_state: PLAUSIBLE_NOT_PROVEN
```

## Material-artifact record

The acquired record contains no authenticated:

- Castello box;
- 1987/1988 letter;
- Japanese television master;
- original sketches with custody;
- treaty or device;
- LeVesque packet;
- Castello identity records.

```yaml
material_artifacts_recovered: 0
classification: CLAIMS_EXCEED_PRODUCTIONS_IN_ACQUIRED_SET
```

## Current decision

```yaml
Castello_source_class: DOCUMENT_PERSONA_OR_CONTESTED_ATTRIBUTED_SPEAKER
mature_hierarchy_content: CONFIRMED
first_securely_dated_public_QA_carrier: PROJECT_AVALON_NOVEMBER_2010
first_composition: UNKNOWN
Hinkle_pre_1996_source_state: NOT_ESTABLISHED
textual_stemma: UNRESOLVED
neutral_working_model: COLLABORATIVE_MULTI_ACTOR
packet_execution: UNCORROBORATED
verified_packet_recipients: 0
material_artifacts_recovered: 0
canonical_authorship_edge: false
canonical_first_composition_edge: false
canonical_distribution_edge: false
```
