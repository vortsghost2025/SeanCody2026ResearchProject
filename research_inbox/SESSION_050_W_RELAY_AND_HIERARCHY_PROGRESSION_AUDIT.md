# SESSION 050 — `W` Relay, Raw Stemma and Hierarchy Progression Audit

**Targets:** `DULCE-CAND-012`, `028`, `035`, `039`–`043`  
**Related:** `RQ-036`, `BRIDGE-036-001`  
**Mode:** raw post acquisition, relay-custody resolution, deterministic diff and exact 1989–1991 source inspection  
**Status:** OPEN — no derivation, authorship or first-composition declaration

## Objective

Session 049 resolves why agents disagreed: one searched only Hinkle/Mystery posts, while two others report a Q&A relay post by `W` inside the same thread.

Acquire the exact relay state and then test the proposed hierarchy-development sequence:

```text
1989 proto-hierarchy
        ↓
1990 intermediate hierarchy
        ↓
unknown-date mature Q&A
```

## Default continuation

Do not stop to ask whether more data is wanted. Continue until every in-scope target is acquired, falsified, blocked with an access record or the search/tool budget is exhausted.

## Priority 1 — Exact `W` relay post

Acquire from Project Avalon Thread 8393:

- raw HTML for every page/view;
- exact post ID;
- poster display name and profile URL;
- timestamp and edit markers;
- complete relay introduction;
- exact Cherry/Hinkle attribution;
- complete Q&A body;
- quotation ancestry;
- attachment and deleted-link records;
- Wayback captures;
- SHA-256 for every raw file.

Resolve:

```yaml
W_IDENTITY:
  account_name:
  profile_metadata:
  relationship_to_Hinkle:
  direct_contact_evidence:
  source_file_received:
  transmission_method:
  posting_date:
```

Do not collapse `W`, Hinkle/Mystery and Bill Ryan into one speaker.

## Priority 2 — Exact hierarchy sentences in the relay state

Return post-linked diplomatic transcriptions of:

```text
The Draco is/are the undisputed master(s)
They work for, and are controlled by the Draco
winged Draco ... top of the hierarchy
working caste / worker caste
Khaarshfashst / Karsh
levels 5-6-7
```

For each sentence return:

```yaml
sentence_id:
raw_text:
post_id:
poster:
timestamp:
HTML_location:
preceding_question:
following_context:
source_layer:
```

Allowed outcomes:

- `CONTROLLED_BY_SENTENCE_CONFIRMED_IN_W_RELAY`
- `MASTER_ONLY_CONTROL_SENTENCE_ABSENT`
- `MIXED_QA_STATES_ACROSS_POSTS`
- `SEARCH_SNIPPET_FALSE_POSITIVE`
- `UNKNOWN`

## Priority 3 — Raw Avalon / Branton corpus and deterministic diff

Store:

1. raw Avalon `W` relay Q&A;
2. earliest available Branton Chapter 11 state;
3. 1996-header state;
4. Bibliotecapleyades state;
5. whale.to state;
6. Archive.org text/PDF state.

Produce:

- diplomatic transcriptions;
- normalized transcriptions with policy;
- sentence-indexed JSON;
- character diff;
- punctuation-normalized diff;
- capitalization-normalized diff;
- sentence-order diff;
- difference CSV;
- file hashes.

Test:

```text
H1 Avalon derived from Branton
H2 Branton derived from an Avalon-like source
H3 both descend from a common ancestor
H4 differences are rendering/transcription only
```

No hypothesis may be marked `REJECTED` or `PROVED` without the raw corpus and reproducible output.

## Priority 4 — LeVesque 1989 exact artifact

Acquire the earliest exact state of Jason Bishop III / Tal LeVesque, `The Dulce Base`.

Return:

- title and byline;
- first date and date basis;
- carrier and issue;
- complete text;
- exact Grey/Draco/Reptoid wording;
- page or line location;
- archive provenance;
- comparison against later mirrors.

Test the reported passages:

```text
Mercenary Agents for another Extraterrestrial Culture (The DRACO)
The Greys and Reptoids are in league ... tension
```

Classify:

- `PROTO_HIERARCHY_EXPLICIT_AGENT_FOR_DRACO`
- `ALLIANCE_TENSION_ONLY`
- `LATER_MIRROR_ADDITION`
- `UNKNOWN`

