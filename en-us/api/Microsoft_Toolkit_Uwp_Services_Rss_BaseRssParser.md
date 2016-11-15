---
permalink: /en-US/api/Microsoft_Toolkit_Uwp_Services_Rss_BaseRssParser.htm
title: Microsoft.Toolkit.Uwp.Services.Rss.BaseRssParser API 
description: API page for Microsoft.Toolkit.Uwp.Services.Rss.BaseRssParser
keywords: windows, app, toolkit, UWP, API
layout: api
search.product: eADQiWindows 10XVcnh
---


# BaseRssParser class

Base class for Rss Parser(s).

## Members

The **BaseRssParser** class has the following types of members:

### Methods

#### GetFeedType(System.Xml.Linq.XDocument doc)

Retrieve feed type from XDocument.

##### Parameters



| Name | Description | Type |


#### LoadFeed(System.Xml.Linq.XDocument doc)

Abstract method to be override by specific implementations of the reader.

##### Parameters



| Name | Description | Type |


#### ProcessHtmlContent(System.String htmlContent)

Fix up the HTML content.

##### Parameters



| Name | Description | Type |


#### ProcessHtmlSummary(System.String htmlContent)

Create a summary of the HTML content.

##### Parameters



| Name | Description | Type |
