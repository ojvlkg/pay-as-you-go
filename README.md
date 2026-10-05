# Pay as you go proxies: how per-GB billing really works, what $5 gets you, and when a monthly plan wins

"Pay as you go" sounds like it settles the question. On a proxy pricing page it often doesn't, because the phrase covers two different meters. You're either billed for the gigabytes you transfer, or you're billed for the IP addresses you hold. Both get labelled pay-as-you-go, and choosing the wrong meter is how people end up buying capacity they never touch.

Here's the short version before the details: if you're crawling pages, monitoring prices, or checking ads from another country, you want per-GB billing. If you need one fixed address in one city that stays yours for six weeks, per-GB is the wrong product entirely, no matter how cheap the headline rate looks.

The rest of this is about what per-GB actually costs once the multipliers land, and where DataImpulse sits in that picture.

## Two meters dressed as one pricing model

Rotating residential and mobile proxies are almost always sold by bandwidth. You buy gigabytes, each request pulls a little data, and the invoice tracks the total. A page fetch of 300 KB is a rounding error against a 5 GB balance, which is why scraping thousands of pages stays cheap.

Static ISP proxies, dedicated datacenter IPs, and most "unlimited bandwidth" plans are sold by IP per month. You pay for the address, and the traffic on it is either unlimited or capped at a level you'll probably never hit.

These two are not interchangeable. An IP-based plan makes no sense for a crawl that needs two million different endpoints across 40 countries, because you'd need thousands of addresses. A bandwidth plan makes no sense for logging into one account from one city every day, because you'd be paying for a rotating identity you don't want.

If your workflow is the second one, note that DataImpulse doesn't sell static ISP proxies at all.

## Why per-GB billing keeps winning on irregular workloads

The interesting part isn't the per-gigabyte rate. It's what happens to gigabytes you don't use.

Most monthly proxy subscriptions reset. Buy a 50 GB plan, burn 6 GB in a slow month, and the other 44 GB evaporate at renewal. Over a year of uneven work, that's not a pricing difference, it's a different business model wearing the same number.

Non-expiring balances change the arithmetic. DataImpulse's own terms are that purchased traffic doesn't expire, so a quiet month costs you nothing and a heavy month doesn't push you into a bigger plan you'll regret next month. For anyone whose data collection comes in bursts (product launches, seasonal price checks, a client project that starts and stops), that's worth more than a 30-cent gap in the per-GB rate.

## The multipliers that break the headline rate

A "$1 per GB" banner is a starting price, not a bill. Three things move it:

**Targeting surcharges.** Country selection is included in DataImpulse's base residential rate. City, state, ZIP, and ASN filters are billed at double the standard per-GB rate on standard residential plans. Datacenter proxies list state, city, ZIP, and ASN targeting as included features, though it's worth confirming current billing treatment with support before you budget on it.

**Success rate.** Every blocked request still costs bandwidth. A provider at $1/GB with a 70% success rate can be more expensive per useful page than one at $1.60/GB that gets through. DataImpulse publishes a 99.51% success rate; treat vendor-published figures as a claim rather than a guarantee, and measure against your own targets.

**The pool you're drawing from.** Resold IPs get burned by other buyers before you ever touch them, which shows up as CAPTCHAs and retries rather than a line item. DataImpulse says it runs a first-party pool sourced through its own network rather than reselling other providers' addresses, which is the reason its ceiling of roughly 90M IPs across 195 countries is worth comparing against larger advertised pools rather than dismissing outright. Bigger isn't automatically better if the same addresses are also being sold to nine other people.

## What $5 actually gets you

DataImpulse has a $5 minimum purchase and no free tier. That's the entry barrier, and it maps differently depending on which pool you're testing:

- $5 → 5 GB of residential traffic at $1/GB
- $5 → 10 GB of datacenter traffic at $0.50/GB
- $5 → 2.5 GB of mobile traffic at $2/GB
- $5 → 1 GB of premium residential traffic at $5/GB

For most people arriving at a pay-as-you-go proxy page, the residential entry pack is the sensible first stop. It's the cheapest per-GB pool that still gives you real consumer IPs, and 5 GB is enough to run a genuine test against the sites you actually care about instead of a generic IP checker.

