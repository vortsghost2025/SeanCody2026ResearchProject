# Sean & Cody Research Atlas

**START HERE.** This is the human- and AI-readable map of what the project has gathered, what connects, what remains uncertain, and what public research should do next.

The project studies two linked things:

1. how narratives, myths, claims, publications, institutions, maps, and media systems evolve across time;
2. how human–AI ensemble research preserves provenance, disagreement, chronology, failures, and discoveries across replaceable model sessions.

The subject may change. The method remains the same: preserve the pieces, identify systems, trace connections, and keep evidence strength separate from interpretation.

---

## 1. Current systems

| System | Scope | State | Entry points |
|---|---|---|---|
| **SYS-001 — Underground / Hidden-World Narrative System** | Shaver, Palmer, Hollow Earth, subterranean beings, UFO bases, Dulce, Antarctica, and related publication networks | ACTIVE | [Shaver→Dulce map](graph/transmissions/SHAVER_TO_DULCE_CHAIN.md), [RQ-023](research_questions/RQ-023-SHAVER-PALMER-BRIDGE-1948-1979.md) |
| **SYS-002 — Human–AI Ensemble Research Architecture** | Model comparison, persistent state, role specialization, disagreement preservation, verification, and human entity resolution | PARTIAL — public July sequence established; private lineage paused | [System record](graph/systems/SYS-002-HUMAN-AI-ENSEMBLE-RESEARCH.md), [Artifact registry](graph/systems/SYS-002-ARTIFACT-REGISTRY.md), [RQ-030](research_questions/RQ-030-ENSEMBLE-ARCHITECTURE-LINEAGE.md) |

SYS-002 is the research machinery used to investigate SYS-001 and future domains. It is not the same historical subject.

---

## 2. Research domains

| Domain | What is being traced | State |
|---|---|---|
| Antarctica / Terra Australis | theoretical geography, maps, voyages, observed Antarctica, and later reinterpretations | **ACTIVE — RQ-031** |
| Hollow Earth | historical theories, Shaver/Palmer, occult networks, UFO publishing, and mail-order transmission | ACTIVE |
| UFO underground bases | Bender, Barker, Bennewitz, Doty, Moore, Walton/Branton, and Dulce | ACTIVE |
| Grey imagery | fiction, testimony, visual standardization, media amplification, and retroactive artifact interpretation | SEEDED |
| Serpent / reptilian traditions | distinct cultures, diffusion, independent similarity, modern reinterpretation, and synthesis | SEEDED |
| CERN / portals / dimensions | scientific terminology versus later occult, media, and conspiracy reuse | DECLARED |
| Human–AI ensemble architecture | diversity, handoffs, state, verification, and human synthesis | PARTIAL — private phase needs isolated local access |

A domain being listed does not mean it is fully ingested or verified.

---

## 3. Current findings

### 3.1 Shaver / Palmer transmission gap

The 1948–1979 interval appears to contain several parallel carrier networks rather than one clean chain:

- Palmer's magazines and presses;
- Gray Barker's Saucerian and small-press network;
- Borderland Sciences and Riley Crabb;
- Raymond Bernard and mail-order publishing;
- fanzines, newsletters, conventions, correspondence, and catalogues.

**Strongest current candidate bridge:** Palmer publication network → Gray Barker professional/publishing network → Bruce Walton/Branton → later Dulce synthesis.

This becomes canonical only where publications, mastheads, imprints, citations, correspondence, or dated artifacts support each transition.

Read: [RQ-023](research_questions/RQ-023-SHAVER-PALMER-BRIDGE-1948-1979.md), [Session 023 variants](research_inbox/SESSION_023_CLAUDE_VARIANTS.md), [Session 023 QC](reports/SESSION_023_CROSS_VARIANT_QC.md).

### 3.2 Human–AI ensemble architecture

The first verified public sequence is:

```text
Sean's cross-domain seed corpus
        ↓
ChatGPT specialist provenance/QC layer
        ↓
explicit audit and application of the prior layer
        ↓
combined persistent session state and implementation tasks
```

This is represented by `ARCH-001` through `ARCH-004`. The earlier private January lineage remains paused until an isolated local archive agent can inspect it read-only.

