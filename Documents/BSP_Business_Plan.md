# BUILDERS STREAM PRO (BSP)
## Business Plan — Q2 2026 Draft
**Founder:** Douglas Miller, BCK Construction Services | Chandler/Henderson County, TX
**Stage:** Pre-Launch | **Launch Target:** Q1 2027 | **Initial Capital:** $10,000

---

# SECTION 1: EXECUTIVE SUMMARY
*Written for a smart 12-year-old — and a busy investor*

**The Problem.** About 3.9 million small construction and renovation companies in the US run their businesses on a chaotic mix of spreadsheets, sticky notes, text messages, and QuickBooks. When a contractor is managing a $200,000 kitchen remodel, they're losing money on change orders they forgot to document, spending Friday nights typing estimates instead of bidding the next job, and getting called 12 times a day by clients who just want to know what's happening. The software built for big construction firms ($20,000/year Procore) is overkill and unaffordable. The cheap alternatives don't actually work the way renovation projects work.

**The Solution.** Builders Stream Pro is a cloud software platform ($79–199/month) that handles everything a small renovation contractor needs in one place — writing estimates, tracking costs, scheduling work, managing change orders, sending invoices, and giving homeowners a portal so they stop calling. It connects directly to QuickBooks so bookkeeping doesn't require re-entering every transaction. Unlike every existing tool, it's built specifically for *renovation* work, not new construction — because fixing an existing house is fundamentally different from building a new one, and no current software actually understands that difference.

**The Market.** There are roughly 450,000–500,000 small contracting businesses in the US that need exactly this and can afford it. The US small contractor software market is worth approximately $450–500 million annually and growing at 11% per year. The renovation/remodel niche within that is the fastest-growing segment and the least well-served.

**The Business Model.** Monthly subscriptions: $79/month for solo operators, $149/month for teams up to 5, $199/month for teams up to 15. 100 paying customers at an average of $149/month = $14,900/month recurring revenue. 400 customers = $59,600/month. No sales team required at launch — customers sign up on their own after a 30-day free trial.

**The Advantage.** The founder has 25 years of software engineering experience and 10+ years working in and around the construction industry through BCK Construction Services. He understands both how to build the software *and* how contractors actually work. That combination is rare, and it means the product won't be built by engineers guessing what contractors need.

**The Ask.** This is a bootstrapped launch on $10,000 of initial capital. No outside funding is being sought for Year 1. The plan is to reach profitability by Q3 2027 at 75–100 paying customers, then decide whether to raise capital to accelerate or stay lean.

---

# SECTION 2: PROBLEM & SOLUTION

## The Problem — With Specificity

**Who has it:** Small general contractors and renovation/remodeling companies with 1–50 employees doing $500K–$5M in annual revenue. This is the "working owner" — the person who swings a hammer Monday and does the books Sunday night. There are approximately 450,000+ of these businesses in the US.

**How often they feel it:** Every single day. The pain is not occasional — it is structural to how the work operates.

**The specific pains, ranked by damage:**

*1. Estimating is manual and slow, and under-quoting costs real money.* A typical renovation estimate takes 4–8 hours to build in Excel. Errors in quantity takeoffs or labor assumptions often aren't discovered until mid-project. Industry data suggests small contractors lose an average of 2–4% of project revenue to estimation errors — on a $2M/year firm, that's $40,000–80,000 in margin disappearing annually. Contractors know this. They just don't have a better option at $100/month.

*2. Change orders are handled informally and contractors get burned.* Scope creep is the renovation industry's profit killer. When the homeowner says "while you're in there, can you also...?" and the contractor says "sure, I'll add it to the invoice" without written authorization, they often end up eating the cost in a dispute. The typical small renovation firm handles 3–8 change orders per project. Most are documented on a text message thread.

*3. Client communication is a time sink.* Homeowners whose house is being torn up are anxious. They call, they text, they want to know if the tile is ordered, when the inspector is coming, and why there are workers drinking coffee in their driveway. The average renovation PM spends 1–2 hours per day on client communication that could be eliminated by a simple customer portal showing project status and photo updates.

*4. QuickBooks sync breaks constantly.* Nearly every SME construction tool claims QuickBooks integration. Nearly every user complains it doesn't actually work — transactions double, categories don't match, or the sync errors silently and they don't find out until month-end. This is the #1 complaint across every review site in the category. It costs hours every month in cleanup.

*5. Project profitability is invisible until it's too late.* Most small contractors can't tell you whether a job is running over budget until the job is done. They find out at invoice time. By then there's nothing to do except take the loss. Real-time job costing — tracking what you've spent vs. what you estimated — is a feature most can't afford in current tools or don't have the time to set up.

**Current workarounds and why they fail:**

- *Buildertrend* ($499–$799/month): Has all the features, built for residential builders. Too expensive for a 3-person operation. Price increases every year. No free trial. Poor data portability. Built for new construction, not renovation.
- *JobTread* ($159/month + $18/user): Closest to the right price. Good UX. But still oriented toward general contracting project management, not renovation-specific workflows. Growing fast, so a genuine threat.
- *Contractor Foreman* ($49–$415/month): Affordable, but rough UX, reliability issues, weaker mobile experience.
- *Spreadsheets + QuickBooks alone*: Free but requires a dedicated admin to manage. Falls apart when team size crosses 3 people or project count crosses 5.

**The market structure problem:** The software tools that work well cost $500+/month (too expensive for small operators). The tools that small operators can afford don't work well enough. This is not a new observation — but it remains genuinely true. The gap between what Buildertrend costs and what small renovation contractors need hasn't closed because the big players are focused on moving upmarket, not down.

## The Solution

**What BSP Does**

BSP is a Django/Python-based SaaS platform covering the full project lifecycle for small renovation and remodeling contractors:

