# OctoAcme Project Management — Quick Start Guide

## Purpose

This repository centralizes and standardizes OctoAcme's project management processes, enabling teams to:

- **Onboard quickly**: New team members can rapidly understand how projects are run
- **Scale institutional knowledge**: Leverage GitHub Copilot Spaces to make process documentation accessible and context-aware
- **Maintain consistency**: Apply uniform standards across all cross-functional projects
- **Improve collaboration**: Share a common language and framework for delivering value

By storing these processes in version control and integrating them with Copilot Spaces, we ensure that both humans and AI tools can access, understand, and apply our practices effectively.

---

## Project Lifecycle Overview

OctoAcme follows a structured yet iterative approach to project delivery:

### 1. **Initiation** — Validate & Authorize
Define the business need, align stakeholders, and create a lightweight project plan.

**Key Activities:**
- Develop Project One-pager (problem, goal, success metrics)
- Identify stakeholders and champions
- Define success criteria and initial timeline
- Conduct go/no-go decision

**Deliverables:** Project One-pager, stakeholder list, high-level timeline, initial risk list

📄 **[Read more: Project Initiation Guide →](octoacme-project-initiation.md)**

---

### 2. **Planning** — Design & Organize
Turn the approved initiative into an actionable backlog and delivery plan.

**Key Activities:**
- Hold kickoff meeting with stakeholders and delivery team
- Create prioritized backlog with acceptance criteria
- Estimate scope (T-shirt sizing or story points)
- Define Definition of Done (DoD)
- Identify dependencies and create release plan

**Deliverables:** Prioritized backlog, release timeline, Definition of Done, risk register

📄 **[Read more: Project Planning Guide →](octoacme-project-planning.md)**

---

### 3. **Execution & Tracking** — Build & Monitor
Manage day-to-day execution and track progress toward milestones.

**Key Activities:**
- Daily standups and weekly delivery syncs
- Pull request workflow with code reviews
- Quality assurance and automated testing
- Track velocity, burndown, and success metrics
- Escalate and resolve blockers

**Deliverables:** Working software increments, sprint demos, updated project board, metrics dashboards

📄 **[Read more: Execution & Tracking Guide →](octoacme-execution-and-tracking.md)**

---

### 4. **Release & Deployment** — Ship & Verify
Deploy features to production with reduced risk and improved observability.

**Key Activities:**
- Complete pre-release requirements (CI, security scans, smoke tests)
- Deploy to staging and production
- Run post-deployment verifications
- Publish release notes and announce to stakeholders

**Deliverables:** Deployed release, release notes, rollback plan, stakeholder announcement

📄 **[Read more: Release & Deployment Guide →](octoacme-release-and-deployment.md)**

---

### 5. **Closing & Continuous Improvement** — Learn & Iterate
Capture learnings and convert them into actionable improvements.

**Key Activities:**
- Conduct retrospectives after sprints, releases, or milestones
- Identify what went well and what could be improved
- Define 2-3 high-priority action items with owners
- Track improvements and measure impact

**Deliverables:** Retrospective notes, action items backlog, continuous improvement metrics

📄 **[Read more: Retrospective & Continuous Improvement Guide →](octoacme-retrospective-and-continuous-improvement.md)**

---

## Roles & Responsibilities

OctoAcme projects involve multiple personas working collaboratively:

### **Project Manager (PM)**
Coordinates delivery activities, manages schedules, risks, and communications.

**Key Responsibilities:**
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent documentation and status reporting

---

### **Product Manager (PdM)**
Defines what should be built to deliver customer and business value.

**Key Responsibilities:**
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders on trade-offs
- Validate solutions through user research and metrics

---

### **Developers**
Design, build, test, and deliver software components.

**Key Responsibilities:**
- Implement features to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Help estimate work and identify technical risks

---

### **QA/Testing**
Validate quality and ensure acceptance criteria are met.

