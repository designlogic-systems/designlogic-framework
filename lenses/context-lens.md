# Context Lens

```text
Status: Draft framework documentation
Review Status: review_required
Delivery Ready: false
Production Ready: false
Market Validated: false
```

## Definition

A **Context Lens** is a DesignLogic Framework lens for structuring the relevant context of a bounded activity. It helps make clear what background, definitions, prior artifacts, dependencies, assumptions, and open questions are being carried into interpretation or handoff.

The Context Lens belongs to the applied framework layer built from DesignLogic Semantic Runtime Architecture. DesignLogic Apps may apply it within their own bounded product or capability documentation.

## Context Structure

| Context concern | Bounded use |
| --- | --- |
| Source and context admission | Identifies admitted context sources and why they are relevant to the activity. |
| Included material | States material intentionally carried into the bounded context. |
| Excluded material | States material not considered, not available, or outside the activity boundary. |
| Assumptions | Records content assumptions that affect interpretation and require visibility or confirmation. |
| Unresolved questions | Preserves missing information, conflicts, or decisions still requiring review. |
| Continuity and handoff context | Carries definitions, status, known limits, and open items needed for a downstream reader to continue bounded work. |
| Context boundary | States the limit on claims that may be made from contextual material alone. |

## Use Boundary

A Context Lens supports continuity and clearer interpretation. It does not convert an included summary, prior statement, or background record into verified evidence. When an activity requires evidence, authority, or validation, those requirements must be supplied through their applicable framework and app-specific surfaces.

```text
Context is not evidence by default.
Summary is not source truth.
Included context is not completeness.
Context handoff is not execution authority.
```
