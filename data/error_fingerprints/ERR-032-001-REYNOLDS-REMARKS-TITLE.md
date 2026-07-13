# ERR-032-001 — Reynolds 1827 Title Mutation

```yaml
ERROR_FINGERPRINT:
  id: ERR-032-001
  status: OPEN_CANDIDATE
  related_bridge: BRIDGE-032-003

  authoritative_form:
    source: "Library of Congress catalogue acquisition"
    title: "Remarks on a review of Symmes' theory, which appeared in the American quarterly review"
    loc_item: "06040937"

  mutated_form:
    title: "Remarks of Symmes' Theory Which Appeared in the American Quarterly Review"

  mutation:
    - "on a review of" collapsed to "of"
    - work reframed from response-to-review into apparent freestanding exposition

  suspected_mechanism:
    - SHARED_ERROR
    - BIBLIOGRAPHIC_SHORTENING
    - MIRROR_REPLICATION

  evidence_state:
    authoritative_catalogue_form: SUPPORTED_FROM_ACQUISITION
    at_least_one_public_mutated_example: SUPPORTED
    copying_sequence: NOT_ESTABLISHED
    earliest_mutated_occurrence: UNKNOWN

  generated_session: SESSION_030
  last_reviewed: 2026-07-13
```

## Why the mutation matters

This is not merely punctuation or capitalization. The two titles imply different document types:

```text
correct: remarks ON A REVIEW of Symmes' theory
mutated: remarks OF Symmes' theory
```

The correct form identifies a publication responding to a prior review. The mutated form obscures the review-and-response chain and makes the pamphlet sound like an independent treatise.

## Current evidence

The acquisition reports the mutated form across several secondary and mirror sites. A web search during curator review also returned the shortened form in a current Wikipedia result.

This supports recording the mutation as a candidate fingerprint. It does not yet establish that all sites copied one another directly.

## Promotion test

To promote this into a documented copied-error chain, collect:

1. dated snapshots or archived versions for each occurrence;
2. exact wording and publication date;
3. the earliest located mutation;
4. evidence of mirroring, attribution, or shared source text;
5. independent catalogues to determine whether the variant predates the web;
6. negative results from authoritative bibliographies using the correct title.

## Allowed synthesis language

Allowed:

> A materially shortened title variant circulates publicly and obscures that Reynolds's pamphlet responds to a review.

Not yet allowed:

> All listed websites copied the error from one known source.
