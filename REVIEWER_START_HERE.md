# Reviewer Start Here

## Purpose

This document prevents a reviewer from having to infer Elyria Systems from a 118-repository account surface.

Choose the route that matches the decision you are making. Do not treat navigation, branding, repository count, or private evidence as a substitute for an inspectable proof path.

## Five-minute orientation

1. Read the governing position in [`README.md`](README.md).
2. Inspect the admitted records in [`public-proof-index.json`](public-proof-index.json).
3. Select one bounded proof surface.
4. Use the pinned revision and named verification route.
5. Compare the observed result with the stated claim boundary.

The review is complete only when the claimed behavior, revision, evidence path, tested corridor, maturity, and non-claim boundary resolve together.

## Technical reviewer route

### Effect refusal

Use [Elyria Pre-Effect Enforcement Harness](https://github.com/Kamanaka5502/elyria-pre-effect-enforcement-harness).

```bash
python -m app.prove --case all
```

Review question:

```text
Does every non-EXECUTE outcome leave protected state unchanged?
```

### Artifact boundary and replay

Use [C.A.S.E. Elyria Systems Boundary Layer](https://github.com/Kamanaka5502/C.A.S.E.-Elyria-Systems-Boundary-Layer).

```bash
npm install
npm run verify
```

Expected marker:

```text
RESULT: C.A.S.E. BOUNDARY PASS
```

### Financial-motion corridor

Use [Elyria Financial Motion Governance](https://github.com/Kamanaka5502/elyria-financial-motion-governance).

```bash
python run_proofs.py
```

Review question:

```text
Does inadmissible synthetic financial intent remain non-binding before simulated value motion?
```

### Bind-time authority specification

Use [Bind-Time Authority Proof](https://github.com/Kamanaka5502/bind-time-authority-proof).

Review the stated invariants and disclosure boundary. This surface is admitted as an implemented bounded specification, not as production cryptography or a production authority fabric.

## Buyer or partner route

1. Start with the [Execution Governance Portfolio](https://github.com/Kamanaka5502/elyria-execution-governance-portfolio).
2. Identify the exact consequence corridor under review.
3. Confirm whether the relevant surface is public, protected, or not yet admitted.
4. Require a pinned revision and reproducible evidence path before using maturity language.
5. Treat customer deployment, integration, certification, and licensing as separate admission events.

Protected materials require an authorized review corridor. Private repository access does not itself grant implementation, reuse, sublicensing, or production rights.

## Hiring reviewer route

Evaluate the work through demonstrated systems distinctions rather than repository count:

```text
proposal vs standing
standing vs authority
authority issuance vs authority consumption
consumption vs observed effect
observed effect vs committed consequence
binding vs continuing standing
decision output vs replayable evidence
```

The public estate demonstrates architecture, deterministic boundary design, failure-closed behavior, evidence contracts, replay, and bounded proof construction. It does not ask a reviewer to accept physical, regulatory, or production claims without corresponding evidence.

## Protected flagship route

`elyria-field-admission-runtime` v0.6.0 / PR #7 is a protected reference implementation candidate.

```text
Validated head: 8434e2ab4af570fc62c567a2cb0e05f4b842dee0
Access: private / authorized review
Target: validation/adversarial-campaign-v1
Main posture: v0.5.0
Public code-proof standing: not admitted
```

An authorized reviewer may inspect its declared workflow evidence. A public reviewer may cite only the accessible evidence summary and must state that the implementation and workflow artifacts are private.

## Refusal conditions

Stop and hold the claim when any of the following occurs:

- the repository cannot be accessed by the intended reviewer;
- the revision is not pinned;
- a pull-request candidate is presented as a `main` release;
- the verification command or artifact is absent;
- the tested corridor is undefined;
- maturity is inherited from another repository;
- a local version number is used to imply cross-repository superiority;
- public visibility is mistaken for licensing or production authorization;
- attribution is broader than the identified artifact supports.

## Governing result

```text
ACCESSIBLE
∧ REVISION_PINNED
∧ EVIDENCE_NAMED
∧ CORRIDOR_BOUNDED
∧ MATURITY_DECLARED
∧ NON_CLAIMS_DECLARED
∧ ATTRIBUTION_RESOLVED
→ ADMISSIBLE_PUBLIC_REFERENCE
```

Anything less remains navigation, a candidate, or protected evidence—not public proof.

