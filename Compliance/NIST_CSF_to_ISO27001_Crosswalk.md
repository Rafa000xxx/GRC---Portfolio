# Compliance Mapping: NIST CSF 2.0 vs. ISO/IEC 27001:2022

**Objective:** To provide a unified control framework for the organization, ensuring that technical security operations satisfy both US Federal standards (NIST) and International standards (ISO).



## Identity & Access Management (IAM)
| NIST CSF 2.0 ID | Function | NIST Category | ISO 27001:2022 Control | Implementation Note |
| :--- | :--- | :--- | :--- | :--- |
| **PR.AC-1** | Protect | Identities are managed and authenticated. | **A.5.16** (Identity Management) | Enforce unique IDs and lifecycle management. |
| **PR.AC-3** | Protect | Access is granted based on Least Privilege. | **A.5.18** (Access Rights) | Quarterly access reviews of the offshore team. |
| **PR.AC-4** | Protect | Network access is managed (Remote Access). | **A.8.22** (Network Security) | VPN/ZTNA with mandatory Phishing-Resistant MFA. |

## Data Security & Privacy
| NIST CSF 2.0 ID | Function | NIST Category | ISO 27001:2022 Control | Implementation Note |
| :--- | :--- | :--- | :--- | :--- |
| **PR.DS-1** | Protect | Data at rest is protected. | **A.8.24** (Information Encryption) | AES-256 encryption on all managed laptops. |
| **PR.DS-2** | Protect | Data in transit is protected. | **A.8.24** (Information Encryption) | TLS 1.3 enforced for all web-facing traffic. |
| **PR.DS-10** | Protect | Log integrity is maintained. | **A.8.15** (Logging) | Logs forwarded to immutable SIEM storage. |

## Incident Management
| NIST CSF 2.0 ID | Function | NIST Category | ISO 27001:2022 Control | Implementation Note |
| :--- | :--- | :--- | :--- | :--- |
| **RS.MA-1** | Respond | Incident response plan is executed. | **A.5.24** (Incid. Mgmt. Planning) | Annual tabletop exercises with offshore leads. |
| **RC.RP-1** | Recover | Recovery plan is implemented. | **A.5.30** (ICT Readiness for BC) | Disaster Recovery (DR) testing performed bi-annually. |

---

### 💡 Analyst Insight for Management
"As a veteran of IT Operations, I recognize that 'Control Drift' often occurs when technical teams focus on one framework while neglecting the other. This mapping ensures that our offshore 1st-line support processes satisfy global audit requirements without doubling the administrative workload."
