# Phase 5: Post-Deployment Verification

Run within 24 hours of a deployment.

- [ ] Run immediate tests — Test all key pages on both mobile and desktop within 1 hour of deployment
- [ ] Compare against pre-deployment baseline — Look for any metric regressions
- [ ] Check CLS specifically — Deployments often introduce layout shifts through new elements, changed styles, or updated fonts
- [ ] Verify LCP element — Has the LCP element changed? A new hero section or image could alter LCP behavior
- [ ] Monitor for 48 hours — Some issues only appear under real traffic. Keep monitoring closely for 2 days after deployment
- [ ] Notify the client — Report on whether the deployment maintained, improved, or degraded performance
