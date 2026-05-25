# DesignLogic Framework Glossary

```text
Status: Draft framework documentation
Review Status: review_required
Delivery Ready: false
Production Ready: false
Market Validated: false
```

These are public-facing, bounded meanings for this repository. A term names a framework surface or relationship; it does not by itself establish implementation, authority, correctness, readiness, or validation.

| Term | Public framework meaning |
| --- | --- |
| **USS** | The internal source architecture / deep canon from which a public DesignLogic-facing architecture is translated. This repository does not assert USS canon authority. |
| **DesignLogic Semantic Runtime Architecture** | The public DesignLogic-facing translation of USS and the architecture layer from which the DesignLogic Framework is built. This repository is not that architecture itself. |
| **DesignLogic Framework** | The applied reusable-module layer built from DesignLogic Semantic Runtime Architecture and documented in this repository. |
| **DesignLogic Apps** | Products and capabilities built from framework modules. Each app has its own evidence, review, and readiness posture. |
| **semantic backend** | A backend-oriented framework perspective for structuring meaning, definitions, artifacts, trace, and bounded decisions; the term does not imply an implemented runtime. |
| **lens** | A reusable perspective for structuring a bounded view of a problem, context, evidence, or backend surface. A lens is not decision authority. |
| **Execution Lens** | A lens that bounds an execution task, including the surfaces available for inspection or change, required outcomes, and validation expectations. |
| **Context Lens** | A lens that structures relevant context for an applied activity without converting context into evidence or authority. |
| **Evidence Lens** | A lens that structures evidence-related material and the limits on claims that may be drawn from it. |
| **Backend Lens** | A lens that structures backend framework work, including definitions, artifact flow, boundaries, and verification posture. |
| **SDS** | A structured definition surface for a system or capability within the framework. An SDS is not proof of implementation. |
| **App SDS** | An SDS scoped to a DesignLogic App or capability built from the framework. It does not establish product validation or readiness. |
| **DefBlock** | A bounded definition unit named by the framework. Its applicable contract determines its required content and permitted interpretation. |
| **MRDC** | A named framework artifact concept whose required fields, lifecycle, and interpretation must be established by an applicable contract. The term alone carries no readiness claim. |
| **DefinitionVersion** | A versioned identity or record for a definition, used to distinguish referenced definition states. Versioning supports trace; it does not prove correctness. |
| **artifact lifecycle** | The bounded progression of an artifact through defined states, reviews, handoffs, or uses under applicable contracts. |
| **authority boundary** | A documented limit on who or what may authorize a decision or action. Describing a boundary is not enforcing it. |
| **review boundary** | A point at which defined review is required before a bounded transition, conclusion, or use may be accepted. |
| **handoff artifact** | An artifact prepared to transfer bounded information or work between defined contexts. Handoff is not deployment. |
| **executable artifact package** | A packaged artifact intended for a defined execution context. Being execution-ready or executable does not mean execution is authorized. |
| **build brief** | A bounded artifact describing work intended for a build activity. It is not evidence that a build is complete, valid, or approved. |
| **DSVH** | A named framework verification-support surface for bounded validation activities. A DSVH result does not establish universal truth, certification, or deployment readiness. |
| **PASDA** | A measurement surface in which metrics may be derived only through stated derivation and formula rules from atomic PASDA signal records, with review or adjudication where required. LLM self-assessment predicts; PASDA measures; variance compares. |
| **Lens-to-GSM** | A named mapping surface for relating lens-derived information to a GSM-facing representation under an applicable mapping definition. Mapping is not proof or authorization. |
| **dataset admission** | The governed acceptance of a dataset candidate for a specified use under defined criteria and review. Admission is not model quality. |
| **model card** | A bounded documentation record about a model and its declared context, constraints, or evidence posture. It does not itself establish model quality or approval. |
| **registry record** | A recorded entry identifying an artifact, model-related item, or state within an applicable registry surface. It is not deployment approval. |
| **trace** | A recorded linkage between defined inputs, artifacts, states, or outputs. Trace supports review; trace is not proof. |
| **validation** | A bounded evaluation against declared criteria. A validation result is not universal truth, production readiness, or authorization. |
| **review** | A bounded evaluation by the applicable reviewer or review process before a stated conclusion or transition is accepted. Review is not approval beyond its stated scope. |

## Measurement Boundary

For CL-EL/PASDA-related interpretation, the allowed evidence path is:

```text
fixture truth
-> branch output
-> output field map
-> PASDA signal derivation rules
-> atomic PASDA signal records
-> review / adjudication where required
-> PASDA metric formulas
-> PASDA metric records
-> bounded reporting
```

Metrics must not be inferred directly from branch text, evidence surface counts, assertion counts, legacy scores, self-assessment records, or operator judgment.
