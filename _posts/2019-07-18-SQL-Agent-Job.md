---
title: "Schedule an monthly AUTO update for fact tables in data warehouse - SQL Agent Job"
date: 2019-03-20
tags: 
  - SQL
  - Stored Procedure
  - Bussiness Intelligence
categories: "Working_Notes" 
---

After we use stored procedure to create some fact tables in our data warehouse for visualization or analyzing purposes, we may need to update it periodly because our transactional database is kept updating. In that case, we might need to schedule an auto execution for the stored procedure to insert the latest records into the tables. SQL Agent Job is a service which enable us to achieve that.

The following link is a basic tutorial that escribes how to create a SQL Server Agent job in SQL Server 2017 by using SQL Server Management Studio, Transact-SQL, or SQL Server Management Objects (SMO).

https://docs.microsoft.com/en-us/sql/ssms/agent/create-a-job?view=sql-server-2017

To create a agent job for monthly data update, it preferrable to set the job execution date on the first day of each month. Then we need to pass the first day and the last day of each month to the parameters in our stored procedure.
