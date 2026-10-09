# Phase 0 — truth audit

Date: 2026-10-09. Method: authenticated GitHub search as Garrettc123, plus the live-surface reconcile. Not a deploy check.

Labels: verified = repo or link exists. partial = repo exists, runtime not proven this pass. aspirational = named in a plan or README, no source checked.

| Item | Class | Evidence |
|---|---|---|
| ai-ops-studio | partial | https://github.com/Garrettc123/ai-ops-studio |
| ai-orchestrator | partial | https://github.com/Garrettc123/ai-orchestrator — described as DFW LLA-47 loop |
| ai-business-platform | partial | https://github.com/Garrettc123/ai-business-platform |
| ARCHITECT_Pro-Enterprise | partial | https://github.com/Garrettc123/ARCHITECT_Pro-Enterprise |
| garcar-autonomous-wealth-system | partial | https://github.com/Garrettc123/garcar-autonomous-wealth-system |
| tree-of-life-system | partial | https://github.com/Garrettc123/tree-of-life-system |
| vertical-dominator-os | partial | private repo, exists |
| operator zeus.py run-once | aspirational | not in skill pack; revenue-agent-system/zeus.py is a different deployer and exited 1 on missing secrets |
| Stripe payment links | verified as offers | see offers/evidence-rules.md |
| Stripe paid cash | not verified | zero paid in the 2026-09-28 charge sample |
| 108+ systems | aspirational | claim sits in tree-of-life-master-integration description; not inventoried here |

Credential dependencies still missing on the operator host used 2026-10-09: VERCEL_TOKEN, STRIPE_SECRET_KEY, DEFENDER_SLACK_WEBHOOK, RAILWAY_API_TOKEN, DEFENDER_DOMAINS, GH_PAT, PERPLEXITY_API_KEY. GitHub connector auth worked. Raw PAT was not required for these writes.