**Key Responsibilities:**
- Execute test plans and validate acceptance criteria
- Report and track defects
- Perform exploratory testing for edge cases

---

### **Stakeholders**
Provide inputs, approvals, and feedback throughout the project lifecycle.

**Key Responsibilities:**
- Define business requirements and success criteria
- Review progress and provide timely feedback
- Make key decisions when needed

---

### **Additional Collaborative Roles**

OctoAcme projects also benefit from additional specialized roles that enhance cross-functional collaboration:

- **Scrum Master:** Facilitates agile ceremonies and removes impediments
- **UX Designer:** Designs user-centered interfaces and validates usability
- **Business Analyst:** Bridges business and technical teams with clear requirements
- **Support Engineer:** Provides customer insights and troubleshoots issues

📄 **[Read more: Detailed Personas & Responsibilities →](octoacme-roles-and-personas.md)**

---

## Communication Workflows & Cadence

Clear, consistent communication is essential to project success.

### **Regular Cadence**
| Meeting | Frequency | Participants | Purpose |
|---------|-----------|--------------|---------|
| **Daily Standup** | Daily (15 min) | Delivery team | Share progress, blockers, dependencies |
| **PM + PdM Sync** | Weekly | PM, Product Manager | Align on priorities, risks, decisions |
| **Delivery Team Sync** | Weekly | PM, Developers, QA | Review progress, update risks, coordinate |
| **Sprint Demo/Review** | End of sprint | Team + Stakeholders | Showcase completed work |
| **Stakeholder Updates** | Monthly | PM, Stakeholders | Report status, upcoming milestones |
| **Retrospective** | End of sprint/release | Delivery team | Reflect and identify improvements |

### **Status Reporting Template**
- **Progress this week:** Summary of completed work
- **Next steps:** Upcoming priorities
- **Risks & blockers:** Open issues requiring attention
- **Asks/Decisions needed:** Input or approvals required

### **Escalation Paths**
1. **Level 1:** Team-level triage in daily standup
2. **Level 2:** PM escalates to Product Lead and dependent teams
3. **Level 3:** Sponsor-level escalation for business-impacting issues

📄 **[Read more: Risk Management & Communication →](octoacme-risks-and-communication.md)**

---

## Quality Assurance & Risk Management

### **Quality Assurance Practices**
- **Unit tests** for new logic
- **Integration tests** where applicable
- **End-to-end smoke tests** for critical flows before release
- **Security scanning** in CI/CD pipeline
- **Manual QA** for feature acceptance when needed
- **Code reviews** with at least one approval before merging

### **Risk Management Process**
Risks are tracked in a **Risk Register** with the following attributes:
- ID, Description, Impact (High/Med/Low), Likelihood (High/Med/Low)
- Owner, Mitigation plan, Status

**Risk Lifecycle:**
1. **Identify:** During planning and ongoing execution
2. **Assess:** Estimate impact and likelihood
3. **Mitigate:** Reduce via actions and contingency plans
4. **Monitor:** Review at weekly syncs and update status

📄 **[Read more: Execution & Tracking →](octoacme-execution-and-tracking.md)**  
📄 **[Read more: Risk Management & Communication →](octoacme-risks-and-communication.md)**

---

## Key Artifacts & Templates

OctoAcme projects use standardized artifacts to maintain consistency:

| Artifact | Purpose | Created During |
|----------|---------|----------------|
| **Project One-pager** | Define problem, goal, success metrics | Initiation |
| **Stakeholder List & Communication Plan** | Identify key contacts and update cadence | Initiation |
| **Prioritized Backlog** | Track work items with acceptance criteria | Planning |
| **Definition of Done (DoD)** | Quality standards for completed work | Planning |
| **Release Plan & Milestone Map** | Timeline and delivery schedule | Planning |
| **Risk Register** | Track and mitigate project risks | Planning, updated weekly |
| **Sprint/Iteration Backlog** | Work committed for current sprint | Execution |
| **Test Plans** | QA strategy and test cases | Planning/Execution |
| **Release Notes** | Document changes and migration steps | Release |
| **Retrospective Notes & Action Items** | Capture learnings and improvements | Closing |

