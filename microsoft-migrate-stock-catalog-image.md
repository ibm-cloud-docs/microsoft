---

copyright:
  years: 2023
lastupdated: "2023-08-07"

keywords: microsoft, mssql 

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

# Migrating existing VSIs from stock image to catalog image
{: #microsoft-migrate-image}

You can manually migrate your existing VSIs that use stock image to VSIs that use the catalog image, if you need to use a more recent version of Microsoft SQL Server.

1. Create a VSI that uses the catalog image that you want.
2. Use Microsoft SQL data migration tools to move your data from the VSI that uses the stock image to the new VSI that uses the catalog imge.
3. Remove the VSI that is using the stock image. 
