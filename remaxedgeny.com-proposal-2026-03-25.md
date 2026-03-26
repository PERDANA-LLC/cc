# GEO Visibility Proposal
## RE/MAX Edge — Brooklyn & Staten Island, NY
**Prepared by:** Thomas Perdana, Cash in Blue LLC
**Contact:** thomas.perdana@cashinblue.com
**Date:** March 25, 2026
**Prepared for:** Michael Napolitano, Broker/Owner

---

## The Problem: You're Invisible Where Buyers Are Looking

Right now, when a buyer in Brooklyn opens ChatGPT, Perplexity, or Google AI Overviews and searches:

> *"Who are the top real estate brokerages in Brooklyn?"*
> *"Best RE/MAX agent in Brooklyn NY"*
> *"Real estate agent near me in Bay Ridge"*

**RE/MAX Edge does not appear.**

Not because you're not the best. You are. You're the **#1 brokerage in the Brooklyn MLS** with **2,603 five-star Zillow reviews** and a **2024 Inman Power Broker Award**.

You don't appear because your website is **actively blocking every AI search engine on the internet** from reading it.

One file. One setting. Completely blocking ChatGPT, Perplexity, Google Gemini, and Claude from ever indexing your site.

---

## The AI Search Reality (2026)

| Platform | Monthly Users | Conversion Rate vs Google |
|----------|--------------|--------------------------|
| Google AI Overviews | 1.5 billion | 4.4x higher |
| ChatGPT Web Search | 900 million | 4.4x higher |
| Perplexity AI | 500 million+ | 4.4x higher |
| Bing Copilot (Microsoft) | 250 million+ | 4.4x higher |

**AI-referred traffic converts at 4.4x the rate of traditional organic search** (SparkToro, 2025).

AI search grew **527%** in the first 5 months of 2025 alone.

Gartner projects traditional Google search traffic will drop **50% by 2028** as AI answers replace click-throughs.

**Only 23% of businesses have taken any action on AI search optimization.**

Your competitors haven't either. This is your window.

---

## Your Current GEO Score: 34/100

We audited remaxedgeny.com using our proprietary GEO analysis framework across 5 parallel analysis tracks.

| Category | Weight | Your Score | Industry Avg |
|----------|--------|-----------|--------------|
| AI Citability & Visibility | 25% | **19/100** | 41/100 |
| Brand Authority Signals | 20% | **48/100** | 38/100 |
| Content Quality & E-E-A-T | 20% | **47/100** | 45/100 |
| Technical Foundations | 15% | **38/100** | 52/100 |
| Structured Data | 10% | **8/100** | 29/100 |
| Platform Optimization | 10% | **34/100** | 31/100 |
| **Overall GEO Score** | | **34/100** | **40/100** |

### AI Platform Readiness

| Platform | Your Score | What It Means |
|----------|-----------|---------------|
| Google AI Overviews | 38/100 | Rarely cited |
| Google Gemini | 42/100 | Partially visible via Google Business Profile |
| Perplexity AI | 32/100 | Not indexed — bot blocked |
| ChatGPT Web Search | 30/100 | Not indexed — bot blocked |
| Bing Copilot | 28/100 | Severely throttled (120s crawl delay) |

---

## The Root Cause: One Line in One File

Your robots.txt — the file that tells search engines what they can and can't read — ends with this:

```
User-agent: *
Disallow: /
```

This means: **"Block everyone not on the whitelist."**

None of these AI crawlers are on your whitelist:

| AI System | Crawler Bot | Status |
|-----------|------------|--------|
| ChatGPT (OpenAI) | GPTBot | BLOCKED |
| Claude (Anthropic) | ClaudeBot | BLOCKED |
| Perplexity | PerplexityBot | BLOCKED |
| Google AI Overviews | Google-Extended | BLOCKED |
| Google Gemini | GoogleOther | BLOCKED |
| TikTok AI | Bytespider | BLOCKED |
| DuckDuckGo AI | DuckAssistBot | BLOCKED |
| Apple AI | Applebot-Extended | BLOCKED |

**Fix:** A developer adds 8 lines to one text file. Under 30 minutes. Zero cost except developer time.

This single fix unlocks your ability to appear in AI search results for the first time.

---

## What We'll Deliver

### Phase 1 — Foundation (Week 1-2)
*The technical unlocks. Immediate AI crawl access.*

**1. robots.txt Repair**
- Add explicit Allow rules for all 8 major AI crawlers
- Reduce Bingbot crawl delay from 120s → 10s
- Estimated impact: Site becomes crawlable by all AI engines within 48-72 hours of implementation

**2. Cloudflare Bot Access**
- Enable "Known Bots" verified bot allowlisting in your Cloudflare WAF
- Stops serving JavaScript challenge pages to AI crawlers and SEO audit tools
- 10-minute toggle in Cloudflare dashboard

**3. JSON-LD Schema Implementation**
- RealEstateAgent + LocalBusiness schema for both Brooklyn and Staten Island locations
- Full NAP (Name, Address, Phone) machine-readable markup
- sameAs links connecting your site to Zillow, remax.com, LinkedIn, Facebook
- Person schema for Michael Napolitano (Broker/Owner) with credential linkage
- WebSite + SearchAction schema for sitelinks search box eligibility
- Estimated impact: Google and AI engines can now identify and verify RE/MAX Edge as an entity

