# SESSION 034 — Independent-Convergence Pilot Brief

**Target:** `RQ-034`  
**Mode:** schema validation through a bounded historical comparison  
**Status:** OPEN — acquisition only

## Objective

Test the new `OBSERVATION_REPORT` and `CONVERGENCE_CLUSTER` schemas on a small historical dataset before using them for modern UAP or other large anomaly catalogues.

The pilot asks:

> When different polar observers reported distant land, mountains, open water, or other horizon anomalies, which similarities came from shared environment, shared scientific expectations, direct transmission, later harmonization, or independent observation?

## Candidate pilot family

Acquire three to five exact primary records from reported polar phantom-land or open-water cases. Candidate leads include:

- John Ross and the reported Croker Mountains, 1818;
- Yakov Sannikov or Eduard Toll and Sannikov Land;
- Robert Peary and Crocker Land, 1906;
- Donald MacMillan's later Crocker Land expedition observations;
- Benjamin Morrell and New South Greenland;
- comparable open-water observations by Kane or Hayes.

These names are leads only. Select records based on primary-source accessibility and clear chronology.

## Required record for each observation

Create one `OBSERVATION_REPORT` containing:

```text
observer full name
role and expedition
ship or field party
observation date and local time
reported coordinates
viewing direction
weather, temperature, visibility, and horizon conditions
original wording
page/image locator
first publication date
maps or sketches
instrument use
later corrections or retractions
known prior expectations or theories
media/publication exposure before the observation
```

## Source requirements

Prioritize:

1. ship logs, journals, diaries, letters, field notes, and original expedition narratives;
2. original charts or sketches;
3. institutional scans and catalogue records;
4. later expedition reports addressing the same claimed feature;
5. modern atmospheric or geographic analysis only after the historical record is fixed.

Do not use an encyclopedic summary as the only source.

## Independence test

For each pair, determine:

- whether the observers knew earlier reports;
- whether they used the same map, theory, or publication;
- whether one expedition was explicitly searching for a previously reported land;
- whether later editors standardized terminology;
- whether observations were recorded before discussion among party members;
- whether multiple reports are actually one report chain.

A later expedition searching for an earlier named land is **not an independent first observation**.

## Environmental and ordinary-cause test

Collect evidence concerning:

- superior mirage or Fata Morgana conditions;
- temperature inversion;
- cloud banks;
- sea ice, grounded ice, or ice islands;
- known land beyond the horizon;
- visibility geometry and Earth curvature;
- dead-reckoning and coordinate uncertainty;
- observer elevation;
- optical-instrument limits.

Do not classify a case as mirage merely because later writers use that label. Locate the environmental or observational basis.

## Feature matrix

Normalize only after preserving raw wording. Compare:

- apparent mountains or coastline;
- color and contrast;
- apparent elevation;
- duration;
- persistence under movement;
- bearing changes;
- sketch or map shape;
- distance estimate;
- disappearance;
- multiple-observer agreement;
- later failure to relocate.

## Required cluster outputs

Build at least two `CONVERGENCE_CLUSTER` records:

### Cluster A — same claimed feature across expeditions

Example structure:

```text
earlier reported land
        ↓ known or unknown exposure
later expedition searches or reports it
```

This tests source transmission and expectation.

### Cluster B — similar observation structure in geographically separate cases

Example structure:

```text
distant mountain-like horizon feature
later not found
possible inversion or ice explanation
```

This tests environmental and perceptual convergence without assuming one shared object.

## Required classifications

Use only supported outcomes:

- `SAME_EVENT_ORDINARY_CAUSE`
- `SHARED_ENVIRONMENTAL_TRIGGER`
- `COMMON_PERCEPTUAL_ERROR`
- `CULTURAL_OR_MEDIA_TRANSMISSION`
- `INVESTIGATOR_CONTAMINATION`
- `LATER_NARRATIVE_HARMONIZATION`
- `INDEPENDENT_PARALLEL`
- `DATA_INSUFFICIENT`
- `UNKNOWN`

## Deliverables

1. Three to five exact `OBSERVATION_REPORT` records.
2. At least two `CONVERGENCE_CLUSTER` records.
3. Source-chain and exposure graph.
4. Feature matrix preserving agreement and contradiction.
5. Environmental/common-cause tests.
6. Failed-search log.
7. Critique of the schemas, including fields that were impossible or misleading.
8. No metaphysical or extraterrestrial conclusion.

## Copy-paste cloud-agent prompt

> Read `docs/METHODOLOGY.md`, `docs/INDEPENDENT_CONVERGENCE_METHOD.md`, `schemas/OBSERVATION_REPORT.md`, `schemas/CONVERGENCE_CLUSTER.md`, `research_questions/RQ-034-INDEPENDENT-OBSERVATIONAL-CONVERGENCE.md`, and `research_inbox/SESSION_034_INDEPENDENT_CONVERGENCE_METHOD_LEADS.md`. Execute `research_inbox/SESSION_034_CONVERGENCE_PILOT_BRIEF.md`. Select three to five primary historical polar phantom-land or open-water observation records with exact dates, coordinates, original wording, editions, page/image locators, instruments, weather/visibility, prior expectations, and later corrections. Build separate Observation Reports, then at least two Convergence Clusters. Test source independence, shared maps/theories, later harmonization, temperature inversions, sea ice, visibility geometry, and coordinate error. A later expedition searching for an earlier named land is not an independent first observation. Preserve contradictions and failed searches. Return raw acquisition only; do not declare an extraordinary phenomenon or create a canonical cross-domain edge.
