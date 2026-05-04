# Deadswitch Disputes — Landing Page

Static landing page for [deadswitch-labs](https://github.com/lordbasilaiassistant-sudo/deadswitch-labs) — an open-source AI medical bill auditor.

## What this repo is

Just the marketing/pre-order page. The actual auditor lives in the `deadswitch-labs` CLI repo.

## What it does NOT do

- **Does not collect or process medical bills.** The hosted upload flow stays in private beta until a privacy review clears it. v1 of this site is pure marketing + a Stripe pre-order link.
- **Does not store anything about you.** No analytics scripts, no tracking pixels, no email harvesting. The only outbound is the Stripe checkout button, and Stripe handles its own data.

## Stripe setup

The page contains a `{{STRIPE_PAYMENT_LINK}}` placeholder that gets swapped for the live Stripe Payment Link URL during deploy. Do not commit a real Stripe URL into this README.

## Deploy

GitHub Pages serves `index.html` from `main`. Just `git push`.

## License

AGPL-3.0, same as the CLI.
