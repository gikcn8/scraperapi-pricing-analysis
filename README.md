# ScraperAPI Free API Key: How to Get One, What the Free Plan Actually Covers, and Which Paid Plan Makes Sense — Complete Guide to Credits, Pricing Tiers, and Getting Started Without a Credit Card

So you've been googling "scraperapi api key free" and you're not quite sure what you're going to get. Is it actually free? Will it expire? What can you even do with 1,000 credits? And honestly — is ScraperAPI worth it once the free trial is over?

I've been down that rabbit hole. Here's everything in plain English.

---

**What Is ScraperAPI and Why Does the API Key Matter?**

ScraperAPI is a web scraping API that handles the part of scraping nobody wants to deal with: rotating proxies, CAPTCHA solving, JavaScript rendering, and anti-bot bypasses. You send it a URL, it sends back the HTML. Simple idea, a lot of engineering underneath.

Every request you send to ScraperAPI has to be authenticated — meaning you need an API key. Without it, nothing works. Your API key is basically your identity on the platform, and it's also how ScraperAPI counts your credits.

The good news: you can get an API key for free, no credit card required. The more nuanced news: what "free" actually means depends on whether you're in your first 7 days or after that.

---

**How to Get Your ScraperAPI Free API Key (Step by Step)**

Getting started takes about two minutes:

1. Head to ScraperAPI's signup page (no credit card required)
2. Enter your email and create a password
3. Confirm your email address
4. Log into your dashboard — your API key is sitting right there on the main screen

That's it. You've got a key. You can start making requests immediately.

The moment you sign up, ScraperAPI gives you **5,000 free API credits for the first 7 days**. Think of this as the real trial window — it's meant to give you enough room to test the API at a realistic scale before you decide whether to stay.

After those 7 days, you drop to the permanent free plan: **1,000 credits per month**, with a maximum of 5 concurrent connections. That's the ongoing free tier. It doesn't expire, it resets monthly, and it doesn't require any payment information.

> 💡 **Quick tip**: If you need extra credits during testing and the 5,000 trial isn't enough, ScraperAPI's support team can sometimes extend it. It doesn't hurt to reach out.

