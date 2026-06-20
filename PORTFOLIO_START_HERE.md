# Elyria Systems — Portfolio Start Here

## Pre-Execution Governance for Systems That Can Bind Consequence

This portfolio is not a catalog of disconnected repositories.

It is a public proof estate organized around one operational question:

> **What must be true before a system is allowed to make consequence real?**

The work operates before execution binds: before an AI agent calls a tool, before an automation changes a record, before authority is relied upon, before a payment or access decision takes effect, and before an approval continues under changed conditions.

---

## 1. Flagship Runnable Proof Surface

### [Elyria Admission Runtime](https://github.com/Kamanaka5502/elyria-admission-runtime)

**Role:** The flagship runnable proof surface.

Elyria Admission Runtime evaluates a proposed movement before consequence binds. Its public reviewer path includes:

```text
movement intake
→ authority check
→ standing check
→ evidence gate
→ custody / hash basis
→ deterministic verdict
→ signed receipt
→ receipt storage
→ replay verification
→ exposure graph
→ proof-packet export
```

Its four public decision outcomes are:

| Verdict | Meaning |
|---|---|
| `ADMIT` | movement may bind consequence |
| `HOLD` | proof or custody requires repair |
| `REFUSE` | movement is blocked by an invalid or refusal-bearing condition |
| `NO_PROVABLE_ADMISSION` | movement attempts to bind without durable proof |

**Reviewer route:** Start with the runtime. Run the local verifier. Submit an admitted path and a black-path attempt. Replay the resulting receipt. Then use the supporting repositories below to inspect the underlying control dimensions.

---

## 2. Category and Governing Thesis

### Pre-Execution Governance

Pre-execution governance is the discipline of determining whether a proposed action may bind operational consequence **before** the protected effect occurs.

It is not post-incident audit, policy-only compliance, or workflow decoration.

A pre-execution governance system must be able to resolve:

```text
What movement is proposed?
What consequence could bind?
What authority exists now—not merely at request time?
What evidence is required and still valid?
What changed since prior approval?
What must be admitted, held, refused, or revalidated?
What receipt proves the decision basis?
What replay can verify later?
```

The governing standard is direct:

> **If inadmissible movement can still bind consequence, the boundary has failed.**

---

## 3. Supporting Repository System

The supporting repositories are not equal-weight products. They are distinct proof and control surfaces beneath the flagship runtime.

### Authority at the consequence boundary

| Repository | What it proves |
|---|---|
| [bind-time-authority-proof](https://github.com/Kamanaka5502/bind-time-authority-proof) | Authority must be evaluated at the exact moment consequence would bind; stale or mismatched standing must refuse. |
| [authority-revocation-witness](https://github.com/Kamanaka5502/authority-revocation-witness) | Previously valid authority does not survive revocation without fresh revalidation. |
| [elyria-agent-action-boundary](https://github.com/Kamanaka5502/elyria-agent-action-boundary) | AI/agent movement must encounter an explicit action boundary before external effect. |

### Evidence, custody, and proof continuity

| Repository | What it contributes |
|---|---|
| [elyria-boundary-proof-register](https://github.com/Kamanaka5502/elyria-boundary-proof-register) | Public proof-register surface for boundary, receipt, and verification posture. |
| [elyria-ai-audit-evidence-pack](https://github.com/Kamanaka5502/elyria-ai-audit-evidence-pack) | Evidence-oriented AI review material and auditability surface. |
| [dimensional-drift-witness](https://github.com/Kamanaka5502/dimensional-drift-witness) | Witness surface for detecting drift that can invalidate prior operating assumptions. |

### Change, revalidation, and continued standing

| Repository | What it proves |
|---|---|
| [elyria-ai-revalidation-engine](https://github.com/Kamanaka5502/elyria-ai-revalidation-engine) | Prior AI approval is not permanent; changes in model, prompt, data, tools, policy, access, or environment can require `REVALIDATE` or `REFUSE`. |
| [authority-revocation-witness](https://github.com/Kamanaka5502/authority-revocation-witness) | Revocation interrupts continuation even when the action remains technically executable. |
| [board-ai-dependency-boundary](https://github.com/Kamanaka5502/board-ai-dependency-boundary) | Dependency review surface for AI becoming structural, load-bearing, or consequence-bearing before proof is sufficient. |

### Refusal and protected-effect control

| Repository | What it contributes |
|---|---|
| [elyria-pre-effect-enforcement-harness](https://github.com/Kamanaka5502/elyria-pre-effect-enforcement-harness) | Pre-effect enforcement posture: decide before protected effect occurs. |
| [elyria-action-firewall](https://github.com/Kamanaka5502/elyria-action-firewall) | Action-control boundary for movement that should not execute without admitted standing. |
| [elyria-clinical-ai-boundary](https://github.com/Kamanaka5502/elyria-clinical-ai-boundary) | Domain-specific boundary work for higher-consequence clinical AI movement. |

### Safe change and execution continuity

| Repository | What it contributes |
|---|---|
| [veritas-safechange](https://github.com/Kamanaka5502/veritas-safechange) | Change-governance surface for controlled modification rather than unsafe continuation. |
| [elyria-runtime-law](https://github.com/Kamanaka5502/elyria-runtime-law) | Runtime-law framing for conditions governing admissible state movement. |
| [elyria-consequence-os-public](https://github.com/Kamanaka5502/elyria-consequence-os-public) | Public-facing consequence-governance system framing. |

---

## How to Review This Portfolio

Do not review all repositories as if they are the same artifact class.

```text
1. Start with Elyria Admission Runtime.
2. Confirm the runnable admission → receipt → replay corridor.
3. Inspect bind-time authority and revocation as the authority basis.
4. Inspect AI Revalidation Engine as the changed-condition control.
5. Inspect pre-effect enforcement and safe-change surfaces for refusal / continuity logic.
6. Treat the remaining repositories as bounded domain corridors, witnesses, experiments, or public-safe proof layers—not as duplicate flagships.
```

---

## Public / Protected Boundary

The public repositories expose reviewer paths, bounded demonstrators, decision models, evidence posture, testable behavior, and buyer-safe proof surfaces.

They do not grant unrestricted reuse rights or disclose all production-grade implementation machinery. Customer-specific runtime architecture, protected validators, signing/key infrastructure, private proof corridors, and controlled deployment designs remain separate from public review.

> **The portfolio is designed to make the category legible without flattening the machinery into a generic software catalog.**

---

## Core Line

> **Elyria Admission Runtime is the flagship runnable proof surface.**
>
> **Pre-Execution Governance is the category: the conditions under which proposed movement may bind consequence.**
>
> **The supporting repositories provide the authority, evidence, revalidation, refusal, replay, and safe-change control surfaces that make the category inspectable.**
