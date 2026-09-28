# Root-Cause Analysis: Recruitment Recommendation Disparity

## Problem statement

Candidates with non-traditional career histories receive materially fewer recommendations for selected roles.

## Evidence reviewed

- Feature list and data dictionary
- Training and validation datasets
- Extraction errors
- Outcome analysis
- Recruiter overrides and complaints
- Release and configuration history

## Root causes

1. Career-gap duration was used without adequate job-related justification.
2. Validation data underrepresented career-returning candidates.
3. Monitoring focused on overall accuracy and not subgroup outcome differences.

## Corrective actions

- Remove or redesign the feature.
- Rebuild representative validation data.
- Review affected applications.
- Add threshold-based subgroup monitoring.
- Repeat independent validation before restart.
