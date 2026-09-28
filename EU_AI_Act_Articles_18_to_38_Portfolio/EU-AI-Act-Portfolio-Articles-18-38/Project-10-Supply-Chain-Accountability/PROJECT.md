# Project 10: EU AI Act Supply-Chain Accountability

> **Portfolio disclaimer:** This project uses fictional organizations, systems, events, findings, and evidence. It demonstrates governance methodology only. It is not legal advice, accreditation, certification, or a formal conformity assessment. Confirm requirements against the current official EU AI Act text, applicable annexes, harmonised standards, guidance, contracts, and competent legal advice.


## Articles covered

EU AI Act Articles 22, 23, 24 and 25.

## Project objective

Map accountability across the AI value chain and establish verification, contractual, modification, incident, withdrawal, and cooperation controls.

## Business scenario

Meridian is established outside the EU and supplies TalentMatch AI through an EU authorized representative, importer, distributors, cloud provider, model supplier, data vendors, and testing subcontractors. Management needs to prevent gaps and identify when another actor becomes the provider.

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

1. Map each legal and contractual actor in the AI value chain.
2. Create an obligations matrix covering documentation, records, incidents and authorities.
3. Draft the authorized representative mandate and termination triggers.
4. Perform importer and distributor verification before market activity.
5. Assess rebranding, substantial modification, and intended-purpose changes under Article 25.
6. Translate obligations into contracts, audit rights, change notice and exit requirements.

## Risk register

| ID | Risk statement | Inherent rating | Primary treatment |
|---|---|---|---|
| SC-01 | No party clearly owns regulatory records | High | Obligations matrix and written mandate |
| SC-02 | Distributor modifies scoring but remains treated as a reseller | Critical | Article 25 role-shift assessment |
| SC-03 | Importer relies only on provider assurances | High | Independent verification checklist |
| SC-04 | Supplier change occurs without provider notice | High | Material-change notification clause |
| SC-05 | Recall communications fail across the value chain | High | Contact tree and coordinated withdrawal procedure |

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

- `01-Value-Chain-Map.md`
- `02-Actor-Obligations-Matrix.md`
- `03-Authorized-Representative-Mandate.md`
- `04-Importer-Distributor-Checklists.md`
- `05-Article25-Role-Shift-Assessment.md`
- `06-Contract-Requirements.md`

## Portfolio statement

Developed a detailed eu ai act supply-chain accountability project for a fictional high-risk AI environment, translating EU AI Act Articles 22, 23, 24 and 25 into governance roles, controls, procedures, evidence, testing and management decisions.

## Core references

- Regulation (EU) 2024/1689, official text: https://eur-lex.europa.eu/eli/reg/2024/1689/oj
- European Commission, AI regulatory framework: https://digital-strategy.ec.europa.eu/en/policies/regulatory-framework-ai
- European Commission, AI Office: https://digital-strategy.ec.europa.eu/en/policies/ai-office
- NIST AI Risk Management Framework: https://www.nist.gov/itl/ai-risk-management-framework
- ISO/IEC 42001 overview: https://www.iso.org/standard/81230.html
- ISO 31000 overview: https://www.iso.org/iso-31000-risk-management.html
- ISO/IEC 27001 overview: https://www.iso.org/standard/27001

Use the official legal text as the controlling source. ISO standards are copyrighted and should be accessed through ISO or an authorized provider.

