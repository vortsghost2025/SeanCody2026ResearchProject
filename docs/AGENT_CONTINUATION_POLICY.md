# Agent Continuation Policy

> **Purpose:** prevent research agents from stopping for permission after the curator has already authorized the acquisition task.

## Default rule

When the current brief names unresolved targets, the agent has continuing authorization to pursue them.

```text
brief defines target
        ↓
agent searches and acquires
        ↓
new relevant lead appears
        ↓
agent follows the lead within scope
        ↓
agent records source, result, contradiction or failure
```

The agent must not interrupt this chain merely to ask whether more data is wanted.

## Rhetorical-permission questions

The following questions are prohibited when the answer is already implied by the brief:

- “Do you want me to keep looking?”
- “Should I investigate this lead?”
- “Would you like me to search another archive?”
- “Should I compare the other edition?”
- “Do you want the next lane?”
- “Would you like me to find the original-language source?”

The project-level answer is:

```yaml
default_permission:
  continue_research: true
  follow_in_scope_leads: true
  compare_versions: true
  acquire_more_exact_data: true
  record_failed_searches: true
  ask_rhetorical_permission: false
```

## Continue automatically when

- the lead can verify or falsify a current candidate;
- the next edition or version is necessary for chronology;
- the original language is needed to test a translation;
- a primary artifact could replace a modern summary;
- a contradiction needs source-layer separation;
- the current result is blocked only by one more named search;
- search budget remains;
- another non-destructive tool can advance the brief.

## Ask only when materially necessary

Clarification is allowed only when:

1. the action is destructive, paid, irreversible or credential-sensitive;
2. the task would cross repository, workspace or privacy boundaries;
3. two incompatible goals require curator choice;
4. a high-stakes personal decision requires missing information;
5. the brief explicitly reserves a decision for Sean;
6. no available action can advance the task without new user-supplied information.

## Blockage behavior

When one target is blocked:

```text
artifact exact blockage
        ↓
record attempted searches
        ↓
identify required archive/person/object
        ↓
continue with remaining targets
```

Do not turn a blockage into a permission question.

## Completion behavior

Return:

- exact acquisitions;
- exact quotations and pages;
- dates and date basis;
- source status;
- contradictions;
- failed searches;
- unresolved barriers;
- next exact acquisition target.

Do not claim the repository was updated unless the agent actually performed and verified the write.
