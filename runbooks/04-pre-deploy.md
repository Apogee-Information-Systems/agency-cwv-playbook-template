# Phase 4: Pre-Deployment Checks

Run these before any major site change goes live.

- [ ] Baseline current scores — Record current CWV metrics for all key pages before the deployment
- [ ] Test staging environment — If available, run PageSpeed tests on the staging site to catch issues before production
- [ ] Check for new render-blocking resources — Is the deployment adding new CSS/JS files? Are they deferred?
- [ ] Verify image optimization — Any new images should be compressed, properly sized, and have dimensions set
- [ ] Test critical interactions — For INP: test key interactions (form submissions, menu toggles, search) on the staging site
- [ ] Plan post-deployment monitoring — Schedule immediate post-deploy tests to catch any regressions quickly
