**🌐 Language:** [Português →](./seguranca-gateway.md) | **English**

---

# Gateway security cycle — June 2026

> A sanitized retrospective. Where no public link exists, the item is declared as a **decision** or **retrospective account**, not as a verifiable fact.

## Context

In June 2026, a poorly-reviewed change to a configuration file takes the environment down for a few minutes. The environment's main function stops being served until the configuration is reverted.

The change was pushed without checking the schema before applying, without a smoke test beforehand, and published straight through.

## Decision

After the incident, three rules are put in place:

- Every change to configuration must go through a validation path that includes consulting the official schema.
- Every change must have a snapshot taken before applying, and a rehearsed rollback.
- Every change must be approved by a second person before going live.

The failure is recorded at [`falhas-e-licoes/`](../../../falhas-e-licoes/), and Felipe agrees to make the episode public.

## Change

From here on, every configuration change now has:

- A versioned baseline taken before the change.
- Verification against the official schema via tooling.
- A harmless smoke test (no delivery, no scope expansion) before applying.
- Explicit approval for REVERSIBLE changes, and a separate gate for DESTRUCTIVE / EXTERNAL changes.

## Public evidence

- **Decision recorded retrospectively:** the weekly retrospective of June 2026 documented the incident and approved the set of rules, with no public link attached to this entry.
- **Retrospective account:** the milestone "formal start of the Wolfpack security cycle" is declared in this publication, with no public link of origin attached to this entry.

## Lesson

The root cause was not in the configuration itself; it was in the absence of review before publishing. Treating "I didn't see anything wrong" as proof of correctness is the error that gave this milestone its date. *Esse quam videri* begins to surface as a mental test after this milestone.
