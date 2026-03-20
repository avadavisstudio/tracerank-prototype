# TraceRank Prototype

TraceRank Prototype is a public proof-of-method demonstration for activation diagnostics in B2B SaaS onboarding flows. It shows how staged synthetic event data can be translated into audit-style outputs such as a Collapse Map, Activation Trace, Ranked Fix List, Measurement OS, and Event Taxonomy.

This prototype is not the paid commercial TraceRank flow. The live commercial flow is buy → intake → CSV upload → audit delivery at app.gettracerank.com.

## What this prototype is

This prototype is a public proof-of-method surface.

It is designed to show how staged onboarding event data can be converted into diagnostic outputs across flows such as signup, verification, workspace creation, import/setup, and first value.

## What this prototype is not

This prototype is not:

- the paid commercial TraceRank product
- a production analytics platform
- a session replay tool
- evidence of client deployments or production integrations
- a substitute for the live commercial TraceRank offer

## Positioning relationship

- Ava Davis Studio LLC = company behind TraceRank
- TraceRank = focused activation diagnostic for B2B SaaS onboarding and first-value flows
- Founding Audit = current commercial offer
- This prototype = public proof-of-method demonstration using synthetic specimen data

## Bridge to the live product

This prototype is a public proof-of-method surface. The paid commercial TraceRank offer is the structured buy → intake → CSV upload → audit delivery flow at app.gettracerank.com.

Prototype input is JSON. Commercial TraceRank input is CSV with user_id, session_id, event_name, stage, and occurred_at.

## Public-safe data note

This prototype uses synthetic specimen data only.

It contains:

- no client data
- no production exports
- no implied customer results
- no implied production deployment

## How to use it

1. Open the live demo or serve the repo locally.
2. Use the auto-loaded specimen dataset or upload a JSON file matching the sample schema.
3. Review the Collapse Map, Activation Trace, Ranked Fix List, Measurement OS, and Event Taxonomy.
4. Export the analysis report.

## Core method

TraceRank applies:

- heuristic stage mapping from event sequences into activation stages
- weighted friction scoring across volatility, drift, and abandonment
- evidence-session surfacing for manual review and prioritization

## Current limitations

- static browser-based prototype
- no persistent storage or authentication
- no live data integrations
- no replay capture
- heuristic scoring only; not benchmarked or production-validated

## Why this matters

Most teams can see drop-off. Fewer can explain exactly where onboarding deteriorates before first value and which intervention should be prioritized first.

TraceRank is an attempt to package that diagnosis more usefully than surface-level analytics alone.

## Public proof

Live product: https://app.gettracerank.com
Prototype demo: https://avadavisstudio.github.io/tracerank-prototype/
Company site: https://avadavisstudio.com

The live product is the primary commercial surface.
The prototype is public proof-of-method using synthetic specimen data.
The company site is the company-verification layer behind TraceRank.

## Author

Ava Davis  
Ava Davis Studio LLC