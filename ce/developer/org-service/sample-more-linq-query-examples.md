---
title: "Sample: More LINQ query examples (Developer Guide for Dynamics 365 Customer Engagement)| MicrosoftDocs"
description: "This sample shows how to create .NET Language-Integrated Query (LINQ) queries"
ms.custom: ""
ms.date: 10/31/2017
ms.reviewer: ""
ms.service: "crm-online"
ms.suite: ""
ms.tgt_pltfrm: ""
ms.topic: "samples"
applies_to: 
  - "Dynamics 365 (online)"
ms.assetid: d5e5ec45-6465-4281-9e14-5f213a8c3bde
caps.latest.revision: 22
author: "KumarVivek"
ms.author: "kvivek"
manager: "jdaly"
---
# Sample: More LINQ query examples
This sample code is for [!INCLUDE[pn_dynamics_crm_online](../../includes/pn-dynamics-crm-online.md)] Customer Engagement. Download the complete sample from [Sample: Work with Queries](https://code.msdn.microsoft.com/Sample-Work-with-Queries-8265a78e). 

## Prerequisites
[!INCLUDE[sdk-prerequisite](../../includes/sdk-prerequisite.md)]
  
## Requirements  
[!INCLUDE[sdk_SeeConnectionHelper](../../includes/sdk-seeconnectionhelper.md)]
  
## Demonstrates  
 This sample shows how to create [!INCLUDE[pn_LINQ](../../includes/pn-linq.md)] queries. The following queries are demonstrated:  
  
-   Retrieve records with `Skip`/`Take` record paging.  
  
-   Use `orderBy` to order items retrieved.  
  
-   Filter multiple entities using LINQ.  
  
-   Build a complex query with LINQ.  
  
## Example  
 [!code-csharp[query#UseLinqQuery](../../snippets/csharp/CRMV8/query/cs/uselinqquery.cs#uselinqquery)]  
  
### See also  
 [Build Queries with LINQ (.NET Language-Integrated Query)](build-queries-with-linq-net-language-integrated-query.md)   
 [Sample: Use LINQ with Late Binding](sample-create-linq-query-late-binding.md)   
 <xref:Microsoft.Xrm.Sdk.Client.OrganizationServiceContext>