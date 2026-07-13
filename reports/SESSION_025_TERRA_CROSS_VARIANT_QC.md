# SESSION 025 — Terra Australis Cross-Variant QC

> ## TOP-LEVEL CURATOR STATUS
>
> ```text
> Acquisition variants received: 3
> Core item-level candidates identified: 5
> Extended map/event/reinterpretation leads: preserved
> Curator-promoted map records: 0
> Canonical transmission edges: 0
> Canonical findings: 0
> RQ-031 status: SEARCHING
> ```
>
> Agreement between models is not independent source verification. All records below remain candidates until the exact item, catalogue metadata, scan, legend, and relationship evidence pass curator review.

## Sources compared

- **Variant A:** Google Doc tab `t.cocjh043fuw4` — concise, self-declared artifact ingestion.
- **Variant B:** Google Doc tab `t.tpdmcjv83hvi` — detailed draft with item candidates and a claimed complete lineage.
- **Variant C:** uploaded Kilo export `Pasted text(3).txt` — broader chronology and reinterpretation layer, truncated at the output limit.

Full provenance is recorded in `research_inbox/SESSION_025_TERRA_VARIANT_MANIFEST.md`.

## Strongest cross-variant agreement

All three outputs converge on a useful five-node research spine:

1. a fifteenth-century printed Ptolemaic world map;
2. Ortelius's 1570 *Typus Orbis Terrarum*;
3. a Bertius South Polar / Terra Australis map from the early seventeenth century;
4. the Bonaparte–Tasman map or closely related Tasman voyage cartography;
5. Cook's 1777 chart of the Southern Hemisphere.

This agreement establishes **research priority**, not canonical facts. The exact holdings, states, dates, titles, call numbers, and annotations still require item-by-item verification.

## Blocking contradictions

| Topic | Variant A | Variant B | Variant C | Curator decision |
|---|---|---|---|---|
| Session identity | Calls itself `SESSION_024` | Calls itself `SESSION_024` | Executes Session 025 brief | Normalize all under Session 025; preserve original labels as source metadata |
| Mercator/Ortelius direction | `Ortelius 1570 → Mercator 1569` | Usually describes Mercator as a source for Ortelius | Describes Mercator/Fine/Ortelius as a chain | Variant A direction is chronologically reversed; no edge promoted |
| Ortelius/Bertius direction | `Bertius 1616 → Ortelius 1570` | Describes shared publisher/family network and later Bertius reuse | Treats Bertius as downstream | Variant A direction is reversed; shared network alone is not transmission |
| Tasman call number | `ML 800` | `ML 863` | No consistently verified item identifier | Exact State Library record must be opened and copied before promotion |
| Tasman date | `ca. 1644` | After 1644; possibly `ca. 1695`, derived from a 1644 source map | Preserves post-1644 uncertainty | Record creation date, source-data date, and heraldic date separately |
| Bertius title | `Descriptio Terrae Substralis` | `Descriptio Terrae Subaustralis`; printed title `Magallanica sive Terra Australis Incognita` | Uses related title forms | Exact printed title and catalogue title must be separate fields |
| Finé phrase origin | Not resolved | Says Finé coined the phrase in 1534 | Points to Schöner/Fine candidates with earlier dates | `UNKNOWN`; locate the earliest surviving artifact carrying the exact phrase |
| Ortelius plate chronology | General 1570 claim | Six states dated 1570–1585, then connects an alleged erasure to Le Maire Strait in 1616 | Does not validate the state sequence | Chronology is internally impossible as written; quarantine until plate/state source is checked |
| Cook's role | Chart designed to refute Dalrymple | Marks death of speculative Terra Australis | More cautiously distinguishes temperate-continent rejection from possible polar land | Preserve only the narrower claim after primary journal/chart review |
| 1820 priority | Not covered | Declares Bellingshausen first confirmed | Preserves Bellingshausen/Bransfield/Palmer dispute | Keep competing claims; no priority resolution without exact logs and calendar handling |
| Ptolemy | Enclosed Indian Ocean becomes structural southern-land requirement | Attributes balancing continent and later terminology directly to Ptolemy | Separates Ptolemaic enclosed-ocean geography from later naming | Do not project `Terra Australis` terminology backward onto Ptolemy |

## Edge audit

### Variant A edge failures

