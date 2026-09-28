# Project 11: High-Risk AI Deployer Governance and FRIA

> **Portfolio disclaimer:** This project uses fictional organizations, systems, events, findings, and evidence. It demonstrates governance methodology only. It is not legal advice, accreditation, certification, or a formal conformity assessment. Confirm requirements against the current official EU AI Act text, applicable annexes, harmonised standards, guidance, contracts, and competent legal advice.


## Articles covered

EU AI Act Articles 26 and 27.

## Project objective

Create a deployer operating model for human oversight, input data, monitoring, logging, notification, contestability, and fundamental-rights assessment.

## Business scenario

A fictional European bank deploys TalentMatch AI for recruitment and a separate credit-assessment AI. The bank must show that approved use, human oversight, data quality, monitoring, evidence, worker information, complaints, and rights impacts are actively managed.

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

1. Map deployer obligations to owners, controls and evidence.
2. Define meaningful human oversight, competence, override and pause authority.
3. Assess input-data relevance, accuracy, representativeness, lineage and correction.
4. Complete a Fundamental Rights Impact Assessment before deployment.
5. Create complaint, contestability and human-review routes.
6. Monitor outcomes, complaints, overrides, incidents and changes.

## Risk register

| ID | Risk statement | Inherent rating | Primary treatment |
|---|---|---|---|
| DEP-01 | Users treat the recommendation as a final decision | Critical | Mandatory human review and automation-bias training |
| DEP-02 | Input data is incomplete or unrepresentative | High | Input quality checks and correction route |
| DEP-03 | SaaS logs are not under deployer control | High | Contractual export and controlled retention copy |
| DEP-04 | Affected people cannot challenge outcomes | High | Contestability and complaint process |
| DEP-05 | FRIA is not updated after material change | High | Change-triggered reassessment |

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

- `01-Deployer-Obligations-Register.md`
- `02-Human-Oversight-Plan.md`
- `03-Input-Data-Checklist.md`
- `04-Fundamental-Rights-Impact-Assessment.md`
- `05-Contestability-Procedure.md`
- `06-Deployer-Monitoring-Plan.md`

## Portfolio statement

Developed a detailed high-risk ai deployer governance and fria project for a fictional high-risk AI environment, translating EU AI Act Articles 26 and 27 into governance roles, controls, procedures, evidence, testing and management decisions.

## Core references

- Regulation (EU) 2024/1689, official text: https://eur-lex.europa.eu/eli/reg/2024/1689/oj
- European Commission, AI regulatory framework: https://digital-strategy.ec.europa.eu/en/policies/regulatory-framework-ai
- European Commission, AI Office: https://digital-strategy.ec.europa.eu/en/policies/ai-office
- NIST AI Risk Management Framework: https://www.nist.gov/itl/ai-risk-management-framework
- ISO/IEC 42001 overview: https://www.iso.org/standard/81230.html
- ISO 31000 overview: https://www.iso.org/iso-31000-risk-management.html
- ISO/IEC 27001 overview: https://www.iso.org/standard/27001

Use the official legal text as the controlling source. ISO standards are copyrighted and should be accessed through ISO or an authorized provider.

