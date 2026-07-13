# SESSION 029 — Reynolds Bridge Cross-Variant QC

> ## TOP-LEVEL CURATOR STATUS
>
> ```text
> Reynolds verification variants: 2
> Item-level primary/near-primary records surviving QC: 5
> Supported bridge findings: 1
> Canonical direct-citation edges: 1
> Canonical known-copy edges: 0
> Negative-evidence records: 1
> RQ-032 status: SEARCHING
> ```

## 1. Core result

The candidate does not resolve into a simple `influence` or `no influence` verdict. It splits:

```text
Symmes theory
    ↓ Reynolds publicly supported it
same identifiable person
    ↓ Reynolds redirected toward Southern Ocean / South-Pole exploration
institutional advocacy
    ↓ commerce, navigation, science, national prestige
explicit Hollow Earth doctrine
    ↘ not located in the 1836 Address
```

The strongest supported finding is therefore **same-person transition plus documented rhetorical reframing**, not proof that Symmes's doctrine caused the United States expedition program.

## 2. Evidence that survives curator QC

### A. John Quincy Adams transition record

The GPT-5.2 variant supplies an exact published-diary item and a November 4, 1826 quotation describing Reynolds as a lecturer supporting Symmes's hollow-Earth theory who had `varied his purpose` toward a Southern Ocean circumnavigation proposal.

This supports:

- `SAME_PERSON_CARRIER`;
- `EXPOSURE_PATH`;
- contemporary recognition of a transition;
- evidence against assuming uninterrupted doctrinal continuity.

It does **not** by itself prove direct Reynolds–Symmes personal contact, because the surviving item used here describes Reynolds's public advocacy rather than naming a joint event or correspondence.

### B. Congressional and state-legislative carrier path

The December 16, 1834 GovInfo memorial records the Rhode Island legislature's recommendation of `the memorial of J. N. Reynolds and others, dated November, 1834`, requesting a voyage of discovery and survey to the South Seas.

This supports an item-level institutional route:

```text
Reynolds memorial
    ↓
state legislature
    ↓
Congress / committee printing
```

The document supports institutional circulation and consideration. It does not show endorsement of Hollow Earth theory.

### C. Reynolds's 1836 *Address*

The verified item is:

```yaml
creator: J. N. Reynolds
title: "Address on the Subject of a Surveying and Exploring Expedition to the Pacific Ocean and South Seas"
delivery_date: 1836-04-03
publication_year: 1836
publisher: Harper & Brothers
ia_identifier: addressonsubjec00reyngoog
ark: ark:/13960/t6b282459
lccn: "04033154"
```

The preface explicitly describes public-press dissemination and packages the speech with correspondence and documents. The text argues for exploration through commerce, hydrography, scientific collection, national standing, and high-latitude achievement.

The OCR contains the passage:

> `What ! extend our researches to regions surrounding the South Pole ! And wherefore not ?`

The same OCR returns no match for `Symmes` and no match for `hollow`.

This is meaningful negative evidence about explicit vocabulary in this text. It does not prove that every earlier influence vanished from Reynolds's thinking.

### D. Poe's January 1837 review

Poe's `South-Sea Expedition`, *Southern Literary Messenger*, vol. III, no. 1, January 1837, pages 68–72, explicitly identifies Reynolds's 1836 *Address*, names Harper & Brothers, and directs readers to Reynolds's dossier.

This satisfies a narrow `DIRECT_CITATION` edge:

```text
Reynolds, Address (1836)
        ↓ direct review/reference
Poe, South-Sea Expedition (1837)
```

### E. Issue-level exposure context

The January 1837 issue index lists both:

- `Arthur Gordon Pym, No. I`;
- Poe's Reynolds review.

This establishes `ISSUE_LEVEL_EXPOSURE_PATH` and editorial proximity. It does not establish that one item caused the other or that the first *Pym* installment borrowed Reynolds language.

## 3. Claims not promoted

### Reynolds and Symmes personal contact

Secondary sources describe joint lectures and a break, but this pass did not produce a primary lecture notice, jointly named pamphlet, correspondence item, or contemporary report documenting the collaboration. Status remains `UNKNOWN / HIGH-PRIORITY LEAD`.

### Reynolds's alleged 1827 pamphlet

