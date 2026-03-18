# TraceRank Prototype

TraceRank is a public proof-of-method prototype for activation diagnostics in B2B SaaS onboarding flows.

It demonstrates how session event logs can be translated into structured diagnostic outputs such as a Collapse Map, Activation Trace, Ranked Fix List, KPI Dictionary, and Event Taxonomy using synthetic specimen data.

## What this prototype is

This prototype is a public-safe proof-of-method demonstration.

It is designed to show how staged onboarding event data can be converted into diagnostic outputs across flows such as signup, verification, workspace creation, import/setup, and first value.

## What this prototype is not

This prototype is not:

- a production analytics platform
- a session replay tool
- an LLM observability stack
- evidence of client deployments or production integrations
- a substitute for the live commercial TraceRank offer

## Positioning relationship

- Ava Davis Studio LLC = company behind TraceRank
- TraceRank = productized activation diagnostic for B2B SaaS onboarding flows
- Founding Audit = current commercial offer
- This prototype = public proof-of-method demonstration using synthetic specimen data

## Bridge to the live product

This prototype is a public proof-of-method surface. The paid commercial TraceRank offer is the structured buy → intake → CSV upload → audit delivery flow at app.gettracerank.com.

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
3. Review the Collapse Map, Activation Trace, Ranked Fix List, KPI Dictionary, and Event Taxonomy.
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

## Public links

- Live demo: https://avadavisstudio.github.io/tracerank-prototype/
- Live product: https://app.gettracerank.com
- Repository: https://github.com/avadavisstudio/tracerank-prototype/

## Author

Ava Davis  
Ava Davis Studio LLC