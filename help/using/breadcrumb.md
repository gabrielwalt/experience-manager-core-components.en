---
title: Breadcrumb Component
seo-title: Breadcrumb Component
description: null
seo-description: The Core Component Breadcrumb Component is a navigation component that builds a breadcrumb of links based on the page's location in the content hierarchy.
uuid: 13e858d5-24ad-4144-adc4-0fa1ffd257c1
contentOwner: User
content-type: reference
topic-tags: authoring
products: SG_EXPERIENCEMANAGER/CORECOMPONENTS-new
discoiquuid: ecd237df-08b8-4deb-9881-66a1f0d65ef3
disttype: dist5
gnavtheme: light
groupsectionnavitems: no
hidemerchandisingbar: inherit
hidepromocomponent: inherit
modalsize: 426x240
index: y
internal: n
snippet: y
---

# Breadcrumb Component{#breadcrumb-component}

The Core Component Breadcrumb Component is a navigation component that builds a breadcrumb of links based on the page's location in the content hierarchy.

## Usage {#usage}

The Breadcrumb Component displays the position of the current page within the site hierarchy, allowing page visitors to navigate the page hierarchy from their current location. This is often integrated into page headers or footers.

Available options, such as the default navigation level and the ability to show the current page or hidden pages, can be defined by the template author in the [design dialog](../using/breadcrumb.md#main-pars_title_1995166862). The content editor can then choose if hidden pages should be shown or not and the actual navigation level for the component in the [edit dialog](../using/breadcrumb.md#main-pars_title).

## Version and Compatibility {#version-and-compatibility}

The current version of the Breadcrumb Component is v2, which was introduced with release 2.0.0 of the Core Components in January 2018, and is described in this document.

The following table details all supported versions of the component, the AEM versions with which the versions of the component is compatible, and links to documentation for previous versions.

<table border="1" cellpadding="1" cellspacing="0" width="100%"> 
 <tbody> 
  <tr> 
   <td>Component Version<br /> </td> 
   <td>AEM 6.3</td> 
   <td>AEM 6.4</td> 
  </tr> 
  <tr> 
   <td>v2<br /> </td> 
   <td>Compatible</td> 
   <td>Compatible</td> 
  </tr> 
  <tr> 
   <td><a href="../using/breadcrumb-v1.md">v1</a></td> 
   <td>Compatible<a href="../using/list-v1.md"></a></td> 
   <td>Compatible</td> 
  </tr> 
 </tbody> 
</table>

For more information about Core Component versions and releases, see the document [Core Components Versions](../using/versions.md).

## Sample Component Output {#sample-component-output}

The following is sample taken from [We.Retail](/content/help/en/experience-manager/6-3/sites/developing/using/we-retail).

### Screenshot {#screenshot}

![](assets/chlimage_1.png) 

### HTML {#html}

```
<nav class="cmp-breadcrumb">
    <ol class="cmp-breadcrumb__list">
        <li class="cmp-breadcrumb__item">
            <a href="/content/we-retail/us.html" class="cmp-breadcrumb__item-link">
                United States
            </a>
        </li>
    
        <li class="cmp-breadcrumb__item">
            <a href="/content/we-retail/us/en.html" class="cmp-breadcrumb__item-link">
                English
            </a>
        </li>
    
        <li class="cmp-breadcrumb__item cmp-breadcrumb__item--active">
            
                Experience
            
        </li>
    </ol>
</nav>
```

### JSON {#json}

```
"breadcrumb":{  
                     "columnClassNames":"aem-GridColumn aem-GridColumn--default--12",
                     "items":[  
                        {  
                           "page":{  
                              "path":"/content/we-retail/us",
                              "pageTitle":null,
                              "name":"us",
                              "description":null,
                              "title":"United States"
                           },
                           "active":false
                        },
                        {  
                           "page":{  
                              "path":"/content/we-retail/us/en",
                              "pageTitle":null,
                              "name":"en",
                              "description":null,
                              "title":"English"
                           },
                           "active":false
                        },
                        {  
                           "page":{  
                              "path":"/content/we-retail/us/en/experience",
                              "pageTitle":null,
                              "name":"experience",
                              "description":null,
                              "title":"Experience"
                           },
                           "active":true
                        }
                     ],
                     ":type":"weretail/components/content/breadcrumb"
                  }
```

>[!NOTE]
>
>As of Core Components release 2.1.0, the Breadcrumb Component supports [schema.org microdata](http://schema.org/BreadcrumbList).

## Edit Dialog {#edit-dialog}

The edit dialog allows the content author to suppress hidden and active pages in the breadcrumbs as well as the depth in the hierarchy it should display.

![](assets/screen_shot_2018-01-12at124250.png)

* **Navigation Start Level** - Where in the hierarchy the breadcrumb component should start to walk down to the current page. For example in We.Retail:

    * 0 starts at `/content`  
    
    * 1 starts at `/content/we-retail`
    * 2 starts at `/content/we-retail/*<country>*`

* **Show hidden navigation items** - Show pages marked as hidden in the breadcrumb (by default they will not be displayed)
* **Hide current page **- Suppress the current page in the breadcrumb (by default it will be displayed)

## Design Dialog {#design-dialog}

The design dialog allows the template author to define what the default values are for the options to suppress hidden and active pages in the breadcrumbs as well as the depth in the hierarchy it should display.

### Main Tab {#main-tab}

![](assets/screen_shot_2018-01-12at124437.png)

* **Navigation Start Level** - Defines the default value for where in the hierarchy the breadcrumb component should start to walk down to the current page when the breadcrumb component is added to a page.
* **Show hidden navigation items** - Defines the default value of the **Show hidden navigation items** option when the breadcrumb component is added to a page.

    * It does not enable or disable the option for the author. It only sets the default value.

* **Hide current page **- Defines the default value of the **Hide current page** option when the breadcrumb component is added to a page.

    * It does not enable or disable the option for the author. It only sets the default value.

### Styles Tab {#styles-tab}

The Breadcrumb Component supports the AEM [Style System](../using/authoring.md#main-pars_header).

## Technical Details {#technical-details}

The latest technical documentation about the Breadcrumb Component [can be found on GitHub](https://github.com/adobe/aem-core-wcm-components/blob/master/content/src/content/jcr_root/apps/core/wcm/components/breadcrumb/v2/breadcrumb).

The entire core components project can be downloaded from GitHub.

Further details about developing Core Components can be found in the [Core Components developer documentation](../using/developing.md). 