---

copyright:
  years: 2023
lastupdated: "2025-03-07"

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

# Microsoft SQL Server images on VPC
{: #microsoft-mssql-image}

When you create a VSI, you specify the operating system image that your VSIs use. You can use Microsoft SQL Server images for VSIs.

If you are using Microsoft SQL on VPC, you have two choices, either:

1.  Microsoft SQL 2022 Web edition, use a stock image.

2.  All other Microsoft SQL servers use a catalog image.

## Selecting an image
{: #microsoft-mssql-select}

To select an image:

1.  In the Images and profiles section, select **Change image**.
2.  On the pop-out window, select either the **Stock** or **Catalog** tab.

    *  Select the Stock Image tab to select the Microsoft SQL Server Web edition 2022 with Windows Server 2022.
    *  Select the Catalog image tab for all other versions and select the image that you want from the list.

## Microsoft SQL Server catalog images
{: #microsoft-mssql-catalog}

IBM provides several images that can be used for Microsoft SQL Server catalog images. The images are listed on the **Change image** pop-up window from the Image and profile section of the Virtual server for VPC form.
