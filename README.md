# Microsoft Entra ID — Employee Offboarding Security Assessment

## Project Overview

This project demonstrates a hands-on Identity and Access Management (IAM) security assessment conducted in a Microsoft Entra ID training environment.

The assessment investigates a simulated employee offboarding failure at a fictional organization, **Harborview Accounting Services**, where a former employee's account remained enabled and retained security group memberships after departure.

The investigation focuses on identifying identity security risks, evaluating account access, performing administrative remediation, reviewing audit evidence, and documenting security findings.

### Key Skills Demonstrated

- Microsoft Entra ID administration
- Identity and Access Management (IAM)
- Employee offboarding security assessments
- User account investigation and access verification
- Security group membership management
- Account disabling and session revocation
- Microsoft Entra ID audit log analysis
- Security risk assessment and remediation documentation

**Environment:** Microsoft Entra ID training tenant

**Scenario:** Fictional employee offboarding security incident

**Purpose:** Hands-on cybersecurity training and professional portfolio demonstration


## Security Investigation Summary

### Identified Security Issue

During a simulated employee offboarding assessment at Harborview Accounting Services, a former employee's Microsoft Entra ID account was found to be enabled after departure.

The account also retained membership in two security groups:

- `SG-Accounting-Staff`
- `SG-Finance-Documents`

These conditions represented an identity security risk because the former employee's account remained active and retained group-based access eligibility.

### Remediation Performed

The following administrative remediation actions were completed:

1. Disabled the former employee's Microsoft Entra ID account.
2. Revoked the account's active sign-in sessions.
3. Removed the account from both identified security groups.
4. Reviewed Microsoft Entra ID audit logs to verify the administrative changes.

### Assessment Outcome

The identified account and group membership risks were remediated and verified through Microsoft Entra ID administrative and audit evidence.

No unauthorized access or data exposure was established during the assessment. The root cause of the offboarding failure was not confirmed, and additional access paths were outside the verified remediation scope.

The assessment demonstrates practical IAM investigation, access remediation, audit verification, and security risk documentation skills.


## Project Evidence and Documentation

The following resources provide supporting evidence and detailed documentation for this IAM security assessment.

### Technical Evidence

[View Microsoft Entra ID Security Screenshots](screenshots/)

Screenshots document the account investigation, administrative remediation, and available audit verification evidence.

### Security Assessment Reports

- [Final Security Assessment Report](reports/IAM-Lab1-Final-Report.txt)
- [Investigation Findings](reports/IAM-Lab1-Findings.txt)
- [Lab Completion Record](reports/IAM-Lab1-Completion.txt)

These documents provide additional details about the assessment scope, identified risks, corrective actions, verification results, and remaining limitations.
