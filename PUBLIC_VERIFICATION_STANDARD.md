# Elyria Public Verification Standard

This standard is the minimum contract for public Elyria proof surfaces.

## 1. Governed object

Every corridor must identify the exact movement or transition being governed and the protected consequence that could bind.

## 2. Current standing

Standing is evaluated at the boundary where consequence would bind. Prior approval, prior standing, authentication, or software availability must not substitute for current standing.

## 3. Admissibility

The decision function must explicitly resolve the movement into a bounded outcome class. `ALLOW`/`EXECUTE` is never inferred from missing information.

## 4. Evidence

Evidence must have an explicit state. Presence alone is insufficient. Unsupported, unverifiable, revoked, stale, contradictory, or malformed evidence must not produce an admitted outcome.

## 5. Authority

Decision, authority, signing, execution, and verification must be separable where the corridor requires it. A decision record is not automatically execution authority.

## 6. Effect control

Non-admitted outcomes must not create the protected effect. The public proof should demonstrate no-effect behavior for negative cases whenever the corridor claims pre-effect enforcement.

## 7. Replay

A receipt must bind enough governing basis to reconstruct the original decision. Changed governing state must not silently inherit an earlier admission.

## 8. Mutation / tamper

The proof surface should include at least one negative test showing that mutation, tampering, or changed governing input is detected and either changes the proof basis or fails closed.

## 9. Time

Where standing can expire or decay, the admission contract must bind an epoch/expiry or an equivalent freshness condition and revalidate before effect.

## 10. Claim discipline

Public claims must be limited to what the repository's executable and inspectable evidence establishes. Local proof is not automatically production certification, universal safety, third-party validation, or regulatory approval.

## 11. Fresh-clone standard

The authoritative reviewer path must be runnable from a fresh checkout with stated dependencies and without unpublished/private state.

## 12. Domain boundary

A vertical proof corridor demonstrates application of the common boundary architecture to one consequence field. It does not establish correctness for unrelated domains.
