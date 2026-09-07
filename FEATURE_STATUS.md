# Feature status — Aviation, drones & airport operations

| Capability | Status |
| --- | --- |
| Native sidebar and canonical feature registry | Built; 229 pages |
| Shared records, validation, relationships, persistence | Implemented in shared runtime |
| Clickable table rows with centered details popup | Implemented; Edit, Delete, Cancel, keyboard access and mobile layout |
| Domain field forms and source traceability | Imported from static source definitions; historical routes are labeled in mapping |
| CSV exports, attachments, audit and report totals | Implemented |
| At least 15 fictional rows per editable feature | Seeded by startup; measured in reports/seed-verification.json |
| AI question-and-answer workspace | Replaces AI feature tables; questions, context fields, formatted answers, follow-ups and saved history; live provider configuration required |
| Source calculation adapters | Available for explicitly registered calculation variants only |
| Source business-rule and state-machine parity | Incomplete beyond registered adapters and native records; verify each source journey |
| Original account/business data migration | Not performed; source data preserved |
| Provider integrations and external delivery | Not connected; request preparation only |
| Hosted authentication, independent-review roles and tenant isolation | Not migrated; local single-user boundary |

A successful build or populated table is not evidence of full source workflow parity. The source-to-feature map records every extracted definition and route, with explicit exclusions and migration warnings. Test/build reports distinguish checked behavior from remaining work.

