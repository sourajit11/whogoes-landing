# WhoGoes.co — SEO, Pricing & Business Launch Advisory

## Context
WhoGoes sells event/tradeshow attendee intent data with LinkedIn post proof. The landing page at `whogoes.co` currently uses "Exhibition Intent Data" as the primary keyword. The founder wants to evaluate SEO-friendliness, optimize for better keywords, revise pricing, and get business launch advice.

Source file: `/Users/sourajitshantikari/Research/Whogoes/index.html`

---

## 1. SEO Analysis — Is "Exhibition Intent Data" the Right Keyword?

**Short answer: No.** "Exhibition intent data" is too niche. Very few people search for that exact phrase.

### What People Actually Search For (ranked by search volume & commercial intent)

| Keyword Cluster | Why It's Better |
|---|---|
| **"tradeshow attendee list"** / "buy tradeshow attendee list" | High commercial intent — people are ready to pay |
| **"trade show lead generation"** / "event lead generation" | Broader, high-volume B2B keyword |
| **"conference attendee data"** | Covers the conference market (huge) |
| **"event visitor data"** / "event attendee data" | Catch-all for all event types |
| **"trade show leads"** | Short, high-volume, direct intent |
| **"who is attending [event name]"** | Long-tail, very high intent — people Google this! |

### Recommended Hero Headline Strategy

**Current:** `[Event/Exhibition/Trade show/Conference] intent data. With proof.`

**Recommended:** Change the rotating words AND the static text to target higher-volume keywords:

```
Find [Trade Show / Conference / Event / Exhibition] Attendees
Before the event starts.
```

Or even better for SEO:

```
Trade Show & Event Attendee Data — With Proof
Know who's going before you go.
```

**Why:** "Attendee data" and "attendees" are what buyers search for, not "intent data" (which is B2B jargon from Bombora/6sense). Your buyers are sales teams and marketers who think in terms of "attendee lists" and "who's going."

### Recommended Title Tag & Meta Description

**Current title:** `WhoGoes — Event Intent Data With Proof`
**Recommended:** `WhoGoes — Trade Show & Event Attendee Data With Proof`

**Current meta:** Good, but could be keyword-richer.
**Recommended:** `Find verified trade show, conference & event attendees with LinkedIn proof. Browse 1,200+ events free. Get names, emails & companies — pay only for contacts you want.`

---

## 2. Other SEO Improvements for the Landing Page

### Critical Issues

1. **No `<h2>` keyword optimization** — Section headings like "Browse events. See real contacts." are catchy but not keyword-rich. Add secondary keywords like "trade show attendee list" or "event lead generation" into H2s.

2. **No schema markup** — Add FAQPage schema (you already have FAQ content!) and Organization schema. Pages with schema get **25-40% higher CTR** in search results.

3. **Tailwind CDN in production** — `<script src="https://cdn.tailwindcss.com">` is meant for development only. This adds ~300KB of JS and hurts page speed. Pre-compile Tailwind to a static CSS file.

4. **No canonical URL** — Add `<link rel="canonical" href="https://whogoes.co/">` to prevent duplicate content issues.

5. **No Open Graph / Twitter meta tags** — Critical for social sharing (your users come from LinkedIn!). Add `og:title`, `og:description`, `og:image`, `twitter:card`.

6. **No sitemap.xml or robots.txt** — Even for a single-page site, these help Google crawl properly.

7. **No alt text on images** — There are no images currently, but the dashboard mockup section could benefit from a real screenshot `<img>` with alt text for image search.

8. **Internal linking is weak** — All links go to `app.whogoes.co`. Consider adding a blog at `whogoes.co/blog` to build topical authority around keywords like "trade show lead generation tips", "how to find event attendees", etc.

9. **Footer links are dead** — Privacy Policy, Terms of Service, GDPR Compliance all point to `#`. Google sees these as low-quality signals.

10. **Contact email is wrong** — Footer says `hello@whogoes.com` but domain is `whogoes.co`. Fix to match.

### Quick Wins (High Impact, Low Effort)

