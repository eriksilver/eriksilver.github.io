---
layout: post
title: Analytics Dashboard
thumbnail-path: "img/Analytics-MB-img.png"
short-description: The app displays a user's Google Analytics data in easy to understand charts
---

{:.center}
![]({{ site.baseurl }}/img/Analytics-MB-img.png)

## Overview

The Analytics Dashboard easily retrieves and displays a user's Google Analytics data in an easy-to-digest charts.

Key Components:
<ol>  
  <li>Authenticate user and save profile data with Firebase</li>
  <li>Consume Google Analytics API to access user's data</li>
  <li>Manage states/views with Angular UI Router</li>
  <li>Utilize a custom alert service for form notifications</li>
  <li>Serve app with Node.js and Heroku</li>
</ol>

## Stack

<ul>
  <li>AngularJS</li>
  <li>Firebase</li>
  <li>Node.js</li>
  <li>Express</li>
  <li>Bootstrap</li>
</ul>

## User Stories

<ol>
  <li>As a user, I want to register and log in to an account.</li>
  <li>As a user, I want to view and edit my profile.</li>
  <li>As a user, I want a preset analytics dashboard with data in chart format.</li>
  <li>As a user, I want to select multiple views and timeframes to analyze my data.</li>
  <li>As an administrator, I want an attractive landing page with a call-to-action.</li>
</ol>

## Results

The Analytics Dashboard is an attractive and easy to use app to access Google Analytics data. I worked through many issues in this app including:
<ul>
<li>authenticating and managing users</li>
<li>dealing with callbacks and using promises</li>
<li>reading API documentation to properly access/utilize the Google Analytics APIs</li>
<li>handling the flow of data and events on a page</li>
<li>managing different states and passing data between states</li>
</ul>
