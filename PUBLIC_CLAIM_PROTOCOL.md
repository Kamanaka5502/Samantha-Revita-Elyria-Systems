# Elyria Public Claim Protocol

## Purpose

This protocol prevents public language from outrunning the evidence and prevents a generic GitHub account link from being treated as technical substantiation.

A public claim is admissible only when a reader can identify:

1. the exact behavior claimed;
2. the exact repository and revision containing it;
3. the executable test or workflow that exercised it;
4. the bounded environment in which it was exercised;
5. the maturity level of the result;
6. the conditions that were not tested;
7. the correct architect and collaborator attribution.

## Required citation block

Use this block in LinkedIn posts, articles, proposals, decks, and technical discussions:

```text
CLAIM
[One precise sentence describing the behavior.]

EVIDENCE SURFACE
Repository: https://github.com/<owner>/<repository>
Revision: <commit, tag, branch, or pull request>
Workflow / artifact: <exact run or artifact>
Tested corridor: <bounded environment and behavior>

CLAIM MATURITY
HYPOTHESIS | IMPLEMENTED | INTERNALLY_TESTED | ADVERSARIALLY_TESTED |
EXTERNALLY_INTEGRATED | INDEPENDENTLY_REPRODUCED

BOUNDARY
[What the evidence does not establish.]

ATTRIBUTION
Architect: <name>
Collaborator / lineage: <name and exact scope, when applicable>
```

## Evidence rules

### A repository title is not proof

A title such as “physics engine,” “certified execution,” “consciousness boundary,” or “governance OS” identifies a project surface. It does not establish physical validity, certification, consciousness, production readiness, regulatory approval, or universal scope.

### Green CI is bounded evidence

A successful workflow establishes that the declared checks passed in the declared environment at the declared revision. It does not establish:

- physical-system validity;
- scientific consensus;
- regulatory certification;
- production reliability;
- managed key custody;
- independent reproduction;
- universal applicability.

### The generic account is navigation, not substantiation

Do not use `https://github.com/Kamanaka5502` as the only evidence link. Link the exact repository and, when the claim depends on a particular revision, the exact commit, pull request, workflow run, or artifact.

### Category language must remain qualified

Permitted:

> Elyria Systems implements a pre-effect execution-governance architecture in bounded software corridors.

Not evidence-supported without additional proof:

> Elyria has replaced all existing governance.

> Elyria is a scientifically recognized new substrate.

> Elyria guarantees physical or regulatory safety.

> All old-stack problems are now moot.

## Claim maturity definitions

| Level | Meaning |
|---|---|
| **HYPOTHESIS** | Architectural or mathematical proposition not yet implemented. |
| **IMPLEMENTED** | Code or formal artifact exists. |
| **INTERNALLY_TESTED** | Declared tests pass under the project’s own control. |
| **ADVERSARIALLY_TESTED** | Defined negative, mutation, replay, race, or refusal cases pass. |
| **EXTERNALLY_INTEGRATED** | A separately operated system has integrated the bounded behavior. |
| **INDEPENDENTLY_REPRODUCED** | An independent party reproduced the result from disclosed evidence. |

The levels are cumulative only when the evidence supports each transition.

## Attribution rules

- Samantha Revita-Wagner is Founder and Lead Architect of Elyria Systems.
- Terry Snyder is Founder and Lead Architect of Veritas Aegis.
- Terry Snyder is attributed as collaborator only on repositories, documents, commits, or surfaces where collaboration or shared lineage is explicitly declared.
- Shared lineage does not imply shared authorship or ownership of the entire Elyria repository estate.
- Every public citation must preserve repository-specific attribution.

## Current canonical references

### Elyria Field Admission Runtime v0.6.0

```text
Repository: https://github.com/Kamanaka5502/elyria-field-admission-runtime
Pull request: https://github.com/Kamanaka5502/elyria-field-admission-runtime/pull/7
Current validated head: 8434e2ab4af570fc62c567a2cb0e05f4b842dee0
Maturity: INTERNALLY_TESTED with declared adversarial regressions
Boundary: software-in-the-loop; no physical, certified, or production admission claim
Architect: Samantha Revita-Wagner
```

### Execution Governance Portfolio

```text
Repository: https://github.com/Kamanaka5502/elyria-execution-governance-portfolio
Maturity: INTERNALLY_TESTED for the exact indexed proof corridors
Boundary: no universal, regulatory, or physical-system claim
Architect: Samantha Revita-Wagner
```

### Bind-Time Authority Proof

```text
Repository: https://github.com/Kamanaka5502/bind-time-authority-proof
Maturity: repository-specific evidence only
Boundary: evaluate the repository’s own tests and claim register before citing behavior
Architect: Samantha Revita-Wagner
```

## Governing rule

> **Where the evidence stops, the claim stops.**