Read: [SYS-002](graph/systems/SYS-002-HUMAN-AI-ENSEMBLE-RESEARCH.md), [registry](graph/systems/SYS-002-ARTIFACT-REGISTRY.md), [RQ-030](research_questions/RQ-030-ENSEMBLE-ARCHITECTURE-LINEAGE.md).

### 3.3 Terra Australis → Antarctica

```text
Acquisition variants received: 5
Core item records promoted: 1
Remaining core candidates: 4
Verified narrow map edges: 1
Canonical full lineage: 0
RQ-031 status: SEARCHING
```

#### First promoted item

**TERRA-MAP-002-A — Abraham Ortelius, *Typvs Orbis Terrarvm*, 1570**

Selected artifact:

```yaml
institution: Library of Congress, Geography and Map Division
call_number: "G1006 .T5 1570"
lccn: "2003683482"
digital_id: "g3200m.gct00126"
map_sheet: 12
imprint: "third imprint of the original 1570 Latin edition"
```

The artifact and scan are verified. The selected online copy is **not** treated as the first imprint or first plate state. The map depicts a named speculative southern continent.

One narrow relationship is verified:

```text
Mercator 1569 → Ortelius 1570
DOCUMENTED_INFLUENCE
scope: general world-map cartography and atlas synthesis
```

That edge does not prove that every Terra Australis label, bay, promontory, or coastline was copied from Mercator. No Finé feature-level edge has been accepted.

Read:

- [RQ-031](research_questions/RQ-031-TERRA-AUSTRALIS-ANTARCTICA-MAP-LINEAGE.md)
- [Ortelius item record](graph/chronologies/TERRA-MAP-002-A-ORTELIUS-1570.md)
- [Mercator → Ortelius edge](graph/transmissions/MAP-EDGE-001-MERCATOR-ORTELIUS-WORLD-MAP.md)
- [Session 026 variants](research_inbox/SESSION_026_ORTELIUS_VARIANT_MANIFEST.md)
- [Session 026 QC](reports/SESSION_026_ORTELIUS_QC.md)
- [Item registry](graph/chronologies/MAP-CHAIN-001-CANDIDATE-REGISTRY.md)

---

## 4. Evidence language

| Type | Meaning |
|---|---|
| `DIRECT_CITATION` | A source explicitly cites, quotes, names, reprints, or references another source |
| `KNOWN_COPY` | Documentary or cartographic evidence establishes copying |
| `TRANSLATION` | A text or map is translated or adapted from another |
| `DOCUMENTED_INFLUENCE` | A dated reliable source documents influence |
| `PERSONAL_CONTACT` | Correspondence, employment, collaboration, meeting, or documented contact |
| `SHARED_PUBLISHER` | Shared publisher/distribution; not proof of influence by itself |
| `SHARED_MOTIF` | Similar content exists, but transmission is unestablished |
| `RETROACTIVE_REINTERPRETATION` | A later framework is projected onto an older artifact or tradition |
| `SPECULATIVE_SIMILARITY` | A possible resemblance requiring investigation |
| `NEGATIVE_EVIDENCE` | A documented search finds an expected trace absent |
| `UNKNOWN` | Available evidence does not support classification |

Evidence classes remain separate:

- **A:** artifact, publication, event, or relationship directly confirmed;
- **B:** well-supported interpretation with uncertainty;
- **C:** plausible but unverified;
- **D:** testimonial or unsupported narrative;
- **E:** contradicted or highly implausible.

A historical map can be Evidence A while a modern claim about it is C, D, or E. A model's declarations of `INGESTED`, `COMPLETE`, `CANONICAL`, or numerical confidence do not alter repository state.

---

## 5. Active queue

| Priority | ID | Target | State | What moves it forward |
|---|---|---|---|---|
| **P0** | **RQ-031** | Terra Australis → observed Antarctica | SEARCHING — 1/5 core items promoted | Verify Ptolemy, Bertius, Tasman, and Cook one item at a time |
| P0 | RQ-023 | Shaver/Palmer transmission, 1948–1979 | PARTIAL | Primary scans, exact pages, mastheads, correspondence, publisher records |
| P0 | RQ-030 | Sean's ensemble-architecture lineage | PARTIAL — paused at private boundary | Isolated local filesystem agent and dated private artifacts |
| P1 | RQ-024 | Barker archive: Walton/Branton correspondence | OPEN | Finding aid, curator response, folder inventory, scans |
| P1 | RQ-029 | Palmer's *Forum* and later Dulce-connected writers | OPEN | Issue run, author index, letters, subscriber evidence |
| P2 | — | Grey chronology | QUEUED | First depictions, testimony, media exposure, reinterpretation |
| P2 | — | Serpent/reptilian decomposition | QUEUED | Separate cultures, texts, diffusion, and modern synthesis |
| P2 | — | CERN portal-language chronology | QUEUED | Scientific terminology versus later popular reuse |

