# Lockdown Mode — Testing Methodology

## Goal
Identify components where Lockdown Mode is expected to limit behavior and test for coverage gaps or bypasses.

## Areas to test
- External interface restrictions (USB, wired interfaces)
- Message parsing (iMessage attachments, MMS)
- WebKit hardening and feature gates
- Developer tool access and debug interfaces

## Approach
- Enumerate permitted vs blocked APIs
- Create minimal inputs that exercise edge-case parsers
- Document reproducible steps without disclosing exploit payloads
