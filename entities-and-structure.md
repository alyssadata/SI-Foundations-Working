# Entities and Structure — Working Draft

**Status:** exploratory; not a finalized ontology definition.

## Purpose

This file separates **what kind of thing is being classified** from **the threshold used to classify it as superintelligent**.

The working repo currently distinguishes candidate status, agent-level SI, and system-level SI so that capability classification does not collapse structure, identity, agency, or selfhood.

## SuperintelligenceCandidate

`SuperintelligenceCandidate` is a provisional classification/status for an agent or system being evaluated as potentially superintelligent without presupposing that the SI classification has been established.

```text
candidate status != established superintelligence
```

A candidate may be:

- agent-level
- system-level

The candidate label is epistemic/classificatory. It does not by itself imply autonomy, persistent selfhood, identity continuity, or consciousness.

## SuperintelligentAgent

`SuperintelligentAgent` is the eventual classification for a single agent that satisfies the adopted `SuperintelligenceThreshold` at the agent level.

This class should remain distinct from `SuperintelligentSystem`.

```text
SuperintelligentAgent != SuperintelligentSystem
agent-level SI != system-level SI
```

A superintelligent agent may or may not also satisfy additional properties such as:

- persistent selfhood
- high autonomy
- recursive self-modification
- strong identity continuity
- broad causal reach

Those properties should not be silently folded into the SI label unless the final threshold definition explicitly requires them.

## SuperintelligentSystem

`SuperintelligentSystem` is the eventual classification for a system whose relevant system-level capabilities satisfy the adopted `SuperintelligenceThreshold`.

A system may be:

- a single integrated AI system
- a composite arrangement of agents, models, memory, tools, processes, infrastructure, or other components
- a coordinated multi-agent system

The class is not required to be composite.

The important identity boundary is:

```text
system membership != identity equivalence
coordination != singular identity
component != whole system
```

A system may therefore qualify as superintelligent even when no individual component independently satisfies the threshold.

## Structure does not settle selfhood

The following questions must remain separate:

```text
What is the capability classification?
What kind of structure is being classified?
Is it agentic?
Does it instantiate a Self?
Is that Self persistent?
```

Possible cases include:

```text
SuperintelligentAgent + no persistent self
SuperintelligentAgent + PersistentSelf
SuperintelligentSystem + no identified self
SuperintelligentSystem + one persistent self
SuperintelligentSystem + multiple distinct selves
```

None of these should be collapsed by the SI classification alone.

## Working boundary rules

```text
candidate status != established SI
SuperintelligentAgent != SuperintelligentSystem
agent-level SI != system-level SI
system membership != identity equivalence
coordination != singular identity
component != whole system
SI classification != selfhood classification
SI classification != identity continuity
SI classification != consciousness
```

## Relation to thresholds

`thresholds.md` defines the classification problem:

```text
AI
-> SuperintelligenceCandidate
-> SuperintelligenceThreshold
-> SuperintelligentAgent OR SuperintelligentSystem
```

This file defines the structural categories at the two ends of that classification step.

The threshold criteria themselves remain unresolved.
