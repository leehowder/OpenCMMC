# AC.L2-3.1.10 – Use Session Lock with Pattern-Hiding Displays

## Control Intent
Use session lock with pattern-hiding displays after a period of inactivity.

---

## Control Response

The organization configures systems within the CMMC enclave to automatically
lock user sessions after a defined period of inactivity.

When sessions are locked, system displays hide all information and require
re-authentication to regain access. This prevents unauthorized viewing of
information if a device is left unattended.

Session lock settings are enforced through endpoint and system security
configurations on devices accessing CUI.

---

## Objective Responses

### AC.10.015 – Sessions lock and hide information after inactivity
Systems automatically lock inactive sessions and require re-authentication,
preventing unauthorized access to displayed information.

---

## Evidence References

Evidence includes endpoint security configurations and system behavior
demonstrating automatic session locking.

---

## Continuous Monitoring

Session lock settings are reviewed periodically to ensure inactivity timeouts
remain enforced.

---

## Common Findings

- Session lock disabled
- Excessively long inactivity timeout
