# RQ-032 — Which hidden carriers connect the project's apparently separate narrative systems?

```yaml
RQ:
  id: RQ-032
  title: "Which hidden carriers connect apparently separate narrative systems?"
  status: SEARCHING
  priority: HIGH

  scope:
    - Antarctica and Terra Australis
    - Hollow Earth and subterranean civilizations
    - UFO underground bases and Dulce
    - Grey-alien imagery and testimony
    - serpent traditions and modern reptilian synthesis
    - CERN, portals, dimensions, and scientific-language reuse
    - occult, science-fiction, paranormal, military, and conspiracy publishing networks

  central_problem: >
    Topic-by-topic research can miss the people, publications, institutions, errors,
    images, terminology, bylines, printers, formats, and distribution systems that
    carry material between domains. This question seeks those hidden carriers without
    assuming that similarity proves transmission.

  core_questions:
    - Which editors, publishers, printers, translators, illustrators, distributors, clubs, archives, broadcasters, platforms, or institutions appear in multiple domains?
    - Which rare phrases, bylines, errors, quotations, labels, diagrams, images, or numerical mistakes recur across domains?
    - How does material change when moving from review to newspaper, pamphlet, book, broadcast, archive, or institutional dossier?
    - Where do speculation, testimony, technical language, and institutional framing change roles?
    - Which apparent bridges are independent parallels, genre conventions, strategic reframings, or later retrospective fusions?
    - What negative evidence would disprove the strongest proposed connections?

  do_not_treat_as_proof:
    - broad thematic similarity
    - chronological overlap without exposure evidence
    - one shared publisher without item-level connection
    - one shared anonymous byline without frequency controls
    - one person appearing in the same broad field
    - model agreement
    - unsourced internet repetition
    - retrospective diagrams that merge traditions
    - a bridge candidate being registered
    - an institution preserving a record being treated as endorsement
    - one person's biography being treated automatically as doctrinal continuity
    - absence of a keyword being treated as total intellectual abandonment
    - a catalogue title being treated as proof of substantive argument
    - primary phrase match being treated automatically as copying or code

  partial_resolution: >
    Three or more bridge candidates have item-level evidence for shared infrastructure,
    exposure paths, lexical or iconographic migration, material reuse, copied error,
    editorial synthesis, documented transformation, strategic reframing, or documented
    discontinuity, while competing explanations remain open.

  positive_resolution: >
    A cross-domain map identifies multiple hidden carriers with source-supported dates,
    mechanisms, and transformations, and distinguishes genuine transmission from shared
    motif, independent parallel development, generic convention, strategic reframing,
    and later retrospective fusion.

  negative_resolution: >
    Major proposed bridges fail contact, chronology, source, phrase-frequency, or
    error-fingerprint tests and are classified as independent parallel, generic convention,
    retrospective pattern matching, abandoned framework, or unknown.

  related_files:
    - CROSS_DOMAIN_BRIDGE_ATLAS.md
    - schemas/BRIDGE_CANDIDATE.md
    - graph/bridges/RQ-032-ANTARCTICA-HOLLOW-EARTH-CANDIDATES.md
    - graph/bridges/BRIDGE-032-003-REYNOLDS-PIVOT.md
    - graph/chronologies/REYNOLDS-1827-REMARKS-CATALOG-RECORD.md
    - graph/transmissions/BRIDGE-EDGE-001-REYNOLDS-POE-REVIEW.md
    - graph/transmissions/BRIDGE-EDGE-002-AQR-REYNOLDS-RESPONSE-CANDIDATE.md
    - graph/transmissions/BRIDGE-EDGE-003-INTELLIGENCER-REYNOLDS-PAMPHLET.md
    - data/negative_evidence/NEG-032-001-REYNOLDS-1836-DOCTRINAL-CARRYOVER.md
    - data/error_fingerprints/ERR-032-001-REYNOLDS-REMARKS-TITLE.md
    - data/error_fingerprints/ERR-032-002-CITIZEN-OF-US-BYLINE.md
    - research_inbox/SESSION_032_BYLINE_INTELLIGENCER_VARIANT_MANIFEST.md
    - reports/SESSION_032_BYLINE_INTELLIGENCER_QC.md

  generated_session: SESSION_027
  current_acquisition_session: SESSION_032
  last_updated: 2026-07-13
```

## Current acquisition state

