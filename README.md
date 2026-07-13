# UniSaaS.UniCORE.Apache

**SCAFFOLD-ANCHOR repository — initial scaffold 2026-06-04.**

Full scaffolding, upstream-fork integration, and source-code work all pending a fresh dedicated kickoff arc. This initial commit exists to lock the repository's identity, licence position, and place in the UniCORE Sanity Check fleet so the work cannot be forgotten.

Author: **Bryan Fred, Unitek Systems Limited, Bedford, United Kingdom.**
First commit: **2026-06-04 17:45 UTC.**

---

## What this repository is

`bryanunitek/UniSaaS.UniCORE.Apache` is the **Apache** family member: SaaS-deployment-shape public gift surface. Documentation today; source code at certification.

**Family purpose:** Open-source HTTP server — primary web-serving substrate for UniCORE.GVB.

**Deployment shape:** This is the **SaaS-shape** member of the family. It tracks the same upstream codebase as [`UniCORE.Apache`](https://git.unitek-systems.com/UniCORE/UniCORE.Apache) (mirror: [GitHub](https://github.com/bryanunitek/UniCORE.Apache)) (on-prem shape) but carries SaaS-specific configuration, multi-tenant isolation patterns, and cloud-native deployment artefacts.

---

## Upstream

- **Upstream project:** https://github.com/apache/httpd
- **Upstream licence:** Apache-2.0
- **Our relationship:** Fork-and-extend. Upstream codebase is consumed verbatim under its original licence; our additions sit on top under CC BY 4.0.

The merge discipline that governs how this repository absorbs upstream changes is documented in [`UPSTREAM-MERGE-DISCIPLINE.md`](https://git.unitek-systems.com/UniCORE/UniSaaS.UniCORE.Apache/src/branch/main/UPSTREAM-MERGE-DISCIPLINE.md) (mirror: [GitHub](https://github.com/bryanunitek/UniSaaS.UniCORE.Apache/blob/main/UPSTREAM-MERGE-DISCIPLINE.md)).

---

## Platforms

Windows · Linux · macOS · iOS · Android

---

## Family — the four-repo pattern

UniCORE.Apache is published as a **four-repo family**:

- `bryanunitek/UniCORE.Apache` — public on-prem-deployment-shape gift surface
- `bryanunitek/UniSaaS.UniCORE.Apache` — public SaaS-deployment-shape gift surface ← **this repo**
- `bryanunitek/UniCORE.Apache-Claw` (private) — on-prem-shape working repository
- `bryanunitek/UniSaaS.UniCORE.Apache-Claw` (private) — SaaS-shape working repository

---

## Status

**SCAFFOLD-ANCHOR** as of 2026-06-04. See [`STATUS.md`](https://git.unitek-systems.com/UniCORE/UniSaaS.UniCORE.Apache/src/branch/main/STATUS.md) (mirror: [GitHub](https://github.com/bryanunitek/UniSaaS.UniCORE.Apache/blob/main/STATUS.md)) for the full status breakdown.

---

## Files in this scaffold commit

- [`README.md`](https://git.unitek-systems.com/UniCORE/UniSaaS.UniCORE.Apache/src/branch/main/README.md) (mirror: [GitHub](https://github.com/bryanunitek/UniSaaS.UniCORE.Apache/blob/main/README.md)) — this file
- [`LICENSE.md`](https://git.unitek-systems.com/UniCORE/UniSaaS.UniCORE.Apache/src/branch/main/LICENSE.md) (mirror: [GitHub](https://github.com/bryanunitek/UniSaaS.UniCORE.Apache/blob/main/LICENSE.md)) — UniCORE additions licence
- [`STATUS.md`](https://git.unitek-systems.com/UniCORE/UniSaaS.UniCORE.Apache/src/branch/main/STATUS.md) (mirror: [GitHub](https://github.com/bryanunitek/UniSaaS.UniCORE.Apache/blob/main/STATUS.md)) — scaffold-anchor status
- [`UPSTREAM-MERGE-DISCIPLINE.md`](https://git.unitek-systems.com/UniCORE/UniSaaS.UniCORE.Apache/src/branch/main/UPSTREAM-MERGE-DISCIPLINE.md) (mirror: [GitHub](https://github.com/bryanunitek/UniSaaS.UniCORE.Apache/blob/main/UPSTREAM-MERGE-DISCIPLINE.md)) — canonical merge discipline
- [`AI-AUTHORSHIP.md`](https://git.unitek-systems.com/UniCORE/UniSaaS.UniCORE.Apache/src/branch/main/AI-AUTHORSHIP.md) (mirror: [GitHub](https://github.com/bryanunitek/UniSaaS.UniCORE.Apache/blob/main/AI-AUTHORSHIP.md)) — AI authorship disclosure

---

## Related repositories — UniCORE programme

**Foundation triad (gift, public, CC BY 4.0):**
- [`UniVERSE`](https://git.unitek-systems.com/UniCORE/UniVERSE) (mirror: [GitHub](https://github.com/bryanunitek/UniVERSE)) — programme
- [`TrueAI`](https://git.unitek-systems.com/UniCORE/TrueAI) (mirror: [GitHub](https://github.com/bryanunitek/TrueAI)) — Foundation (Nine Invariants)
- [`UniCORE-AI`](https://git.unitek-systems.com/UniCORE/UniCORE-AI) (mirror: [GitHub](https://github.com/bryanunitek/UniCORE-AI)) — reference architecture (12 Levels)

**Implementation reference (deployment-shape pair):**
- [`UniCORE`](https://git.unitek-systems.com/UniCORE/UniCORE) (mirror: [GitHub](https://github.com/bryanunitek/UniCORE)) — on-prem-shape
- [`UniSaaS.UniCORE`](https://git.unitek-systems.com/UniCORE/UniSaaS.UniCORE) (mirror: [GitHub](https://github.com/bryanunitek/UniSaaS.UniCORE)) — SaaS-shape

**Substrate-services layer (deployment-shape pair):**
- [`UniCORE.GVB`](https://git.unitek-systems.com/UniCORE/UniCORE.GVB) (mirror: [GitHub](https://github.com/bryanunitek/UniCORE.GVB)) — on-prem-shape
- [`UniSaaS.UniCORE.GVB`](https://git.unitek-systems.com/UniCORE/UniSaaS.UniCORE.GVB) (mirror: [GitHub](https://github.com/bryanunitek/UniSaaS.UniCORE.GVB)) — SaaS-shape

---

## Contact

- **Public discussion:** [GitHub Discussions](https://github.com/bryanunitek/UniSaaS.UniCORE.Apache/discussions)
- **Private contact / connection request:** [LinkedIn — Bryan Fred](https://www.linkedin.com/in/bryan-fred-02209753/)

---

*Author: Bryan Fred, Unitek Systems Limited, Bedford, United Kingdom. Public. Given, not sold. Irrevocable.*
