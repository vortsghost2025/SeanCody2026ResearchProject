# SESSION 046 — Castello Persona, Hinkle Role and Packet-Seeding Acquisition Brief

**Targets:** `DULCE-CAND-012`, `ERR-036-010`, `ERR-036-012`, `ERR-036-013`  
**Related:** `RQ-036`, `BRIDGE-036-001`  
**Mode:** exact confession-source acquisition, participant-role reconstruction and manufactured-independence test  
**Status:** OPEN — no origin declaration

## Objective

The hierarchy-content question is already resolved at the text level.

The next task is to authenticate or falsify the quoted provenance claims that:

1. Thomas Edwin Castello was a created persona;
2. Cherry Hinkle / Ann or Anne West answered questions as if she were Castello;
3. Tal LeVesque corrected, mixed and supplemented her material;
4. LeVesque distributed roughly one hundred packets to authors and lecturers to create the appearance of multiple sources;
5. Branton compiled, sequenced and possibly further edited the resulting material.

## Default continuation rule

Do not stop to ask whether more data is wanted. Follow every in-scope lead until:

- the exact source object is acquired;
- the lead is falsified;
- access is blocked and documented;
- search/tool budget is exhausted.

Read `docs/AGENT_CONTINUATION_POLICY.md`.

## Priority 1 — `TEC is a creation`

Acquire the exact source containing:

> `TEC (Thomas Edwin Castello) is a creation.`

Return:

```text
sender and recipient
exact date
email headers or recording metadata
complete preceding and following messages
original spelling and punctuation
archive / collector provenance
publication or book reproducing it
edition and page
image or stable exact locator
```

Determine whether the quote is:

- original email text;
- a transcription by Adam Gorightly;
- paraphrase in a later article;
- quotation copied from another website;
- altered or truncated.

## Priority 2 — Hinkle / Ann West answer role

Acquire the exact source for the statement that a woman identified as Ann/Anne West or Cherry Hinkle:

> answered the questions as if she were TEC.

Return:

- exact name form used in the source;
- speaker and recipient;
- date;
- complete context;
- which questions or text were being discussed;
- whether the statement applies to the entire Q&A or one version;
- Hinkle's own response or competing account;
- relationship among Hinkle, LeVesque, Mary Martin, John Lear and Branton.

Do not infer that Hinkle wrote every unsigned answer.

## Priority 3 — LeVesque mixing/editing statement

Acquire the exact source for the reported statement that LeVesque:

- took material or `rantings` from Ann West / Cherry Hinkle;
- corrected material he considered wrong;
- added his own research;
- mixed it together;
- used it as the basis for original Dulce Base articles.

Return the complete paragraph and identify exactly which two articles or documents are meant.

Compare against:

- Bishop III, *The Dulce Base*;
- O'Connell/TAL article;
- Hamilton/TAL *The Deep Dark Secret at Dulce*;
- Castello Q&A;
- *The Dulce Book*.

## Priority 4 — One-hundred-packet distribution

Acquire the exact source for the claimed packet strategy.

Return:

```text
exact quotation
speaker
recipient
exact date
packet count
packet description
mailing period
named recipients
sample contents
cover letter or envelope
recipient acknowledgements
later talks/articles/books traceable to packet
```

Search for surviving packets in:

- Adam Gorightly papers or correspondence;
- Cherry Hinkle / Ann West materials;
- Norio Hayakawa collections;
- Bill Hamilton / UFORCES materials;
- John Lear papers;
- Branton correspondence;
- Val Valerian / Leading Edge collections;
- Bill Cooper acknowledgements and papers;
- private UFO archive inventories;
- conference-speaker collections.

## Priority 5 — Adam Gorightly source audit

Acquire the exact edition and pages of *Saucers, Spooks and Kooks* or another Gorightly work containing the LeVesque correspondence.

Return:

```text
full title
edition
publisher
publication year
ISBN
chapter
page range
verbatim compliant excerpts
whether original email images are reproduced
Gorightly's description of provenance
correspondence date
```

Separate:

- Gorightly's narration;
- direct LeVesque quotation;
- quoted Hinkle material;
- Gorightly inference;
- later web summary.

## Priority 6 — Branton editorial role

Search for Branton correspondence or statements that identify:

- what material he received from LeVesque;
- whether he interviewed anyone;
- who wrote the questions;
- whether he edited the answers;
- when Chapter 11 was assembled;
- whether he knew Castello was a persona;
- whether he received Hinkle material directly.

A 2009 forum claim that Branton fabricated sections is a hostile secondary lead only. Acquire the full thread, poster identity claims, date, quoted version, and any response by Branton or participants.

## Priority 7 — Independence graph

For every named recipient or downstream author create:

| Recipient/source | Packet receipt evidence | Date | Later artifact | Shared wording | Claimed direct knowledge | Dependency result |
|---|---|---:|---|---|---|---|
|  |  |  |  |  |  |  |

Use:

- `DIRECT_PACKET_RECIPIENT`
- `PROBABLE_PACKET_RECIPIENT`
- `CITED_LEVESQUE`
- `DERIVATIVE_OF_RECIPIENT`
- `INDEPENDENT_OF_PACKET_NOT_ESTABLISHED`
- `NO_DEPENDENCY_FOUND`
- `UNKNOWN`

## Required source-status labels

- `CONFIRMED_PRIMARY`
- `PRIMARY_ITEM_METADATA_ONLY`
- `DIRECT_QUOTE_IN_VERIFIED_SECONDARY`
- `SECONDARY_TRANSCRIPTION`
- `SECONDARY_PARAPHRASE`
- `HOSTILE_PARTICIPANT_CLAIM`
- `UNVERIFIED_WEB_REPETITION`
- `UNKNOWN`

## Stop rules

Do not:

- call Castello fictional solely because multiple websites say so;
- treat Gorightly's paraphrase as LeVesque's exact wording;
- assign every Q&A sentence to Hinkle;
- assign every unsigned edit to Branton;
- count packet recipients as independent witnesses;
- treat a recipient repeating a packet as observational convergence;
- claim all Dulce lore came from one packet without item-level comparison;
- stop to ask whether the curator wants more data;
- claim repository synchronization unless actually performed.

## Deliverables

1. Exact confession-source artifact or bounded failure report.
2. Hinkle-role source record and competing-account table.
3. Packet-seeding source record.
4. Recipient/dependency graph.
5. Branton editor-role record.
6. Exact Gorightly edition/page record.
7. Failed-search and archive-contact log.
8. Recommendation only; no canonical promotion without curator review.

## Copy-paste agent prompt

> Read `AGENTS.md`, `docs/AGENT_CONTINUATION_POLICY.md`, `docs/METHODOLOGY.md`, `research_questions/RQ-036-REPTILIAN-SYNTHESIS-GREY-FUSION.md`, `graph/transmissions/CASTELLO_QA_AUTHORSHIP_PROVENANCE_CANDIDATE.md`, `reports/SESSION_045_DATE_AUTHORSHIP_CROSS_QC.md`, and error fingerprints `ERR-036-010` through `ERR-036-014`. Execute `research_inbox/SESSION_046_CONFESSION_PACKET_AND_AUTHORSHIP_ACQUISITION_BRIEF.md`. Do not stop to ask whether more data is wanted. Acquire the exact original sources for the LeVesque `TEC is a creation`, Hinkle answering as TEC, material-mixing and one-hundred-packet statements. Return complete context, headers, dates, edition/pages, provenance, participant disagreements, packet recipients and downstream dependency analysis. Separate original quotation, transcription, paraphrase and later web repetition. Do not declare a canonical authorship or hoax edge without the exact artifact.
