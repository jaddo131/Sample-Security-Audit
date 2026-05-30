# 🛡️ Botium Toys Security Audit

## 📋 Project Overview

This project documents a cybersecurity audit performed for **Botium Toys**, a fictional retail company. The assessment evaluates the organization's security controls, regulatory compliance posture, and overall risk exposure based on the provided audit scope and risk assessment.

The objective of this audit was to identify security gaps, assess compliance requirements, and recommend improvements to strengthen the organization's security posture.

---

## 🎯 Audit Scope

The audit reviewed the following assets and systems:

* Employee workstations, laptops, and mobile devices
* Internal network infrastructure
* Internet connectivity
* Data storage and retention systems
* Accounting, telecommunications, and database systems
* Security systems and ecommerce platforms
* Inventory management systems
* Warehouse and storefront assets
* Legacy systems requiring ongoing maintenance

---

## 🔍 Security Controls Assessment

| Control                          | Status                   |
| -------------------------------- | ------------------------ |
| Least Privilege                  | ❌ Not Implemented        |
| Disaster Recovery Plan           | ❌ Not Implemented        |
| Password Policy                  | ⚠️ Weak Implementation   |
| Separation of Duties             | ❌ Not Implemented        |
| Firewall                         | ✅ Implemented            |
| Intrusion Detection System (IDS) | ❌ Not Implemented        |
| Backups                          | ❌ Not Implemented        |
| Antivirus Software               | ✅ Implemented            |
| Legacy System Monitoring         | ⚠️ Partially Implemented |
| Encryption                       | ❌ Not Implemented        |
| Password Management System       | ❌ Not Implemented        |
| Physical Locks                   | ✅ Implemented            |
| CCTV Surveillance                | ✅ Implemented            |
| Fire Detection/Prevention        | ✅ Implemented            |

---

## 📑 Compliance Assessment

### PCI DSS

| Requirement                               | Status |
| ----------------------------------------- | ------ |
| Restricted Access to Cardholder Data      | ❌      |
| Secure Credit Card Processing Environment | ❌      |
| Encryption of Cardholder Data             | ❌      |
| Secure Password Management                | ❌      |

**Key Findings**

* Cardholder data is accessible by all employees.
* No encryption protects customer payment information.
* Password management controls are insufficient.

---

### GDPR

| Requirement                         | Status |
| ----------------------------------- | ------ |
| Customer Data Privacy Protection    | ❌      |
| 72-Hour Breach Notification Process | ✅      |
| Data Classification & Inventory     | ❌      |
| Privacy Policy Enforcement          | ✅      |

**Key Findings**

* GDPR notification procedures are documented.
* Data privacy protections require improvement.
* Data inventory and classification processes are missing.

---

### SOC 1 / SOC 2

| Requirement                       | Status |
| --------------------------------- | ------ |
| User Access Policies              | ❌      |
| Confidentiality of Sensitive Data | ❌      |
| Data Integrity Controls           | ✅      |
| Data Availability Controls        | ✅      |

**Key Findings**

* Integrity and availability controls are established.
* Access management controls are insufficient.
* Sensitive customer information lacks adequate protection.

---

## ⚠️ Risk Assessment

### High-Risk Findings

* No encryption for customer payment data
* Lack of least-privilege access controls
* No separation of duties
* Missing IDS solution
* No disaster recovery plan
* No backup strategy
* Weak password requirements
* No centralized password management

### Medium-Risk Findings

* Incomplete asset inventory
* Undefined legacy system maintenance procedures
* Lack of data classification controls

---

## 🛠️ Recommendations

### Priority 1 – Critical

* Implement encryption for customer and payment data
* Deploy role-based access control (RBAC)
* Enforce least-privilege principles
* Implement separation of duties
* Deploy an IDS/IPS solution

### Priority 2 – High

* Create and test disaster recovery procedures
* Implement automated backups
* Deploy centralized password management
* Strengthen password complexity requirements

### Priority 3 – Medium

* Establish asset inventory management
* Develop a formal data classification policy
* Create documented legacy system maintenance procedures

---

## 📈 Security Posture Summary

| Category              | Assessment          |
| --------------------- | ------------------- |
| Physical Security     | Strong              |
| Network Security      | Moderate            |
| Access Control        | Weak                |
| Data Protection       | Weak                |
| Incident Detection    | Weak                |
| Disaster Recovery     | Weak                |
| Regulatory Compliance | Partially Compliant |

### Overall Risk Rating: 🔴 HIGH

Botium Toys demonstrates adequate physical security controls and basic network protections; however, significant deficiencies exist in access management, data protection, monitoring, and disaster recovery capabilities. Immediate remediation of critical security gaps is recommended to reduce regulatory and operational risk.

---

## 🧠 Skills Demonstrated

* Risk Assessment
* Security Auditing
* Compliance Analysis
* PCI DSS
* GDPR
* SOC Controls
* Access Control Review
* Vulnerability Identification
* Security Recommendations
* Technical Documentation
