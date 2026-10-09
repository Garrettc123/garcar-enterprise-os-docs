# Implementation roadmap

## Phase 0 — Truth audit

Done as a document on 2026-10-09: `audit/phase-0-truth.md`. Not a runtime audit.

## Phase 1 — Commercial wrapper

UI control panel and landing page are in `garcar-enterprise-os-ui`. Asset and offer schemas are in core. Evidence rules are in `offers/evidence-rules.md`. Screenshots and demo links are still missing.

## Phase 2 — Repo and deployment governance

Repos exist. CI workflows exist. Conclusions are not recorded yet. Deploy targets are none.

## Phase 3 — Offer packaging

Templates map only to LLA-47, AI-AUDIT-299, ENT-AUDIT-3500, MARS-750, MARS-1500, GROWTH-1497. Cash stays false until Stripe `paid=true` and last4 is not 4242.

## Phase 4 — Validation automation

Starter scorer is in `garcar-enterprise-os-services` `validation_hub.py`. It does not call production.

## Phase 5 — Revenue operations

Not connected. CRM and billing writes are out of scope until a paid charge exists.
