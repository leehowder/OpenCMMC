# AC.L2-3.1.8 – Limit Unsuccessful Logon Attempts

## Control Intent
Limit the number of unsuccessful logon attempts.

---

## Control Response

The organization implements authentication protections to limit unsuccessful
logon attempts for user accounts accessing the CMMC enclave.

Authentication systems are configured to detect repeated failed logon attempts
and apply protective measures such as throttling, temporary lockout, or
additional verification requirements. These protections reduce the risk of
brute-force and credential-stuffing attacks.

Authentication protections are enforced through centralized identity and
authentication services.

---

## Objective Responses

### AC.8.013 – Unsuccessful logon attempts are limited
Authentication systems enforce limits or protections on repeated unsuccessful
logon attempts.

---

## Evidence References

Evidence includes identity provider authentication protection settings and
security configurations enforcing logon attempt limits.

---

## Continuous Monitoring

Authentication protection settings are reviewed periodically to ensure they
remain enabled and effective.

---

## Common Findings

- No limits on failed logon attempts
- Protections applied inconsistently
