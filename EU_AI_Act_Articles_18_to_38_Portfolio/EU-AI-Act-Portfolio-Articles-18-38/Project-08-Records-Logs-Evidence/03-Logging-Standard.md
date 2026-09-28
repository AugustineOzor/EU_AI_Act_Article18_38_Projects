# AI Logging Standard

## Required events

- Authenticated user or service identity
- Date, time and relevant environment
- AI system, model, configuration and version
- Relevant input category and data source identifiers
- Output, recommendation or action identifier
- Human review, override, pause or escalation
- Tool calls and external-system actions
- Error, policy decision and security alert
- Deployment, configuration and model changes

## Safeguards

- Do not log secrets or unnecessary full prompts by default.
- Apply role-based access, integrity protection and access monitoring.
- Synchronize time sources and document clock standards.
- Test retrieval, readability and linkage to incidents.
- Define redaction, export, deletion and legal-hold procedures.