[👉 Sign up for a free ScraperAPI API key — no credit card needed](https://www.scraperapi.com/?fp_ref=coupons)

---

**What Can You Actually Do With 1,000 Free Credits?**

Here's where things get interesting — and a little deceptive if you don't know about the credit multiplier system.

ScraperAPI doesn't charge a flat "1 credit per request" for everything. The credit cost depends on *what* you're scraping and *how* you're scraping it:

| Request Type | Credits Used |
|---|---|
| Standard page (plain HTML) | 1 credit |
| JavaScript rendering (`render=true`) | +10 credits (total: 10–11) |
| Premium proxies (`premium=true`) | +10 credits |
| Premium + JS rendering combined | 25 credits |
| Ultra-premium proxies | +30 credits |
| Ultra-premium + JS rendering | **75 credits** |
| Amazon product pages | 5 credits (auto-applied) |
| Google/Bing SERP | 25 credits (auto-applied) |
| LinkedIn | 30 credits (auto-applied) |

So on the free plan, 1,000 credits means:
- Up to **1,000 basic HTML scrapes** (no JS, plain sites)
- Or about **100 JavaScript-rendered pages**
- Or about **40 Amazon product pages**
- Or about **40 Google search results**
- Or a depressing **13 ultra-premium + JS pages**

The domain-based multipliers are automatic — you don't opt into them. The moment your request hits an Amazon URL, 5 credits are deducted per request whether you wanted that or not.

For the free tier, the 1,000 credits is genuinely enough to test the API on simple sites or small hobby projects. It's not enough to run any real production workload. That's kind of the point — it's a taste, not a feast.

---

**Where to Find Your API Key in the Dashboard**

Once you're logged in, your API key is displayed prominently on the dashboard homepage. If you ever think it's been compromised or exposed somewhere you didn't intend, you can regenerate it:

1. Click your email address in the bottom left corner of the dashboard
2. Select **Manage API keys**
3. Click **New API key**
4. Copy the new key and replace the old one in your code

One thing to know: you can only regenerate a key once every 24 hours, so don't do it by accident right before a big scraping job.

---

**ScraperAPI Plans: Full Comparison (Free Through Enterprise)**

The free API key gets you started, but if you're planning to use ScraperAPI for anything beyond prototyping, you'll need to understand the paid tiers. Here's the full picture:

| Plan | Monthly Price | Annual Price (per month) | API Credits | Concurrent Threads | Geotargeting | Pay-As-You-Go |
|---|---|---|---|---|---|---|
| **Free** | $0 | — | 1,000/month | 5 | US only | No |
| **Hobby** | $49/mo | $44.10/mo | 100,000 | 20 | US & EU | No |
| **Startup** | $149/mo | $134.10/mo | 1,000,000 | 50 | US & EU | No |
| **Business** | $299/mo | $269.10/mo | 3,000,000 | 100 | 50+ countries | No |
| **Scaling** | $475/mo | $427.50/mo | 5,000,000 | 200 | 50+ countries | ✅ Yes |
| **Professional** | $975/mo | $877.50/mo | 10,500,000 | 300 | 50+ countries | ✅ Yes |
| **Advanced** | $1,975/mo | $1,777.50/mo | 21,500,000 | 500 | 50+ countries | ✅ Yes |
| **Enterprise** | Custom | Custom | 22M+ | 500+ | Full + dedicated | ✅ Yes |

A few important details that the table can't quite capture:

**Annual billing saves 10% on all paid plans.** If you know you're going to use ScraperAPI long-term, the annual option is a straightforward way to cut costs.

**Pay-As-You-Go only kicks in at Scaling ($475/mo) and above.** This is a bigger deal than it sounds. On Hobby, Startup, and Business, if you burn through your credits before the month ends, you're just cut off. No warning email, no grace period — your requests simply start failing. Your options at that point are: wait for the billing cycle to reset, or upgrade to the next tier.

**Geotargeting beyond US & EU requires the Business plan.** If you need to scrape from specific countries in Asia, South America, or elsewhere, the Hobby and Startup plans won't do it.

**The Scaling plan is labeled "most popular"** for a reason — it's the first tier with PAYG, which means you're not stuck at a hard wall when you go over budget.

Purchase links by plan:

- [👉 Get started free — claim your free API key](https://www.scraperapi.com/?fp_ref=coupons)
- [👉 Try the Hobby Plan — $49/month, 100,000 credits](https://www.scraperapi.com/?fp_ref=coupons)
- [👉 Startup Plan — $149/month, 1,000,000 credits](https://www.scraperapi.com/?fp_ref=coupons)
- [👉 Business Plan — $299/month, 3,000,000 credits + global geotargeting](https://www.scraperapi.com/?fp_ref=coupons)
- [👉 Scaling Plan — $475/month, 5,000,000 credits + PAYG overage](https://www.scraperapi.com/?fp_ref=coupons)
- [👉 Professional Plan — $975/month, 10.5M credits](https://www.scraperapi.com/?fp_ref=coupons)
- [👉 Advanced Plan — $1,975/month, 21.5M credits](https://www.scraperapi.com/?fp_ref=coupons)
- [👉 Enterprise — Custom pricing, talk to sales](https://www.scraperapi.com/?fp_ref=coupons)

---

**The Credit Multiplier: The One Thing You Must Understand Before Choosing a Plan**

This is the part most guides gloss over, and it's the reason a lot of people feel blindsided by their first bill.

The headline number on each plan — "100,000 credits" for Hobby — assumes a world where every request costs exactly 1 credit. In practice, almost no production use case works that way.

Let me show you what the Hobby plan ($49/month, 100K credits) actually gets you in realistic scenarios:

| Use Case | Credits Per Request | Actual Requests on Hobby |
|---|---|---|
| Scraping basic news/blog pages | 1 | 100,000 pages |
| Scraping JS-heavy sites | 10 | 10,000 pages |
| Scraping Amazon product pages | 5 | 20,000 pages |
| Scraping Google search results | 25 | 4,000 SERPs |
| Protected sites, ultra-premium + JS | 75 | ~1,333 pages |

The math is brutal at the high end. Seventy-five credits per request means your "100,000-credit" plan runs out after just 1,333 pages — that's a single afternoon of scraping a difficult target.

The credits also **do not roll over**. Whatever you don't use resets at the start of your next billing cycle.

None of this means ScraperAPI is a bad deal — it means you need to know your use case before picking a plan. If you're scraping straightforward e-commerce sites or simple HTML pages, the credit math is very reasonable. If you're planning to scrape protected, JavaScript-heavy targets at high volume, run the multiplier math first.

---

**What ScraperAPI Is Actually Good At (And Where It Struggles)**

ScraperAPI isn't equally strong on every website. Based on independent benchmarks from early 2026:

**Where it shines:**
- **Amazon** — 98% success rate, comprehensive structured data endpoints returning 18+ parsed fields (ASIN, price, ratings, reviews, BSR, images, seller info)
- **Zillow** — 100% success rate, fastest response times
- **Google SERP** — strong structured endpoint, though at 25 credits per SERP it adds up fast
- **Walmart, Etsy, eBay** — all above 93% success rate
- **Standard HTML sites** — highly reliable at 1 credit per request

**Where it struggles:**
- **Instagram, Twitter/X, Booking.com** — 0% success rate in independent testing. These simply don't work.
- **Login-required pages** — ScraperAPI's Terms of Service explicitly forbid scraping behind login walls. It won't handle form filling, OAuth flows, or 2FA.
- **Stale data warning** — on difficult targets, ScraperAPI applies a 10-minute forced result cache. If you're tracking real-time pricing or stock levels, this matters.

The average overall success rate across all tested sites is around 63%, which is slightly above the industry average but a far cry from the 99.99% claimed for structured data endpoints specifically.

Ratings from real users back this up — ScraperAPI holds a 4.6/5 on Capterra (62 reviews), 4.5/5 on Trustpilot, and 4.4/5 on G2. Ease of use scores are particularly high (4.9/5 on Capterra), and the documentation is consistently praised. The main complaints cluster around credit costs being higher than expected and reliability on harder targets.

---

**Available Discount Codes and Current Promotions**

ScraperAPI doesn't run frequent public sales, but there are a few verified discount codes that have been circulating and tested:

- **SCRAPE10** — 10% off on paid plans (widely verified)
- **ANWAR10** — 10% off all subscription plans
- **Annual billing** — a built-in, reliable 10% discount if you commit to a full year

The 10% codes may apply at checkout when subscribing. Worth trying before you pay full price.

> Pro tip: The most reliable discount is always the annual billing toggle — it's right there on the pricing page and never requires a code.

[👉 Start free and apply your discount at checkout](https://www.scraperapi.com/?fp_ref=coupons)

---

**Making Your First API Request**

Once you have your free API key, making your first request is genuinely straightforward. ScraperAPI supports multiple integration methods:

**Simple GET request (curl):**
bash
curl "https://api.scraperapi.com?api_key=YOUR_API_KEY&url=https://example.com"


**Python example:**
python
import requests

payload = {
    'api_key': 'YOUR_API_KEY',
    'url': 'https://example.com'
}

response = requests.get('https://api.scraperapi.com', params=payload)
print(response.text)


**With JavaScript rendering enabled:**
python
payload = {
    'api_key': 'YOUR_API_KEY',
    'url': 'https://example.com',
    'render': 'true'
}


**Via proxy mode** (for tools that accept a proxy configuration):

http://scraperapi:YOUR_API_KEY@proxy-server.scraperapi.com:8001


You can also use ScraperAPI through their SDK (available for Python and Node.js), through their DataPipeline for scheduled no-code scraping jobs, via their MCP Server for LLM integrations, or through a community n8n node for workflow automation.

One practical note: always set a 70-second timeout in your application. ScraperAPI recommends this for maximum success rates, especially on harder targets that take longer to process.

---

**Who Should Actually Sign Up for the Free Plan?**

The free ScraperAPI API key is a legitimately good fit if:

- You're **prototyping a scraping project** and want to test the waters before spending money
- You're learning web scraping and need a **simple, documented API** to practice with
- You have a **small personal project** that doesn't need more than 1,000 basic page requests per month
- You want to **test your target sites** before committing to a paid plan (do your Amazon pages actually work? How many credits do they cost? Test it first on the free tier)
- You're building **something for a hackathon or demo** and don't need production scale

The free plan is not a good fit if you're trying to run any kind of recurring data pipeline or production scraping job. For that, Hobby at $49/month is the realistic entry point.

---

**Choosing the Right Paid Plan**

Here's a rough guide based on use case:

**Hobby ($49/month):** Best for side projects, freelancers scraping a few sites occasionally, or developers still evaluating before scaling up. The 20 concurrent threads are enough for small parallel jobs. The US & EU geotargeting limitation is worth noting if you need other regions.

**Startup ($149/month):** The jump from 100K to 1 million credits is substantial. If you're running a real small-to-medium scraping workflow — price monitoring for an e-commerce business, regular data pulls for market research — this is where most indie developers land.

**Business ($299/month):** The first plan with global geotargeting (50+ countries). If your scraping needs country-level targeting outside of the US and EU, this is the minimum plan you need. Also the first tier with unlimited analytics history.

**Scaling ($475/month):** The "most popular" tier for a reason — it's the first plan where you're not hard-cut-off when credits run out. Pay-As-You-Go means your scraper keeps working; you just pay for the overage. If you've ever had a production scraper silently fail mid-month because you hit your credit limit, you'll understand why this matters.

**Professional and Advanced:** High-volume recurring pipelines, agency-scale data collection, or situations where you need 300–500 concurrent threads. Priority routing and priority support are included.

**Enterprise:** You're past the point of self-serve. Custom credits, a dedicated support team, your own Slack channel with ScraperAPI's team. [👉 Talk to their sales team here.](https://www.scraperapi.com/?fp_ref=coupons)

---

**The Bottom Line**

Getting a free ScraperAPI API key takes two minutes and genuinely costs nothing. The 5,000-credit trial window in the first 7 days gives you enough room to actually test your use case at a realistic scale — don't just make three requests and call it done. Use those credits deliberately: try your actual target URLs, check the credit cost (the `sa-credit-cost` header in every response tells you exactly what each request cost), and do the math on what a paid plan would actually get you before committing.

The free plan's permanent 1,000 credits per month is honest about what it is — a testing tier, not a production option. If you need more, the Hobby plan at $49/month is a reasonable starting point for real projects, and the annual billing discount knocks it down to $44.10/month.

Just remember: the credit multiplier is the whole game. Know what you're scraping, run the math, and don't let the headline credit number be the only thing you look at.

[👉 Claim your free ScraperAPI API key — no credit card required](https://www.scraperapi.com/?fp_ref=coupons)
