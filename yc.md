# Rybbit - YC Application Fall 2025

---

## Founders

**Bill Yang**
- _Profile complete_

**Who writes code, or does other technical work on your product? Was any of it done by a non-founder? Please explain.**
All architecture, backend, frontend, infra and CI/CD are built and maintained by me. There have been a few open source contributors.

**Are you looking for a cofounder?**
Yes. I’m actively open to a co-founder stronger on the distribution side but haven’t yet found a good fit yet.

**Founder Video**
https://www.youtube.com/watch?v=Y5Hgtqeb1GE

---

## Company

**Company name**
Rybbit

**Describe what your company does in 50 characters or less.**
All-in-one open source analytics

**Company URL, if any**
[https://www.rybbit.io/](https://www.rybbit.io/)

**Demo Video**
_None uploaded_

**Please provide a link to the product, if any.**
[https://demo.rybbit.io/21](https://demo.rybbit.io/21)

**What is your company going to make? Please describe your product and what it does or will do.**
- Open source web/product analytics platform with paid cloud offering.
- Full web analytics dashboard, realtime, web vitals tracking, session replay, funnels, journeys, goals, error tracking, uptime monitoring, revenue tracking, experiments.

**Where do you live now, and where would the company be based after YC?**
Irvine CA / SF

**Explain your decision regarding location.**
Irvine isn't a great place to build a startup, so I'd like to build Rybbit in a tech hub like SF in its early days.

---

## Progress

**How far along are you?**
I launched in early May and the product is fully functional. Both the self-hosted and cloud versions are available. I have 7,500 Github stars and 20,000 Docker image pulls for self-hosting so far.

**How long have each of you been working on this? How much of that has been full-time? Please explain.**
I started in mid-January, and it's been all part-time. I will go full-time if I join YC.

**What tech stack are you using, or planning to use, to build this product? Include AI models and AI coding tools you use.**
**Tech stack:**
- TS monorepo with Next.js and Node.js backend
- Stripe/BetterAuth/Drizzle
- Postgres/Clickhouse
- Hetzner/Cloudflare R2 (only for cloud)

**AI Tools:**
- Cursor
- Claude Code

**Are people using your product?**
Yes

**How many active users or customers do you have? How many are paying? Who is paying you the most, and how much do they pay you?**
I have ~1,500 signups since launch, and out of those ~40 are paying customers. $840 MRR.

**Do you have revenue?**
Yes

**How much revenue do you have?**
- **Jun 2025**: $1057
- **May 2025**: $1430
- **Apr 2025**: $0
- **Mar 2025**: $0
- **Feb 2025**: $0
- **Jan 2025**: $0
- **Dec 2024**: $0

**Where does your revenue come from?**
All of my revenue comes from monthly/annual subscriptions.
(My June revenue is lower than May because I switched the default checkout subscription from annual to monthly to be more user friendly)

**Anything else you would like us to know regarding your revenue or growth rate?**
I had viral launch on Reddit and received 5k Github stars in just over a week. I get 400-600 new users on my landing page every day, and ~7% of them signup for at least the free plan. I currently get 3-4 new paid subscriptions every week.

You can see my public analytics for my landing page on [https://demo.rybbit.io/21](https://demo.rybbit.io/21)

**If you are applying with the same idea as a previous batch, did anything change?**
_Unanswered_

**If you have already participated or committed to participate in an incubator, "accelerator" or "pre-accelerator" program, please tell us about it.**
_Unanswered_

---

## Idea

**Why did you pick this idea to work on? Do you have domain expertise in this area? How do you know people need what you're making?**
I built Rybbit for myself. I run Tomato.gg (1.5M monthly visits) and couldn't find an analytics platform I liked after GA4's migration made it unusable.

My unique domain expertise:
1.  Built Tomato.gg into the #1 World of Tanks analytics site despite entering 5 years late.
2.  Self-hosted all Tomato.gg infra, including timeseries database with billions of rows and 1+ tb raw data.
3.  Tested Rybbit with Tomato.gg's 10M+ monthly events from day one.

I know people need this because:
-   Users spent days trying to self-host Rybbit despite easier alternatives.
-   Customers explicitly tell me they migrated from GA, PostHog, and Plausible.
-   40 paying customers in 2 months with minimal marketing.

**Who are your competitors? What do you understand about your business that they don't?**
Two segments exist:
-   **Enterprise (PostHog, Mixpanel, Amplitude):** Feature-rich but complex.
-   **Privacy-focused (Plausible, Fathom):** Simple but limited.

Rybbit fills the gap: powerful analytics with intuitive UI. My competitors don't believe you can be both simple AND powerful. My experience building Tomato.gg as an 'everything app' for World of Tanks proves otherwise.

Plausible will never go beyond privacy friendly web analytics because they are scared of bloat. Posthog has gone to the other extreme by being unapologetically maximalist in being a huge platform.

My current traction shows this resonates with startups and SMBs who want more than Plausible but find Posthog overwhelming.

**How do or will you make money? How much could you make?**
SaaS subscriptions: $19+/mo Pro tier, custom enterprise pricing.
-   **Current:** $800 MRR, 40 paying customers, 2.7% free-to-paid conversion.
-   Open source drives top-of-funnel (7.5k GitHub stars → 1,500 signups → 40 paid).

**Current Pro tiers ($19+/mo):**
-   Managed hosting + automatic updates
-   Advanced features: funnels, session replay, web vitals, realtime, ...

**Path to $10M ARR:**
-   20,000 paying SMBs at $40/m avg
-   OR 100 enterprises at $8k/mo avg

**Which category best applies to your company?**
Analytics

**If you had any other ideas you considered applying with, please list them.**
_Unanswered_

---

## Equity

**Have you formed ANY legal entity yet?**
No

**Describe the planned equity ownership breakdown.**
100% - Bill Yang

**Have you taken any investment yet?**
No

**Are you currently fundraising?**
No

---

## Curious

**What convinced you to apply to Y Combinator? Did someone encourage you to apply? Have you been to any YC events?**
I know a few people who have done YC and all of them have recommended it. One of my best friends, Chris Weaver (Onyx W24), encouraged me to apply and I nearly joined his company twice.

My mentor from my first internship, Jacob Grafenstein (Elayne S24), also did YC.

Chris took me to the Brian Chesky event during his W24 batch.
