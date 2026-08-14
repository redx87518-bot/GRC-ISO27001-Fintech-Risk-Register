# ISO 27001:2022 Risk Register - Nigerian Fintech Case Study

![ISO27001](https://img.shields.io/badge/Framework-ISO27001:2022-blue) ![Status](https://img.shields.io/badge/Status-Completed-green)

## Overview

This project demonstrates the development of a practical risk register aligned to ISO 27001:2022 for a Nigerian fintech organization handling customer payments and sensitive financial information. It applies a structured risk assessment approach to identify common cybersecurity and information-security risks and map them to relevant Annex A controls.

## Objective

Demonstrate practical GRC skills in:
- Risk assessment and scoring
- ISO 27001:2022 control mapping
- Risk treatment planning
- Security governance documentation

## Framework

The project uses **ISO 27001:2022 Annex A controls** as the primary information-security control framework for identifying appropriate safeguards and treatment actions.

## Contents

The accompanying Excel workbook contains three sheets:

1. **Risk Register** — Documents 10 realistic fintech risks, affected assets, threats, vulnerabilities, likelihood, impact, calculated risk score, mapped ISO 27001:2022 controls, treatment decisions, owners, target dates, and residual risk.
2. **Control Mapping** — Maps each identified risk to an applicable Annex A control and provides implementation guidance.
3. **Treatment Plan** — Converts identified risks into actionable remediation tasks with assigned owners, status, and due dates.

## Key Risks Covered

- Phishing leading to credential theft
- Third-party API data breach
- SIM swap fraud
- Insider data exfiltration
- Ransomware on file server
- DDoS on payment gateway
- Misconfigured S3 bucket
- Unpatched VPN
- Weak password policy
- No MFA on admin console

## Methodology

Risk scores are calculated using a **5x5 risk matrix**, where:

**Risk Score = Likelihood × Impact**

Both likelihood and impact are rated from **1 to 5**. Higher scores indicate greater inherent risk and help prioritize treatment.

Controls were selected by considering the nature of each threat, the affected asset, the identified vulnerability, and the applicability of relevant **ISO 27001:2022 Annex A** controls. Treatment options include mitigation, acceptance, transfer, and avoidance.

## Tools Used

- Microsoft Excel / OpenPyXL
- ISO 27001:2022
- ISO 27001:2022 Annex A
- 5x5 Risk Matrix
- GRC risk assessment methodology

## Key Learnings

- Risk registers provide a structured way to connect business assets, threats, vulnerabilities, controls, and remediation decisions.
- Effective GRC requires translating technical cybersecurity risks into measurable business risks and actionable treatment plans.
- ISO 27001:2022 control mapping helps organizations establish consistent security measures and demonstrate governance over information-security risks.

## Author

**Buhari Abdulgafar**  
Aspiring GRC/SOC Analyst  
Cisco & ISO 27001 Certified  
manl2443@zohomail.com
