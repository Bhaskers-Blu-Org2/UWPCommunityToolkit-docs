---
permalink: /en-US/api/Microsoft_Toolkit_Uwp_UI_Animations_AnimationExtensions.htm
title: Microsoft.Toolkit.Uwp.UI.Animations.AnimationExtensions API 
description: API page for Microsoft.Toolkit.Uwp.UI.Animations.AnimationExtensions
keywords: windows, app, toolkit, UWP, API
layout: api
search.product: eADQiWindows 10XVcnh
---


# AnimationExtensions class

These extension methods perform animation on UIElements

## Members

The **AnimationExtensions** class has the following types of members:

* [Methods](#Methods)

* [Properties](#Properties)

### Methods

#### Offset(Windows.UI.Xaml.UIElement associatedObject,System.Single offsetX,System.Single offsetY,System.Double duration,System.Double delay)

Animates the offset of the the UIElement.

##### Parameters



| Name | Description | Type |




#### Scale(Microsoft.Toolkit.Uwp.UI.Animations.AnimationSet animationSet,System.Single scaleX,System.Single scaleY,System.Single centerX,System.Single centerY,System.Double duration,System.Double delay)

Animates the scale of the the specified UIElement.

##### Parameters



| Name | Description | Type |




#### Blur(Microsoft.Toolkit.Uwp.UI.Animations.AnimationSet animationSet,System.Double value,System.Double duration,System.Double delay)

Animates the gaussian blur of the the UIElement.

##### Parameters



| Name | Description | Type |




#### BeginAsync(Windows.UI.Xaml.Media.Animation.Storyboard storyboard)

Begins a Storyboard animation and returns a task that completes when the animaton is complete

##### Parameters



| Name | Description | Type |




#### Fade(Windows.UI.Xaml.UIElement associatedObject,System.Single value,System.Double duration,System.Double delay)

Animates the opacity of the the UIElement.

##### Parameters



| Name | Description | Type |




#### Fade(Microsoft.Toolkit.Uwp.UI.Animations.AnimationSet animationSet,System.Single value,System.Double duration,System.Double delay)

Animates the opacity of the the UIElement.

##### Parameters



| Name | Description | Type |




#### Blur(Windows.UI.Xaml.FrameworkElement associatedObject,System.Double value,System.Double duration,System.Double delay)

Animates the gaussian blur of the the UIElement.

##### Parameters



| Name | Description | Type |




#### Offset(Microsoft.Toolkit.Uwp.UI.Animations.AnimationSet animationSet,System.Single offsetX,System.Single offsetY,System.Double duration,System.Double delay)

Animates the offset of the the UIElement.

##### Parameters



| Name | Description | Type |




#### Rotate(Windows.UI.Xaml.UIElement associatedObject,System.Single value,System.Single centerX,System.Single centerY,System.Double duration,System.Double delay)

Animates the rotation in degrees of the the UIElement.

##### Parameters



| Name | Description | Type |




#### Rotate(Microsoft.Toolkit.Uwp.UI.Animations.AnimationSet animationSet,System.Single value,System.Single centerX,System.Single centerY,System.Double duration,System.Double delay)

Animates the rotation in degrees of the the UIElement.

##### Parameters



| Name | Description | Type |




#### Scale(Windows.UI.Xaml.UIElement associatedObject,System.Single scaleX,System.Single scaleY,System.Single centerX,System.Single centerY,System.Double duration,System.Double delay)

Animates the scale of the the specified UIElement.

##### Parameters



| Name | Description | Type |




### Properties

#### IsBlurSupported

Gets a value indicating whether the platform supports blur.