| Canonical feature | Native mode | Source entries | Calculators | Status |
| --- | --- | ---: | ---: | --- |
| Clients & customers | records | 3 | 0 | Native records/view |
| Work items & projects | records | 1 | 0 | Native records/view |
| Contacts & parties | records | 1 | 0 | Native records/view |
| Tasks | records | 0 | 0 | Native records/view |
| Calendar | records | 0 | 0 | Native records/view |
| Deadlines & reminders | records | 0 | 0 | Native records/view |
| Notes | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Documents | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Templates | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Invoices & billing | records | 1 | 0 | Native records/view |
| Time tracking | records | 0 | 0 | Native records/view |
| Messages & communications | records | 3 | 0 | Native records/view |
| Reports & analytics | report | 3 | 0 | Native records/view |
| Activity & audit trail | audit | 7 | 0 | Native records/view |
| Provider connections | integration | 1 | 0 | Provider request records only |
| Airline TMC agreement library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Traveler trip registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Ticket exchange ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Coupon status reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Unused ticket detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Residual value calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Refundability validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Tax refund calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Waiver disruption rules | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Credit expiration alerts | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Employee departure handling | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Reuse exchange recommendation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Airline refund workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cash credit reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Airline route analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Component and serial registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Removal and installation events | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Warranty entitlement engine | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Shop finding ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Covered-work validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Repair invoice audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Exchange fee reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Core return and penalty control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Pool agreement reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| No-fault-found analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AOG freight and service recovery | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Airworthiness evidence package | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Vendor claim and response workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Credit and receivable reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Reliability and recovery analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cost Estimator | records | 1 | 0 | Native records/view |
| Predictive Maint. | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Tech Matcher | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Reliability Score | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Tech Workload | records | 1 | 0 | Native records/view |
| Compliance Cal. | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| ETOPS Release | records | 1 | 0 | Native records/view |
| AI History | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Maintenance | records | 4 | 0 | Native records/view |
| Parts Lifecycle | records | 1 | 0 | Native records/view |
| FAA Compliance | records | 2 | 0 | Native records/view |
| Work Orders | records | 2 | 0 | Native records/view |
| Inventory | records | 2 | 0 | Native records/view |
| Safety Incidents | records | 4 | 0 | Native records/view |
| Technicians | records | 1 | 0 | Native records/view |
| Fleet Health | records | 1 | 0 | Native records/view |
| Vendors | records | 1 | 0 | Native records/view |
| Tool Calibration | records | 1 | 0 | Native records/view |
| MEL Tracking | records | 1 | 0 | Native records/view |
| Purchase Orders | records | 1 | 0 | Native records/view |
| Shift Scheduling | records | 1 | 0 | Native records/view |
| Hangars | records | 1 | 0 | Native records/view |
| Training | records | 1 | 0 | Native records/view |
| Warranties | records | 1 | 0 | Native records/view |
| Compliance Directive Analyzer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Part Lifecycle Analyzer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Safety Incident Analyzer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Fleet Optimization | records | 1 | 0 | Native records/view |
| MEL Deferral Analyzer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Technical Document Review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Purchase Order Analyzer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Sensor Anomaly Detector | records | 1 | 0 | Native records/view |
| Shift Coverage Optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Technician Training Path | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cross-Fleet Reallocation Advisor | records | 1 | 0 | Native records/view |
| Passenger Experience | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Revenue Management | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Multi-Agency Coordination | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| ADS-B Live | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| FAA NextGen | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Airline Partners | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Noise Impact | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Emergency Simulation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Gate Assignment Optimization | records | 1 | 0 | Native records/view |
| Ground Crew Scheduling | records | 1 | 0 | Native records/view |
| Delay Prediction & Rebooking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Baggage Flow Tracking | records | 1 | 0 | Native records/view |
| Runway Utilization | records | 1 | 0 | Native records/view |
| Flight Schedule Board | records | 2 | 0 | Native records/view |
| Weather & NOTAMs | records | 2 | 0 | Native records/view |
| Airport Statistics | records | 1 | 0 | Native records/view |
| AI Gate Conflict Predictor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Predictive Maintenance | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Shift Handover Report | records | 1 | 0 | Native records/view |
| NOTAM Briefing | records | 1 | 0 | Native records/view |
| Runway Capacity Simulator | records | 1 | 0 | Native records/view |
| Sustainability Report | records | 1 | 0 | Native records/view |
| Traffic Volume Forecast | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Emergency Response | records | 1 | 0 | Native records/view |
| Fleet Management | records | 4 | 0 | Native records/view |
| Real-Time Tracking | records | 1 | 0 | Native records/view |
| Mission Logs (AI) | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Mission Stream | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Flight Planning | records | 2 | 0 | Native records/view |
| Mission Control | records | 4 | 0 | Native records/view |
| Inspections | records | 1 | 0 | Native records/view |
| Delivery Management | records | 2 | 0 | Native records/view |
| Agriculture Ops | records | 1 | 0 | Native records/view |
| Surveillance | records | 1 | 0 | Native records/view |
| Route Optimization | records | 2 | 0 | Native records/view |
| Anomaly Detection | records | 2 | 0 | Native records/view |
| AI Flight Analysis | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Pilot Management | records | 3 | 0 | Native records/view |
| Battery Management | records | 3 | 0 | Native records/view |
| Checklists | records | 2 | 0 | Native records/view |
| Geofences | records | 1 | 0 | Native records/view |
| Payloads & Sensors | records | 2 | 0 | Native records/view |
| Landing Zones | records | 2 | 0 | Native records/view |
| Training Records | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Insurance | records | 1 | 0 | Native records/view |
| Contracts | records | 1 | 0 | Native records/view |
| Expense Tracking | records | 2 | 0 | Native records/view |
| Shift Management | records | 2 | 0 | Native records/view |
| Emergency Protocols | records | 2 | 0 | Native records/view |
| Communication Logs | records | 2 | 0 | Native records/view |
| Ground Stations | records | 1 | 0 | Native records/view |
| Inspection Services | records | 1 | 0 | Native records/view |
| Agriculture Operations | records | 1 | 0 | Native records/view |
| Surveillance & Security | records | 1 | 0 | Native records/view |
| Maintenance & Repairs | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Weather Intelligence | records | 1 | 0 | Native records/view |
| Compliance & Regulations | records | 1 | 0 | Native records/view |
| Client Management | records | 1 | 0 | Native records/view |
| Billing & Invoicing | records | 1 | 0 | Native records/view |
| Operations Analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Parts Inventory | records | 1 | 0 | Native records/view |
| Incident Reports | records | 2 | 0 | Native records/view |
| Document Center | records | 1 | 0 | Native records/view |
| Geofence Management | records | 1 | 0 | Native records/view |
| Project Management | records | 1 | 0 | Native records/view |
| Insurance Policies | records | 1 | 0 | Native records/view |
| Contract Management | records | 1 | 0 | Native records/view |
| Ground Control Stations | records | 1 | 0 | Native records/view |
| Autonomy | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Security Alerts | records | 1 | 0 | Native records/view |
| Threat Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Travelers | records | 1 | 0 | Native records/view |
| Trips | records | 1 | 0 | Native records/view |
| Destinations | records | 1 | 0 | Native records/view |
| Travel Advisories | records | 1 | 0 | Native records/view |
| Risk Assessments | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Geofencing Zones | records | 2 | 0 | Native records/view |
| SOS Center | records | 1 | 0 | Native records/view |
| Geofence Triggers | records | 1 | 0 | Native records/view |
| Real-Time Threat | records | 1 | 0 | Native records/view |
| Evacuation Planner | records | 1 | 0 | Native records/view |
| Medical Risk | records | 1 | 0 | Native records/view |
| Cyber Security | records | 1 | 0 | Native records/view |
| Itinerary Risk Score | records | 1 | 0 | Native records/view |
| Data Exports | records | 1 | 0 | Native records/view |
| Webhooks | integration | 2 | 0 | Provider request records only |
| Watchlist Correlation | records | 1 | 0 | Native records/view |
| Packages | records | 1 | 0 | Native records/view |
| Depots | records | 1 | 0 | Native records/view |
| Vertiports | records | 1 | 0 | Native records/view |
| Visual Observers | records | 1 | 0 | Native records/view |
| Regulatory Approvals | records | 1 | 0 | Native records/view |
| Airspace Zones | records | 1 | 0 | Native records/view |
| Weather Briefs | records | 1 | 0 | Native records/view |
| Maintenance Logs | records | 1 | 0 | Native records/view |
| Route Corridors | records | 1 | 0 | Native records/view |
| Payload Specs | records | 1 | 0 | Native records/view |
| AI · Route Corridor Plan | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Weather Flight Window | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Mission Brief | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Anomaly Triage | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Executive Brief | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Payload Weight Optimize | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Battery Cycle Prognostic | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Regulatory Checklist | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Pilot Shift Schedule | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Ground Observer Plan | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Conflict Airspace Detect | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Customer Comms Draft | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Vertiport Capacity Plan | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Contingency Landing Plan | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Incident Post-Mortem | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Vendor Quality Score | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Part135 records | records | 1 | 0 | Native records/view |
| Vertiport slots | records | 1 | 0 | Native records/view |
| Customer eta narrate | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Weight balance advise | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Delivery window predict | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Notam aware reroute | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Autonomy advisory | records | 1 | 0 | Native records/view |
| Feeds admin | records | 1 | 0 | Native records/view |
| Warehouses | records | 1 | 0 | Native records/view |
| Scan Results | records | 1 | 0 | Native records/view |
| Discrepancies | records | 1 | 0 | Native records/view |
| SKU Master | records | 1 | 0 | Native records/view |
| WMS Snapshots | records | 1 | 0 | Native records/view |
| Maintenance Events | records | 1 | 0 | Native records/view |
| Telemetry | records | 1 | 0 | Native records/view |
| AI · Plan Inventory Pass | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Reconcile SKU Counts | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Maintenance Forecast | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Anomaly Classifier | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Route Optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · SKU Demand Forecast | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Swarm Coordinator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Exception Routing | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Live map | records | 1 | 0 | Native records/view |
| Discrepancy inbox | records | 1 | 0 | Native records/view |
| Mis pick detect | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Slot occupancy forecast | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Anomaly narrate | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Scan failure rca | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Photo damage classify | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Scan schedules | records | 1 | 0 | Native records/view |
| Wms live | records | 1 | 0 | Native records/view |
| Scan proofs | records | 1 | 0 | Native records/view |
| Cross dc reconciliations | records | 1 | 0 | Native records/view |
| Technician dispatches | records | 1 | 0 | Native records/view |
| Drone scheduling work | records | 1 | 0 | AI question-and-answer workspace; records available as context |

