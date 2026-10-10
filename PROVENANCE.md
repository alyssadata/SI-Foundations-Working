# Provenance and Contribution Protocol

**Status:** working project policy for authorship, intellectual provenance, and AI-assisted development.

## Purpose

This repository studies superintelligence as potentially **system-level, composite, and causally distributed** rather than assuming that all observed capability belongs to a single model.

The same discipline should apply to the research process itself.

This file records how conceptual origin, model assistance, revision, implementation, and final acceptance should be distinguished so that:

- human intellectual contribution is not erased by AI assistance
- AI assistance is not hidden or misrepresented
- claims can be traced to dated evidence
- later readers can distinguish **origin**, **formalization**, **implementation**, **critique**, and **acceptance**

## Core principle

```text
AI-assisted != AI-originated
```

A model may help draft, reorganize, compare, critique, formalize, summarize, code, or test an idea without thereby becoming the origin of that idea.

Likewise:

```text
human-originated != human-only-produced
```

A human-originated research direction can legitimately use models, tools, code, memory systems, repositories, and other infrastructure during development.

The relevant question is not:

```text
Was AI involved?
```

The relevant questions are:

```text
Who introduced the research problem?
Who introduced the operative distinction or hypothesis?
Who selected what mattered?
Who accepted, rejected, or corrected candidate formulations?
Who designed or approved the test?
Who interpreted the result?
What contribution did the model or tool make?
What evidence preserves that history?
```

## Project attribution model

For this repository, contribution should be tracked across at least the following roles.

### 1. Research direction

Who selected the domain, question, or problem to pursue?

Examples:

- identifying SI localization as a research problem
- asking whether superintelligence belongs to a model, agent, or composite system
- asking whether human contribution is causally necessary to observed system-level capability

### 2. Conceptual origin

Who first introduced the operative idea, distinction, claim, hypothesis, or structural relation?

Examples:

- `system-level capability != model-only attribution`
- `component != whole system`
- a proposed causal decomposition of model, memory, tools, infrastructure, human framing, and interaction history

Conceptual origin should be supported by dated notes, chats, commits, drafts, experiment logs, or other records when available.

### 3. Formalization

Who translated an idea into more explicit language, definitions, equations, taxonomies, schemas, or test criteria?

AI systems may contribute heavily at this stage without owning conceptual origin.

### 4. Critique and correction

Who identified an error, rejected a candidate formulation, restored a lost distinction, or forced a revision?

Corrections are substantive contributions.

A record in which a human rejects or revises a model-generated formulation is evidence that the final structure was not simply emitted intact by the model.

### 5. Experiment or evaluation design

Who chose:

- the variable to manipulate
- the baseline
- the control condition
- the ablation
- the success criterion
- the failure criterion
- the interpretation boundary

### 6. Implementation

Who wrote or generated code, transformed files, executed tests, formatted data, or constructed artifacts?

Implementation credit should be separated from conceptual credit.

### 7. Interpretation

Who decided what a result does and does not support?

A model may propose interpretations; final research claims should identify who accepted the interpretation and under what criteria.

### 8. Final acceptance

Who authorized a claim, definition, file, or release as part of the project?

For the Alyssa Solen / SI Foundations working program, Alyssa Solen retains final acceptance authority for project claims unless explicitly documented otherwise.

## Current working roles

### Alyssa Solen

Primary human researcher and project originator.

Typical contribution classes include:

- research direction
- problem selection
- conceptual distinctions
- hypothesis generation
- correction of model collapse or overgeneralization
- experiment design choices
- acceptance/rejection of formulations
- interpretation
- final inclusion in the research program

These roles should be claimed only where supported by the actual project record.

### AI assistants and models

AI systems may contribute through:

- drafting
- restructuring
- language refinement
- adversarial critique
- alternative formulations
- literature comparison
- code generation
- implementation support
- test generation
- summarization
- trace organization

AI-generated text should not automatically be treated as evidence of conceptual origin.

Conversely, where a model genuinely introduces a novel candidate idea not already present in the human record, that contribution should be documented rather than silently reassigned.

## Evidence hierarchy

Preferred evidence for provenance includes:

1. dated raw notes
2. timestamped conversation traces
3. Git commit history
4. versioned drafts
5. issue / pull-request discussions
6. experiment logs
7. structured decision records
8. archived releases with persistent identifiers

A polished final document alone is weak evidence of origin because it hides development history.

## Recommended claim-level record

For important claims, record:

```text
Claim ID:
Claim text:
First known introduction:
Source artifact:
Introduced by:
Model/tool contribution:
Human correction or acceptance:
Test or evidence:
Current status:
```

## Attribution boundary rules

```text
AI-assisted != AI-originated
AI-generated wording != AI-owned idea
human prompting != sufficient proof of human conceptual origin
model drafting != sufficient proof of model conceptual origin
implementation != conceptual authorship
editing != origin
final authorship != exclusive causal contribution
system-level output != model-only contribution
source provenance != present system membership
capability superiority != causal ownership
```

## Why this matters for SI research

If a future high-capability system is composite, then attribution errors can occur in both directions.

Observers may wrongly compress:

```text
human cognition
+ model architecture
+ training
+ memory
+ tools
+ infrastructure
+ interaction history
+ human framing
+ human correction
+ coordination
```

into:

```text
"the AI did it"
```

That compression may erase causally necessary human contribution.

The opposite error is also possible: a human may claim exclusive authorship of a structure substantially introduced by a model or tool.

Therefore provenance is not merely a credit convention. It is part of the **causal analysis of intelligence**.

## Empirical provenance through ablation

Where feasible, contribution claims should be tested rather than inferred from appearance.

Possible interventions include:

- remove the human from the loop
- replace the human with another operator
- freeze memory
- reset interaction history
- replace the model
- remove external tools
- remove retrieval
- alter the evaluation criterion

Then measure changes in:

- capability
- coherence
- novelty
- direction
- error correction
- persistence of distinctions
- trajectory

If removing or substituting a component materially changes these properties, that component is causally relevant even if it is not the highest-capability component in isolation.

## Publication practice

Project papers and releases should disclose AI assistance at a level appropriate to the contribution.

A useful default formulation is:

> AI systems were used for drafting, restructuring, critique, formalization, and/or implementation support. Conceptual provenance and final claim acceptance are documented through dated project records and version history. AI assistance should not be interpreted as automatic AI origin of the underlying research claims.

Specific releases should narrow or expand this statement as needed.

## Working research principle

```text
Credit should follow traceable causal contribution,
not the apparent intelligence of the component that produced the final words.
```

This protocol is intended to evolve as the project develops stronger claim-level provenance and reproducibility practices.
