# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. Titles and team structures vary by organization, and one person may hold multiple roles on a smaller team. When responsibilities are combined, make the decision owner and handoffs explicit so accountability remains clear.

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
- Weekly alignment with project and engineering leads
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

## Executive Sponsor / Business Owner

### Role Summary
The Executive Sponsor or Business Owner is accountable for the business outcome and ensures the initiative has appropriate priority, resources, and organizational support.

### Responsibilities
- Confirm the business outcome, strategic fit, and priority with the Product Manager
- Secure or escalate resource and funding needs
- Resolve escalated scope or priority conflicts
- Make or escalate the final business go/no-go decision using delivery, risk, and readiness input

### Decision and Approval Boundaries
Owns business priority, resource sponsorship, and business go/no-go decisions. Does not replace the Product Manager's day-to-day backlog prioritization or technical leads' technical recommendations; seeks their input before deciding.

### Typical Communication and Handoffs
Receives concise status, risks, options, and explicit decision requests from the Project Manager; aligns with the Product Manager on outcomes and priority. Provides decisions and changes in direction back to both so plans and stakeholders can be updated. Stakeholders contribute business impact and readiness input.

---

## Technical Lead / Architect

### Role Summary
The Technical Lead or Architect guides the technical approach and helps the team make sound design, integration, and quality decisions.

### Responsibilities
- Lead technical design and document significant architecture decisions
- Advise on integration choices, technical standards, and non-functional requirements
- Work with Developers to break down work, estimate effort, and review implementation
- Identify technical dependencies and risks, and coordinate mitigation

### Decision and Approval Boundaries
Owns or recommends technical design decisions within agreed architecture and engineering standards. Escalates material cost, schedule, security, or product trade-offs to the appropriate Product Manager, Project Manager, or Executive Sponsor rather than unilaterally changing scope.

### Typical Communication and Handoffs
Pairs with Developers on designs, estimates, reviews, and technical risk actions; explains feasibility and trade-offs to the Product Manager; gives the Project Manager dependency and delivery-risk updates. Provides implementation and technical-readiness information to QA/Testing and Operations/Site Reliability.

---

## UX / Product Designer

### Role Summary
The UX or Product Designer researches user needs and shapes interactions and visual experiences that are useful, accessible, and testable.

### Responsibilities
- Plan or conduct user research and synthesize findings
- Create interaction flows, prototypes, and visual design specifications
- Validate usability and incorporate feedback
- Consider accessibility and communicate design rationale and edge cases

### Decision and Approval Boundaries
Owns design recommendations and design artifacts within the agreed product direction. The Product Manager owns product priorities and outcomes; design, implementation, and scope trade-offs are agreed with the relevant product and technical partners.

### Typical Communication and Handoffs
Works with the Product Manager to connect user needs to problem statements and acceptance criteria; reviews feasibility with Developers and the Technical Lead; partners with QA/Testing to make expected behavior and usability testable. Shares research and prototypes with stakeholders for feedback, which the Product Manager helps prioritize.

---

## Security / Privacy Lead

### Role Summary
The Security or Privacy Lead advises the team on protecting systems and data, meeting applicable requirements, and managing security and privacy risks.

### Responsibilities
- Identify security, privacy, threat, and compliance requirements and risks
- Recommend controls and required reviews
- Advise the Technical Lead and Developers on secure implementation and data handling
- Coordinate or advise on verification of required controls and remediation of findings

### Decision and Approval Boundaries
Defines or interprets security and privacy requirements within their remit and identifies findings that must be resolved or formally accepted by an authorized owner. Does not make product-priority or business go/no-go decisions; communicates unresolved release risks to the Project Manager and decision-makers.

### Typical Communication and Handoffs
Partners with the Technical Lead and Developers to integrate controls into designs and implementation, and with QA/Testing to verify them. Records review outcomes and open risks for the Project Manager, who coordinates escalations and release readiness. Provides risk input to the Product Manager and Executive Sponsor when decisions affect scope or release.

---

## Data / Analytics Lead

### Role Summary
The Data or Analytics Lead makes sure the team can measure whether the work achieves its intended outcomes and that reported data is fit for purpose.

### Responsibilities
- Define instrumentation, event, and measurement approaches
- Advise on data quality, privacy-aware collection, and reporting
- Validate analytics implementation and outcome reporting
- Surface measurement limitations and insights to inform decisions

### Decision and Approval Boundaries
Owns analytics definitions and measurement recommendations in collaboration with the Product Manager. The Product Manager owns product success metrics and prioritization; data collection must also satisfy applicable Security/Privacy requirements.

### Typical Communication and Handoffs
Works with the Product Manager to operationalize success metrics, with Developers to implement and document events, and with QA/Testing to verify instrumentation. Shares progress and outcome data with the Project Manager for status reporting and with the Product Manager and stakeholders for product decisions.

---

## Operations / Site Reliability Lead

### Role Summary
The Operations or Site Reliability Lead helps ensure the service can be deployed, operated, supported, and recovered reliably.

### Responsibilities
- Define operational readiness, monitoring, alerting, support, and reliability needs
- Contribute to deployment, rollback, capacity, and recovery planning
- Review operational risks and readiness evidence
- Support incident response and post-incident learning, including follow-up actions

### Decision and Approval Boundaries
Owns or advises on operational readiness criteria and operational risk within their remit. Raises unmet readiness requirements and recommends whether operational safeguards are sufficient; business go/no-go remains with the authorized sponsor or business owner, informed by the Product Manager and Project Manager.

### Typical Communication and Handoffs
Coordinates readiness checks with Developers and QA/Testing, and shares operational dependencies and risks with the Project Manager. Works with the Product Manager and stakeholders to explain service impact, support expectations, and rollout considerations. Provides monitoring and incident learnings to Developers and relevant decision-makers after release.

---

## QA / Testing

QA/Testing plans and performs verification against acceptance criteria and quality expectations, reports findings, and provides test and readiness evidence to the team. It works with Product Managers to clarify expected behavior, Developers to reproduce and resolve defects, and Technical Leads and Operations/Site Reliability on technical and operational checks. The Project Manager coordinates defect and readiness visibility; release risk decisions are made by the authorized decision-maker with appropriate input.

## Stakeholders

Stakeholders provide relevant customer, business, operational, and organizational context and feedback. They collaborate with the Product Manager on needs and impact, provide readiness input to the Project Manager and Executive Sponsor, and receive coordinated updates. They inform decisions but do not automatically own product, technical, or release approval unless explicitly assigned that authority.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Teams may combine roles or use different titles; make ownership, approval authority, and handoffs explicit when adapting these definitions.
