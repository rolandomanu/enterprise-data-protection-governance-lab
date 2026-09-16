# 🛡️ Enterprise Data Protection & Governance Lab

![Microsoft Purview](https://img.shields.shields.io/badge/Microsoft_Purview-DLP_&_Information_Protection-blue)
![Forcepoint DLP](https://img.shields.shields.io/badge/Forcepoint-Endpoint_DLP-red)
![Compliance](https://img.shields.shields.io/badge/Compliance-ISO_27001_%7C_NIST_CSF-green)

## Executive Summary

This hands-on laboratory environment simulates an enterprise-grade Data Loss Prevention (DLP) and Data Governance program. It demonstrates how to integrate **Microsoft Purview**, **Forcepoint DLP**, and **Microsoft Entra ID** to enforce data classification, insider threat mitigation, control assurance, and continuous compliance monitoring across hybrid environments.

The architecture is strictly aligned with **ISO/IEC 27001 (A.8.12 Data Leakage Prevention)** and **NIST CSF 2.0 (PR.DS Data Security)**.

---

## 📂 Repository Structure

* **`01_Data_Classification`**: Sensitivity labels, SIT definitions & auto-labeling rules
* **`02_DLP_Policies`**: Endpoint, cloud & exchange DLP policy configurations
* **`03_Insider_Risk_Scenarios`**: Exfiltration vector detection & user risk triggers
* **`04_Risk_Register`**: Risk scoring, impact analysis & mitigation controls
* **`05_Governance_Dashboard`**: Incident tracking, KPI reporting & audit logs
* **`06_Compliance_Mapping`**: Control mapping against ISO 27001 & NIST CSF
* **`07_Audit_Evidence`**: Remediation tracking, log collection & control assurance
* **`08_Executive_Reports`**: Risk trend analysis & executive security summaries
* **`09_Microsoft_Purview_Learning_Journey`**: Badges, cert labs & hands-on Purview skills tracking

---

## 🏗️ Core Governance & Technical Capabilities

### 1. Data Classification & Information Protection (`01_Data_Classification`)
* Automated sensitivity labeling (`Confidential`, `Restricted - PII/PCI`, `Public`).
* Custom Sensitive Information Types (SITs) using regular expressions (Regex) and keyword dictionaries.

### 2. DLP Policy Enforcement (`02_DLP_Policies`)
* Multi-channel DLP rules preventing unauthorized USB transfers, personal web uploads, and external email forwarding.
* Integration between Microsoft Purview DLP and Forcepoint Endpoint DLP.

### 3. Insider Threat Mitigation (`03_Insider_Risk_Scenarios`)
* Detection logic for anomalous data download activity and exfiltration attempts during employee offboarding windows.

### 4. Compliance & Control Assurance (`04_Risk_Register`, `06_Compliance_Mapping` & `07_Audit_Evidence`)
* Full traceability matrix connecting technical DLP rules directly to ISO 27001 Annex A controls and NIST CSF subcategories.
* Remediation tracking logs and audit evidence documentation.

### 5. Executive Visibility & Skills Tracking (`05_Governance_Dashboard`, `08_Executive_Reports` & `09_Purview_Journey`)
* High-level reporting metrics, risk trend analyses, and documented Microsoft Purview technical competencies.

---

## 🛠️ Tech Stack & Standards

* **Platforms:** Microsoft Purview (DLP, Information Protection, Insider Risk), Forcepoint DLP, Microsoft Entra ID (RBAC)
* **Frameworks:** ISO/IEC 27001:2022, NIST CSF 2.0