- **Estimating:** Line-item estimates with labor, material, and markup templates. Build a full estimate in under an hour rather than a full day.
- **Job Costing:** Real-time comparison of estimated vs. actual costs. The contractor sees a green/yellow/red dashboard on every project, updated as expenses are logged.
- **Change Orders:** Digital change order workflow — description, cost, homeowner signature via link. No more "I thought we agreed on that."
- **Scheduling:** Visual project calendar and phase management. Assign tasks to crew members and subcontractors.
- **Client Portal:** A branded link the homeowner gets on Day 1. Shows project timeline, current phase, photos, approved change orders, and payment schedule. Cuts client phone calls by an estimated 60–70%.
- **Invoicing and Progress Billing:** Generate invoices tied to project milestones. Send via email or the portal. One-click QuickBooks sync.
- **QuickBooks Online Integration:** Bi-directional sync for customers, invoices, payments, and job expense categories. Certified through the Intuit Partner Program. This is a day-one engineering priority, not an afterthought.
- **Field Operations:** Mobile photo capture with auto-labeling, daily log entry, and time tracking for crew members.

**Why 10x Better**

BSP is not 10% better than existing tools on individual features — experienced competitors have had years to refine their feature sets. The 10x claim rests on three things:

1. **Price-to-feature ratio at the $79–199/month tier.** No current tool delivers this full feature set at this price. The closest (JobTread at $159/month + per-user fees) charges more for a team of three.
2. **Renovation-specific workflows.** This is the real differentiation. Renovation starts with unknowns (existing conditions, hidden surprises, homeowner living on-site). The phases are different: initial scope → demo/discovery → revised scope → rough-in → finishes → punch list → close-out. No current tool has purpose-built phase templates and workflow rules for this sequence. BSP will.
3. **A QuickBooks integration that actually works.** This is table stakes done right. Being certified through Intuit's partner program, building with proper error handling, and making it the #1 engineering priority before launch is not glamorous — but it is a genuine differentiator because competitors consistently fail at it.

## The Unique Insight

Here is what this plan is built on that competitors either don't know or don't believe:

*Renovation work is not a simplified version of new construction. It is a fundamentally different type of project. New construction starts with certainty — a blueprint, a clean site, a defined scope. Renovation starts with uncertainty — existing conditions, hidden problems, homeowners living in the work zone, scope that evolves. The entire project lifecycle, risk profile, cash flow pattern, and client relationship is different.*

Every current tool — Procore, Buildertrend, JobTread, CoConstruct — was designed with new construction mental models and then adapted for renovation. The workflows assume you know the scope before you start. Renovation contractors know that's rarely true. BSP will be designed from day one for a workflow that begins with "we don't know exactly what we're getting into yet" — and manages that uncertainty as a first-class project state rather than an exception.

The secondary insight: *Review aggregators (G2, Capterra, Software Advice) now dominate how small contractors choose software.* The first tool that reaches 200+ authentic positive reviews in the renovation niche will become the default recommendation for that buyer segment. That position is currently unoccupied. It can be seized in 12–18 months by a product with genuine product-market fit and an active customer success motion.

---

# SECTION 3: MARKET ANALYSIS

## TAM / SAM / SOM — Calculation Methodology

These numbers are derived from third-party research (Mordor Intelligence, Precedence Research, Software Advice buyer data, Fortune Business Insights) cross-referenced with competitor revenue estimates. They are not invented. Confidence ratings are noted.

**TAM — Total Addressable Market**
The US construction management software market is approximately $1.0–1.1 billion annually (2024–2025). Source: Mordor Intelligence, Grand View Research, Precedence Research — three separate reports converging on the same range. Historical CAGR: 8–10%. Projected CAGR through 2034: 9.36%. *Confidence: HIGH — multiple independent sources agree.*

**SAM — Serviceable Addressable Market**
Small and medium enterprises represent approximately 44–46% of the total US construction software market, based on segment breakdowns from Fortune Business Insights (2024). Applied to $1.1B: SAM = approximately $450–500M annually. This is the market for cloud-based tools priced under $500/month, targeting firms with fewer than 500 employees. *Confidence: MEDIUM — derived segment math, not directly sourced.*

**SOM — Serviceable Obtainable Market**
BSP's direct target: US renovation/remodeling contractors with 1–50 employees and $500K–$5M in revenue. This sub-segment represents approximately 12–15% of the SME construction software market, or $60–80M in current annual spend. At year-three target pricing and penetration, BSP's realistic revenue ceiling before hitting distribution constraints is $15–25M ARR — achievable with 700–1,000 paying customers at $150–200/month average.

*Why the renovation sub-segment? Because it is the fastest-growing (12–14% CAGR vs. 8–9% for commercial), the least consolidated (no dominant player owns it), and the most distinct from new construction in workflow requirements.*

**The math that matters for Year 1:**
- There are approximately 3.9 million construction businesses in the US (Census Bureau/BLS)
- Approximately 450,000 are renovation/remodeling-focused with 1–50 employees
- Of those, roughly 20–30% are actively looking to switch or adopt new software in any given year = 90,000–135,000 potential buyers annually
- Capturing 0.1% of that in Year 1 = 90–135 paying customers
- That is the actual Year 1 target. It is modest, achievable, and does not require a miracle.

## Target Customer Persona

**"Marcus, The 8-Person Remodeler"** (Primary)

Marcus is 41, runs a residential remodeling company in a Sun Belt suburb — Phoenix, Dallas, Orlando, Charlotte. He started as a carpenter, got his GC license 10 years ago, and has slowly grown to 8 people: himself, a lead carpenter, two carpenters, two laborers, an office manager who works part-time, and his wife who handles bookkeeping on nights and weekends.

His company does $1.8M a year. He takes home about $95,000 after paying himself a salary. He runs 4–6 jobs simultaneously: kitchen remodels, bathroom renovations, additions, and the occasional full gut-rehab.

