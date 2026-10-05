# NetNut Pricing: All Six Residential Tiers, the Real Cost per GB, and the Pay-As-You-Go Route Around the $99 Minimum

NetNut's pricing page answers the "how much" question in about four seconds — $99 a month — and then hands you six GB buckets and an annual-billing toggle that quietly changes every number. If you came here to figure out what a realistic NetNut bill looks like for a 50 GB/month scraping job, the table below is the short version, and it isn't $99.

## NetNut's residential pricing, plan by plan

NetNut sells rotating residential traffic in fixed monthly GB buckets. There's no slider, no pay-as-you-go top-up, and no per-request option on the public page.

| Plan | Traffic included | Billed monthly | Effective rate | Billed annually (per month) | Effective rate |
| --- | --- | --- | --- | --- | --- |
| Starter | 28 GB | $99/mo | $3.53/GB | $84/mo | $3.00/GB |
| Advanced | 72 GB | $249/mo | $3.45/GB | $210/mo | $2.93/GB |
| Production | 150 GB | $499/mo | $3.32/GB | $423/mo | $2.82/GB |
| Semi-Pro | 350 GB | $999/mo | $2.85/GB | $850/mo | $2.43/GB |
| Professional | 800 GB | $1,999/mo | $2.49/GB | $1,696/mo | $2.12/GB |
| Master | 2 TB | $3,750/mo | $1.87/GB | $3,180/mo | $1.59/GB |

Those figures come straight from NetNut's own rotating-residential pricing block, which is repeated verbatim across its country and use-case pages. One line above it matters more than it looks: "prices subject to change based on use cases." In other words, the list is a starting point for a conversation, not a checkout price.

A quick note if you've seen NetNut quoted at $6/GB or even $29/GB elsewhere. Those numbers float around in comparison posts, and they're usually either a different product line, an older scrape, or a mixed-up entry price. The published block above is the one to anchor on.

## What every NetNut plan includes

All six tiers come with the same feature set — the only variable is bandwidth:

- Unlimited concurrent connections
- City and state level targeting
- API access
- IP whitelisting
- A dedicated account manager

That last item explains a chunk of the price. NetNut isn't selling bandwidth to anonymous buyers; it's selling bandwidth plus a named human who'll sit in a remote session with your dev if the integration misbehaves. Whether that's worth $3.53/GB versus $1/GB depends entirely on whether you're the kind of buyer who ever emails support.

NetNut's network pitch is the other half of the story: 85M+ residential IPs across 195+ countries, routing through ISP partnerships rather than peer devices, which the company markets as "one-hop connectivity." The practical claim is lower latency and better session stability than SDK-based pools, because traffic isn't bouncing through someone's idle laptop.

## The three things the pricing page doesn't say out loud

**1. There's no pay-as-you-go below $99.** If your project needs 8 GB this month, you still buy 28 GB. That works out to an effective $12.38/GB for the traffic you actually use. NetNut's entry tier is a floor, not a starting point.

**2. Bandwidth is metered in both directions.** NetNut's billing FAQ is explicit: usage is the sum of data sent *to* and *from* the target site, including request headers, request data, response headers, and response data. If your scraper POSTs fat JSON payloads or pulls large headers, you're paying for the upload side too. That's not unusual in the industry, but it does mean 28 GB is less runway than it sounds.

**3. Whether unused GB rolls over isn't stated on the pricing block.** It's a genuinely important question for anyone with lumpy traffic, and the honest answer is: ask before you sign. NetNut's trial process also runs through sales — you sign up, then contact the team via WhatsApp, Telegram, Skype, email, or live chat with your product type, target domains, use case, and required bandwidth. It's an approval flow, not a self-serve free tier.

One more gap: the public pricing block covers rotating residential only. Static ISP, mobile, and datacenter rates aren't published there — those come out of a sales conversation. Fine if you enjoy sales conversations.

## The annual toggle is worth roughly 11–15%

Comparing the two columns, paying yearly moves the entry plan from $3.53 to $3.00/GB and the 2 TB plan from $1.87 to $1.59/GB. On the Master tier, that's a $6,840 annual difference. It also locks you into 12 months of a fixed bucket, which is the exact opposite of what you want if your scraping volume swings with the calendar.

## A different pricing model: DataImpulse, where traffic doesn't expire

If your reaction to "28 GB minimum, bills monthly, no small plans" is a sigh, the alternative model is worth ten minutes of your time.

DataImpulse prices residential traffic at **$1/GB with a $5 minimum** — you buy 5 GB for $5, and it sits on your account until you use it. Traffic never expires. Buy 1 TB and the rate drops to $0.80/GB; at 5 TB it's $0.70/GB. The pool is 90M+ ethically sourced IPs across 195+ countries, with rotating and sticky sessions, HTTP(S) and SOCKS5, and free country-level targeting. City, ASN, and ZIP filtering on standard residential is billed at double the per-GB rate.

Here's the full set of DataImpulse products, since the residential tier isn't the only line:

