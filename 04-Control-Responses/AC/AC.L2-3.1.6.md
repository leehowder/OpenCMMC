# AC.L2-3.1.6 – Use Non-Privileged Accounts or Roles for Non-Administrative Functions

## Control Intent
Use non-privileged accounts or roles when accessing non-security functions.

---

## Control Response

The organization requires users to perform routine operational activities using non-privileged accounts or roles within the CMMC enclave. Privileged accounts are reserved exclusively for administrative or security-related functions and are not used for daily business operations.

Each user who requires administrative capabilities is issued separate accounts for privileged and non-privileged activities. Standard user accounts are used for normal system access, application usage, and handling of Controlled Unclassified Information (CUI). Privileged accounts are used only when administrative actions are necessary and are accessed for the minimum duration required.

Technical controls are implemented to prevent standard user accounts from performing administrative functions and to restrict privileged account usage to authorized administrative tasks. Users are trained on the proper use of privileged versus non-privileged accounts and are prohibited from bypassing these requirements.

Where technical or operational constraints exist, the organization documents the limitation and implements compensating controls such as enhanced logging, monitoring, and management review of privileged activities.

---

## Objective Responses

### AC.6.010 – Non-privileged accounts are used for non-administrative functions
Users perform non-administrative functions using standard, non-privileged accounts, and privileged accounts are restricted to administrative activities.

---

## Evidence References

Evidence supporting this control includes account inventories showing separate privileged and non-privileged accounts, system configuration settings restricting administrative privileges, authentication logs, and user training records.

---

## Continuous Monitoring

Privileged account usage is reviewed at least quarterly and upon personnel or role changes to ensure continued compliance with non-privileged account usage requirements.

---

## Common Findings

- Privileged accounts used for routine user activities
- Lack of separate administrative and standard user accounts
- Inadequate monitoring of privileged account usage
