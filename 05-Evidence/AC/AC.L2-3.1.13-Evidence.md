# Evidence – AC.L2-3.1.13
## Protect CUI Confidentiality During Transmission

---

## Control Overview

This document describes the evidence used to demonstrate implementation of
AC.L2-3.1.13, which requires cryptographic protection of CUI during transmission.

This evidence supports the control response documented in the System Security Plan (SSP).

---

## Evidence Objectives

Evidence for this control demonstrates that:

- CUI is encrypted during transmission
- Secure communication protocols are enforced
- Unencrypted transmission of CUI is not permitted

---

## Evidence Artifacts

### 1. Encryption of Data in Transit

Evidence demonstrating encryption may include:

- Enforcement of HTTPS or TLS for cloud services handling CUI
- Configuration preventing access to services over insecure protocols
- Organizational requirement that CUI is transmitted only over encrypted channels

Examples of acceptable sources:

- Microsoft 365 GCC High service encryption enforcement
- Entra ID application access settings requiring secure transport
- Google Workspace encryption and secure transport settings

---

## Evidence Retention

Evidence supporting this control is retained in accordance with organizational
policy and contractual requirements and is available for review during assessment.

---

## Notes

Encryption must protect the confidentiality of CUI whenever it is transmitted,
including access from remote locations using managed devices.
