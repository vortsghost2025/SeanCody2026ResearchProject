# BRIDGE-032-003 — Jeremiah N. Reynolds Pivot

```yaml
BRIDGE_CANDIDATE:
  id: BRIDGE-032-003
  title: "Jeremiah N. Reynolds: Symmes advocate → Antarctic and South-Seas expedition lobbyist"
  status: SUPPORTED_SPLIT
  related_question: RQ-032

  endpoints:
    - object_type: CONCEPT_AND_PUBLIC_ADVOCACY
      object_id: SYMMES-HOLLOW-EARTH-LECTURE-PERIOD
      role: SOURCE_SIDE
    - object_type: INSTITUTIONAL_EXPLORATION_PROGRAM
      object_id: REYNOLDS-SOUTHERN-OCEAN-ADVOCACY
      role: DESTINATION_SIDE

  supported_mechanisms:
    - SAME_PERSON_CARRIER
    - EXPOSURE_PATH
    - INSTITUTIONAL_CARRIER
    - RHETORICAL_REFRAMING

  not_established:
    - PERSONAL_CONTACT_WITH_SYMMES_FROM_PRIMARY_ARTIFACT
    - DOCUMENTED_CAUSAL_INFLUENCE_OF_HOLLOW_EARTH_DOCTRINE
    - CONTINUOUS_LEXICAL_MIGRATION_INTO_1836_ADDRESS
    - COMPLETE_REPUDIATION_OF_ALL_EARLIER_IDEAS

  current_assessment:
    evidence_class: B
    confidence: MEDIUM_HIGH
    curator_note: >
      Primary and near-primary records document the same person moving from public
      support of Symmes's theory into formal Southern Ocean and South-Pole advocacy.
      The mature public case uses commercial, scientific, navigational, and national
      rationales, while explicit Hollow Earth terminology is not located in the 1836
      Address. The bridge is therefore supported as biography, exposure, institutional
      migration, and reframing—not as proven doctrinal transmission.

  generated_session: SESSION_029
  last_reviewed: 2026-07-13
```

## Supported chronology

### November 4, 1826 — transition described by John Quincy Adams

The published Adams diary describes Reynolds as a man who had lectured in support of Captain John Cleves Symmes's theory and says that, after ridicule of the theory, Reynolds had `varied his purpose` toward a voyage of circumnavigation to the Southern Ocean.

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
  source_status: PRIMARY_DIARY_IN_PUBLISHED_EDITION
```

**Finding supported:** one identifiable person occupied both roles, and a contemporary observer explicitly described a pivot.

**Finding not supported:** that Symmes's doctrine materially caused the later exploration program.

### February 22, 1828 — South-Pole identity

Adams later described Reynolds as `the projector of an expedition to the South Pole`.

This confirms that Reynolds had become publicly legible in Washington as an expedition advocate rather than only a Hollow Earth lecturer.

### November–December 1834 — state and congressional circulation

A December 16, 1834 congressional printing of the East India Marine Society memorial reproduces the Rhode Island legislature's reference to:

> `the memorial of J. N. Reynolds and others, dated November, 1834`

and recommends the proposed South-Seas voyage to Congress.

```yaml
source:
  issuing_body: "23d Congress, 2d Session"
  title: "Memorial of the East India Marine Society of Salem, Mass."
  document_date: 1834-12-16
  archive: GovInfo
  stable_pdf: "https://www.govinfo.gov/content/pkg/SERIALSET-00268_00_00-038-0075-0000/pdf/SERIALSET-00268_00_00-038-0075-0000.pdf"
```

**Finding supported:** Reynolds's advocacy moved through state-legislative and congressional print channels.

**Boundary:** this is institutional circulation of an exploration proposal, not institutional endorsement of Hollow Earth theory.

### 1836 — mature public advocacy dossier

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
  stable_item: "https://archive.org/details/addressonsubjec00reyngoog"
  stable_ocr: "https://archive.org/stream/addressonsubjec00reyngoog/addressonsubjec00reyngoog_djvu.txt"
```

The preface says Reynolds is circulating the speech through `the medium of the public press` and packages the address with correspondence and documents.

The South-Pole section begins:

> `What ! extend our researches to regions surrounding the South Pole ! And wherefore not ?`

The surrounding rationale concerns science, national honor, navigation, commerce, whaling, surveying, and knowledge.

## Transformation record

| Element | Result |
|---|---|
| Polar extremities as meaningful frontier | RETAINED |
| Expedition as a way to test or acquire knowledge | RETAINED |
| Commercial protection and fisheries | ADDED / EMPHASIZED |
| Navigation, charts, hydrography, natural history | ADDED / EMPHASIZED |
| National prestige and state sponsorship | ADDED / EMPHASIZED |
| Explicit hollow and habitable Earth | NOT LOCATED IN 1836 ADDRESS |
| `Symmes` as source or authority | NOT LOCATED IN 1836 ADDRESS |
| Polar opening as destination | NOT LOCATED IN 1836 ADDRESS |
| Public rationale | REFRAMED AS INSTITUTIONAL EXPLORATION |

## Negative evidence

A reproducible OCR search of the 1836 *Address* returned:

```text
Symmes: no match
hollow: no match
```

This supports a narrow conclusion: Reynolds did not explicitly ground the 1836 published institutional case in those terms.

It does not establish:

- that no synonyms or indirect conceptual remnants survive;
- that earlier speeches or correspondence used no Hollow Earth language;
- that Reynolds had fully abandoned the theory by 1827;
- that the OCR is error-free.

See `data/negative_evidence/NEG-032-001-REYNOLDS-1836-DOCTRINAL-CARRYOVER.md`.

## Unresolved high-value evidence

1. A primary lecture notice, pamphlet, newspaper report, or letter naming Reynolds and Symmes together.
2. The exact 1827 artifact described as *Remarks of Symmes' Theory Which Appeared in the American Quarterly Review*.
3. Reynolds correspondence explaining the break or transition in his own words.
4. A broader phrase search across the 1836 *Address*, 1835 *Voyage of the Potomac*, and earlier lecture material.
5. Evidence distinguishing genuine intellectual abandonment from strategic rhetorical suppression.

## Curator decision

```text
Same-person bridge: supported
Exposure path: supported
Institutional carrier: supported
Rhetorical reframing: supported
Personal contact: not yet promoted
Doctrinal transmission: not established
Complete abandonment: not established
Candidate status: SUPPORTED_SPLIT
```
