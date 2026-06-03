# POS System — Gas Station

Point-of-sale system built for a gas station in Honduras. Handles fuel and product transactions, cart management, cash and card payments, shift reporting, and inventory tracking. Delivered as a single-file SPA with no build step or server dependency — runs on any browser on existing hardware.

> Used in daily operations at a real gas station.

## Stack

HTML · CSS · Vanilla JavaScript — no framework, no bundler, no external dependencies.

## Features

### POS Terminal
- Fuel and store product transaction entry
- Cart management — quantity editing, price overrides, line item removal
- Cash and card payment processing with change calculation
- Receipt generation per transaction

### Inventory
- Real-time stock tracking for store products
- Low-stock alerts
- Stock adjustment and purchase logging

### Shift Reporting
- Daily sales summaries
- Shift close reports with revenue breakdown by category
- Cash session reconciliation — expected vs. actual cash at close

### Administration
- Product and price catalog management
- User and cashier account management

## Design Decisions

Built as a self-contained single-file app because the target environment — a small gas station — runs on low-spec hardware with no local server. The modular section layout (sidebar navigation + content panels) mirrors a traditional desktop POS UX while running entirely in the browser with no internet dependency.

## How to Run

No install required:

```bash
open pos_system.html
# or drag the file into any modern browser
```

## Highlights

- Deployed and used in daily operations at a real gas station
- Single-file SPA — zero dependencies, works offline, no setup needed on any machine
- Semantic color token system for consistent status indicators across the UI
- Cash session reconciliation with expected vs. actual tracking at shift close

---

Built by Homer Palada — CS student at Universidad Católica de Honduras, graduating May 2027.
