# Eve Research Runtime

## Status

The current research runner uses the open-source Eve framework pinned to exact version `0.24.6`.

This is a reproducibility baseline, not a custom Eve distribution:

- Eve source has not been modified for this project.
- No Eve fork, patch branch, or custom build has been promoted into the research workflow.
- Any future Eve source experiment must live in a separate repository or worktree.
- The pinned stock runner remains available as the comparison and fallback baseline.

## Current orchestration pattern

The active workflow separates one parent orchestrator from three declared specialist roles:

```text
parent orchestrator
        ├── acquirer
        ├── source-critic
        └── qc-auditor
```

The parent owns the research brief, phase boundaries, final file writes, independent verification, and bounded closure. Specialist agents perform only their declared phase.

The standard client is run with full subagent support and against the pinned local Eve service. Package execution is pinned rather than floating to a newer Eve release.

## Phase discipline

A normal research lane proceeds through:

```text
research continuation brief
        ↓
acquisition
        ↓
source critique
        ↓
QC audit
        ↓
bounded closure
        ↓
output manifest
        ↓
verified recovery archive
```

Each phase receives explicit stop rules. Agents must not silently promote catalogue metadata into inspected-item evidence, inaccessible searches into negative proof, or repeated mirrors into independent witnesses.

## Workspace and sandbox behavior observed

The following behavior was observed under the stock `0.24.6` runner:

- `/new` creates a fresh ephemeral `/workspace`.
- A file copied into a static sandbox template may not appear in an already-running session.
- A declared subagent may receive a private sandbox that cannot see a parent-verified file.
- A subagent-private write may not persist into the parent workspace.
- The parent can still hold and verify the authoritative phase inputs.

A private-subagent visibility failure is therefore recorded as a runtime visibility discrepancy, not automatically as a missing research artifact or substantive evidence gap.

## Parent-write rule

When a specialist returns a complete report, the parent must:

1. preserve the complete returned text;
2. write the final phase artifact itself;
3. verify that the file exists;
4. calculate the parent-side SHA-256;
5. keep the specialist result and parent artifact boundaries explicit.

This avoids treating an unverified private-sandbox path as durable output.

## Recovery-integrity rule

When an Eve parent-side artifact cannot be exported directly and must be reconstructed from a complete transcript:

- record the original Eve parent-side path;
- record the original Eve parent-side SHA-256 separately;
- label the local copy as recovered or reconstructed;
- calculate a separate SHA-256 for the recovered copy;
- never claim byte identity unless independently verified;
- preserve the original bounded verdict and evidence limitations.

Recovery changes the carrier, not the authorized research conclusion.

## Credential and generated-state boundary

Credentials belong in `.env` only and must never be committed. Public examples may contain variable names but no real values.

Generated Eve state such as `.eve/` is runtime material, not research evidence and not repository content.

Recommended exclusions include:

```gitignore
.env
.env.*
.eve/
```

## Future source-build exploration

Eve is also relevant to the separate Wave–Kilo Integrated Supervisor architecture because it provides an open-source reference for:

- parent/subagent orchestration;
- isolated workspaces and execution boundaries;
- typed delegation and task lifecycle control;
- streaming, cancellation, and restart behavior;
- model routing;
- durable artifact export and recovery.

The likely first experimental patch would target parent/subagent workspace visibility plus automatic durable artifact export. That work is exploratory only and is not authorized as part of the current reproducible research runner.

## Curator boundary

Eve automates acquisition, criticism, QC, and preservation. It does not replace curator authority.

No first source, canonical identity, authenticated authorship, canonical edge, resolved chronology, or final entity resolution may be promoted without Sean's curator review and the repository's normal evidence rules.
