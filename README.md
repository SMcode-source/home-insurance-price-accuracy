# Home Insurance Price Accuracy

A single-page summary of how accurately a statistical model reproduces what
twelve UK home insurers charge for a given risk, measured only on held-out
weeks the model never saw.

**→ https://smcode-source.github.io/home-insurance-price-accuracy/**

## The data is synthetic

Every figure on the page comes from a **synthetic sample extract**, not from
real market data. The generator reproduces the structural features that make
this problem hard — multiplicative rating, minimum-premium floors, per-brand
declines, tactical price drift — which is what makes the measurements
meaningful as engineering.

The brand names are labels on invented data. **Nothing on this page describes
any real insurer's pricing, and none of it should be quoted, cited or
benchmarked as if it did.**

## What is in this repository

Only the published page. The modelling code, the vendor-extract tooling and the
collection pipeline live in a separate private repository; this repo exists so
the results summary has a public URL.

The page is generated from that project's `ui/index.html` by `ui/build_public.py`
— it is not hand-maintained here, so do not edit `index.html` directly.
