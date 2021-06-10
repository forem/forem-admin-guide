---
description: Creating new pages on your Forem
---

# Pages

### Overview

The `/admin/customization/pages` page allows you to:

* Create a new page
* View existing pages

### Creating a Page

Visiting `/admin/customization/pages/new` allows you to create a new page.

* Title = title of the page
* Slug = slug of the page
* Description = description, used mostly by search engines
* Template
  * [Here's a Contained example](https://dev.to/about)
  * [Here's a full\_within\_layout example](https://dev.to/downloads)
  * json //todo
* Body Markdown / Body HTML
  * You'll usually use _one or the other_
  * You should have a very specific reason for using HTML and not Markdown
* Social Image
  * This is the social image for the page, [related info here](config/images.md#main-social-image)
* Is Top Level Path?
  * If checked, your page lives at `/slug`
  * If not checked, your page lives at `/page/slug`
* Use as 'Locked Screen'
  * This determines if the page will be used as a landing page for anonymous viewers \(landing pages replace the traditional registration screen\). This feature _only_ works for private Forems. If your Forem is public, the landing page will not display.
  * Only one page can be used as a locked screen at a time. 
  * Locked screens can be overwritten. To use another locked screen when there is already a locked screen in use, click the "Overwrite current locked screen" button in the modal that appears when "Use as 'Locked Screen'" is clicked.
* Feature Flag
  * //todo

### What can you do with pages?

* [Here is an example of a simple contained Markdown page](https://dev.to/about)
* [Here is an example of a full\_within\_layout page that uses HTML](https://dev.to/downloads)
* You can create more sophisticated pages, such as:
  * [A blend of static content with custom CSS + dynamic posts](https://dev.to/shecoded)
  * [A full-on conference experience](https://dev.to/codeland)

