# Sessions 057–060 — Eve Research Summary

## Scope

Sessions 057 through 060 used the pinned stock Eve `0.24.6` runtime to test a repeatable specialist-agent research pipeline while continuing the Dulce / Branton / *Matrix II* carrier and edition investigation.

The runtime used one parent orchestrator with declared `acquirer`, `source-critic`, and `qc-auditor` roles. Each session ended in a bounded outcome rather than a forced resolution.

This report summarizes public research conclusions and workflow findings. It does not promote recovered transcript copies into byte-identical Eve originals and does not publish credentials, private infrastructure, or local machine paths.

---

## Session 057 — COSCON34 carrier identity

### Question

Could the surviving `COSCON34` material be assigned a secure carrier identity, work identity, first composition date, canonical authorship, or chronology?

### Bounded result

```yaml
classification: PARTIAL
carrier_identity: UNKNOWN
work_identity: OPEN_OR_UNKNOWN
first_composition_date: UNRESOLVED
lane_status: CLOSED_AT_BOUNDED_EVIDENCE_LEVEL
```

A March 18, 1994 reference establishes only a terminus post quem for the surviving editorialized carrier state. It does not establish the date of the embedded Q&A or prove that the carrier is *Cosmic Conflict* chapter 34.

No first source, canonical identity, authenticated authorship, canonical edge, or resolved chronology was established.

### Reopening evidence

- an explicit carrier header;
- contents or directory context;
- an authenticated earlier carrier;
- item-level evidence connecting `COSCON34` to a named work.

---

## Session 058 — *Matrix II* 1990 first-edition physical escalation

### Question

Does “Pasturing and Use of Surface Earth Humans,” with the surrounding Draco, Grey, Bishop, LeVesque, and Dulce entries, appear in the numbered 458-page 1990 first edition of *Matrix II*?

### Bounded result

```yaml
classification: PARTIAL
first_edition_inspected: false
physical_access: BLOCKED
1990_presence: UNRESOLVED
```

Two dealer-described numbered copies were located as catalogue/dealer leads, but no readable decisive interior pages from a verified 1990 first edition were acquired.

The section remains confirmed at page 95 in the inspected 1991 third edition only. Its 1991 page position cannot be transferred backward into the 1990 edition.

### Reopening evidence

- a verified numbered 458-page 1990 copy;
- title, copyright, limitation, and contents pages;
- the decisive section pages;
- a first-to-third-edition page-level comparison.

---

## Session 059 — *The Dulce Book*, *The Dulce Wars*, and *Cosmic Conflict*

### Question

Do these titles represent one work under several names, retitled editions, expansion or abridgement states, distinct compilations sharing chapters, or a mixed editorial family?

### Bounded result

```yaml
classification: PARTIAL
outcome: ITEM_IDENTITY_UNRESOLVED
```

The acquired Internet Archive *Dulce Book* digital carrier preserves a 34-item contents structure and Branton-associated internal material, but it does not establish a commercial print edition.

*The Dulce Wars* remained catalogue-level only. *Cosmic Conflict* lacked a decisive carrier. A similarly labelled Internet Archive item proved to be an off-target Rampalé/Kerson work and was excluded from the target-pair relation test.

No hypothesis—single work, retitle, expansion/abridgement, distinct compilation, or mixed family—was confirmed at item level.

### Reopening evidence

- complete *Dulce Wars* item pages and contents;
- a reliable *Cosmic Conflict* carrier;
- commercial-edition metadata for *The Dulce Book*;
- complete comparable chapter bodies and placement evidence.

---

## Session 060 — Commercial-edition verification

### Question

Can identified commercial editions of *The Dulce Book* and *The Dulce Wars* be verified at item level, and can their edition evidence resolve the editorial relationship?

### Bounded result

```yaml
classification: PARTIAL
acquisition_verdict: PARTIAL
source_critique: PASS_WITH_CORRECTIONS
qc_result: 25_OF_25_PASS
qc_verdict: PASS_WITH_CORRECTIONS
outcome: COMMERCIAL_EDITION_RELATION_UNRESOLVED
```

### Supported findings

*The Dulce Wars* is verified only at reliable-catalogue level. Supported catalogue fields include its title, subtitle, ISBNs, publisher, recorded 1999 date, and Open Library identifiers.

No physical or scanned target-edition pages were acquired. The page-count contradiction remains unresolved:

```text
140 — MARC / Google Books catalogue evidence
150 — Open Library display
152 — reported lead, not located in Session 060
168 — reported lead, not located in Session 060
```

No physical page count was selected.

The reported 2011 *Dulce Wars* state remains unverified. The reported approximately-2003 Global Communications commercial edition of *The Dulce Book* remains not located, not disproven.

The *Dulce Book* OCR findings apply only to the acquired digital carrier. Duplicate Internet Archive files are one carrier represented by multiple uploads, not independent edition witnesses.

The off-target Rampalé item does not resolve the Branton *Dulce Book* versus *Dulce Wars* relationship.

### Outcomes not authorized

- `COMMERCIAL_EDITION_VERIFIED`
- `RETITLE_RELATION_SUPPORTED`
- `EXPANSION_ABRIDGEMENT_RELATION_SUPPORTED`
- `DISTINCT_COMPILATION_RELATION_SUPPORTED`

### Reopening evidence

- front, spine, and back cover;
- title and copyright pages;
- edition or printing statement;
- complete contents;
- Chapter 11 or equivalent Castello Q&A placement;
- Commander X foreword and Branton notes;
- physical page count resolving 140 / 150 / 152 / 168;
- a reliable item or catalogue record for the reported *Dulce Book* commercial edition;
- verification of the reported 2011 state;
- WorldCat/OCLC corroboration;
- comparable item pages sufficient to test retitling, expansion, abridgement, or distinct compilation.

---

## Runtime findings across the four sessions

The research sequence exposed a reproducible distinction between research gaps and runtime visibility gaps:

```text
parent verifies authoritative input
        ↓
private subagent cannot see parent file
        ↓
parent passes complete content or replays result
        ↓
parent writes and hashes durable phase artifact
```

A private sandbox's inability to see a parent-verified file does not mean the research brief was absent. Similarly, a specialist report written only inside a private sandbox is not durable until the parent writes and verifies it.

When direct export was unavailable, complete Eve transcripts were used to reconstruct local recovery copies. Every recovered copy preserved the original Eve path and SHA-256 separately, received its own recovery hash, and was not described as byte-identical.

See [Eve Research Runtime](../docs/EVE_RESEARCH_RUNTIME.md) for the complete runtime and recovery rules.

---

## Persistent research boundaries

- Catalogue metadata is not inspected-item evidence.
- Seller descriptions are leads unless supported by item pages.
- Later-edition content cannot be transferred into an earlier edition.
- Upload dates and internal dates are not automatically publication dates.
- Duplicate mirrors or uploads are not independent witnesses.
- A title variant is not automatically an independent work or edition.
- Inaccessible searches are barriers, not proof of absence.
- Artifact existence remains separate from the truth of claims inside the artifact.
- Final promotion and entity resolution require curator review.
