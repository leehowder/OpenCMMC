# AC.L2-3.1.3 – Control the Flow of CUI

## Control Intent
Control the flow of Controlled Unclassified Information (CUI) in accordance with approved authorizations.

---

## Control Response

The organization controls the flow of Controlled Unclassified Information (CUI) within the CMMC enclave to ensure CUI is accessed, processed, stored, and transmitted only through authorized systems, users, and data paths.

The system boundary for CUI is explicitly defined in the System Security Plan (SSP). CUI is permitted to flow only between components identified as in scope within the enclave. Data flows involving CUI are documented and reviewed to ensure they align with contractual and operational requirements.

Technical controls are implemented to restrict unauthorized transfer of CUI. These controls include access restrictions on file sharing, application-level controls that limit external sharing, and configuration settings that prevent CUI from being transmitted to unauthorized destinations.

Users are prohibited from transferring CUI to non-approved systems, personal devices, or consumer cloud services. Procedures governing CUI handling and transmission are communicated to users through policy and training.

Changes to systems, applications, or workflows that may affect the flow of CUI are reviewed prior to implementation to ensure CUI remains confined to authorized data paths.

---

## Objective Responses

### AC.3.006 – Authorized CUI flows are identified
Authorized flows of CUI are identified and documented through system boundary definitions and data flow descriptions maintained as part of the SSP.

### AC.3.007 – Unauthorized CUI flows are prevented
Technical and procedural controls prevent the transfer of CUI to unauthorized systems, users, or destinations outside the defined enclave.

---

## Evidence References

Evidence supporting this control includes documented system boundaries, data flow descriptions, configuration settings restricting external sharing, and user policies governing CUI handling.

---

## Continuous Monitoring

CUI data flows are reviewed upon system changes and periodically to ensure continued compliance with authorized data flow requirements.

---

## Common Findings

- Undefined or undocumented CUI data flows
- Users sharing CUI outside approved systems
- External sharing controls not properly restricted
