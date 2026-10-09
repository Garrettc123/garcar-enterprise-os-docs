# Garcar Enterprise OS

Unifying layer above the portfolio. It stores system metadata, repo topology, commercial packaging, deployment status, and validation evidence.

This document does not claim cash, MRR, or a live deploy.

## Modules

1. Asset Registry — systems, owners, docs, status, dependencies, commercial tags.
2. Repo Registry — GitHub repos, branches, CI, environments, release state.
3. Offer Engine — maps a verified asset to an existing SKU. Does not invent prices.
4. Validation Hub — tests, screenshots, logs, links, credential readiness. No public claim without a row here.
5. Control Panel UI — portfolio health and next action. Lives in `garcar-enterprise-os-ui`.

## Layers

Compute, storage, network, management, security, application. Infra repo owns the first five as runbooks. Application code stays in core, services, and ui.

## Repo map

| Repo | Role | Visibility intent |
|---|---|---|
| garcar-enterprise-os-docs | Architecture, offers, onboarding, collateral | public |
| garcar-enterprise-os-ui | Control panel and investor-safe pages | public |
| garcar-enterprise-os-core | Domain models, scoring, validation workflows | private |
| garcar-enterprise-os-services | Asset registry, repo registry, offer engine, validation hub | private |
| garcar-enterprise-os-infra | Docker, Kubernetes, Terraform, CI, secrets references | private |

Push order used: docs, ui, core, services, infra.
