# FLOOD Record ID Registry

This registry prevents ID collisions and distinguishes delivered records from reserved future work. Session headings must list only IDs actually delivered; reserved IDs must remain explicitly marked.

| ID | Status | Description | Session |
|---|---|---|---|
| FLOOD-001 | DELIVERED | Master comparative flood record | 009 |
| FLOOD-002 | DELIVERED | Atra-Hasis / Ziusudra | 009 |
| FLOOD-003 | DELIVERED | Gilgamesh Tablet XI | 009 |
| FLOOD-004 | DELIVERED | Genesis / Noah | 009 |
| FLOOD-005 | DELIVERED | Deucalion | 009 |
| FLOOD-006 | DELIVERED | Manu | 009 |
| FLOOD-007 | DELIVERED | Egypt negative record | 009 |
| FLOOD-008 | DELIVERED | Zoroastrian drought variant | 009 |
| FLOOD-009 | DELIVERED | Gun-Yu flood | 013 |
| FLOOD-010 | DELIVERED | Nüwa sky-patching | 013 |
| FLOOD-011 | DELIVERED | Southwest China brother-sister type | 013 |
| FLOOD-012 | DELIVERED | Aztec Fourth Sun / Nahui-Atl | 013 |
| FLOOD-013 | DELIVERED | Maya Popol Vuh wooden people | 013 |
| FLOOD-014 | DELIVERED | Mesoamerican comparative analysis | 013 |
| FLOOD-015 | DELIVERED | Polynesian comparative record | 014 |
| FLOOD-016 | DELIVERED | Melanesian traditions | 014 |
| FLOOD-017 | DELIVERED | Ojibwe / Algonquian earth-diver | 014 |
| FLOOD-018 | DELIVERED — QUARANTINE PENDING SOURCE | Lakota tradition; primary ethnography required | 014 |
| FLOOD-019 | DELIVERED — SOURCE REMEDIATION REQUIRED | Pima / Cherokee / Apache / Mandan composite | 014 |
| FLOOD-020 | DELIVERED | Global distribution / negative evidence | 014 |
| FLOOD-021 | RESERVED | China non-Han traditions | 022 queued |
| FLOOD-022 | RESERVED | West Africa — Yoruba / Fon / Dogon / Akan | 022 queued |
| FLOOD-023 | RESERVED | West Africa continued | 022 queued |
| FLOOD-024 | RESERVED | West Africa continued | 022 queued |
| FLOOD-025 | RESERVED | Andean traditions — Inca / Viracocha / Unu Pachakuti | Future |
| FLOOD-026 | RESERVED | Central American non-Maya traditions | Future |
| FLOOD-027 | RESERVED | Pacific Northwest earth-diver deep dive | 023 queued |
| FLOOD-028 | RESERVED | Sub-Arctic / Inuit traditions | 023 queued |
| FLOOD-029 | RESERVED | South American traditions — Tupinamba / Cañari | Future |
| FLOOD-030 | RESERVED | Comparative master for Americas block | Future |

## Registry rules

1. Never assign a reserved ID to a different subject.
2. A record is counted only after a canonical JSON file exists and validates.
3. `DELIVERED` means present in session research, not canonical ingestion complete.
4. Session headings must match actual delivered IDs.
5. Changes to this registry require a descriptive commit message and corresponding session or issue reference.
