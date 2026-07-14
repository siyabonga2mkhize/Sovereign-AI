# POPIA Compliance Documentation

## A Sovereign AI Blueprint for Carbon Footprint Hotspot Detection in KZN Computer Labs

---

**Document Version:** 1.0
**Date:** 13 July 2026
**Project Lead:** Siyabonga Mkhize
**Project Co-Lead:** Meluleki Shandu

---

## 1. Introduction

### 1.1 What is POPIA?

The **Protection of Personal Information Act (POPIA)** (Act No. 4 of 2013) is South Africa's comprehensive data protection legislation. It came into full force and effect on **1 July 2021**. POPIA aims to:

- Give effect to the constitutional right to privacy
- Protect individuals from harm by protecting their personal information
- Regulate the processing of personal information by public and private bodies
- Establish minimum requirements for the processing of personal information

### 1.2 Why POPIA Applies to Our Project

POPIA applies to **"any natural or juristic person who processes personal information"** by automated or non-automated means. As our project collects, stores, and processes personal information (such as student IDs, login times, and consent records) through automated systems, we are a **Responsible Party** under POPIA and must comply with all eight conditions for lawful processing.

---

## 2. The Eight Conditions for Lawful Processing

POPIA sets out **eight conditions** that must be met when processing personal information. Below is how our project complies with each condition.

---

### Condition 1: Accountability

| Requirement | Our Compliance Approach |
|-------------|------------------------|
| The Responsible Party must ensure all conditions for lawful processing are met | We have designated **Siyabonga Mkhize** as the Information Officer responsible for POPIA compliance |
| Document all processing activities | We maintain a detailed **Data Requirements Dictionary** documenting every data field collected |
| Implement compliance measures | We have built POPIA compliance into our system architecture from the design phase |

**Implementation:**

- **Information Officer Appointment:** Siyabonga Mkhize serves as the designated Information Officer, responsible for ensuring compliance with POPIA's lawful processing conditions and handling data subject rights requests
- **Compliance Documentation:** All data processing activities are documented in our Data Requirements Dictionary
- **Regular Audits:** We will conduct quarterly compliance reviews to ensure ongoing adherence to POPIA

---

### Condition 2: Processing Limitation

| Requirement | Our Compliance Approach |
|-------------|------------------------|
| Personal information must be processed lawfully and in a manner that does not infringe privacy | We only process data with **explicit consent** or on the basis of **legitimate interest** |
| Data must be collected for a **specific, explicitly defined, and lawful purpose** | Our purpose is clearly defined: **detect energy waste and reduce carbon footprint** |
| Data must be **adequate, relevant, and not excessive** (Data Minimization) | We collect **only** the minimum data necessary: anonymized student IDs, login/logout times, and consent records |

**Implementation:**

- **Lawful Basis for Processing:** Under Section 11 of POPIA, our processing is justified by:
  1. **Consent** – Students and lab staff provide explicit consent
  2. **Legitimate Interest** – Processing is necessary for the legitimate interests of DUT (energy efficiency and cost savings)
- **Data Minimization:** We do not collect student names, ID numbers, or any identifiable information beyond anonymized session IDs
- **Purpose Limitation Statement:** Personal information is processed **only** for carbon footprint hotspot detection and energy optimization

---

### Condition 3: Purpose Specification

| Requirement | Our Compliance Approach |
|-------------|------------------------|
| Personal information must be collected for a **specific, explicitly defined, and lawful purpose** | Purpose is documented in our consent forms and project scope |
| Data subjects must be informed of the purpose at the time of collection | Clear, simple language (isiZulu and English) in consent forms |
| Information may not be retained for longer than necessary | Retention periods are defined (30-180 days for most data) |

**Implementation:**

- **Purpose Statement:** *"Your anonymized data is being collected to help DUT detect energy waste in computer labs, reduce electricity costs, and lower our carbon footprint. This data will only be used for energy optimization purposes."*
- **Retention Policy:**

| Data Type | Retention Period | Justification |
|-----------|------------------|---------------|
| Telemetry Data | 90 days | Sufficient for trend analysis |
| Session Data (Anonymized) | 30 days | Usage pattern analysis |
| Alert Logs | 180 days | Audit and compliance |
| Consent Logs | 7 years | POPIA legal requirement |
| System Logs | 30 days | Debugging and security |

---

### Condition 4: Further Processing Limitation

| Requirement | Our Compliance Approach |
|-------------|------------------------|
| Further processing must be **compatible with the original purpose** of collection | We only use data for energy optimization |
| Data may not be used for incompatible purposes without new consent | Any new use requires **re-consent** from data subjects |

