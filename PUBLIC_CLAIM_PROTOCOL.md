# Elyria Public Claim Protocol

## Purpose

This protocol prevents public language from outrunning the evidence. It also prevents a generic GitHub link, a private repository, a repository title, or green automation from being treated as substantiation beyond its exact tested corridor.

A public claim is admissible only when a reader can identify and access:

1. the exact behavior claimed;
2. the exact repository and revision containing it;
3. the executable test, workflow, command, or preserved artifact supporting it;
4. the bounded environment in which it was exercised;
5. the maturity level of the result;
6. the conditions that were not tested;
7. the correct architect and collaborator attribution;
8. whether the cited state is `main`, a tag, a branch, or a pull-request candidate.

## Required citation block

```text
CLAIM
[One precise sentence describing the behavior.]

EVIDENCE SURFACE
Repository: https://github.com/<owner>/<repository>
Access: PUBLIC | PRIVATE_AUTHORIZED | RESTRICTED
Revision: <exact commit or tag>
Revision state: MAIN | TAG | BRANCH | PULL_REQUEST_CANDIDATE
Workflow / command / artifact: <exact reproducible path>
Tested corridor: <bounded environment and behavior>

CLAIM MATURITY
HYPOTHESIS | IMPLEMENTED | INTERNALLY_TESTED | ADVERSARIALLY_TESTED |
EXTERNALLY_INTEGRATED | INDEPENDENTLY_REPRODUCED

PUBLIC VERIFICATION POSTURE
PUBLICLY_REPRODUCIBLE | PUBLICLY_INSPECTABLE | SUMMARY_ONLY | PROTECTED

BOUNDARY
[What the evidence does not establish.]

ATTRIBUTION
Architect: <name>
Collaborator / lineage: <name and exact scope, when applicable>
```

## Access law

Private evidence may support an authorized private review. It cannot silently become independently verifiable public proof.

```text
exact private revision
+ exact private workflow
+ explicit access limitation
→ protected reference claim

protected reference claim
!= publicly reproducible claim
```

When the public cannot inspect the cited implementation or workflow, the public statement must say `SUMMARY_ONLY` or `PROTECTED`.

## Evidence rules

### A repository title is not proof

A title such as “physics engine,” “certified execution,” “consciousness boundary,” or “governance OS” identifies a project surface. It does not establish physical validity, certification, consciousness, production readiness, regulatory approval, or universal scope.

### Green automation is bounded evidence

A successful run establishes that the declared checks passed at the declared revision in the declared environment. It does not establish physical-system validity, scientific consensus, regulatory certification, production reliability, managed key custody, independent reproduction, or universal applicability.

### A pull request is a candidate

```text
OPEN + MERGEABLE + GREEN
→ VALIDATED CANDIDATE
→ NOT MERGED MAIN RELEASE
```

The target branch must be named. A merge into a validation branch does not imply promotion to `main`.

### Versions do not compare across repositories

Semantic versions are local to their repository release line. A numerically larger version in one repository does not outrank another repository's version. Canonical role, maturity, and evidence govern precedence.

### The generic account is navigation, not substantiation

Do not use `https://github.com/Kamanaka5502` as the only evidence link. Use the exact admitted record in [`public-proof-index.json`](public-proof-index.json).

### Category language remains qualified

Admissible:

> Elyria Systems implements pre-effect execution-governance patterns in bounded software corridors identified in its public proof index.

Not established without additional proof:

> Elyria has replaced all existing governance.

> Elyria is a scientifically recognized new substrate.

> Elyria guarantees physical, regulatory, or production safety.

## Claim maturity definitions

| Level | Meaning |
|---|---|
| `HYPOTHESIS` | Architectural or mathematical proposition not yet implemented. |
| `IMPLEMENTED` | Code or a formal artifact exists. |
| `INTERNALLY_TESTED` | Declared tests pass under project control. |
| `ADVERSARIALLY_TESTED` | Defined negative, mutation, replay, race, or refusal cases pass. |
| `EXTERNALLY_INTEGRATED` | A separately operated system integrated the bounded behavior. |
| `INDEPENDENTLY_REPRODUCED` | An independent party reproduced the result from disclosed evidence. |

Maturity is revision-specific and claim-specific. It is not inherited from another repository, collaborator, paper, workflow, or version number.

## Protected flagship reference

```text
Repository: Kamanaka5502/elyria-field-admission-runtime
Access: PRIVATE_AUTHORIZED
Pull request: #7
Validated head: 8434e2ab4af570fc62c567a2cb0e05f4b842dee0
Revision state: PULL_REQUEST_CANDIDATE
Target branch: validation/adversarial-campaign-v1
Main posture: v0.5.0
Candidate posture: v0.6.0
Internal maturity: ADVERSARIALLY_TESTED in declared software workflows
Public verification posture: PROTECTED
```

This is the strongest protected implementation candidate currently identified. It is not admitted as public code proof while its repository and workflow evidence require authorized access.

## Attribution rules

- Samantha Beatrice Revita-Wagner is Founder and Lead Architect of Elyria Systems.
- Terry Snyder is Founder and Lead Architect of Veritas Aegis.
- Terry Snyder is attributed as collaborator only on repositories, documents, commits, or proof surfaces where collaboration or shared lineage is explicitly declared.
- Shared lineage does not imply shared authorship, ownership, implementation, or validation across the entire Elyria estate.
- Every public citation preserves repository-specific attribution.

## Governing rules

> **Where the evidence stops, the claim stops.**

> **Where access stops, public verification stops.**

