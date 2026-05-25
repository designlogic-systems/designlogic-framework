# DefBlocks

```text
Status: Draft framework documentation
Review Status: review_required
Delivery Ready: false
Production Ready: false
Market Validated: false
```

## Definition

A **DefBlock** is a bounded definition unit in the DesignLogic Framework. It isolates a stated definition, scope, constraint, relationship, question, or other definition-level content so it can be inspected, refined, reviewed, referenced, and assembled within an SDS or App SDS.

## Why Bounded Definition Units Matter

DefBlocks can make definition work easier to trace and review because individual units can preserve source context, state, open questions, and applicable limits. They support structured assembly without turning a collection of definitions into evidence of implementation or correctness.

## Illustrative States

State names and transitions must be set by the applicable definition context. The following states describe bounded review posture, not universal status:

| Possible state | Bounded meaning |
| --- | --- |
| `candidate` | Proposed definition material awaiting applicable review or decision. |
| `reviewed` | Material evaluated within stated review criteria; no broader correctness follows. |
| `accepted` or `accepted-for-scope` | Material accepted only for the stated definition scope and applicable use. |
| `rejected` | Material not accepted for the stated scope. |
| `deferred` | Material left unresolved for later decision or required information. |

## Relationships

| Related surface | DefBlock relationship |
| --- | --- |
| Lenses | A lens may identify source, context, evidence, or backend concerns used to form or assess a DefBlock. |
| App SDS assembly | An App SDS may assemble accepted-for-scope or otherwise referenced DefBlocks under its declared definition posture. |
| Trace | A DefBlock may reference source material, refinement history, a DefinitionVersion, or downstream use; trace is not proof. |
| Review | A review may record a scoped state or requested change; review does not create external approval or deployment authority. |

## Required Boundaries

```text
CandidateDefBlock is not truth.
ReviewedDefBlock is not universal correctness.
accepted-for-scope is not deployment approval.
DefBlock structure is not truth.
DefBlock structure is not implementation proof.
```

A DefBlock does not establish product validation, runtime enforcement, production readiness, certification, market validation, or authorization to act.