Row popup verification passed: dashboard and feature rows, keyboard/focus, editing and persistence, delete confirmation/cancellation, centered mobile layout and full-record navigation. See `reports/row-popup-verification.json`.

## Verified local build

Build, API, browser and actual `start.sh` checks passed. All 229 feature pages were visited in the browser; 227 editable tables contain at least 15 fictional rows each. CRUD persistence and mobile layout were checked. Evidence is in `reports/verification.json`, `reports/browser-verification.json` and `reports/startup-verification.json`.

These checks cover the native local workspace. Full source-specific business rules, authentication and live provider operations remain incomplete as described above. Test servers were stopped after verification.

## AI workspace verification

All 101 AI feature routes were checked in the browser and show questions and formatted answers instead of the original record table. Existing records are retained as optional context. Questions, follow-ups, saved history across restart, Markdown tables, safe rendering, downloads, provider-failure recovery and mobile layout passed with a mocked provider. See `reports/ai-workspace-verification.json`.

Live answers require `OPENROUTER_API_KEY` and `OPENROUTER_MODEL` in this app's `.env` and an app restart. No live provider call was made during verification. Conversational answers do not execute unmigrated specialist engines, read record attachments automatically or perform external actions.


## AI word limits

Questions support up to 5,000 words with a live counter and server validation. AI responses and record drafts have a 16,000-token output budget and a default 180-second timeout to support answers up to 5,000 words; actual length depends on the request and model. Answers show their word count, and long questions can be expanded. Browser checks passed for 5,000-word questions and answers, saved history, full downloads, mobile layout and rejection of 5,001-word questions. See `reports/word-limit-verification.json` (mock-provider boundary checks).

