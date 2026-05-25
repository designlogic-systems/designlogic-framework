# Build Brief

```text
Status: Draft framework documentation
Review Status: review_required
Delivery Ready: false
Production Ready: false
Market Validated: false
```

## Definition

A **build brief** is a bounded artifact prepared for a builder, developer, agent, workflow, or app-building system. In the DesignLogic Framework, it communicates stated requirements, limits, questions, and review or authority conditions for a potential build activity without establishing that activity has been authorized or completed.

## Build Brief Content

| Content area | Purpose |
| --- | --- |
| Purpose | Identifies the bounded build-facing outcome being described. |
| Input source | References applicable SDS, App SDS, DefinitionVersion, handoff artifact, source context, or admitted input material. |
| Structured requirements | States requirements, expected outputs, constraints, and relevant artifact relationships. |
| Exclusions | States work, surfaces, behavior, or claims outside the brief. |
| Assumptions | Identifies assumptions affecting interpretation or requiring confirmation. |
| Open questions | Records unresolved matters that may require review or deferral before build activity. |
| Acceptance or review criteria | States criteria for bounded review of a resulting artifact or proposed output. |
| Handoff boundary | Identifies receiving context, transferred material, and limitations on downstream interpretation. |
| Build authority boundary | States separately required permission for tool access, generation, execution, release, or deployment. |

## Relationship To Artifact Transfer

A build brief may be included in a handoff artifact or an executable artifact package for a declared downstream process. Inclusion communicates bounded requirements; it does not remove review or authority requirements. Any resulting implementation or output requires its own evidence and validation posture.

## Required Boundaries

```text
builder-ready does not mean build-authorized.
build brief is not completed implementation.
build brief is not market validation.
build brief is not product approval.
build brief does not authorize tool access, code generation, deployment, or release unless separately authorized.
```

A build brief does not establish runtime governance enforcement, correctness, production readiness, certification, customer acceptance, or authority to execute.
