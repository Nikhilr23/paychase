# PayChase

**Get paid without the awkward chase.**

PayChase is a lightweight browser-based invoice follow-up tracker for freelancers and small service businesses. It helps users see what is outstanding, identify overdue invoices, and generate professional payment reminder messages without needing a full accounting platform.

## MVP features

- Add and track invoices
- Outstanding, overdue, and recovered totals
- Automatic overdue-day calculation
- Search and status filters
- Friendly, standard, and firm reminder generator
- Copy reminders to clipboard
- Mark invoices as paid
- Delete invoices
- Browser-only persistence with `localStorage`
- Responsive interface
- No account, backend, or API keys required

## Follow-up cadence

The interface presents a simple example playbook: due date, +3 days, +7 days, +14 days, and +30 days. The MVP generates reminders on demand; it does **not** automatically send email.

## Technology

- HTML
- CSS
- Vanilla JavaScript
- Browser `localStorage`

## Privacy / architecture

The current MVP stores invoice data locally in the user's browser. There is no server-side database or authentication layer in this version. Users should avoid entering sensitive information they do not want stored in their browser profile.

## Future validation-driven roadmap

Potential upgrades after user validation include authentication, cloud sync, scheduled email delivery, saved reminder history, configurable cadences, Stripe subscriptions, accounting integrations, and team accounts.

## Run locally

Open `index.html` in a modern browser, or serve the directory with any static web server.

## Status

Early-stage MVP built for product validation.
