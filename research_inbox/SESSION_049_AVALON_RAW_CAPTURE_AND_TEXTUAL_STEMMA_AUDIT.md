# SESSION 049 — Avalon Raw Capture and Textual-Stemma Audit

**Targets:** `DULCE-CAND-012`, `DULCE-CAND-028`, `DULCE-CAND-035`, `DULCE-CAND-036`  
**Related:** `RQ-036`, `BRIDGE-036-001`  
**Mode:** raw carrier acquisition, reproducible transcription and textual stemma  
**Status:** OPEN — no derivation direction or authorship declaration

## Objective

Session 048 establishes a November 2010 Project Avalon public Q&A carrier containing mature hierarchy wording. The remaining decisive question is textual:

> Is the Avalon state a derivative copy of Branton Chapter 11, a distinct state descending from a common source, or evidence that Branton edited an earlier Hinkle-associated source?

Resolve this using reproducible raw captures and deterministic comparison, not prose impressions.

## Default continuation

Do not stop to ask whether more data is wanted. Continue until each target is acquired, falsified, blocked with an access record or the tool/search budget is exhausted.

## Priority 1 — Complete raw Avalon capture

Acquire every available state of Project Avalon Thread 8393:

```text
showthread
printthread
archive view
Wayback captures
mobile/text views
quoted copies in replies
```

Return:

- complete HTML files;
- capture URLs and timestamps;
- thread page numbers;
- post IDs;
- poster names and attribution basis;
- original post timestamps;
- edit markers;
- attachment URLs;
- deleted or inaccessible resources;
- cryptographic hashes for every raw file.

Do not rely on search-result snippets as the final corpus.

## Priority 2 — Exact Q&A extraction

Extract the complete Hinkle/Avalon Q&A body into:

1. diplomatic transcription preserving spelling, punctuation, capitalization, brackets and line breaks;
2. normalized transcription with a documented normalization policy;
3. sentence-indexed table;
4. source map linking every sentence to post ID and raw HTML location.

Include the full context surrounding:

```text
working caste
white Draco
undisputed master / masters
controlled by the Draco
Khaarshfashst / Karsh
levels 5-6-7
Nightmare Hall
```

## Priority 3 — Earliest Branton carrier capture

Acquire the earliest available raw Branton/Chapter 11 states separately:

- early BBS/manuscript claim;
- claimed 1991 state;
- 1996 header state;
- earliest web mirror;
- Bibliotecapleyades;
- whale.to;
- Archive.org text/PDF.

For each return:

```text
raw file
capture date
claimed publication date
date basis
file header or metadata
chapter title
complete Q&A text
compiler notes
hash
```

Do not treat a later upload date as the composition date.

## Priority 4 — Reproducible diff

Produce four comparisons:

1. raw character diff;
2. whitespace-normalized diff;
3. punctuation/capitalization-normalized diff;
4. sentence/order diff.

Classify every difference:

```yaml
difference_type:
  - WORD_ADDITION
  - WORD_DELETION
  - WORD_SUBSTITUTION
  - NUMBER_AGREEMENT
  - CAPITALIZATION
  - PUNCTUATION
  - BRACKET_STYLE
  - QUOTATION_MARK
  - EXPLICIT_BRANTON_GLOSS
  - QUESTION_ORDER
  - PARAGRAPH_ORDER
  - OCR_OR_TRANSCRIPTION_ERROR
  - UNKNOWN
```

Return machine-readable CSV/JSON plus a human-readable report.

## Priority 5 — Direction-of-edit tests

Test, do not assume:

```text
H1: Hinkle copied Branton and removed/altered glosses
H2: Branton edited a Hinkle-associated source
H3: both descend from a third common source
H4: differences are rendering/transcription artifacts
```

Evidence that can discriminate:

- signed Branton notes embedded in one carrier only;
- shared errors;
- corrections that create or remove grammatical coherence;
- sentence-order changes;
- unique typos preserved downstream;
- contemporaneous citations to one state;
- file metadata and capture chronology.

Valid outcomes:

- `AVALON_DERIVED_FROM_BRANTON`
- `BRANTON_DERIVED_FROM_AVALON_LIKE_SOURCE`
- `COMMON_ANCESTOR_MOST_LIKELY`
- `RENDERING_DIFFERENCES_ONLY`
- `STEMMA_UNRESOLVED`

## Priority 6 — Separate Hinkle Repton corpus

