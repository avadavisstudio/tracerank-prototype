# TraceRank Prototype

TraceRank is a browser-based prototype that turns session event logs into audit-style activation diagnostics for workflow-heavy SaaS and AI flows.

It uses synthetic specimen data or uploaded JSON event data to surface:
- where users stall
- which stage absorbs the most friction
- which fixes should be prioritized first

Outputs in the prototype:
- Collapse Map
- Activation Trace
- Ranked Fix List
- Measurement Plan / KPI Dictionary
- Event Taxonomy
- Exportable analysis report

**Live demo:** https://avadavisstudio.github.io/tracerank-prototype/  
**Repository:** https://github.com/avadavisstudio/tracerank-prototype

## What this is
A public-safe method demo showing heuristic stage mapping and weighted friction scoring across signup, verification, workspace creation, import/setup, and first output.

## What this is not
- not a production analytics platform
- not a session replay tool
- not an LLM observability stack
- not evidence of customer deployments or production integrations

## Public-safe data note
This prototype uses synthetic specimen data only.

It contains:
- no client data
- no production exports
- no implied customer results
- no implied production deployment

## How to use it
1. Open the live demo or serve the repo locally with `python3 -m http.server 4173`
2. Use the auto-loaded specimen dataset or upload a JSON file matching the sample schema
3. Review the Collapse Map, Activation Trace, Ranked Fix List, KPI Dictionary, and Event Taxonomy
4. Export the analysis report

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

## Screens
![Dashboard](screenshots/dashboard.png)
![Collapse Map](screenshots/collapse-map.png)
![Activation Trace](screenshots/activation-trace.png)
![Ranked Fix List](screenshots/ranked-fix-list.png)
![Measurement Plan](screenshots/measurement-plan.png)

## Why this matters
Most teams can see drop-off. Fewer can explain exactly where the activation flow starts breaking and what should be fixed first.

TraceRank is an attempt to package that diagnosis more usefully than surface-level analytics alone.

## Author
Ava Davis  
Ava Davis Studio LLC
