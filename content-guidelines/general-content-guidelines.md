---
layout: page
title: General content guidelines
category: Content guidelines
published: true
---

- [Structure](#structure)
- [Formatting content](#formatting)
- [Language](#language)
- [Dynamic content](#dynamic-content)
{: class="toc"}

<div class="content-67 content-first">

These guidelines apply to structuring and writing all design manual pages, to ensure consistent information presentation and style. 
{: class="lead-in"}
</div>

<h2 id="structure">Structure</h2>

<div class="content-67 content-first">

Most design manual pages consist of a definition or overview of the topic of the page, plus some number of subsections giving detailed information about it. When structuring a page, follow these guidelines:

* All sub-headers within the pages should be coded as jump/anchor links, to allow for easy deep linking from other design manual pages.
* Only include sections/sub-sections that pertain to the specific item you are defining.
* The structure outlined for a page type may not align with every single item; use your discretion to add different sections as necessary to convey the needed design information.

</div>

<h2 id="formatting">Formatting content</h2>

<div class="content-67 content-first"> 
Present components of behavior, styling, use cases, etc as bullet points, to allow readers to skim content easily. Include an image or a live code example of those components as needed.

Example: 
* Background lightbox: Gray 80% #75787b, 70% opacity
* Font: Avenir Next Regular
* Padding: 30px

### Code examples

Design manual pages should demonstrate content visually along with explanation text. When possible, include a live code example of the design manual item. If live code is not practical, use images to show an example or illustrate a concept.

### Image links

Sometimes it may be appropriate to include a small version of an image on the page, with a link to a larger version that shows more detail. When including a link to a larger version of an image, include explicit link text, and make both the image itself and the text link to the larger version.

</div>


<h2 id="language">Language</h2>

<div class="content-67 content-first"> 

#### Capitalization
Headers and sub-headers will use sentence case

Example: “Use case” not “Use Case” 

#### Plural vs singular
Use plural case to describe components, unless referring to a specific instance of that component when singular reference should be used

Example: 
* “Modals can be effective for communicating a warning or alert outside the main web page.” 
* “When a modal opens, set the focus to the first element users need to interact with.” 

</div>

<h2 id="dynamic-content">Dynamic content</h2>

<div class="content-67 content-first"> 
The purpose of dynamic content is to make it easy to reuse content “snippets” from page to page. This eliminates the need to copy and paste the same content again and again or update many separate pages if standards change over time. 

Dynamic content is defined centrally within Jekyll includes or data files and can be pulled into other design manual pages. The include file or data file can be updated once, and all the places that use dynamic content will automatically update.

Currently, dynamic content is used to specify color data (color name and hex #) on component pages. Detailed instructions for using the color data is located on [the github wiki](https://github.com/cfpb/design-manual/wiki/Using-data-files).
</div> 