| Action | Impact |
|---|---|
| Add FAQPage schema markup (JSON-LD) | +25-40% CTR from search |
| Fix title tag to include "Trade Show" | Better keyword targeting |
| Replace Tailwind CDN with compiled CSS | 2-3x faster page load |
| Add canonical URL | Prevents duplicate content |
| Add OG meta tags | Better LinkedIn/social sharing |
| Add `robots.txt` + `sitemap.xml` | Proper crawling |
| Create a blog section | Long-term organic traffic engine |

### Content Pages to Create (for SEO long-tail)

Each of these could be a separate page or blog post:
- `/events/ces-2026` — individual event pages rank for "[event name] attendees"
- `/blog/trade-show-lead-generation-guide`
- `/blog/how-to-find-conference-attendees`
- `/blog/event-attendee-data-vs-intent-data`
- `/compare/whogoes-vs-bombora`
- `/compare/whogoes-vs-6sense`

---

## 3. Pricing Recommendation

### Your Proposed Pricing

| Tier | Credits | Per Credit |
|---|---|---|
| $10 | 100 | $0.10 |
| $50 | 750 | $0.067 |
| $100 | 2,000 | $0.05 |

### Current Landing Page Pricing

| Tier | Credits | Per Credit |
|---|---|---|
| Free | 20 | $0 |
| $1 | 20 | $0.05 |
| $5 | 100 | $0.05 |
| $20 | 400 | $0.05 |

### Market Context

- **VisitorsList** (direct competitor): Minimum $5,000 per project
- **Bombora**: $25K/year contracts
- **6sense**: $50K/year contracts
- **Leadfeeder**: $99-$1,199/month
- **RB2B**: $1,000/month for 10K visitors
- **Instantly.ai lead finder**: $47-$197/month
- **Trade show CPL industry average**: $112/lead
- **General B2B lead cost**: $40-$300/lead

### My Recommendation

Your proposed pricing ($0.05-$0.10/contact) is **extremely cheap** relative to the market. A verified trade show attendee with email and LinkedIn proof is worth $1-$5 per contact minimum.

**Recommended pricing tiers:**

| Tier | Credits | Per Credit | Discount |
|---|---|---|---|
| Starter | Free | 20 credits | $0 (trial) |
| $29 | 200 | $0.145 | — |
| $79 | 750 | $0.105 | 28% off |
| $149 | 2,000 | $0.075 | 48% off |

**Why higher than your proposal:**
1. Industry CPL for trade shows is $112. Even at $0.15/contact, you're 700x cheaper.
2. Your unique value (LinkedIn proof + individual contact) is worth a premium over raw attendee lists.
3. You can always lower prices. Raising them later is harder.
4. Higher prices = perceived higher quality. At $0.05/contact, buyers may question data quality.
5. The volume discount on higher tiers drives upsell behavior.

**Alternative: Keep it simple with 2 tiers:**

| Tier | Price |
|---|---|
| Free | 20 credits |
| Credits | $0.10 each (buy any amount) |

---

## 4. Business Launch Strategy

### Who WhoGoes Is For (Target Personas)

**Primary (start here):**
1. **SDR/BDR teams at B2B SaaS companies** — They prospect before events, need attendee lists for pre-event outreach. They already use tools like Apollo, Instantly, ZoomInfo.
2. **Field marketers / event marketers** — Responsible for maximizing event ROI. They need to book meetings before the booth opens.

**Secondary (expand later):**
3. **Sales leaders at companies that exhibit at trade shows** — Budget holders who pay $20K-$100K for a booth but have no pre-event prospecting strategy.
4. **Agencies running outreach for clients** — Lead gen agencies, SDR-as-a-service firms.
5. **Recruiters** — People attending industry events are often open to conversations.

### Who to Target First

**Start with SDRs and sales reps who are active on LinkedIn.** Why:
- They already understand the value of event-based prospecting
- They can buy with a credit card (no enterprise sales cycle)
- They share tools on LinkedIn (viral growth potential)
- Low price point = no procurement approval needed

### Go-to-Market Channels (Ranked by Priority)

1. **LinkedIn organic content** — Post about specific upcoming events (e.g., "CES 2026 is in 3 weeks. We've already found 2,847 people who posted about attending. Here's what we found..."). This is free and hyper-targeted.

2. **Cold outreach to SDRs/AEs** — Use your own tool! Find people posting about attending events, then reach out: "I noticed you're attending [event]. We built a tool that finds everyone else who posted about going. Want to see the list?"

