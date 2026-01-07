# Evidence – AC.L2-3.1.6
## Use Non-Privileged Accounts or Roles for Non-Security Functions

---

## Evidence Statement

Evidence for AC.L2-3.1.6 demonstrates that users access systems and perform
non-security-related functions using non-privileged accounts or non-privileged
roles, even when those users are authorized to perform administrative or
security functions under separate conditions.

This evidence supports the control response documented in the System Security Plan (SSP).

---

## Evidence Description

Evidence demonstrates that routine user activities are performed in a
non-privileged access context. When users access email, files, applications,
or other systems that process, store, or transmit Controlled Unclassified
Information (CUI), they do so without administrative or security privileges
active.

Where separate accounts are used, evidence demonstrates that users authenticate
with a standard, non-privileged account for routine operations and switch to a
privileged account only when performing authorized administrative or security
functions.

Where role-based access control is used, evidence demonstrates that users
operate in a non-privileged role for routine activities and explicitly assume
a privileged role only when administrative or security functions are required.
Role changes provide an equivalent reduction in access privileges as switching
between privileged and non-privileged accounts.

Evidence further demonstrates that administrative or security privileges are
not persistently active during normal system use and that elevated access is
limited to the duration and context necessary to perform privileged functions.

---

## Evidence Availability

Evidence supporting this control is available through identity and access
management configurations showing default non-privileged access contexts,
account or role separation, and the absence of administrative privileges during
routine user activity, and is retained in accordance with organizational policy
and contractual requirements.

