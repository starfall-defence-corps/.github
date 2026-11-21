# ⭐ Starfall Defence Corps Academy

> *Training the next generation of cyber defence operators through gamified, hands-on Ansible training.*

**A hands-on course in defensive Ansible automation.** Each mission is a GitHub template repo with its own Docker lab — real containers, real SSH, real services — and a grader that checks your work with `make test`. Open a pull request and **ARIA**, the Academy's AI analyst, reviews your code.

The Voidborn are probing our fleet. Your job: learn to defend it — with code.

## 🚀 Start Here

1. **[sdc-academy](https://github.com/starfall-defence-corps/sdc-academy)** — the Academy hub: who it's for, the full mission map, requirements and enrolment
2. **[Mission 0 — Reporting for Duty](https://github.com/starfall-defence-corps/mission-0-reporting-for-duty)** — enrol here: click **Use this template**, clone, `make doctor`, and earn your first green ARIA banner in ~15 minutes
3. Work through the missions in order, starting with [Mission 1.1 — Fleet Census](https://github.com/starfall-defence-corps/mission-1-1-fleet-census) — each repo tells you where to go next

## 🗺️ The Course

| Module | What you learn | Ends with |
|--------|----------------|-----------|
| **Mission 0 — Enrolment** | Environment shakeout: boot a node, first Ansible command | ✅ Your first green ARIA banner (~15 min) |
| **Module 1 — Foundation** (missions 1.1–1.6) | Inventory, playbooks, hardening, templates, roles & Vault, host discovery | 🎯 [Gateway Simulation](https://github.com/starfall-defence-corps/gateway-simulation) — 75-min capstone |
| **Module 2 — Advanced** (missions 2.1–2.6) | Molecule testing, CIS compliance, orchestration, CI/CD, incident response | 🎯 [Master Simulation](https://github.com/starfall-defence-corps/master-simulation) — 3.5-hr capstone |
| **Module 3 — MOS electives** | [MOS 4 — Eyes Everywhere](https://github.com/starfall-defence-corps/mission-3-4-eyes-everywhere) (telemetry at scale) · [MOS 5 — Battle Rattle](https://github.com/starfall-defence-corps/mission-3-5-battle-rattle) (reusable IR runbooks) | 🎯 2+ MOS = Commander rank (more MOS + Final Exercise *in development*) |

## 🤖 ARIA

**[ARIA](https://github.com/starfall-defence-corps/aria)** (Automated Review & Intelligence Analyst) is the shared GitHub Action every mission calls on pull requests, plus the pytest plugin behind every mission's `make test` output. The local grader decides pass or fail; ARIA's PR review adds written feedback when you add an `ANTHROPIC_API_KEY` secret to your copy.

📖 Full lore, briefings, and rank progression: [Course Outline](https://github.com/starfall-defence-corps/sdc-academy/blob/main/COURSE_OUTLINE.md) · Reference library: [Field Manuals](https://github.com/starfall-defence-corps/sdc-academy/tree/main/field-manuals)

---

*Built for cadets who learn by doing, not by reading.*
