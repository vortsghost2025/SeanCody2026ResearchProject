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
    creator_signature_in_collected_text: "J. N. Reynolds"
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

  search_state:
    free_source_search: EXHAUSTED_FOR_CURRENT_PASS
    next_access_required:
      - PAID_NEWSPAPER_ARCHIVE
      - LIBRARY_OF_CONGRESS_ISSUE_OR_MICROFILM_ACCESS
      - EXACT_REPRINT_OR_SCRAPBOOK_IDENTIFICATION

  scope: >
    Reynolds's prefatory note states that the following numbers were written in reply
    to the American Quarterly review and were first published in the National
    Intelligencer. The collected pamphlet is printed by Gales & Seaton in Washington.
    Its OCR preserves the transitions to No. II and No. III and signatures by J. N.
    Reynolds. Exact newspaper issue dates, pages, columns, headings, bylines, and
    serialization wording remain unrecovered after a bounded free-source search.

  exclusions:
    - This edge does not establish editorial endorsement of Symmes's theory.
    - It does not establish that every pamphlet word appeared identically in the newspaper.
    - It does not establish a McBride-to-Reynolds copying edge.
    - It does not establish that the citizen byline appeared in the newspaper versions.
    - It does not establish exact public exposure dates until the issues are found.

  generated_session: SESSION_032
  updated_session: SESSION_032_CONTINUATION
  last_reviewed: 2026-07-13
```

## Primary statement

The pamphlet preface says the numbers:

> `were first published in the National Intelligencer`

It describes three parts:

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

This confirms that the pamphlet collects a numbered response series. The newspaper originals are still required to identify the exact schedule, headings, editorial framing, and textual changes.

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

The material format changes from ephemeral newspaper response to durable pamphlet. That transformation may alter audience, authority, and later citation without implying that the printer endorsed the doctrine.

## Continuation search result

The free/public continuation did not recover exact installments.

Closest leads:

- a *Genius of Liberty* reprint lead dated November 10, 1827, referring to material from the *National Intelligencer* around October 31, 1827;
- a McBride scrapbook containing relevant *Intelligencer* clippings but with insufficient OCR and image resolution;
- bibliographic indications of other Symmes-related *Intelligencer* material in 1827.

None is currently sufficient to identify No. I, II, or III at issue level.

Read: `research_inbox/SESSION_032_CONTINUATION_CLOSEOUT.md`.

## Current boundary

Already verified:

- prior newspaper publication;
- three-part structure;
- collected-pamphlet relation;
- Washington/Gales & Seaton print pathway.

Still unresolved:

- each issue date;
- page and column;
- heading and newspaper signature;
- surrounding editorials and advertisements;
- whether the citizen byline appeared in serialization;
- exact newspaper-to-pamphlet textual comparison.

Do not repeat broad free-web searches unless a new archive or exact issue lead appears.
