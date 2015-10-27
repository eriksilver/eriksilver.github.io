---
layout: post
title: How to Create a Jekyll Blog with Poole (or Type Theme)
---

### Update October 2015
I wanted a portfolio site in addition to a blog, so I found a version of the Type Theme to replace my original Poole theme blog.
The Type Theme was made into a portfolio site by XXXXXX, and I have since extended it further and made my own customizations like the full blog page. Simply modifying and extending a theme is one of the beauties of using Jekyll.

### What is Jekyll, anyway?
Jekyll is a site generator for blogs that uses static (read: text) files. It will take a directory of text files and run them through 1) a converter (e.g. Markdown) and 2) a Liquid renderer and spit out a ready to publish website.

### What is Poole?
Poole calls itself a "diligent and noble steward" for building Jekyll sites, aka the "Jekyll Butler." It is designed to make a clear setup path for a Jekyll site by providing a full plain Jekyll install with some examples pages, posts, templates, etc to get you up and running fast.

It also has two design themes available Hyde and Lanyon (used on this site).

### Super Fast Setup
* Go to the local directory for your new blog.
* Copy the Poole repository from [Github](https://github.com/poole/poole)
* Clone the repository
<pre><code>$ git clone https://github.com/poole/poole</code></pre>

* This will create a 'poole' directory with all the files in it
* This command will run the site locally in the browser
    <pre><code>$ cd poole</code></pre>
    <pre><code>$ jekyll serve</code></pre>

More details on [setup and installation](https://github.com/poole/poole) are on Github.

### Customizations
Archive Page
I like some of the customizations done by by [Joshua Lande](http://joshualande.com/jekyll-github-pages-poole/), like the Archive page. So I wanted to set one up on my Poole blog.
To do this, I created an 'archive.md' file and saved it in the blog directory.

### Summary
* I found this faster and prettier than working through the setup instructions from [Jekyll](www.jekyllrb.com).
* I like starting with theme that already incorporates some design. Plus the theme is totally customizable.
