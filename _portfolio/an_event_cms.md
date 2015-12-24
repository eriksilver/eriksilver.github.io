---
layout: post
title: Event Management System
thumbnail-path: "img/events-screen.png"
short-description: An event management app to display, add, and edit event information. 
---

{:.center}
![]({{ site.baseurl }}/img/events-screen.png)

{:.center}
<a href="https://events-to-manage.herokuapp.com/" title="Event Management App">
<i class="fa fa-laptop fa-3x icon-space"></i>
</a>
<a href="https://github.com/eriksilver/Events-CMS" title="Event CMS GitHub">
<i class="fa fa-github-square fa-3x icon-space"></i>
</a>




## Overview

This app is an example of a content management system (CMS) that was built for events. It allows the user to view a list of events, add a new event, and edit existing events

Key Components:
<ol>  
  <li>Four views including Event List, Add Event, Edit Event, and About</li>
  <li>Firebase database (2 way sync) with operations to create, edit, and delete events</li>
  <li>Custom directive in list view to display event details</li>
  <li>Utilizes a custom alert service for form notifications</li>
  <li>Manage states/views with UI Router</li>
  <li>HTML5 and Angular form validation</li>
  <li>Event data schema with eight fields</li>
  <li>Serve app with Node.js + Express | Deploy with Heroku</li>
</ol>

## Stack

<ul>
  <li>AngularJS</li>
  <li>Firebase</li>
  <li>Node.js</li>
  <li>Express</li>
  <li>Foundation</li>
</ul>

## User Stories

<ol>
<li>As a user, I want to see a list of events and click to see event details</li>
<li>As a user, I want a page to edit an event</li>
<li>As a user, I want to delete an event from the view and the database</li>
<li>As a user, I want a page to add an event</li>
<li>As an administrator, I want event data validated before submission</li>
<li>As an administrator, I want an alert notification when a submission is successful</li>
</ol>

## Results

The Event Management app was my first introduction to Foundation, which overall, is similar to Bootstrap.   I worked through several issues in this app including:
<ul>
<li>HTML5 and Angular form validation</li>
<li>Converting date formats from the date picker</li>
<li>Creating a custom directive with an isolated scope</li>
<li>Setting up an alert service for form validation with a timeout</li>
</ul>
