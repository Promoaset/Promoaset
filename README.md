# ViKlandCraft sleep-income workflow

A practical, compliance-aware affiliate-content engine for [ViKlandCraft](https://beviklandcraft.art.blog), focused on UK woodworking, crafts, tools, materials and project guides.

## What this does

- Finds buyer-intent topics that fit the site’s real woodworking/craft expertise.
- Produces one useful, original article draft each week.
- Adds a clear affiliate disclosure before recommendations.
- Checks factual freshness, safety language, originality, search intent and link-register fields.
- Keeps publishing gated until the site is ready and the owner approves the final article.
- Creates a short weekly report covering drafts, blockers, clicks, conversions and next actions.

## Current constraints

The connected WordPress site is live and has a custom domain, but its current plan does not expose automated site editing. The workflow therefore prepares review-ready drafts and a queue rather than pretending to publish. Hands-off publishing requires a WordPress plan and site configuration that support the required authoring tools, plus approved affiliate accounts and link IDs.

This system can create assets and opportunities; it cannot guarantee traffic, programme acceptance or income.

## Files

- [`automation/weekly-content-playbook.md`](automation/weekly-content-playbook.md) — the unattended weekly runbook.
- [`automation/content-queue.csv`](automation/content-queue.csv) — the first 12 weeks of topics and monetisation intent.
- [`automation/link-register.csv`](automation/link-register.csv) — tracking register for affiliate links.
- [`compliance/affiliate-disclosure.md`](compliance/affiliate-disclosure.md) — disclosure copy and placement rules.
- [`compliance/site-readiness.md`](compliance/site-readiness.md) — launch gates and missing inputs.
- [`drafts/001-best-woodworking-tools-for-beginners-uk.md`](drafts/001-best-woodworking-tools-for-beginners-uk.md) — first draft to edit, fact-check and publish when ready.

## Human approvals still required

1. Join any affiliate programme and accept its terms.
2. Supply the legal/trading name and public privacy email used on the site.
3. Confirm product claims, safety advice, prices and stock before publication.
4. Approve publication or enable an explicitly reviewed publishing workflow.
5. Choose whether to upgrade WordPress; no purchase is made by this repository.
