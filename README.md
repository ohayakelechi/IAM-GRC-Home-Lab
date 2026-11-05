# IAM & GRC Security Home Lab

## Project Overview

This project focuses on Identity and Access Management (IAM) and Governance, Risk, and Compliance (GRC).

I created a simulated company environment to practice reviewing employee access, identifying security risks, and recommending improvements to access controls.

The goal was to understand how organizations manage user permissions, enforce least privilege, and evaluate security risks.

## Tools & Frameworks

- Google Sheets
- CSV files
- NIST SP 800-53
- Role-Based Access Control (RBAC)
- GitHub

## Project Objectives

- Review employee access permissions.
- Identify unauthorized or excessive privileges.
- Apply RBAC and least-privilege principles.
- Conduct a security risk assessment.
- Map security findings to NIST controls.
- Document findings and recommended remediation.

## Phase 1: IAM & GRC Security Audit

I created a fictional company with 10 employee accounts across IT, HR, Finance, and Sales.

I developed an RBAC access matrix to determine which resources employees should be authorized to access.

After comparing simulated employee permissions against the approved matrix, I identified three security findings.

### Audit Results

| Metric | Result |
|---|---|
| Accounts Reviewed | 10 |
| Passed | 7 |
| Failed | 3 |
| Access Review Pass Rate | 70% |

### Security Findings

**1. Excessive Administrative Privileges — High Risk**

An IT Support employee had more administrative permissions than required for their role.

**2. Unauthorized Financial Access — High Risk**

A Sales Representative had access to financial information outside their job responsibilities.

**3. Incomplete Employee Offboarding — Medium Risk**

A former employee's disabled account still had Sales CRM permissions assigned.

### Risk Assessment

I evaluated the findings using a simulated 5x5 likelihood and impact risk matrix.

| Risk | Score | Level |
|---|---|---|
| Excessive Administrative Privileges | 20 | High |
| Unauthorized Financial Access | 15 | High |
| Incomplete Employee Offboarding | 12 | Medium |

### NIST Security Controls

I mapped the findings to relevant NIST SP 800-53 controls:

- **AC-2:** Account Management
- **AC-3:** Access Enforcement
- **AC-6:** Least Privilege
- **IA-2:** Identification and Authentication (not assessed)

### Recommended Remediation

I developed a remediation plan recommending the removal of unauthorized access, reduction of excessive privileges, and cleanup of permissions assigned to terminated employees.

The findings remain open because the proposed changes have not been implemented or verified.

## Project Files

| File or Folder | Description |
|---|---|
| Employee-directory.csv | Fictional employee directory |
| Access-Matrix.csv | Approved RBAC permissions |
| iam-access-audit.csv | Simulated employee access review |
| risk-register.csv | Risk scores and mitigation strategies |
| nist-control-mapping.csv | Security findings mapped to NIST controls |
| Reports/ | Security audit report and documentation |
| Policies/ | Access control policy, if uploaded |
| Evidence/ | Supporting screenshots, if uploaded |

## Phase 2: Microsoft Entra ID

**Status: Planned**

The next phase will focus on hands-on identity administration using Microsoft Entra ID.

Planned activities include:

- Creating test user accounts.
- Configuring security groups.
- Managing group memberships.
- Reviewing and modifying access assignments.
- Disabling test accounts during employee offboarding.
- Verifying and documenting access changes.

This section will be updated once the hands-on implementation is completed.

## Key Takeaways

This project helped me strengthen my understanding of IAM and GRC through simulated access reviews, risk assessments, and security documentation.

I gained experience identifying access control weaknesses, applying least-privilege principles, and mapping findings to recognized security controls.

---

**Disclaimer:** Phase 1 uses fictional employee information and simulated access assignments. No production systems or real employee accounts were audited.
