# Execution Lens

```text
Status: Draft framework documentation
Review Status: review_required
Delivery Ready: false
Production Ready: false
Market Validated: false
```

## Definition

An **Execution Lens** is a DesignLogic Framework lens for structuring a bounded task or operation. It makes the permitted material, change surface, intended outcome, limits, validation expectations, and reporting obligation visible before work is interpreted as complete.

It is a reusable applied module built from DesignLogic Semantic Runtime Architecture. A DesignLogic App may apply an Execution Lens in an app-specific context, but the app must supply its own evidence and authority for any action.

## What It Identifies

| Element | Purpose |
| --- | --- |
| Available source, material, or context | States what may be read or relied on for the bounded activity. |
| Allowed scope | Identifies permitted activity and explicit exclusions. |
| Intended direction or outcome | States the requested result without implying it has been achieved or approved. |
| Files or surfaces in scope | Names applicable artifact, repository, system, or documentation surfaces. |
| Validation expectations | Declares checks or review needed for the bounded output. |
| Stop or defer conditions | Identifies conflicts, missing authority, missing source material, or unsafe uncertainty that prevent completion. |
| Reporting requirements | States what changed, what was checked, what remains unresolved, and what boundary applies. |

## Compact Structure

| Layer | Content |
| --- | --- |
| `Availability` | Admitted sources and materials; surfaces available to read, use, or change; excluded material. |
| `Direction` | Intended output, bounded task, applicable deliverables, and reporting requirement. |
| `Orientation` | Definitions, layer relationship, context, assumptions, dependencies, and authority limits needed to interpret the task. |
| `Stabilization` | Status posture, required boundaries, validation expectations, stop/defer conditions, and unresolved questions. |

## Use Boundary

An Execution Lens can structure documentation, definition, artifact, verification, or app-oriented work where the allowed activity and reporting boundary are declared. It can support a handoff by making scope and outstanding review visible. It cannot establish that a produced output is correct, authorized, implemented, deployable, or production-ready.

```text
An Execution Lens is not execution authority.
A task instruction is not approval.
A validation expectation is not proof.
Handoff is not deployment.
```
