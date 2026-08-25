**🌐 Language:** [Português →](./robustez-operacional.md) | **English**

---

# Operational robustness — July 2026

> A sanitized retrospective. Where no public link exists, the item is declared as a **decision** or **retrospective account**, not as a verifiable fact.

## Context

In July 2026, several systems that had been running fine start failing in different ways. A cron job freezes overnight. An authentication expires without warning. A command too long for the operating system has to be rewritten. Nothing is dramatic on its own; together it is more than enough to be exhausting.

## Decision

The whole month becomes a cleanup of what already exists. The rule: nothing new in functionality before what is already running is stabilized.

The choice is deliberate. Adding on top of something that falls is not building — it is accumulating debt.

## Change

Out of July, three new habits:

- Health check per shift, with an explicit list of what to verify.
- A cron health check that alerts when a scheduled job does not run within its expected window.
- An "Always Check" document that is updated every time something new goes into production.

## Public evidence

- **Decision recorded retrospectively:** the July 2026 retrospective documented the set of fixes and the shared perception that maturity is not registration, with no public link attached to this entry.
- **Retrospective account:** the operational rule "nothing new before stabilization" was adopted in the same month, with no public link of origin attached to this entry.

## Lesson

To mature is to make what already exists stop breaking. Adding features is easy; defending what is already standing is the real work.