On a typical Tuesday morning, Marcus has driven to three job sites before 9am. He has seven unread text messages from homeowners. He has a QuickBooks notification that a payment didn't sync. He has an estimate due Friday for a $280,000 kitchen/bath that he hasn't started because he needs to think through the labor hours. His office manager can't find the signed change order for the Johnson job, and the homeowner is claiming they never approved the extra work.

Marcus uses Buildertrend but barely — it's too complicated and he never got properly onboarded. He uses QuickBooks for invoicing. He uses Excel for estimates. He uses text messages for everything else. He pays $499/month for Buildertrend and feels guilty that he doesn't use it more. He has been "meaning to learn it properly" for two years.

Marcus would switch to a simpler tool tomorrow if it cost less, was easier to use, and his QuickBooks sync actually worked. He will not switch to something he's afraid of. He makes software decisions based on what his contractor friends recommend and what comes up first on Google when he searches "Buildertrend alternative."

**"Lisa, The Solo Renovator"** (Secondary)

Lisa is 34, runs a 3-person handyman/renovation company focusing on kitchens and bathrooms in inner-ring suburbs. Revenue: $480K. She pays herself $55,000. She uses a combination of Jobber (which she knows is the wrong tool), Google Sheets for estimates, and her iPhone camera for documentation.

Lisa is price-sensitive. She will not pay $200/month for software. She will pay $79/month if the tool saves her 3–4 hours a week. Her primary buying criterion is "does this work on my phone?"

**"Derek, The CoConstruct Refugee"** (Time-Limited Opportunity)

Derek runs a 22-person custom renovation firm at $4.5M revenue. He used CoConstruct for 6 years and built his entire operation around it — selection sheets, client portals, custom templates. When Buildertrend acquired CoConstruct in 2021, they stopped meaningful development. Derek has been "migrating" to Buildertrend for 18 months but hates the UX and thinks the pricing is too high. He is actively evaluating JobTread and whatever else comes up in his search results.

Derek is the highest-value customer BSP can target, but the window is closing as JobTread consolidates this cohort. He needs to be prioritized in the first 12 months.

## Why NOW? Market Timing Factors

**1. Buildertrend is vulnerable.** The category leader for SME residential construction has raised prices twice in the past 24 months (Essential tier: now $499–$799/month). They are moving upmarket, focused on growing from residential to commercial, and increasingly ignoring the small operator who made them famous. This price increase without proportional feature improvement is a classic incumbent vulnerability signal.

**2. CoConstruct is a dead product with live customers.** Buildertrend acquired CoConstruct in February 2021 and has not released meaningful new features for it since. There are an estimated 8,000–12,000 CoConstruct users who are migration-anxious and will switch to whatever they are shown first that looks credible. This cohort will be absorbed by competitors within 18–24 months. BSP can capture a meaningful share of it in 2027 if the launch is timed right.

**3. AI is creating a new differentiation window.** Only 1.5% of small contractors have AI integrated into multiple business processes (RICS survey, 2025). The first SME construction tool to ship genuinely useful AI features — AI-assisted estimating, photo-to-daily-log, natural language change order drafts — at the $99–200/month tier will have a meaningful marketing advantage for 12–18 months before competitors copy it. This window exists right now and will close.

**4. Review aggregators have become the primary purchase channel.** G2 and Capterra now dominate construction software discovery. JobTread became the fastest-growing construction tech company in North Texas primarily because Software Advice ranked it #1 for user satisfaction — and the company aggressively marketed that ranking. BSP can pursue the same playbook by seeding reviews from early customers.

**5. Python/Django makes this more achievable than it's ever been.** Django's ORM, built-in admin, and extensive third-party package ecosystem (for payments, email, authentication, file storage) means a single experienced developer can build a production-quality multi-tenant SaaS in 6–9 months where it would have taken 3 engineers 18 months in 2010. The infrastructure advantage for solo technical founders has never been greater.

## Competitor Positioning — Honest Assessment

**Buildertrend** — Category leader, ~1 million users, estimated $150–200M ARR. Unarguable brand recognition in residential construction. BSP cannot out-feature Buildertrend in Year 1 and should not try. BSP's competitive position against Buildertrend is purely on price transparency, renovation workflow fit, and onboarding speed. Buildertrend's weakness is that it's too complex, too expensive, and built for new construction.

