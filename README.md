# KhataScan demo

Built demo of [KhataScan](https://github.com/affanabbas-786/khatascan): a photo of a
handwritten bahi khata becomes a digital ledger with totals, customer statements and
WhatsApp reminders. By Dazzle Tech LLC.

Live: https://affanabbas-786.github.io/khatascan-demo/

## What this repo is

Compiled output only. No source, no API keys, no backend credentials. The source
lives in a private repository.

## What works in the demo

Capture (multi-page), the review screen with its per-page sum check, the customer
ledger, statement PDF and WhatsApp reminder links, all offline after first load.

**The scan is a fixture, not a real AI call.** With no backend configured the app
returns a prepared page so the whole flow can be walked through. One demo page
carries a deliberate misread so the sum check fires and you can see how a wrong
reading is caught.
