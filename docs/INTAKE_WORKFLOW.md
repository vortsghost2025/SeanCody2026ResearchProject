# Research Intake Workflow

## Default rule

Sean may submit raw ideas, research exports, Markdown files, JSON candidates, spreadsheets, scans, or source lists without organizing them first.

## Routing pipeline

1. **Acquire** — place the untouched batch in `research_inbox/`.
2. **Audit** — check duplication, entity identity, source quality, dates, quotations, IDs, and schema fit.
3. **Classify** — route each finding as one of:
   - canonical candidate
   - update to existing record
   - source object
   - connection edge
   - map record
   - person or institution record
   - hypothesis
   - negative-evidence record
   - research question
   - quarantine
   - duplicate or deprecated item
4. **Validate** — apply the canonical base schema and any cluster schema.
5. **Commit** — preserve provenance and use a descriptive commit message.
6. **Recompute** — counts come from committed machine-readable records, never prose estimates.

## Repository lanes

- `research_inbox/` — unreviewed acquisitions
- `research_questions/` — questions and hunches, not facts
- `data/claims/` — accepted canonical records
- `data/quarantine/` — preserved but unresolved candidates
- `reports/` — audits, ingestion reports, and state summaries
- `schemas/` — base and cluster validation contracts

## Autonomy rule

Routine organization, schema-safe corrections, registry maintenance, quarantine decisions, and documentation updates may be performed directly. Large-scale crawling, OCR, bulk source acquisition, and mass record conversion should be delegated to an agent when available, then audited before ingestion.