1. **`Ortelius 1570 → Mercator 1569`** is reversed in time. The accompanying explanation actually argues for Mercator influencing Ortelius.
2. **`Bertius 1616 → Ortelius 1570`** is reversed in time. A later map may reuse Ortelius-era labels, but the stated edge cannot represent historical transmission.
3. **`Cook 1777 → Dalrymple 1770`** mixes chronology and semantics. If Cook responds to or refutes Dalrymple, the record needs a relationship such as `RESPONDS_TO` or a documented influence/refutation note—not a generic transmission edge in the current direction.

### Variant B edge overclassification

- Being named in Ortelius's `Catalogus Auctorum` can establish bibliographic acknowledgment, but it does not automatically prove that a specific southern coastline, label, or plate geometry was copied from every listed author.
- Family ties and shared publishers establish a network, not `DIRECT_CITATION` or `KNOWN_COPY` by themselves.
- A probable model or likely source is not a direct citation unless the artifact or a reliable bibliographic source explicitly says so.
- The claimed 1570–1585 plate-state sequence cannot be explained by a 1616 discovery without identifying a later plate, later state, or separate map.

### Variant C edge limitations

- Several edges rely on Wikipedia, commercial map descriptions, or general historical summaries rather than item-level catalogue notes or page-cited scholarship.
- At least one edge reuses a record ID already assigned to another map, so the edge table cannot be imported safely.
- The output was truncated before its failed-search section and acquisition summary were complete.

## Candidate promotion table

| Candidate | Why it matters | Blocking requirement | Status |
|---|---|---|---|
| Ptolemaic world map, Ulm 1482 | Establishes the printed enclosed-Indian-Ocean model | One exact holding, shelfmark, scan, printed labels, and distinction from later Terra Australis theory | `ITEM_CANDIDATE` |
| Ortelius, *Typus Orbis Terrarum*, 1570 | Major atlas amplification node | Exact 1570 item/state, stable scan, southern-label transcription, and page-cited source analysis | `ITEM_CANDIDATE` |
| Bertius South Polar map, 1616 | Dedicated South Polar / Terra Australis representation | Exact printed title, catalogue title, edition/state, institution, identifier, scan, and plate-reuse evidence | `ITEM_CANDIDATE` |
| Bonaparte–Tasman map | Bridges voyage data and changing Australian geography | Resolve catalogue ID, object date versus source-data date, authorship, and what the artifact actually leaves blank or connected | `ITEM_CANDIDATE` |
| Cook, Southern Hemisphere chart, 1777 | Empirical constraint on a temperate southern continent | Exact museum/library item, scan, chart annotations, voyage-account context, and careful statement of what Cook did and did not establish | `ITEM_CANDIDATE` |
| Mercator world map, 1569 | Possible source for Ortelius | Open one surviving institutional scan and identify the exact southern labels and geometry | `UNVERIFIED_LEAD` |
| Oronce Fine map, 1531/1534 | Early named southern-continent representation | Resolve exact artifact/date and the earliest occurrence of the disputed Latin phrase | `UNVERIFIED_LEAD` |
| 1820 observation cluster | Transition to observed Antarctic geography | Exact logs/charts, calendar conversion, feature observed, and competing priority claims | `EVENT_CLUSTER_LEAD` |
| Mallery/Hapgood ice-free reinterpretation | Modern myth-transmission layer | Earliest exact publication, edition, page, quoted claim, invoked map, and criticism | `REINTERPRETATION_LEAD` |

## Canonical status decision

Neither Google Doc's self-declared `INGESTED`, `COMPLETE`, `CANONICAL`, `UPDATED`, or confidence language is accepted.

The repository now recognizes:

- three preserved acquisition variants;
- five high-priority item candidates;
- several extended leads;
- a set of explicit contradictions and edge failures.

It does **not** yet recognize a canonical Terra Australis chronology or transmission chain.

## Next curator pass

Do not request another broad overview. Verify the five core item candidates one at a time:

1. open the exact institutional catalogue page;
2. record the item identifier and shelfmark exactly;
3. open the primary scan or IIIF image;
4. transcribe the relevant southern label or legend;
5. separate observed, inferred, copied, and speculative geography;
6. verify edition/state/date;
7. create an edge only when a source identifies copying, citation, shared plate, adaptation, or documented influence.

After three or more item records pass that gate, `RQ-031` may be reconsidered for `PARTIAL` status.
