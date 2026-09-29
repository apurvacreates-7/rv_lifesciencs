# FreeStand × RV Lifesciences — Demo Hub

Two WhatsApp sampling journeys in the FreeStand demo UI:

1. **Pain relief spray**: ads and gym QR lead to WhatsApp qualification, then SKU match, Shiprocket delivery, relief feedback, 1mg/Amazon conversion and episodic re-engagement
2. **Gummies & supplements**: a quiz ad leads to WhatsApp qualification with a doctor guardrail, then a 7-day trial, Day 1/4/7 check-ins, feedback, a 30-day pack and Day-25 replenishment

`index.html` is a self-contained bundle served as-is by GitHub Pages. SKU pack images are placeholders until real pack shots are supplied.

## Celin Gold click-through demo

Live: https://apurvacreates-7.github.io/rv_lifesciencs/celin-gold/

Three 11-step demos in one Freestand app shell, switched with the toggle at the top:

1. **Celin Gold · Delhi pollution season** (D2C WhatsApp sampling): Instagram Reel, click-to-WhatsApp consent, three questions, PIN/address/OTP, fulfilment, day 7 and day 15 check-ins, AQI and marathon re-engagement, analytics
2. **Doctor network activation** (offline experience, WhatsApp-run): doctor list import, Magicflow journey, WhatsApp invite or AI voice call, 8,000-kit fulfilment, kit handover in the OPD, patient QR activation, monthly doctor re-engagement, analytics
3. **Celin Gold · Website sampling** (search ad × web form): Google Search ad, name/email/phone on RV's landing page, OTP sent on WhatsApp and typed into the web form, brand questions, PIN-first address and eligibility checks, claim confirmation, shipping and delivery updates on WhatsApp, day-15 feedback, RV Wellness Club loyalty (chemist bill on WhatsApp → stamp, 4th pack free), refill-reminder re-engagement, analytics

Move with Next/Back or the ← → keys; buttons inside the phone are clickable; ⌘K / Ctrl+K jumps to any step; `#d2c-4`, `#doc-9` or `#web-3` in the URL opens a step directly. `celin-gold/index.html` is fully self-contained (inline CSS/JS, embedded images; only Google Fonts load externally). All people, numbers and records in it are fictional.

## Archive
- `archive/rv_hub_spray_gummies_web.html` — previous hub with all three tabs (pain relief spray, gummies, website sampling). The live `index.html` shows only the website sampling demo; the spray and gummies demos are also kept inside it under `window.HUB_DEMOS_HIDDEN`.

## HUL BeBeautiful SmartPick Box demo

`hul-smartpick/index.html` is a clone of the Celin Gold shell (same skeleton, CSS, engine, hash routing, step bar and CDP panel), re-themed in blush, cream and deep plum. It has one 10-step journey: BeBeautiful article widget, three questions with store pickup, WhatsApp OTP and confirmation, delivery to Gupta General Store, pickup QR, retailer-app QR verification, the Red Label counter cross-sell, bill upload with points, the HUL wallet explainer and the results dashboard. Deep links run from `#web-1` to `#web-10`, and the top tabs jump between chapters. It is self-contained (only Google Fonts load externally). All people, stores, numbers and records in it are fictional.
