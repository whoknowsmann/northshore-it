# North Shore IT — Website & Business Reference

This repo contains the marketing website for **North Shore IT LLC**, a freelance managed IT services business targeting small professional offices in the Skokie/Evanston/North Shore Chicago area.

---

## The Business

### What It Is
A solo-operated IT services LLC delivering remote IT support to small private practices (law firms, accountants, financial advisors, real estate offices) in the North Shore Chicago suburbs. Priced aggressively — roughly 50% below market rate — because overhead is minimal and the delivery model relies on AI-agent-assisted remote support via Tailscale tunnel.

### Why It Works
- Big MSPs (iTeknologia, ReadyNetworks, XL.net) don't focus on 1–8 person offices
- Those offices need IT but can't justify $150–200/user/month
- Remote-first delivery + AI-assisted labor keeps costs low enough to undercut significantly
- North Shore is affluent — clients pay for reliability and personal service
- Sticky clients: once set up, they rarely leave

### Target Market
**Phase 1 (launch):** Lawyers, accountants, financial advisors, real estate offices
- No HIPAA compliance needed
- Professional confidentiality concerns make the "Local First" pitch land well

**Phase 2 (6–12 months in):** Psych practices, dental offices, small medical practices
- Requires HIPAA Business Associate Agreements (BAA templates needed)
- Wife (licensed RN → CRNA) provides clinical credibility and referral network

### Key Details
- **LLC Name:** North Shore IT LLC ✅ (confirmed available with IL SOS)
- **Domain:** northshoreitsupport.com (available, not yet registered as of session)
- **Brand name:** North Shore IT
- **Location:** Skokie, IL (serving Skokie, Evanston, Wilmette, Lincolnwood, Morton Grove, Niles)
- **Operator:** Jack — handles sales, client relationships, in-person onboarding visits
- **Delivery:** AI agents handle remote execution via Tailscale; Jack handles edge cases

---

## Pricing

### Monthly Retainer Tiers

| Tier | Users | Price | Market Rate |
|---|---|---|---|
| Micro | 1–3 users | $299/mo | $450–600/mo |
| Small | 4–7 users | $449/mo | $750–1,200/mo |
| Standard | 8–12 users | $699/mo | $1,400–2,000/mo |

- Month-to-month, no contracts
- No per-ticket charges
- Business hours (M–F 9am–5pm CT), remote only
- Off-menu work: **$85/hr**

### Break-Even
Monthly overhead: ~$200–225/mo (insurance + tools + LLC fees)
Target profit: ~$1,000/mo
Required revenue: ~$1,200/mo → achievable with 4–5 clients

---

## The "Local First" Privacy Package

A one-time add-on for clients who want full data sovereignty. Everything runs on hardware in their office.

**Price: $499 all-in (one-time)**

| Item | Cost |
|---|---|
| Business-grade mini-PC (Dell OptiPlex 3080 Micro or Lenovo ThinkCentre M920q) | $150 |
| Internal 5TB HDD (daily encrypted backup) | $75 |
| External 2TB drive (manual offsite/failsafe backup) | $50 |
| Setup, software config, staff onboarding (1 hr) | $200 |
| Ongoing monitoring | Included in retainer |

### Software Stack (all open-source, runs on the mini-PC)
- **Nextcloud** — local file storage/sync (replaces Google Drive/Dropbox)
- **Vaultwarden** — self-hosted password manager (replaces LastPass/1Password)
- **Pi-hole** — DNS-level ad/tracker blocking, office-wide
- **Matrix/Element** — encrypted team messaging (replaces Slack)
- **Encrypted backup** — automated nightly to internal HDD; external drive for manual offsite rotation

### Hardware Notes
We standardize on two models exclusively — same hardware every time = same config, same troubleshooting, easy replacements:
- **Dell OptiPlex 3080 Micro** — i5-10500T, 16GB RAM, 256GB NVMe + secondary 2.5" bay for 5TB HDD
- **Lenovo ThinkCentre M920q Tiny** — i5-8500T, 16GB RAM, 256GB NVMe + secondary 2.5" bay

We source these as business-grade refurbished units. Don't mention sourcing to clients unless asked — some older clients have outdated perceptions of refurb hardware. These are enterprise-spec machines that came off corporate leases; they're more reliable than most consumer-new PCs.

### Future: Home NAS for Offsite Backup
Once client base generates enough recurring revenue, the plan is a Synology DS223 + 2× 8TB IronWolf drives (~$450) as a home NAS. Clients' mini-PCs would back up nightly over Tailscale to Jack's NAS — fully automated, no manual drive swaps.

**Revenue trigger:** Offer "Managed Offsite Backup" at +$25/mo per client during in-person onboarding (not advertised on site yet). At 3 clients = NAS paid off in ~6 months.

**DO NOT advertise the offsite backup add-on on the public site until the NAS infrastructure is live.** Handle it verbally during onboarding in the meantime.

### Future: Private AI
Local LLM hosting (Ollama) is aspirational. The mini-PCs can't run LLMs at usable speed (i5 + 16GB = 30+ seconds per response). Revisit when client base justifies a home GPU farm (RTX 3090s). Would offer private AI inference over Tailscale as a premium feature — "Local First AI."

---

## Competitive Landscape

| Competitor | Focus Area | Est. Pricing |
|---|---|---|
| iTeknologia | Chicago / Evanston / Skokie | ~$150–200/user/mo |
| ReadyNetworks | Evanston (since 2013) | ~$150–200/user/mo |
| XL.net | Chicago metro | ~$150–200/user/mo |
| BTI | Chicagoland | ~$150–200/user/mo |

