# RQ-035 — How did Grey imagery standardize across fiction, testimony, hypnosis, illustration, and mass media?

```yaml
RQ:
  id: RQ-035
  title: "How did Grey imagery standardize across fiction, testimony, hypnosis, illustration, and mass media?"
  status: SEARCHING
  priority: HIGH

  scope:
    - nineteenth- and early-twentieth-century speculative imagery
    - early UFO-era humanoid diversity
    - Betty and Barney Hill source chronology
    - hypnosis, dreams, artist reconstructions, and investigator prompting
    - television, film, book-cover, magazine, and illustration carriers
    - later witness descriptions
    - Zeta Reticuli interpretation history
    - visual and lexical contamination
    - negative-control encounter descriptions

  central_problem: >
    The standardized Grey image may reflect a mixture of independent observation,
    shared human perception, earlier fiction and illustration, hypnosis and investigator
    effects, mass-media feedback, commercial cover art, and later narrative harmonization.
    The project must reconstruct the chronology without assuming either pure invention
    or direct physical continuity.

  core_questions:
    - What did each witness say before hypnosis, publication, artwork, or media exposure?
    - Which visual features first appeared in fiction, dreams, hypnosis, sketches, books, television, film, and later testimony?
    - Which reports remain morphologically unlike the standardized Grey?
    - When did the term `Grey` become attached to earlier descriptions?
    - Which artists, producers, investigators, publishers, and broadcasters served as carriers?
    - Can any later testimony be shown to use a distinctive feature or phrase after exposure?
    - Which alleged contamination links fail because exposure cannot be demonstrated?

  do_not_treat_as_proof:
    - visual resemblance by itself
    - an episode airing before testimony without exposure evidence
    - later artwork as an exact record of earlier wording
    - hypnosis recall as equivalent to a contemporaneous statement
    - a franchise premiere date as the date of all later mythology
    - the phrase `Grey alien` projected backward onto sources that did not use it
    - one secondary summary replacing primary transcripts or images
    - lack of a mundane explanation as proof of an extraterrestrial interpretation

  partial_resolution: >
    At least five item-level artifacts and three observation/report records are aligned
    by event date, report date, hypnosis or interview date, publication date, broadcast
    date, visual features, and exposure evidence, with at least one contamination claim
    supported or rejected.

  positive_resolution: >
    A source-supported chronology distinguishes literary precursors, independent witness
    descriptions, investigator or hypnosis effects, mass-media standardization, and later
    testimony feedback, while preserving morphological diversity and uncertainty.

  negative_resolution: >
    Available sources cannot establish pre-exposure wording or media contact strongly
    enough to distinguish independent observation from cultural contamination.

  related_files:
    - data/grey_reptilian_motif_timeline_seed_2026-07-12.csv
    - reports/SESSION_036_GREY_REPTILIAN_QC.md
    - graph/bridges/BRIDGE-035-001-GREY-VISUAL-STANDARDIZATION.md
    - docs/INDEPENDENT_CONVERGENCE_METHOD.md
    - schemas/OBSERVATION_REPORT.md
    - schemas/CONVERGENCE_CLUSTER.md
    - research_inbox/SESSION_037_GREY_VISUAL_CONTAMINATION_BRIEF.md

  generated_session: SESSION_036
  current_acquisition_session: SESSION_037
  last_updated: 2026-07-14
```

## Current seed state

The canonical seed contains:

```text
GREY-001 through GREY-008
plus UFO-002 and UFO-003 as diversity controls
```

The Session 036 extension proposed six more Grey-related rows, but none is imported yet.

## First high-value test

```text
1961 Hill event and earliest statements
        ↓
Betty's dreams / separate source chain
        ↓
1964 hypnosis sessions
        ↕ reported pre-session television exposure
artist reconstructions
        ↓
1966 book
        ↓
1975 television dramatization
        ↓
1977 film standardization
        ↓
1987 commercial cover standardization
```

The question is not whether these artifacts look similar. The question is which features were present at each dated stage and whether exposure or editorial transfer can be documented.

## Required output structure

Every observation or testimony record should use `OBSERVATION_REPORT`.

Every comparison should use `CONVERGENCE_CLUSTER` and preserve:

- original wording;
- raw feature terms;
- normalized feature terms;
- report-chain independence;
- exposure before statement;
- investigator and media contamination;
- ordinary/common perceptual alternatives;
- contradictions and dropped details.

## Current counts

```text
Canonical Grey seed records: 8
Proposed extension rows imported: 0
Primary Hill archive identified: 1
Observation reports built: 0
Visual artifact records promoted: 0
Contamination edges verified: 0
Contamination hypotheses rejected: 0
RQ-035: SEARCHING
```
