# ERR-032-001 — Reynolds 1827 Title Mutation

```yaml
ERROR_FINGERPRINT:
  id: ERR-032-001
  status: OPEN_CANDIDATE_PRIMARY_FORM_CONFIRMED
  related_bridge: BRIDGE-032-003

  authoritative_form:
    source:
      - "Library of Congress catalogue"
      - "Internet Archive LOC-derived title-page scan"
    title: "Remarks on a review of Symmes' theory, which appeared in the American quarterly review"
    loc_item: "06040937"
    ia_identifier: remarksonreviewo00reyn

  mutated_forms:
    - "Remarks of Symmes' Theory Which Appeared in the American Quarterly Review"
    - "Remarks on Symmes' Theory"

  mutation:
    - "on a review of" collapsed to "of" or omitted
    - response-to-review structure obscured
    - work reframed as an apparent freestanding exposition

  suspected_mechanisms:
    - SHARED_ERROR
    - BIBLIOGRAPHIC_SHORTENING
    - MIRROR_REPLICATION
    - INDEPENDENT_SHORTENING

  evidence_state:
    authoritative_primary_form: CONFIRMED
    at_least_one_public_mutated_example: SUPPORTED
    multiple_reported_mutated_examples: LEAD
    copying_sequence: NOT_ESTABLISHED
    earliest_mutated_occurrence: UNKNOWN

  generated_session: SESSION_030
  updated_session: SESSION_031
  last_reviewed: 2026-07-13
```

## Why the mutation matters

```text
primary:
Remarks ON A REVIEW of Symmes' theory...

mutated:
Remarks OF Symmes' theory...
```

The primary form identifies a direct response in a print controversy. The mutated form hides that relationship and makes the pamphlet appear to be an independent treatise.

The pamphlet preface strengthens the distinction: Reynolds says the pieces were written in reply to an *American Quarterly* review and first published in the *National Intelligencer*.

## Current evidence

Confirmed:

- the exact primary title through the LOC-derived scan and OCR;
- one or more public shortened variants;
- material change in the apparent document type.

Not confirmed:

- the first person or bibliography to introduce the shortened form;
- a single copying chain connecting all current sites;
- whether some variants are independent catalogue abbreviations.

## Promotion test

Collect:

1. dated catalogue and bibliography occurrences;
2. archived snapshots of web occurrences;
3. exact wording and attribution;
4. earliest located mutation;
5. evidence of mirroring or shared source text;
6. independent abbreviations that may explain parallel shortening.

## Allowed synthesis language

Allowed:

> A materially shortened title variant circulates publicly and obscures that Reynolds's pamphlet responds to a review.

Not yet allowed:

> All listed websites copied the error from one known source.