**Implementation:**

- **Compatibility Check:** Before any new data use is considered, we conduct a compatibility assessment
- **Re-Consent Mechanism:** If we wish to use data for a purpose beyond energy optimization (e.g., research publication), we will obtain **fresh explicit consent**
- **Documentation:** All data processing purposes are documented and tracked

---

### Condition 5: Information Quality

| Requirement | Our Compliance Approach |
|-------------|------------------------|
| Responsible Party must take reasonably practicable steps to ensure data is **complete, accurate, not misleading, and up-to-date** | We implement data validation and quality checks |

**Implementation:**

- **Data Validation:** All telemetry data is validated against expected ranges (e.g., wattage between 0-500W)
- **Correction Mechanism:** Data subjects can request correction of inaccurate data
- **Regular Review:** Data quality is reviewed monthly to identify and correct errors

---

### Condition 6: Openness

| Requirement | Our Compliance Approach |
|-------------|------------------------|
| Data subjects must be aware of **what data is collected and how it is used** | Transparent privacy policies and consent forms |
| Documentation must be maintained on all processing activities | We maintain a complete **Data Requirements Dictionary** |

**Implementation:**

- **Privacy Policy:** A clear, simple privacy policy is available in both English and isiZulu
- **Consent Forms:** Explicit, informed consent is obtained before any data collection begins
- **Transparency Dashboard:** Lab administrators and students can view what data is being collected about them

---

### Condition 7: Security Safeguards

| Requirement | Our Compliance Approach |
|-------------|------------------------|
| Implement appropriate, reasonable technical and organisational measures to prevent **loss, damage, or unlawful access** | Multiple layers of security implemented |
| Security measures must be **appropriate to the risks** | Risk-based approach to security |

**Implementation:**

| Security Measure | Description |
|------------------|-------------|
| **Encryption at Rest** | All data stored on Cloud Africa is encrypted using AES-256 |
| **Encryption in Transit** | All data transmission uses TLS 1.3 |
| **Access Control** | Role-based access control (RBAC) – only authorized lab managers can access data |
| **Authentication** | Multi-factor authentication for admin access |
| **Automated Backups** | Daily encrypted backups stored securely |
| **Audit Logs** | All access to personal information is logged |
| **Data Breach Protocol** | Incident response plan in place, with mandatory reporting to Information Regulator within 72 hours |

---

### Condition 8: Data Subject Participation

| Requirement | Our Compliance Approach |
|-------------|------------------------|
| Data subjects have the right to **access, correct, and delete** their personal information | We implement full data subject rights |
| Requests must be handled **without unreasonable delay and free of charge** | We have automated systems to handle requests |

**Implementation - Data Subject Rights:**

| Right | How We Enable It |
|-------|------------------|
| **Right to Access** | Data subjects can request a copy of all their personal information held by the system |
| **Right to Rectify** | Data subjects can request corrections to inaccurate or incomplete data |
| **Right to Deletion ("Vala/Sula")** | The **"Vala/Sula"** (Close/Delete) command triggers a hard delete of all school data on request |
| **Right to Object** | Data subjects can object to the processing of their personal information |
| **Right to Restrict** | Data subjects can request that processing be restricted |
| **Right to Complain** | Data subjects can lodge a complaint with the Information Regulator |

---

## 3. The "Vala/Sula" Right to Deletion

### 3.1 What is "Vala/Sula"?

"**Vala**" (Close) and "**Sula**" (Delete) are isiZulu terms that represent our implementation of the **Right to Deletion** under POPIA.

While POPIA does not expressly provide for a "right to be forgotten," it does provide for a **"right to delete"** with requirements substantially similar. Section 24 of POPIA allows data subjects to request deletion where information is:

- Inaccurate
- Irrelevant
- Excessive
- Out-of-date
- Incomplete
- Misleading
- Obtained unlawfully

### 3.2 "Vala/Sula" Implementation

```python
# privacy/data_deletion.py
def vala_sula_delete(school_id):
    """
    Permanently deletes ALL data associated with a school
    This implements the Right to Deletion under POPIA Section 24
    """
    # Delete telemetry data
    Telemetry.objects.filter(school_id=school_id).hard_delete()
    
    # Delete user data
    User.objects.filter(school_id=school_id).hard_delete()
    
    # Delete session data
    Session.objects.filter(school_id=school_id).hard_delete()
    
    # Delete carbon footprint data
    CarbonFootprint.objects.filter(school_id=school_id).hard_delete()
    
    # Delete consent logs
    ConsentLog.objects.filter(school_id=school_id).hard_delete()
    
    # Confirm deletion
    return {"status": "DELETED", "school_id": school_id}
```

