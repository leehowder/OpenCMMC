# Evidence – AC.L2-3.1.15
## Authorize Remote Execution of Privileged Commands

---

## Control Overview

This document describes the evidence used to demonstrate implementation of
AC.L2-3.1.15, which requires authorization for remote execution of privileged commands.

This evidence supports the control response documented in the System Security Plan (SSP).

---

## Evidence Objectives

Evidence for this control demonstrates that:

- Remote execution of privileged commands is explicitly authorized
- Privileged commands cannot be executed remotely by unauthorized users
- Authorization is enforced by system configuration

---

## Evidence Artifacts

### 1. Authorization for Remote Privileged Actions

Evidence demonstrating authorization may include:

- Configuration requiring administrative roles to perform remote privileged actions
- Restrictions preventing standard users from executing privileged commands remotely
- Explicit enablement of remote administrative capabilities only for authorized roles

Examples of acceptable sources:

- Microsoft Entra ID role assignments governing remote administration
- Microsoft Intune policies restricting remote administrative actions
- Google Workspace Admin roles and device access restrictions

---

## Evidence Retention

Evidence supporting this control is retained in accordance with organizational
policy and contractual requirements and is available for review during assessment.

---

## Notes

Authorization must be enforced prior to allowing remote execution of any
privileged or administrative commands.
