# BRIDGE-EDGE-003 — *National Intelligencer* → Reynolds 1827 Pamphlet

```yaml
TRANSMISSION_EDGE:
  id: BRIDGE-EDGE-003
  status: VERIFIED_PUBLICATION_PATH_WITH_ISSUE_LEVEL_GAP
  canonical: true

  from:
    type: NEWSPAPER_SERIALIZATION
    publication: "National Intelligencer"
    place: Washington
    pieces: 3
    creator_signature: "J. N. Reynolds"
    exact_issue_dates: UNKNOWN
    exact_pages_columns: UNKNOWN
    verification: PRIMARY_AUTHOR_PREFACE_AND_INTERNAL_NUMBER_STRUCTURE

  to:
    type: COLLECTED_PAMPHLET
    title: "Remarks on a review of Symmes' theory, which appeared in the American quarterly review"
    creator_catalogue: "Jeremiah N. Reynolds"
    printed_attribution: "By a Citizen of the United States"
    place: Washington
    printer: "Gales & Seaton"
    year: 1827
    ia_identifier: remarksonreviewo00reyn
    ark: ark:/13960/t1tf1gd11
    lccn: "06040937"

  edge_type:
    - SERIALIZATION_TO_PAMPHLET
    - REPRINT_PATH
    - SHARED_PRINT_INFRASTRUCTURE

  evidence_class: A_FOR_PRIOR_PUBLICATION_RELATION
  issue_level_evidence_class: UNKNOWN
  confidence: HIGH_FOR_PATH

  scope: >
    Reynolds's prefatory note states that the following numbers were written in reply
    to the American Quarterly review and were first published in the National
    Intelligencer. The collected pamphlet is printed by Gales & Seaton in Washington.
    Its OCR preserves the transitions to No. II and No. III and signatures by J. N.
    Reynolds. Exact newspaper issue dates, pages, columns, headings, and serialization
    wording have not yet been recovered.

  exclusions:
    - This edge does not establish editorial endorsement of Symmes's theory.
    - It does not establish that every pamphlet word appeared identically in the newspaper.
    - It does not establish a McBride-to-Reynolds copying edge.
    - It does not establish exact public exposure dates until the issues are found.

  generated_session: SESSION_032
  last_reviewed: 2026-07-13
```

## Primary statement

The pamphlet preface says the numbers:

> `were first published in the National Intelligencer`

It then describes three parts:

1. a physical view of the theory;
2. polar-sea inquiry independent of speculation;
3. the national and scientific expedition case.

## Internal serialization structure

The collected text preserves:

```text
No. I — reply begins
        ↓ signed J. N. Reynolds
No. II — To the Editor of the American Quarterly Review
        ↓ signed J. N. Reynolds
No. III — To the Editor of the American Quarterly Review
```

This confirms that the pamphlet collects a numbered response series. The newspaper originals are still required to identify the exact publication schedule and any editorial or textual changes.

## Carrier significance

```text
American Quarterly Review controversy
        ↓
Washington newspaper serialization
        ↓
collected pamphlet by Gales & Seaton
        ↓
portable artifact for broader public and institutional circulation
```

The material format changes from ephemeral periodical response to durable pamphlet. That transformation may affect audience, authority, and later citation even without changing the doctrine.

## Next promotion layer

Already verified:

- prior newspaper publication;
- three-part structure;
- collected pamphlet relation.

Still required:

- each issue date;
- page and column;
- heading and signature;
- surrounding editorial framing and advertisements;
- exact newspaper-to-pamphlet textual comparison.
