# White Label Reseller Hosting: What Does RackNerd's $14.59 Plan Include, How Many cPanel Accounts Do You Need, and What Does Year Two Cost? (All 6 Plans Compared)

RackNerd sells white label reseller hosting on two separate lines, and the price gap between them is large enough that most buyers should look at both before ordering. The standard cPanel line starts at **$14.59/month** for 40 GB SSD, 2 TB of transfer and 20 cPanel accounts. A second, annual-only line starts at **$34.88/year** for 75 GB. Every plan ships with cPanel and WHM, white-label hostnames and nameservers, LiteSpeed with LSCache, CloudLinux, JetBackup daily backups, Softaculous and a free ClientExec license.

Below is which tier fits which client count, the full six-plan table, what year one and year two actually cost, and the parts of "white label" that RackNerd does not cover.

> **Quick pick:** most readers should start on the **cPanel Reseller 40 GB plan at $14.59/month**. It holds 20 client accounts, and RackNerd sells extra cPanel accounts at $0.50/month each, so you can grow past 20 without jumping to the $22.59 tier. If you need disk more than accounts and don't mind paying for a year up front, the **75 GB RESELLER plan at $34.88/year** is the cheapest entry point on the page.
> 👉 [Check current RackNerd reseller plan availability and pricing](https://bit.ly/RacKnerd)

## What "white label" actually covers

White label reseller hosting means you buy capacity in bulk from a provider, put your own brand on it, and sell it to your clients. The upstream company stays invisible. The mechanics are the same across the industry:

1. You buy a reseller plan that includes a set amount of disk, transfer and cPanel account slots.
2. You get WHM on top of cPanel. WHM is where you create each client's account, set package limits, suspend or terminate, and upgrade.
3. You brand it: your company name, your logo, and private nameservers such as ns1.yourbrand.com. Clients logging into cPanel see your brand, not the provider's.
4. You set retail prices. The gap between your wholesale cost and what you charge is your margin.
5. The provider runs the servers, hardware, security patching and network.

RackNerd's reseller page states that accounts come with "fully whitelabel hostname & nameservers," and WHM access is included on every plan, which is the layer that makes step 3 possible.

What white label does not cover is support. Your clients will open tickets with you, not with RackNerd. RackNerd advertises 24/7 support with an average response under 10 minutes, but that support is for you as the account holder. Some hosts sell "white label support," where the provider answers your clients' tickets under your brand. RackNerd does not advertise that on its reseller page, so plan on handling first-line support yourself, or hire for it.

The same applies to outages. If a node goes down, your clients blame your brand. Industry guidance is to pick a provider with a documented uptime record of 99.9% or better before you commit, because the reputational cost lands on you either way.

## All six RackNerd reseller plans

RackNerd currently lists two product lines on its reseller pages: three monthly-billed cPanel tiers with published account limits, and three annual-billed tiers that are priced far lower per year.

| Plan | Disk / transfer | cPanel accounts | Price (USD) | Order |
| --- | --- | --- | --- | --- |
| RESELLER 75 GB | 75 GB SSD / 2.5 TB | Not published on the plan listing | $34.88/year (~$2.91/mo) | [Order the 75 GB annual plan](https://bit.ly/RacKnerd) |
| RESELLER 110 GB | 110 GB SSD / 5 TB | Not published on the plan listing | $64.88/year (~$5.41/mo) | [Order the 110 GB annual plan](https://bit.ly/RacKnerd) |
| RESELLER 180 GB | 180 GB SSD / 9 TB | Not published on the plan listing | $94.88/year (~$7.91/mo) | [Order the 180 GB annual plan](https://bit.ly/RacKnerd) |
| cPanel Reseller 40 GB | 40 GB SSD / 2 TB | 20 | **$14.59/mo** or $175.08/yr | [Order the 40 GB cPanel plan](https://bit.ly/RacKnerd) |
| cPanel Reseller 100 GB | 100 GB SSD / unmetered | 40 | $22.59/mo or $271.08/yr | [Order the 100 GB cPanel plan](https://bit.ly/RacKnerd) |
| cPanel Reseller 200 GB | 200 GB SSD / unmetered | 60 | $36.59/mo or $439.08/yr | [Order the 200 GB cPanel plan](https://bit.ly/RacKnerd) |

Two things to notice in that table. First, the annual tiers look almost too cheap next to the cPanel line: 75 GB for $34.88/year versus 40 GB for $175.08/year. They are annual-only and promotional, availability moves, and the listing does not publish a cPanel account allowance for them. If account count is what you're buying, ask sales to confirm the allowance before you pay. Second, annual billing on the cPanel line costs exactly 12× the monthly rate. Paying yearly does not reduce the price there; it only prepays it.

### Included on every plan

| Feature | Detail |
| --- | --- |
| Control panel | cPanel plus WHM, full reseller access |
| Branding | White-label hostname and private nameservers |
| Web server | LiteSpeed with LSCache |
| Isolation | CloudLinux per-account limits |
| Backups | Daily, powered by JetBackup, stored off-site and replicated to separate disaster-recovery locations |
| Installer | Softaculous one-click installer |
| SSL | Free SSL certificates on accounts |
| Kernel | KernelCare, patched without reboots |
| Billing software | Free ClientExec license |
| Migration | Free migrations, arranged by ticket |
| Billing cycles | Monthly or annual |
| Activation | Immediate after order |
| Upgrades | Self-service from the client area |
| Locations | Los Angeles, New York City, Germany, France, Singapore |

Two caveats on that list. The billing panel is **ClientExec, not WHMCS**. If your workflow is built on WHMCS, you license it separately. And on locations, RackNerd's ordering guide lists Miami where the product page lists New York City. Confirm your preferred datacenter in the cart before checkout rather than assuming.

## What year one and year two actually cost

RackNerd does not publish a separate renewal rate for reseller plans, so budget on the current public price continuing: the 40 GB tier runs **$175.08 in year one and $175.08 in year two** if you pay annually, or 12 × $14.59 if you stay monthly. The 100 GB tier is $271.08/year and the 200 GB tier is $439.08/year on the same basis.

The annual tiers are the ones to treat carefully. Promotional annual pricing often renews at a different figure, and RackNerd's reseller page doesn't state what that figure is. Ask in a pre-sales ticket, in writing, before you build a client base on a $34.88/year plan.

Extra accounts are the other cost lever. RackNerd sells additional cPanel accounts at **$0.50/month or $6.00/year each**, billed to match your cycle, arranged through sales. That changes the math on tier selection:

- 40 GB plan + 10 extra accounts = $19.59/month for 30 accounts and 40 GB of disk.
- 100 GB plan = $22.59/month for 40 accounts and 100 GB of disk.

If your clients are small brochure sites that eat 1-2 GB each, the first option is cheaper and you keep $3/month. If each client needs 5 GB or more, the 100 GB tier wins because disk, not accounts, becomes the binding limit.

Run the per-client cost before you set retail prices. Twenty accounts on the $14.59 plan works out to about **$0.73 per account per month** at full occupancy. Sell at $6/month and twenty clients produce $120 in revenue against $14.59 in cost. That's the whole business model, minus your support hours.

## Limits and things the sales page doesn't spell out

**Account ceilings are real, and the workaround is manual.** There's no unlimited-accounts claim here. You get 20, 40 or 60 depending on tier, and anything beyond that goes through a sales ticket at $0.50/month per account. Factor a day of back-and-forth into any launch that assumes instant scaling.

**Disk is allocated per plan, not per client.** WHM lets you create packages whose quotas sum to more than your plan's disk. That's normal overselling practice, but the physical limit is the plan's disk. Watch inode-heavy WordPress installs; a 2 GB site with thousands of cache files behaves differently from a 2 GB site with a hundred.

**No published refund window.** The reseller page doesn't state a money-back period the way some competitors do. Ask before ordering, especially on annual plans where the upfront amount is larger.

**Support is yours to staff.** Covered above, but it belongs in the budget. Industry guidance puts the point where reseller hosting becomes meaningful income at roughly **25 to 30 active clients**. Below that, you're running a small side service, not replacing project income.

**Who shouldn't buy this:** anyone whose client relationships are one-off projects. If you build a site, hand it over and never speak to the client again, adding hosting adds a support obligation with no recurring relationship behind it. White label reselling works when you already have clients who trust you with monthly services.

## How RackNerd's pricing sits next to other white label options

Three reference points, all from provider pages, none of them RackNerd's numbers:

| Provider | Product | What you get | Price |
| --- | --- | --- | --- |
| TOSHOST | Hero-Starter | 30 GB storage, 1000 GB transfer, 15 cPanel accounts | $20/mo |
| TOSHOST | Hero Alter | 90 GB storage, 2000 GB transfer, 50 cPanel accounts | $35/mo |
| TOSHOST | Devs Spacial | 150 GB storage, 5000 GB transfer, 80 cPanel accounts, dedicated IP | $70/mo |
| HOSTKEY | White label server reselling | 16 cores, 32 GB RAM, 500 GB NVMe, 1 Gbps | $149/mo or $0.20/hr |

Against the cPanel-heavy plans, RackNerd's 200 GB tier at $36.59 gives 60 accounts and 200 GB, which is more of both than TOSHOST's $35 tier at 50 accounts and 90 GB. On entry pricing, RackNerd's $14.59 for 20 accounts undercuts TOSHOST's $20 for 15.

HOSTKEY is a different product category: you resell dedicated, GPU and virtual servers, not cPanel accounts, and the program carries real requirements. HOSTKEY asks for **at least EUR 1000 in monthly turnover and 10 servers within the first six months**, forbids reselling below HOSTKEY's own price for the same configuration, and reviews discount rates quarterly. Those are HOSTKEY's rules for its server program, not RackNerd's.

RackNerd runs its own dedicated server reseller program separately from reseller hosting, and the terms are lighter: free to join, no monthly fee, no revenue floor, and discounts of 5% at 3-5 active servers up to 20% at 51 or more. It requires an established website or company and you handle client support. If you outgrow shared reselling, that's the next step in the same account.

## FAQ

**Can you actually make money with white label reseller hosting?**
Yes, as recurring side income. The commonly cited threshold is 25-30 active clients before the monthly margin is worth the support load. At $14.59 cost for 20 accounts, the margin per client is large; the constraint is your time, not the wholesale price.

**Do you need technical skills?**
Not for the server side. RackNerd's plans are fully managed, with system administrators handling the backend, and WHM's interface covers account creation, package limits and suspension. You do need to be comfortable being the first person a client emails when their site breaks.

**Can clients see RackNerd anywhere?**
Not through the hosting layer. White-label hostnames and private nameservers mean the brand on the account is yours. Watch the edges: default cPanel pages, error emails and anything you paste from provider documentation can leak the upstream name if you don't customize them.

**What happens to your reputation when the server goes down?**
It takes the hit, not the provider. That's the trade for the margin. It's also why the uptime record matters more than the price difference between two resellers.

**Is WHMCS included?**
No. The free billing license is ClientExec. WHMCS is a separate purchase if you need it.

## Which plan to buy

Three rules, based on the numbers above:

- **1-19 client sites, mostly small WordPress builds:** cPanel Reseller 40 GB at $14.59/month. Add accounts at $0.50 each as you fill up rather than stepping up a tier early. 👉 [Start with the 40 GB plan](https://bit.ly/RacKnerd)
- **20-40 clients, or clients with heavier sites:** cPanel Reseller 100 GB at $22.59/month. Forty account slots and unmetered transfer remove the two ceilings you'd hit first.
- **Agency with dozens of sites:** cPanel Reseller 200 GB at $36.59/month, or the 180 GB annual tier at $94.88/year if account count turns out to be sufficient once sales confirms it.

Before you pay, get three things confirmed in a ticket: the renewal price on your chosen tier, whether a refund window applies, and the cPanel account allowance on the annual plans if you're going that route. Then check the datacenter in the cart matches the city you actually want.

👉 [Compare RackNerd's reseller plans and place your order](https://bit.ly/RacKnerd)
