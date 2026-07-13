# SESSION 025 — Cloud Variant A: Terra Australis Lead List

**Source:** Google Doc tab `t.xuxjjf7kpr4u`  
**Source URL:** https://docs.google.com/document/d/1bRjBuxtBOj0xa9HjhqjGGnY6GKbktzATO4tlGMskh_Y/edit?tab=t.xuxjjf7kpr4u  
**Acquisition status:** `RAW_LEADS — NOT_INGESTED`  
**Record class:** `UNVERIFIED_LEAD`  
**Curator status:** QC REQUIRED

> **Evidence prohibition:** No claim in this file may be cited as evidence in a synthesis, chronology, graph edge, map lineage, or final report unless it has a corresponding item-level `MAP_RECORD` with a dated primary-map scan, institutional catalogue record, and stable archive URL.

## Raw returned material

- Tasman-era maps where Australia begins to be distinguished from the speculative southern land. `[archive]`
- Cook’s second voyage and related charts demonstrating the empirical reduction of Terra Australis to polar regions, paving the way for nineteenth-century Antarctic exploration. `[nationalarchives.gov]`
- Records to build, analogous to the Shaver schema:
  - `TERRA-MAP-001` — `FAMILY_BUCKET`: Early Ptolemaic / Magellanica depictions of a closed southern land.
  - `TERRA-MAP-002` — `FAMILY_BUCKET`: High-baroque *Terra Australis Incognita* maps (Bertius, Ortelius, Hall), with shorelines and speculative toponymy. `[static-prod.lib.princeton]`
  - `TERRA-MAP-003` — `FAMILY_BUCKET`: Tasman-era and Dutch charts separating “New Holland” from a diminishing Terra Australis. `[archive]`
  - `TERRA-MAP-004` — `FAMILY_BUCKET`: Cook-era charts demonstrating the empirical demolition of a temperate southern continent in favor of a polar Antarctica. `[nationalarchives.gov]`
- Proposed deliverable: one Markdown file with dated map entries, archive or scan URLs, short excerpts from legends, and a timeline from hypothetical continent to mapped Antarctica.
- Proposed structural analogy: speculative cartographic Terra Australis → empirically verified Antarctica, compared with speculative underground-world narratives and later document-driven base narratives.

## Family-bucket rule

`TERRA-MAP-001` through `TERRA-MAP-004` are organizational buckets, not historical artifacts. They may group search targets, but they cannot receive Evidence A status and cannot be used as graph nodes representing a single map.

Each bucket must split into item-level records such as:

```text
TERRA-MAP-002-A
TERRA-MAP-002-B
TERRA-MAP-002-C
```

Each item-level record must identify one exact map or edition and include, at minimum:

- exact title;
- creator/mapmaker;
- date and edition state;
- publishing city and language;
- holding institution and catalogue/call number;
- stable primary scan URL;
- exact southern labels or annotations;
- observed, inferred, and speculative features kept separate;
- evidence class and uncertainty notes.

## Promotion gate

A statement may move from `UNVERIFIED_LEAD` to an item-level artifact only after curator review confirms the primary scan and catalogue metadata. A family bucket may never be promoted wholesale.

## Immediate curator note

This output identifies useful research waves and candidate families but does not yet supply exact maps, editions, catalogue records, stable scans, quotations, or source-supported transmission edges. It remains a lead document only.