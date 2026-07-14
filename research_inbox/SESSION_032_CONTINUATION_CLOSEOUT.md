# SESSION 032 — Continuation Closeout

**Targets:** `BRIDGE-EDGE-003`, `ERR-032-002`, `BRIDGE-032-003`, `RQ-032`  
**Mode:** failed-search preservation and curator boundary  
**Status:** CLOSED FOR FREE-WEB SEARCH — issue-level recovery requires restricted archive access

## Result

The primary pamphlet claim remains verified:

> The three Reynolds response numbers `were first published in the National Intelligencer`.

The collected pamphlet preserves three numbered sections signed `J. N. Reynolds`, but the exact newspaper originals were not recovered.

```yaml
BRIDGE-EDGE-003:
  status: VERIFIED_PUBLICATION_PATH_WITH_ISSUE_LEVEL_GAP
  canonical: true
  exact_issues: NOT_ACQUIRED
  free_source_search: EXHAUSTED_FOR_CURRENT_PASS
```

## Search boundary

Targeted searches covered:

- distinctive phrases from the pamphlet;
- `To the Editor of the American Quarterly Review`;
- `J. N. Reynolds` with Symmes and *National Intelligencer*;
- newspaper reprint indexes and snippets;
- Virginia newspaper leads;
- Symmes and McBride bibliographies;
- McBride scrapbook references;
- Library of Congress and Chronicling America leads;
- Google Books and HathiTrust references;
- free snippets from commercial newspaper archives.

## Closest leads

### *Genius of Liberty*, November 10, 1827

A partial lead reports material reprinted from the *National Intelligencer* of approximately October 31, 1827 discussing Reynolds and Symmes's theory. The accessible snippet is insufficient to identify it as one of the three response numbers.

**Status:** `UNVERIFIED_REPRINT_LEAD`.

### McBride scrapbook

A digitized scrapbook contains *National Intelligencer* clippings related to Symmes, Hollow Earth, and Reynolds. OCR and image quality did not permit reliable isolation of the three serialized numbers.

**Status:** `PRIMARY_CONTAINER_LEAD — ARTICLE IDENTIFICATION INCOMPLETE`.

### Continuing Symmes material

Bibliographic leads indicate that Symmes-related material continued to appear in the *Intelligencer* during 1827. Exact item-level records were not acquired in this pass.

## Missing issue-level fields

```text
publication date
page
column
article heading
signature/byline
opening and closing lines
surrounding advertisements or editorials
newspaper-to-pamphlet textual changes
whether the citizen byline appeared in serialization
```

## Access requirement

Further recovery should use one of:

- a complete paid newspaper archive run;
- Library of Congress microfilm or on-site digital access;
- direct issue browsing for March–November 1827;
- a high-quality transcription of the McBride scrapbook;
- an institutional research request.

Do not continue repeating broad free-web searches unless a new archive, index, or exact issue lead appears.

## Byline boundary

Both primary title pages use `By a Citizen of the United States`.

The correct evidentiary split is:

```yaml
shared_phrase_occurrence: VERIFIED
awareness_of_reviewed_work: SUPPORTED
awareness_of_McBride_attribution_phrase: SUPPORTED_FROM_REYNOLDS_TEXT
awareness_of_exact_McBride_title_page_as_visual_source: INFERRED_PLAUSIBLE_NOT_PROVEN
deliberate_echo: PLAUSIBLE_NOT_PROVEN
shared_circle_signaling: PLAUSIBLE_NOT_PROVEN
generic_anonymity_convention: VIABLE
copying_or_coordination_edge: NOT_ESTABLISHED
```

The phrase is a supported but non-diagnostic fingerprint. Its contextual value comes from proximity, shared controversy, and Reynolds's textual reference—not from rarity alone.

## Entity guardrail

`Jeremiah N. Reynolds` and `William Reynolds` remain distinct entities. No Wilkes Expedition observation may be assigned to Jeremiah without a primary source explicitly naming him.

## Curator decision

```text
Session 032 broad/free-source work: closed
Publication carrier: retained as verified
Issue-level serialization records: unresolved
Shared byline: retained as supported non-diagnostic fingerprint
Deliberate echo: plausible interpretation only
Copying edge: not created
RQ-032: SEARCHING, archival gap parked
Next active public lane: RQ-033 polar observability
```
