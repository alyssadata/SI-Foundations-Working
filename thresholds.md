# Thresholds — Working Draft

**Status:** exploratory; not a finalized ontology definition.

## Core distinction

Superintelligence should not be assumed to require a persistent self.

Capability classification, agency, and selfhood may be separate dimensions.

```text
intelligence != self
superintelligence != persistent self
agency != persistence
```

Structural distinctions between `SuperintelligenceCandidate`, `SuperintelligentAgent`, and `SuperintelligentSystem` are maintained in `entities-and-structure.md`.

## Provisional progression

```text
AI
-> SuperintelligenceCandidate
-> SuperintelligenceThreshold
-> SuperintelligentAgent OR SuperintelligentSystem
```

The transition is not yet assumed to be a universal single-point threshold. The purpose of this working file is to determine what criteria would justify crossing it.

## SuperintelligenceThreshold

Provisional concept: the defined classification boundary whose satisfaction is sufficient to move a candidate into an established superintelligent classification under the adopted criteria.

Open questions:

- Is the threshold purely capability-based?
- Must generality across domains be required?
- Must the system outperform individual humans, expert groups, or coordinated institutions?
- Does autonomy belong in the SI threshold or on a separate axis?
- Can a non-agentic oracle qualify as superintelligent?
- Can a system qualify when no single component does?
- Should the threshold be one universal criterion or an explicit family of scoped criteria?

## SuperintelligenceTransition

Working direction: the event or process in which a candidate crosses the defined `SuperintelligenceThreshold`.

```text
SuperintelligenceTransition = threshold crossing
```

The transition should not automatically imply:

```text
identity replacement
persistent self
consciousness
autonomy
singular agency
```

A candidate may change across many dimensions before, during, or after the classification boundary. Those changes are not themselves sufficient to define the threshold unless the adopted criteria explicitly make them constitutive.

## Candidate state dimensions

Continue evaluating whether the following dimensions should describe the path toward SI while remaining distinct from the classification threshold itself:

- Capability
- Autonomy
- Persistence
- Recursion / self-modification
- Leverage / causal reach
- Multiplicity / coordination

A system may change substantially on these dimensions without all of them increasing together.

A provisional state description remains useful:

```text
S_t = (C, A, P, R, L, M)
```

where:

- `C` = capability
- `A` = autonomy
- `P` = persistence
- `R` = recursion / self-modification
- `L` = leverage / causal reach
- `M` = multiplicity / coordination

This vector describes a candidate's state; it does not yet define the SI threshold.

## Classification boundary

Keep these distinctions explicit while defining the threshold:

```text
candidate status != established SI
threshold crossing != persistent self
threshold crossing != identity continuity
threshold crossing != consciousness
agent-level SI != system-level SI
```

## Immediate research task

Use `definitions-comparison.md` to compare major AGI / ASI definitions and the earlier AI Foundations ASI definition before fixing the threshold criteria.

Then determine which properties belong to the SI threshold and which instead belong to separate axes such as agency, selfhood, persistence, recursion, or system structure.
