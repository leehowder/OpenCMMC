# Evidence Standards – Open CMMC

## Purpose

This document defines the evidence standards used throughout the Open CMMC framework.
It exists to eliminate ambiguity, reduce assessor interpretation, and ensure
organizations collect sufficient and repeatable evidence for CMMC Level 2.

CMMC does not prescribe specific tools.
However, assessors require clear proof that controls are implemented and operating.

---

## Evidence Design Principles

All evidence must:

- Demonstrate **actual implementation**, not intent
- Be **verifiable** and **repeatable**
- Include **date/time context**
- Align directly to the applicable control and objective
- Be understandable without oral explanation

---

## Evidence Types

Acceptable evidence types include:

- System screenshots
- Logs and records
- Configuration exports
- Reports from security tools
- Completed forms or logs
- Policy references **paired with technical proof**

Policies alone are never sufficient.

---

## Screenshot Standards

All screenshots must show:

- System or tenant context (where feasible)
- The control setting or state being demonstrated
- Date and time (system clock, log timestamp, or filename)
- No sensitive data beyond what is required

Redaction is permitted but must not obscure relevance.

---

## Naming Convention

Recommended filename format:
[ControlID]-[EvidenceType]-[System]-YYYY-MM-DD.ext



### Example
---

## Platform-Specific Evidence Examples

Open CMMC provides **illustrative examples** using common platforms such as:

- Microsoft Entra ID / Intune
- Google Workspace / Endpoint Management
- Linux / Windows native tools
- Common MDM and IdP platforms

These examples are **not endorsements** and do not exclude other valid solutions.

---

## Evidence Anti-Patterns (Explicitly Not Acceptable)

- Verbal explanations without artifacts
- Policies without technical corroboration
- Screenshots without date/time context
- Screenshots that hide the relevant control state
- “Trust me” statements

---

## Evidence Retention

Evidence should be retained in accordance with organizational policy
and contractual requirements.

Evidence must be available for assessment upon request.

---

## Assessor Perspective

Assessors evaluate evidence based on:
- Sufficiency
- Specificity
- Traceability
- Consistency with SSP narratives

This standard is designed to meet those expectations.

