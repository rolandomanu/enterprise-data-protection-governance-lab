# SSN Detection Rule

## Purpose

Detect and prevent unauthorized transmission of Social Security Numbers (SSNs).

## Risk

Unauthorized disclosure of SSNs may result in identity theft, regulatory violations, and reputational damage.

## Detection Logic

Example Pattern:

XXX-XX-XXXX

Regex Example:

\b\d{3}-\d{2}-\d{4}\b

## Actions

- Alert Security Team
- Log Event
- Notify User
- Block Transmission (High Severity)

## Severity

High

## Related Controls

- Data Loss Prevention (DLP)
- Sensitive Data Protection
- Access Control
