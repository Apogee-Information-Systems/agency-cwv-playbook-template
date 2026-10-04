# Phase 1: Client Onboarding

Run these checks when you first take on a new client's site.

- [ ] Baseline all key pages — Run PageSpeed Insights (mobile + desktop) on the homepage, top 5 landing pages, and any high-conversion pages (pricing, contact, checkout)
- [ ] Record baseline scores — Document current LCP, INP, CLS, FCP, TBT, and overall Performance Score for each page
- [ ] Check field data availability — Verify whether the site has enough traffic for Chrome User Experience Report (CrUX) field data. If not, lab data will be your primary source
- [ ] Identify the LCP element on each key page — Is it an image? A text block? A video? Knowing this tells you where to focus optimization
- [ ] Audit third-party scripts — List all third-party scripts (analytics, chat widgets, ads, tracking pixels). Note which ones are render-blocking
- [ ] Check image optimization — Are images served in modern formats (WebP/AVIF)? Are dimensions set? Are they responsive?
- [ ] Test on real devices — Lab tests on a fast laptop don't reflect mobile experience. Test on a mid-range Android device or use throttled DevTools
- [ ] Set performance budgets — Based on baselines and "Good" thresholds, define target values for each metric:
  - LCP: ≤ 2.5s (stretch: ≤ 1.8s)
  - INP: ≤ 200ms (stretch: ≤ 100ms)
  - CLS: ≤ 0.1 (stretch: ≤ 0.05)
  - Performance Score: ≥ 90
- [ ] Set up automated monitoring — Configure daily automated tests for all key pages (both mobile and desktop strategies). If the client has no sitemap: add key URLs manually; many tools support sitemap + manual URL entry.
- [ ] Configure alerts — Set threshold-based alerts so you're notified when any metric crosses its budget
- [ ] Document the monitoring setup — Record which pages are monitored, which budgets are set, and who receives alerts