None publish pricing. All target 10+ employee businesses. Our gap is below them.

**Key differentiator message:** *"Flat monthly rate, no contracts, half the price of the big IT firms — and we respond faster."*

---

## Go-to-Market

### Phase 1 — Pre-Launch (Before Move)
- [ ] Register domain: northshoreitsupport.com (Cloudflare Registrar, ~$10/yr)
- [ ] File LLC Articles of Organization (ilsos.gov, $150)
- [ ] Get E&O + Cyber Liability insurance quotes (~$150/mo combined)
- [ ] Set up Google Workspace business email (hello@northshoreitsupport.com)
- [ ] Draft standard service agreement / client contract
- [ ] Write Tailscale onboarding playbook (steps to set up new client)

### Phase 2 — First Clients (Month 1–3 in Skokie)
- [ ] Google Business Profile (free local SEO)
- [ ] Cold outreach: walk into 20–30 local law/accounting offices
- [ ] Tap wife's clinical network for warm intros
- [ ] Goal: 2 signed clients by end of Month 3

### Phase 3 — Scale (Month 4–12)
- [ ] Google Ads (~$200–400/mo): target "IT support Evanston", "IT help Skokie"
- [ ] Solicit Google reviews from happy clients
- [ ] Add psych/dental once HIPAA layer is ready
- [ ] Goal: 5+ clients, $1,500+/mo

### HIPAA Prep (Before Any Medical/Dental/Psych Client)
- [ ] Draft Business Associate Agreement (BAA) template
- [ ] Confirm Tailscale access is encrypted + logged (it is by default)
- [ ] Write data handling policy (1–2 pages)
- [ ] One-time consult with healthcare attorney (~$200–400)

---

## The Website

### Tech Stack
Plain HTML + CSS. No frameworks, no build tools, no npm. Intentional — easy to hand off, easy to deploy anywhere, zero dependencies. Two files:

- `index.html` — main one-page marketing site
- `privacy.html` — dedicated "Local First" page for the privacy package

### Running Locally
```bash
cd northshore-it
python3 -m http.server 8899
# Open http://localhost:8899
```

### Deployment (TODO)
Not yet deployed. Options in rough order of preference:
1. **Cloudflare Pages** — free, fast, deploys from this GitHub repo on push, includes CDN + HTTPS. Recommended.
2. **Netlify** — similar to Cloudflare Pages, also free tier
3. **GitHub Pages** — works fine for static HTML, already set up here
4. **Self-hosted** — only if Jack wants to eat his own cooking (running it on a mini-PC)

### Site Structure

**index.html — Main Site**
- Nav (fixed, dark navy)
- Hero — tagline, 4 stats (50% below market, <1hr response, $0 per-ticket, Local)
- Why North Shore IT — 6 value prop cards
- Services — full checklist of everything in the monthly retainer
- Pricing — 3 tier cards with market rate comparison
- Local First teaser — dark section linking to privacy.html
- Contact — email + hours + location
- Footer

**privacy.html — Local First Page**
- Hero — "Your data belongs in your building"
- The Problem — 4 cards on cloud/AI risks
- Hardware — Dell OptiPlex 3080 + Lenovo M920q specs, why we chose them
- Software Stack — Nextcloud, Vaultwarden, Pi-hole, encrypted backup, Matrix
- Pricing — $499 all-in with itemized breakdown
- FAQ — 4 questions for tech-averse clients
- CTA — links back to contact on main page

### Design Decisions
- Color scheme: dark navy (#0f1f3d) + blue (#2563eb) + white — professional, trustworthy, not "tech startup"
- Font: Inter (Google Fonts) — clean, readable, widely trusted
- No JavaScript — intentional, fast load, no attack surface
- Privacy page uses a red accent to convey urgency/risk without being alarming
- Pricing cards show market rate comparison — the savings are the product

---

## Key Decisions Log

| Decision | Choice | Reason |
|---|---|---|
| Business name | North Shore IT LLC | Local identity, immediate geographic trust signal, good SEO |
| Domain | northshoreitsupport.com | Only clean .com available for the brand; .org was available but wrong for a for-profit |
| Pricing model | Flat monthly per office size | Predictable for clients, no per-ticket nickel-and-diming |
| Micro tier price | $299/mo | Covers overhead (~$200/mo) + buffer; still ~50% below market |
| Access method | Tailscale (not raw SSH) | Encrypted, audited, easy to revoke, HIPAA-compatible |
| Privacy hardware | Dell OptiPlex 3080 / ThinkCentre M920q | Standardized = faster setup, easier maintenance; enterprise-grade, widely available |
| Backup strategy | Internal 5TB HDD + external 2TB | 3-2-1 approach; both drives included in $499 one-time package |
| No Ollama | Deferred | i5/16GB can't run LLMs at usable speed; revisit with GPU farm later |
| Target first | Lawyers/accountants | No HIPAA; easier compliance; still sticky, still pay well |
| Site framework | Plain HTML/CSS | Zero deps, easy to deploy, easy to hand off |

---

## Full Business Plan Doc
Lives at: `/hub/IT Business - North Shore.md`
(The Hub is a shared filesystem mounted at `/hub` — not in this repo)

---

*North Shore IT LLC — Skokie, IL*
*hello@northshoreitsupport.com*
