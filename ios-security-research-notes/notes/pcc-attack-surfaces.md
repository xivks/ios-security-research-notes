# PCC — Attack Surfaces & Threat Models

## Overview
Private Cloud Compute (PCC) introduces off-device compute and attestation. This note outlines likely threat surfaces to review.

## Potential targets
- Serialization/deserialization of off-device inputs
- Attestation/identity verification flaws
- Misconfigured access control between on-device and cloud components
- Data-in-transit / integrity checks failures

## Test ideas
- Fuzz any client-server API that consumes serialized data
- Test attestation tokens for replay / tampering
- Evaluate edge cases in data deserialization (large arrays, nested objects)
