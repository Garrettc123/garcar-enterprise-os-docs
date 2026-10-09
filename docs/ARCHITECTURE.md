# Architecture

Garcar Autonomous Enterprise OS is the governing shell over the portfolio. It is not a claim that every named system is in production.

## Modules

1. Asset Registry — canonical systems, status, owner, evidence links.
2. Repo Registry — GitHub repo, branch, CI conclusion, deploy target.
3. Offer Engine — one existing SKU per asset. No invented price.
4. Validation Hub — tests, screenshot, log, link, docs. Public claim only after green.
5. Control Panel UI — operator view. Investor page is a separate file and repeats the same statuses.

## Layers

Compute, storage, network, management, security, application. Infra holds runbooks. Application code stays in core, services, and ui.

## Truth rule

verified = repo plus runtime plus tests checked. partial = repo exists, runtime not proven. aspirational = named only. A 16-system count was not inventoried on 2026-10-09.
