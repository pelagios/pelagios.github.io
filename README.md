## Welcome to the Pelagios Network site

This is a general guide to finding your way around this repository. 
For information about getting started with Markdown, such as how to format the text, have a look at the [README](README.md) file. 

### Why GitHub Pages?
The Pelagios Network site has been built using GitHub Pages because it is a lightweight, easy-to-use tool, which enables decentralised collaboration. And since the Pelagios Network is run by the community, we want to make it as simple as possible for everyone to contribute to the site. If you'd like to learn more about GitHub Pages, [this](https://pages.github.com/) is a great place to start.

### Contributing to the site
The Activity Coordinators of the Network are responsible for maintaining the pages of each activity.


### Basic Content Arrangement
Most of the visible content on the site is kept in the [Content](pelagios.github.io/content/) folder. In here you'll find subfolders labelled:
1. Activities
2. Case-studies
3. Partners

In these folders you will be able edit the content that will appear on the relevant pages. These pages are all written in Markdown, which is why they have .md extensions in the filenames. 

Images on the site are generally kept in the [Assets](pelagios.github.io/assets/) folder, with a filename that specifies where on the site it is used. 

### The Template
The site has been designed in a way that allows information from all of the sections to link easily across the different pages. This is done through the frontmatter in the site template. Most of the site is laid out using this simple template. Depending on the page topic the template will look slightly different every time: 

Activities:

![Activities](/documentation/Activity_Template.jpg)

Case Studies:

![Case Studies](/documentation/CaseStudy_Template.jpg)

Partners:

![Partners](/documentation/Partner_Template.jpg)

An important item in the templates is the Category field. Categories are listed in square brackets  [ ] and create the link 
between content in different parts of the site. 


### Different types of pages
Not all pages on the site are written in Markdown. 
Some pages contain data or static information that are used across the site, and that is not otherwise rendered as individual files like documents or pages. In these cases, the files might be configured as YML, JSON or CSV files. In our case, this can be seen in the people.yml file, where the names of individual people are added. This list can be found in the [Data](pelagios.github.io/_data/) folder. This file can be edited in the same way as any other, as long as you follow the template. 