**JobTread** — The most dangerous competitor. Fastest-growing (#6 Deloitte Fast 500 in 2025), 7,500+ customers, $159/month + per-user pricing. Clean UX. Strong community. BSP cannot be a worse version of JobTread. The differentiation must be genuine: renovation-specific workflows, no per-user fees, and the QuickBooks integration done right. JobTread is winning the general SME contractor market — BSP should let them have it and win renovation contractors specifically.

**Contractor Foreman** — Budget option at $49–$415/month. Broad features, rough UX, less active development. Positioned for the most price-sensitive buyers. BSP should not compete on price below $79/month because the resulting product cannot be quality. If a customer is only willing to pay $49/month, they are not BSP's customer.

**Jobber** — 200,000+ users but primarily field service (HVAC, plumbing, landscaping) rather than construction. Their estimating and job costing are shallow. Many Jobber users who move into renovation work quickly outgrow it. BSP can capture this transition moment.

**Procore** — Not a direct competitor at BSP's target customer size. Procore averages $20,000–100,000/year per customer. No small remodeler is choosing between BSP and Procore. The relevance to BSP is that Procore's marketing validates the category and establishes "construction management software" as a real product category in contractor consciousness.

---

# SECTION 4: BUSINESS MODEL

## Revenue Streams

**Primary: Monthly SaaS Subscriptions**

| Tier | Price | Included | Target Buyer |
|------|-------|----------|--------------|
| Solo | $79/month | 1 user, up to 5 active projects | Lisa: solo renovator |
| Team | $149/month | Up to 5 users, unlimited projects | Marcus: 3–8 person crew |
| Professional | $199/month | Up to 15 users, all features + priority support | Derek: 10–25 person firm |

Annual plans: 15% discount (equivalent to ~$67/$127/$169/month). Target: 40% of customers on annual plan by Year 2, because it improves cash flow and reduces churn.

*Pricing rationale: Buildertrend's base tier is $499/month. JobTread is $159 + $18/user. At $149/month flat for a 5-person team, BSP is materially cheaper than both with no per-user surprises. This price point is not permanent — at 500+ customers, the data will exist to raise it. But at launch, the pricing has to be a reason to try it, not a reason to pause.*

**Secondary (Year 2+): Add-On Modules**
- AI Estimating Assistant: +$29/month (AI-powered line-item estimating using historical project data)
- Subcontractor Portal: +$19/month (lightweight link-based portal for subs — no login required)
- eSign add-on: +$9/month (change order and contract signatures via DocuSign integration)

These are Year 2 revenue streams. Do not build them in Year 1. Validate core product first.

**Not Pursuing at Launch:** Marketplace commissions, referral partnerships, white-label licensing. These are distractions until the core product has product-market fit.

## Unit Economics

**Target unit economics at steady state (Year 2):**
- Average Revenue Per User (ARPU): $165/month (blended across tiers)
- Customer Acquisition Cost (CAC): $300–500 (target — heavily content/review-driven)
- Churn: 3–4% monthly in Year 1 (industry average for SMB SaaS), targeting 2% by Year 2
- LTV (at 3% monthly churn = 33-month avg. lifetime): 33 × $165 = $5,445
- LTV:CAC ratio target: 10:1 or better *because* CAC is kept low through content/review strategy

*Honest note: Monthly churn of 3–4% is realistic for SMB SaaS in Year 1. At 3% monthly churn, you lose roughly 30% of your customer base every year. This means you need to be adding customers faster than you're losing them every single month. This math is why the GTM section is the most important part of this plan.*

## The Simple Revenue Formula

```
[Customers] × [ARPU] × [12 months] = Annual Recurring Revenue

Year 1 Exit Rate: 150 customers × $149 avg × 12 = $268,200 ARR
Year 2 Exit Rate: 400 customers × $165 avg × 12 = $792,000 ARR
Year 3 Exit Rate: 800 customers × $175 avg × 12 = $1,680,000 ARR
```

## Path to Profitability

With Douglas as the sole developer/founder and minimal team in Year 1, the break-even point is approximately 75 paying customers at the Team tier ($149/month):

- 75 × $149 = $11,175 MRR
- Monthly costs at that stage: ~$1,500 (infrastructure, tools, marketing spend, admin)
- Gross margin: ~87% (SaaS infrastructure costs are low at this scale)
- Net profit at 75 customers: ~$9,675/month before founder salary

This is achievable by Q3 2027 at the growth rates projected. The business can sustain itself before needing to hire, which preserves the founder's flexibility to not raise outside capital.

---

# SECTION 5: GO-TO-MARKET

## The First 100 Customers — Specific Plan

There is no viral loop in B2B SaaS at this stage. There is no "build it and they will come." The first 100 customers come from doing 100 specific, unsexy things. Here is exactly what those things are.

**Channel 1: CoConstruct Migration (Customers 1–40)**

This is the single highest-ROI channel available in 2026–2027, and it has a closing window. CoConstruct users are in active migration anxiety. They are posting in Facebook Groups, Reddit (r/Construction, r/Contracting), and the CoConstruct user community asking "where should I go?"

Actions:
- Build a specific "Migrate from CoConstruct" landing page that addresses their exact fears (data import, selection sheets, client portal continuity)
- Create a free CoConstruct data import tool — JSON/CSV ingest of their project history
- Join the Facebook Group "Buildertrend Users / CoConstruct Migration" and participate authentically (not spam)
- Create a 10-minute YouTube walkthrough video: "I'm a CoConstruct user — here's what BSP looks like from your perspective"
- Offer free white-glove onboarding (1-hour screen share) for the first 50 CoConstruct migrants

Cost: Primarily founder time. Target: 40 customers from this channel in the first 6 months post-launch.

**Channel 2: Direct Outreach in Texas (Customers 1–25)**

BCK Construction Services gives this plan something most SaaS startups don't have: real relationships in the construction industry. The founder knows contractors. Contractors know the founder. This personal network is the fastest path to the first 10–25 paying customers.

Actions:
- Personally contact every contractor the founder has worked with or knows through BCK
- Offer them 6 months free in exchange for weekly feedback calls and an honest review on G2/Capterra at month 3
- Ask each early customer for 2 referrals to other contractors
- Attend Texas-specific contractor associations: Texas Association of Builders, AGC of Texas, local NKBA chapters
- Booth (or simply attend) at the Greater Dallas Home Improvement & Remodeling Expo

Cost: ~$1,000 in travel/events. Target: 25 customers, 15 of whom convert to paid after the free period.

**Channel 3: Content SEO + YouTube (Customers 25–70, 6–18 months)**

The long-game channel. Contractors search YouTube and Google constantly: "how to write a construction estimate," "best construction software for small contractors," "Buildertrend vs JobTread," "how to handle a change order dispute."

Actions:
- Publish 2 YouTube videos per month starting 90 days before launch. No production budget needed — screen recordings and walkthroughs.
- Target keywords: "renovation management software," "construction estimating software small contractor," "CoConstruct alternative," "Buildertrend too expensive alternative"
- Publish 1 blog post per week on the BSP site. Focus on tutorials and comparisons, not marketing fluff.
- Create a free "Renovation Estimate Template" in Excel — offered as a lead magnet in exchange for email address

Cost: Founder time + ~$100/month for simple screen recording/video editing tools. Revenue impact begins appearing 6–12 months after content is published. Target: 45 customers from inbound over the first 18 months.

**Channel 4: G2/Capterra Review Seeding (Supports all channels)**

This is not a customer acquisition channel on its own — it is the multiplier on every other channel. When a contractor hears about BSP and goes to verify it on G2 or Capterra, what they find determines whether they start a trial.

Actions:
- Set a goal of 50 G2 and 50 Capterra reviews by Month 6. This is aggressive but achievable with 75+ customers who are getting active support.
- Build an in-app prompt: "Did your invoice sync correctly with QuickBooks? Tell G2 what you think!" — triggered after a successful QB sync
- Send a personal email from the founder to every customer at Month 3 asking for an honest review
- Do NOT incentivize reviews (violates platform rules and looks fake)

Cost: Founder time. These reviews will drive $0 in Month 1 and will be the most valuable marketing asset in Month 12.

**Channel 5: Partnership with a QuickBooks ProAdvisor (Customers 70–100+)**

QuickBooks ProAdvisors are bookkeepers and accountants who serve small contractor clients. They already have relationships with exactly BSP's target customer. Many of them are frustrated explaining to clients why their Buildertrend QB sync keeps breaking.

Actions:
- Identify 5–10 QuickBooks ProAdvisors in Texas who work with contractors
- Offer them a referral fee: $100 for every paying customer they refer who stays 3+ months
- Give them a demo-ready account with sample renovation project data they can show clients
- Create a "BSP Partner" landing page they can link to

Cost: $100/customer acquisition from this channel. At 30 customers, that's $3,000 in referral fees. Highly cost-effective.

## 90-Day Launch Plan (Q1 2027)

*Assumes MVP is complete and in beta by January 1, 2027.*

**JANUARY 2027 — CONTROLLED LAUNCH**

Week 1: Go live. Send personal email to 50 contacts from the BCK Construction network. Offer: 3 months free, all I ask is 30 minutes of feedback at weeks 2 and 6. Goal: 15 signups, 10 active users.

Week 2: Fix the 5 most critical bugs reported in week 1. Do not add features. Do not change pricing. Do not panic about low signup numbers. Call every active user.

Week 3: Publish first YouTube video: "BSP Walkthrough — Everything a Small Renovation Contractor Needs in One Place." Post in r/Construction and r/Contracting with a disclosure that you're the founder.

Week 4: Launch the "Migrate from CoConstruct" landing page. Post about it in the CoConstruct Facebook community. Be transparent — you're the founder and you built something for them. Ask for feedback, not sales.

Month 1 goal: 20 total signups, 12 active weekly users, 0 bugs that lose data.

**FEBRUARY 2027 — ACTIVATION FOCUS**

Week 5: Personal onboarding call with every customer who signed up in January but hasn't entered a project yet. Find out why. Fix whatever is stopping them.

Week 6: Send first G2 review request email. Target: 10 reviews by end of February. Do not ask until the customer has successfully sent at least one invoice.

Week 7: Publish second YouTube video: "How to Handle a Renovation Change Order — and How to Document It So You Never Lose Money Again." Optimize for the keyword "renovation change order template."

Week 8: Apply to Intuit's QuickBooks Developer Program (if not already done). Begin the certification process — this takes 4–8 weeks and gives a trust badge that competitors may lack.

Month 2 goal: 40 total signups (20 new), 25 active users, 5 converted to paid plans.

**MARCH 2027 — CONVERT AND RETAIN**

Week 9: First batch of free trials end. Personal outreach to every trial user who hasn't converted. Ask: "What would need to be true for you to pay $149/month for this?" — and actually listen.

Week 10: Raise the first piece of content specifically targeting contractors leaving Buildertrend — "I Spent $499/Month on Buildertrend and Switched. Here's Honest Comparison." Publish on BSP blog and distribute via email list.

Week 11: Open referral program — every paying customer who refers a contractor who pays for 3 months gets 1 month free. Keep it simple.

Week 12: Q1 review. Count paying customers. Count monthly churn. Count support tickets and categorize by type. Make a list of the 10 features customers asked for most. Prioritize accordingly for Q2 development.

Month 3 goal: 60 total signups, 40 active, 20 paying. Monthly revenue: ~$3,000. This is not the number that pays the bills — it is the number that proves the model works.

---

# SECTION 6: OPERATIONS

## Technology Stack

This is a mature, proven stack optimized for a solo technical founder who needs to move fast without creating technical debt that kills the company in Year 3.

**Backend:** Django 5.x + Django REST Framework. Python 3.12. PostgreSQL 16 as primary database. Redis for caching and background jobs. Celery for async tasks (email sending, QB sync, report generation).

**Frontend:** HTMX + Alpine.js for the main application. This is a deliberate choice — not React or Vue — because it keeps the codebase in Python/Django world and significantly reduces frontend complexity. The goal is a fast, functional application, not a showcase of JavaScript framework sophistication. Mobile responsiveness via Tailwind CSS.

**Mobile:** Progressive Web App (PWA) for field operations at launch. Native iOS/Android apps are a Year 2 priority if PWA adoption is insufficient. The field crew mobile experience is critical — if it doesn't work on a job site with spotty cell service, the product fails.

**Infrastructure:** AWS (ECS/Fargate for containers, RDS for PostgreSQL, ElastiCache for Redis, S3 for file storage). Estimated infrastructure cost: $150–300/month at launch, scaling to $800–1,500/month at 500 customers. Docker-based local development with production parity.

**Payments:** Stripe. Monthly and annual billing, automatic retries, dunning management. This is non-negotiable — Stripe's payment infrastructure would take months to replicate and costs fractions of a percent of revenue.

**Email:** Postfix/Mailgun for transactional email. Already operational based on existing infrastructure. This is a cost advantage.

**QuickBooks Integration:** Intuit OAuth 2.0 + QuickBooks Online API v3. Webhook-based real-time sync rather than polling. This is the integration built correctly, not bolted on.

**Monitoring:** Sentry for error tracking (free tier adequate at launch). AWS CloudWatch for infrastructure. Simple uptime monitoring (Better Uptime, free tier).

**Development tooling:** GitHub for version control. GitHub Actions for CI/CD. This pipeline needs to be set up in the first week of development — not as an afterthought.

## Team — Who to Hire First and When

**Launch (Q1 2027): Solo**
Douglas handles all development, customer support, sales, and marketing. This is only viable because of 25 years of engineering experience. At fewer than 100 customers, support volume is manageable with a 2-hour daily support window and a good knowledge base. Do not hire in Year 1 unless MRR exceeds $15,000/month.

**Hire #1: Part-Time Customer Success (Q3 2027, ~75 paying customers)**
A customer success person whose job is onboarding, support, and review generation. Not a full-time employee — a 20-hour/week contractor at $25–35/hour. Total cost: $2,000–2,800/month. ROI: each additional customer retained for one extra month pays for approximately 5 hours of their time.

**Hire #2: Contract Marketing / Content Creator (Q4 2027 or Q1 2028)**
Someone who can write blog posts, manage the YouTube channel, and run the G2/Capterra review program. This can be a $1,500–2,500/month freelancer initially. Paid content creation at this stage has better ROI than paid advertising.

**Hire #3: Second Developer (Year 2, 300+ customers)**
At 300+ customers, development velocity becomes the constraint. The backlog of requested features will be 6+ months long. A second Django developer (senior, $90–110K/year fully loaded) is necessary to accelerate product development and prevent churn driven by "they never build what I ask for."

Do not hire a sales team until Year 3. BSP's go-to-market is product-led and content-led. A traditional SaaS sales team requires $60–80K/year per rep and is only cost-effective at $300–500/month ARPU or above.

## Legal Requirements

**Entity formation:** Form a Texas LLC (or convert BCK Construction Services' structure appropriately). Cost: ~$300. Do this before taking the first dollar of payment. Required immediately.

**Terms of Service and Privacy Policy:** These must be drafted before launch. Not negotiable. A template from a SaaS legal firm (Bonterms, Clerky) works for Year 1. Budget: $500–1,000 for review by a startup lawyer.

**QuickBooks Partner Agreement:** Required to use the Intuit API commercially and to display the "Works with QuickBooks" badge. Free. Apply through the Intuit Developer Portal. Processing time: 4–8 weeks. Start this in October 2026 (before MVP completion).

**Data handling:** Texas has not yet enacted a comprehensive consumer privacy law (as of mid-2026), but CCPA applies to California customers. Implement basic data privacy controls (opt-out, data deletion) from day one to avoid retrofit costs.

**Contracts with customers:** Standard click-through SaaS agreement is sufficient at launch. Include limitation of liability, as a contractor storing project financials could conceivably make claims if data is lost.

## Key Partnerships

**Intuit (QuickBooks):** The most important partnership. Certified partner status provides marketing visibility through the QuickBooks App Store (free app listing, accessible to QBO's 7M+ small business users). Apply in Year 1, pursue active listing in Year 2.

**Texas Association of Builders (TAB):** Industry association membership gives credibility and access to contractor communities. Explore whether they have a preferred vendor program. Cost: $500–1,500/year.

**National Association of the Remodeling Industry (NARI):** The primary national trade association for remodelers. Exhibiting at a local NARI chapter event provides direct access to BSP's target customer. Cost per event: $200–800.

---

# SECTION 7: FINANCIAL PROJECTIONS

## Assumptions (State them, own them)

1. Douglas works on BSP as a primary focus starting Q3 2026. Personal living expenses are covered by BCK Construction Services and The Lawn Rangers income during Year 1. BSP does not need to pay his salary until Q3 2027.
2. Average Revenue Per User (ARPU): $149/month in Year 1, growing to $165 in Year 2, $175 in Year 3 as more customers move to Professional tier.
3. Monthly churn: 4% in Q1-Q2 2027 (new product, bugs, wrong-fit customers), declining to 3% in Q3-Q4 2027, 2.5% in Year 2, 2% in Year 3.
4. Customer growth: Primarily organic/content in Year 1. No paid advertising budget until Q3 2027.
5. Infrastructure costs scale with customer count but remain below 5% of revenue at scale.
6. No outside funding is raised. If growth stalls at <50 customers by Q4 2027, funding options are revisited.

## Year 1 — Quarterly (2027)

| | Q1 2027 | Q2 2027 | Q3 2027 | Q4 2027 | **FY 2027** |
|---|---|---|---|---|---|
| New customers added | 20 | 30 | 40 | 45 | 135 |
| Churned customers | 2 | 4 | 6 | 8 | 20 |
| Total paying customers (end) | 18 | 44 | 78 | 115 | 115 |
| Avg customers in quarter | 9 | 31 | 61 | 97 | — |
| Quarterly Revenue | $4,023 | $13,842 | $27,237 | $43,323 | **$88,425** |
| Infrastructure / AWS | $1,350 | $1,800 | $2,100 | $2,700 | $7,950 |
| Tools, subscriptions, software | $600 | $600 | $600 | $600 | $2,400 |
| Marketing (events, content tools) | $1,200 | $1,500 | $1,500 | $1,500 | $5,700 |
| Legal / Admin | $1,500 | $300 | $300 | $300 | $2,400 |
| Customer success contractor (Q3+) | $0 | $0 | $5,400 | $6,000 | $11,400 |
| Founder salary draw (Q3+) | $0 | $0 | $7,500 | $10,000 | $17,500 |
| **Total Expenses** | $4,650 | $4,200 | $17,400 | $21,100 | **$47,350** |
| **Net Profit / (Loss)** | ($627) | $9,642 | $9,837 | $22,223 | **$41,075** |

*Note: The $10,000 initial budget covers Q1 development costs and the operating deficit. All Q2+ expenses are funded by revenue.*

## Year 2 Summary (2028)

| Metric | Value |
|--------|-------|
| Starting customers | 115 |
| Ending customers | 380 |
| Average customers | 248 |
| ARPU | $165/month |
| Annual Revenue | **$490,320** |
| Annual Expenses | $198,000 |
| — Infrastructure | $28,000 |
| — Marketing | $42,000 |
| — Customer success (0.5 FTE) | $38,000 |
| — Second developer (6 months) | $55,000 |
| — Founder salary (full year) | $80,000 |
| — Tools, legal, admin | $18,000 |
| **Net Profit** | **$292,320** |

*Caveat: These Year 2 numbers assume the second developer hire goes well and accelerates product development without major rework of the core architecture. If the hire is delayed or ineffective, revenue growth also slows.*

## Year 3 Summary (2029)

| Metric | Value |
|--------|-------|
| Starting customers | 380 |
| Ending customers | 820 |
| Average customers | 600 |
| ARPU | $175/month |
| Annual Revenue | **$1,260,000** |
| Annual Expenses | $620,000 |
| — Infrastructure | $65,000 |
| — Marketing | $95,000 |
| — Team (3 FTE total) | $340,000 |
| — Tools, legal, admin | $35,000 |
| — Founder salary | $120,000 |
| **Net Profit** | **$640,000** |

*At this stage, BSP has a choice: stay lean and profitable (taking $640K+ out of the business), or reinvest aggressively in growth to pursue the $10M+ ARR opportunity. Year 3 is when that strategic decision actually matters.*

---

# SECTION 8: RISKS & MITIGATION

## Risk 1: JobTread Consolidates the SME Market Before BSP Can Launch

**Likelihood: HIGH. Impact: HIGH.**

JobTread is growing at an extraordinary rate — it hit 7,500 customers in 2025, up from roughly 3,000 in 2023, and was the #6 fastest-growing company in North America on the Deloitte Technology Fast 500. If they maintain that trajectory, they will have 15,000+ customers by the time BSP launches, and the CoConstruct migration cohort may be exhausted.

**Mitigation:** Do not compete with JobTread for the general small-contractor market. BSP's initial positioning must be specifically renovation/remodeling, not "better general contractor software." JobTread does not own renovation. It is winning the general GC space. BSP should concede that fight and win the renovation fight, where JobTread's general workflows are a disadvantage.

*Pivot trigger: If JobTread adds renovation-specific workflow templates and marketing before Q1 2027 launch, the positioning differentiation is significantly weakened. In that case, evaluate whether BSP should narrow further (e.g., kitchen-and-bath remodeling only) or compete on price.*

## Risk 2: Product-Market Fit is Not Found in Year 1

**Likelihood: MEDIUM. Impact: EXISTENTIAL.**

The plan assumes that small renovation contractors will sign up, find value quickly, and retain at 96%+ monthly. That is an assumption, not a fact. It is possible that the first 50 customers try BSP and find it doesn't solve their actual problems — wrong feature priorities, wrong UX assumptions, wrong workflow model.

**Mitigation:** The first 30 customers are treated as a paid beta program, not a product launch. Every customer gets a personal onboarding call. Every support ticket is read by the founder. Weekly feedback aggregation determines what gets built in the next sprint. The antidote to bad PMF is fast feedback loops, not more features.

*Pivot trigger: If monthly active usage rate is below 60% at Month 3 (i.e., 40%+ of paying customers are not logging in weekly), that is a PMF signal, not a retention problem. Stop acquiring customers and diagnose.*

## Risk 3: QuickBooks Integration Breaks and Destroys Trust

**Likelihood: MEDIUM. Impact: HIGH.**

BSP is positioning its QuickBooks integration as a core differentiator. If the integration breaks — due to Intuit API changes, rate limiting, or bugs — and customers lose transactions or get incorrect financial data, the reputational damage is severe in a market that communicates heavily via word-of-mouth.

**Mitigation:** Build with error handling and monitoring from day one. Every QB sync failure sends an immediate alert to the founder's phone. Every customer whose sync fails gets a personal email within 4 hours. Run a dedicated test environment against a real QuickBooks sandbox that runs nightly integration tests. Pursue Intuit's certified partner program not just for marketing but because the certification process catches integration problems early.

*Pivot trigger: If Intuit changes its API terms or pricing in a way that makes the integration unviable (they have done this to other apps), evaluate building a direct accounting module or pivoting to Xero as the primary integration.*

## Risk 4: Founder Burnout / Solo Execution Risk

**Likelihood: MEDIUM. Impact: HIGH.**

Douglas is building this alone while running BCK Construction Services and The Lawn Rangers. The risk is that the workload of building, launching, and supporting a SaaS product while running other businesses becomes unsustainable, and quality or velocity drops.

**Mitigation:** Set explicit time boundaries before development starts. If BSP cannot get a minimum of 25 dedicated hours per week, push the launch to Q2 2027 rather than compromise quality. The $10,000 budget is insufficient to hire meaningful help — the real mitigation is that 25 years of engineering experience means the founder can execute faster per hour than a junior team. If BCK Construction or Lawn Rangers revenue can fund a part-time developer assistant by Q3 2026, use it. One more pair of hands building non-core features (admin tooling, email templates) would meaningfully reduce burnout risk.

*Pivot trigger: If by October 2026 the MVP is not at least 70% complete, the Q1 2027 launch is not viable. Be honest about this in October rather than launching an incomplete product.*

## Risk 5: Churn Exceeds Projections and the Business Is a Treadmill

**Likelihood: MEDIUM. Impact: HIGH.**

SaaS businesses with high monthly churn are treadmills — you run harder and harder just to stay in place. At 6% monthly churn (achievable with a mediocre product), BSP would lose 50% of its customers every year. This means adding 100 customers to replace the ones lost, before growing at all.

**Mitigation:** Churn is almost always a product problem, not a pricing or marketing problem. Customers who see clear value don't churn. The mitigation is to invest disproportionately in onboarding — the first 30 days determine whether a customer retains or churns — and to track feature usage by cohort. Customers who use the QB sync at least once per week churn at half the rate of customers who don't. That kind of insight drives product priority.

*Pivot trigger: If monthly churn exceeds 5% for two consecutive months after Month 6, it is a PMF signal. Stop growth activities and do 20 exit interviews with churned customers before spending another dollar on acquisition.*

---

# SECTION 9: 12-MONTH ROADMAP WITH MILESTONES

*Clock starts July 1, 2026. Launch is Q1 2027.*

## Milestone 1: Working MVP — October 31, 2026

**Success metric:** A single contractor can create a project, write an estimate, generate and send a change order for homeowner approval, create an invoice, and sync it to QuickBooks — end to end, in production, with a real QuickBooks account. Multi-tenant data isolation confirmed. No data loss in 72-hour soak test.

**What this milestone is not:** Feature-complete. Beautiful. Scalable to 10,000 users. Just: the core workflow works.

**Pivot trigger:** If by November 1 the QB sync is not working reliably, do not launch in January. Push to March. A broken QB sync at launch will generate bad reviews that are impossible to overcome.

## Milestone 2: 5 Paying Beta Users — November 30, 2026

**Success metric:** 5 contractors who are not related to the founder are paying $79–149/month and actively using the software to run at least one real project. They have not been offered free service. They chose to pay.

**What this validates:** That the product solves a real problem at the price point. Extremely important signal before spending marketing budget.

**Pivot trigger:** If you cannot get 5 paying beta users from your personal network in November, the product is not ready to launch. Do not proceed to January launch. Use December to do intensive user interviews and determine what is blocking conversion.

## Milestone 3: Public Launch — January 15, 2027

**Success metric:** Product is publicly accessible at buildersstreampro.com. Pricing page is live with clear Stripe integration. A contractor who finds BSP on Google can sign up for a free trial, use the product, and convert to paid without any intervention from the founder. G2 and Capterra profiles are live.

**This is not:** A press launch. A ProductHunt hunt. An announcement on Twitter. It is a quiet, controlled opening of the door to paying customers.

**Pivot trigger:** If the product crashes, loses data, or has a critical bug in the first week post-launch, take it down and fix it. Reputation damage from a bad launch is worse than a delayed launch.

## Milestone 4: 50 Paying Customers — April 30, 2027

**Success metric:** 50 customers paying at least $79/month, with at least 70% logging in at least once in the past 7 days. Monthly churn below 5%. At least 10 customers on the Team tier ($149/month) or higher.

**What this validates:** The product has real retention, not just trial-to-paid conversion. Real retention means real product-market fit signal.

**Pivot trigger:** If by April 30 BSP has fewer than 30 paying customers despite active outreach, reassess the positioning. If it has 50 customers but 40% churn in the first 90 days, stop acquiring and fix the product.

## Milestone 5: Cash Flow Positive — July 31, 2027

**Success metric:** Monthly revenue exceeds monthly expenses (including founder salary draw of $5,000/month) for two consecutive months. At projected growth, this happens around 75–85 paying customers.

**Why this matters:** Cash flow positive means BSP survives without outside capital. It also means the business has time to grow correctly rather than under pressure. This is the financial moment of validation.

**Pivot trigger:** If cash flow positive has not been achieved by September 30, 2027, the customer growth rate is insufficient to sustain the business on $10,000 of initial capital. At that point, evaluate: (a) reduce expenses further and extend runway, (b) seek a small seed round ($100K–250K), or (c) consider that the market fit is weak and this may not be the right product in this form.

## Milestone 6: 100 Paying Customers and First Hire — September 30, 2027

**Success metric:** 100+ paying customers. Monthly churn below 3.5%. MRR at $14,900+. First part-time customer success contractor hired and productive. At least 20 reviews on G2 (average 4.0+ stars) and 15 reviews on Capterra.

**What this signals:** The business is working. Revenue can support a first hire. The review profile is building. The content strategy is generating some inbound. This is the first moment where the plan shifts from "prove the model" to "grow the model."

**Pivot trigger:** If the G2/Capterra average rating is below 4.0 stars at 20 reviews, something is wrong with the product, not the marketing. Do not spend money on growth until the rating is addressed. A 3.7 on Capterra at 20 reviews will actively block conversion from the review channel.

---

## A Note on Honesty

This plan is built on real numbers, stated assumptions, and acknowledged risks. It is not a pitch deck designed to impress investors. The projected numbers are achievable — not certain.

The most likely failure mode is not a bad market or an insurmountable competitor. It is the founder underestimating how long it takes to build a production-quality product, overestimating how fast early customers convert, and running out of energy (not money) before the business reaches escape velocity.

The antidote to that failure mode is simple in concept and difficult in practice: ship faster than you plan, learn from every churned customer, and treat every support ticket as product research.

BSP is a real problem worth solving. The market is real. The timing is as good as it's going to get. The founder has the skills to build it. Whether it succeeds will be determined almost entirely by the quality of execution over the next 18 months.

---

*Document version: 1.0 | June 27, 2026*
*Author: Based on analysis by Claude (Anthropic) for BSP strategic planning*
