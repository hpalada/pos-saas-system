# POS SaaS System

Point-of-sale system built for a gas station — handles fuel and product transactions, inventory management, shift reporting, and daily operations. Delivered as a single-file web application with no server dependency.

> **Note:** This repository contains the UI shell and system architecture. Client transaction data is not included.

## Tech Stack

- **Frontend** — HTML, CSS, Vanilla JavaScript (no framework)
- **Architecture** — Single-page application with module-based navigation
- **Styling** — Custom design system with semantic color tokens

## Features

### POS Terminal
- Product and fuel transaction entry
- Cart management with quantity and price editing
- Payment processing (cash, card)
- Receipt generation

### Inventory
- Real-time stock tracking for store products
- Low-stock alerts
- Stock adjustment logging

### Reporting
- Daily sales summaries
- Shift close reports
- Revenue breakdown by product category

### Administration
- User and cashier management
- Product and price catalog management
- Shift scheduling

## System Design

Built as a self-contained single-page app to run on low-spec hardware common in small gas station environments. The modular section layout (sidebar navigation + content panels) mirrors a traditional desktop POS UX while running entirely in the browser.

## Files

| File | Description |
|---|---|
| `pos_system.html` | Complete POS application — open directly in a browser |

## How to Run

No server or build step required:

```bash
open pos_system.html
# or drag into any modern browser
```

## Highlights

- Developed a full POS system used in daily operations at a gas station
- Designed a modular section-based SPA architecture with no framework dependency
- Built a semantic color token system for consistent status indicators (alerts, confirmations, warnings)
- Handled transactions, inventory tracking, and end-of-shift reporting in a single deployable file
