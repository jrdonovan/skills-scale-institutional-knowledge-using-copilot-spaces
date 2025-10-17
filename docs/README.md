# OctoAcme Project Management Guide

Welcome to OctoAcme's project management documentation! This guide provides a comprehensive overview of how we manage projects, from initial idea to delivery and continuous improvement.

## 🎯 Core Principles

Our project management approach is built on five foundational principles:

- **Customer-first**: Prioritize customer value and usability in every decision
- **Iterative delivery**: Deliver small, testable increments to get feedback early and often
- **Clear ownership**: Every project has a named Project Manager (PM) and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback, learning, and continuous improvement

## 👥 Core Roles

Understanding who does what is essential for effective collaboration:

- **Project Manager (PM)**: Coordinates delivery, schedules, risk management, and communications
- **Product Manager (PdM)**: Defines outcomes, prioritizes backlog, and measures success
- **Developers**: Implement features, collaborate on design, and ensure testability
- **QA/Testing**: Validate quality and acceptance criteria
- **Stakeholders**: Provide inputs, feedback, and approvals

For detailed role descriptions, see [OctoAcme Roles and Personas](octoacme-roles-and-personas.md).

## 🔄 Project Lifecycle

Our projects follow a structured lifecycle with five key stages:

### 1. Initiation
**Goal**: Validate the business need and align stakeholders

- Create a Project One-pager (problem, goal, success metrics)
- Identify stakeholders and establish communication plan
- Define high-level timeline and resource needs
- Build initial risk list
- **Decision Gate**: Move to planning when success metrics are clear and priority is confirmed

📖 [Detailed Initiation Guide](octoacme-project-initiation.md)

### 2. Planning
**Goal**: Turn the approved initiative into an actionable plan

- Hold kickoff meeting with stakeholders and delivery team
- Create prioritized backlog with acceptance criteria
- Estimate scope and define Definition of Done (DoD)
- Identify dependencies and integration points
- Create release plan and milestone map

📖 [Detailed Planning Guide](octoacme-project-planning.md)

### 3. Execution & Tracking
**Goal**: Deliver iteratively while maintaining quality and visibility

- Daily standups (15 min) focused on progress and blockers
- Weekly delivery syncs to show progress and flag risks
- Demo/Review at end of each sprint or milestone
- Use project board workflow: Backlog → Ready → In Progress → In Review → QA → Done
- Track velocity, burndown, and success metrics

📖 [Detailed Execution Guide](octoacme-execution-and-tracking.md)

### 4. Release & Deployment
**Goal**: Safely deliver features to production

- Ensure all acceptance criteria are met
- Complete pre-release checklist (CI passing, security scans, smoke tests)
- Deploy to staging, then production
- Run post-deploy verifications
- Announce release and document known issues

📖 [Detailed Release Guide](octoacme-release-and-deployment.md)

### 5. Retrospective & Close
**Goal**: Capture learnings and drive continuous improvement

- Hold retrospective after each sprint, release, or milestone
- Document what went well and what could be improved
- Create 2-3 actionable items with owners and due dates
- Track action items in backlog and review in weekly PM sync

📖 [Detailed Retrospective Guide](octoacme-retrospective-and-continuous-improvement.md)

## 📅 Communication Cadence

Consistent communication keeps everyone aligned:

- **Weekly sync**: PM + PdM alignment meeting
- **Twice-weekly standups**: Delivery team coordination (or as agreed)
- **Monthly stakeholder updates**: Progress, metrics, and upcoming milestones
- **Ad-hoc escalations**: As needed for blockers and urgent decisions

For risk management and communication templates, see [Risk Management & Communication](octoacme-risks-and-communication.md).

## 📋 Key Artifacts

These documents and tools support our project workflow:

| Artifact | Purpose | Owner | When Created |
|----------|---------|-------|--------------|
| **Project Charter / One-pager** | Define problem, goal, and success metrics | PM + PdM | Initiation |
| **Roadmap and Release Plan** | Map timeline and milestones | PM + PdM | Planning |
| **Sprint/Iteration Backlog** | Track work items with acceptance criteria | PM | Planning & Execution |
| **Definition of Done** | Define quality standards | Team | Planning |
| **Risk Register** | Track and mitigate risks | PM | Initiation & ongoing |
| **Release Notes** | Document changes and known issues | PM + Dev | Release |
| **Retrospective Notes** | Capture learnings and action items | PM | After milestones |

## 🚀 Getting Started

### For New Projects
1. Start with the [Project Initiation Guide](octoacme-project-initiation.md) to create your One-pager
2. Follow the [Planning Guide](octoacme-project-planning.md) to build your backlog
3. Use the [Execution Guide](octoacme-execution-and-tracking.md) to manage daily delivery

### For Existing Team Members
- Keep your Project Charter updated in the project repo
- Review the [Communication Guide](octoacme-risks-and-communication.md) for templates
- Refer to specific process docs as needed during each lifecycle stage

### For Copilot Spaces Integration
Add process-specific docs to `.copilot/` in your project repo if you want GitHub Copilot Spaces to use them as context for AI-assisted project management.

## 📚 Additional Resources

- [Project Management Overview](octoacme-project-management-overview.md) - High-level summary
- [Roles and Personas](octoacme-roles-and-personas.md) - Detailed role descriptions
- [Risk Management & Communication](octoacme-risks-and-communication.md) - Communication templates and escalation paths

---

**Questions or suggestions?** Reach out to your Project Manager or contribute improvements to these docs through pull requests.
