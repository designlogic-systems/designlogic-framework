# Evidence Lens

```text
Status: Draft framework documentation
Review Status: review_required
Delivery Ready: false
Production Ready: false
Market Validated: false
```

## Definition

An **Evidence Lens** is a DesignLogic Framework lens for structuring evidence-related material and the boundaries of a claim under review. It makes visible the evidence that is available, evidence that is missing, the conclusion that the material can safely support, and where review or adjudication is still required.

It is an applied reusable module built from DesignLogic Semantic Runtime Architecture. Its use within a DesignLogic App does not replace product-specific validation or authority.

## Evidence Structure

| Evidence concern | Bounded use |
| --- | --- |
| Claim under review | States the specific conclusion being considered rather than allowing an implied general claim. |
| Available evidence | Identifies admitted material relevant to that claim and its declared source or trace where available. |
| Missing evidence | Records evidence not present but required to support, narrow, or reject the claim. |
| Evidence strength | Describes how directly admitted evidence supports the stated claim within the review boundary; it is not an invented score or metric. |
| Overclaim risk | Identifies conclusions that would exceed the available evidence or confuse structure with proof. |
| Safe conclusion boundary | States the most bounded conclusion supported for the stated purpose. |
| Review or adjudication need | Identifies where a qualified review, authority decision, or defined adjudication remains required. |

## Metric And Trace Boundary

Where a framework surface defines metrics, including a PASDA-related surface, a metric must be derived through its applicable admitted signals, rules, formulas, and required review or adjudication. Evidence descriptions, traces, assertion counts, self-assessment, or contextual material do not independently establish a metric or its truth.

## Use Boundary

```text
Evidence structure is not truth.
Metric is not truth.
Trace is not proof.
Claim support must match available evidence.
Review is bounded, not universal truth.
```

An Evidence Lens can help prevent overclaiming in framework documentation and app-specific review material. It cannot establish correctness, certification, model quality, deployment readiness, production readiness, or market validation.
