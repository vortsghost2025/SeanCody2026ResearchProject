# SESSION 028 — Jeremiah Reynolds Bridge Verification Brief

**Target:** `BRIDGE-032-003`  
**Related question:** `RQ-032`  
**Mode:** narrow public-source verification  
**Status:** COMPLETED — reviewed in Session 029

## Curator result

The audit produced a supported split finding rather than a single continuous influence edge:

```text
Symmes advocacy
    ↓ same person / exposure
Jeremiah N. Reynolds
    ↓ contemporary pivot and institutional reframing
Southern Ocean / South-Pole exploration advocacy
```

Supported now:

- `SAME_PERSON_CARRIER`;
- `EXPOSURE_PATH`;
- `INSTITUTIONAL_CARRIER`;
- `RHETORICAL_REFRAMING`;
- Reynolds's 1836 *Address* → Poe's January 1837 review as `DIRECT_CITATION`.

Not established:

- a primary artifact documenting Reynolds and Symmes together at a lecture or in correspondence;
- Symmes's doctrine as a causal basis of Reynolds's mature expedition program;
- exact Reynolds passages copied into *Pym*;
- complete abandonment of all earlier Symmes-related ideas.

Read:

- [Session 029 variant manifest](SESSION_029_REYNOLDS_VERIFICATION_VARIANT_MANIFEST.md)
- [Session 029 QC](../reports/SESSION_029_REYNOLDS_CROSS_VARIANT_QC.md)
- [Supported bridge finding](../graph/bridges/BRIDGE-032-003-REYNOLDS-PIVOT.md)
- [Reynolds → Poe edge](../graph/transmissions/BRIDGE-EDGE-001-REYNOLDS-POE-REVIEW.md)
- [Negative-evidence record](../data/negative_evidence/NEG-032-001-REYNOLDS-1836-DOCTRINAL-CARRYOVER.md)
- [Next verification brief](SESSION_030_REYNOLDS_1827_REMARKS_VERIFICATION_BRIEF.md)

---

## Original objective

Test whether Jeremiah N. Reynolds was merely the same person who moved from Symmes's Hollow Earth lecture circuit into Antarctic exploration advocacy, or whether specific ideas, language, contacts, or institutional pathways moved with him.

The task allowed all outcomes:

- documented influence;
- exposure opportunity only;
- personal contact without conceptual transmission;
- deliberate abandonment/reframing;
- independent exploration advocacy;
- negative evidence.

## Required artifact set

The task requested exact, dated, item-level records for:

1. Symmes Circular No. 1 (1818), preferably an institutional scan.
2. Reynolds/Symmes lecture notices, pamphlets, newspaper reports, or correspondence from the 1820s.
3. Reynolds's memorials, petitions, speeches, or correspondence seeking an Antarctic/South-Seas expedition.
4. Reynolds's 1836 *Address on the Subject of a Surveying and Exploring Expedition to the Pacific Ocean and South Seas*.
5. John Quincy Adams diary entries or correspondence mentioning Reynolds and Symmes's theory.
6. Congressional committee reports, Navy correspondence, or expedition-funding records naming Reynolds.
7. Poe's 1837 review of Reynolds and the relevant 1838 *Pym* passages.

## Required metadata

```text
exact title
creator
publication or document date
edition / issue / volume
publisher / printer / newspaper
institution / archive
catalogue ID / call number / shelfmark
stable scan or transcript URL
page or image number
exact quotation
source type: primary / scholarly secondary / later summary
```

## Tests performed

### Test A — Personal-contact record

Requested:

- collaboration dates;
- lecture locations;
- publications or notices naming both;
- correspondence or contemporary descriptions;
- date and nature of any break.

**Result:** public support of Symmes's theory was documented; a primary jointly naming lecture/contact artifact was not located.

### Test B — Lexical continuity

Requested searches for:

- open at the poles;
- habitable interior;
- warm/rich land;
- expedition as proof;
- distinctive percentages, coordinates, mottos, or phrasing.

**Result:** the available 1836 OCR contains no `Symmes` or `hollow`. This became narrow negative evidence, with OCR and synonym limitations preserved.

### Test C — Rhetorical transformation

```text
Symmes/Hollow Earth period
        ↓
commercial/scientific/national exploration advocacy
```

**Result:** polar exploration remained central, while commerce, navigation, science, hydrography, and national prestige became the published institutional rationale.

### Test D — Institutional carrier

The audit documented movement through:

- public lectures;
- state legislatures;
- Congress and committees;
- Harper & Brothers;
- the periodical press.

Institutional recording and circulation were not treated as endorsement of Hollow Earth theory.

### Test E — Reynolds → Poe text reuse

**Result:** Poe's named review is verified as `DIRECT_CITATION`. Exact Reynolds→*Pym* passage alignment remains open, so `KNOWN_COPY` was not promoted.

### Test F — Disproof and negative evidence

The audit actively tested:

- contemporary descriptions of Reynolds changing course;
- absence of explicit theory language in the mature published case;
- independent commercial and scientific rationales;
- whether later summaries overstate causal continuity.

## Completion decision

```yaml
brief_status: COMPLETED
candidate_status: SUPPORTED_SPLIT
direct_citation_edges: 1
known_copy_edges: 0
next_decisive_artifact: "Alleged 1827 Remarks of Symmes' Theory pamphlet"
```
