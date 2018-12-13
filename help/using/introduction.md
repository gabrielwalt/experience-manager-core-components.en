---
title: Core Components Introduction
seo-title: Core Components Introduction
description: null
seo-description: Components have always been a fundamental element of the AEM experience, making page creation simple but powerful for the author and the creation of new components flexible and extensible for the developer. Core Components were introduced to provide robust and extensible base components, built on the latest technology and best practices. 
uuid: b815c7d1-fbb0-4480-bd23-42606ff8b1eb
contentOwner: User
content-type: reference
topic-tags: introduction
products: SG_EXPERIENCEMANAGER/CORECOMPONENTS-new
discoiquuid: c44bb0d7-5d91-4659-878e-a0658fe29aa2
disttype: dist5
gnavtheme: light
isoverview: true
issectionnavparent: true
index: y
internal: n
snippet: y
---

# Core Components Introduction{#core-components-introduction}

In Adobe Experience Manager, components are the structural elements that constitute the content of the pages being authored. Components have always been a fundamental element of the AEM experience, making page creation simple but powerful for the author and the development of components flexible and extensible for the developer.

Core Components were introduced to provide robust and extensible base components, built on the latest technology and best practices, and adhering to accessibility guidelines and are compliant with the WCAG 2.0 AA standard. Core components make page authoring more flexible and customizable, and extending them to offer custom functionality is simple for the developer.

## Core Components - Core Features {#core-components-core-features}

The Core Components are:

<table border="1" cellpadding="1" cellspacing="0" width="100%"> 
 <tbody>
  <tr>
   <td><strong>Pre-Configurable</strong></td> 
   <td>Templates can define how the page authors can use them.<br /> </td> 
  </tr>
  <tr>
   <td><strong>Versatile</strong></td> 
   <td>Authors can create most kind of content with them.<br /> </td> 
  </tr>
  <tr>
   <td><strong>Easy-to-Use</strong></td> 
   <td>Authors can efficiently create and manage content with them.<br /> </td> 
  </tr>
  <tr>
   <td><strong>Production-Ready</strong><br /> </td> 
   <td>Usable out-of-the-box! They are robust, well-tested, and perform well.<br /> </td> 
  </tr>
  <tr>
   <td><strong>Accessible</strong></td> 
   <td>They comply WCAG 2.0 standard, provide ARIA labels, and support keyboard navigation.</td> 
  </tr>
  <tr>
   <td><strong>Easy to Style</strong><br /> </td> 
   <td>The components implement the Style System and the markup follows BEM CSS naming.</td> 
  </tr>
  <tr>
   <td><strong>SEO Friendly</strong></td> 
   <td>The HTML output is semantic and provides schema.org microdata annotations.</td> 
  </tr>
  <tr>
   <td><strong>PWA/SPA/App Ready </strong></td> 
   <td>Their streamlined JSON output can also be used for client-side rendering.<br /> </td> 
  </tr>
  <tr>
   <td><strong>Extensible</strong></td> 
   <td>To cover custom needs but without starting from scratch, everything can be extended.</td> 
  </tr>
  <tr>
   <td><strong>Open Source</strong></td> 
   <td>If something is not as it should be, contribute improvements on GitHub (Apache License).</td> 
  </tr>
  <tr>
   <td><strong>Versioned</strong></td> 
   <td>The core components won’t break your site when improving things that might impact you.</td> 
  </tr>
 </tbody>
</table>

## Available Components {#available-components}

The current version of the Core Components features the following components.

* [Breadcrumb](../using/breadcrumb.md)
* [Form Button](../using/form-button.md)
* [Carousel](../using/carousel.md)
* [Form Container](../using/form-container.md)
* [Content Fragment](../using/content-fragment-component.md)
* [Form Hidden  
  ](../using/form-hidden.md)
* [Form Options](../using/form-options.md)
* [Form Text  
  ](../using/form-text.md)
* [Image](../using/image.md)
* [Language Navigation](../using/language-navigation.md)
* [List](../using/list.md)
* [Navigation](../using/navigation.md)
* [Page](../using/page.md)
* [Quick Search](../using/quick-search.md)
* [Social Media Sharing](../using/sharing.md)
* [Tabs](../using/tabs.md)
* [Text](../using/text.md)
* [Title](../using/title.md)

The [We.Retail reference site](/content/help/en/experience-manager/6-3/sites/developing/using/we-retail) illustrates how the core components can be used.

>[!NOTE]
>
>Core Components are not immediately available to authors, the [development team must first integrate them to your environment](../using/using.md). Once integrated, they may be made available and pre-configured via the [template editor](/content/help/en/experience-manager/6-3/sites/authoring/using/templates) or in [design mode](/content/help/en/experience-manager/6-3/sites/authoring/using/default-components-designmode).

>[!CAUTION]
>
>Some versions of individual Core Components may only be compatible with certain versions of AEM.
>
>See the individual help page (linked to in the previous list) for the specific component for compatibility information or reference the [Core Components Versions](../using/versions.md) document for more information.

## When to Use Core Components {#when-to-use-core-components}

As the Core Components are all-new, and offer multiple benefits, it is recommended for new AEM projects to use them. For existing projects, a migration should be part of a larger project effort, for example a rebranding or overall refactoring.

For specific use recommendations, see [When to Use the Core Components?](../using/developing.md#main-pars_title_534144336) in the [Developing Core Components](../using/developing.md) document.

## Gems Session Overview {#gems-session-overview}

For an introduction to the Core Components, the features they offer, and how they are leveraged in AEM, check out the AEM Gems Session [AEM Core Components.](/content/help/en/experience-manager/kt/eseminars/gems/AEM-Core-Components)

[Gems on Adobe Experience Manager](/content/help/en/experience-manager/kt/eseminars/gems/aem-index) is a series of technical deep dives delivered by Adobe experts. This series complements the product documentation and of all the other technical channels, allowing developers to get in touch and go deep on a specific topic.

## WKDN Developer Tutorial {#wkdn-developer-tutorial}

[Get started developing AEM Sites with Core Components by following this step by step tutorial.](/content/help/en/experience-manager/6-4/sites/developing/using/getting-started)

## Core Components Support {#core-components-support}

Core Components are an integral part of AEM and supported as is, under the same terms and conditions as if they were delivered as part of the Quickstart.

Like other product features, the general rule of end-of-life is:

* Components are first announced to be deprecated before being removed
* At the earliest they are then removed from the AEM release following the announcement.

This gives customers at least one release cycle to move to the new version of the component, before support ends.

The version of each component clearly states the AEM versions that it supports. When support ceases for a version of AEM, then so does the support of the Core Components for that version of AEM.

For details about the support of component customizations, see the [Customizing Core Components](../using/customizing.md) page of the relevant Core Components Version.

## Foundation Component Support {#foundation-component-support}

Since the Foundation Components have served as a basis of so much project development over many versions, they will continue to be supported into the foreseeable future.

However, Adobe's development emphasis has shifted to the Core Components and new features will be added to them whereas only bug fixes will be made to the Foundation Components.

<!-- 

Comment Type: annotation
Last Modified By: pid90611
Last Modified Date: 2018-03-27T09:06:05.428-0400

Same comment as above, need to check with Gabriel if this needs some note about what will happen with the deprecated components after the next cycle.

 -->
