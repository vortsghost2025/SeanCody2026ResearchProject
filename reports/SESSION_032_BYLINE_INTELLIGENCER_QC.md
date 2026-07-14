# SESSION 032 — Byline / *National Intelligencer* Curator QC

> ## TOP-LEVEL STATUS
>
> ```text
> Historical acquisition variants: 2
> Continuation reports: 1
> McBride 1826 title-page byline: PRIMARY-CONFIRMED
> Reynolds 1827 title-page byline: PRIMARY-CONFIRMED
> Reynolds prior National Intelligencer publication: PRIMARY-CONFIRMED
> Exact newspaper dates/pages/columns: NOT ACQUIRED
> Free-source issue search: CLOSED / EXHAUSTED FOR CURRENT PASS
> Shared-byline distinctiveness: LOW / UNRESOLVED
> Deliberate echo: PLAUSIBLE, NOT PROVEN
> Copying edge: NOT CREATED
> Reynolds publication-carrier path: VERIFIED
> ERR-032-002: SUPPORTED NON-DIAGNOSTIC FINGERPRINT
> Entity namesake guardrail: ENFORCED
> RQ-032: SEARCHING — ARCHIVAL GAP PARKED
> Next active lane: RQ-033
> ```

## 1. Primary records surviving all variants

### McBride 1826

```yaml
title: "Symmes's Theory of Concentric Spheres: Demonstrating that the Earth Is Hollow, Habitable Within, and Widely Open about the Poles"
associated_creator: "James McBride"
printed_attribution: "By a Citizen of the United States"
place: Cincinnati
printer_publisher: "Morgan, Lodge and Fisher"
year: 1826
ia_identifier: symmesstheoryofc00mcbr
ark: ark:/13960/t9j392z40
openlibrary_edition: OL14638371M
worldcat_source_edition: "925094"
source_collection: "University of Pittsburgh Library System"
```

### Reynolds 1827

```yaml
title: "Remarks on a review of Symmes' theory, which appeared in the American quarterly review"
associated_creator: "Jeremiah N. Reynolds"
printed_attribution: "By a Citizen of the United States"
place: Washington
printer_publisher: "Gales & Seaton"
year: 1827
ia_identifier: remarksonreviewo00reyn
ark: ark:/13960/t1tf1gd11
lccn: "06040937"
source_collection: "Library of Congress"
```

The Reynolds scan and OCR confirm that the pieces `were first published in the National Intelligencer`.

## 2. Correct awareness split

The earlier wording `explicit awareness supported` was too compressed. It is now decomposed:

```yaml
awareness_of_reviewed_work: SUPPORTED
awareness_of_McBride_attribution_phrase: SUPPORTED_FROM_REYNOLDS_TEXT
awareness_of_exact_McBride_title_page_as_visual_source: INFERRED_PLAUSIBLE_NOT_PROVEN
```

Reynolds explicitly refers to the reviewed Symmes work as written by a `Citizen of the United States`. That proves awareness of the attribution phrase inside the controversy. It does not prove that he copied the exact visual title-page formula or intentionally used it as a code.

## 3. What the shared byline proves

Supported:

- both primary title pages carry the same civic anonymity formula;
- the works are adjacent in date and subject;
- Reynolds knew the reviewed work and its citizen attribution;
- Reynolds uses the same phrase on his response pamphlet;
- the match is historically worth tracking.

Not supported:

- a textual-copying edge;
- a secret-group code;
- direct instructions from McBride or Symmes;
- rarity sufficient to make the phrase diagnostic alone;
- intent to signal doctrinal loyalty.

## 4. Cross-variant disagreement

Variant A treated deliberate echo and shared-circle signaling as strongly supported.

Variant B was the safer baseline because it found unrelated period uses and retained generic anonymity as a competing explanation.

Curator state:

```yaml
primary_match: VERIFIED
historical_proximity: VERIFIED
awareness_of_reviewed_work: SUPPORTED
awareness_of_attribution_phrase: SUPPORTED
awareness_of_exact_title_page_source: INFERRED_PLAUSIBLE_NOT_PROVEN
rhetorical_echo: PLAUSIBLE_NOT_PROVEN
shared_circle_signal: PLAUSIBLE_NOT_PROVEN
copying_or_coordination: NOT_ESTABLISHED
generic_period_convention: VIABLE
```

## 5. Reynolds publication-carrier path

The primary preface establishes:

```text
American Quarterly Review criticism
        ↓
three Reynolds response numbers
first published in the National Intelligencer
        ↓
Gales & Seaton collected pamphlet, 1827
```

The pamphlet preserves No. I, No. II, and No. III and signs the responses `J. N. Reynolds`.

```yaml
BRIDGE-EDGE-003:
  status: VERIFIED_PUBLICATION_PATH_WITH_ISSUE_LEVEL_GAP
  supported:
    - PRIOR_NEWSPAPER_SERIALIZATION
    - COLLECTED_PAMPHLET_REPRINT
    - SAME_WASHINGTON_PRINT_INFRASTRUCTURE
  unresolved:
    - exact_issue_dates
    - page_and_column
    - newspaper_heading
    - newspaper_byline
    - wording_changes
```

This is a carrier edge, not evidence that Gales & Seaton endorsed Symmes's cosmology.

## 6. Continuation result and search closure

A further targeted pass failed to recover the exact installments from free/public sources.

Searches included:

- distinctive pamphlet phrases;
- numbered-response headings;
- newspaper reprint indexes;
- Virginia newspaper snippets;
- Symmes/McBride bibliographies;
- the McBride scrapbook;
- HathiTrust, Google Books, and LOC leads;
- free snippets from commercial archives.

Closest leads did not reach issue-level proof:

- *Genius of Liberty*, November 10, 1827, referencing material from an October 31 *National Intelligencer*;
- McBride scrapbook clippings with unusable OCR;
- bibliographic references to other Symmes material in the *Intelligencer* during 1827.

The gap is now parked behind:

- paid newspaper access;
- Library of Congress microfilm or issue browsing;
- institutional research assistance;
- or an exact reprint lead.

Do not repeat broad free-web cycling without a new archive or issue identifier.

## 7. Frequency-control boundary

The current result establishes that the phrase was not unique. It does not provide a reliable frequency, rarity score, or printer/topic concentration.

A stronger control would require at least five exact non-Symmes occurrences with title, year, city, printer, subject, exact title-page form, and stable scan.

Until then, `ERR-032-002` has contextual but low standalone diagnostic value.

## 8. Entity-resolution guardrail

`Jeremiah N. Reynolds` and `William Reynolds` remain distinct people.

```text
Jeremiah N. Reynolds — Symmes-related writer, advocate, lobbyist
William Reynolds — U.S. Navy officer in the Wilkes Expedition
```

No 1840 Wilkes sighting may be assigned to Jeremiah without an explicit primary source.

The permanent guardrail is methodologically valid even while the repository continues replacing secondary biographical leads with crew lists, service records, and journals.

## 9. Curator decision

```text
McBride title page: promoted
Reynolds title page: promoted
Shared phrase occurrence: promoted
Awareness of reviewed work: supported
Awareness of exact title-page visual source: plausible, not proven
Deliberate copying: not established
Rhetorical echo: plausible interpretation only
National Intelligencer prior publication: promoted
Exact newspaper installments: unresolved and archive-gated
Gales & Seaton carrier path: promoted narrowly
ERR-032-002: SUPPORTED_NONDIAGNOSTIC_FINGERPRINT
Session 032 free-source lane: closed
Next active lane: RQ-033
```

Read: `research_inbox/SESSION_032_CONTINUATION_CLOSEOUT.md`.
