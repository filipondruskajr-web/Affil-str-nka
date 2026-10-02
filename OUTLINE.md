# Investment Affiliate Site for Slovakia: Site Outline

Working outline for a Slovak-language website that compares brokers and investment
platforms and earns affiliate commissions. The structure borrows from the large
English-language affiliate sites and is adapted for the Slovak market.

---

## 1. What the English sites have in common

| Site | Core model | What to copy |
|---|---|---|
| **NerdWallet** (US) | "Best X" lists plus individual reviews, 1–5 star scores | Advertiser disclosure at the top of every money page; "Best for…" labels on each product card; key numbers (fee, minimum deposit) visible on the card |
| **BrokerChooser** (EU/global) | Broker reviews built from real funded accounts, 1,200+ data points | Published **methodology** page; country-specific "best brokers in [country]" pages; "Find my broker" quiz; scam-broker warning list |
| **Investopedia** | Large educational library that feeds the "best brokers" pages | Glossary and beginner guides as the SEO base, with internal links to the money pages; author and expert-reviewer box |
| **The Motley Fool / The Ascent** | Product reviews alongside long-form guides | "How to buy [stock/ETF]" guides that each end with a broker recommendation |
| **StockBrokers.com** | Deep annual testing plus awards | Yearly **awards** ("Best broker 2026") that brokers often quote and link back to |
| **Monevator / Money to the Masses** (UK) | Fee comparison tables, cost by portfolio size | "Cheapest platform for €X" pages and fee calculators. Flat vs. % fee and FX fees decide which platform wins |

**Common pattern:** education → comparison → review → CTA (affiliate link).
Trust signals (methodology, named authors, update dates, disclosure) sit on every
page that makes money.

---

## 2. Positioning for Slovakia

- **Language:** Slovak first. Optionally add Czech later, since it is a nearby market with similar brokers.
- **Gap in the market:** Large international sites (BrokerChooser has a `/sk` version) cover
  brokers but go light on **Slovak specifics**. Your advantage is local depth:
  - Slovak taxes: the **1-year holding exemption** for securities on regulated markets,
    taxing dividends, filing the **daňové priznanie typ B**, and health-insurance contributions
  - Whether the platform is in Slovak, has a SK/EUR account, SEPA deposits, a local branch, and support
  - Slovak and Czech products: **Finax**, **Portu**, bank funds (Tatra banka, SLSP, VÚB), the **III. pilier (DDS)** and the **II. pilier**
- **Target audience:** beginners aged 22–45 who want to start with ETFs or monthly investing, plus
  intermediate investors who want to cut costs.

---

## 3. Sitemap

```
/                                   Homepage
/porovnanie-brokerov                Comparison table (filterable)
/najlepsi-brokeri                   Hub: "Best brokers in Slovakia 2026"
   /najlepsi-brokeri/pre-zaciatocnikov
   /najlepsi-brokeri/na-etf
   /najlepsi-brokeri/na-akcie
   /najlepsi-brokeri/sporiaci-plan       (monthly investing plans)
   /najlepsi-brokeri/lacni               (lowest fees)
/recenzie                           Hub: all reviews
   /recenzie/xtb
   /recenzie/interactive-brokers
   /recenzie/trading-212
   /recenzie/trade-republic
   /recenzie/finax
   /recenzie/portu
   /recenzie/revolut-investovanie
   /recenzie/...
/porovnanie                         Head-to-head comparisons
   /porovnanie/xtb-vs-trading-212
   /porovnanie/finax-vs-portu
   /porovnanie/ibkr-vs-xtb
/investovanie                       Education hub
   /investovanie/ako-zacat
   /investovanie/etf
   /investovanie/akcie
   /investovanie/dividendy
   /investovanie/robo-advisori
   /investovanie/dochodok          (II. and III. pillar, PEPP)
/dane                               Tax hub (major SEO asset)
   /dane/dan-z-investicii
   /dane/oslobodenie-po-1-roku
   /dane/danove-priznanie-krok-za-krokom
   /dane/dividendy-a-zrazkova-dan
/nastroje                           Tools
   /nastroje/kalkulacka-zlozeneho-uroku
   /nastroje/kalkulacka-poplatkov       (fees by portfolio size)
   /nastroje/kalkulacka-dane
   /nastroje/najdi-brokera              (quiz)
/ako-to-ocenujeme                   Methodology
/o-nas                              About, authors, contact
/ako-zarabame                       How we make money (affiliate disclosure)
/varovania                          Warnings about scams and unlicensed brokers
/slovnik                            Glossary
/newsletter
Legal: /ochrana-osobnych-udajov, /cookies, /obchodne-podmienky
```