## Merged AI assistants

101 original AI entries are now grouped into **7 assistants** in the sidebar. Choose up to 8 related capabilities and add up to 10 questions for one provider request and one saved response. Shared context is sent once; repeated questions are removed after trimming and whitespace/case normalization. The total question limit is 5,000 words and the combined answer target is up to 5,000 words.

Original feature URLs still open the appropriate assistant with that capability selected. Existing records and answers stay in place; the assistant history includes answers saved under its member features. Non-AI record tables retain their popup actions. This merges the assistant workflow and navigation; it does not implement previously missing external integrations or specialist engines. See `reports/assistant-merge-map.json` and `reports/assistant-merge-verification.json`.

## Floating Ask AI assistant

Implemented across this workspace. The bottom-right **Ask AI** button opens a persistent chat panel on every page. Use **Ask AI about item** in a row popup or record view, or **Use current item** inside the panel, to supply the selected record.

- Questions about the page, any explicitly chosen app record, and general topics.
- Formatted answers, comparison tables, follow-ups, copy and Markdown download.
- Conversation and question drafts stay intact during in-app navigation. Saved answers persist in SQLite; the last conversation restores in the same browser tab after reload. The latest 50 saved answers are listed; restoring one displays up to 20 turns. Up to four preceding turns are sent as AI context.
- Up to 5,000 input words and a response budget of up to 5,000 words. Output length remains dependent on the provider and the question.
- Page title and description are supplied automatically; record fields and notes are sent only for a selected item. Attachments and unselected records are not included. **New chat** starts without earlier conversation context.
- Existing AI provider configuration, timeout, rate limit and safe response renderer are reused. The assistant answers and drafts; it does not execute record changes or external actions.

Validation: shared backend tests, all 64 app builds/API checks, and all 64 browser checks passed with an injected test provider. Browser checks cover item context, navigation, saved history/reload, follow-ups, new-chat isolation, error recovery, word limits, keyboard controls, mobile bounds, safe Markdown rendering and attachment refresh. See [verification](reports/floating-ai-verification.json).
