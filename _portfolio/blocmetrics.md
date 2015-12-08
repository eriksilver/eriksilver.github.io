---
layout: post
title: Song Player Analytics
thumbnail-path: "img/bloc-jams-analytics-MB.png"
short-description: An internal analytics service to track metrics within the Bloc Jams song player app
---

{:.center}
![]({{ site.baseurl }}/img/bloc-jams-analytics-MB.png)

## Overview

This analytics service is built within a song player called Bloc Jams. It tracks the internal metrics of total song plays by song name, total song plays by day, and total song plays by month. The metrics are displayed as charts in a dashboard view.

Components:
<ol>
  <li>A client side event handler that executes a callback when a metric is recorded</li>
  <li>An Angular model to capture displayable events</li>
  <li>A new state accessible in the navigation to view event results/charts</li>
</ol>

## Stack

<ul>
  <li>AngularJS</li>
  <li>Keen IO</li>
</ul>

## User Stories

<ol>
  <li>As an administrator, I want to capture events from any page in the song player app.</li>
  <li>As an administrator, I want to view a dashboard of the captured events.</li>
</ol>

## Results

The analytics app was interesting to further deepen my knowledge of Angular and learn about charting libraries and data services (ChartJS, NVD3) and ultimately settle on Keen IO for their superb analytics tools and built-in charting.  
