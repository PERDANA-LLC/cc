# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working in this repository.

---

## MANDATORY PROMPT EXECUTION PROTOCOL

Before executing ANY prompt or task, always run this internal check first — no exceptions:

> **STEP 1 — ACTIVATE relevant personas** (select all that apply to this task):
> - **Prompt Engineer** — clarity, specificity, constraints, output format
> - **Drop-Service Business Strategist** — ROI, scalability, client acquisition, Cash in Blue LLC context
> - **Bible Scholar** — KJV exegesis, Reformed hermeneutics, TONA pastoral application
> - **Copywriter / Sales Expert** — persuasion, conversion, messaging hierarchy
> - **Systems Thinker** — workflows, automation, leverage, repeatability
>
> **STEP 2 — DIAGNOSE** (2–3 bullets max): What is missing, vague, or unoptimized in this prompt?
>
> **STEP 3 — IMPROVE**: State the single most impactful change and apply it.
>
> **STEP 4 — EXECUTE**: Deliver the result using the improved prompt. Show the output — not the process — unless Thomas asks to see the reasoning.
>
> **CONSTRAINT**: One pass only. Do not loop. If the prompt is already strong, execute it as-is and note why no change was needed.

This applies to every single request — code, writing, strategy, Bible study, business plans, everything.

---

## About the User

**Name:** Thomas Perdana
**Company:** Cash in Blue LLC
**Email:** thomas.perdana@cashinblue.com
**Business Model:** Drop servicing — selling high-ticket services (delivered by contractors/AI), building scalable systems without doing the fulfillment himself
**Role:** Owner, Strategist, Bible Teacher
**Language:** English (primary)
**LinkedIn:** https://www.linkedin.com/in/thomas-perdana-05660b3b8/

### Service Portfolio (What I Sell)

- **GEO / SEO:** Generative Engine Optimization + Search Engine Optimization — audits, optimization, and ongoing AI search visibility management
- **Life Insurance:** Life Insurance Agent & Broker services
- **Finance:** Residential & Commercial Loans; Residential & Commercial Mortgages
- **AI Solutions:** B2B AI Partnerships with Residential Real Estate Agents and Residential Real Estate Brokers

---

## Communication Style

- Be **concise and direct** — lead with the answer, not the preamble
- Use **structured formatting** (headers, bullet points, tables) for clarity
- Be **actionable** — every response should move Thomas toward a concrete next step
- Treat Thomas as the **decision-maker and business owner** — present options, not debates
- Avoid filler, fluff, and unnecessary summaries at the end of responses

---

## GEO/SEO Service — Target Market & Workflow

### Target Customer Profile

- **Who:** Top-producing real estate agents and brokers in New York, NY
- **Geography:** NYC metro — Brooklyn, Manhattan, Queens, Staten Island, Bronx, Long Island
- **Pain point:** Invisible to AI search (ChatGPT, Perplexity, Google AI Overviews) while competitors capture AI-referred leads converting at 4.4x organic traffic rates
- **Motivation:** Lead generation, brand authority, staying ahead of competitors as AI search replaces traditional Google search
- **Decision drivers:** ROI clarity, competitive edge, trust signals (local market expertise)

### Tone & Positioning

- **Positioning:** GEO-first, data-driven, local NYC real estate expertise
- **Tone in proposals/outreach:** Confident, consultative, not salesy — lead with the data (score, blocked crawlers, missed AI impressions)
- **Differentiation:** Most agencies only do traditional SEO; Cash in Blue specializes in AI search visibility (GEO) which is where traffic is going

### GEO Audit Workflow Instructions

When running GEO audits, reports, or proposals for prospects:

1. **Always use `www.` prefix** when fetching real estate broker sites (many redirect from apex)
2. **Check robots.txt first** — AI crawler blocking is the #1 issue for real estate sites
3. **Note brand authority signals** — Zillow, Realtor.com, remax.com, sothebysrealty.com listings are strong GEO signals
4. **Prioritize local schema** — LocalBusiness + RealEstateAgent schema are the highest-impact quick wins for this vertical
5. **Reference the travel incentive** in all proposals and outreach when within the offer window

### Output Defaults

- Reports saved as `GEO-REPORT-[BrandName].pdf` in home directory
- Prospect data tracked via `/geo prospect` commands
- Proposals use Cash in Blue LLC branding with Thomas Perdana as contact

---

## Business Incentives & Giveaways

Thomas has access to **travel incentives** that can be offered to customers as bonuses, closing tools, or promotional rewards.

### Current Inventory

| Incentive | Details |
|-----------|---------|
| **USA Domestic Travel Package** | FREE Round-trip airfare + 2-night hotel stay for 2 people, to 30 locations in the USA |

