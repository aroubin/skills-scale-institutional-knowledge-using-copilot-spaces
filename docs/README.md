# OctoAcme Project Management Overview

> This document provides a brief, comprehensive summary of the project management processes used by OctoAcme. For full details, refer to the individual documents in this folder. See also: [Issue #2 – Process doc summary: OctoAcme program management workflows](https://github.com/aroubin/skills-scale-institutional-knowledge-using-copilot-spaces/issues/2).

---

## Summary

OctoAcme's project management approach is grounded in clear roles, structured workflows, and principles that prioritize customer value and iterative delivery. The organization divides project execution into lifecycle stages: **initiation**, **planning**, **execution**, **release**, and **retrospectives**. Each project begins with a defined one-pager outlining goals, metrics, stakeholders, and risks, establishing a common baseline. Planning then breaks down initiatives into actionable backlogs with acceptance criteria, prioritized work, and a release plan, ensuring dependencies and potential risks are clearly identified and mapped.

Key roles are deliberately delineated for clarity and accountability. The **Project Manager (PM)** steers delivery and communication, coordinates planning, and manages risks. The **Product Manager** defines priorities and success metrics, maintaining alignment with stakeholders. **Developers** drive feature implementation, quality, and test coverage, while dedicated **QA** ensures acceptance criteria are validated. Each persona is actively involved in regular standups, reviews, and planning sessions, encouraging transparency and psychological safety.

Communication is structured through frequent cadences: daily standups and weekly syncs for rapid issue escalation, monthly stakeholder updates, and regular retrospectives. Project boards in GitHub provide visibility into work status, while decision and risk registers document and track key actions. Status and incident templates ensure stakeholders remain informed of progress, risks, and resolutions in a consistent manner.

Quality assurance is deeply integrated. Automated tests, linting, and security scans are prerequisites to merging pull requests, and manual QA is conducted for feature acceptance as needed. Releases follow a rigorous checklist—deployments are staged, smoke-tested, and accompanied by rollback plans and release notes. Retrospectives after each release or milestone distill lessons learned, transforming them into actionable improvements tracked through backlogs and reviewed in ongoing cycles, reinforcing a culture of continuous improvement and excellence.

---

## Key Workflows

| Stage | Description | Reference |
|-------|-------------|-----------|
| Initiation | Define project goals, metrics, stakeholders, and risks via a one-pager | [octoacme-project-initiation.md](./octoacme-project-initiation.md) |
| Planning | Break down initiatives into backlogs, set acceptance criteria, map dependencies | [octoacme-project-planning.md](./octoacme-project-planning.md) |
| Execution & Tracking | Run standups, manage the board, escalate blockers, track decisions | [octoacme-execution-and-tracking.md](./octoacme-execution-and-tracking.md) |
| Release & Deployment | Staged deployments, smoke tests, rollback plans, release notes | [octoacme-release-and-deployment.md](./octoacme-release-and-deployment.md) |
| Retrospectives | Capture lessons learned, create improvement actions, feed back into backlog | [octoacme-retrospective-and-continuous-improvement.md](./octoacme-retrospective-and-continuous-improvement.md) |

---

## Core Roles & Personas

| Role | Responsibilities |
|------|-----------------|
| Project Manager (PM) | Delivery ownership, risk management, stakeholder communication, planning coordination |
| Product Manager | Priority definition, success metrics, stakeholder alignment |
| Developer | Feature implementation, test coverage, code quality |
| QA Engineer | Acceptance criteria validation, exploratory testing, release sign-off |

See [octoacme-roles-and-personas.md](./octoacme-roles-and-personas.md) for full persona descriptions.

---

## Communication Strategies & Cadence

- **Daily standups** – surface blockers quickly and keep the team aligned
- **Weekly syncs** – review progress, risks, and upcoming milestones
- **Monthly stakeholder updates** – communicate status, decisions, and risks upward
- **Retrospectives** – held after each release or milestone to capture learnings
- **GitHub project boards** – real-time visibility into work status
- **Risk & decision registers** – structured tracking of key decisions and mitigations
- **Status & incident templates** – consistent stakeholder communication during incidents

See [octoacme-risks-and-communication.md](./octoacme-risks-and-communication.md) for details.

---

## Quality Assurance Practices

- Automated tests, linting, and security scans are required before merging pull requests
- Manual QA validates feature acceptance criteria prior to release
- Releases follow a rigorous checklist: staged deployment → smoke testing → rollback plan → release notes
- Post-release retrospectives capture issues and drive continuous improvement

See [octoacme-project-management-overview.md](./octoacme-project-management-overview.md) for the overarching QA philosophy.
