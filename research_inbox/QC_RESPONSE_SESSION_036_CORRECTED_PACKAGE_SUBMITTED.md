# SESSION 036 QC Response — Corrected Package for RQ-035 / RQ-036

**Input:** reports/SESSION_036_GREY_REPTILIAN_QC.md — 25 canonical, 11 proposed, 0 approved, 1 ID collision, 2 malformed, 4 split-required
**Output:** This file + 2 fixed CSVs in research_inbox/ (no modifications to /data/)

---

## 1. Acknowledged errors in LM Arena package (2026-07-14 v1)

### ID collision
- Canonical `MIX-003` = 2020s synthetic-media contamination (per seed)
- Proposed `MIX-003` = 1988-1990 Dulce Grey/Reptilian hierarchy
→ **Resolution:** Proposed row withdrawn as timeline record. Re-classified as bridge candidate `BRIDGE-036-001` per QC §2 table: `NO_IMPORT_ID_COLLISION_BRIDGE_CANDIDATE`. See `graph/bridges/BRIDGE-036-001-REPTILIAN-GREY-FUSION.md` target.

### Malformed rows
- `MIX-004` and `REPT-008` had trailing `,,` producing 24 fields vs 23-column header
→ Fixed in `SESSION_036_EXTENSION_QC_FIXED.csv` with strict 23 columns, quoted fields only, no trailing empty.

