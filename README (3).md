# Pen Lab

A tiny fake store for practising tracking fixes: dataLayer -> Google Tag Manager -> GA4, with breaks planted on purpose.
Lab only: no real orders, no real ad clicks.

## Pages
- `go.html`: pretends to be the redirect after an ad click. `?mode=broken` drops every URL parameter.
- `index.html`: landing page. Shows the URL parameters it received.
- `product.html`: "Buy now" creates order 1001, 1002, ... in this browser.
- `thankyou.html`: pushes the purchase to the dataLayer. `SEND_ONCE` is the switch for drill 4.

GTM container: `GTM-WN4RCT89` (already in `index.html`, `product.html` and `thankyou.html`; `go.html` has no GTM on purpose).

## Notebook
One line per drill. Symptom first, in the words a client would use.

| Date | Drill | Symptom (what I saw) | Where I looked | Cause | Fix | Proof |
|---|---|---|---|---|---|---|
| | | | | | | |
