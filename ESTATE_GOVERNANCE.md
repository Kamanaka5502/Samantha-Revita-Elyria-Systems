# Elyria Repository Estate Governance

## Governing position

The Elyria repository estate is a governed evidence field. Repository creation does not grant canonical standing. Public visibility does not grant proof standing. A passing check does not grant production standing.

Only a named record in [`public-proof-index.json`](public-proof-index.json) may represent an admitted canonical public proof surface.

## Independent state dimensions

The following dimensions must never be collapsed into one status label:

| Dimension | Examples |
|---|---|
| Visibility | public, private, restricted |
| Lifecycle | discovered, classified, admitted, canonical, superseded, retired, quarantined |
| Evidence maturity | hypothesis, implemented, internally tested, adversarially tested, externally integrated, independently reproduced |
| Deployment posture | local demonstrator, software-in-the-loop, integration candidate, deployment candidate, admitted deployment |
| Authority posture | navigation, specification, proof surface, protected reference, production authority |
| Rights posture | public inspection, proprietary, restricted, licensed, customer-specific |

A repository can be public and non-canonical. It can be internally tested and not publicly verifiable. It can be a strong implementation and still lack deployment admission.

## Lifecycle states

```text
DISCOVERED
→ CLASSIFIED
→ ADMITTED
→ CANONICAL
→ SUPERSEDED | RETIRED

Any state
→ QUARANTINED
```

### `DISCOVERED`

The repository exists. No architectural, proof, or claim authority is inferred.

### `CLASSIFIED`

Its role, visibility, ownership, claim boundary, and relation to other surfaces are named.

### `ADMITTED`

An exact revision, evidence path, tested corridor, maturity, boundary, and attribution record have passed review.

### `CANONICAL`

The surface is the current authoritative reference for its declared role. Canonical standing is role-specific and does not transfer to adjacent repositories.

### `SUPERSEDED`

A named successor has taken the role. Historical evidence remains replayable; new claims route to the successor.

### `RETIRED`

The surface is preserved for lineage but must not be cited as current.

### `QUARANTINED`

Visibility, evidence, ownership, security, or claim coherence is unresolved. No external claim may bind to the repository.

## Canonical admission invariant

```text
IDENTIFIED
∧ ROLE_DECLARED
∧ REVISION_PINNED
∧ ACCESS_DECLARED
∧ EVIDENCE_NAMED
∧ REPLAY_PATH_PRESENT
∧ CORRIDOR_BOUNDED
∧ MATURITY_DECLARED
∧ CLAIM_BOUNDARY_DECLARED
∧ ATTRIBUTION_RESOLVED
→ ELIGIBLE_FOR_CANONICAL_ADMISSION
```

Eligibility does not automatically grant admission. The registry record is the binding act.

## Public proof law

A surface is admissible as public proof only when the intended public reviewer can access the exact evidence supporting the claim.

```text
PRIVATE IMPLEMENTATION + PRIVATE WORKFLOW
→ PROTECTED REFERENCE
→ NOT PUBLIC CODE PROOF
```

A public summary may accurately describe private results if it declares the access limitation. It may not convert inaccessible evidence into independent public verification.

## Branch and release law

```text
open pull request != merged release
mergeable != merged
validation branch != main
green candidate checks != production admission
```

Every citation must identify whether the revision is a `main` commit, tag, branch head, or pull-request candidate.

## Version law

Version numbers are local to a repository and its release line.

```text
repo-A v0.8.2 cannot be ranked against repo-B v0.6.0 by number alone
```

Cross-repository precedence is controlled by declared role, canonical status, supersession, maturity, and evidence—not semantic-version magnitude.

## Supersession law

When one repository replaces another, the registry must name:

```text
predecessor
successor
role transferred
effective revision
reason
historical evidence location
claims that remain valid
claims that no longer bind
```

Until that record exists, both repositories remain separately bounded and neither silently inherits the other's proof.

## Current estate rule

The account contains 118 repositories in the 2026-08-05 snapshot. Only records explicitly admitted by the proof index are canonical public proof surfaces. All other repositories remain supporting, protected, experimental, historical, or unclassified until individually classified.

No archive operation, visibility change, deletion, or cross-repository ownership claim should occur without a separate review of lineage, IP, evidence custody, and external dependencies.

## Change control

Changes to canonical status require:

1. an exact proposed registry diff;
2. evidence for the new revision;
3. an updated claim boundary;
4. an explicit public/protected posture;
5. preserved predecessor lineage;
6. review before merge.

This makes the repository estate itself subject to the same rule as the runtime:

> **No motion binds without current standing, named authority, and replayable evidence.**

