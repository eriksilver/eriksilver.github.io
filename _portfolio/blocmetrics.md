---
layout: post
title: Analytics Service for a song player app
thumbnail-path: "img/blocipedia.png"
short-description: Build an internal analytics service to track metrics within the Blocjams songplayer web app.
---

{:.center}
![]({{ site.baseurl }}/img/blocipedia.png)

## Overview

This analytics service is built within a songplayer called Blocjams and tracks internal metrics of song play count, list of songs, and page visits and displays in a dashboard.

Components:
<ol>
  <li>A client side event handler that executes a callback when a metric is recorded</li>
  <li>An Angular model to capture displayable events</li>
  <li>A new state accessible in the navigation to view event results</li>
</ol>

## Stack

<ol>
  <li>AngularJS</li>
  <li>Firebase</li>
  <li>KeenIO</li>
  <li>Grunt</li>
  <li>Heroku</li>
</ol>

## User Stories

<ol>
  <li>As an administrator, I want to capture events from any page in the song player app.</li>
  <li>As an administrator, I want to view a dashboard of events capture from the app where I included the event handler</li>
</ol>

## Results

The analytics app was in interesting to further deepen my knowledge of Angular and learn about charting libraries (ChartJS, xxx) and ultimately settle on KeenIO for their superb analytics capability and built in charting.  
