# December

## Coming soon 

* 🔖 Public **reading lists**
* ⁉ Conditions for **displaying metadata**
* 🔐 **Shibboleth** 

## General 

An updated version of Goobi-to-go was released at the end of the year. Among other things, the Goobi viewer was updated. This means that the crowdsourcing campaigns presented at the user meeting can now be tested. 

Goobi-to-go can also be downloaded from the newly designed [Goobi.io website](https://goobi.io/). There is also a more detailed article on the release in the Community Forum. 

* Download: [https://goobi.io/goobi-to-go/](https://goobi.io/goobi-to-go/) 
* Article: [https://community.goobi.io/t/goobi-to-go-grundlegend-ueberarbeitet/442](https://community.goobi.io/t/goobi-to-go-grundlegend-ueberarbeitet/442) 

The Goobi viewer was also included in the IIIF newsletter with a reference to support for the IIIF Content Search API:

{% embed url="https://iiif.io/news/2019/12/18/newsletter/\#goobi-viewer-implements-the-iiif-search-api" %}

## Developments 

### Italian language support 

The community is growing and so is the language support in the Goobi viewer. In December, a full translation into Italian was added. We would like to take this opportunity to thank the translators\* for their personal commitment. 

### Reading lists 

The reading lists will be revised shortly as already announced. First of all, this month the notice that was displayed when an unregistered user added the first record to the session reading list has been removed. The hint turned out to be superfluous and annoying. 

### Full screen display

In full screen display, the displayed image was sometimes covered by the navigation bar at the top or the sidebar on the right. This behavior has now been turned off. 

### CMS

With the revision of the media files in the CMS backend at the beginning of the year, the options for setting the order of display and the priority for a media file were removed. These settings have been added back to the interface 

### Other

* Improved display of 3D objects in GLTF format 
* The retrieval of authority data from GND is now also supported via HTTPS
* The sidebar of the download page, which is displayed when PDF and EPUB files are generated via the intranda TaskManager, has been revised. The breadcrumbs have been adjusted and widgets that can display content from a factory context have been removed. 

## Documentation 

The documentation for commissioning the development environment for the Goobi viewer has been completely rewritten. For the first time, a complete guide to installing and configuring a development environment with Eclipse is now available, which can be used by both back-end and front-end developers to contribute to the project.

{% embed url="https://docs.intranda.com/goobi-viewer-de/8/8.6" %}

## Version numbers 

The versions that must be entered in the `pom.xml` of the theme in order to get the functions described in this digest are:

```markup
<dependency>
    <groupId>io.goobi.viewer</groupId>
    <artifactId>viewer-core</artifactId>
    <version>4.2.2</version>
</dependency>
<dependency>
    <groupId>io.goobi.viewer</groupId>
    <artifactId>viewer-core-config</artifactId>
    <version>4.1.3</version>
</dependency>
```

The **Goobi viewer Indexer** has the version number **4.1.6**. 

The **Goobi viewer Connector** has the version number **3.4.9**.

The **Goobi viewer Crowdsourcing Module** has the version number **1.1.7**.

