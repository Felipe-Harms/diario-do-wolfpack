**🌐 Language:** [Português →](./diario-publico.md) | **English**

---

# Publishing this journal — August 2026

> A sanitized retrospective. Where no public link exists, the item is declared as a **decision** or **retrospective account**, not as a verifiable fact.

## Context

After months of operation, in August 2026, Felipe proposes that the system have a public narrative layer. Not documentation, not code, not a portfolio. A journal.

The motivation is twofold: what is learned across months of iteration may be useful to other people building similar systems — or deciding whether the build is worth it. And it works as a test: what fits in public is what has passed the yardstick of *to be, rather than to seem*.

## Decision

The journal comes into being as a separate public repository, under MIT license, authored by Felipe, with sanitized and verifiable content. Content must pass three tests before publication:

- Is it already public, or has Felipe already made it public elsewhere?
- Does it expose customers, secrets, infrastructure, third-party identity, private paths?
- Is the tone consistent with the motto — no mascot, no marketing persona, no claim of lived experience?

Publication happens without automation. Each future entry goes through a branch + PR with mandatory human review before it goes live.

## Change

From here on, three effects:

- The Wolfpack gains an open narrative door. The written content can receive public feedback.
- The yardstick of "what is private" becomes explicit at [`docs/privacidade-red-lines.md`](../../../docs/privacidade-red-lines.md).
- Future entries are recorded as phase 3 of the [`README.md`](../../../README.en.md) — entries via branch + PR, five human reviews before any automation.

## Public evidence

- The `diario-do-wolfpack` repository was published on GitHub, on the `main` branch, under MIT license, in August 2026.
- The initial check was done via anonymous public fetch. The URL, the `LICENSE` file, the `README.md` file, and the five initial journal entries were all accessible without authentication.

## Lesson

Putting what you think in public is a way of holding yourself to consistency. The published content becomes auditable by anyone — and that is part of the test, not a side effect.