---

## 4. Homepage (top to bottom)

1. **Header:** logo · Brokers ▾ · Reviews · Comparison · Learn ▾ · Taxes · Tools · 🔍 search
2. **Hero:** "Find the best broker for investing in Slovakia" with two buttons:
   **[Compare brokers]** and **[Take the 1-minute quiz]**
3. **Trust bar:** "X brokers tested with real money · updated [month/year] · independent methodology"
4. **Top 3 picks:** cards with logo, score (e.g. 4.8/5), a "Best for…" label (ETFs / beginners /
   lowest fees), 3 key numbers (stock fee, minimum deposit, SK language ✓), a CTA
   **[Visit site]** (affiliate link), and a "Read review" link
5. **"What kind of investor are you?"** tiles: Beginner · Monthly saver · Active trader ·
   Passive (robo-advisor) · Retirement savings. Each tile leads to the matching "best" page
6. **Mini comparison table:** 5–7 brokers with a link to the full table
7. **Tools teaser:** compound interest calculator embedded inline
8. **Beginner guides:** 6 article cards (how to start, what an ETF is, taxes…)
9. **Taxes section:** "How to file investment income in your tax return" (seasonal: Jan–Mar)
10. **Newsletter signup:** lead magnet such as "Free PDF: Investing in 7 steps + tax checklist"
11. **Footer:** affiliate disclosure, **risk warning**, methodology, about us, legal pages

---

## 5. Page templates

### 5.1 "Best brokers for X" (main money page)
1. H1 + author + expert reviewer + "Updated: dd.mm.yyyy"
2. **Affiliate disclosure** (1–2 sentences linking to /ako-zarabame)
3. Quick summary: a short list "Our top picks", one line per broker with its "Best for" label and a CTA
4. Comparison table (sortable on desktop, cards on mobile)
5. Detailed section for each broker:
   - Logo, score, **Pros / Cons**
   - Key facts: fees, minimum deposit, markets/ETFs, SK language, regulator (NBS/KNF/BaFin/CySEC…),
     investor protection limit, deposit methods
   - "Who it suits / who it doesn't"
   - CTA button plus a CFD risk warning where it applies
6. How we chose (short, with a link to the methodology)
7. How to choose a broker (buying guide)
8. FAQ (schema markup)
9. Related articles

### 5.2 Broker review
1. Header: score, verdict in one sentence, CTA, last update
2. Score breakdown: fees · platform · products · deposits/withdrawals · security · support · education
3. Pros / Cons
4. Fees in detail (table: stocks, ETFs, FX conversion, inactivity, withdrawal fees)
5. Is it safe? (regulation, investor protection, years in business)
6. Account opening step by step, with screenshots
7. Platform and mobile app (own screenshots and a short video)
8. Taxes for Slovaks: what reports the broker provides and how to use them in the tax return
9. Alternatives (links to vs. pages)
10. Verdict + CTA + FAQ

### 5.3 Head-to-head (X vs Y)
Summary winner per category → side-by-side table → section per category → "Choose X if… / choose Y if…" → two CTAs.

### 5.4 Educational guide
Article content → contextual box "Where to buy it" (top 2 brokers) → related guides. These pages exist to win SEO traffic and send readers to the money pages through internal links.

### 5.5 Tools
- **Compound interest calculator** (monthly investment, years, return)
- **Fee calculator:** enter portfolio size and monthly contribution to see the annual cost at each broker.
  This is the most persuasive tool and leads straight to a CTA.
- **Tax calculator** (with a 1-year exemption check)
- **Find my broker quiz:** 5–6 questions that end in a recommendation and an email capture

---

## 6. Trust and legal (must have)

