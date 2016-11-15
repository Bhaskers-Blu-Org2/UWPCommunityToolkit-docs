---
permalink: /en-US/api/Microsoft_Toolkit_Uwp_Services_Twitter_TwitterOAuthRequestBuilder.htm
title: Microsoft.Toolkit.Uwp.Services.Twitter.TwitterOAuthRequestBuilder API 
description: API page for Microsoft.Toolkit.Uwp.Services.Twitter.TwitterOAuthRequestBuilder
keywords: windows, app, toolkit, UWP, API
layout: api
search.product: eADQiWindows 10XVcnh
---


# TwitterOAuthRequestBuilder class

OAuth request builder.

## Members

The **TwitterOAuthRequestBuilder** class has the following types of members:

### Constructors

#### contructor

Initializes a new instance of the [TwitterOAuthRequestBuilder](Microsoft_Toolkit_Uwp_Services_Twitter_TwitterOAuthRequestBuilder.htm) class. Authorization request builder.

##### Parameters



| Name | Description | Type |


### Methods

#### GetAuthHeaderParameters()

Get list of auth header parameters.

##### Parameters



| Name | Description | Type |


#### GetEncodedUri(System.Uri requestUri,System.Collections.Generic.IEnumerable(Microsoft.Toolkit.Uwp.Services.OAuth.OAuthParameter) parameters)

Get encoded Uri.

##### Parameters



| Name | Description | Type |


#### GenerateNonce()

Generate nonce.

##### Parameters



| Name | Description | Type |


#### GenerateTimeStamp()

Generate timestamp string.

##### Parameters



| Name | Description | Type |


#### GenerateSignature()

Generate signature.

##### Parameters



| Name | Description | Type |


#### GenerateAuthorizationHeader()

Generate authorization header.

##### Parameters



| Name | Description | Type |


#### GetSignParameters()

Get list of sign parameters.

##### Parameters



| Name | Description | Type |


### Properties

#### SignatureMethod

Gets signature method.



#### ConsumerKey

Gets consumer key.



#### ConsumerSecret

Gets consumer secret.



#### Verb

Gets or sets HTTP verb for request.



#### TokenSecret

Gets access token secret.



#### Signature

Gets signature getter.



#### AuthorizationHeader

Gets authorization header getter.



#### Token

Gets access token.



#### EncodedRequestUri

Gets encoded Request Uri.



#### RequestUriWithoutQuery

Gets request Uri without query.



#### QueryParams

Gets list of query parameters.



#### Version

Gets version.



#### Nonce

Gets nonce.



#### Timestamp

Gets timestamp.



### Fields

#### Realm

Realm for request.

