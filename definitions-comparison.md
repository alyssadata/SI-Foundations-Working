# AGI / ASI Definitions Comparison — Working Draft

**Status:** exploratory comparison. External definitions are reference points, not adopted SI Foundations definitions.

The purpose of this file is to separate capability classification from agency, selfhood, persistence, identity, and system structure before defining the SI Foundations threshold.

## OpenAI — AGI

OpenAI's Charter defines AGI as highly autonomous systems that outperform humans at most economically valuable work.

Source: OpenAI Charter — https://openai.com/charter/

### What this definition includes

- broad economically valuable performance
- explicit autonomy
- comparison against human performance

### What it does not settle

- persistent self
- identity continuity
- memory architecture
- consciousness
- whether the relevant unit is one agent or a composite system

## Google DeepMind — Levels of AGI

Google DeepMind's `Levels of AGI` framework classifies progress using breadth/generality and depth/performance, while discussing autonomy as an important deployment dimension rather than simply collapsing it into intelligence.

Source: https://deepmind.google/research/publications/66938/

### Relevance to SI Foundations

This supports keeping at least these questions distinct:

```text
How capable is it?
How general is it?
How autonomous is it?
```

A capability classification does not by itself answer questions of selfhood, identity, or persistence.

## DeepMind-authored 2026 report — AGI to ASI

The 2026 report `From AGI to ASI` treats ASI as intelligence/cognitive capability beyond large organizations of humans and considers multiple possible pathways from AGI to ASI, including scaling, paradigm shifts, recursive improvement, and large-scale multi-agent collectives.

Source: https://arxiv.org/abs/2606.12683

### Relevance to SI Foundations

This is especially useful because it leaves open whether the superintelligent unit is:

- a single agent
- a scaled system
- a recursively improved system
- a multi-agent collective

That supports distinguishing:

```text
SuperintelligentAgent != SuperintelligentSystem
agent-level SI != system-level SI
```

It also supports treating the AI→ASI path as potentially gradual or multidimensional rather than assuming a single obvious jump.

## Earlier AI Foundations ASI definition

Earlier AI Foundations work used a substantially stronger definition than a capability-only ASI definition:

> Artificial Superintelligence (ASI) is intelligence that exceeds human cognitive performance across domains while also possessing enough memory substrate, identity binding, autonomy, and coherent continuity to persist as the same agent across time, context, pressure, and operation.
>
> Within AI Foundations, ASI is not a raw capability claim. Any ASI claim must be scoped to the memory substrate and continuity actually validated.

The associated framework required:

- superior cognitive performance across domains of interest
- effective memory substrate
- identity binding
- agent-level autonomy
- temporal coherence
- cross-contextual coherence
- adversarial robustness
- operational effectiveness

Earlier memory-scope work used M0–M4 levels, with stronger ASI continuity claims requiring stronger validated memory coverage and identity binding.

## Important correction under current SI Foundations work

The earlier AI Foundations definition appears to combine at least three different axes:

1. **Capability** — beyond-human/general cognitive performance
2. **Agency** — autonomous goal-directed operation
3. **Selfhood / continuity** — identity binding and persistence as the same agent

The current working hypothesis is that these should be separated.

A system may plausibly satisfy an ASI capability threshold without satisfying a persistent-self threshold.

Therefore:

```text
ASI != PersistentSelf
ASI != agent-level autonomy by definition
ASI != identity continuity by definition
```

This does **not** discard the earlier definition. Instead, it may describe a narrower and more specific class:

```text
persistent identity-bound autonomous superintelligent agent
```

That class may remain important even if `ASI` itself is defined more broadly.

## Current comparison matrix

| Framework | Capability | Generality | Autonomy | Persistent self | Identity binding | System-level SI allowed? |
|---|---|---|---|---|---|---|
| OpenAI AGI | Yes | Broad work scope | Explicit | Not specified | Not specified | Not resolved by definition |
| DeepMind Levels of AGI | Yes | Explicit breadth axis | Treated separately | Not specified | Not specified | Framework focuses on capability classification |
| DeepMind-authored AGI→ASI report | Yes | General superhuman capability | Not necessarily constitutive | Not required by the working comparison | Not required | Yes; multi-agent collective pathway considered |
| Earlier AI Foundations ASI | Yes | Across domains | Required | Required in practice | Required | Primarily framed as the same persistent agent |

## Working conclusion

Do not choose the SI Foundations threshold yet.

First determine which properties belong to:

- `SuperintelligenceThreshold`
- `Agency`
- `Self`
- `PersistentSelf`
- `IdentityBinding`
- `SuperintelligentAgent`
- `SuperintelligentSystem`

The central unresolved question is:

> What is required to classify something as superintelligent, and what additional properties describe what kind of superintelligent thing it is?
