# SESSION_023 — Cross-Variant QC

**Inputs:** Claude Variant A and Claude Variant B  
**Decision:** preserve both; promote neither wholesale  
**RQ affected:** RQ-023

## What the two variants independently converge on

Both variants identify a non-empty 1948–1979 transmission interval and point to several recurring carrier environments:

1. Raymond A. Palmer's post-*Amazing Stories* publication ecology.
2. Gray Barker's *Saucerian* and small-press network.
3. Borderland Sciences / Riley Crabb material.
4. Raymond Bernard and hollow-earth book or mail-order circulation.
5. Later Bruce Walton / Branton material as a possible bridge into Dulce-era synthesis.

This convergence is useful for directing verification. It is not independent historical confirmation because both branches are from the same model family and may share sources, assumptions, and failure modes.

## Major disagreements and QC failures

### 1. Status inflation

Variant A correctly labels itself a draft. Variant B labels itself `INGESTED`, `READY FOR GRAPH`, and `COMPLETE` while curator sign-off remains pending. Repository status is therefore reset to `RAW_ACQUISITION`.

### 2. Chain versus parallel networks

Variant A argues for at least five parallel carrier networks. Variant B compresses the material into a more definite Palmer → Barker → Walton → Dulce chain. The current evidence may support several documented relationships, but not yet one fully demonstrated causal transmission chain.

### 3. Shared publisher is not influence

Both variants sometimes treat a shared publisher, distributor, magazine ecology, or broad UFO-community membership as evidence of influence. These are different edge types.

- `SHARED_PUBLISHER` establishes a publishing relationship.
- `PERSONAL_CONTACT` establishes contact.
- `DIRECT_CITATION` requires a locatable citation or quotation.
- `DOCUMENTED_INFLUENCE` requires evidence that one source or person affected another.
- `SHARED_MOTIF` records resemblance without transmission.

No edge may be upgraded merely because two books appeared under the same imprint.

### 4. Raymond Bernard publication path conflict

Variant A describes *The Hollow Earth* through self-publication, Health Research/mail-order circulation, and a later University Books edition. Variant B states that Barker's press reprinted Bernard. Exact editions, dates, and imprints must be reconciled before a publisher edge is accepted.

### 5. *The Secret World* timing conflict

Both variants date the work to 1975, while Variant B calls it posthumous. Richard Shaver's death is also placed in 1975. Exact publication month and edition chronology must be checked before using `posthumous`.

### 6. McKee source classification conflict

Variant A calls a 2024 item a preprint and also labels it peer-reviewed. Those statuses are not interchangeable. Publication venue and review status must be verified.

### 7. Bender underground-base wording

The phrase describing an "Agharta-type underground UFO base in Antarctica" is potentially important, but it must be located in the 1962 primary text or clearly attributed to a secondary summary. Publication existence alone does not verify the exact wording.

### 8. Moore/Doty/Bennewitz inference

Neither variant establishes that Moore, Doty, or Bennewitz read Shaver as a template. Shared network membership, friendship claims, APRO involvement, and proximity to Barker material remain insufficient without dated evidence.

### 9. Research-question ID collision

Variant A proposes RQ-024 through RQ-029. Variant B reuses RQ-023 through RQ-025 for different questions. Existing repository IDs control. Proposed questions must be renumbered and deduplicated before creation.

### 10. Confidence scores are not calibrated

Variant A assigns 8.5/10 and Variant B 9.2/10 despite unresolved bibliographies, mutable web sources, edge-type errors, and unverified quotations. These scores are retained only as model self-reports and are not adopted by the curator.

## Preliminary curator decision

RQ-023 is **partially resolved**:

- the interval appears to contain several identifiable carrier communities;
- some publication and publisher relationships are plausible and potentially documentable;
- no fully verified direct path to Bennewitz, Doty, Moore, or the complete Dulce synthesis has yet been established.

## Promotion order

1. Verify publication existence, issue dates, page ranges, imprints, and scans.
2. Verify quotations against primary pages.
3. Create publication and person entities.
4. Add only low-inference edges first: `DIRECT_CITATION`, `REPRINT`, `SHARED_PUBLISHER`, `PERSONAL_CONTACT`.
5. Add `DOCUMENTED_INFLUENCE` only when the source explicitly supports it.
6. Keep motif resemblance and unresolved downstream transmission separate.

## Highest-value next targets

- Gray Barker archive holdings for Walton/Branton correspondence and business records.
- Exact Barker masthead credits in Palmer publications.
- Exact editions and imprints of Bernard's *The Hollow Earth*.
- Primary pages for Bender's 1962 underground-base material.
- Exact dates for Walton's pre-1983 manuscripts.
- Palmer's *Forum* and Barker newsletters for names later connected to New Mexico or Bennewitz.

## Canonical result from this pass

No historical claim is promoted solely because both Claude branches repeat it. The canonical result is the **research map**: likely carrier networks, identified conflicts, verification priorities, and a partial status update for RQ-023.
