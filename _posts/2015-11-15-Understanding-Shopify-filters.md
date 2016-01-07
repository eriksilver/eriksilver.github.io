---
layout: post
title: How to work with Shopify Collection Filters' and their limitations
tags: Shopify, filters, How to
published: true
permalink: /blog/
---

#Shopify Collection Filters
A client that was designing a new store reached out for help to understand how Shopify collection and product filters work and their inherent limitations.

The overview below explains Shopify’s “native” product categorization. If you are looking for something different or a customized solution, let’s talk to understand what your project needs.

#Shopify Product Categorization:

* Products are organized first by Collections and then by product Tags. Product tags are used as Filters.

* Shopify filters are only for “refinement”, that is, they chain filter tags together with an “and” so that when multiple filters are selected the products remaining must meet the criteria for the first filter AND the second filter AND the third filter.

* Each Collection has it’s own URL. For example, a jewelry collection on this gifting website would be found at the url: www.supermarkethq.com/collections/jewelry.

* Shopify has a three filter limit. For example, if looking at jewelry, and then search for a necklace, that is gold, and is over 20 inches long. The three filters look be something like necklace+gold+over20. The url in this case would look like www.yourwebsite.com/collections/jewelry+necklace+gold+over20/.

* As you can see, Shopify uses the url for filtering, which also means each time a filter is selected there is a page refresh. Depending on the speed of your site, this can affect the user experience.

* Another limitation to keep in mind is if you have a large product catalog, Shopify has a limitation to display 50 products at one time. If you have a large collection you will likely want to implement pagination for your collections.

* Many Shopify themes default to drop down boxes for filtering. For a client we designed a modified version that uses radio buttons. Check out this post that gets into the code and gritty details.

Here is a Shopify [article](https://docs.shopify.com/support/your-store/collections/filtering-a-collection-with-multiple-tag-drop-down) with more details about their filtering system and a [demo shop](http://satterfield-pfeffer5655.myshopify.com/collections/all) to try out the filters for yourself.

What questions do you have about Shopify product filters?

Contact me [here](/contact) if you want to talk Shopify filters.   
