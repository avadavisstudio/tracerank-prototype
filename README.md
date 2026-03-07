# TraceRank Prototype

TraceRank is a public-safe behavior forensics **prototype/method demonstration** for workflow-heavy SaaS and AI journeys.

It ingests **synthetic specimen data** (synthetic event logs) and generates decision-grade diagnostic outputs:
- Collapse Map
- Activation Trace
- Ranked Fix List
- Measurement Plan / KPI Dictionary
- Event Taxonomy

**Live demo:** https://avadavisstudio.github.io/tracerank-prototype/  
**Repository:** https://github.com/avadavisstudio/tracerank-prototype

## Screens

![Dashboard](screenshots/dashboard.png)
![Collapse Map](screenshots/collapse-map.png)
![Activation Trace](screenshots/activation-trace.png)
![Ranked Fix List](screenshots/ranked-fix-list.png)
![Measurement Plan](screenshots/measurement-plan.png)

## Public-safe data note

This prototype uses **synthetic specimen data** for demonstration only.  
It contains **no client data**, no production exports, and **no implied production deployment** or customer outcomes.


## Why I built this

Most product teams can track clicks, page views, and drop-off rates, but they still cannot clearly see where users begin to hesitate, loop, lose trust, drift from the intended path, or abandon the journey entirely.

I built this prototype to test a state-first diagnostic model that turns event streams into audit-style outputs instead of surface-level analytics.

## Core scoring model

TraceRank scores three primary forms of collapse:

- **Volatility**: unstable behavior, repeated toggling, erratic sequence movement, hesitation loops
- **Drift**: movement away from the intended activation path, low-commitment actions, sequence decay
- **Abandonment**: stalled or exited journeys before meaningful completion

These signals are combined into a higher-level collapse severity view so the system can rank where intervention matters most.

## Current prototype capabilities

- Upload and analyze a JSON event log
- View per-session diagnostic patterns
- Surface collapse stages and root symptoms
- Rank issues by severity
- Export a structured analysis report
- Demonstrate public-safe specimen outputs for audit presentation

## Data note

This prototype uses **synthetic specimen event data** for demonstration only.

It does **not** contain client data, production data, or implied customer results.

## Why this matters

User failure is rarely random.

Breakdown usually comes from:
- sequence friction
- unclear next steps
- hidden requirements
- trust instability
- weak handoff logic
- incomplete measurement

TraceRank is designed to make those failures visible earlier.

## Roadmap

Next iterations:
- CSV ingestion
- saved audits
- richer visual exports
- multi-project analysis
- stronger weighting controls
- deck-ready specimen output

## Author

Ava Davis  
Ava Davis Studio LLC  
State-First Architecture Lab
