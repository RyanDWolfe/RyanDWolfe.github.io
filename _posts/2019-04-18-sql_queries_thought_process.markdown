---
layout: post
title:      "SQL Queries Thought Process"
date:       2019-04-18 17:46:56 +0000
permalink:  sql_queries_thought_process
---


I always start with what I want in plain English and write it out if it is complex. Then I look for a table with the majority of the information I want or would like to display and set my 'FROM'. Then I take a step back and fill out what I want to see inbetwee the 'SELECT' and even chain from other tables without thinking about how I will get it to work.

Next I like to write out in plain English what my specific conditions might be with their respective SQL: AVG, SUM, largest, order by, etc., but I do not like to add it to my statement just yet.

Then I figure out how to match up all the right primary and foreign keys with 'JOIN', add the conditions to the end and see what I get. I inevitably screw up singular/plural table/column names. Fix those and start refining my conditions to get the output I want.
