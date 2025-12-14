# OctoAcme — Cross-Team Communication Guide

## Purpose
Establish clear protocols for effective communication and collaboration across multiple teams, reducing friction and improving delivery outcomes.

## When to Use Cross-Team Communication
- Dependencies between teams require coordination
- Shared resources or infrastructure are involved
- Cross-functional initiatives span multiple team boundaries
- Incidents or escalations impact multiple teams
- Knowledge sharing or best practices need to be disseminated

---

## Cross-Team Communication Checklist

### Planning Phase
- [ ] Identify all teams involved in the initiative
- [ ] Map dependencies between teams early in planning
- [ ] Establish primary contact person from each team
- [ ] Define shared success metrics and goals
- [ ] Create a RACI matrix for key deliverables (Responsible, Accountable, Consulted, Informed)
- [ ] Schedule recurring sync meetings if long-term collaboration is needed
- [ ] Document communication channels and protocols in project plan

### Dependency Management
- [ ] Document each dependency in the project board or tracking tool
- [ ] Assign owners for each side of the dependency
- [ ] Set clear deadlines and handoff criteria
- [ ] Establish checkpoints to validate dependency status
- [ ] Create contingency plans for critical dependencies
- [ ] Escalate blocked dependencies promptly per escalation path

### Communication Cadence
- [ ] Determine appropriate meeting frequency (weekly, bi-weekly, etc.)
- [ ] Set up shared communication channels (Slack channel, Teams group, etc.)
- [ ] Define async update format (written status updates, project board updates)
- [ ] Schedule regular demos or show-and-tell sessions
- [ ] Agree on response time expectations for questions or requests

### Documentation Standards
- [ ] Use a single source of truth for project status (README, project board, wiki)
- [ ] Maintain a shared decision log for cross-team decisions
- [ ] Document integration points and API contracts
- [ ] Create runbooks for shared systems or processes
- [ ] Keep meeting notes accessible to all relevant teams
- [ ] Link related issues and PRs across team repositories

### Conflict Resolution
- [ ] Define escalation path for disagreements or blockers
- [ ] Establish criteria for when to escalate to leadership
- [ ] Document decision-making authority and approval workflows
- [ ] Create a forum for technical discussions and trade-off analysis
- [ ] Maintain blameless culture focused on outcomes, not individuals

---

## Communication Templates

### Cross-Team Status Update Template
```
## Team: [Your Team Name]
## Project/Initiative: [Initiative Name]
## Date: [YYYY-MM-DD]

### Progress Since Last Update:
- [Key accomplishments]
- [Milestones reached]

### What We Need from Other Teams:
- [Team Name]: [Specific request or dependency]

### What We're Providing to Other Teams:
- [Team Name]: [Deliverable or support being provided]

### Risks & Blockers:
- [Any cross-team risks or blockers requiring attention]

### Next Steps:
- [Planned work for next period]
```

### Dependency Handoff Template
```
## From Team: [Team A]
## To Team: [Team B]
## Deliverable: [Name of deliverable]
## Handoff Date: [YYYY-MM-DD]

### What's Being Handed Off:
- [Description of work completed]
- [Links to PRs, documents, or artifacts]

### Acceptance Criteria:
- [ ] [Criterion 1]
- [ ] [Criterion 2]

### Known Issues or Limitations:
- [Any caveats or technical debt]

### Support Available:
- Contact: [Name, Slack handle]
- Availability: [Office hours, response time]
- Documentation: [Links to relevant docs]
```

### Cross-Team Incident Communication Template
```
## Incident: [Incident ID/Name]
## Severity: [High/Medium/Low]
## Affected Teams: [List of teams]
## Last Updated: [Timestamp]

### Current Status:
- [Brief status summary]

### Impact:
- [What's affected, scope of impact]

### Actions Taken:
- [What's been done so far]

### Teams Involved & Responsibilities:
- [Team A]: [Their role/actions]
- [Team B]: [Their role/actions]

### Next Update: [Time of next update]
```

