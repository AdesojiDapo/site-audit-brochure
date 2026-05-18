# Curiosity, Site Audits in Plain English

**For:** owners and editors of WordPress, Webflow, and custom-built business websites
**By:** Curiosity  ·  All enquiries: admin@curiositybyade.com
**Price:** **£499 flat** · No retainer, no surprises · International invoicing on request
**Turnaround:** **5 business days** from kickoff call to written report

---

## What you get

Five deliverables, all yours to keep:

1. **A written audit report.** Roughly 8 to 15 pages of plain English findings, sorted by severity. Every issue includes a one-line fix you or your developer can act on.
2. **A site-wide review.** Extends the audit beyond the homepage to the standard attack surface: login, REST API, sitemap, feed, common WordPress paths, and a sample of internal pages.
3. **A live before-and-after homepage demo.** One representative page rebuilt to show how the recommendations land visually, with your existing brand and advertisers preserved.
4. **A presentation.** A short slide deck of the audit and the recommendations, ready to share with your team or the people who pay for the work.
5. **A 45-minute walk-through call.** I take you through every finding, answer questions, and help you prioritise.

All five live in one online folder, ready to transfer to your account in one click.

---

## What I check

| Category | What gets reviewed |
|---|---|
| **Security** | CMS version disclosure, REST API enumeration, XML-RPC, login brute-force protection, admin path exposure, third-party script supply chain, OAuth tokens, security headers (CSP, HSTS, X-Frame-Options, Referrer-Policy, Permissions-Policy) |
| **Privacy** | Trackers loaded before consent, cookies set on first visit, leaked user emails in public content, RSS or sitemap information disclosure |
| **Performance** | Page weight, third-party origin count, render-blocking assets, image lazy-loading, font loading strategy, estimated Lighthouse score |
| **Accessibility** | WCAG 2.1 AA contrast checks, viewport zoom, heading order, image alt coverage, focus visibility, skip link, keyboard navigation |
| **Design** | Typography hierarchy, layout consistency, mobile breakpoints, ad placement quality, social preview cards, broken shortcodes |
| **Code quality** | Dead CSS, unused plugins, invalid HTML, version fingerprinting, abandoned dependencies, inline event handlers |
| **SEO and structure** | robots.txt, sitemap, canonical tags, redirect map readiness |

I do not run noisy scanners. Every probe is a single HEAD or GET request made with a standard browser User-Agent, the way a real visitor's browser behaves.

---

## How it works

| Day | What happens |
|---|---|
| **Day 0** | 30-minute kickoff call. You share the URL and any context I should know (advertisers, recent incidents, things you do not want changed). |
| **Days 1–3** | I run the audit. No access to your hosting is needed for the standard package. |
| **Day 4** | I draft the report and the slide deck. |
| **Day 5** | 45-minute walk-through call. You receive the folder with everything. |

If you also want the homepage redesign demo, that adds a second week.

---

## Who this is for

- Personal-brand sites of public figures (broadcasters, columnists, professionals) who want to know their site is not a liability.
- Mid-size publishers and media houses whose WordPress has grown organically over the years.
- B2B websites where the marketing team owns the site but does not have a security or design specialist in-house.
- NGOs and trade associations that want documentation more than dazzle.

It is **not** for: enterprise SaaS apps, e-commerce with payment flows, or sites needing penetration testing. Those need a different specialist.

---

## What is in scope, and what is not

**In scope**

- Homepage HTML in detail
- Security headers (CSP, HSTS, X-Frame, X-Content-Type, Referrer, Permissions)
- REST API enumeration paths
- Login and admin paths
- XML-RPC, RSS feed, sitemap, robots.txt
- Standard WordPress and Drupal attack-surface paths
- A sample of internal pages from the sitemap
- Third-party trackers and consent flow
- Accessibility signals from the markup (WCAG 2.1 AA)
- Performance signals (asset count, page weight, font strategy)

**Not in scope**

- Penetration testing or active exploitation
- Authenticated user-journey testing
- Payment flow and checkout audits
- Source-code review or hosting-config review
- Database or backup security
- Brute-force or rate-limit testing against live forms
- Probing non-standard ports or subdomain portals
- Mobile app review
- Vulnerability scanning with automated tools

Any of the above can be quoted as a separate engagement.

---

## Proof

Three recent audits, ready to read:

- **JimiDisu.com (Nigerian news commentary site)** — 15 security findings including open REST API user enumeration, no brute-force protection on `wp-login.php`, and 10+ trackers running without consent. Full report and redesign demo: [github.com/AdesojiDapo/jimidisu-redesign](https://github.com/AdesojiDapo/jimidisu-redesign)
- **ipintegration.com (UK enterprise tech)** — Properly hardened site. The audit found two High-severity items (a WCAG-blocking viewport setting, a missing Content-Security-Policy) and a tight list of minor improvements. About 16 engineering hours of remediation work: [github.com/AdesojiDapo/ipintegration-audit](https://github.com/AdesojiDapo/ipintegration-audit)
- **vgpensions.com (Nigerian pension fund administrator)** — Regulated financial services site. Strong baseline hardening, four High items, all best-practice gaps rather than active vulnerabilities. About 24 engineering hours plus a recommended follow-up on the portal subdomains: [github.com/AdesojiDapo/vgpensions-audit](https://github.com/AdesojiDapo/vgpensions-audit)

All three audits used the same checklist. Same severity grading. Same deliverables.

---

## What it costs

| Package | What you get | Price | Turnaround |
|---|---|---|---|
| **Audit** | All five deliverables above | **£499** | 5 business days |
| **Audit + Homepage Redesign Demo** | Audit + one representative page rebuilt as a live preview | **£1,199** | 10 business days |
| **Audit + Full Site Redesign + Migration** | Audit + every template rebuilt + content migration + redirects | **From £4,995** | 4 to 6 weeks |

Payment terms: 50 percent on kickoff, 50 percent on delivery. UK invoice in GBP by default. USD or NGN invoice on request for international clients. Bank transfer or Stripe.

---

## How to book

Reply to this brochure or send a one-line email to **admin@curiositybyade.com** with your site URL. I will reply within one business day with a 30-minute kickoff slot.

If you would like to see what one of these audits actually looks like before committing, the JimiDisu.com and ipintegration.com reports linked above are public and free to read.

---

*Curiosity is an independent site-audit practice. We focus on independent media, personal-brand websites, and small B2B publishers, with clients in Nigeria, the UK, and the US.*
