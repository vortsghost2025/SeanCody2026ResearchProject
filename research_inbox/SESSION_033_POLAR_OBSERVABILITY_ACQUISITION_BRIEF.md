# SESSION 033 — Polar Observability Acquisition Brief

**Target:** `RQ-033`  
**Mode:** primary-source instrument, route, and entity-resolution audit  
**Status:** OPEN — acquisition only

## Objective

Determine what Jeremiah N. Reynolds's era could directly observe, weakly constrain, or not test at all concerning:

- polar openings;
- navigable polar seas;
- coastlines and land sightings;
- sub-ice or subsurface structures;
- planetary internal structure.

Do not treat lack of observational capacity as evidence that a feature existed.

## Phase A — Jeremiah N. Reynolds, 1829 private expedition

Locate exact primary records for the private expedition associated with Reynolds:

```text
ship names
captains and officers
route and dates
highest or southernmost latitudes
weather and sea-ice conditions
navigation instruments
soundings and measurement methods
landings and observations
mutiny/termination records
Reynolds's own role and journal statements
```

Return exact editions, pages, archive identifiers, and quotations.

## Phase B — instrument capability

For each instrument actually documented, record:

```yaml
instrument:
measurement:
range_or_precision:
shipboard_use:
weather_or_ice_limitations:
primary_manual_or_log:
what_claim_it_could_test:
what_claim_it_could_not_test:
```

Prioritize:

- sextant/octant;
- chronometer or lunar-distance methods;
- compass and magnetic dip/variation instruments;
- lead-line sounding;
- thermometer and barometer;
- telescope;
- charting and dead reckoning.

Do not list modern technologies merely because they were absent; establish the historical capability from manuals, inventories, or logs.

## Phase C — Symmes claim observability matrix

Separate at least these hypotheses:

| Claim | Directly testable by surface voyage? | Weakly constrained? | Requires later methods? |
|---|---|---|---|
| giant navigable polar opening |  |  |  |
| persistent warm polar sea |  |  |  |
| small under-ice passage |  |  |  |
| subglacial basin/lake |  |  |  |
| large crustal cavity |  |  |  |
| planet-scale hollow interior |  |  |  |

Every cell must cite an instrument, route, log, or later geophysical method.

## Phase D — Wilkes Expedition entity and sighting audit

Keep these people separate:

```text
Jeremiah N. Reynolds — advocate / organizer / writer
William Reynolds — passed midshipman aboard Peacock
```

For every Antarctic sighting attributed to `Reynolds`, return:

```text
full name
rank
ship
journal/log source
observation date
reported coordinates
exact quotation
other named witnesses
later geographic identification
modern coordinate comparison
```

Do not use modern summaries as the sole source.

## Phase E — wrong-place test

For selected routes, quantify or bound:

- celestial-navigation error;
- longitude uncertainty;
- dead-reckoning accumulation;
- sea-ice drift;
- ship diversion;
- visibility and mirage risk;
- chart uncertainty.

Classify each claimed mismatch as:

- `POSITION_ERROR_PLAUSIBLE`;
- `ICE_BLOCKED_ACCESS`;
- `VISIBILITY_OR_MIRAGE_RISK`;
- `COORDINATE_MATCH_SUPPORTED`;
- `FEATURE_NOT_OBSERVABLE_WITH_CARRIED_INSTRUMENTS`;
- `UNKNOWN`.

## Failure and negative evidence

Record:

- missing logs;
- inaccessible archives;
- uncertain names;
- contradictory coordinates;
- later map corrections;
- claims that cannot be tied to a primary record.

## Deliverables

1. Exact expedition source records.
2. Instrument inventory with capability limits.
3. Symmes claim-observability matrix.
4. Jeremiah/William Reynolds entity table.
5. Three to seven sighting-coordinate records.
6. Evidence for and against practical wrong-location scenarios.
7. Later-technology comparison.
8. Failed-search log.
9. Recommended classifications only; no canonical metaphysical conclusion.

## Copy-paste cloud-agent prompt

> Read `RESEARCH_ATLAS.md`, `research_questions/RQ-033-POLAR-OBSERVABILITY-LIMITS.md`, `research_inbox/SESSION_033_POLAR_OBSERVABILITY_WILKES_LEADS.md`, `data/entity_resolution/ENTITY-RESOLUTION-001-JEREMIAH-WILLIAM-REYNOLDS.md`, and `graph/bridges/BRIDGE-032-003-REYNOLDS-PIVOT.md`. Execute `research_inbox/SESSION_033_POLAR_OBSERVABILITY_ACQUISITION_BRIEF.md`. Work only on what nineteenth-century polar expeditions could actually observe or falsify. Obtain primary logs, crew lists, instrument inventories, navigation methods, soundings, ice/weather records, coordinates, and exact quotations. Keep Jeremiah N. Reynolds separate from William Reynolds of the Wilkes Expedition. Build a claim-observability matrix for giant polar openings, navigable polar seas, under-ice passages, subglacial basins, crustal cavities, and planet-scale hollow interiors. Distinguish access failure from nonexistence and inability to observe from positive evidence. Return failed searches and uncertainty. Do not declare Hollow Earth confirmed or disproved as a single undifferentiated claim.
