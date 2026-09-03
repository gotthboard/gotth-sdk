# gotth-sdk

Reserved for supported API clients and extension contracts shared by GOTTH
applications and integrators.

## Intended boundary

This project may eventually own generated or deliberately maintained clients,
version negotiation, typed public API models, compatibility fixtures, and
extension contracts. Each server remains authoritative for authentication,
authorization, rate limits, transactions, and product behavior.

Implementation begins only after a public API is stable enough to support a
versioned compatibility promise. Generating clients from a changing internal
API would merely fossilize churn.

## Non-goals

- An internal-domain-model dump or plugin runtime.
- Server authorization, persistence, or business policy.
- Compatibility promises before the public API and deprecation rules exist.

## Status

Placeholder only. There is no implementation, API, release, tag, compatibility
promise, or dependency to pin.
