# PayChase

**Get paid without the awkward chase.**

Live MVP: https://nikhilr23.github.io/paychase/

PayChase is a lightweight browser-based invoice follow-up tracker for freelancers and small service businesses. It helps users see what is outstanding, identify overdue invoices, and generate professional payment reminder messages without needing a full accounting platform.

## Current MVP

- Add and track invoices
- Edit and delete invoices
- Outstanding, overdue, and paid-tracked totals
- Automatic overdue-day calculation
- Search and status filters
- Friendly, standard, and firm reminder generator
- Copy reminders to clipboard
- Mark invoices as paid
- Export invoice data as a JSON backup
- Browser-only persistence with `localStorage`
- Responsive interface and keyboard focus states
- Installable web-app manifest
- No account, backend, external API, or API keys required

## Follow-up cadence

The interface presents a simple example playbook: due date, +3 days, +7 days, +14 days, and +30 days. The MVP generates reminders on demand; it does **not** automatically send email.

## Technology

HTML, CSS, vanilla JavaScript, browser `localStorage`, GitHub Actions, and GitHub Pages.

## Privacy / architecture

The current MVP stores invoice data locally in the user's browser. There is no server-side database or authentication layer. Users should avoid entering sensitive information they do not want stored in their browser profile.

## Acquisition / handoff notes

The project is intentionally small and transferable: static source code, no backend infrastructure, no production secrets, and no external service dependencies in the current version. A buyer can continue the existing browser-only product or extend it with authentication, cloud sync, scheduled email delivery, reminder history, configurable cadences, billing, accounting integrations, and team accounts.

No revenue, customer, traffic, or profitability claims are made in this repository.

## Run locally

Open `index.html` in a modern browser, or serve the directory with any static web server.

## Status

Functional early-stage MVP built for product validation and potential acquisition.