```text
Methodology commentary variants: 1
Initial historical acquisition variants: 2
Reynolds verification variants: 2
Reynolds 1827 catalogue variants: 1
Reynolds/AQR text-pair variants: 1
Byline/Intelligencer variants: 2
Normalized bridge candidate clusters: 10
Candidates deep-verified: 1
Supported bridge findings: 1
Canonical direct-citation/review edges: 1
Canonical direct-response edges: 1
Canonical publication-carrier edges: 1
Canonical known-copy edges: 0
Negative-evidence records: 1
Error/phrase fingerprint candidates: 2
RQ-032 status: SEARCHING
```

## First deep-verification result — Reynolds

```text
Symmes Hollow Earth advocacy
        ↓ same person / exposure
Jeremiah N. Reynolds
        ↓ Adams records public pivot in 1826
1827 response to AQR
        ├── partial defense of hollow/open-pole possibility
        ├── rejection/bracketing of detailed five-sphere claims
        └── explicit separation of theory from expedition
        ↓
National Intelligencer serialized response
        ↓
Gales & Seaton collected pamphlet
        ↓
1836 institutional case without explicit Symmes/hollow vocabulary
```

### Supported

- Adams described Reynolds as a lecturer supporting Symmes's theory who had `varied his purpose` toward Southern Ocean circumnavigation.
- Reynolds's 1827 pamphlet partially defends a hollow/open-pole possibility while separating speculation from expedition rationale.
- The pamphlet preface says its three numbers were first published in the *National Intelligencer*.
- The collected text preserves the numbered response structure and Reynolds signatures.
- McBride 1826 and Reynolds 1827 both use the primary-confirmed title-page formula `By a Citizen of the United States`.
- Reynolds explicitly knew the McBride/Symmes attribution.
- Reynolds's 1836 *Address* uses commercial, scientific, navigational, and national rationales without located `Symmes` or `hollow` terms.
- Poe's January 1837 review directly identifies and reviews Reynolds's 1836 book.

### Not established

- A primary artifact naming Reynolds and Symmes together in correspondence or one lecture notice.
- Full loyalty to every Symmes claim.
- Symmes's doctrine as the causal basis of the mature expedition program.
- Exact copied passages from Reynolds into *Pym*.
- Complete paragraph-by-paragraph AQR alignment.
- Deliberate copying, coordination, or secret-code use of the citizen byline.
- Exact *National Intelligencer* issue dates, pages, columns, headings, and bylines.

## Current classification

```yaml
BRIDGE-032-003:
  status: SUPPORTED_PARTIAL_CONTINUITY_AND_STRATEGIC_REFRAMING
  supported:
    - SAME_PERSON_CARRIER
    - EXPOSURE_PATH
    - INSTITUTIONAL_CARRIER
    - PARTIAL_DOCTRINAL_CONTINUITY_IN_1827
    - STRATEGIC_AND_ARGUMENTATIVE_REFRAMING
    - VERIFIED_NEWSPAPER_TO_PAMPHLET_CARRIER
    - PRIMARY_CONFIRMED_SHARED_BYLINE_CONTEXT
  not_established:
    - PRIMARY_PERSONAL_CONTACT_ARTIFACT
    - FULL_SYMMES_DOCTRINAL_LOYALTY
    - DOCTRINE_AS_CAUSE_OF_1836_PROGRAM
    - BYLINE_COPYING_OR_SECRET_CODE

BRIDGE-EDGE-002:
  status: VERIFIED_DIRECT_RESPONSE
  canonical: true
  content_alignment: PARTIAL

BRIDGE-EDGE-003:
  status: VERIFIED_PUBLICATION_PATH_WITH_ISSUE_LEVEL_GAP
  canonical: true

ERR-032-001:
  status: OPEN_TITLE_MUTATION_CANDIDATE

ERR-032-002:
  status: SUPPORTED_NONDIAGNOSTIC_FINGERPRINT
  deliberate_echo: PLAUSIBLE_NOT_PROVEN
  copying_edge: false
```

## Why RQ-032 remains SEARCHING

The resolution threshold requires at least three independent bridge clusters to pass item-level tests or be rejected with documented negative evidence. Reynolds is still the only deeply verified cluster. The project has now mapped a compact review → newspaper → pamphlet → institutional-rhetoric pathway, but not yet a multi-cluster cross-domain system.

## Current exact task

Do not repeat title-page authentication or broad Reynolds biography.

Recover the three Reynolds numbers from the *National Intelligencer* and return:

```text
issue date
page and column
article heading
signature/byline
opening and closing lines
surrounding editorials and advertisements
textual differences from the pamphlet
```

Determine whether the citizen byline appears in the newspaper serialization or was added for pamphlet collection. Do not create a McBride → Reynolds copying edge without new evidence.