---

## 6. Current cloud-agent assignment

### Verify one exact Ptolemaic item

Do **not** build another broad Terra Australis overview.

> Read `RESEARCH_ATLAS.md`, `research_questions/RQ-031-TERRA-AUSTRALIS-ANTARCTICA-MAP-LINEAGE.md`, `reports/SESSION_026_ORTELIUS_QC.md`, and `graph/chronologies/MAP-CHAIN-001-CANDIDATE-REGISTRY.md`. Work only on `TERRA-MAP-001-A` — the Ptolemaic world map in the Ulm 1482 edition. Select one exact institutional copy. Return the catalogue title, institution, call number or shelfmark, stable item page, primary scan or IIIF link, edition/imprint details, and a transcription of the southern land bridge or labels from the image. Compare it carefully with the Bologna 1477 tradition only where exact artifacts support the comparison. Keep Ptolemy's enclosed Indian Ocean distinct from the later named Terra Australis. Return `UNKNOWN` where the source trail is insufficient. Do not commit, ingest, freeze, or mark RQ-031 partial or resolved.

After Ptolemy passes curator review, proceed to Bertius, Tasman, and Cook one exact artifact at a time.

Preferred public sequence after RQ-031:

```text
Terra Australis / Antarctica map lineage
        ↓
Grey imagery and testimony chronology
        ↓
serpent traditions and modern reptilian synthesis
        ↓
CERN scientific language versus portal reinterpretation
```

---

## 7. Private/local lane — paused safely

```text
private historical repositories — read only
        ↓
isolated archive agent with dedicated config
        ↓
sanitized architecture-artifact report
        ↓
curator QC
        ↓
public repository
```

Do not give the archive agent write access to the projects it studies. Do not reuse active Genesis or source-build sessions or their configs.

---

## 8. Generic research prompt

> Read the Sean & Cody Research Atlas and all linked files for **[SYSTEM / DOMAIN / RQ / ITEM]**. Do not redesign the repository and do not assume repeated claims are verified. Find primary sources, exact dates, pages, quotations, stable archive links, catalogue IDs, shelfmarks, and documented contacts. Separate `DIRECT_CITATION`, `KNOWN_COPY`, `TRANSLATION`, `DOCUMENTED_INFLUENCE`, `PERSONAL_CONTACT`, `SHARED_PUBLISHER`, `SHARED_MOTIF`, `RETROACTIVE_REINTERPRETATION`, `SPECULATIVE_SIMILARITY`, `NEGATIVE_EVIDENCE`, and `UNKNOWN`. Record failed searches and contradictions. Return raw acquisition plus an acquisition summary. Do not mark anything canonical, ingested, complete, or resolved; curator review is required.

For a narrow task:

> Work only on **[RQ ID / ITEM ID]**. Return evidence that would satisfy or falsify its promotion criteria. Do not provide a general essay.

---

## 9. Canonical method documents

- [Repository Architecture](docs/REPOSITORY_ARCHITECTURE.md)
- [Puzzle-Piece Intake](docs/PUZZLE_PIECE_INTAKE.md)
- [Methodology](docs/METHODOLOGY.md)
- [Entity schema](schemas/ENTITY.md)
- [Motif schema](schemas/MOTIF.md)
- [System schema](schemas/SYSTEM.md)
- [Chronology schema](schemas/CHRONOLOGY.md)
- [Propagation schema](schemas/PROPAGATION.md)
- [Transmission-edge schema](schemas/TRANSMISSION_EDGE.md)
- [Research-question schema](schemas/RESEARCH_QUESTION.md)
- [Negative-evidence schema](schemas/NEGATIVE_EVIDENCE.md)
- [Acquisition-summary schema](schemas/ACQUISITION_SUMMARY.md)

**Maintenance rule:** update this page whenever a system, domain, research question, promoted artifact, verified edge, contradiction, or acquisition priority changes.
