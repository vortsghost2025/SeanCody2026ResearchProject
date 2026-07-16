# ERR-036-002 — A+B+C Co-Presence / Linkage Collapse

```yaml
ERROR_FINGERPRINT:
  id: ERR-036-002
  title: "Separate ingredients in one compilation mistaken for one connected hierarchy"
  status: SUPPORTED_STRUCTURAL_ERROR
  related_question: RQ-036
  related_bridge: BRIDGE-036-001

  error_pattern: >
    A model marks an artifact FULL because it contains reptilian or Draconian
    entities, a separate statement that Greys are created or controlled, and
    underground-base or treaty material, even though the text does not connect
    the reptilian group to control of those Greys inside that system.

  collapsed_structure:
    - A occurs somewhere in artifact
    - B occurs somewhere else
    - C occurs elsewhere
    - model infers A controls B inside C

  required_structure:
    A_to_B_link: "same identified reptilian/Draconian authority explicitly or securely implied as controlling, creating, commanding, using or being served by the Greys"
    AB_to_C_link: "that same relationship explicitly or securely implied inside the base/treaty/genetic/secret-program system"

  trigger_artifact:
    title: Matrix II
    inspected_version: "1991 third edition with added material"
    finding: >
      The book contains reptilian entities, a non-reptilian higher culture that
      creates Greys, and extensive base/program material, while an editor note
      describes Reptilian humanoids as enemies of Greys. Ingredient co-presence
      therefore does not form a Draco-over-Grey chain.

  generated_session: SESSION_042
  last_reviewed: 2026-07-15
```

## Correct test

```text
A alone
+
B alone
+
C alone
        ≠ FULL
```

```text
identified A
        ↓ controls / creates / commands / uses
identified Greys B
        ↓ within
identified C system
        = FULL_LINKED_CHAIN
```

## Required fields for future candidate records

```yaml
relationship_linkage:
  A_entity:
  B_grey_group:
  A_to_B_wording:
  A_to_B_status: EXPLICIT | IMPLIED | ABSENT | CONTRADICTED | UNKNOWN
  C_system:
  AB_to_C_wording:
  AB_to_C_status: EXPLICIT | IMPLIED | ABSENT | UNKNOWN
  co_presence_only: true | false
```

## Common false positives

- a book mentions Draco in one chapter and Grey cloning in another;
- Greys are created by a different species than the named reptilians;
- reptilians are enemies or competitors of Greys;
- Greys and reptilians merely occupy the same base;
- a later editor adds the hierarchy in a note beside an earlier quotation;
- an index or table-of-contents heading is treated as the full passage;
- a secondary summary joins details that the primary text keeps separate.

## Promotion boundary

No artifact receives `FULL_LINKED_CHAIN` until exact wording identifies:

1. the reptilian/Draconian authority;
2. the Grey group;
3. their relationship;
4. the base/treaty/genetic/secret-program context;
5. a page, timestamp or tightly connected passage set;
6. the edition or version containing that wording.
