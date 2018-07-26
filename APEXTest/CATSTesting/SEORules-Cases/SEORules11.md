---
# required metadata

title: Extra title metadata is provided - SEO Rules | Microsoft Docs
description: This topic provides test cases in CATS to validate content with SEO rules - Title duplicated values

# optional metadata

#ROBOTS:
#audience:
#ms.devlang:
ms.reviewer: reutam
ms.suite: ems
#ms.tgt_pltfrm:
#ms.custom:

---

# SEO Rules on Title metadata - Title duplicated values

Page has one and only one "title" metadata.  
+ The title is "Extra title metadata is provided - SEO Rules | Microsoft Docs"  
+ The length is 45.

> [!WARNING] 
> Failed - Pages have duplicated Title metadata and the value.

## Missing/Extra Title
Any article should contain one and only one Title metadata.
## Title length
Title metadata should contain 43-59 characters, including spaces but excluding “| Microsoft Docs” at the end.
## Missing Title suffix
Any Title metadata should end with “- * | Microsoft Docs” where * stands for a non-empty string, e.g., “Xamarin” or “Bot Service”.
## Duplicated Title in articles
All the articles tested in the same test run should have unique Title metadata (i.e., no duplicated values among pages).
