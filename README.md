# Acronis 365 Backup: Why Microsoft Doesn't Back Up Your Data, and a $4/Month Fix That Covers Exchange, OneDrive, SharePoint and Teams

Microsoft 365 keeps your mail, files and Teams chatter available, but long-term protection of that data is largely your problem. Microsoft runs the infrastructure; recovery from a ransomware hit, a malicious insider, or a sync error that quietly overwrites a year of documents falls on the account owner. That gap is exactly why searches for "Acronis 365 backup" exist — and why Acronis's Cyber Protect platform, which does agentless cloud-to-cloud backup of Exchange, OneDrive, SharePoint and Teams, keeps showing up in those conversations.

One practical route to that platform is Sharktech, a hosting provider founded in 2003 that resells hosted Acronis backup as a capacity-based service. Instead of per-seat licensing, you pay for storage: plans start at **$4/month with 200 GB included**, and everything you protect — M365 data included — draws from that pool.

> **Quick take:** For a small business or a single critical server, the sensible entry is Sharktech's 200 GB plan. Monthly costs $4 (overage $0.02/GB); annual prepay works out to $2/month but carries a higher overage rate, so it only makes sense if your footprint stays near 200 GB. 👉 [Configure the $4/month 200 GB plan and see your live total at Sharktech](https://portal.sharktech.net/cart.php?a=add&pid=648&configoption%5B1862%5D=200&configoption%5B1863%5D=0&billingcycle=monthly&aff=1626)

## Does Microsoft 365 already include backup?

No — not in the way most people assume. Acronis's own breakdown of the shared-responsibility model puts it plainly: Microsoft is responsible for the datacenter, network, application and OS layers, plus short-term recovery of the service itself. You are responsible for the data: protection against ransomware, accidental deletion, sync errors and malware, along with backup, retention and compliance requirements like GDPR, HIPAA, FINRA and SOX.

The recycle bin and version history cover small accidents with tight time windows. They don't help when an attacker deletes a SharePoint site, when a departed employee's mailbox needs to be recovered eight months later, or when you need to prove retention for an audit. Microsoft reported 1,220 new CVEs in a recent period, and Acronis notes attacks against Teams keep climbing — the threat surface is real even if the platform itself is reliable.

This is the case for a third-party copy that lives outside Microsoft's control, on a schedule you set, with retention you decide.

## What Acronis actually backs up in Microsoft 365

Acronis's cloud-to-cloud backup covers the four things M365 admins care about: Exchange Online mailboxes (user, shared, group, including Kiosk-plan and litigation-hold mailboxes), OneDrive files and folders, SharePoint Online sites, and Microsoft 365 Teams — teams, channels, channel files, team mailboxes, meetings, team sites and OneNote notebooks. New users, groups, sites and teams are picked up automatically, so a new hire doesn't fall through the cracks because nobody updated a backup selection.

Recovery is granular: individual emails, files, sites, contacts and attachments can be restored without rolling back everything around them. Acronis positions recovery in seconds as the goal, and you can search mailboxes by subject, sender, recipient and date before restoring.

Acronis's documentation also spells out limits that most marketing pages skip, and they matter when you're planning:

- The standard cloud-agent backup ("Microsoft 365 Business – Backup") runs **up to 6 times per day** (default once daily).
- A company can protect up to **50,000 workloads**, with a conversion ratio of 10 mailboxes = 2 teams = 2 sites = 1 OneDrive account.
- A newer "Direct Backup to Microsoft 365 Backup Storage" mode runs every 10 minutes, but with fixed retention and no granular recovery.
- A locally installed agent covers Exchange Online mailboxes only, and none of the three methods can restore to an on-premises Exchange Server.

Because Sharktech sells Acronis by storage capacity rather than by seat, your M365 backups simply consume your storage pool — mailboxes and file versions included. Whether you're protecting 20 mailboxes or a mixed fleet of servers plus M365, the billing logic stays the same.

## Sharktech's Acronis backup plans: full pricing table

