# HANDOFF.md — Laredo Concrete Leveling

**Last updated:** 2026-10-27 (site build + launch)

## Shipped
- 4 pages live: `/`, `/concrete-leveling-laredo-tx/`, `/get-a-quote/`, `/about/`
- Schema: LocalBusiness on all pages, Service + FAQPage on money page, WebSite on hub
- `sitemap.xml` + `robots.txt`, mobile-responsive, GBP footer mention
- Quote form: client-side validation; posts JSON to `LEAD_ENDPOINT` when set; otherwise one-click pre-filled email fallback (nothing silently lost)

## Live URL
- https://wreid11.github.io/concrete-leveling-laredo/ (GitHub Pages, main branch)
- Vercel migration pending board's hosting-provider choice (TES-8)

## Waiting on decisions
1. **Hosting:** board to pick Vercel provider connection (asked on TES-8). After connect: import repo, set custom subdomain, update BASE_URL canonicals + sitemap (one find/replace), redeploy.
2. **Lead endpoint:** operator to set the form delivery (Formspree/FormSubmit email, or Vercel function + webhook). 15-minute task; until then submissions use the email fallback.
3. **Domain:** buy exact-match domain (~$11/yr, e.g. `concreteleveling-laredo.com`) and point it at the site. Recommended before content push.
4. **Exclusive lead buyer:** sales side — first 3 leads free to lock in a contractor at $150–200/mo (playbook: research synthesis Week 1).
5. **GBP claim:** create/claim Google Business Profile for the brand; swap footer link; add listing URL to SITE.md.

## Next actions (in order)
1. Wire lead endpoint (operator, 15 min)
2. Vercel/domain decision (board) → URL swap (agent, 10 min)
3. Submit sitemap to Google Search Console + Brave on the final domain (agent, day of domain live)
4. 90 days: first GSC review — quick wins only, per RULES.md pace