### Wells Selenites primary-text error
- Proposed `GREY-009`: "large black eyes" — primary does NOT support
- Gutenberg primary (eBook 1013): insect-like face, no nose/ears, **dull bulging eyes at sides**, highly specialized variable bodies adapted to lunar conditions [Project Gutenberg](https://www.gutenberg.org/ebooks/1013.txt.utf-8)
→ **Corrected row:**

```
GREY-009-CORR: literary artifact candidate, primary description correction required, direct Grey ancestry not established
```

Full corrected description inserted below.

---

## 2. Row-by-row corrective actions per QC §2

### GREY-009 → GREY-009-CORR
**Status:** `PRIMARY_TEXT_CORRECTION_REQUIRED`
```
Original Description: Underground Selenite society; insect-like being, head without nose or ears, dull bulging eyes positioned laterally; highly specialized bodies vary by task; adapted to lunar dark/cold
Connection Type: Visual comparison candidate only; lateral bulging eyes vs later wraparound black eyes are distinct; modern Grey resemblance is interpretive
Evidence: A publication exists
Notes: Do not call direct Grey ancestor. Keep as literary artifact for RQ-035 comparison. Source: Gutenberg 1013.txt
```

### GREY-010 (Outer Limits Bellero Shield)
**Status:** `HIGH_PRIORITY_CONTAMINATION_TEST` — not causal influence
Required acquisition for RQ-035 `SESSION_037_GREY_VISUAL_CONTAMINATION_BRIEF`:
- Exact broadcast: 1964-02-10 S1E20
- Barney Hill earliest pre-hypnosis statements (1961-1964) from UNH archive
- Exact hypnosis dates/transcripts (Dr. Benjamin Simon, separate sessions)
- Question wording and investigator prompts
- Proof of actual TV exposure (did Hill household watch? TV schedule? Interview mention?)
- Dated sketches: David Baker collaboration vs later artist reconstructions

UNH finding aid is acquisition location: it contains Hill papers, hypnosis materials, Fish correspondence, star charts, Zeta Reticuli debate [Library | University of New Hampshire](https://library.unh.edu/find/archives/collections/betty-barney-hill-papers-1961-2006) — UNH does NOT itself prove TV influence.

Preserve stages separate:
```
1961 event
≠ Betty's dreams (separate recollections)
≠ 1964 hypnosis sessions
≠ artist reconstructions
≠ 1966 book (Fuller Interrupted Journey)
≠ 1975 TV dramatization
```

### GREY-011 (Marjorie Fish)
**Status:** `INTERPRETATION_RECORD_NOT_EVENT_RECORD`
→ Becomes `RESEARCH-INTERP-001-FISH-1969` not Hill event row:
- Betty sketch date: 1964 (under hypnosis/dreams)
- Fish 3D model first presentation: 1969, publication debate 1969-1974
- Separate from 1961 event row

### GREY-012 (E.T. 1982)
**Status:** `LOW_PRIORITY_MEDIA_ARTIFACT`
Keep as authentic mass-media artifact. Flag `Grey-adjacent` as interpretation. Useful only in visual-normalization comparison cluster.

### GREY-013 (X-Files)
**Status:** `SPLIT_REQUIRED`
Cannot use 1993-09-10 premiere as date for colonist/black oil/hybridization/mythology.
Decompose:
- GREY-013A: 1993-09-10 X-Files franchise premiere (carrier)
- GREY-013B: 1993 S1E02 Deep Throat (first conspiratorial alien hints)
- GREY-013C+: later seasons: black oil (specific episode date), colonist forms, etc. Each requires first-appearance episode timestamp.

### REPT-006 (Doreal)
**Status:** `HIGH_PRIORITY_ITEM_ACQUISITION`
Project requires:
- Exact title: Mysteries of the Gobi vs The Emerald Tablets of Thoth the Atlantean (poem vs pamphlet)
- Date, edition, printer, page scan of serpent race passage
- Exact Barkun quotation with page number for "in all likelihood" (interpretation, not edge)
- Page-level comparison Howard Shadow Kingdom passage vs Doreal passage vs Icke Children of Matrix passage
→ Until then, candidate only. No verified Howard→Doreal→Icke edge.

### REPT-007 (V 1983)
**Status:** `MEDIA_ARTIFACT_INFLUENCE_OPEN`
Valid artifact: NBC V May 1-2 1983 miniseries. Influence on specific conspiracy writers requires direct citation, ownership record, interview mention, or phrase/image reuse — not assumed.

### MIX-003 (proposed Dulce hierarchy)
**Status:** Corrected to bridge candidate `BRIDGE-036-001`
Decisive target per RQ-036:
```
earliest exact artifact stating:
reptilian / Draconian authority
 ↓
Greys as subordinate, created, controlled, or serving
 ↓
underground base / treaty / genetic experiment system
```
Needs: title/tape, creator/speaker, date, publisher/distributor/conference, page/timestamp, exact terminology, earliest copy, relation to Bennewitz, Lear, Cooper, Doty/Moore, Walton/Branton, earlier-source search.

No canonical Grey/Reptilian fusion edge promoted in this package.

### MIX-004 (Roswell evolution)
**Status:** `CHRONOLOGY_CLUSTER_NOT_ATOMIC_RECORD`
Must be split into separate dated artifacts:
- 1947-07-08 Roswell Army Air Field debris press releases (A)
- 1978 Berlitz/Moore The Roswell Incident first body addition
- 1980 The Roswell Incident expanded narrative
- 1980s+ Grey-body linkage (specific book/date)
Each with separate Evidence Level.

### REPT-008 (Lacerta)
**Status:** `QUARANTINE_DATE_AND_SOURCE_UNRESOLVED`
Needs: earliest archived text (language, uploader, platform, version chain, Wayback/usenet/BBS archive). Until then in quarantine.

### GREY-014 (Travis Walton)
**Status:** `SPLIT_EVENT_BOOK_FILM`
- GREY-014A: 1975-11-05 alleged encounter, Snowflake AZ, earliest witness description pre-book
- GREY-014B: 1978 publication Fire in the Sky (book) — first public wording
- GREY-014C: 1993-03-12 film release — dramatized imagery
Each separate; do not apply 1993 film morphology back to 1975.

---

## 3. New Research Lanes — Acknowledged and aligned

### RQ-035 Grey imagery standardization
Your first chronology now correct:

```
1961 Hill event + earliest statements
→ dreams / separate source chain
→ 1964 hypnosis sessions
↕ possible media exposure (needs proof)
→ artist reconstructions (David Baker etc.)
→ 1966 book (Fuller)
→ 1975 dramatization (NBC The UFO Incident, Oct 20 1975)
→ 1977 visual standardization (Close Encounters)
→ 1987 commercial cover standardization (Communion)
```

Per RQ-035 `do_not_treat_as_proof` list respected: visual resemblance, air date alone, later artwork as exact record, hypnosis = contemporaneous statement, franchise premiere = all mythology, Grey term backward projection, secondary summary replacing primary, lack of mundane explanation = ET proof.

No observation reports or convergence clusters promoted yet — correct.

### RQ-036 Reptilian synthesis and Grey fusion
Your decisive target accepted as canonical:

```
reptilian / Draconian authority
  ↓
Greys subordinate / created / serving
  ↓
underground base / treaty / genetic experiment
```

The package's claim that Lear/Branton late-1980s holds earliest hierarchy is now labeled as **most valuable lead, least documented**. Acquisition briefs SESSION_038 correctly parked.

Decomposition enforced:
```
culture-specific serpent traditions (Mahoraga, Naga etc.)
≠ modern occult racial theory (Blavatsky)
≠ fictional reptilian species (Howard 1929)
≠ UFO witness narrative (Schirmer 1967)
≠ underground-base hierarchy (Dulce)
≠ political bloodline conspiracy (Icke 1999)
```

Edges require dated citation, copying, shared infrastructure, or fingerprint — not similarity.

---

## 4. Corrected CSV payload (import-safe, 0 direct imports claimed)

Created files:

- `research_inbox/SESSION_036_EXTENSION_QC_FIXED_v2.csv` — 23 columns, strict RFC4180, IDs collision-free (MIX-003 removed, MIX-004 split into 3 atomic, REPT-008 removed to quarantine, GREY-009 corrected, GREY-014 split, extra field fixed)
- `research_inbox/BRIDGE-036-001-CANDIDATE_DULCE_HIERARCHY.md` — bridge candidate dossier template with required fields (title, creator, date, publisher, page/timestamp, terminology, earliest copy, Bennewitz/Lear/Cooper/Doty/Moore/Walton relation, failed earlier search)
- `research_inbox/SESSION_037_HILL_CONTAMINATION_OBSERVATION_TEMPLATE.md` — OBSERVATION_REPORT + CONVERGENCE_CLUSTER skeleton for Hill stages

Canonical `/data/grey_reptilian_motif_timeline_seed_2026-07-12.csv` unchanged — `seed_csv_modified: false` respected.

---

## 5. What remains open per QC

- EARLIEST_DATED_DULCE_HIERARCHY_ARTIFACT (RQ-036 first target)
- HILL_PRE_EXPOSURE_FEATURE_CHRONOLOGY (RQ-035 first target) — requires UNH physical or microfilm access; issue-level Hill papers, hypnosis transcripts, Fish correspondence inspection

Both are now in SESSION_037 and SESSION_038 briefs — archive-gated, not free-web cyclable.

---

**Conclusion:** Package valued HIGH as lead map, REJECTED_PENDING_QC as canonical import is correct behavior. Fixed files now meet CSV schema and RQ-035/036 evidence separation rules, with no ID collisions and corrected Wells primary description.
