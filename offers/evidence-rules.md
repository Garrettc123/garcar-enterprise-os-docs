# Evidence rules

A public revenue claim needs a reference in this folder. A Stripe payment link is an offer. It is not cash.

Cash is a Stripe charge with `paid=true` and last4 not 4242. HubSpot appointment amounts are not cash.

## Existing SKUs (links active as of 2026-09-28 skill reconcile)

Do not add a price that is not in this list.

| SKU | Kind | URL |
|---|---|---|
| LLA-47 | $47 one-time | https://buy.stripe.com/3cI00j7YV0hQgDp8BR43S2v |
| AI-AUDIT-299 | $299 one-time | https://buy.stripe.com/14A5kD3IF9Sqdrd05l43S2l |
| ENT-AUDIT-3500 | $3500 one-time | https://buy.stripe.com/4gMfZh1Ax2pYbj5dWb43S2t |
| MARS-750 | sub starter | https://buy.stripe.com/4gM7sL6UR3u29aX4lB43S2r |
| MARS-1500 | sub growth | https://buy.stripe.com/7sY4gz1Ax3u20Er6tJ43S2s |
| GROWTH-1497 | sub | https://buy.stripe.com/8x29AT7YVe8G3QD4lB43S2m |

Retired, do not send: `https://buy.stripe.com/dRm8wPbb72pY2Mz8BR43S1D`.

## Cash status on this pass

Not cash. The 2026-09-28 reconcile recorded four failed charge objects and zero paid on `acct_1SS3dpFKGbk21LK5`. This scaffold does not re-query Stripe.