| Product | Rate | Minimum purchase | What you get for the minimum | Volume pricing | Get started |
| --- | --- | --- | --- | --- | --- |
| Residential | $1/GB | $5 | 5 GB | $0.80/GB at 1 TB, $0.70/GB at 5 TB | Start with 5 GB of residential proxies for $5 |
| Premium Residential | $5/GB | $5 | 1 GB | $50 for 10 GB; custom from $20,000 at 5 TB+ | See DataImpulse premium residential rates |
| Mobile | $2/GB | $5 | 2.5 GB | — | Check DataImpulse mobile proxy pricing |
| Datacenter | $0.50/GB | $5 | 10 GB | — | Compare DataImpulse datacenter plans |

Two details worth knowing before you buy. Premium residential includes country, city, ASN, and ZIP targeting at no extra charge, plus a personal account manager — the tier for people who specifically want the hand-holding NetNut bundles into every plan. And intro-plan purchases come with a 7-day money-back guarantee on card payments, as long as you've used under 80% of the traffic; crypto purchases don't qualify for a refund.

## Same traffic, two very different invoices

This is where "cheap per GB" arguments either survive contact with reality or don't.

| Monthly traffic | NetNut (monthly billing) | DataImpulse | Difference |
| --- | --- | --- | --- |
| 28 GB | $99 | $28 | −72% |
| 72 GB | $249 | $72 | −71% |
| 150 GB | $499 | $150 | −70% |
| 350 GB | $999 | $350 | −65% |
| 800 GB | $1,999 | $800 (1 TB tier) | −60% |
| 2 TB | $3,750 ($3,180 annual) | ~$1,638 (at $0.80/GB) | −56% |

The gap narrows as volume climbs, but it never closes — NetNut's annual-billed 2 TB rate of $1.59/GB is still roughly double DataImpulse's $0.80/GB tier.

That said, this isn't a like-for-like comparison, and pretending otherwise would be dishonest. NetNut is selling ISP-connected infrastructure with a dedicated account manager attached to every tier, plus published 500B+ monthly routed request volume and a support model built around enterprise onboarding. If your workload genuinely depends on session stability against aggressively protected targets, and your finance team wants an account manager on the invoice, that difference is real and you should pay for it.

## When NetNut's pricing is the right call

- **You consistently burn 800 GB to 2 TB a month and want a vendor relationship**, not a self-serve dashboard. At that volume the per-GB premium is a procurement line item, not a project killer.
- **You need mobile, ISP static, and residential from one supplier** with one contract and one support thread.
- **Your traffic is predictable enough that annual prepay makes sense.** The 11–15% discount only pays off if you'd have spent the money anyway.
- **Compliance or procurement requires a named account manager** and documented onboarding. NetNut is structured for that from day one.

## When it isn't

- **You're below 100 GB a month.** You're paying for 28 GB whether you use 8 or 27, and the effective rate on partially-used buckets climbs fast.
- **Your workload is seasonal.** A fixed monthly bucket is the wrong instrument for pre-holiday spikes followed by quiet quarters. Non-expiring traffic is the right instrument.
- **You're still testing.** Buying a $99 bucket to find out whether a provider works on your targets is an expensive experiment when the same test costs $5.
- **You need flexibility on targeting.** NetNut includes city/state selection in every plan; if you need ASN or ZIP-level filtering at volume, price that out on both sides before deciding.

## Questions people actually ask about NetNut pricing

**Does NetNut have a pay-as-you-go plan?**
Not on the public pricing page. The smallest published bucket is 28 GB at $99/month, and the platform starts from GB buckets rather than a top-up balance.

**Is there a NetNut free trial?**
There's a trial, but it's not self-serve. You sign up and then contact the sales team with your product type, target domains, use case, and required bandwidth. Trial accounts are set up case by case.

**Why is NetNut more expensive per GB than budget providers?**
Three reasons stack up: bucket-based monthly billing means you always buy more than you use at low volumes, ISP partnership routing costs more than SDK-collected pools, and every plan carries a dedicated account manager. You're paying for architecture and service, not just bandwidth.

**Do NetNut prices change?**
Their own pricing block says "prices subject to change based on use cases." Treat the published list as the starting point of a quote.

**What if my monthly usage is under 30 GB?**
Then a bucket model is working against you. At $1/GB with a $5 minimum, the same 28 GB costs $28 on a pay-as-you-go model, and the leftover traffic stays on your account instead of evaporating at the end of the billing cycle. 👉 See how DataImpulse's per-GB pricing compares for your volume

## The bottom line

NetNut's pricing is straightforward once you decode it: six GB buckets, $99 to $3,750 per month, roughly 11–15% off if you prepay a year, and a dedicated account manager wrapped into every tier. It's a subscription model with a service layer, aimed at teams with steady, predictable volume.

If that's you, the published rates are reasonable and the annual discount is real. If it isn't — if you're testing, spiking, or sitting under 100 GB a month — you're paying for 28 GB you didn't use and $3.53/GB for traffic that costs $1/GB elsewhere, with no expiry clock running. The $5 entry point makes that comparison cheap to run on your own targets instead of taking anyone's word for it. 👉 Try DataImpulse's 5 GB starter package and price it against your real usage
