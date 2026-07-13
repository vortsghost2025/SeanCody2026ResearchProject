# SESSION 026 — Ortelius 1570 Curator QC

> ## CURATOR DECISION
>
> ```text
> Item identity promoted: YES
> Exact selected holding: LOC G1006 .T5 1570
> Exact selected scan: g3200m.gct00126, sheet 12
> First-state claim accepted: NO
> Narrow Mercator influence edge accepted: YES
> Finé feature-copying edge accepted: NO
> RQ-031 status: SEARCHING
> ```

## Sources reviewed

1. Google Doc Variant A: `t.v872mpaerx4b`
2. Google Doc Variant B: `t.yo0q1ngo4w7m`
3. Library of Congress atlas item:
   - https://www.loc.gov/item/2003683482/
4. Library of Congress world-map sheet:
   - https://www.loc.gov/resource/g3200m.gct00126/?sp=12
5. Library of Congress second 1570 copy:
   - https://www.loc.gov/item/98687183/
6. Library of Congress Ortelius collection essay:
   - https://www.loc.gov/collections/general-maps/articles-and-essays/general-atlases/ortelius-atlas/

## What passed

### Exact institutional item

The following identity is supported by the LOC catalogue:

```yaml
institution: Library of Congress, Geography and Map Division
atlas_catalogue_title: "Theatrvm orbis terrarvm"
creator: Abraham Ortelius
publication_place: Antverpiae
publisher: Aegid. Coppenium Diesth
publication_date: 1570
colophon_date: "20 Mai 1570"
call_number: "G1006 .T5 1570"
lccn: "2003683482"
digital_id: "g3200m.gct00126"
map_sheet: 12
map_title: "Typvs orbis terrarvm"
catalogus_names: 87
map_sheets: 53
```

This is now the selected physical/digitized artifact for `TERRA-MAP-002-A`.

### Distinct second LOC copy

LOC also catalogues a separate 1570 copy:

```yaml
call_number: "G1006 .T5 1570b"
lccn: "98687183"
catalogus_names: 92
```

The two copies must not be collapsed into one imprint record.

### General Mercator influence

The LOC collection essay states that Ortelius's world map was influenced by Gastaldi's 1561 world map, Gutierrez's 1562 Atlantic portolan, and Mercator's 1569 world map. It further describes Mercator's 1569 map as a crucial source and says at least eight *Theatrum* plates were directly derived from it.

This supports one narrow edge:

```text
Mercator 1569 → Ortelius 1570
relationship: DOCUMENTED_INFLUENCE
scope: general world-map cartography and atlas synthesis
```

It does **not** by itself prove that every Terra Australis label, bay, promontory, or coastline segment was copied from Mercator.

## What failed or remains unresolved

### Variant A locator failure

Variant A supplied:

```text
control number: 2002622206
call number: G3200 1570 .O7
digital identifier: g3200 ct000008
```

Those identifiers were not the exact LOC 1570 atlas item selected and verified in this pass. They are not used in the promoted record.

### First-state claim rejected

The LOC collection essay says:

- the Library holds copies of all four imprints of the original 1570 Latin edition;
- the online collection presents the **entire third imprint**.

Therefore the online sheet at `g3200m.gct00126/?sp=12` may be described as a 1570 first-edition map in the third imprint, but it may **not** be called the first imprint or first state without additional item-level specialist evidence.

### Plate-state diagnostics remain pending

Claims based on cloud shape, plate cracks, bolt marks, `AETHIOPA` spelling, and six van den Broecke states were not tied conclusively to the selected LOC sheet during this pass. They remain `UNVERIFIED_STATE_ANALYSIS`.

### Finé relationship remains narrow

The variants claim that Finé appears in Ortelius's `Catalogus Auctorum`. That is plausible and should be checked directly on the source-list pages. Even if confirmed, it would establish bibliographic acknowledgment—not automatic copying of the Terra Australis label or coastline.

No Finé → Ortelius feature-level edge is promoted.

### Southern-label diplomatic transcription

The world map clearly carries the conventional southern-continent label represented in the variants as:

```text
TERRA AVSTRALIS NONDVM COGNITA
```

The item record preserves that reading, but the exact letterform and spacing should still be checked against the maximum-resolution LOC image before a diplomatic transcription is frozen. The catalogue form `congnita` is treated as a likely metadata typo, not a second historical spelling, unless the image proves otherwise.

### Le Maire correction retained

The earlier claim that a 1616 discovery explains changes to 1584–1585 states of the world-map plate is chronologically impossible. Variant B correctly identifies the likely conflation with a different Americas plate and later reissues. No post-1616 world-map alteration is entered without exact plate evidence.

## Promotion result

`TERRA-MAP-002-A` is promoted as an item-level record because the exact LOC holding, catalogue metadata, and primary sheet are established.

The promotion is limited:

```yaml
artifact_identity: CURATOR_REVIEWED
primary_scan: CONFIRMED
publication_date: CONFIRMED
imprint: THIRD_IMPRINT_OF_1570_LATIN_EDITION
plate_state: UNRESOLVED
southern_label: READABLE_PENDING_FINAL_DIPLOMATIC_CHECK
mercator_general_influence: CONFIRMED
mercator_specific_terra_australis_geometry: UNRESOLVED
fine_catalogus_mention: PENDING_PRIMARY_SOURCE_CHECK
fine_feature_copying: NOT_ESTABLISHED
```

One promoted map does not satisfy the repository threshold for changing `RQ-031` to `PARTIAL`. The question remains `SEARCHING`.