# Project 09: AI Incident, Corrective Action and Regulatory Response

> **Portfolio disclaimer:** This project uses fictional organizations, systems, events, findings, and evidence. It demonstrates governance methodology only. It is not legal advice, accreditation, certification, or a formal conformity assessment. Confirm requirements against the current official EU AI Act text, applicable annexes, harmonised standards, guidance, contracts, and competent legal advice.


## Articles covered

EU AI Act Articles 20 and 21.

## Project objective

Establish an operational process to detect non-compliance, contain risk, investigate root cause, notify relevant parties, implement corrective and preventive action, and authorize safe restart.

## Business scenario

Post-market monitoring shows that TalentMatch AI recommends fewer candidates with non-traditional career histories for interview. The issue could arise from historical data, proxy features, extraction errors, or monitoring gaps. Meridian must respond quickly and preserve evidence.

## Scope

### Included

- TalentMatch AI and directly related provider/deployer processes
- Governance records, decisions, controls and evidence
- Relevant suppliers, representatives, importers, distributors or assessment actors
- Operational and regulatory response processes
- Material changes and lifecycle events

### Excluded

- Formal legal opinions
- Real personal data
- Real regulator submissions
- Formal accreditation or certification
- Claims that a real organization is compliant

## Governance roles

- **Executive sponsor:** approves resources and significant residual risk.
- **Project owner:** maintains the project method and deliverables.
- **Legal/compliance:** reviews regulatory interpretation and escalation.
- **System/business owner:** supplies system facts and operates controls.
- **Data owner:** governs data purpose, quality, lineage, access and retention.
- **Security owner:** owns cybersecurity, logging, access and incident controls.
- **Quality owner:** controls procedures, evidence, CAPA and review.
- **Internal audit/assurance:** independently tests design and operation.

## Detailed activities

1. Define AI incident categories and internal severity levels.
2. Create a Detect-Validate-Contain-Escalate-Investigate-Correct-Notify-Retest-Restart workflow.
3. Define withdrawal, recall, restriction and customer-notification triggers.
4. Perform root-cause analysis across data, model, configuration, people, process and supplier factors.
5. Track CAPA ownership, due dates, verification and closure evidence.
6. Conduct a tabletop exercise and produce lessons learned.

## Risk register

| ID | Risk statement | Inherent rating | Primary treatment |
|---|---|---|---|
| INC-01 | A discriminatory outcome continues while the issue is investigated | Critical | Immediate containment and affected-use suspension |
| INC-02 | Stakeholders receive inconsistent information | High | Approved notification matrix and communications owner |
| INC-03 | A repaired model is restarted without independent validation | High | Retest and formal restart approval |
| INC-04 | Corrective actions close without proving effectiveness | High | Effectiveness review and closure evidence |
| INC-05 | Evidence is lost during incident response | High | Preservation checklist and legal hold |

## Delivery method

### Phase 1: Initiate

- Approve the project charter, scope, roles and evidence standard.
- Confirm system facts, intended purpose, actors, deployment and lifecycle stage.
- Establish naming, versioning, review and approval conventions.

### Phase 2: Discover and assess

- Collect evidence from business, technical, legal, privacy, security and quality owners.
- Test completeness, relevance, accuracy and traceability.
- Record gaps without assuming that missing evidence proves compliance.

### Phase 3: Design controls

- Translate each obligation into a control objective.
- Define a control owner, operator, frequency, evidence and failure response.
- Integrate controls into existing quality, security, risk and change processes where practical.

### Phase 4: Implement and test

- Complete the worked examples in the supporting files.
- Perform document review, sample testing and a tabletop or retrieval exercise.
- Record findings, corrective actions and residual limitations.

### Phase 5: Approve and monitor

- Obtain accountable review and approval.
- Establish scheduled and event-driven review triggers.
- Track evidence currency, overdue actions and control failures.

## Acceptance criteria

- Every obligation has a named owner and evidence source.
- Every artifact is versioned and approved.
- High and critical findings have treatment or deployment restrictions.
- Evidence can be retrieved without relying on personal knowledge.
- Material changes trigger reassessment.
- Portfolio limitations and synthetic data are disclosed.

## Portfolio outcomes

- A complete, auditable project narrative
- Completed example registers and procedures
- Reusable templates
- Article-to-evidence traceability
- Management-level recommendations

## Evidence included

- `01-Incident-Response-Plan.md`
- `02-Incident-Classification-Matrix.md`
- `03-Root-Cause-Analysis.md`
- `04-CAPA-Register.md`
- `05-Notification-Matrix.md`
- `06-Tabletop-Exercise-Report.md`

## Portfolio statement

Developed a detailed ai incident, corrective action and regulatory response project for a fictional high-risk AI environment, translating EU AI Act Articles 20 and 21 into governance roles, controls, procedures, evidence, testing and management decisions.

## Core references

- Regulation (EU) 2024/1689, official text: https://eur-lex.europa.eu/eli/reg/2024/1689/oj
- European Commission, AI regulatory framework: https://digital-strategy.ec.europa.eu/en/policies/regulatory-framework-ai
- European Commission, AI Office: https://digital-strategy.ec.europa.eu/en/policies/ai-office
- NIST AI Risk Management Framework: https://www.nist.gov/itl/ai-risk-management-framework
- ISO/IEC 42001 overview: https://www.iso.org/standard/81230.html
- ISO 31000 overview: https://www.iso.org/iso-31000-risk-management.html
- ISO/IEC 27001 overview: https://www.iso.org/standard/27001

Use the official legal text as the controlling source. ISO standards are copyrighted and should be accessed through ISO or an authorized provider.

