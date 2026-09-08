# Operational Human Oversight Framework v0.1

## Working Research Framework

**Author:** Lei Gao  
**Research area:** AI Governance, Human Oversight, Agentic AI Governance  
**Status:** Research-in-progress / Working Framework v0.1

---

## 1. Purpose

This working framework explores how Human Oversight can be translated from a general governance principle into an operational control structure for increasingly autonomous and agentic AI systems.

The framework focuses on a practical governance question:

> When should automated operation continue, when should a human intervene, who should have authority to intervene, what actions should be permitted, and what evidence should be preserved?

The objective is to develop a reusable structure for Human Oversight across different AI deployment contexts.

---

## 2. Core Governance Logic

The current operational sequence is:

**AI / Trust Event  
→ Intervention Trigger  
→ Escalation Level  
→ Human Authority  
→ Permitted Human Action  
→ Evidence / Logging Requirement  
→ Return-to-Operation Condition**

Each stage addresses a different governance requirement.

---

## 3. AI / Trust Event

The process begins with an event or condition that may require additional oversight.

Examples may include:

- abnormal system behaviour
- uncertainty above an accepted threshold
- trust degradation
- conflicting instructions or policies
- ambiguous delegation
- unexpected model behaviour
- high-impact decisions
- safety concerns
- rights-related risks
- accountability uncertainty

Not every event requires human intervention.

The governance challenge is to determine which events should trigger additional oversight and at what level.

---

## 4. Intervention Trigger

An intervention trigger defines the condition under which automated operation should no longer continue without additional review.

Potential trigger categories include:

### Risk Trigger
The potential impact of a decision exceeds an accepted risk threshold.

### Uncertainty Trigger
The system lacks sufficient confidence, context, authority, or information.

### Behavioural Trigger
Observed AI or agent behaviour deviates from expected or authorized behaviour.

### Policy Trigger
An action conflicts with legal, organizational, contractual, ethical, or operational requirements.

### Authority Trigger
The AI system reaches the boundary of its delegated authority.

### Trust Trigger
Trust indicators deteriorate below an acceptable level.

---

## 5. Escalation Level

Human Oversight should not necessarily operate as a binary choice between full automation and full manual control.

A risk-proportionate escalation structure may include:

### Level 0 — Automated Continuation

The system continues operation within authorized and monitored boundaries.

### Level 1 — Human Notification

A human is informed, but automated operation may continue.

### Level 2 — Human Review

A qualified human reviews the situation before further action.

### Level 3 — Human Authorization

The AI system cannot proceed without explicit human approval.

### Level 4 — Temporary Hold / Suspension

Automated operation is paused pending investigation or intervention.

### Level 5 — Human Override / Termination

An authorized human overrides, reverses, or terminates the automated action or process.

---

## 6. Human Authority

Meaningful Human Oversight requires clearly defined authority.

A human reviewer should not merely be present.

The governance structure should specify:

- who is authorized to intervene
- what qualifications are required
- what information must be available
- what decisions the human may make
- whether the human may override the AI system
- whether the human may suspend or terminate operation
- who is accountable for the intervention decision

Authority should be proportionate to the risk and impact of the AI system.

---

## 7. Permitted Human Actions

Depending on the escalation level, authorized human actions may include:

- acknowledge
- request additional information
- continue automated operation
- modify system parameters
- require additional review
- approve
- reject
- pause
- suspend
- override
- rollback
- terminate
- resume operation

These actions should be explicitly defined rather than assumed.

---

## 8. Evidence and Logging Requirements

Human Oversight should generate a traceable governance record.

Relevant evidence may include:

- event that triggered intervention
- system state
- confidence or uncertainty information
- relevant trust indicators
- reason for escalation
- identity and authority of the reviewer
- information presented to the reviewer
- decision made
- action taken
- timestamp
- override or rollback record
- justification
- return-to-operation conditions

This evidence supports:

- auditability
- traceability
- accountability
- incident investigation
- regulatory review
- organizational learning

---

## 9. Return-to-Operation Condition

Human intervention should not end with the intervention decision itself.

The governance framework should define when and how automated operation may resume.

Possible requirements include:

- identified problem resolved
- human authorization obtained
- risk reduced to an acceptable level
- system state validated
- required evidence recorded
- policy conflict resolved
- corrective action completed
- additional monitoring activated

A system should not automatically resume solely because the intervention period has ended.

---

## 10. Bounded Autonomy

The framework treats Human Oversight as part of a broader model of **bounded autonomy**.

Under bounded autonomy:

- AI systems may act autonomously within defined authority boundaries
- higher-risk actions require stronger oversight
- authority boundaries are explicit
- intervention mechanisms are predefined
- escalation pathways are available
- humans retain meaningful control over critical actions
- evidence is preserved throughout the process

The objective is not to eliminate autonomy, but to make autonomy governable.

---

## 11. Operational Control Matrix

A working control matrix may take the following form:

| AI / Trust Event | Intervention Trigger | Escalation Level | Human Authority | Permitted Action | Evidence Requirement | Return-to-Operation Condition |
|---|---|---|---|---|---|---|
| Low-risk anomaly | Monitoring threshold exceeded | Level 1 | Operator | Review / continue | Event log | Normal indicators restored |
| High uncertainty | Confidence below threshold | Level 2 | Qualified reviewer | Review / modify | Decision record | Human validation |
| Policy conflict | Rule conflict detected | Level 3 | Authorized decision-maker | Approve / reject | Policy + decision log | Conflict resolved |
| Critical abnormal behaviour | Safety or trust threshold breached | Level 4 | Supervisor / system owner | Suspend | Full incident record | Risk remediation |
| Unauthorized or harmful action | Authority boundary exceeded | Level 5 | Authorized human controller | Override / rollback / terminate | Full audit trail | Formal reauthorization |

This matrix is illustrative and remains under development.

---

## 12. Application Contexts

The framework is being explored across multiple contexts.

### Agentic AI Trust Systems

Human intervention within agentic AI trust architectures and trust lifecycles.

Related public work:

**ITU-T FG-TIDA Theme #16 — Operational Human Oversight Integration for Agentic AI Trust Systems**

https://github.com/FG-TIDA/themes/issues/16

### Smart Sustainable Cities

Human Oversight in AI-enabled urban systems and public-service environments.

Related work:

**FGAI4SSC-I-015 — ITU-T FG-AI4SSC**

### Multilateral AI Governance

Translation of operational Human Oversight concepts into broader Responsible AI and international digital governance contexts.

Related public contribution:

**UN Digital Cooperation Portal**

https://www.undigitalcooperation.org/organization/details?id=1830

---

## 13. Research Development

Future development may include:

- sector-specific intervention triggers
- risk-proportionate escalation models
- human authority taxonomies
- evidence requirement matrices
- agent permission boundaries
- human-agent delegation models
- incident and rollback governance
- evaluation criteria for meaningful Human Oversight
- mappings to international AI governance frameworks and standards

---

## 14. Status and Scope

This document is a **working research framework (v0.1)**.

It is not:

- an adopted international standard
- an ITU Recommendation
- a certification framework
- legal advice
- a regulatory compliance determination

The framework is intended to support research, discussion, experimentation, and future validation.

---

## Researcher

**Lei Gao**  
AI Governance & Human Oversight Researcher

Visiting Research Fellow  
Centre for Asian and Transcultural Studies (CATS)  
Heidelberg University

LinkedIn:  
https://www.linkedin.com/in/lei-gao-cybernetics

GitHub:  
https://github.com/leigao-research