### Process Checklists

To enhance consistency and accountability, use these checklists throughout the project lifecycle:

- **[Onboarding Checklist](octoacme-onboarding-checklist.md)** — Accelerate new team member integration
- **[Cross-Team Communication Guide](octoacme-cross-team-communication.md)** — Coordinate across multiple teams
- **[Stakeholder Engagement Checklist](octoacme-stakeholder-engagement.md)** — Systematically manage stakeholder relationships

📄 **[View sample templates in individual guides →](octoacme-project-management-overview.md)**

---

## Core Principles

OctoAcme project management is guided by these principles:

- **Customer-first:** Prioritize customer value and usability
- **Iterative delivery:** Deliver small, testable increments
- **Clear ownership:** Each project has a named PM and Product Lead
- **Data-informed decisions:** Measure impact and iterate based on evidence
- **Psychological safety:** Encourage feedback and learning

📄 **[Read more: Project Management Overview →](octoacme-project-management-overview.md)**

---

## Getting Started

### For New Team Members
1. Read this README to understand the overall framework
2. Review the [Project Management Overview](octoacme-project-management-overview.md) for core principles
3. Explore the [Roles & Personas](octoacme-roles-and-personas.md) guide to understand your responsibilities
4. Dive into lifecycle-specific guides as needed for your current project phase

### For Project Managers
1. Start with the [Initiation Guide](octoacme-project-initiation.md) when kicking off a new project
2. Use the templates provided in each guide
3. Store project artifacts in your project repo (in `docs/` or `.copilot/`)
4. Update status weekly and keep the Risk Register current

### For Developers
1. Review the [Execution & Tracking](octoacme-execution-and-tracking.md) guide for workflow standards
2. Follow PR conventions and quality standards
3. Participate in standups and sprint planning
4. Contribute to retrospectives

---

## Using These Docs with Copilot Spaces

To maximize the value of these processes:

1. **Add to `.copilot/` directory:** Copy relevant docs into your project's `.copilot/` folder so Copilot Spaces can use them as context
2. **Reference in prompts:** When asking Copilot for help, reference specific guides (e.g., "Following the OctoAcme planning guide, help me...")
3. **Keep updated:** As processes evolve, update the docs in this repository to maintain a single source of truth

---

## Additional Resources

### Core Process Guides
- [Project Management Overview](octoacme-project-management-overview.md) — High-level principles and scope
- [Project Initiation Guide](octoacme-project-initiation.md) — Validate and authorize work
- [Project Planning Guide](octoacme-project-planning.md) — Create actionable plans and backlogs
- [Execution & Tracking Guide](octoacme-execution-and-tracking.md) — Day-to-day management
- [Release & Deployment Guide](octoacme-release-and-deployment.md) — Ship safely to production
- [Retrospective & Continuous Improvement Guide](octoacme-retrospective-and-continuous-improvement.md) — Learn and iterate
- [Roles & Personas](octoacme-roles-and-personas.md) — Detailed role definitions
- [Risk Management & Communication](octoacme-risks-and-communication.md) — Manage risks and stakeholders

### Checklists & Tools
- [Onboarding Checklist](octoacme-onboarding-checklist.md) — Structured onboarding for new team members
- [Cross-Team Communication Guide](octoacme-cross-team-communication.md) — Effective cross-team collaboration
- [Stakeholder Engagement Checklist](octoacme-stakeholder-engagement.md) — Systematic stakeholder management

---

## Questions or Feedback?

If you have questions about these processes or suggestions for improvement:
- Open an issue in this repository
- Discuss in your team's retrospective
- Contact the Project Management Office (PMO)

Remember: These processes are living documents. We continuously improve them based on team feedback and lessons learned.
