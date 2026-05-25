# Lenses

```text
Status: Draft framework documentation
Review Status: review_required
Delivery Ready: false
Production Ready: false
Market Validated: false
```

## Role In The Framework

A **lens** is a reusable semantic structuring surface in the **DesignLogic Framework**. It identifies what kind of attention, material, boundaries, and artifacts matter for a bounded activity. Lenses help applied work remain explicit about scope, context, evidence, implementation concerns, and review needs.

```text
DesignLogic Semantic Runtime Architecture
= public architecture layer

DesignLogic Framework
= applied reusable modules built from the architecture

DesignLogic Apps
= products and capabilities built from the framework
```

Lenses belong to the applied framework layer. DesignLogic Apps may use lenses in their own documented contexts, with their own implementation evidence, validation, review, and authorization.

## Core Boundary

```text
A lens structures attention and artifact formation.
A lens is not authority, proof, or implementation.
```

## Why Lenses Matter

Lenses give work a declared semantic frame before conclusions or downstream artifacts are formed. A lens can identify included material, excluded material, claim limits, required handoffs, or validation expectations without turning those declarations into evidence or authority.

| Lens contribution | Framework use |
| --- | --- |
| Scope clarity | Identifies what the bounded activity may inspect, form, or report. |
| Semantic continuity | Records relevant definitions, context, and unresolved questions across an artifact lifecycle or handoff. |
| Claim restraint | States what evidence or validation can and cannot support. |
| Boundary visibility | Makes review and authority needs explicit before downstream use. |

## Current Lens Family

| Lens | Primary concern | Document |
| --- | --- | --- |
| Execution Lens | Bounded task direction, permitted surfaces, validation, and reporting. | [execution-lens.md](execution-lens.md) |
| Context Lens | Admitted context, exclusions, assumptions, and continuity. | [context-lens.md](context-lens.md) |
| Evidence Lens | Evidence available for a claim and the safe conclusion boundary. | [evidence-lens.md](evidence-lens.md) |
| Backend Lens | Definitions, artifact flow, system surfaces, and implementation boundaries. | [backend-lens.md](backend-lens.md) |

## Relationship To Framework Surfaces

| Framework surface | Lens relationship |
| --- | --- |
| SDS and App SDS | A lens may structure definition work or review context; a definition is not implementation proof. |
| Artifact contracts | A lens may guide artifact formation or handoff content; artifact structure is not correctness. |
| Authority boundaries | A lens may expose where review or authority is required; it does not grant either. |
| Verification surfaces | A lens may state validation expectations or evidence needs; validation result is not universal truth. |
| Model pipeline surfaces | A lens may identify governed records or claim boundaries; dataset admission or registration is not model quality or deployment approval. |

## What Lenses Do Not Establish

A lens does not establish implementation completion, runtime governance enforcement, semantic correctness, product validation, model quality, customer acceptance, deployment readiness, production readiness, certification, or market validation. It does not authorize a decision, an execution, a release, or a deployment.