3. **Product Hunt launch** — Great for early traction with tech-savvy buyers.

4. **LinkedIn Ads** — Target by job title (SDR, BDR, Sales Development, Field Marketing) + company size (50-5000 employees).

5. **SEO/Content marketing** — Write comparison pages (WhoGoes vs Bombora), event-specific guides, trade show prospecting playbooks. This compounds over time.

6. **Partnerships** — Integrate with Instantly.ai, Apollo, Clay, Smartlead. "Export to [tool]" button = distribution through their ecosystems.

### Direct Competitors

| Competitor | What They Do | Pricing | WhoGoes Advantage |
|---|---|---|---|
| **VisitorsList** | Sells bulk attendee/exhibitor email lists | $5,000+ per project | 100x cheaper entry point, self-serve, LinkedIn proof |
| **ExhibiTrac** | 750K+ exhibitor database | Custom pricing | You have attendees (not just exhibitors), with proof |
| **ExpoCaptive** | Trade show attendee lists | Custom pricing | Self-serve, instant access, pay-per-contact |
| **BuyersContacts** | Bulk attendee lists (43yr old company) | Custom pricing | Modern UX, individual proof, no sales process |
| **Bombora** | Account-level web browsing intent | $25K/year | Individual contacts (not accounts), visible proof, 1000x cheaper |
| **6sense** | Account-level intent + ABM | $50K/year | Same as Bombora — individual + proof + cheap |
| **Swapcard/Grip/Bizzabo** | On-site lead capture at events | Per-event licensing | You work BEFORE the event, not during |

### WhoGoes Unique Position

**No one else does exactly what you do.** The competitive landscape breaks into:
- **Enterprise intent platforms** (Bombora, 6sense) — Account level, no proof, $25K-$50K+
- **Bulk list sellers** (VisitorsList, ExpoCaptive) — No proof, no self-serve, $5K+ minimums
- **On-site lead capture** (Swapcard, Bizzabo) — Only works during the event, not before

**WhoGoes is the only tool that:**
1. Provides individual-level attendee data (not account-level)
2. Includes LinkedIn post as verifiable proof
3. Works BEFORE the event (pre-event prospecting)
4. Is self-serve with pay-per-contact pricing
5. Has a free preview (no signup required)

### Business Potential

**Market size indicators:**
- U.S. trade show market: **$15.8B** (2024), growing to $17.3B by 2028
- Global exhibition market: **$66.3B**, projected $95.5B by 2031
- 13,000+ trade shows per year in the U.S. alone
- 82% of attendees have buying authority
- 72% of exhibitors cite lead gen as #1 reason to attend
- **94% of marketers say they fail to convert event leads** (your gap to fill)

**Revenue potential (conservative):**
- If 500 users buy $29/month average = **$174K ARR**
- If 2,000 users buy $50/month average = **$1.2M ARR**
- If you capture just 0.1% of the $15.8B trade show market = **$15.8M**

**Key growth lever:** Every new event you add creates a new keyword target ("CES 2026 attendees", "HIMSS 2026 attendees") and a new market of potential buyers.

---

## 5. Summary of Recommended Actions

### Immediate (This Week)
1. Update hero headline keywords: "Exhibition Intent Data" → "Trade Show & Event Attendee Data"
2. Fix title tag and meta description for SEO
3. Add FAQPage schema markup
4. Add OG/Twitter meta tags (critical for LinkedIn sharing)
5. Fix dead footer links and wrong email address
6. Add canonical URL

### Short-Term (This Month)
7. Replace Tailwind CDN with compiled CSS
8. Update pricing to the recommended tiers ($29/$79/$149)
9. Add robots.txt and sitemap.xml
10. Create 2-3 comparison pages (vs Bombora, vs 6sense)
11. Start posting on LinkedIn about upcoming events

### Medium-Term (Next 2-3 Months)
12. Launch individual event SEO pages (`/events/ces-2026`)
13. Start a blog for long-tail keyword content
14. Product Hunt launch
15. Build CSV export and CRM integrations
16. Start cold outreach to SDR teams using your own data

---

## Verification
- Review keyword changes against Google Search Console after deployment
- Test page speed with Lighthouse before/after Tailwind CDN removal
- Validate schema markup at https://validator.schema.org/
- Check OG tags with https://www.opengraph.xyz/
