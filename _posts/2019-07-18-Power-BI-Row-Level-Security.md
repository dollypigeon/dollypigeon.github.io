---
title: "How to add a user that is not in your organisation with Row Level Security (RLS) in Power BI ?"
date: 2019-03-20
tags: 
  - Power BI
  - Data Visulization
  - Bussiness Intelligence
categories: "Working_Notes" 
---

Row Level Security is a very powerful function in Power BI, it can help you restrict data access for given users. In Power BI desktop, filters restrict data access at the row level, and you can define filters within roles. The document of Power BI tutorial from Microsoft has explained how to use Row Level Security step by step. (https://docs.microsoft.com/en-us/power-bi/service-admin-rls)<!-- more --> 

However, after we create the role in Power BI desktop, when we try to add a user outside our organisation or a user within our organisation but with different email suffix to the role we just created, we will get the following message. It means, we have to add the user to our organisation first to be able to add the user to the role.

![Error](/assets/images/2019-07-18/RLSerror.png)

The simplest way to solve this problem is to invite him/she as a guest user to the Azure Active Directory.

So log in to Azure using your organisation email, click Azure Active Directory –> Users –> Add New Guest User, then type in his/her email address and send out the invitation. After the user accept your invitation, he/she is now in your organisation, and you are able to add he/she to the role.
