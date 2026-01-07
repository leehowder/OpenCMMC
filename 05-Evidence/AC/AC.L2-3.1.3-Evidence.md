# Evidence – AC.L2-3.1.3
## Control the Flow of Controlled Unclassified Information (CUI)

---

## What You Are Proving

You are proving that CUI is only allowed to exist and move inside approved
systems and that it cannot be sent to systems or locations that are not
authorized.

---

## How to Collect Evidence for This Control

### 1. Identify the Systems Allowed to Handle CUI

Confirm which systems are approved to store, process, or transmit CUI.

**How to check:**
- Open the System Security Plan (SSP)
- Locate the section that lists in-scope systems
- Confirm that these systems are the only ones used for CUI

If a system is not listed as in scope, CUI should not be on it.

---

### 2. Confirm How CUI Is Allowed to Move

Confirm how CUI moves between approved systems during normal work.

**How to check:**
- Identify where CUI is created (for example: email, file storage, applications)
- Identify where CUI is sent or shared
- Confirm that CUI only moves between systems listed as in scope in the SSP

You should be able to explain, in plain language, how CUI flows and where it does not go.

---

### 3. Verify That CUI Cannot Be Sent Outside Approved Systems

Confirm that technical settings prevent CUI from being shared externally.

**How to check in Microsoft GCC High:**
- Review file sharing settings for SharePoint, OneDrive, and Teams
- Confirm external sharing is disabled or restricted
- Confirm users cannot send CUI to personal email or cloud storage

**How to check in Google Workspace:**
- Review Drive sharing settings
- Confirm external sharing is restricted or disabled
- Confirm users cannot share files containing CUI outside the organization

If users can freely share files externally, this control is not met.

---

### 4. Confirm Users Know Where CUI Is Allowed

Confirm users are expected to keep CUI inside approved systems.

**How to check:**
- Review written guidance or policy that explains where CUI may be stored or shared
- Confirm users are instructed not to move CUI to unauthorized systems
- Confirm users understand which systems are approved for CUI

Users should not have to guess where CUI is allowed to go.

---

## Where This Evidence Comes From

Evidence for this control comes from:
- The SSP system boundary definition
- Application and sharing configuration settings
- Organizational rules governing CUI handling

This evidence is retained according to organizational policy and is available
during assessment.
