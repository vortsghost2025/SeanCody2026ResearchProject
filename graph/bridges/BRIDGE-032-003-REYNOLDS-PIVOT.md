# BRIDGE-032-003 — Jeremiah N. Reynolds Pivot

```yaml
BRIDGE_CANDIDATE:
  id: BRIDGE-032-003
  title: "Jeremiah N. Reynolds: Symmes advocate → Antarctic and South-Seas expedition lobbyist"
  status: SUPPORTED_PARTIAL_CONTINUITY_AND_STRATEGIC_REFRAMING
  related_question: RQ-032

  endpoints:
    - object_type: CONCEPT_AND_PUBLIC_ADVOCACY
      object_id: SYMMES-HOLLOW-EARTH-PERIOD
      role: SOURCE_SIDE
    - object_type: INSTITUTIONAL_EXPLORATION_PROGRAM
      object_id: REYNOLDS-SOUTHERN-OCEAN-ADVOCACY
      role: DESTINATION_SIDE

  supported_mechanisms:
    - SAME_PERSON_CARRIER
    - EXPOSURE_PATH
    - INSTITUTIONAL_CARRIER
    - BIBLIOGRAPHIC_CONTINUITY
    - PARTIAL_DOCTRINAL_CONTINUITY_IN_1827
    - STRATEGIC_AND_ARGUMENTATIVE_REFRAMING

  not_established:
    - PRIMARY_PERSONAL_CONTACT_ARTIFACT_NAMING_REYNOLDS_AND_SYMMES_TOGETHER
    - FULL_LOYALTY_TO_ALL_SYMMES_CLAIMS
    - SYMMES_DOCTRINE_AS_CAUSAL_BASIS_OF_1836_PROGRAM
    - CONTINUOUS_LEXICAL_MIGRATION_INTO_1836_ADDRESS
    - COMPLETE_AQR_PARAGRAPH_ALIGNMENT

  current_assessment:
    evidence_class: B
    confidence: HIGH_FOR_SPLIT_FINDING
    curator_note: >
      Reynolds publicly supported Symmes-related ideas, pivoted toward a Southern Ocean
      expedition program, and in 1827 still defended a narrower hollow/open-pole
      possibility while explicitly separating speculative cosmology from the independent
      scientific and national case for exploration. By 1836 his published institutional
      case foregrounded commerce, navigation, science, and national prestige, with no
      explicit Symmes or hollow-Earth terminology located in the available OCR.

  generated_session: SESSION_029
  updated_session: SESSION_031
  last_reviewed: 2026-07-13
```

## Supported chronology

### November 4, 1826 — contemporary pivot description

John Quincy Adams's published diary describes Reynolds as a man who had lectured in support of Captain John Cleves Symmes's theory and says that, after ridicule of the theory, Reynolds had `varied his purpose` toward a voyage of circumnavigation to the Southern Ocean.

```yaml
source:
  creator: John Quincy Adams
  publication: "Memoirs of John Quincy Adams, comprising portions of his diary from 1795 to 1848"
  volume: VII
  diary_entry_date: 1826-11-04
  published_volume_date: 1875
  publisher: J. B. Lippincott & Co.
  ia_identifier: memoirsofjohnqui07adam
  ark: ark:/13960/t5j963k68
```

This supports a same-person transition and contemporary recognition of reframing. It does not establish that every earlier idea disappeared.

### 1827 — partial continuity and explicit separation

The LOC-derived Internet Archive scan verifies:

```yaml
creator_catalogue: "Reynolds, Jeremiah N."
printed_attribution: "A Citizen of the United States"
title: "Remarks on a review of Symmes' theory, which appeared in the American quarterly review"
place: Washington
printer: "Gales & Seaton"
year: 1827
ia_identifier: remarksonreviewo00reyn
ark: ark:/13960/t1tf1gd11
lccn: "06040937"
```

The text establishes four different positions that must not be collapsed:

