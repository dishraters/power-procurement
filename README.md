# Power Procurement

A buyer-facing landing page for Jeremy's Power Procurement concept.

## Concept

Power Procurement helps high-usage businesses lower gas/electric costs by running a supplier reverse auction through Power Kiosk. The business shares its current rate/usage, qualified suppliers bid on the account, and the lowest qualified offer can be selected when it beats the current rate.

## What this page does

- Explains the reverse-auction offer in plain English.
- Shows a simple savings estimator for first-step buyer engagement.
- Frames the page as the QR-code destination for a 100-card direct-mail pilot.
- Captures the next production requirements: CRM/email integration, unique QR tracking, postcard API, and warm-call queue.

## Local development

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
```

## Production notes

The lead form is currently demo-only. Before using with real buyers, connect it to:

1. CRM or Google Sheet lead capture.
2. Email alert to Jeremy.
3. Per-company QR tracking / UTM parameters.
4. Postcard mail API campaign records.
5. Privacy/consent language appropriate for the final use case.