👉 [Start with the $5 residential pack and see what 5 GB covers on your own targets](https://bit.ly/dataimPulse)

## Every DataImpulse plan currently on the pricing pages

Four proxy types, each with its own tiers. Prices are USD, billed as one-time top-ups rather than recurring subscriptions, and unused traffic doesn't expire.

| Proxy type | Package | Traffic included | Effective rate | Price | Billing | Get it |
| --- | --- | --- | --- | --- | --- | --- |
| Residential | Intro | 5 GB | $1.00/GB | $5 | One-time top-up | [Grab the 5 GB residential plan](https://bit.ly/dataimPulse) |
| Residential | Basic | 50 GB | $1.00/GB | $50 | One-time top-up | [Buy 50 GB of residential traffic](https://bit.ly/dataimPulse) |
| Residential | Standard | 100 GB | $1.00/GB | $100 | One-time top-up | [Top up 100 GB residential](https://bit.ly/dataimPulse) |
| Residential | Advanced | 1 TB | $0.80/GB | $800 | One-time top-up | [Get the 1 TB residential tier with volume pricing](https://bit.ly/dataimPulse) |
| Datacenter | Intro | 10 GB | $0.50/GB | $5 | One-time top-up | [Try 10 GB of datacenter traffic](https://bit.ly/dataimPulse) |
| Datacenter | Standard | 100 GB | $0.50/GB | $50 | One-time top-up | [Buy 100 GB datacenter](https://bit.ly/dataimPulse) |
| Datacenter | Volume | 1 TB | $0.45/GB | $450 | One-time top-up | [Take the 1 TB datacenter tier](https://bit.ly/dataimPulse) |
| Datacenter | Custom | 5 TB+ | Custom | From $2,250 | Custom quote | [Request custom datacenter pricing](https://bit.ly/dataimPulse) |
| Mobile | Intro | 2.5 GB | $2.00/GB | $5 | One-time top-up | [Start with 2.5 GB of 4G/5G mobile proxies](https://bit.ly/dataimPulse) |
| Mobile | Standard | 25 GB | $2.00/GB | $50 | One-time top-up | [Buy 25 GB of mobile traffic](https://bit.ly/dataimPulse) |
| Mobile | Volume | 1 TB | $1.60/GB | $1,600 | One-time top-up | [Get 1 TB of mobile traffic at volume pricing](https://bit.ly/dataimPulse) |
| Mobile | Custom | 5 TB+ | Custom | From $8,000 | Custom quote | [Request custom mobile pricing](https://bit.ly/dataimPulse) |
| Premium residential | Intro | 1 GB | $5.00/GB | $5 | One-time top-up | [Test 1 GB of premium residential](https://bit.ly/dataimPulse) |
| Premium residential | Standard | 10 GB | $5.00/GB | $50 | One-time top-up | [Buy 10 GB of premium residential](https://bit.ly/dataimPulse) |
| Premium residential | Custom | 5 TB+ | Custom | From $20,000 | Custom quote | [Request custom premium residential pricing](https://bit.ly/dataimPulse) |

Two things stand out in that table. The residential and mobile volume tiers both land at a 20% discount versus the standard rate, and the discount only kicks in at 1 TB. Datacenter volume comes in thinner at roughly 10% off. If you're shopping in the 5 to 100 GB range, you're paying list price regardless of which package you pick — so there's no reason to over-buy "to get a better rate" at that scale.

Prices and tiers do move; the numbers above reflect what the vendor's pricing pages and third-party reviews listed most recently. Confirm on the checkout page before you commit.

## How the setup actually goes

There are no contracts to sign and no account manager assigned at these tiers. The documented flow is short:

1. Create an account and open the dashboard.
2. Add a plan and pick the proxy type you want.
3. Top up the balance with the number of GBs you need.
4. Set country targeting, choose rotating or sticky sessions, and pick HTTP(S) or SOCKS5.
5. Move the credentials into your scraper, browser profile, or manager tool.

Sticky sessions matter more than people expect. Rotating IPs give you a new address per request, which is what you want for distributed crawling. A sticky session holds the same IP across a sequence of requests, which you need for anything with a login, a cart, or a multi-step funnel. Getting that setting wrong produces "why does this site keep logging me out" problems that look like a proxy fault but aren't.

The pool supports HTTP, HTTPS, and SOCKS5, and there are integration guides for Selenium, Scrapy, Puppeteer, and the common anti-detect browsers.

## Refunds, payment methods, and the crypto catch

DataImpulse doesn't offer a free trial. What it offers instead is a 7-day money-back guarantee on first purchases paid by card, valid provided you've used less than 80% of the traffic. Crypto payments on entry plans are not refundable.

That distinction is worth reading twice. If your plan is "buy the $5 pack, test it, and claim a refund if it doesn't work," pay by card and keep consumption under 4 GB of the 5 GB. Hit 4.1 GB and the guarantee is gone.

Payment options cover cards, PayPal, and cryptocurrency.

## When you should not buy pay-as-you-go proxies

Per-GB billing is excellent for irregular workloads and bad for a few specific ones. Being honest about the second group saves money:

**You need static ISP addresses.** DataImpulse doesn't sell them, and no per-GB rotating pool substitutes for a fixed residential IP tied to one location.

**You need a fully managed scraping API.** If you'd rather send a URL and get structured JSON back without managing a pool, that's a different product category with different pricing per 1,000 requests.

**Your targets are banks or government portals.** DataImpulse states this isn't the intended use. Rotating residential IPs against financial and government logins creates problems for you and for the pool.

**You're running the largest possible crawl against the most aggressive anti-bot stacks.** DataImpulse's ~90M+ first-party pool is mid-sized next to vendors advertising 175M+ and 400M+. For very high-volume work where IP overlap drives block rates, a bigger pool can win despite costing several times more per gigabyte.

## Where it lands, practically

For a developer testing a scraping idea, a small agency running regional price checks, or anyone whose proxy usage comes in unpredictable bursts, the $1/GB residential entry point plus non-expiring traffic is about as low-risk as paid proxies get. You spend $5, you either get useful pages or you don't, and leftover traffic waits for you instead of expiring.

For a team burning hundreds of gigabytes every month against protected targets, the honest advice is the same as it is for any provider: measure cost per successful request on your own targets before scaling, because the published rate tells you very little about the blocked requests you'll still pay for.

👉 [Check the current DataImpulse plans and start with the $5 top-up](https://bit.ly/dataimPulse)

## FAQ

**Is there a free trial?**
No. The minimum purchase is $5, and the closest equivalent is the 7-day money-back guarantee on card payments for first purchases with under 80% of traffic consumed.

**Does unused traffic expire?**
No. Purchased gigabytes stay on the balance, which is the main practical difference from a monthly subscription that resets.

**Do I need to choose a plan before I know my volume?**
You choose a top-up amount, not a recurring plan, so there's no penalty for starting at 5 GB and adding more later at the same per-GB rate.

**What does advanced targeting cost?**
Country targeting is included. City, state, ZIP, and ASN filters are billed at double the standard per-GB rate on standard residential proxies.

**Which proxy type should I start with?**
Residential if you're hitting sites that block datacenter IPs. Datacenter if speed and cost matter more than looking like a home user. Mobile only when a target genuinely requires carrier IPs, since it costs twice the residential rate.
