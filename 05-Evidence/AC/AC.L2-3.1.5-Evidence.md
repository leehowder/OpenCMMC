# Evidence – AC.L2-3.1.5
## Employ the Principle of Least Privilege

---

## What This Evidence Shows

This evidence shows that users, roles, and system accounts only have the
minimum access needed to do their jobs and do not have extra or unnecessary
permissions.

This supports AC.L2-3.1.5 (Least Privilege) in the System Security Plan (SSP).

---

## How Least Privilege Is Demonstrated

### 1. Users Only Have Access They Need

Users are assigned access based on their job role. They are not given
permissions “just in case” or because it is convenient.

**Examples of how this is shown:**

- In **Microsoft GCC High**, looking at a user in Entra ID shows that:
  - The user does not have admin roles unless their job requires it
  - The user is only a member of groups needed for their work

- In **Google Workspace**, looking at a user shows that:
  - The user does not have Admin roles
  - The user only has access to the services they actually use

If a user does not need access to something, they are not given access.

---

### 2. Administrative Permissions Are Limited

Administrative permissions are only given to users whose job requires them.

**Examples of how this is shown:**

- In **Microsoft GCC High**, directory roles (such as Global Administrator or
  other admin roles) are assigned to only a small number of users.
- In **Google Workspace**, Admin roles are assigned only to designated
  administrators, not regular users.

Most users have **no administrative permissions at all**.

---

### 3. Permissions Match Job Responsibilities

Access permissions match what a person actually does for work.

**Examples of how this is shown:**

- IT administrators have access needed to manage systems
- Regular users have access needed to perform their daily work
- Security or compliance staff have access needed for oversight functions

No user has broad or “all access” permissions unless their role truly requires it.

---

### 4. Access Is Reviewed and Cleaned Up

Permissions are reviewed periodically and when someone’s job changes.

**Examples of how this is shown:**

- When an employee changes roles, access they no longer need is removed
- When an employee leaves, their access is removed
- Periodic reviews confirm users still need the access they have

This prevents users from slowly accumulating more access than necessary.

---

## Where This Evidence Exists

This evidence exists in the organization’s identity and access management system
(such as Microsoft Entra ID or Google Workspace Admin Console) and supporting
access review records.

Evidence is retained according to organizational policy and is available for
assessment.
