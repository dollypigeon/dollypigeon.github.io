---
title: "Using Power BI Bookmark for data with multiple structures"
date: 2019-06-16
tags: 
  - Power BI
  - Data Visulization
  - Bussiness Intelligence
categories: "Working_Notes" 
---

Sometimes our data can have various data structures. For example, a company that has lots of sites may have more than one structure to group their sites. They may be group by regions and head offices while site is at the lowest level, regions and head offices are the highest level in their own structures. When we are creating the Power BI dashboards for that kind of data, we might need to have same charts with different legends to show the data patterns from different structures. 

The easiest way is probably creating mutiple pages and put charts for each data structure on each page. But if you already have multiple pages for different visualizations, it will be likely to make users feel confusing. In that case, we can use Bookmark to enable showing the same charts with different data structures in one page. 

Here is an example of how it looks like: 
![Bookmark](/assets/images/2019-07-18/Bookmark.gif)

From the above gif, we can see three buttons on the dashboard controlling different views. The default dashboard is showing the view by region, 
