# OctoAcme Project Management Docs

Welcome to the OctoAcme project management documentation suite. This collection provides the centralized source of truth for our project management processes, structured knowledge, and best practices. Use these artifacts to onboard, learn, or reference OctoAcme approaches to delivering projects with clarity, accountability, and efficiency.

---

## Project Management Processes (Summary)

OctoAcme follows a structured, customer-first project management approach that emphasizes iterative delivery, clear ownership, and data-informed decisions. The organization operates projects through a well-defined lifecycle spanning five phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**. This phased approach ensures that all projects begin with validated business needs and measurable success criteria, move through organized planning with prioritized backlogs and risk management, execute with daily oversight and quality checkpoints, and conclude with systematic knowledge capture. The framework is intentionally lightweight yet comprehensive, requiring key artifacts like Project One-pagers, Risk Registers, and Sprint Backlogs to maintain alignment without unnecessary overhead.

OctoAcme defines four core personas that work in close collaboration: **Project Managers** coordinate schedules, risks, and communications to keep delivery on track; **Product Managers** define what should be built and prioritize the backlog based on customer value; **Developers** implement features while maintaining high standards for testing and code quality; and **QA/Testing** validates acceptance criteria and product quality. Communication happens through multiple synchronized cadences—daily 15-minute standups focused on progress and blockers, weekly delivery syncs between PM and PdM to review progress and flag risks, and monthly stakeholder updates. A clear escalation path exists for blockers: team-level triage → PM escalation → Product Lead involvement → sponsor-level escalation for business-impacting issues.

During execution, OctoAcme uses GitHub Projects with a standardized workflow (Backlog → Ready → In Progress → In Review → QA → Done) to maintain visibility and flow. Pull requests are kept small (≤400 lines when possible), require at least one approval, and must pass automated CI tests and security scanning before merging. Quality is enforced through unit tests for new logic, integration tests where applicable, end-to-end smoke tests before release, and manual QA for feature acceptance. Teams track velocity and burndown metrics, monitor success indicators tied to the original Project One-pager, and maintain dashboards for error rates, latency, and usage signals.

Releases are standardized by type (Patch, Minor, Major) with pre-release requirements including passing CI, drafted release notes, and documented rollback plans. Risk management is proactive—teams maintain a Risk Register throughout the project lifecycle (ID, Description, Impact, Likelihood, Owner, Mitigation, Status) and review it weekly. After each sprint, release, or incident, OctoAcme conducts retrospectives to capture learnings and convert them into actionable improvement items tracked in the backlog. This cycle of execution, reflection, and continuous enhancement embeds organizational learning and ensures processes evolve based on real team experience.

---

## Quick Links to Process Docs

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](octoacme-roles-and-personas.md)
