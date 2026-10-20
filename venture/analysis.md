# Opportunity analysis and recommendation (2026-10-20)

Status: **draft for Johnny's decision.** Evidence comes from `research/01–03`. Every figure below that isn't cited there is an **assumption**, and is labelled as one.

## 0. Verdict on the stated target

**$40k/month within 1–3 months, from under $1k, at 1–2 h/week: rejected.** No option below comes close, and the research found no credible evidence of anyone doing it.
- RevenueCat 2026 (checked myself): only 17% of new subscription apps reach $1k MRR within two years, and 4.6% reach $10k.
- Of products that do reach $1k MRR, the median takes about 8 months (Indie Hackers 2022, small sample).

Working target used below: first revenue in 1–3 months, a $1k/month go/no-go by month 12, and $40k/month only as a long-run ceiling.

**Acquiring a business:** not viable on under $1k. Even micro-startups sell for about $5k (Microns). Revisit only if the budget changes.

## 1. Five opportunities compared

Score each from 1 to 5 (higher = better): **D** = credible demand, **P** = profit after delegation, **O** = low owner involvement. These are judgement calls, not measurements.

### 1. Quote Follow-Up Autopilot — D3 P3 O4 = **10**
- **Who pays and why:** Solo and small painting/trade contractors who send quotes but don't follow up. That's people on Jobber Core, Joist, or Word/PDF quotes.
- **What it does:** The contractor BCCs or forwards the quote email to a unique address. The system then sends 2–3 polite, timed follow-ups to the homeowner, with replies going to the contractor. It stops automatically when the homeowner replies.
- **Alternatives:** Jobber Connect, ResponsiBid ($179+/mo), QuoteIQ, CRMs, or Gmail scheduled send done by hand.
- **Why we could compete:**
  - Jobber reserves automated quote follow-ups for Connect and up (checked myself on 2026-10-20: Core $21/mo vs Connect $70/mo on annual promo pricing, $49 vs $139 at list).
  - We'd be a single-purpose $25/mo tool that works with any quoting method.
  - Johnny knows how contractors actually quote.
- **Evidence for:**
  - The gap is confirmed on Jobber's own pricing page.
  - Forum anecdotes put win rates at 10–30% with follow-ups lasting up to 60 days, so the pain is real.
  - Follow-up is directly tied to revenue.
- **Evidence against:**
  - We have no direct customer voice asking for this (Reddit was blocked).
  - Jobber could unbundle the feature.
  - Contractors may be too disorganized to BCC every quote.
- **Startup cost:** about $100–300 (domain, small ad test). **Ongoing:** about $50–100/mo at small scale.
- **First revenue:** 3–8 weeks if the test works (assumption).
- **Getting customers:**
  - A paid search test on terms like "quote follow up software contractor".
  - Listings on Capterra and similar directories (free tiers).
  - A free "quote follow-up email templates" page.
  - Johnny posting occasionally in contractor groups he already belongs to.
- **Material risks:**
  - **Email deliverability:** a spam complaint could suspend the sending account. This is the biggest one.
  - **CASL:** a homeowner who asked for a quote is likely an "inquiry" with implied consent for 6 months. Needs confirmation.
  - Gmail/Outlook direct integration is avoided on purpose, because it triggers a US$500–4,500/yr security assessment.
- **Biggest unanswered question:** Will contractors pay $25/mo *and* actually BCC their quotes?

### 2. Painter Estimating Workbook (Excel/Google Sheets) — D2 P2 O5 = **9**
- **Who pays:** Painters who want production-rate-based pricing but won't pay for software.
- **Why us:** Built on Johnny's real production rates and his existing calculator.
- **Evidence for:**
  - PaintTalk painters prefer their own-rate spreadsheets (older evidence).
  - Etsy shows sales of $3–$29 templates.
  - Near-zero maintenance.
- **Evidence against:**
  - Low price ceiling.
  - Free versions from Benjamin Moore, Workyard and Knowify.
  - Etsy is saturated with AI-made listings.
  - ChatGPT can build a basic version.
- **Cost:** under $50. **First revenue:** 2–6 weeks (assumption). **Channel:** Etsy and Gumroad search.
- **Risk:** Platform fees and ranking can change at any time.
- **Biggest unanswered question:** Can it sell at $29–49 when $5 and free versions exist?

