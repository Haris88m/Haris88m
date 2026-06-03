# Haris Mekic

**Independent builder & researcher of production agentic systems — solo, with AI as co-engineer.**

I design and ship local-first, bring-your-own-model agent platforms, then audit them honestly from the outside. One person, working alongside frontier models — not a funded team. I publish outcomes you can verify and withhold the build-method that makes them defensible.

---

## What I work on

I build **gate-first agentic operating-system shells**: a workforce of model-backed agents that a human keeps on a dial, where every irreversible action passes a human-in-the-loop gate before it runs. The intelligence is brought by the operator (bring-your-own-model); the platform supplies the controllable surface — chat, an agent grid, an approval queue, per-agent autonomy levels, file-based memory, append-only audits, and a fail-closed quality guard.

The thesis I keep testing in public: in a category where the agent harness and the open `SKILL.md` capability format are now **commodities**, defensibility lives in the layers most tools lack by default — a deep human-in-the-loop gate layer, sealed/audited output boundaries, an inspectable file-based memory, a fail-closed retention guard, and a disciplined build-and-verify development loop.

---

## Current research

### [`agentic-os-audit`](https://github.com/Haris88m/agentic-os-audit) — an independent third-party technical audit

A full outside-auditor review of a production agentic platform, written to auditor-integrity standard: **every non-trivial claim labelled VERIFIED / PARTIAL / UNVERIFIED**, no superlatives, asymmetry weighted honestly (one person + AI vs funded teams). It inventories capabilities against an already-published open repo, maps what was consumed from open source and what was deliberately not, grounds the comparison in the public research literature, and works the cost/scalability math out loud with stated assumptions. Where the public code does not back a claim, it says so plainly.

### [`servari-open`](https://github.com/Haris88m/servari-open) — the open framework

An **Apache-2.0**, dependency-free shell: a React front end over a pure standard-library Python server on `127.0.0.1` (same-origin, no CORS), bring-your-own-model. A fresh clone renders every panel from seed data — runnable by a stranger. The published surface includes the BYOM router, the autonomy-dial gate layer (high-risk actions queue for human approval **even at maximum autonomy**), the allow-listed action runner (not a raw shell), file-based memory, an append-only audit + token meter, and a fail-closed local server. It publishes the verifiable shell and interfaces; the orchestration intelligence stays private — a deliberate, asymmetric line.

---

## How I work: I consume, I do not harness

Other tools **ship a harness**. My approach is the opposite: I **consume**.

I consume patterns one-way from permissively-licensed open source — re-implement the *idea* inside my own owned stack (standard-library Python, not the vendors' code), keep a segregated reference copy for provenance, and run a real test before anything joins the system. Vendor source sits in clearly-marked reference directories that the running code never imports. Inbound consumption is real and frequent; outbound is constrained to a verifiable shell plus interfaces — never the method.

Consuming the commodity part of the stack (harness patterns, edit-safety, context-discipline, trajectory-eval) is the rational move, not an admission. The defensibility is spent on the part that is composed and gated.

---

## Built with

`Claude Opus 4.8` (lead engineering & authoring) · `Claude Sonnet`, `OpenAI GPT`, `Google Gemini` (cross-checks) · Python (stdlib) · React + TypeScript · OpenAI-compatible model routing

I work with these models as collaborators and adversarial reviewers — the most credible review datapoint I keep is a claim being **challenged by a less-correlated model and conceded/corrected** rather than defended.

---

## Posture

- **Outcomes shared, build-method withheld.** I publish what can be verified and reproduced; I keep the proprietary composition private. That is a competitive-defensibility choice, stated openly.
- **Honesty is the deliverable.** Cost figures I cite are **API-equivalent cost-to-serve, not cash** (the work runs largely on a flat-rate subscription). Multipliers carry their scope. Counts are an inventory, not a validation. Unfinished tracks are labelled unfinished.
- **Gates over trust.** Reversible work moves fast; the actions that bite — deploy, send, spend, publish, merge, secrets — always wait for a human. The gate is mechanical, not a prompt instruction.

---

> Built by one person with AI assistance. The maturity of larger, funded competitors is a roadmap to learn from — not a deficit to spin.