### 3.3 Data Subject Rights Process

```
┌─────────────────────────────────────────────────────────────────┐
│              DATA SUBJECT RIGHTS REQUEST PROCESS               │
├─────────────────────────────────────────────────────────────────┤
│                                                                 │
│  ┌──────────────┐    ┌──────────────┐    ┌──────────────┐     │
│  │  Data Subject│───▶│  Request     │───▶│  Identity    │     │
│  │  Makes       │    │  Received    │    │  Verified    │     │
│  │  Request     │    │              │    │              │     │
│  └──────────────┘    └──────────────┘    └──────────────┘     │
│         │                    │                    │            │
│         │                    │                    │            │
│         ▼                    ▼                    ▼            │
│  ┌──────────────┐    ┌──────────────┐    ┌──────────────┐     │
│  │  Request     │    │  Action      │    │  Response    │     │
│  │  Assessed    │───▶│  Taken       │───▶│  Provided    │     │
│  │  (Validity)  │    │  (Access/    │    │  (Free of    │     │
│  │              │    │   Correct/   │    │   Charge)    │     │
│  └──────────────┘    │   Delete)    │    └──────────────┘     │
│                      └──────────────┘                         │
│                                                                 │
└─────────────────────────────────────────────────────────────────┘
```

---

## 4. Consent Mechanism

### 4.1 Explicit Consent Requirement

POPIA mandates that personal information must be processed lawfully and transparently, with the data subject's consent forming a key legal basis for such processing. For consent to be valid under POPIA, it must be:

- **Informed** – The data subject understands what they are consenting to
- **Voluntary** – No coercion or pressure
- **Specific** – Consent is for a particular purpose
- **Explicit** – Clear, unambiguous indication of consent

### 4.2 Our Consent Form

**Consent for Data Collection – KZN Carbon AI Project**

*Siyacela ukuthi ufunde lolu lwazi ngaphambi kokuvuma.*

**What we collect:**
- Anonymized student ID (hashed, not your actual ID number)
- Login and logout times
- Computer usage patterns (idle time, active time)
- Consent record

**What we DO NOT collect:**
- Your name
- Your ID number
- Your contact details
- Any sensitive personal information

**How we use your data:**
- To detect energy waste in computer labs
- To reduce DUT's electricity costs
- To lower DUT's carbon footprint
- To improve lab management

**Your rights:**
- You can withdraw consent at any time
- You can request access to your data
- You can request deletion of your data ("Vala/Sula")
- You can lodge a complaint with the Information Regulator

**Consent:**
☐ I have read and understood this information
☐ I consent to the collection and processing of my anonymized data for energy optimization purposes

**Signature:** _________________ **Date:** _______________

---

## 5. Data Sovereignty & Cross-Border Transfers

### 5.1 POPIA's Restriction on Cross-Border Transfers

POPIA **restricts cross-border data sharing** under **Section 72**, which prohibits transferring personal information outside the Republic of South Africa unless certain conditions are met.

### 5.2 Our Compliance Approach

| Requirement | Our Implementation |
|-------------|-------------------|
| Personal information must **not** be transferred outside South Africa without adequate protection | All data is hosted on **Cloud Africa** – South African servers |
| The recipient must provide an **adequate level of protection** | Cloud Africa is POPIA-compliant and operates within South African jurisdiction |
| Data subjects must be informed of cross-border transfers | No cross-border transfers occur |

### 5.3 Why Cloud Africa?

| Feature | Benefit for POPIA Compliance |
|---------|------------------------------|
| **Local hosting on South African soil** | Zero data leakage to foreign jurisdictions |
| **POPIA-compliant infrastructure** | Meets all security safeguard requirements |
| **Managed infrastructure** | Automated patches and security updates |
| **Automated backups** | Data recovery without compromising compliance |
| **Scalability** | Can expand to more schools while maintaining compliance |

---

## 6. Information Officer Appointment

### 6.1 POPIA Requirement

POPIA requires that public and private bodies **register an Information Officer** to ensure compliance with the lawful processing conditions and deal with data subject rights requests.

### 6.2 Our Information Officer

| Role | Name | Responsibilities |
|------|------|------------------|
| **Information Officer** | Siyabonga Mkhize | Overall POPIA compliance, handling data subject requests, reporting breaches |
| **Deputy Information Officer** | Meluleki Shandu | Day-to-day compliance, security implementation, staff training |

