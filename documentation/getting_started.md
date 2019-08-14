## Welcome to the Pelagios Network site

This is a general guide to finding your way around this repository. 
For information about getting started with Markdown, have a look at the [README](README.md) file. 

### The Template
Most of the site is laid out using a simple template, which can have information added and removed as needs be. Depening on the page topic it will look slightly different every time: 

Activities:

![Activities](/documentation/Activity_Template.jpg)

Case Studies:

![Case Studies](/documentation/CaseStudy_Template.jpg)

Partners:

![Partners](/documentation/Partner_Template.jpg)



The most important item in the templates is the Category field. Categories are listed in square brackets  [ ] and create the link 
between content in different parts of the site. 

### Basic Content Arrangement
Most of the content on the site is kept in the _Content_ folder. In here you'll find subfolders labelled
1. Activities
2. Case-studies
3. Partners

In these folders you will be able edit the content that will appear on the relevant pages.


### When to use data
Use data (YAML, JSON, or CSV files in the _data folder_) for site-wide content or other primarily static information that is not otherwise rendered as individual files like documents or pages.

Examples of data might be the site’s authors, or a glossary of terms.

Generally, the distinction between collections and data is that data files do not have a large markdown body, and live in a single file, rather than multiple files. Unlike collections, data files cannot render as individual files.

The data folder is not a substitute for the site’s _config.yml_ file. Data files should contain information about the subject of the site, while the config file contains settings that deterimine how the site is built.
