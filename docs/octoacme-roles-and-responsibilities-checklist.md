# OctoAcme — Roles & Responsibilities Checklist

Use this checklist at project kickoff and during planning to assign clear ownership across common activities. Complete the **Role Assignment** section for each project and reference it throughout initiation, planning, and execution.

See [Roles and Personas](./octoacme-roles-and-personas.md) for full role descriptions.

---

## RACI Key

| Symbol | Meaning |
|--------|---------|
| **R** | Responsible — does the work |
| **A** | Accountable — final decision / sign-off |
| **C** | Consulted — provides input before the decision |
| **I** | Informed — notified of outcomes |

---

## Activity → Role Mapping

| Activity | PM (Project) | PdM (Product) | Developer | QA / Testing | Scrum Master | Business Analyst | UX Designer | Customer Support | DevOps Engineer |
|---|---|---|---|---|---|---|---|---|---|
| Requirements gathering | C | A | C | C | I | R | C | C | I |
| User story writing & acceptance criteria | I | A | C | C | I | R | C | I | I |
| UX / Wireframe design | I | C | C | I | I | C | R/A | C | I |
| Backlog prioritisation | C | A | C | C | I | C | C | C | I |
| Sprint planning | C | C | C | C | R/A | C | I | I | I |
| Estimation | I | C | R | C | A | C | C | I | C |
| Definition of Done approval | C | A | R | R | C | C | I | I | C |
| CI/CD pipeline ownership | I | I | C | C | I | I | I | I | R/A |
| Environment provisioning | I | I | C | C | I | I | I | I | R/A |
| Test plan creation | I | C | C | R/A | I | C | I | I | C |
| Acceptance / UAT sign-off | C | A | I | R | I | C | C | C | I |
| Release plan & go/no-go | A | C | C | C | C | I | I | I | C |
| Deployment execution | I | I | C | I | I | I | I | I | R/A |
| Monitoring & alerting setup | I | I | C | I | I | I | I | I | R/A |
| Incident response | A | I | R | C | I | I | I | R | R |
| Incident communication (external) | A | C | I | I | I | I | I | R | C |
| Risk register ownership | R/A | C | C | C | C | C | I | I | C |
| Stakeholder status updates | R/A | C | I | I | I | I | I | I | I |
| Retrospective facilitation | I | I | I | I | R/A | I | I | I | I |
| Customer feedback triage | C | A | C | I | I | C | C | R | I |

> **Note:** This table reflects typical patterns. Adjust assignments per project during kickoff.

---

## Role Assignment for a Project

Complete this section at the project kickoff and keep it up to date throughout the project lifecycle.

| Role | Assigned To | Notes / Scope Limits |
|---|---|---|
| Project Manager | | |
| Product Manager | | |
| Scrum Master | | |
| Business Analyst | | |
| UX Designer | | |
| Lead Developer | | |
| Developer(s) | | |
| QA / Testing | | |
| DevOps Engineer | | |
| Customer Support Representative | | |
| Key Stakeholder(s) | | |

### Assignment Checklist

- [ ] All roles above are either assigned or explicitly marked "not needed for this project"
- [ ] Each assigned person has acknowledged their responsibilities
- [ ] Role assignments are recorded in the project one-pager or project board
- [ ] Escalation path is defined for each role (backup contact)
- [ ] RACI table reviewed and adjusted for project-specific activities
- [ ] Checklist linked from the project initiation doc and planning board

---

## Cross-Functional Ownership Quick Reference

Use this at a glance during initiation and planning when questions of ownership arise.

| "Who owns…" | Primary Owner | See also |
|---|---|---|
| Product vision & roadmap | Product Manager | Business Analyst |
| Requirements & user stories | Business Analyst | Product Manager |
| User experience & prototypes | UX Designer | Business Analyst |
| Schedule & milestone tracking | Project Manager | Scrum Master |
| Sprint cadence & ceremonies | Scrum Master | Project Manager |
| Code quality & implementation | Developer | DevOps Engineer |
| CI/CD & deployment pipeline | DevOps Engineer | Developer |
| Test strategy & QA sign-off | QA / Testing | Developer |
| Customer feedback & support | Customer Support Rep | Product Manager |
| Risk register | Project Manager | All roles |
| Incident response | DevOps Engineer | Project Manager |
