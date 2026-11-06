# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. Roles below are candidate responsibilities, not mandatory staffing positions. The roles a project needs depend on its size, risk, and context; one person may hold multiple roles when appropriate. For clarity, teams should still identify who is accountable for each decision and handoff.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## Candidate Project Roles and Interactions

The roles in this section make common ownership areas and handoffs explicit. They complement the core roles above and can be combined or omitted based on project needs. If a role is not staffed separately, assign its responsibilities to a named person and make that ownership visible to the team.

| Persona | Core responsibilities | Decision authority | Key collaborators | Key handoffs |
| --- | --- | --- | --- | --- |
| Product Owner / Business Owner | Define desired outcomes and business priorities; clarify needs; accept completed deliverables against agreed criteria; resolve day-to-day scope trade-offs. | Decides product or business priorities and acceptance within the agreed scope and delegated authority; brings material scope, outcome, or funding changes to the Sponsor. | Product Manager, Project Manager, Business Analyst, stakeholders, delivery team. | Gives prioritized outcomes and acceptance decisions to the team; shares priority or scope changes with the Project Manager for plan and stakeholder updates; escalates major changes to the Sponsor. |
| Business Analyst | Elicit, analyze, and document requirements; make acceptance criteria clear and testable; maintain traceability between needs, backlog items, and validation. | Recommends requirement detail and clarification; does not independently approve changes to business priorities or project scope. | Product Owner, Product Manager, Developers, QA / Test Lead, Project Manager, stakeholders. | Hands agreed requirements and acceptance criteria to the delivery team and QA; surfaces ambiguity, scope gaps, and requirement changes to the Product Owner and Project Manager. |
| Technical Lead / Solution Architect | Guide technical design and architecture; coordinate engineering decisions; identify technical risks, constraints, and dependencies. | Makes or facilitates technical decisions within agreed architecture, standards, and delegated authority; escalates material cost, schedule, security, or scope impacts. | Developers, QA / Test Lead, Security / Privacy Lead, Operations / Service Owner, Project Manager. | Provides design decisions, estimates, technical risks, and dependency impacts to the team and Project Manager; shares implementation and support information with QA and Operations. |
| QA / Test Lead | Define test strategy, coverage, and quality evidence; coordinate testing; report defects and quality risks; assess readiness against acceptance criteria. | Recommends quality readiness and release risks; does not waive product acceptance criteria or independently authorize a release unless delegated by the project’s release policy. | Product Owner, Business Analyst, Technical Lead, Developers, Change / Release Manager, Project Manager. | Gives test results, open defects, and readiness recommendation to the Product Owner, Project Manager, and release decision-maker; coordinates defect triage with Developers and Technical Lead. |
| Change / Release Manager | Coordinate release planning, required approvals, deployment communications, and rollback or mitigation readiness. | Coordinates the release process and confirms required controls are complete; release approval remains with the authority defined by the project or organization. | Project Manager, QA / Test Lead, Technical Lead, Operations / Service Owner, stakeholders. | Collects readiness evidence and approvals; communicates deployment plan and status; hands deployment outcomes and release records to Operations and the Project Manager. |
| Operations / Service Owner | Represent supportability, service levels, monitoring, incident response, and operational readiness; participate in service handover. | Defines or advises on operational acceptance and service requirements within their remit; escalates unmet service or operational risks to the Project Manager and appropriate owner. | Technical Lead, Change / Release Manager, QA / Test Lead, Project Manager, support teams. | Shares operational requirements early; reviews runbooks, monitoring, and support plans; accepts or records outstanding handover items after deployment. |
| Security / Privacy Lead (where relevant) | Identify security and privacy requirements and risks; advise on controls, data handling, and required reviews. | Advises on security and privacy compliance and required controls; findings that affect approval or delivery are handled through the applicable organizational review and escalation process. | Product Owner, Business Analyst, Technical Lead, Developers, QA / Test Lead, Project Manager, relevant security or privacy stakeholders. | Communicates requirements and review findings to the delivery team and Project Manager; confirms review evidence or outstanding risks with the designated approval stakeholders. |

### Working with Existing Roles

- **Planning:** The Product Owner / Business Owner and Product Manager clarify outcomes and priorities. The Business Analyst turns needs into traceable requirements and acceptance criteria. The Technical Lead identifies architecture, estimates, and dependencies. The Project Manager incorporates scope, capacity, risks, and dependencies into the delivery plan and escalates decisions that exceed delegated authority.
- **Delivery:** Developers implement the agreed backlog and collaborate with the Technical Lead on design. The Business Analyst and Product Owner resolve requirement questions and assess proposed changes. The Project Manager coordinates schedule, dependencies, risks, and communications; material scope or business trade-offs go to the Product Owner and, when needed, the Sponsor.
- **Quality review:** The QA / Test Lead coordinates validation against acceptance criteria with Developers and the Business Analyst. Results and unresolved risks are shared with the Product Owner and Project Manager. The Product Owner makes acceptance decisions within their authority; quality or compliance exceptions follow the project’s defined approval path.
- **Release:** The Change / Release Manager coordinates approvals and deployment readiness using CI, test, and security evidence. The QA / Test Lead advises on quality readiness, while the Technical Lead and Operations / Service Owner confirm technical and operational preparedness. The release approver is the person or body named by the applicable release policy; the Project Manager coordinates the decision and stakeholder update.
- **Operational handover:** The Technical Lead and Change / Release Manager hand over implementation details, release records, runbooks, monitoring, and known issues to the Operations / Service Owner. The Project Manager tracks outstanding actions and confirms owners and follow-up dates. The Sponsor is engaged by the Project Manager for business-impacting risks or decisions outside delegated authority.

These interaction points are guidance, not a substitute for project-specific decision rights. At kickoff, the Project Manager should document named owners, approval authority, and escalation paths for the project.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