### 6.3 Information Officer Duties

- Ensure compliance with all eight POPIA conditions
- Handle data subject rights requests (access, correction, deletion)
- Maintain records of all processing activities
- Report data breaches to the Information Regulator
- Conduct regular compliance audits
- Provide staff training on POPIA requirements

---

## 7. Data Breach Response Plan

### 7.1 What is a Data Breach?

A data breach is any **unauthorized access, disclosure, or loss** of personal information. Under POPIA, data breaches must be reported to the Information Regulator.

### 7.2 Our Response Protocol

| Phase | Action | Responsible Party | Timeline |
|-------|--------|-------------------|----------|
| **Detection** | Identify and confirm the breach | System Monitoring Team | Immediate |
| **Containment** | Isolate affected systems, prevent further breach | Meluleki Shandu | Within 1 hour |
| **Assessment** | Determine scope and impact of breach | Siyabonga Mkhize | Within 4 hours |
| **Notification** | Report to Information Regulator | Siyabonga Mkhize | Within 72 hours |
| **Notification** | Inform affected data subjects | Siyabonga Mkhize | As soon as reasonably possible |
| **Remediation** | Fix vulnerability, implement safeguards | Meluleki Shandu | Within 7 days |
| **Review** | Conduct post-incident review | Both | Within 30 days |

---

## 8. Compliance Checklist

| Condition | Requirement | Status | Evidence |
|-----------|-------------|--------|----------|
| **1. Accountability** | Information Officer appointed | ✅ | Section 6 |
| **2. Processing Limitation** | Lawful basis documented | ✅ | Section 2.2 |
| **3. Purpose Specification** | Purpose documented | ✅ | Section 2.3 |
| **4. Further Processing** | Compatibility assessed | ✅ | Section 2.4 |
| **5. Information Quality** | Data validation in place | ✅ | Section 2.5 |
| **6. Openness** | Privacy policy published | ✅ | Section 2.6 |
| **7. Security Safeguards** | Security measures implemented | ✅ | Section 2.7 |
| **8. Data Subject Participation** | Rights mechanism in place | ✅ | Section 2.8 |
| **Cross-Border Transfer** | Local hosting only | ✅ | Section 5 |
| **Consent** | Explicit consent obtained | ✅ | Section 4 |
| **Data Breach Plan** | Response protocol in place | ✅ | Section 7 |

---

## 9. Ongoing Compliance

### 9.1 Regular Reviews

| Activity | Frequency | Responsible |
|----------|-----------|-------------|
| Compliance audit | Quarterly | Information Officer |
| Security assessment | Monthly | Deputy Information Officer |
| Privacy policy review | Annually | Information Officer |
| Staff training | Bi-annually | Both |
| Data subject rights audit | Annually | Information Officer |

### 9.2 Amendments

POPIA regulations were amended on **17 April 2025**, strengthening data subject rights and imposing stricter compliance obligations. We commit to:

- Monitoring all regulatory updates from the Information Regulator
- Updating our compliance documentation as regulations evolve
- Implementing any new requirements promptly

---

## 10. Conclusion

Our project, **A Sovereign AI Blueprint for Carbon Footprint Hotspot Detection**, is fully committed to POPIA compliance. By:

1. **Hosting all data locally** on Cloud Africa (South African servers)
2. **Obtaining explicit consent** from all data subjects
3. **Implementing the "Vala/Sula" right to deletion**
4. **Appointing a designated Information Officer**
5. **Documenting all processing activities**
6. **Implementing robust security safeguards**

We ensure that personal information is processed lawfully, transparently, and with full respect for the privacy rights of all individuals.

---

## 11. References

1. Protection of Personal Information Act No. 4 of 2013
2. POPIA Section 11 – Lawful grounds for processing
3. POPIA Section 24 – Data subject rights to correction and deletion
4. POPIA Section 72 – Cross-border data transfers
5. Information Regulator of South Africa – Guidance Notes
6. POPIA Regulations (amended 17 April 2025)

---

**Document Approved By:**

| Name | Role | Signature | Date |
|------|------|-----------|------|
| Siyabonga Mkhize | Information Officer | ___________ | 13/07/2026 |
| Meluleki Shandu | Deputy Information Officer | ___________ | 13/07/2026 |

---

**A Sovereign AI Blueprint for Carbon Footprint Hotspot Detection** | **Public Services & Inclusion** | **Siyabonga Mkhize & Meluleki Shandu**