### 3. Instant-Quote Website Widget for Painters — D2 P3 O3 = **8**
- **What it is:** Homeowners get a price range on the contractor's own site, and the contractor gets the lead. Priced at $29/mo.
- **Evidence for:** Competitors charge $99–$495/mo.
- **Evidence against:**
  - PaintPricing ($29) and CostHonest ($79) already sell nearly this exact product, with no visible traction.
  - Many painters' websites get little traffic.
- **Extra burden:** Embed and website support.

### 4. BC Building-Permit Lead Feed (paid data) — D? P3 O3 = **unscored**
- **What it is:** Weekly email or CSV of new residential permits from BC municipal open data, sold to trades at $29–49/mo.
- **Status: hypothesis only.** It was not researched. Which municipalities publish usable data, what the licence terms are, and what competitors exist are all unknown.
- **Next step:** Research it before scoring.

### 5. Shopify App (small merchant utility) — D2 P2 O2 = **6**
- **Evidence for:** Real buyer traffic and 0% revenue share up to US$1M.
- **Evidence against:**
  - 2026 forums show new apps with 0–3 installs after weeks.
  - Ongoing merchant support load.
  - Johnny has no edge in this market.
- **Verdict:** Rejected.

**Rejected outright:** Chrome extensions (opaque takedowns, no built-in billing), SEO directories (AI Overviews, scaled-content policy), generic templates or AI wrappers (commoditized, high churn).

## 2. Economics for the top two

**Shared assumptions:**
- All figures in CAD per month at about month 12.
- Prices exclude GST/PST, because a merchant of record collects and remits those.
- Paddle fees: 5% + $0.50 (US prices converted roughly).
- Replacement labour at market rates: VA support $25/h; developer maintenance $90/h; owner management valued at $50/h.
- Income tax isn't modelled. It depends on Johnny's overall income; ask an accountant.

### Option 1: Follow-Up Autopilot at $25/mo
- **Churn assumption:** 6%/mo (SMB, low price). **CAC assumption:** $40–150 per customer via paid search, unproven.

| | Downside | Base | Upside |
|---|---|---|---|
| Paying customers | 5 | 40 | 150 |
| Revenue | $125 | $1,000 | $3,750 |
| Payment fees (≈7%) | –$9 | –$70 | –$263 |
| Hosting, DB, email sending, domain | –$45 | –$70 | –$150 |
| Refunds/chargebacks (2%) | –$3 | –$20 | –$75 |
| Support VA (1 / 3 / 8 h) | –$25 | –$75 | –$200 |
| Dev maintenance (1 / 2 / 4 h) | –$90 | –$180 | –$360 |
| **Operating profit** | **–$47** | **$585** | **$2,702** |
| Owner management (1 / 1.5 / 2 h/wk × $50) | –$215 | –$325 | –$430 |
| **Profit after paying for everyone's time** | **–$262** | **$260** | **$2,272** |
| New customers/mo to replace churn | 0.3 | 2.4 | 9 |
| Acquisition spend to sustain (at $75 CAC) | $25 | $180 | $675 |
| **Cash to owner after acquisition** | **–$72** | **$405** | **$2,027** |

*Cash to owner = operating profit minus acquisition spend. It excludes the owner-time value, because Johnny does that work himself.*

- **Break-even:** about 2 customers covers hosting. About 7 covers hosting plus minimal paid support and maintenance. About 25–30 covers everything, including Johnny's time at market rate.
- **For $40k/mo:** about 1,850 customers, with roughly 110 new customers every month just to stay flat. At $75 CAC that's about $8k/mo in acquisition. Not credible in this horizon.
- **Startup cash:** about $350–450. That's a $20 domain, about $60 for two months of hosting and email, and a $300 ad cap.

### Option 2: Estimating Workbook at $39 one-time
- **Fees:** assume about 12% all-in on Etsy (Etsy fee page unverified), and 10% + $0.50 on Gumroad direct.
- **Repeat purchases:** ~0. **Refunds:** 4%.

| | Downside | Base | Upside |
|---|---|---|---|
| Sales/mo | 2 | 15 | 50 |
| Revenue | $78 | $585 | $1,950 |
| Fees + refunds | –$13 | –$94 | –$312 |
| Etsy ads (optional) | $0 | –$50 | –$150 |
| Support (0.5 / 1 / 2 h VA) | –$13 | –$25 | –$50 |
| **Operating profit = owner cash** | **$52** | **$416** | **$1,438** |

