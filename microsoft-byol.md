---

copyright:
  years: 2022
lastupdated: "2022-10-17"

keywords: microsoft, byol, BYOL, license

subcollection: microsoft

---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}
{:codeblock: .codeblock}
{:pre: .pre}
{:screen: .screen}
{:term: .term}
{:tip: .tip}
{:note: .note}
{:important: .important}
{:deprecated: .deprecated}
{:table: .aria-labeledby="caption"}
{:external: target="_blank" .external}
{:table: .aria-labeledby="caption"}
{:generic: data-hd-programlang="generic"}
{:download: .download}
{:DomainName: data-hd-keyref="DomainName"}

# Bring Your Own License (BYOL)
{: #microsoft-byol}

{{site.data.keyword.cloud}} supports Bring Your Own Licenses (BYOL). Since 2019, Microsoft has had a specific set of rules that customers should follow when using their licenses on cloud providers. On August 29th, 2022 Microsoft changed their policy with two announcements. The first customer [announcement](https://www.microsoft.com/en-us/licensing/news/options-for-hosted-cloud) states that Microsoft BYOL can be deployed on shared (multi-tenant hosts). Previously this was limited to dedicated (single-tenant) hosts. Customers should read and understand the new terms and conditions in the [Microsoft FAQ](https://www.microsoft.com/en-us/licensing/news/new-software-assurance-benefit-to-support-hosting-from-third-party-providers). The [blog](https://blogs.partner.microsoft.com/mpn/new-licensing-benefits-make-bringing-workloads-and-licenses-to-partners-clouds-easier/) posting on BYOL provides more detailed information and Microsoft also has a [training video](https://licensingschool.eventbuilder.com/hostingcustomer). Basically, when a customer uses BYOL, they will be able to license Windows Server by virtual core instead of physical cores and on public multi-tenant instances. 

Customers should review these revised rules and their current spending and usage patterns to determine which deployment model makes the most financial and technical performance sense. Some workloads are steady state and require consistent infrastructure and some workloads are bursty and can be cycled on and off to take advantage of hourly pricing.

Depending on the {{site.data.keyword.cloud_notm}} solution, Microsoft software is purchased pay-as-you-go (hourly, monthly, yearly) on shared or dedicated resources. For BYOL, as of October 19th 2022, you can provision BYOL Microsoft licenses on dedicated and shared hosts.
