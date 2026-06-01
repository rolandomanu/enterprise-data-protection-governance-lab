# Credit Card Detection Rule

## Purpose

Identify and protect payment card information from unauthorized transmission.

## Risk

Exposure of payment card information may lead to fraud, financial loss, and compliance violations.

## Detection Logic

Common Card Patterns:

- Visa
- MasterCard
- American Express

Example Regex:

\b(?:\d[ -]*?){13,16}\b

## Actions

- Generate Alert
- Record Incident
- Escalate for Review

## Severity

High

## Related Controls

- PCI DSS
- DLP Monitoring
- Security Governance