---

## Best Practices for Cross-Team Collaboration

### Do's
- ✅ **Communicate proactively** — Share updates before being asked
- ✅ **Be explicit** — Don't assume others have context
- ✅ **Document decisions** — Capture rationale for future reference
- ✅ **Respect boundaries** — Understand other teams' priorities and constraints
- ✅ **Show appreciation** — Recognize contributions from partner teams
- ✅ **Use async communication** — Respect time zones and work schedules
- ✅ **Keep stakeholders informed** — Use RACI to determine who needs updates

### Don'ts
- ❌ **Don't bypass communication channels** — Follow established protocols
- ❌ **Don't assume alignment** — Verify understanding explicitly
- ❌ **Don't hoard information** — Share knowledge openly
- ❌ **Don't create surprise dependencies** — Surface needs early
- ❌ **Don't blame other teams** — Focus on solutions, not fault
- ❌ **Don't over-communicate** — Be concise and respect others' time
- ❌ **Don't skip retrospectives** — Use them to improve collaboration

---

## Meeting Types for Cross-Team Work

### Kickoff Meeting
**Frequency:** Once at project start  
**Participants:** All team leads and key contributors  
**Purpose:** Align on goals, scope, responsibilities, and communication plan  
**Duration:** 60 minutes

### Sync Meeting
**Frequency:** Weekly or bi-weekly  
**Participants:** Representatives from each team  
**Purpose:** Status updates, dependency checks, issue resolution  
**Duration:** 30 minutes

### Technical Design Review
**Frequency:** As needed during design phase  
**Participants:** Technical leads and architects  
**Purpose:** Review integration points, APIs, and technical approach  
**Duration:** 60-90 minutes

### Demo / Show & Tell
**Frequency:** End of sprint or milestone  
**Participants:** All team members and stakeholders  
**Purpose:** Showcase integrated work, gather feedback  
**Duration:** 30-45 minutes

### Retrospective
**Frequency:** After major milestone or release  
**Participants:** All team members involved  
**Purpose:** Reflect on collaboration, identify improvements  
**Duration:** 60 minutes

---

## Escalation Path for Cross-Team Issues

1. **Team Level** — Discuss directly between team representatives
2. **Lead Level** — Escalate to team leads if no resolution in 2 business days
3. **Manager Level** — Escalate to managers if blocking critical path
4. **Director/VP Level** — Escalate for strategic decisions or resource conflicts

**When to escalate:**
- Issue is blocking critical path for more than 2 days
- Repeated attempts at resolution have failed
- Decision requires authority beyond team leads
- Resource constraints cannot be resolved locally

---

## Tools & Resources

### Communication Tools
- Slack/Teams: Real-time chat and channels
- Email: Formal communications and decisions
- GitHub Issues: Work tracking and transparency
- Confluence/Wiki: Shared documentation
- Video conferencing: Synchronous meetings

### Tracking Tools
- GitHub Projects: Cross-team project boards
- JIRA: Issue and dependency tracking
- Miro/Mural: Collaborative whiteboarding
- Shared calendars: Meeting coordination

---

## Related Resources
- [Roles & Personas](octoacme-roles-and-personas.md) — Understand responsibilities across roles
- [Risk Management & Communication](octoacme-risks-and-communication.md) — Risk and stakeholder communication
- [Execution & Tracking](octoacme-execution-and-tracking.md) — Day-to-day execution practices
- [Stakeholder Engagement Checklist](octoacme-stakeholder-engagement.md) — Managing stakeholder relationships

---

## Tips for Effective Cross-Team Communication

1. **Start with why** — Explain the business context and impact
2. **Use visuals** — Diagrams and flowcharts clarify complex topics
3. **Be specific** — Provide concrete examples and action items
4. **Follow up in writing** — Document verbal agreements
5. **Celebrate wins together** — Build team camaraderie
6. **Learn from failures** — Use incidents as learning opportunities
7. **Invest in relationships** — Build trust through regular interaction
