# scm-simulation-dashboard
Interactive Supply Chain Simulation &amp; Performance Dashboard — tracks 15 KPIs across P2P, Supplier, S&amp;OP, and Finance with a live what-if simulation engine and bidirectional cascade logic.

<img width="1879" height="976" alt="Screenshot 2026-07-02 022320" src="https://github.com/user-attachments/assets/f2c97cfe-df96-4ae7-a2c1-8e86c81468eb" />

<img width="1891" height="979" alt="Screenshot 2026-07-02 022432" src="https://github.com/user-attachments/assets/95e384bb-6fdc-4293-9b43-bf3aabf0f14a" />

# Supply Chain Simulation & Performance Dashboard

An interactive, data-driven decision-support tool built independently using HTML and JavaScript on a real supply chain dataset.

## What it does

- Tracks **15 interdependent KPIs** across P2P Operations, Supplier Performance, S&OP Planning, and Finance & Spend
- Simulates the downstream impact of any operational change in real time — improving OTIF automatically cascades through Supplier Score, NCRs, Chargebacks, and S&OP gap simultaneously
- Addresses a critical gap in conventional supply chain reporting: moves beyond static dashboards to model real operational behaviour, where every intervention triggers cascading consequences across all functions
- Benchmarks current actuals at **33% operational health** against a 95% industry-standard target — and identifies the minimum intervention required to close that gap

## How to use

Open `SCM_Dashboard_v4_2.html` in any modern browser. No installation or dependencies required.

Click **⚡ Simulate** in the top-right corner to open the simulation panel. Drag any slider to model a what-if scenario — all dependent metrics update live.

## Dataset

Built on a real supply chain dataset covering Jan–Apr 2024: 25 POs, 10 suppliers, 18 GRNs, 17 invoices, and 12 NCRs across Raw Materials, Logistics, Packaging, IT Services, and Professional Services categories.

## Tech

HTML · CSS · Vanilla JavaScript · SVG charts · No external frameworks or libraries required
