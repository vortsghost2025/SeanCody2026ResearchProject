# SESSION 032 — Byline / *National Intelligencer* Curator QC

> ## TOP-LEVEL STATUS
>
> ```text
> Historical acquisition variants: 2
> McBride 1826 title-page byline: PRIMARY-CONFIRMED
> Reynolds 1827 title-page byline: PRIMARY-CONFIRMED
> Reynolds prior National Intelligencer publication: PRIMARY-CONFIRMED
> Exact newspaper dates/pages/columns: NOT ACQUIRED
> Shared-byline distinctiveness: LOW / UNRESOLVED
> Deliberate echo: PLAUSIBLE, NOT PROVEN
> Copying edge: NOT CREATED
> Reynolds publication-carrier path: SUPPORTED
> ERR-032-002: SUPPORTED FINGERPRINT, NON-DIAGNOSTIC ALONE
> RQ-032: SEARCHING
> ```

## 1. Primary records surviving both variants

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

Internet Archive independently confirms the item, date, publisher, associated creators, identifier, ARK, Open Library edition, and source-edition WorldCat number.

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

The scan and OCR confirm the preface statement that the numbers were written in reply to the *American Quarterly* and `were first published in the National Intelligencer`.

## 2. What the shared byline proves

Supported:

- both primary title pages carry the same civic anonymity formula;
- the works are adjacent in date and subject;
- Reynolds explicitly identifies the reviewed Symmes work as written by a `Citizen of the United States`;
- Reynolds then uses the same phrase on his own collected response;
- the match is historically worth tracking.

Not supported:

- a textual copying edge;
- a private code or secret group marker;
- direct instruction from McBride or Symmes to use the byline;
- rarity sufficient to make the phrase diagnostic by itself.

## 3. Cross-variant disagreement

Variant A classifies deliberate echo and shared-circle signaling as strongly supported.

Variant B is more defensible because it finds unrelated period uses and keeps deliberate echo at `possible` while treating generic anonymity as a live explanation.

The curator position is:

```yaml
primary_match: VERIFIED
historical_proximity: VERIFIED
explicit_awareness_of_McBride_attribution: SUPPORTED
rhetorical_echo: PLAUSIBLE
shared_circle_signal: PLAUSIBLE
copying_or_coordination: NOT_ESTABLISHED
generic_period_convention: SUPPORTED_AS_COMPETING_EXPLANATION
```

The explicit awareness matters: this is not a blind coincidence between unrelated texts. But awareness plus reuse still does not disclose Reynolds's intent.

## 4. Reynolds publication-carrier path

The primary preface establishes:

```text
American Quarterly Review criticism
        ↓
three Reynolds response numbers
first published in the National Intelligencer
        ↓
Gales & Seaton collected pamphlet, 1827
```

The pamphlet OCR also preserves the internal transition to `No. II` and `No. III`, each addressed to the editor of the *American Quarterly Review*, and signs the numbers `J. N. Reynolds`.

This supports a verified publishing/reprint pathway even though issue-level newspaper records remain missing.

## 5. Edge classification

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
    - whether wording changed between serialization and pamphlet
```

This is a carrier edge, not proof that Gales & Seaton endorsed Symmes's cosmology.

## 6. Frequency-control failure

Neither variant completed the requested bounded control.

The current result only establishes that the phrase was not unique. It does not establish a reliable frequency, rarity score, topic concentration, or printer concentration.

The next control must return at least five exact non-Symmes occurrences with:

- title;
- year;
- city;
- printer/publisher;
- subject;
- exact title-page form;
- stable scan or catalogue record.

Until then, `ERR-032-002` is a verified phrase match with **low diagnostic value when used alone**.

## 7. Curator decision

```text
McBride title page: promoted
Reynolds title page: promoted
Shared phrase occurrence: promoted
Deliberate copying: rejected as unproven
Deliberate rhetorical echo: retained as plausible interpretation
National Intelligencer prior publication: promoted
Exact newspaper installments: still open
Gales & Seaton carrier path: promoted narrowly
ERR-032-002: SUPPORTED_NONDIAGNOSTIC_FINGERPRINT
```

## 8. Next exact task

Do not repeat title-page authentication.

Recover the three *National Intelligencer* issues and compare them with the pamphlet for:

- date, page, column, heading, and signature;
- wording changes;
- whether `Citizen of the United States` appears in serialization;
- surrounding advertisements or editorial framing;
- whether the collected pamphlet changed the response's apparent audience or authority.
