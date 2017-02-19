---
layout: post
title: "BART Throughput Pattern"
description: "prediction"
categories: ["Throughput", "Prediction", "Machine Learning"]
location: "UC Berkeley"
---

{% include image.html url="https://mengxinji.github.io/MengxinJi.github.io/images/output_hlFikR.gif" caption="Bayarea Bart Throughput" width="200" align="right" %}

Bay Area Rapid Transit (BART) Throughput Pattern Analysis

Visualize the throughput of the BART among 45 stations, from 2011 to 2015, with more than 40 million ridership record. 

Investigate the key factors for the daily total throughput with generalized linear model. Study a wide range of factors, like weather information (temperature, humidity) and demographic data (crime rate, income). The top 3 statistically significant factors are: visibility, humidity, and wind speed.

Applied random forest to assess the variable importance of each factor, which helps capture the non-linear impact from each factor. The most important factors are consistent with the linear model.
