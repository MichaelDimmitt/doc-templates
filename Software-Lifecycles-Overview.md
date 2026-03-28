# Software Lifecycles Overview

## The Hierarchy

Everything in software nests inside the **Business Lifecycle** — the top-level lifecycle that encompasses all others.

```
Business Lifecycle
└── Product Lifecycle
    └── SDLC (per feature/release)
        └── Sprint / CI-CD cycles
```

---

## Business Lifecycle (Top Level)

**Phases:** Idea → Validate → Build → Launch → Grow → Scale → Mature → Exit/Reinvent

This is where vision, strategy, money, and sales live. Everything else exists to serve the business goal.

| Artifact | Phase |
|---|---|
| Vision statement | Idea / Validate |
| Business plan | Validate / Build |
| Pitch deck | Validate (fundraising) |
| Revenue model | Launch → ongoing |
| Sales process | Grow / Scale |
| OKRs / strategy | Every phase |

**Note:** Vision sits above all phases — it's the fixed "why" that the entire business lifecycle orients around.

---

## Product Lifecycle

**Phases:** Discovery → Build → Launch → Growth → Maturity → Decline/Pivot

Nested inside the business lifecycle. Answers: *should we build this, are people using it, does it solve the real problem, should we invest more or kill it?*

| Artifact | Phase |
|---|---|
| Project brief, personas | Discovery |
| PRD, roadmap, experience canvas | Discovery |
| Technical spec, project plan | Build |
| Sprint plans, status updates | Build |
| Release notes, postmortem, retro | Launch |
| Goals, signals, measures | Growth / ongoing |
| DACI decisions, meeting notes | Every phase |
| Team health monitor | Every phase |

**Key distinction from SDLC:** SDLC ends at "shipped." Product lifecycle asks "now what?"

---

## SDLC (Software Development Lifecycle)

**Phases:** Requirements → Design → Implementation → Testing → Deployment → Maintenance

Engineering-focused. Describes how code gets built. A product may run many SDLC cycles across its lifetime.

- Audience: engineers, QA, DevOps
- Concerned with: code quality, builds, releases, bugs, technical debt

---

## Other Lifecycles to Know

### Code / System Level
| Lifecycle | Description |
|---|---|
| CI/CD pipeline | Commit → build → test → deploy → monitor |
| API lifecycle | Design → publish → version → deprecate → retire |
| Data lifecycle | Ingestion → processing → storage → consumption → archival/deletion |
| Dependency lifecycle | Adopt → use → deprecate → migrate off |
| Secret/credential lifecycle | Issue → rotate → revoke |

### Product / Business Level
| Lifecycle | Description |
|---|---|
| Product Lifecycle (PLC) | Introduction → growth → maturity → decline (classic marketing model) |
| Customer lifecycle (AARRR) | Awareness → acquisition → activation → retention → referral → revenue |
| Feature lifecycle | Idea → experiment → build → launch → measure → scale or kill |

### Team / Org Level
| Lifecycle | Description |
|---|---|
| Agile/Scrum cadences | Sprint cycles, PI planning (SAFe), quarterly OKR cycles |
| Team Topologies | How teams are structured and interact (stream-aligned, platform, enabling, complicated-subsystem) |

### Infrastructure / Ops Level
| Lifecycle | Description |
|---|---|
| Incident lifecycle | Detect → triage → mitigate → resolve → postmortem |

---

## Meta-Pattern

Almost everything in software has a lifecycle because everything has a beginning, a useful period, and an end. The discipline is knowing *which* lifecycle applies to the decision you're making:

- A PM cares about the product lifecycle
- An SRE cares about the incident lifecycle
- A platform team cares about the API lifecycle
- A founder cares about the business lifecycle
