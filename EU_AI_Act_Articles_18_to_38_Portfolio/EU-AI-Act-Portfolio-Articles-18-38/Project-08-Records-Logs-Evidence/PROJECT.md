# Project 08: AI Records, Logs and Regulatory Evidence Management

> **Portfolio disclaimer:** This project uses fictional organizations, systems, events, findings, and evidence. It demonstrates governance methodology only. It is not legal advice, accreditation, certification, or a formal conformity assessment. Confirm requirements against the current official EU AI Act text, applicable annexes, harmonised standards, guidance, contracts, and competent legal advice.


## Articles covered

EU AI Act Articles 18, 19 and 21.

## Project objective

Create a controlled evidence-management programme that ensures required documentation and operational logs are retained, protected, accessible, and capable of supporting regulatory cooperation.

## Business scenario

Meridian has completed development of TalentMatch AI, but evidence is fragmented across engineering repositories, cloud logging, ticketing, legal folders, and the quality system. Log retention varies by platform, ownership is unclear, and management cannot demonstrate that every required record can be retrieved promptly.

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

1. Inventory every evidence artifact and assign a unique evidence ID.
2. Separate Article 18 documentation records from Article 19 operational logs.
3. Define retention rules, triggers, legal holds, secure disposal, and exceptions.
4. Map provider, deployer, and vendor control over logs.
5. Define minimum logging events and prohibited logging practices.
6. Test evidence retrieval through a simulated competent-authority request.

## Risk register

| ID | Risk statement | Inherent rating | Primary treatment |
|---|---|---|---|
| EVID-01 | Technical documentation is deleted or overwritten before the retention requirement ends | High | Controlled repository, immutable versions, ownership and retention rule |
| EVID-02 | SaaS logs expire before they can support an investigation | High | Contractual retention/export requirement and deployer copy |
| EVID-03 | Logs contain unnecessary personal data | High | Logging minimization, privacy review and access restriction |
| EVID-04 | Evidence cannot be located during a regulatory request | High | Master index, retrieval testing and response coordinator |
| EVID-05 | Provider and deployer assume the other party owns retention | High | Responsibility matrix and contract schedule |

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

- `01-Evidence-Inventory.md`
- `02-Retention-Schedule.md`
- `03-Logging-Standard.md`
- `04-Log-Ownership-Matrix.md`
- `05-Regulatory-Response-Procedure.md`
- `06-Evidence-Retrieval-Test.md`

## Portfolio statement

Developed a detailed ai records, logs and regulatory evidence management project for a fictional high-risk AI environment, translating EU AI Act Articles 18, 19 and 21 into governance roles, controls, procedures, evidence, testing and management decisions.

## Core references

- Regulation (EU) 2024/1689, official text: https://eur-lex.europa.eu/eli/reg/2024/1689/oj
- European Commission, AI regulatory framework: https://digital-strategy.ec.europa.eu/en/policies/regulatory-framework-ai
- European Commission, AI Office: https://digital-strategy.ec.europa.eu/en/policies/ai-office
- NIST AI Risk Management Framework: https://www.nist.gov/itl/ai-risk-management-framework
- ISO/IEC 42001 overview: https://www.iso.org/standard/81230.html
- ISO 31000 overview: https://www.iso.org/iso-31000-risk-management.html
- ISO/IEC 27001 overview: https://www.iso.org/standard/27001

Use the official legal text as the controlling source. ISO standards are copyrighted and should be accessed through ISO or an authorized provider.