`Remarks of Symmes' Theory Which Appeared in the American Quarterly Review` is repeatedly mentioned in secondary summaries. No exact institutional copy, scan, title page, author statement, or catalogue record survived this pass. It is now the highest-priority continuity test.

### Reynolds → Poe `KNOWN_COPY`

The variants repeat a scholarly claim that Poe reused roughly 700 words from Reynolds in *Pym*. Neither variant supplied aligned passages with Reynolds page/image numbers and Poe chapter/page locators. `KNOWN_COPY` is therefore not promoted.

### 1842 bankruptcy-petition Reynolds

The Claude variant raises a `J. N. Reynolds` associated with Poe's bankruptcy petition. Identity resolution is incomplete. It may be Jeremiah N. Reynolds or a namesake. No contact edge is created.

### Poe deathbed `Reynolds`

The anecdote remains quarantined. Named scholarship disputes both the reported word and the proposed identity. It is unnecessary to the documented review/publication relationship.

### 1829 Antarctic-shore claim

The Claude variant says Reynolds's private expedition reached the Antarctic shore. This was not confirmed with a primary log, voyage narrative, coordinates, or item-level source in this pass.

## 4. Cross-variant corrections

| Claim | Curator correction |
|---|---|
| Adams transition entry dated 1828 | The quoted `varied his purpose` entry is dated November 4, 1826 in Variant B. |
| Poe review at page 65 | Verified transcript gives pages 68–72. |
| Reynolds *Address* dated January 1836 | The title page gives 1836; the address was delivered April 3 and the preface is dated October 10. A January publication date is unsupported. |
| `KNOWN_COPY` already established | Only direct review/reference is established. Exact parallel-text alignment remains open. |
| SLM co-location proves textual borrowing | Co-location proves issue-level exposure opportunity only. |
| No `Symmes`/`hollow` proves complete abandonment | It proves absence of those strings in one OCR transcription, with OCR and synonym limits. |
| `convert to Captain Symmes` directly concerns Reynolds | It is useful evidence of political stigma around exploration proposals, but requires full diary context before being attached to Reynolds specifically. |
| 1827 pamphlet proves continued belief | The pamphlet itself has not yet been located or authenticated. |

## 5. Curator classifications

| Sub-question | Current class | Reason |
|---|---|---|
| Reynolds publicly supported Symmes theory before later expedition advocacy | `SUPPORTED SAME_PERSON_CARRIER / EXPOSURE_PATH` | Contemporary Adams diary description. |
| Symmes doctrine caused Reynolds's mature Antarctic program | `NOT ESTABLISHED` | Later primary advocacy rests on other rationales; explicit theory language absent. |
| Reynolds's 1836 advocacy explicitly carried Hollow Earth terminology | `NEGATIVE_EVIDENCE` | No `Symmes`/`hollow` in OCR; contemporary transition language. |
| Reynolds advocacy entered legislative and congressional systems | `SUPPORTED INSTITUTIONAL_CARRIER` | 1834 memorial and 1836 documentary dossier. |
| Reynolds *Address* → Poe review | `DIRECT_CITATION` | Poe explicitly names and reviews the book. |
| Reynolds *Address* → *Pym* copied passages | `OPEN` | Exact alignment missing. |
| Reynolds–Symmes personal collaboration | `OPEN` | Primary jointly naming artifact missing. |

## 6. Why the negative result matters

The hidden bridge is real, but it may be a bridge of **biography, reputation, advocacy technique, and institutional access**, not a bridge carrying the original cosmology intact.

That is a stronger historical finding than forcing either extreme:

- `Hollow Earth directly created the expedition`; or
- `the two phases were completely unrelated`.

The available evidence instead suggests a person moved between frameworks while retaining a polar/exploration focus and replacing the public rationale.

## 7. Next decisive artifact

Verify the alleged 1827 Reynolds pamphlet:

```text
Remarks of Symmes' Theory Which Appeared in the American Quarterly Review
```

Required:

- exact title-page transcription;
- creator attribution;
- date, printer, city, edition, and extent;
- institution and catalogue identifier;
- stable scan;
- passages showing Reynolds's position after the break;
- phrase comparison with his 1836 *Address*;
- evidence for or against continued doctrinal commitment.

Until that artifact is located, the Reynolds bridge remains `SUPPORTED_SPLIT`, and `RQ-032` remains `SEARCHING`.
