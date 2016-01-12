---
layout: post
title: Replacing Shopify Collection drop down filters with radio buttons
tags: Shopify, filters, How to
published: true
permalink: /blog/Replacing-Shopify-Collection-drop-down-filters-with-radio-buttons
---

#Shopify Collection Filters
A client's site had drop down filters for their product tags. The radio buttons offer a better user experience and a better aesthetic.

The page originally looked like this:
{:.center}
![]({{ site.baseurl }}/img/jewelry-dropdown.jpg)

And with radio buttons, the filtering looked like this:
{:.center}
![]({{ site.baseurl }}/img/jewelry-radio.jpg)

The original implementation using the drop down displays all product tags available and then when a user selects a tag, jQuery is used to add that tag to the url handle using 'window.location.href'. That will reload the page with the tag filter in place. The url will look like this if the "rings" tag is selected: www.supermarkethq.com/collections/jewelry/rings
To learn more about how Shopify filters and uses the url, see this [post](http://eriksilver.github.io/blog/How-to-work-with-Shopify-Collection-Filters-and-their-limitations).

##How to filter with radio buttons
The radio button implementation is more complex and includes additional elements:
* Custom collection filters - assigns the tags/radio filters for each collection - way to subcategorize a collection.
* Refactor the selector to an input and add additional CSS classes for the radio buttons
* Add logic to check if a radio button is selected - only one can be selected at a time

Here is a look at the final radio button code:
{% gist 57acc1a8330a8d8dff50%}

What questions do you have about Shopify collection and product filters?

Contact me [here](http://eriksilver.github.io/contact) if you want to chat about your project needs.   
