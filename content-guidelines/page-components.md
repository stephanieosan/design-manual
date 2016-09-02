---
layout: page
title: For page components section
category: Content guidelines
published: true
---

- [Structure](#structure)
- [Imagery](#imagery)
- [Language](#language)
- [Dynamic content](#dynamic-content)
{: class="toc"}

<div class="content-67 content-first">

Use the following as a guideline for creating the sub-sections on a design manual page. 
{: class="lead-in"}


* All sub-headers within the pages should be coded as jump/anchor links, to allow for easy deep linking from other design manual pages. 
* Only include sections/sub-sections that pertain to the specific item you are defining. 
* This structure may not align with every single item; use your discretion to add different sections as necessary to convey the needed design information.


</div>

<h2 id="structure">Structure</h2>

<div class="content-67 content-first">

#### Title (h1)

#### Definition
A brief (2-3 sentence) description of what the item is and generally what it is used for.

#### Use case(s) (h2)

Explain why and when that element should and should not be used.

* Include default/most common use cases
* Include variations on use cases, if applicable 
* If the element should only be used in a few specific circumstances, simply explain the acceptable use cases rather than detail the instances where it should not be used (the majority)
* Include examples, where possible
* Include an image of the default version

#### Behavior (h2)

Explain the details of any interactions involved with that item.

* **Creating accessible behaviors**—sub-section dedicated to development and design considerations in order to make those behaviors 508 compliant and accessible
* **Small-screen behavior**—include a sub-section (if necessary) that details any behaviors that are different on a smaller screen

* **Responsive**—describe component behavior as it scales to smaller screens (i.e., how content stacks, in what order it should appear, etc.)

#### Content guidelines (h2) 
Guidance for creating content associated with that component, including instructions around content goals, best practices around writing headlines/links (if applicable) and approximate length/word count maximums

#### Style (h2)
Create different sub-sections for defaults and variations on style, include different states for each as needed (onstate, hover state, etc.). If the component is comprised of several different areas, break out the styles for each area separately to make it easier to digest. 

* Small-screen style—include a sub-section (if necessary) that details any styles that are different on a smaller screen

Styles should be as detailed as necessary to create the component, including things like font, color, padding, etc. Per FEWD preference, put them in alpha order.

For example: 

* Alignment: centered horizontally and vertically on top of lightbox
* Background: White #ffffff
* Background lightbox: Gray-80 #75787b, 70% opacity
* Color: Black #101820
* Font: Avenir Next Regular
* Padding: 30px
* Text size body: 16px
* Text size header: 22px
* Top border: 3px CFPB Green #20aa3f
 
Include an example of the style (preferably a coded example, or if not, an image) 

#### Code (h2) 
Include live coded examples from Capital Framework as available, and links to resources to learn more about the live components

#### Print (h2) 
Include any print-specific styles or guidelines when necessary

</div>

<h2 id="imagery">Imagery</h2>

<div class="content-67 content-first"> 
* Include an image with use case to show a default example of the component 
* When possible, use a live coded example in place of an image
* Image width should be no more than 50% of content area
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