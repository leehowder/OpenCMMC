# Evidence – AC.L2-3.1.11
## Terminate Sessions After Defined Conditions

---

## Control Overview

This document describes the evidence used to demonstrate implementation of
AC.L2-3.1.11, which requires user sessions to be terminated after defined
conditions such as inactivity.

This evidence supports the control response documented in the System Security Plan (SSP).

---

## Evidence Objectives

Evidence for this control demonstrates that:

- User sessions do not remain active indefinitely
- Session timeout conditions are explicitly defined
- Re-authentication is required after session termination

---

## Evidence Artifacts

### 1. Session Timeout Enforcement

Evidence demonstrating session termination may include:

- Defined inactivity timeout values for user sessions
- Configuration preventing unlimited or persistent login sessions
- Enforcement of re-authentication after session termination

Examples of acceptable sources:

- Microsoft Entra ID Conditional Access session controls
- Microsoft Intune device lock or session timeout policies
- Google Workspace Admin Console session duration settings

---

## Evidence Retention

Evidence supporting this control is retained in accordance with organizational
policy and contractual requirements and is available for review during assessment.

---

## Notes

Session termination must occur automatically based on defined conditions and
must require re-authentication to regain access.
