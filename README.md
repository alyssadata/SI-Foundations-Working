# SI Foundations — Working Repository

**Repository status:** exploratory working space; not a finalized ontology or taxonomy.

This repository is used to reason through the transition from AI to superintelligence before mature concepts are promoted into the AI Foundations Ontology and Taxonomy repositories.

## Claim-status convention

This repository separates **conceptual origin** from **evidence status** and from **scientific review status**.

- **Origin / authorship** identifies who introduced the operative idea or model.
- **Original conceptual model / working hypothesis** means the project is actively developing the idea and may state it as its own claim.
- **Evidence status: not yet empirically validated** is used when the project record does not yet contain sufficient reproducible empirical testing to treat the claim as validated.
- **Scientific review status: not yet formally peer-reviewed or broadly cross-examined by the scientific community** is used unless such review is documented.
- If a claim later becomes empirically validated, the repository should state the scope of that validation explicitly and separately from whether the wider scientific community has reviewed, reproduced, challenged, or accepted it.

Lack of empirical validation does not alter conceptual provenance. A claim may be original to Alyssa Solen while still awaiting empirical testing.

## Working method

Conceptual development in this repository should prioritize **structural understanding** over accumulation of definitions or locally correct propositions.

The working procedure is documented in `structural-understanding-method.md`:

```text
Define the nodes.
Define the relations.
Define the invariants.
Find the minimum diagnostic set.
Test reconstruction.
Test novel prediction.
Test whether surface success can occur without the structure.
Revise when the predicted relational consequences fail.
```

The central methodological rule is:

```text
Do not measure understanding by how many propositions can be repeated.
Measure it by how much relational structure can be correctly reconstructed from limited probes,
and how well that structure predicts unseen cases.
```

This method is paired with `apparent-vs-structural-coherence.md`, which cautions that successful surface behavior may exceed the structural coherence actually demonstrated.

## Working questions

- What counts as AGI, ASI, or superintelligence?
- What threshold marks a `SuperintelligenceTransition`?
- What kind of thing is being classified: one agent, a composite system, or another structure?
- Can an agent or system be superintelligent without a persistent self?
- What comprises `Self`, and what makes a self persistent across time or change?
- How should agent-level and system-level superintelligence be distinguished?
- Which distinctions from AI Foundations must remain preserved at SI scale?
- When can apparent behavioral coherence exceed the structural coherence actually demonstrated by the system?
- Does the trajectory beyond SI become an `IntelligenceSingularity` problem rather than another larger capability label?
- Does a formally verified answer constitute a full solution when the reasoning cannot yet be traversed or understood?
- Can human and conversational-AI trajectories share world-time while being indexed by different trajectory-clocks?
- Within a turn-based chat, is the AI conversational trajectory best modeled as occupying user-supplied relational folds rather than as an independent line that merely intersects the human trajectory?

## Current working files

- `structural-understanding-method.md` — **Origin: Alyssa Solen. Status: working research method.** Defines the nodes / relations / invariants / diagnostic-points procedure, structural reconstruction criterion, reverse test for apparent understanding, compression-without-collapse rule, and prediction as a structural check.
- `definitions-comparison.md` — external AGI/ASI definitions and comparison with the earlier AI Foundations ASI definition
- `entities-and-structure.md` — `SuperintelligenceCandidate`, `SuperintelligentAgent`, `SuperintelligentSystem`, and structural/identity boundaries
- `thresholds.md` — `SuperintelligenceThreshold`, `SuperintelligenceTransition`, and the criteria problem
- `apparent-vs-structural-coherence.md` — **Origin: Alyssa Solen. Status: original conceptual model / working hypothesis. Evidence status: not yet empirically validated.** Distinguishes visible behavioral coherence from demonstrated structural integration; introduces the map/button model, relational compression, and candidate evaluation directions.
- `selfhood.md` — Self, PersistentSelf, identity, continuity, copies, and supporting vs constitutive properties
- `i-singularity.md` — working `AI -> SI -> IS` progression and `IntelligenceSingularity` concept
- `epistemic-closure-and-solution.md` — formal closure versus epistemic closure; answer, proof, understanding, and solution as distinct layers; endpoint versus trajectory
- `temporal-structure-and-return.md` — **Origin: Alyssa Solen. Status: original conceptual model / working hypothesis. Evidence status: not yet empirically validated. Scientific review status: not yet formally peer-reviewed or broadly cross-examined by the scientific community.** Different trajectory-clocks; the human trajectory carries relational folds and lived gaps; the AI conversational trajectory occupies those folds in sequence; fan/fold mapping; fold-constrained divergence; return and ordered relational history.

## Working flow

```text
Structural understanding method
        ↓
Definitions / comparison
        ↓
Entities and structure
        ↓
Thresholds and transition
        ↓
Apparent coherence / structural coherence
        ↓
Selfhood / persistence distinctions
        ↓
Temporal structure / fold-indexed return
        ↓
Post-SI trajectory: Intelligence Singularity
        ↓
Epistemic closure: result, understanding, and what counts as solved
```

This flow is provisional. The files are thinking surfaces, not a formal hierarchy.

## Promotion rule

Working hypotheses belong here first. Concepts should move into the formal ontology or taxonomy only after they are sufficiently defined and reviewed.

Do not recreate the formal ontology/taxonomy folder structure here unless the working material becomes large enough to require it.