- **For $40k/mo:** about 1,200 sales every month. Not credible.
- **Startup cash:** under $50.

**Reading these together:** the base cases point to a few hundred dollars a month in year one. That's real money for very little time, but it's nowhere near $40k. Both are worth testing only because the tests are cheap and can be stopped quickly.

## 3. Hands-off operating model (Option 1)

| Function | Handled by | Cost | When Johnny steps in |
|---|---|---|---|
| Sales | Landing page + self-serve checkout (Paddle/Stripe) | Fees only | Never, after launch |
| Onboarding | Automated welcome email with the customer's unique BCC address and a 2-minute setup guide | $0 | Never |
| Delivery | Hosted scheduler sends the follow-ups and stops on reply | In hosting | Never, unless a bug |
| Billing | Merchant of record: renewals, failed-payment retries, tax | 5% + 50¢ | Never |
| Support | Help page + support inbox. Johnny triages for 30 min/wk at first; a VA later | $0–75/mo | Weekly inbox check |
| Refunds | Written policy (14-day no-questions) handled in the payment dashboard | Refund amount | About 1 click per case |
| Monitoring | Uptime checker + error alerts by email/SMS | $0–10/mo | When an alert fires |
| Maintenance | A new Claude Code session, run by Johnny or a paid developer, when something breaks | $90/h dev, or Johnny's time | Rare; needs a human to start it |
| Emergencies | Sending suspended or app down → automatic pause + status notice to customers | — | Same day ideally; within a week at most |

**If Johnny is away for two weeks:** sign-ups, billing, follow-up sending and renewals keep running. Support emails wait unanswered, and nobody fixes an outage unless he has hired a developer on call. The mitigation is a status page and an auto-reply promising answers within 3 business days.

**When this Claude Code session closes:** nothing I write keeps running unless it's deployed to hosting. Once deployed, the app, scheduler, payment provider and monitoring all keep running on their own. I am *not* an ongoing employee. Fixes need someone to open a new session.

## 4. Recommendation and validation test

**Run the Option 1 test (Follow-Up Autopilot), with the Option 2 workbook as a cheap parallel test.**
- **Why Option 1:** it's the only gap confirmed on an incumbent's own pricing page, it brings recurring revenue, and it's fully automatable without sales calls.
- **Why add Option 2:** it costs under $50 and gives a faster read on whether contractors will pay for Johnny's estimating knowledge at all.

### Test A: Follow-Up Autopilot pre-sale
- **What we build:** a landing page plus a working email-only MVP (BCC → scheduled follow-ups), with checkout at a $15/mo founding-member price. Real card charges, cancel anytime.
- **Traffic:**
  - About $300 in Google Ads (Canada and US) on high-intent terms.
  - A few posts by Johnny in contractor groups he's already in. Only with his approval, roughly 30 minutes total.
- **Budget cap:** $400 all-in. **Duration:** 30 days from launch.
- **Success:** ≥5 paying customers, AND ≥3 of them forwarded at least 3 real quotes in their first two weeks, AND paid-ad cost ≤$60 per paying customer.
- **Iterate once:** 2–4 payers → change the messaging and price, and spend at most $200 more.
- **Stop:** fewer than 2 payers after $300 spent, or 0 customers actually using it.
- **What a pass proves:** some contractors will pay and will use it. **What it doesn't prove:** retention, or that growth beyond paid ads is possible.

### Test B: Workbook
- **Setup:** list it on Etsy and Gumroad at $39. **Budget:** under $50. **Duration:** 45 days.
- **Success:** ≥8 sales. **Stop:** ≤2 sales.
- **What a pass proves:** demand on the marketplace, not a business that scales.

## 5. Decisions needed from Johnny (batched)
1. Accept the revised target: $1k/month by month 12 as go/no-go, with $40k as the long-run ceiling.
2. Approve Test A, Test B, or both.
3. Approve spend up to $450 and the accounts to open: domain, hosting, Paddle or Stripe, email sending (Postmark/Resend), Google Ads, Etsy/Gumroad.
4. Name and branding: keep it separate from Grandview (assumed yes).
5. Confirm with an accountant: GST status, and BC PST small-seller eligibility given the contractor exclusion.
6. Is Johnny willing to post a few times in contractor groups he's already in? This counts as contacting people, so it needs his say-so.
