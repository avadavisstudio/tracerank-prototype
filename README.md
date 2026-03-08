# TraceRank Prototype

Local-first behavior forensics prototype that analyzes session event logs and generates diagnostic artifacts for workflow-heavy SaaS and AI journeys.

**Live demo:** https://avadavisstudio.github.io/tracerank-prototype/  
**Repository:** https://github.com/avadavisstudio/tracerank-prototype

## What it does

TraceRank turns session event logs into decision-grade diagnostic outputs for workflow-heavy SaaS and AI products.

Instead of showing surface-level analytics only, it helps identify where journeys begin to fail through:
- hesitation
- loops
- drift
- trust loss
- abandonment

It generates public-safe specimen outputs such as:
- Collapse Map
- Activation Trace
- Ranked Fix List
- Measurement Plan / KPI Dictionary
- Event Taxonomy

## Why it exists

Most teams can see drop-off. Fewer can explain exactly where the workflow starts collapsing and why.

TraceRank is a state-first prototype built to make failure patterns visible earlier by translating raw event sequences into diagnostic artifacts that are easier to review, prioritize, and present.

## Public-safe note

This prototype uses **synthetic specimen data only**.

It contains:
- no client data
- no production exports
- no implied customer results
- no implied production deployment

## Quick start

### Option 1: Use the live demo

Open the public demo in your browser:

https://avadavisstudio.github.io/tracerank-prototype/

### Option 2: Run locally

From the repo root, serve the static files locally:

`python3 -m http.server 4173`

Then open:

`http://localhost:4173`

## Demo flow

1. Open the prototype
2. Click **Load specimen dataset** to analyze the built-in synthetic example
3. Or click **Upload your own JSON** and choose a file that matches the sample schema
4. Review the session inspector and generated outputs
5. Click **Export analysis report** to download the structured report

## Expected JSON shape

```json
{
  "sessions": [
    {
      "sessionId": "s_001",
      "userId": "u_001",
      "company": "Acme",
      "events": [
        { "ts": "2026-03-07T12:00:00Z", "type": "page_view_landing" }
      ]
    }
  ]
}
