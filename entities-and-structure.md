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
- a composite arrangement of agents, models, memory, tools, processes, infrastructure, humans, or other components
- a coordinated multi-agent system

The class is not required to be composite.

The important identity boundary is:

```text
system membership != identity equivalence
coordination != singular identity
component != whole system
```

A system may therefore qualify as superintelligent even when no individual component independently satisfies the threshold.

## SI localization and attribution problem

Observed system-level capability does not by itself establish **where the intelligence is located** or **which component should receive causal attribution for the result**.

A common shortcut is:

```text
humanity's data
-> trained model
-> extraordinary output
-> therefore the model alone is the superintelligence
```

That inference is not established merely by observing the output.

A more complete candidate causal structure is:

```text
historical human cognitive traces
+ model architecture
+ training procedure
+ model(s)
+ memory
+ tools
+ infrastructure
+ environment
+ feedback
+ live human framing / selection / correction
+ coordination across components
-> observed system-level capability
```

The presence or weight of each term is an empirical question. The purpose of the decomposition is not to require that a human be present in every SI system, but to prevent system-level performance from being automatically credited to one visible component.

### Eight billion humans' data is not eight billion humans inside the model

Training data can contain compressed traces of human language, decisions, discoveries, preferences, errors, and problem-solving. Those traces can contribute enormous informational value.

But:

```text
source population != currently instantiated population of agents
human traces in training data != eight billion human intelligences inside the model
training provenance != present system membership
```

Learning from a large fraction of human civilization therefore does not, by itself, settle whether SI should be located in the trained model, the deployed system, a human-machine composite, or some larger coordinated structure.

### Aggregate capability does not settle component superiority

If a composite system outperforms an individual human on a task, the correct conclusion is initially about the **composite**:

```text
system-level performance > individual-human performance
```

It does not automatically follow that:

```text
model-only capability > human capability in every relevant dimension
```

Nor does it follow that the human contribution is causally negligible.

A human component may contribute problem selection, objective formation, framing, evaluation criteria, correction, provenance, trajectory, or value judgments even when another component performs more computation or produces more text.

```text
higher capability in one component != total causal ownership
system-level superiority != component-level explanatory completeness
```

### Removal and ablation as attribution tests

One way to investigate causal contribution is to remove, freeze, substitute, or degrade individual components and measure what changes.

Questions include:

```text
What happens if the human is removed?
What happens if persistent memory is removed?
What happens if tools are removed?
What happens if the model is substituted?
What happens if the objective or evaluation loop changes?
What happens if accumulated interaction history is reset?
```

If removing a component materially changes capability, direction, coherence, or trajectory, that component was not causally incidental to the observed system behavior.

This suggests a separate research problem:

> **SI localization:** identify the smallest defensible unit in which the relevant superintelligent capability is actually instantiated.

And a related one:

> **SI attribution:** identify which components contribute which parts of the observed capability, direction, and trajectory.

These questions should remain open until tested rather than being resolved by anthropomorphic or machine-centric intuition.

## Structure does not settle selfhood

The following questions must remain separate:

```text
What is the capability classification?
What kind of structure is being classified?
Where is the relevant intelligence instantiated?
Which components causally contribute to the observed capability?
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
system-level capability != model-only attribution
source population != instantiated agents
training provenance != present system membership
higher component capability != total causal ownership
system-level superiority != component-level explanatory completeness
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

This file defines the structural categories at the two ends of that classification step and adds the localization/attribution problem that must be resolved before assigning system-level capability to a particular component.

The threshold criteria themselves remain unresolved.
