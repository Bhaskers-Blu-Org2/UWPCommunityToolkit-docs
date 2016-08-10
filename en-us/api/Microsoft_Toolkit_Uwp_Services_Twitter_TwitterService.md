---
permalink: /en-US/api/Microsoft_Toolkit_Uwp_Services_Twitter_TwitterService.htm
title: Microsoft.Toolkit.Uwp.Services.Twitter.TwitterService API 
description: API page for Microsoft.Toolkit.Uwp.Services.Twitter.TwitterService
keywords: windows, app, toolkit, UWP, API
layout: default
search.product: eADQiWindows 10XVcnh
---


# TwitterService class

Class for connecting to Twitter.

## Members

The **TwitterService** class has this types of members

* [constructors](#constructors)

* [methods](#methods)

* [properties](#properties)

* [fields](#fields)

### constructors

#### contructor

Initializes a new instance of the [TwitterService](Microsoft_Toolkit_Uwp_Services_Twitter_TwitterService.htm) class. Default private constructor.



### methods

#### Initialize(Microsoft.Toolkit.Uwp.Services.Twitter.TwitterOAuthTokens oAuthTokens)

Initialize underlying provider with relevent token information.

##### parameters



| name | description | type |


#### Logout()

Log user out of Twitter.



#### TweetStatusAsync(System.String message,Windows.Storage.Streams.IRandomAccessStream[] pictures)

Post a Tweet with associated pictures.

##### parameters



| name | description | type |


#### LoginAsync()

Log user in to Twitter.

##### parameters



| name | description | type |


#### RequestAsync(Microsoft.Toolkit.Uwp.Services.Twitter.TwitterDataConfig config,System.Int32 maxRecords)

Request list data from service provider based upon a given config / query.

##### parameters



| name | description | type |


#### GetUserTimeLineAsync(System.String screenName,System.Int32 maxRecords)

Retrieve user timeline data.

##### parameters



| name | description | type |


#### Initialize(System.String consumerKey,System.String consumerSecret,System.String callbackUri)

Initialize underlying provider with relevent token information.

##### parameters



| name | description | type |


#### GetUserAsync(System.String screenName)

Retrieve user data.

##### parameters



| name | description | type |


#### SearchAsync(System.String hashTag,System.Int32 maxRecords)

Search for specific hash tag.

##### parameters



| name | description | type |


### properties

#### Provider

Gets a reference to an instance of the underlying data provider.



#### UserScreenName

Gets the current logged in user screen name.



#### Instance

Gets public singleton property.



### fields

#### tokens

Field for tracking oAuthTokens.



#### instance

Private singleton field.



#### isInitialized

Field for tracking initialization status.



#### twitterDataProvider

Private singleton field for TwitterDataProvider.

