# Deal Detail View

Standalone interactive prototype of a **Deal / Opportunity detail view** for a roofing CRM.

Single self-contained `deal-detail-view.html` — no build step, no dependencies beyond Tailwind and the Geist font loaded from a CDN. Open the file in any modern browser.

## Features

- Deal hero with value, probability, estimated close, and pipeline stepper.
- Customer, property, and insurance-claim panels.
- Estimate with roofing line items and totals.
- **Quick actions:** log call, send SMS, send email, create task, add note.
- Creation and edit modals, delete confirmation popups, and confirmation toasts.
- Activity timeline with type filters, plus a tasks list with complete / edit / delete.

State is held in memory and resets on reload (prototype).

## Run

Open `deal-detail-view.html` directly in a browser, or serve the folder statically:

```
python3 -m http.server 8080
# then visit http://localhost:8080/deal-detail-view.html
```
