---
weight: 1
title: Guideline for Troubleshooting
authors: null
categories:
tags: null
date: "2022-08-21"
description:  
draft: false
lastmod: "2022-08-21"
series: null
toc: true
---



<!--more-->
---

### **Proactive Troubleshooting Framework**
1) Use the Cause and Effect diagram to guide the process.  
The diagram breaks down the instrument into many categories according to the problem nature.  Follow through each cause and rule out some causes so that we can drill down on one specific cause.

2) Develop some troubleshooting tools.  Here are some examples of tools:  
&emsp;a) Run unextracted standard mix with matrix, and unextracted blank every time prior to running samples for system suitability.  
&emsp;&emsp;Use a R-Shiny app to plot the trend for each analyte in the standard mix.  The monitoring parameters could be retention time, peak area of quantifier, qualifier, and associated internal standards.  
&emsp;b) Use a R-Shiny app to plot the trend for mass spectrometer, parameters could include, but not limited to, the detector voltage.  

### **The Use of System Suitability Test**
1) Adjust the threshold so that it is sensitive enough to catch the change of LC and MS/MS.  
2) Build the chart of trend over time. 