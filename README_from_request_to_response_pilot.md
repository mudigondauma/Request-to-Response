# From Request to Response — Pilot Prototype

This bundle contains a single-file working prototype for the **Agentic Solutioning System for Enterprise Deal Shaping** pilot.

## Files
- `from-request-to-response-pilot-prototype.html` — clickable prototype
- `README_from_request_to_response_pilot.md` — quick usage guide

## What the prototype demonstrates
This is a thin-slice pilot, not a production system. It shows:
- pilot request intake
- governed response-pack generation
- Green / Amber / Red human review routing
- audit-style run log
- pilot KPI cockpit
- target architecture and pilot controls

## How to use it
1. Open `from-request-to-response-pilot-prototype.html` in any modern browser.
2. In the Intake view, click one of the synthetic example cases.
3. Click **Generate governed response pack**.
4. Move through the tabs in this order:
   - Response workbench
   - Human review
   - KPI cockpit
   - Architecture & controls

## Recommended live demo path
Use the **Managed network transformation RFP** example.
It gives the strongest “real pilot” narrative because it shows:
- a material shaping use case
- approved pattern retrieval
- an Amber review route
- executive brief generation
- clear measurement logic for scale

## Important limits
- No live LLM calls
- No live enterprise systems
- No customer data
- No CRM write-back
- No autonomous external send

The prototype uses embedded synthetic data and deterministic logic to make the operating model visible and safe to share.