Capture the full Adrian Dorsey / Hinkle exchange and preserve it as a separate artifact.

Return:

- complete question/answer sequence;
- post IDs and timestamps;
- `Repton`, `Dracon`, `Kaarsh`, `King of This World`, Tibet, Telos and Mt. Shasta passages;
- speaker-turn reconstruction;
- whether the text is Hinkle's direct answer or an intermediary transcription;
- relation to *My Fated Life* and the 2012 interview.

Do not merge this corpus into the original Castello Q&A.

## Priority 7 — Lear 2008 full transcript

Acquire the full Project Camelot/Avalon interview transcript and video timestamps for Lear's claims about:

- retyping and redrawing;
- the female source;
- Mr. X;
- hidden boxes;
- six or more recovery expeditions;
- Hamilton and possible LeVesque participation;
- dates of Castello disappearance and box searches.

Classify each as participant self-attestation unless corroborated by an object or another direct participant.

## Priority 8 — 2013 Hinkle and recovery-project states

Acquire full raw captures of:

- Hinkle's April 1991 death/impersonation statement;
- the `Dulce Project 2013` recovery thread;
- claimed box contents;
- organizer identity;
- funding requests;
- outcome and follow-up.

Separate Hinkle's own words from organizer or commenter claims.

## Priority 9 — Persisting material-object targets

Continue searching for:

- 1987/1988 Castello-attributed letters;
- Japanese television special;
- original drawings with custody;
- hidden-box documentation;
- source packets;
- Castello identity records;
- Tilton 1987 manuscript;
- July 1990 newsletter.

Record bounded failures rather than repeating possession claims.

## Source labels

- `CONFIRMED_PRIMARY`
- `RAW_WEB_CARRIER`
- `PARTICIPANT_SELF_ATTESTATION`
- `DIRECT_QUOTE_IN_VERIFIED_SECONDARY`
- `SECONDARY_TRANSCRIPTION`
- `SECONDARY_PARAPHRASE`
- `PARTICIPANT_POSSESSION_CLAIM`
- `UNVERIFIED_WEB_REPETITION`
- `UNKNOWN`

## Stop rules

Do not:

- infer derivation direction from snippets;
- call 2010 a pre-1996 composition date;
- merge the Repton corpus into the original Q&A;
- treat forum formatting as original punctuation without raw HTML;
- count signed Branton notes as Castello answer voice;
- treat Lear's account as authentication of Castello;
- treat Hinkle or LeVesque as sole author from participant testimony;
- claim physical corroboration without an object;
- stop to ask whether more data is wanted.

## Deliverables

1. Raw Avalon carrier archive with hashes.
2. Diplomatic and normalized Hinkle Q&A transcriptions.
3. Raw Branton carrier archive with hashes.
4. Machine-readable and human-readable diffs.
5. Textual-stemma hypothesis ranking.
6. Separate Hinkle Repton corpus record.
7. Lear participant-account record.
8. 2013 Hinkle/recovery-project record.
9. Material-artifact failure/acquisition report.
10. Recommendation only; curator promotion required.

## Copy-paste agent prompt

> Read `AGENTS.md`, `docs/AGENT_CONTINUATION_POLICY.md`, `docs/METHODOLOGY.md`, `research_questions/RQ-036-REPTILIAN-SYNTHESIS-GREY-FUSION.md`, `graph/chronologies/CASTELLO_BRANTON_QA_VERSION_MATRIX.md`, `graph/transmissions/CASTELLO_QA_AUTHORSHIP_PROVENANCE_CANDIDATE.md`, `graph/transmissions/HINKLE_LEVESQUE_DISTRIBUTION_MODELS.md`, `reports/SESSION_048_AVALON_QA_TEXTUAL_STATE_CROSS_QC.md`, and `ERR-036-023` through `ERR-036-025`. Execute `research_inbox/SESSION_049_AVALON_RAW_CAPTURE_AND_TEXTUAL_STEMMA_AUDIT.md`. Continue without asking permission. Acquire complete raw Project Avalon Thread 8393 and earliest Branton Q&A carrier states, store hashes, produce diplomatic and normalized transcriptions, and generate deterministic character/sentence diffs. Test Avalon-derived-from-Branton, Branton-derived-from-earlier-source, common-ancestor and rendering-only hypotheses. Preserve the Hinkle Repton/King-of-World exchange as a separate corpus. Do not infer direction from snippets or call the 2010 public carrier a pre-1996 composition date.