- **Affiliate disclosure** on every money page, plus a full "How we make money" page
- **Risk warnings:** a general one ("Investing involves risk, you may lose money…"). For CFD brokers,
  the ESMA-mandated warning "X % of retail investor accounts lose money…", which partners will require
- **Methodology page** with weighted criteria (e.g. fees 30 %, safety 20 %, platform 15 %…)
- **Named authors** with bios. Ideally an expert reviewer (a licensed financial advisor or tax advisor for the tax content)
- **Update dates** and a changelog of fee changes
- **Legal check:** have a Slovak lawyer confirm that the site is *information/advertising*
  and not **financial intermediation** under zákon č. 186/2009 Z. z. (NBS-supervised). Avoid
  personal "advice" wording, and check the conditions of each affiliate program
- GDPR: cookie banner (affiliate tracking cookies need consent), privacy policy

---

## 7. Monetization

| Source | Notes |
|---|---|
| Broker affiliate programs (CPA / revenue share) | XTB, Interactive Brokers, Trading 212, Trade Republic, eToro, Lightyear, etc. Check which ones accept Slovak traffic and pay in EUR |
| Slovak/Czech platforms | Finax, Portu, possibly DDS (III. pillar) partners. Contact them directly |
| Affiliate networks | e.g. Dognet, CJ, Awin, or a broker's in-house program |
| Newsletter | Sponsored slots once the list is large enough |
| Later | Paid e-book or course ("Investment tax return step by step"), consultations through a partner |

---

## 8. Content plan: first 30 pieces

**Money pages (10):** Best brokers in Slovakia · Best for beginners · Best for ETFs · Cheapest brokers ·
Best monthly investing plan · reviews: XTB, IBKR, Trading 212, Trade Republic, Finax

**Comparisons (5):** XTB vs Trading 212 · Finax vs Portu · IBKR vs XTB · Trade Republic vs Trading 212 ·
Broker vs bank funds

**Education (10):** How to start investing · What is an ETF · Best world ETFs (VWCE, IWDA…) ·
How much to invest per month · Robo-advisors explained · Dividends · II. vs III. pillar ·
Investing for children · Common beginner mistakes · Glossary

**Taxes (5):** Tax on investments in SK · 1-year exemption explained · Tax return step by step ·
Dividends and withholding tax · Health insurance on investment income

---

## 9. Technical and SEO notes

- **Stack:** WordPress (with Rank Math and a custom table plugin) for speed, or Astro/Next.js
  with a headless CMS for performance and custom tools
- Broker data (fees, scores) in **one central data source** so tables, cards and reviews update together
- Affiliate links through **cloaked redirects** (`/go/xtb`) with `rel="sponsored nofollow"`
- Schema: `Review`, `FAQPage`, `Article`, `BreadcrumbList`
- Mobile first: tables turn into cards and the CTA button stays sticky on reviews
- Analytics: click tracking per CTA position, so you can see which placements convert

---

## 10. Launch roadmap

1. **Weeks 1–2:** legal check, apply to affiliate programs, brand and domain, design system
2. **Weeks 3–6:** templates, methodology, about/disclosure pages, first 10 money pages
3. **Weeks 7–10:** 15 education and tax articles, compound interest and fee calculators
4. **Month 3+:** quiz, newsletter, comparisons, seasonal tax push (Jan–Mar), first "Awards 2027"

---

### Sources consulted
- BrokerChooser methodology: https://www.brokerchooser.com/methodology
- BrokerChooser Slovakia: https://brokerchooser.com/sk/slovakia
- NerdWallet best brokers: https://www.nerdwallet.com/investing/best-brokers/
- Money to the Masses platform comparison: https://moneytothemasses.com/saving-for-your-future/investing/best-cheapest-investment-platform-for-50000-savings
- Finder UK investments: https://finder.com/uk/investments
- Brokers for Slovak investors and the 1-year exemption: https://freenance.io/comparisons/best-stock-brokers-slovakia-2026/
- InvestingInTheWeb, brokers in Slovakia: https://investingintheweb.com/brokers/brokers-in-slovakia/
- Zákon č. 186/2009 Z. z.: https://static.slov-lex.sk/static/SK/ZZ/2009/186/20250710.html

> Note: fees, tax rules and broker availability change. Check every figure against primary sources before publishing.
