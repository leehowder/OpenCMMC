# System Security Plan (SSP)
## CMMC Level 2 – Open CMMC Template

---

## 1. System Identification

### 1.1 Organization Information
- Organization Name:
- Address:
- Point of Contact:
- Title:
- Email:
- Phone:

### 1.2 System Name
- System Name:
- System Acronym:
- System Owner:
- Information System Security Officer (ISSO):

### 1.3 CMMC Level
- CMMC Level: Level 2
- Assessment Type: C3PAO / Self-Assessment (as applicable)

---

## 2. System Description

The system is a defined CMMC Level 2 enclave used to store, process, and transmit Controlled Unclassified Information (CUI) in support of government contracts.

The system is intentionally scoped to reduce exposure, limit access, and ensure consistent implementation of security controls aligned with NIST SP 800-171 Rev. 2.

---

## 3. CUI Description and Handling

### 3.1 CUI Categories
- CUI Categories Handled:
- Governing Authority (Contract / Program):

### 3.2 CUI Handling
CUI is handled only within the defined enclave. Unauthorized storage, processing, or transmission of CUI outside the enclave is prohibited.

---

## 4. System Boundary Definition

### 4.1 In-Scope Components
The following components are within the CMMC assessment boundary:
- Managed endpoints authorized for CUI access
- Identity and access management services
- CUI storage and collaboration services
- Security monitoring and logging components

### 4.2 Out-of-Scope Components
The following components are explicitly out of scope:
- Personal devices
- Non-managed systems
- Corporate IT systems not authorized for CUI
- Consumer cloud services

### 4.3 Boundary Rationale
The boundary is defined to:
- Minimize assessment scope
- Reduce attack surface
- Support clear evidence collection
- Enable consistent control implementation

Supporting diagrams are maintained separately.

---

## 5. System Environment

### 5.1 System Architecture
- Deployment Model: Cloud / Hybrid / Endpoint-Centric
- Operating Systems:
- Hosting Environment:

### 5.2 Interconnections
All interconnections involving CUI are:
- Authorized
- Documented
- Monitored

Unauthorized data flows are not permitted.

---

## 6. Roles and Responsibilities

| Role | Responsibilities |
|----|----|
| Executive Leadership | Program authority and oversight |
| System Owner | System operations and security |
| ISSO | Compliance oversight and evidence |
| Control Owners | Control execution |
| Users | Policy compliance |

---

## 7. Policies and Procedures

The organization maintains written policies and procedures addressing all CMMC Level 2 control families. Policies are reviewed annually and upon significant change.

Policy templates are maintained separately.

---

## 8. Risk Management

### 8.1 Risk Assessment
Risk assessments are performed periodically and upon system changes.

### 8.2 Risk Treatment
Identified risks are mitigated, accepted, transferred, or avoided based on impact and likelihood.

---

## 9. Control Implementation Summary

This system implements all applicable CMMC Level 2 controls derived from NIST SP 800-171 Rev. 2.

Detailed control responses and objective mappings are maintained in the Open CMMC Control Response Library.

---

## 10. Control-by-Control Responses

### 10.1 Applicability
All 110 CMMC Level 2 controls and 320 associated assessment objectives apply unless explicitly noted.

### 10.2 Control Response Methodology
- Each control is addressed using standardized response templates
- Each objective includes:
  - Implementation description
  - Evidence examples
  - Review frequency

Detailed responses are provided as controlled attachments to this SSP.

---

## 11. Plan of Action and Milestones (POA&M)

Identified gaps are documented in a POA&M.

Each POA&M entry includes:
- Description
- Root cause
- Risk impact
- Corrective action
- Target completion date

---

## 12. Continuous Monitoring

### 12.1 Monitoring Approach
Continuous monitoring is implemented through:
- Periodic evidence review
- Control owner attestations
- Change tracking
- Incident logging

Monitoring activities are tracked using task management or GRC tooling.

---

## 13. Incident Response

The organization maintains an incident response capability to detect, respond to, and recover from security incidents.

Incident response procedures are documented separately.

---

## 14. Training and Awareness

All users complete security awareness training prior to accessing CUI and at least annually thereafter.

Training completion is documented.

---

## 15. Media Protection and Sanitization

Media containing CUI is protected, controlled, and sanitized in accordance with NIST SP 800-88.

Media sanitization activities are logged and retained.

---

## 16. Assumptions and Constraints

### 16.1 Assumptions
- All users access the system using managed devices
- Internet connectivity is external to the boundary
- Cloud providers are treated as part of the enclave when authorized

### 16.2 Constraints
- Budget and resource limitations
- Contractual requirements
- Technology dependencies

---

## 17. Review and Approval

This SSP is reviewed:
- At least annually
- Upon significant system change
- Prior to assessment

### Approval

System Owner: _______________________  
ISSO: ______________________________  
Date: ______________________________
