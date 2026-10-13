# Cloud Security Architecture & Compliance

## Overview
I conducted a shared responsibility and compliance analysis for a healthcare cloud environment. The focus was on encryption, access control, monitoring, and network security, with alignment to HIPAA requirements.

## Key Findings
- Cloud provider secures infrastructure and offers encryption services.
- Organization must manage keys, enforce MFA, and review access.
- Gaps identified in backup encryption, centralized key management, MFA, and vulnerability assessments.

## Recommendations
- Implement **MFA** for all accounts.
- Encrypt all backups containing PHI.
- Centralize **key management** across environments.
- Conduct **regular access reviews** and automated account deactivation.
- Deploy **SIEM** for centralized logging and monitoring.
- Upgrade outdated firewalls and perform vulnerability assessments.
- Update and test disaster recovery plans.

## Conclusion
Addressing these gaps strengthens security posture, protects PHI, and enhances HIPAA compliance in hybrid cloud environments.
