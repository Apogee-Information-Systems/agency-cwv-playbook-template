# Agency CWV Playbook (Template Repo)

A **template repository** for running Core Web Vitals monitoring as a repeatable SOP. One repo per agency: add client files, follow the runbooks, and use GitHub Issue Forms for weekly/monthly/deploy checks.

**Who it’s for:** Agencies and dev teams that monitor many client sites and want a single place to track clients, budgets, and runbooks.

**What you need:** A GitHub account (to use the template and Issues). Any CWV tool (e.g. PageSpeed Insights or an automated monitoring service) to run the tests.

- Add one file per client in `/clients/`
- Use `/runbooks/` as your operating procedure
- Use the GitHub Issue Forms to run weekly/monthly/deploy checks

**Canonical article:** [Core Web Vitals Monitoring Checklist for Agencies](https://apogeewatcher.com/blog/core-web-vitals-monitoring-checklist-for-agencies)

For a lighter option (checklist only, no runbooks or client tracking), see [cwv-monitoring-checklist](https://github.com/Apogee-Information-Systems/cwv-monitoring-checklist).

## Quick start
1) Click **Use this template** to create a repo for your agency/team.
2) Create a new client file:
   - Copy `/clients/_client-template.md` → `/clients/<client-slug>.md`
3) Start work via Issues:
   - **New Issue** → “CWV: New client onboarding”
4) Keep an inventory:
   - Update `/ops/monitoring-inventory.csv`

## Suggested workflow
- One client = one file in `/clients/`
- Every week: open “CWV: Weekly monitoring” issue, tick boxes, note deltas
- Every month: open “CWV: Monthly deep review” issue, summarize trends
- Before/after deployment: open pre-/post-deploy issues

## Automate your monitoring

This playbook is tool-agnostic. To run CWV tests on a schedule, get alerts when metrics cross your budgets, and keep historical data for many sites, you can use [Apogee Watcher](https://apogeewatcher.com) — multi-tenant PageSpeed monitoring built for agencies. [Learn more →](https://apogeewatcher.com)