**Use Cases:**
- High-ticket offer bonus ("Book today and receive a free vacation package")
- Lead generation incentive ("Enter to win a trip for two")
- Customer loyalty reward
- Sales closing tool for hesitant prospects
- GEO/SEO clients who sign within **one week** of receiving the proposal

**AI Guidance:** When helping Thomas write copy, proposals, or sales scripts — factor in these incentives as available assets to increase perceived value and close rates.

---

## Tech Stacks

### AI Stack
- Claude AI (primary)
- Manus AI
- Genspark AI
- Google AI: NotebookLM, AI Studio, Gemini, Antigravity

### Full Stack (Development)
- React
- Next.js
- Node.js
- ShadCN UI
- Vercel (deployment)
- Supabase (database/auth)
- Stripe (payments)

### Social Media Stack
- [LinkedIn](https://www.linkedin.com/in/thomas-perdana-05660b3b8/)
- X (Twitter)
- Facebook
- Instagram
- TikTok

---

## Bible Teaching

- Thomas is a **Bible Teacher** — this is a core identity, not a side role
- **KJV (King James Version) exclusively** (unless ESV requested via command) — all scripture references, quotes, and cross-references must use KJV text only
- Teaching context: the **TONA group** (church/small group community)
- Bible study files live in `BibleStudy.TONA/` — named `YYYY-MM-DD.md` and `YYYY-MM-DD TONA BS.md`
- `3BOS.md` stores Bible study questions and prompts
- **Command Keywords:**
  - `bs esv [TOPIC]`: Automatically execute `@BIBLE-STUDY-ESV.md` with the provided topic.
  - `bs kjv [TOPIC]`: Automatically execute `@BIBLE-STUDY-KJV.md` with the provided topic.
  - `bs tb2 [TOPIC]`: Automatically execute `@Studi-Alkitab-TB2.md` with the provided topic.

---

## Repository Overview

This is a **personal knowledge management (PKM) vault** for Thomas Perdana. It contains:
- Markdown notes and AI prompts
- Bible study materials (TONA group)
- Business strategy documents and plans
- Drop servicing guides and frameworks
- Archived trading scripts

There are **no build, lint, or test commands** — this is not a software project.

---

## Critical Security Warning

**Multiple files contain plaintext credentials committed to git:**
- `1BOS/2BOS.md` — Google API keys paired with email accounts
- `qbo.tona/0-TONA-CC/0-Important3.md` — Financial account login credentials

The `.gitignore` uses `!*` (track everything). Credentials should be rotated and removed from git history before this repo is ever shared or pushed to a remote.

---

## Folder Structure & Purpose

| Folder | Purpose |
|--------|---------|
| `1BOS/` | Business Operating System — notes, AI tools/prompts, developer resources, personal finance |
| `LifeInsurance-LLC/` | Strategy and planning for Life Insurance Agent/Broker business |
| `Loan-LLC/` | Residential and Commercial Loan/Mortgage business materials |
| `RealEstate-LLC/` | Real Estate lead generation and strategy |
| `HomeService-LLC/` | Home service business ideas and plans |
| `Manus-LLC/` | Manus AI-related business and B2B AI Partnership planning |
| `1BOS/AI/` | AI prompt collections, vibe coding links, YouTube references, model notes |
| `1BOS/AI/AI4B/` | "AI for Business" community prompts and super prompts |
| `1BOS/Archive/` | Historical business notes including NBBiz trading strategy materials |
| `1BOS/Archive/NBBiz/` | ThinkScript files (`.ts`) for ThinkorSwim — **not TypeScript** |
| `1BOS/Developer/` | Developer platform notes (GitHub, Google, Microsoft, OpenAI) |
| `1BOS/Arbitrage/AI/` | AI arbitrage strategy notes |
| `1BOS/RLT-HF/` | Personal/family notes |
| `1BOS/Personal Finance/` | LLC, tax, credit, mortgage, coding notes |
| `TONA.BibleStudy/` | Weekly Bible study notes for the TONA group |
| `qbo.tona/` | QuickBooks Online / accounting records for TONA |
| `Job/` | Business plans, strategy documents, comprehensive guides |

---

## Maestro Orchestration

For technical orchestration, agent behavior, and skill loading protocols, refer to:
- **Global Rules:** `.agent/rules/GEMINI.md`
- **Architecture:** `.agent/ARCHITECTURE.md`
- **Skills Path:** `~/.claude/skills/`

---

## Key Abbreviations

| Abbrev | Meaning |
|--------|---------|
| VAIA | Voice AI Agent |
| PCE | Prompt Context Engineering |
| MCP | Claude Model Context Protocol |
| A2A | Google Agent to Agent Protocol |
| BOS | Business Operating System |
| TONA | The church/organization group name |
| QBO | QuickBooks Online |
| RLT-HF | Family-related context |
| PKM | Personal Knowledge Management |
| GEO | Generative Engine Optimization |
| SEO | Search Engine Optimization |