Sharktech runs one Acronis product (a Cyber Protect backup package) with four billing cycles. All include the same **200 GB** of cloud storage; what changes is the base price and the rate for storage beyond that. These figures come from Sharktech's own pricing announcement and current service page:

| Plan | Included storage | Price | Overage (per extra GB) | Order |
| --- | --- | --- | --- | --- |
| Monthly | 200 GB | $4.00/mo | $0.02/GB | [Order the monthly 200 GB plan](https://portal.sharktech.net/cart.php?a=add&pid=648&configoption%5B1862%5D=200&configoption%5B1863%5D=0&billingcycle=monthly&aff=1626) |
| Quarterly | 200 GB | $8.00/3 months | $0.04/GB | [Check current quarterly pricing](https://bit.ly/SharKtech) |
| Semi-annual | 200 GB | $12.00/6 months | $0.06/GB | [Check current semi-annual pricing](https://bit.ly/SharKtech) |
| Annual | 200 GB | $24.00/yr | $0.12/GB | [Check current annual pricing](https://bit.ly/SharKtech) |

A second, optional add-on exists: File Sync & Share, which turns the backup target into a shareable drive. Its overage runs $0.03/GB monthly, $0.06/GB quarterly, $0.12/GB semi-annually and $0.24/GB annually. It's only billed if you switch it on, and Sharktech's own page reminds you to check the itemized selection before confirming the order — the final recurring price depends on the capacity and options you pick in the portal checkout.

## Which billing cycle actually costs less

The advertised prices hide the real story, so here's the math most articles skip. What you pay per year depends on both the base rate and the overage rate applied to whatever sits beyond 200 GB.

Take a **300 GB dataset** (100 GB over the included base):

- Monthly: 12 × ($4 + 100 × $0.02) = **$72/year**
- Quarterly: 4 × ($8 + 100 × $0.04) = **$48/year**
- Semi-annual: 2 × ($12 + 100 × $0.06) = **$36/year**
- Annual: $24 + 100 × $0.12 = **$36/year**

Same data, same product — the monthly plan costs double the annual one over a year. The nominal overage rate climbs as the cycle lengthens ($0.02 → $0.12 per GB), but the base price drops faster, so the annual plan wins until your dataset gets seriously large. The practical decision rule:

- **Under ~250–300 GB and stable** → annual or semi-annual. Effective base cost is $2/month, and you'd have to blow well past the included storage for the higher overage rate to bite.
- **Growing unpredictably, or already past 1 TB** → run the numbers before prepaying. The overage gap narrows the annual advantage as the extra volume grows, and quarterly sits awkwardly in the middle — cheaper than monthly, worse than either extreme in most scenarios.

One more quirk worth knowing: the annual plan is only $24 up front, which makes it tempting to grab for a dataset you haven't actually measured. Measure first. Overage on the annual cycle is the steepest of the four, and third-party reviews consistently point out that Sharktech doesn't advertise a money-back guarantee on this service — a prepay is a commitment. 👉 [Open the Sharktech cart and confirm your configured total before you commit](https://portal.sharktech.net/cart.php?a=add&pid=648&configoption%5B1862%5D=200&configoption%5B1863%5D=0&billingcycle=monthly&aff=1626)

## Buying through Sharktech vs. buying Acronis directly

Acronis sells Cyber Protect subscriptions itself, licensed per protected workload — workstations, servers, virtual hosts — with a free allowance of Acronis-hosted cloud storage (50–250 GB depending on the workload type). Licenseware's licensing wiki, updated in October 2026, lists the store edition covering Microsoft 365 backup from €89.99 per year; real deployments with servers and multiple workloads climb quickly from there, and security, disaster recovery and other modules are separate SKUs.

Sharktech collapses all of that into a single storage-metered bill. There's no per-device accounting, no add-on SKU math — you pick a cycle, fill a pool, done. That structure favors three groups:

1. **Small and mid-sized businesses** protecting a handful of machines plus M365 data, where per-workload licensing gets expensive relative to actual storage used.
2. **Dedicated server or VPS customers already at Sharktech**, since backups to the same provider avoid egress fees between your box and the backup target, and there's one support number for both.
3. **MSPs and small IT shops** quoting clients, where a flat per-GB cost makes per-client pricing predictable.

It's still genuine Acronis Cyber Protect — the same platform PCMag scored 4.5/5 with an Editors' Choice award for Cyber Protect 17 — running on Sharktech's infrastructure: DDoS-protected datacenters in Chicago, Denver, Los Angeles and Amsterdam, redundant high-availability backup servers, and a 24/7 in-house engineering team. The trade-off is that it's a self-service add-on: you configure retention policies and schedules yourself in the Acronis console rather than getting a managed-service white-glove treatment.

One capability worth flagging: Acronis's Active Protection anti-ransomware layer, which monitors process behavior and scans backups for malware before you restore them (so you don't reinfect yourself from your own safety copy), is part of the Cyber Protect package rather than a separately billed module — a common extra charge elsewhere. Storage-side deduplication and compression also help keep the per-GB cost low when you're versioning mailboxes and file shares daily.

## Who this setup isn't for

Honesty about limits saves everyone time. The Sharktech route fits capacity-based needs; it's a weaker match if you want any of the following:

- **A managed backup service** where the provider designs retention, tests restores and hands you reports. Sharktech gives you the console and support, but the operational work is yours.
- **Massive datasets.** Beyond a few terabytes, per-GB storage costs at any provider deserve a hard comparison against self-hosted options, and the annual plan's $0.12/GB overage is unforgiving at scale.
- **Restores to on-premises Exchange.** Acronis's M365 backup methods don't support it — if that's your recovery target, you'll need a different tool regardless of vendor.

Reputationally, third-party reviews of Sharktech are thin — Trustpilot sits around 3.5 with a limited review count, with praise for low-latency connections and responsive support, and the missing refund guarantee as the recurring gripe. The company claims over 1,000 business customers across 73 countries, but treat the review base as what it is: small.

## FAQ

**Is Acronis 365 backup a separate product I have to buy?**
No. Microsoft 365 protection is a capability of the Acronis Cyber Protect platform. Through Sharktech you buy storage capacity and use the platform's M365 backup against it — there's no separate M365 add-on to configure at signup.

**How often are M365 backups taken?**
Acronis's standard cloud-agent backup supports up to 6 runs per day (once daily by default); the direct-to-Microsoft-storage mode runs every 10 minutes but trades away granular recovery and flexible retention. Manual runs are capped at 10 per hour.

**What can't be restored?**
None of Acronis's three M365 backup methods can restore data to an on-premises Exchange Server. Restores target Microsoft 365 objects — mailboxes, files, sites, Teams items — at whatever granularity the chosen method supports.

**Is there a free trial or refund?**
Neither Sharktech's service page nor its pricing announcement advertises a trial or money-back guarantee for the Acronis service. Treat prepayments, especially annual, as final and size your storage conservatively.

**How long does setup take?**
There's nothing to install on the M365 side — the agentless cloud-to-cloud approach runs from Acronis's cloud, and you manage everything through the web console. Servers and desktops need the Acronis agent, which covers Windows, Linux and macOS, plus VMware, Hyper-V, KVM, Proxmox and application-level backups for Microsoft SQL, Exchange and SharePoint.

## The bottom line before you order

Pick by dataset size, not by the sticker price: **stable under ~300 GB → the $24/year annual plan** (effective $2/month); **growing or uncertain → monthly at $4 with the gentlest overage rate**; anything in between, price your actual extra gigabytes against the table above before choosing quarterly or semi-annual. If your only need is a handful of M365 mailboxes and the Acronis per-workload store pricing looks heavier than the problem warrants, Sharktech's capacity model is the cheaper on-ramp to the same platform — and it's the same Cyber Protect product that earned PCMag's 4.5/5.

Check your current storage footprint, add headroom for a year of growth, then 👉 [start with the 200 GB plan and confirm your exact price in the Sharktech cart](https://portal.sharktech.net/cart.php?a=add&pid=648&configoption%5B1862%5D=200&configoption%5B1863%5D=0&billingcycle=monthly&aff=1626) before the checkout line items surprise you.