## Priority 5 — `Pasturing and Use of Surface Earth Humans`

Acquire the complete ten-page text attributed to LeVesque/Bishop in the earliest *Matrix II* state.

Return:

- exact edition;
- title/copyright pages;
- section pages;
- full hierarchy wording;
- Draco caste structure;
- Grey mercenary language;
- citations/source list;
- relation to `The Dulce Base` and Q&A;
- version differences between 1990 and 1991 editions.

Do not use a later Dulce Book excerpt as proof of the *Matrix II* wording without alignment.

## Priority 6 — Tilton first edition

Test the reported object:

```text
Christa Tilton
The Bennewitz Papers
Crux Publications, Tulsa
1991
85 pages
reported Tom Benson collection / one OCLC holding
```

Acquire:

- OCLC record;
- title/copyright pages;
- complete contents;
- exact fabrication passage;
- provenance;
- comparison with 1992/1994 96-page Inner Light editions.

Determine whether the Castello-fabrication statement appears in the 1991 state or was added later.

## Priority 7 — Nippon Television March 24, 1990

Acquire the Japanese broadcast reportedly featuring LeVesque:

- network and program title;
- Japanese title;
- broadcast date/time;
- producer;
- segment credits;
- LeVesque interview transcript;
- Hayakawa role;
- recording or archive holding;
- distinction from Hinkle's claimed model/illustration program.

## Priority 8 — Lear full interview

Acquire raw video/transcript and timestamps for:

- retyping and redrawing;
- female source;
- Mr. X;
- hidden boxes;
- recovery expeditions;
- Hamilton/LeVesque participation;
- claimed dates.

Treat as participant self-attestation unless corroborated.

## Priority 9 — Sensitive credibility claims

Do not use third-party mental-health labels as historical proof. Exclude amateur diagnosis and hearsay medical claims from the authorship decision.

Test credibility through:

- original document provenance;
- internal consistency;
- external records;
- contemporaneous statements;
- artifact production.

## Required deliverables

1. `W` relay-post record.
2. Exact hierarchy-sentence map.
3. Raw hashed Avalon/Branton corpus.
4. Deterministic diff package.
5. 1989 proto-hierarchy artifact record.
6. 1990 intermediate-hierarchy artifact record.
7. Tilton first-edition record.
8. Nippon broadcast record.
9. Lear interview record.
10. Failed-search/access log.
11. Recommendation only; curator promotion required.

## Stop rules

Do not:

- search only one username and generalize to the thread;
- assign relay text directly to Hinkle without the relay layer;
- infer stemma direction from punctuation alone;
- call 2010 a pre-1996 composition date;
- call later mirrors independent sources;
- use a later excerpt as proof of an earlier edition;
- authenticate Castello through participant belief;
- use unverified health allegations as credibility adjudication;
- stop to ask whether more data is wanted.

## Copy-paste agent prompt

> Read `AGENTS.md`, `docs/AGENT_CONTINUATION_POLICY.md`, `docs/METHODOLOGY.md`, `research_questions/RQ-036-REPTILIAN-SYNTHESIS-GREY-FUSION.md`, `reports/SESSION_049_AVALON_RELAY_AND_STEMMA_CROSS_QC.md`, `graph/textual_stemma/CASTELLO_QA_AVALON_BRANTON_STEMMA.md`, and `ERR-036-026` through `ERR-036-028`. Execute `research_inbox/SESSION_050_W_RELAY_AND_HIERARCHY_PROGRESSION_AUDIT.md`. Continue without asking permission. First acquire the complete raw `W` relay post from Project Avalon Thread 8393 with post ID, timestamp, full Q&A, attribution header and hashes. Confirm or falsify the exact `controlled by the Draco` sentence in that relay state. Then create a reproducible Avalon-versus-Branton corpus and diff. Separately acquire the exact 1989 `The Dulce Base` artifact, the complete 1990 `Pasturing and Use of Surface Earth Humans` section, the 1991 Tilton Crux edition and the March 24, 1990 Nippon Television program. Preserve relay, participant, editor and mirror layers separately. Do not declare derivation direction or authorship without raw objects.
