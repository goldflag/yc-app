# Rybbit - YC Fall 2025 Application

## Founders

**Bill Yang**  
*Profile complete*

### Technical Work
**Who writes code, or does other technical work on your product? Was any of it done by a non-founder? Please explain.**

All architecture, backend, frontend, infra and CI/CD are built and maintained by me. There have been a few open source contributors.

### Looking for Cofounder
**Are you looking for a cofounder?**

Yes. I'm actively open to a co-founder stronger on the distribution side but haven't yet found a good fit yet.

### Founder Video
*(No information provided)*

## Company

**Company name:** Rybbit

**Describe what your company does in 50 characters or less:**  
All-in-one open source web + product analytics

**Company URL:** https://www.rybbit.io/

**Demo Video:** None uploaded

**Product Link:** https://demo.rybbit.io/21

### Product Description
**What is your company going to make? Please describe your product and what it does or will do.**

Rybbit is an open source web/product analytics platform with a paid cloud offering.

It has web analytics, web vitals tracking, session replay, funnels, journeys, goals, error tracking, and uptime monitoring.

A lot of sites run 2-3 tracking scripts (for example Google Analytics for general analytics and Hotjar for session replays) which is really bad for performance. Rybbit will have best features from each analytics platform in one place.

Rybbit stays easy to use despite having a lot of features through good defaults that "just work" -- like how iOS wins over Android despite low customizability because the default experience is what matters for most users.

### Location
**Where do you live now, and where would the company be based after YC?**  
Irvine CA / SF

**Explain your decision regarding location:**  
Irvine isn't a great place to build a startup, so I'd like to build Rybbit in a tech hub like SF in its early days.

## Progress

### Development Stage
**How far along are you?**

I launched in early May and the product is fully functional. Both the self-hosted and cloud versions are available. I have 7,500 Github stars and 22,000 Docker image pulls for self-hosting so far.

**How long have each of you been working on this? How much of that has been full-time? Please explain.**

I started in mid-January, and it's been all part-time. I ran Tomato.gg alongside my job for the entire time, so I'm used to juggling both.

### Tech Stack
**What tech stack are you using, or planning to use, to build this product? Include AI models and AI coding tools you use.**

**Tech stack:**
- TS monorepo with Next.js and Node.js backend
- Stripe/BetterAuth/Drizzle
- Postgres/Clickhouse
- Hetzner/Cloudflare R2 (only for cloud)

**AI Tools:**
- Cursor
- Claude Code

### Usage & Revenue
**Are people using your product?** Yes

**How many active users or customers do you have? How many are paying? Who is paying you the most, and how much do they pay you?**

I have ~1,600 signups since launch, and out of those ~45 are paying customers. $900 MRR.

I am also have an upcoming 2k MRR enterprise deal in which the customer (a gaming division of Tencent) will be onboarded in 2 months.

**Do you have revenue?** Yes

### Monthly Revenue

| Month | Revenue |
|-------|---------|
| Jun 2025 | $1,057 |
| May 2025 | $1,430 |
| Apr 2025 | $0 |
| Mar 2025 | $0 |
| Feb 2025 | $0 |
| Jan 2025 | $0 |
| Dec 2024 | $0 |

**Where does your revenue come from?**

All of my revenue comes from monthly/annual subscriptions.

(My June revenue is lower than May because I switched the default checkout subscription from annual to monthly to be more user friendly)

**Anything else you would like us to know regarding your revenue or growth rate?**

I had viral launch on Reddit 2 months ago and received 5k Github stars in just over a week. I get 400-600 new users on my landing page every day, and ~7% of them signup for at least the free plan. I currently get 3-4 new paid subscriptions every week.

You can see my public analytics for my landing page on https://demo.rybbit.io/21

I am also working on a partnership with an AI powered user intent startup to power their session replays infrastructure.

## Idea

### Motivation & Domain Expertise
**Why did you pick this idea to work on? Do you have domain expertise in this area? How do you know people need what you're making?**

I built Rybbit for myself. I run Tomato.gg (1.5M monthly visits) and couldn't find so I built my own.

**My unique domain expertise:**

1. Built Tomato.gg into the #1 World of Tanks analytics site despite entering 5 years late
2. Self-hosted all Tomato.gg infra, including timeseries database with billions of rows and 1+ tb raw data
3. Tested Rybbit with Tomato.gg's 10M+ monthly events

**I know people need this because:**

1. Users spent days trying to self-host Rybbit despite easier alternatives (it was difficult to self-host at launch but I have fixed this)
2. Customers explicitly tell me they migrated from GA, PostHog, and Plausible
3. 45 paying customers in 2 months with minimal marketing

Every year it becomes easier to build on the web -- even more so in 2025 because of tools like Lovable. But analytics platforms are becoming more and more difficult to use. A non-technical person building a business using Lovable or Bolt is probably only going to have access to basic data. Rybbit makes whole categories of analytics (product analytics + session replays) accessible to less technical customers.

### Competition
**Who are your competitors? What do you understand about your business that they don't?**

**Two segments exist:**

- **Enterprise** (PostHog, Mixpanel, Amplitude, Google Analytics): Feature-rich but complex and over indexed into B2B SaaS
- **Privacy-focused** (Plausible, Fathom): Simple but extremely limited

There's a large gap between these two that Rybbit fills.

My competitors don't believe you can be both simple + powerful. My experience building Tomato.gg as an 'everything app' World of Tanks for proves otherwise. Video games statistics are a lot more complicated than website analytics in many ways, but 3rd party gaming statistics sites have successfully gotten regular gamers to be addicted to tracking their stats.

I've also noticed many of the best analytics platforms are all concentrated into B2B SaaS. It's probably the most lucrative market, but it's a small fraction of internet businesses. Non B2B SaaS companies like media companies are generally stuck with Google Analytics.

**Rybbit also has counter-positioning because:**

1. Plausible/Fathom can't add more features because it goes against their branding as dead-simple one page dashboards
2. Posthog/GA/Amplitude can't simplify their platform because existing enterprise customers rely on complicated workflows

### Business Model
**How do or will you make money? How much could you make?**

SaaS subscriptions: $19+/mo Pro tier, custom enterprise pricing.  
Current: $900 MRR, 45 paying customers

Open source drives top-of-funnel (7.5k GitHub stars → 1,500 signups → 40 paid).

**Current Pro tiers ($19+/mo):**
- Managed hosting + automatic updates
- Advanced features: funnels, session replay, web vitals, realtime, ...

**Path to $10M ARR:**
- 20,000 paying SMBs at $40/m avg
- OR 100 enterprises at $8k/mo avg

**Category:** Analytics

## Equity

**Have you formed ANY legal entity yet?** No

**Planned equity ownership breakdown:**  
100% - Bill Yang

**Have you taken any investment yet?** No

**Are you currently fundraising?** No

## Additional Information

### Why YC?
**What convinced you to apply to Y Combinator? Did someone encourage you to apply? Have you been to any YC events?**

I know a few people who have done YC and all of them have recommended it. One of my best friends, Chris Weaver (Onyx W24), encouraged me to apply and I nearly joined his company twice.

My mentor from my first internship, Jacob Grafenstein (Elayne S24), also did YC

Chris took me to the Brian Chesky event during his W24 batch.

### Legal
**List each founder's citizenship(s):**  
Bill Yang, United States

**Are any of the founders covered by noncompetes or intellectual property agreements that overlap with your project?** No

**Is there anything else we should know about your company? Pending lawsuits, cofounders who have left, etc.** No
