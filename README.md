<!--
  GitHub profile readme — github.com/alexanderpersson3/alexanderpersson3
  Auto-rendered at github.com/alexanderpersson3 as the profile homepage.
-->

# Alexander Persson

> Builder of AI + finance tools, plus Nordic SaaS and self-hosted infra.
> Stockholm-based.

[![GitHub](https://img.shields.io/badge/follow-alexanderpersson3-181717?logo=github&logoColor=white&style=flat)](https://github.com/alexanderpersson3)
[![Email](https://img.shields.io/badge/email-D14836?logo=gmail&logoColor=white&style=flat)](mailto:persson.aleksander@gmail.com)
![Location](https://img.shields.io/badge/Stockholm-Sweden-006AA7?logo=sweden&logoColor=FECC00&style=flat)

---

## Currently Working On — AI + Finance Portfolio

Six AI/finance systems. Each runs end-to-end on free public data; the
numbers in the right-hand column are from live runs.

| Repo | One-liner | Real demo output |
|---|---|---|
| [**ic-memo-copilot**](https://github.com/alexanderpersson3/ic-memo-copilot) | Citation-first SEC-filing memo agent with a two-stage audit gate (mechanical + LLM) | LLY FY2025 10-K → 23 claims, **0% unknown** after a v1→v4 iteration |
| [**relative-value-lab**](https://github.com/alexanderpersson3/relative-value-lab) | Pairs cointegration stat-arb with Bonferroni + BH-FDR correction, no look-ahead | Universe sweep: **2/15 survive FWER** (V/MA, JNJ/PFE) — the honest answer |
| [**private-credit-early-warning**](https://github.com/alexanderpersson3/private-credit-early-warning) | LM tone delta + FRED macro → ranked borrower watchlist | 6-issuer cohort, **rank-AUC 0.778** |
| [**nordic-deal-sourcing-graph**](https://github.com/alexanderpersson3/nordic-deal-sourcing-graph) | TED v3 procurement signal → ranked PE/corp-dev sourcing targets | Live SE: Peab #1 across 2,266 notices · Live NO: Matriks AS #1 |
| [**nordic-microstructure-lab**](https://github.com/alexanderpersson3/nordic-microstructure-lab) | Avellaneda-Stoikov MM + benchmark on synthetic + live Coinbase L2 | Inventory-skew unit-tested; honest about the calibration tension |
| [**family-office-intelligence**](https://github.com/alexanderpersson3/family-office-intelligence) | Fama-French 3-factor portfolio review + scenario engine + CIO memo | β_Mkt 0.60, R² 0.89, equity-drawdown-20% → −12.07% P&L |

**Featured writing** — [LLY long / PFE short, a GLP-1 thesis](https://github.com/alexanderpersson3/ic-memo-copilot/blob/main/docs/sample-thesis-LLY-PFE.md). A worked investment opinion built on the IC Memo Copilot's output: named position, sized, catalysts, stop.

---

## The Wider Stack

Outside the finance portfolio, ~100 private repos. A sampler:

| Domain | Examples |
|---|---|
| **Production SaaS** | [Rezepta](https://rezepta.app) (Next.js + Supabase recipe/meal-planning) · Tegner wine-import monorepo · Mixpost SaaS (PHP, Phase-3 multi-tenant admin) |
| **Self-hosted infra** | Mailcow email platform (control plane) · Hetzner clusters · Cloudflare R2/Workers · Docker compose stacks |
| **Swedish accounting infra** | K2 årsredovisning + INK2 declaration (SIE4 → iXBRL → Bolagsverket pipeline) · Bokio integration · Bolagsverket API clients |
| **Mobile** | Rezepta Mobile (Flutter) · OpenNutriTracker (Dart, AI-powered) · Kegg (SwiftUI iOS/macOS) |
| **Data + AI scrapers** | Recipe scraper (11,553+ recipes × USDA enrichment) · Pyfinviz insider-trading API · SAS EuroBonus deal crawler · Matprishistorik (Swedish food-price tracking) |
| **IoT / hardware** | JetCup — digital *pantsystem* (IoT bottle-deposit-return system) |

---

## Tech I'm Using Right Now

### Quant / Finance Stack

![Python](https://img.shields.io/badge/Python-3.12-3776AB?logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?logo=pandas&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?logo=scipy&logoColor=white)
![statsmodels](https://img.shields.io/badge/statsmodels-blueviolet)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikit-learn&logoColor=white)
![matplotlib](https://img.shields.io/badge/matplotlib-11557C)
![pydantic](https://img.shields.io/badge/pydantic-E92063?logo=pydantic&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?logo=pytest&logoColor=white)
![Click](https://img.shields.io/badge/Click-CLI-blueviolet)

**Data sources:** SEC EDGAR · FRED · Kenneth French Library · TED v3 ·
Coinbase REST · Yahoo Finance · Loughran-McDonald finance lexicon · XBRL.

### LLM / AI Engineering

![Anthropic](https://img.shields.io/badge/Anthropic_Claude-D4A373?logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?logo=openai&logoColor=white)
![DeepSeek](https://img.shields.io/badge/DeepSeek-3776AB)
![Google Gemini](https://img.shields.io/badge/Google_Gemini-4285F4?logo=google&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)

**Patterns I rely on:** prompt caching, two-stage audit gates (mechanical
substring + LLM semantic), structured output via JSON-mode + Pydantic
validation, provider-agnostic abstraction layers (Anthropic ↔ DeepSeek
swap behind one interface), claim-level citation discipline.

### Frontend / Full-Stack Web

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?logo=next.js&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?logo=tailwindcss&logoColor=white)
![Convex](https://img.shields.io/badge/Convex-FF6B6B)
![Shopify](https://img.shields.io/badge/Shopify-7AB55C?logo=shopify&logoColor=white)
![MDX](https://img.shields.io/badge/MDX-1B1F24?logo=mdx&logoColor=white)

### Mobile

![Swift](https://img.shields.io/badge/Swift-F05138?logo=swift&logoColor=white)
![SwiftUI](https://img.shields.io/badge/SwiftUI-006AFE?logo=swift&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?logo=dart&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?logo=flutter&logoColor=white)

### Backend & Data

![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?logo=node.js&logoColor=white)
![Ruby](https://img.shields.io/badge/Ruby-CC342D?logo=ruby&logoColor=white)
![Rails](https://img.shields.io/badge/Rails-CC0000?logo=rubyonrails&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?logo=php&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?logo=supabase&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white)

### Infra & Ops

![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Hetzner](https://img.shields.io/badge/Hetzner_Cloud-D50C2D)
![DigitalOcean](https://img.shields.io/badge/DigitalOcean-0080FF?logo=digitalocean&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?logo=cloudflare&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?logo=vercel&logoColor=white)
![Mailcow](https://img.shields.io/badge/Mailcow-self--hosted-blueviolet)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=github-actions&logoColor=white)

### Swedish Operator Specifics

![Bolagsverket](https://img.shields.io/badge/Bolagsverket-API-yellow)
![SIE4](https://img.shields.io/badge/SIE4-accounting-006AA7)
![iXBRL](https://img.shields.io/badge/iXBRL-årsredovisning-006AA7)
![Bokio](https://img.shields.io/badge/Bokio-integration-blue)
![FRED](https://img.shields.io/badge/FRED-macro_data-005DAA)

---

## Ask Me About

- LLM pipelines that don't hallucinate quotes — two-stage audit gates, prompt caching, structured output
- Stat-arb without look-ahead — the `.shift(1)` discipline, plus multiple-testing correction on universe sweeps
- LM-based disclosure tone for credit monitoring, including where it misses PR-managed disclosure
- Public-data target ranking for PE / corp-dev — TED v3 procurement-momentum and the Nordic entity-resolution gotchas
- The Avellaneda-Stoikov calibration tension — why textbook γ/k usually loses to a constant-spread benchmark on synthetic data
- Self-hosted email at scale — Mailcow + AWS SES
- Swedish accounting infra — SIE4 → iXBRL → Bolagsverket end-to-end, K2 årsredovisning automation, Bokio integration

## How to Reach Me

GitHub DM or open an issue on any of the repos. Stockholm-based.

If one of the repos overlaps something you work on, I'd be interested
to hear how you approach it.

<!--
  Setup reminders for whenever you have 5 min:
  1. Pin the 6 portfolio repos to the profile (Customize your pins in the UI)
  2. Add LinkedIn URL to the Reach Me section above (currently absent)
  3. Optional: add a banner GIF of the LLY memo iteration trajectory or the V/MA equity curve
  4. Optional: github-readme-stats card showing top languages — but only if you want the public TypeScript/Python split visible, since the AI-finance portfolio is Python-heavy
-->
