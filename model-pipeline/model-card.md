# Model Card

```text
Status: Draft framework documentation
Review Status: review_required
Delivery Ready: false
Production Ready: false
Market Validated: false
```

## Definition

A **model card** is a bounded documentation record in the DesignLogic Framework for a separately evidenced model or model candidate. It records declared context, evidence posture, limitations, and authority boundaries. This document defines the record surface; it does not imply that a model exists.

## Model Card Surface

| Record area | Bounded description |
| --- | --- |
| Model identity | Identifies a referenced model or candidate and applicable version or record identity where separately established. |
| Intended use | States declared permitted or proposed uses and excluded interpretations. |
| Source data or dataset references | Identifies admitted datasets, admission records, provenance, or other referenced data context where available. |
| Training or evaluation context | Records available separately evidenced training or evaluation context, criteria, results, and limits; absence must remain visible. |
| Limitations | States known exclusions, missing evidence, unsuitable uses, and unresolved questions. |
| Risk and boundary notes | Records material risks and non-authority limitations relevant to intended use. |
| Evidence posture | States which claims have documented evidence and which remain unsupported or subject to review. |
| Review status | Records applicable review state, reviewer scope, and unresolved review/adjudication needs. |
| Authority boundary | States permissions or approvals still required for use, action, release, or deployment. |

## Use Boundary

A model card may support review of declared model-related information only where its referenced material is available and bounded. It cannot turn absent evidence into a claim, turn an evaluation result into universal correctness, or grant authority to rely on a model output.

## Required Boundaries

```text
Model card is not model quality.
Evaluation result is not universal correctness.
Model card is not deployment approval.
Model output is not authority.
```

A model card does not establish that training occurred, that a model is production-ready, that deployment is approved, or that any app has implemented or accepted model use.
