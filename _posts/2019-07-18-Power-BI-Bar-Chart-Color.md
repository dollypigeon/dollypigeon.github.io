---
title: "Distinguish the color of the first business day of each month in the bar charts in Power BI"
date: 2019-07-18
tags: 
  - Power BI
  - Data Visulization
  - Bussiness Intelligence
categories: "Working_Notes" 
---
In Power BI, when we have a bar chart displaying quite a long period of time like the chart below, it might be quite hard for user to read which bar is the start date of a month. Therefore, we can consider highlight the bar of the first date of each month with a different color to make the chart clearer and easier to read.  This article is explaining how we can achieve that.

![BarChart](/assets/images/2019-07-18/BarChart.png)

Normally we have a date dimension table that contains all the date we need for the data visualization. So the easiest way to achieve that is creating a measure to match the date to the start date of each month. In that case, it is pretty simple, you only need to create one measure to define the color f
