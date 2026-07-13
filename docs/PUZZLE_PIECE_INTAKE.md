# Puzzle-Piece Intake Method

## Purpose

The project does not require Sean to package every observation as a formal research assignment.

Sean supplies pieces that appear connected across domains, times, cultures, religions, technologies, publications, projects, model outputs, or lived observations. The curator determines what each piece is, where it belongs, what it may connect to, and what evidence would be required to strengthen or reject the connection.

The observed connection is the starting signal, not the conclusion.

## Division of roles

### Sean — systems perception

Sean identifies:

- pieces that appear structurally related;
- recurring forms across different domains;
- timelines that may intersect;
- old architecture that appears inside newer work;
- unexpected continuity between projects;
- questions that arise from the shape of the system rather than from one isolated fact.

Sean is not required to pre-classify, normalize, cite, or prove the piece before submitting it.

### Curator — preservation, classification, and testing

The curator must:

1. Preserve the submitted piece and its provenance.
2. Determine whether it is a source, claim, entity, motif, system, chronology event, propagation event, model observation, negative record, or unresolved question.
3. Separate what the piece says from whether it is true.
4. Trace relevant timelines backward toward earliest known appearances.
5. Compare geography, culture, language, religion, nationality, publication networks, and later reinterpretations.
6. Distinguish documented transmission from resemblance.
7. Preserve contradictions instead of forcing a clean narrative.
8. Route unresolved material to quarantine or the research-question queue.
9. Promote only what survives the required level of verification.

## Accepted input forms

A puzzle piece may be:

- a Google Doc tab;
- a repository or file;
- an image or screenshot;
- a quotation;
- a model response;
- a remembered connection;
- a book, myth, religion, theory, map, place, person, event, or date;
- an architectural pattern from an earlier project;
- a contradiction between two outputs;
- a failed search;
- an intuition that two systems share the same underlying structure.

## Routing logic

| Piece type | Primary destination |
|---|---|
| Raw model or human output | `research_inbox/` |
| Person, organization, publication, place, expedition | entity object |
| Statement made by a source | claim object |
| Recurring symbolic or narrative feature | motif object |
| Multi-domain interacting structure | system object |
| Dated appearance or transformation | chronology object |
| Movement between places, cultures, languages, or media | propagation object |
| Relationship between objects | transmission edge |
| Unresolved contradiction or weakly supported item | `data/quarantine/` |
| Explicit unanswered problem | `research_questions/` |
| Search performed with no useful result | negative-evidence object |
| Session-level synthesis | `reports/` |

A single submitted piece may produce several objects.

## Cross-project architecture rule

A repository may be relevant even when its surface domain is not.

For example, an old project may contain useful architecture for:

- multi-model disagreement;
- state persistence across disposable agents;
- role specialization;
- provenance;
- verification gates;
- checkpointing;
- externalized memory;
- model handoffs;
- regression tracking;
- preserving failures as data.

The curator should extract the architectural pattern rather than importing the old domain wholesale.

A private repository must not be copied into a public repository without explicit approval. Sensitive code, credentials, financial details, personal data, and domain-specific operational material remain private. Only a sanitized abstraction may be proposed for public use.

## Evidence discipline

The following must remain distinct:

- the piece exists;
- a source made a claim;
- two pieces resemble one another;
- contact or shared infrastructure existed;
- transmission is documented;
- influence is documented;
- the underlying factual claim is true.

The project may map all seven without collapsing them into one judgment.

## Working principle

Sean does not need to explain the whole puzzle before submitting a piece.

The curator's job is to determine whether the piece:

- fills an existing gap;
- creates a new branch;
- changes a timeline;
- exposes a contradiction;
- reveals an architectural ancestor;
- belongs to another system entirely;
- or should remain unconnected until more evidence appears.

The system must remain capable of saying both:

> This connection is structurally important.

and

> This connection is not yet historically demonstrated.
