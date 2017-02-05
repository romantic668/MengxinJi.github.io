---
layout: post
title: "California Soda Market"
description: "Policy Impact"
categories: ["Soda Market", "Policy"]
location: "UC Davis"
---

{% include image.html url="https://mengxinji.github.io/MengxinJi.github.io/images/school.png" caption="California High Schools" width="200" align="right" %}

Policy Impact of California soda market

I am now working on a project with professor Kristin Kiesel about California soda market. We aim to figure out the policy effect on California soda consumption and impact on teenager obesity rate. There was a implementation of a state-mandated ban about banning high school student consume soft drink, especially soda during school time. With the data collected from all California supermarkets containing household level consumptions with detailed transaction record, like time, quantity, product information and so on, together with California census data recording teenager obesity rate, we used causal inference method and in a triple difference approach, aiming to find the causality between the policy and the soft drink market consumption and policy impact on teenager obesity rate.  . We compare soft drink purchases of households with school-age children before and after implementation with purchases of households without school-age children in California, as well as households with and without school-age children in other states. The original data is over 32gb and stored in text file. For most of work, I use R to do data analysis and data visualization. To be specifically, I used dplyr, ggplot2 packages to do exploratory analysis and data analysis. I try to use analysis causal inference from policy.  Due to large data size, I also use SPARK based on python interface, mainly MapReduce and SQL to some data mergence work.  

Our analysis does not support the notion that school-age children compensate for the limited availability at school with increased consumption at home. We are now working on the manuscript and aim to some top tier peer-review journal. 