| Component | Reynolds's 1827 position |
|---|---|
| Five concentric spheres and detailed internal structure | Explicitly not defended |
| Earth possibly hollow and widely open at the poles | Retained as plausible speculation |
| Speculation sufficient to justify an expedition | Rejected |
| Polar expedition justified independently by inquiry, science, and national purpose | Defended |

This is `PARTIAL_DOCTRINAL_CONTINUITY`, not full continuity and not complete abandonment.

### Publication carrier

The pamphlet says the response numbers were first published in the *National Intelligencer*.

```text
American Quarterly Review criticism
        ↓
National Intelligencer response series
        ↓
Gales & Seaton collected pamphlet
```

This creates a high-value publishing-infrastructure test. Exact newspaper dates and bylines remain open.

### February 22, 1828 — South-Pole identity

Adams later described Reynolds as `the projector of an expedition to the South Pole`, confirming that the institutional exploration identity was publicly established.

### November–December 1834 — legislative and congressional circulation

A December 16, 1834 congressional printing reproduces the Rhode Island legislature's reference to `the memorial of J. N. Reynolds and others, dated November, 1834` and recommends the South-Seas proposal to Congress.

This supports institutional circulation of an exploration program, not governmental endorsement of Hollow Earth theory.

### 1836 — mature institutional dossier

```yaml
source:
  creator: J. N. Reynolds
  title: "Address on the Subject of a Surveying and Exploring Expedition to the Pacific Ocean and South Seas"
  delivery_date: 1836-04-03
  publication_year: 1836
  preface_date: 1836-10-10
  publisher: Harper & Brothers
  ia_identifier: addressonsubjec00reyngoog
  ark: ark:/13960/t6b282459
  lccn: "04033154"
```

Its visible rationale concerns science, national honor, navigation, commerce, whaling, surveying, and knowledge. The available OCR yields no match for `Symmes` or `hollow`.

## Transformation record

| Element | 1827 | 1836 |
|---|---|---|
| Polar extremities as meaningful frontier | RETAINED | RETAINED |
| Expedition as empirical inquiry | RETAINED | RETAINED / INSTITUTIONALIZED |
| Earth possibly hollow/open at poles | PARTIALLY DEFENDED | NOT LOCATED |
| Five-sphere details | NOT DEFENDED | ABSENT |
| Theory as sufficient expedition basis | REJECTED | ABSENT |
| Scientific and navigational rationale | EMPHASIZED AS INDEPENDENT | DOMINANT |
| Commercial and national rationale | PRESENT/DEVELOPING | DOMINANT |
| Public rhetoric | THEORY/EXPEDITION SEPARATED | FULLY INSTITUTIONAL |

## Negative-evidence boundary

The 1836 result remains:

```text
Symmes: no match
hollow: no match
```

It supports absence of explicit doctrinal vocabulary in that publication. It does not erase the 1827 partial defense or prove no indirect influence.

## Related fingerprints

- `ERR-032-001`: mutated short title obscuring the review-response relationship.
- `ERR-032-002`: shared `A Citizen of the United States` attribution between adjacent Symmes-related publications.

Neither currently establishes a copying chain.

## Curator decision

```text
Same-person bridge: supported
Exposure path: supported
Institutional carrier: supported
1827 partial doctrinal continuity: supported
Strategic separation of theory and expedition: supported
1836 explicit doctrinal carryover: not located
Full loyalty to Symmes system: not supported
Complete abandonment in 1826: contradicted by 1827 text
Doctrine as cause of mature expedition program: not established
Candidate status: SUPPORTED_PARTIAL_CONTINUITY_AND_STRATEGIC_REFRAMING
```

## Next exact test

Execute `research_inbox/SESSION_032_CITIZEN_BYLINE_INTELLIGENCER_BRIDGE_BRIEF.md` to verify the shared citizen byline and reconstruct Reynolds's *National Intelligencer* serialization.