**4. llms.txt Creation**
- A structured, AI-readable summary of your brokerage at remaxedgeny.com/llms.txt
- Adopted by ChatGPT and Perplexity as a direct readability standard
- Describes: who you are, what areas you serve, your rankings, key agents, and key pages

**Projected score after Phase 1: 58-65/100**

---

### Phase 2 — Authority (Month 1-2)
*The content that gets you cited.*

**5. FAQPage Schema + Content**
- 10 question-answer pairs targeting high-intent Brooklyn real estate queries
- Schema-marked for Google AI Overviews and Bing Copilot
- Examples:
  - *"What is the best real estate brokerage in Brooklyn?"*
  - *"How much does it cost to sell a home in Brooklyn NY?"*
  - *"Who is the #1 RE/MAX agent in Brooklyn?"*
  - *"What neighborhoods does RE/MAX Edge serve?"*

**6. About Page Rebuild**
- Michael Napolitano's full credential stack: Inman Power Broker 2024, #30 RE/MAX nationally, 17+ years, NY State Licensed LLC Broker (#10491207598)
- Brokerage founding story and market philosophy
- Named agent roster with individual bios and MLS specializations
- Embedded Zillow review widget (2,603 reviews, 5 stars)

**7. Monthly Brooklyn Market Report**
- Original MLS-sourced data: median sale price, days on market, list-to-sale ratio
- Published monthly with sourced statistics
- This is the single highest-value content type for AI citation — AI systems preferentially cite sources with original, proprietary data

**Projected score after Phase 2: 68-74/100**

---

### Phase 3 — Domination (Month 3-6)
*The compounding signals that lock in market leadership.*

**8. LinkedIn Company Page Buildout**
- Weekly market update posts
- Complete all profile fields with keyword-rich descriptions
- Employee connections and endorsements
- Target: 2,000+ followers (currently: 440)

**9. YouTube Channel Launch**
- 10 Brooklyn neighborhood tour videos
- Monthly Brooklyn market update videos
- Agent spotlight videos
- YouTube feeds Google Gemini's multi-modal AI sourcing — currently your biggest missing signal

**10. Reddit Authority Building**
- Authentic participation in r/Brooklyn and r/NYCRealEstate
- Data-backed responses referencing your MLS statistics
- Reddit is Perplexity's #1 community validation source

**11. IndexNow Implementation**
- Instant Bing notification on every new listing or content publish
- Eliminates the crawl delay gap that currently throttles Bing Copilot

**Projected score after Phase 3: 78-84/100**

---

## Your Competitive Advantage

You have something most competitors don't: **documented, verifiable authority.**

- **2,603 Zillow reviews at 5 stars** — the highest review count we've seen for a NYC brokerage
- **#1 Brooklyn MLS** — not a claim, a verifiable market ranking
- **#30 nationally at RE/MAX** — quantified national standing
- **2024 Inman New York Power Broker Award** — credible industry recognition
- **17+ years** broker/owner experience — tenure that competitors can't match

Right now, AI systems can't reach any of this. Once we fix that, this authority becomes your unfair competitive advantage in AI search — the same way it already is in traditional search.

---

## Investment

### Recommended Package: GEO Foundation + Authority

| Phase | Deliverables | Investment |
|-------|-------------|-----------|
| **Phase 1 — Foundation** | robots.txt, Cloudflare, Schema, llms.txt | **$1,497** |
| **Phase 2 — Authority** | FAQ schema, About rebuild, Market reports (3 months) | **$2,497/mo** |
| **Phase 3 — Domination** | LinkedIn, YouTube, Reddit, IndexNow | **$1,997/mo** |

**Most clients start with Phase 1 only** to see results before committing to ongoing work. Phase 1 is a one-time implementation — the ROI is immediate and permanent.

### Starter Option: Phase 1 Only
- robots.txt + Cloudflare fix
- Full JSON-LD schema (both locations)
- llms.txt creation
- **One-time: $1,497**
- **Results visible within 2 weeks**

---

## Book This Week — Receive a Complimentary Travel Incentive

As a thank-you for signing within **7 days of receiving this proposal**, Cash in Blue LLC will include a complimentary:

> **USA Domestic Travel Package**
> FREE Round-trip airfare + 2-night hotel stay for 2 people
> 30 destinations across the United States
> Valued at $500+

This offer expires **April 1, 2026.**

---

## Why Cash in Blue LLC

- **GEO-first agency** — we specialize in AI search visibility, not traditional SEO
- **Local market expertise** — we understand the NYC real estate landscape and what buyers are searching for
- **Data-driven** — every recommendation is backed by audit data, not assumptions
- **Fast implementation** — Phase 1 complete within 2 weeks of engagement
- **Transparent reporting** — monthly GEO score tracking so you see exactly what's improving

---

## Next Step

Reply to schedule a 20-minute call to walk through the audit findings and answer any questions.

**Thomas Perdana**
Cash in Blue LLC
thomas.perdana@cashinblue.com
[LinkedIn](https://www.linkedin.com/in/thomas-perdana-05660b3b8/)

---

*This proposal is based on a live GEO audit of remaxedgeny.com conducted on March 25, 2026. All scores and findings reflect the site's current state as of that date.*
