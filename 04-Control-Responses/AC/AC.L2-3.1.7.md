# AC.L2-3.1.7 – Prevent Non-Privileged Users from Executing Privileged Functions

## Control Intent
Prevent non-privileged users from executing privileged functions.

---

## Control Response

The organization enforces technical controls to prevent non-privileged users
from executing privileged or administrative functions within the CMMC enclave.

Privileged functions such as system configuration changes, security management,
and administrative actions are restricted to authorized privileged roles and
accounts. Standard user accounts do not have permissions to perform privileged
operations.

Access control mechanisms are implemented through centralized identity and
access management systems to ensure privileged functions require authorized
administrative roles. Attempts by non-privileged users to access administrative
interfaces or execute privileged actions are denied by system configuration.

---

## Objective Responses

### AC.7.012 – Non-privileged users are prevented from executing privileged functions
Privileged system functions are restricted to authorized administrative roles,
and standard user accounts are technically prevented from performing such actions.

---

## Evidence References

Evidence includes identity provider role assignments and system configurations
demonstrating enforcement of privilege restrictions.

---

## Continuous Monitoring

Privileged role assignments are reviewed at least quarterly and upon personnel
changes to ensure continued enforcement.

---

## Common Findings

- Standard users assigned administrative roles
- Administrative functions accessible without privileged credentials
