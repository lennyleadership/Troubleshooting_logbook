---
weight: 1
title: Reconstitution Solvent Issue
authors: null
categories: ["MS/MS: Peak Shape"]
tags: [Dwell Time]
date: "2022-08-21"
description:  
draft: false
lastmod: "2022-08-21"
series: null
toc: true
---



<!--more-->
---

## Symptom
<div class = "row">
<img width ="360" height= "200" src = "/docs/images/Screenshot 2022-08-18 221057.png" style ="float: left" HSPACE="10" VSPACE="10"/>
This is from marijuana metabolite.  The normal presentation is on the right, the fronting peaks on the left.  The peaks are all the same for three MRM. 
We don't use a guard column.  

</div>

## Investigation, Troubleshooting Tool and Root Cause

<b>Investigation and Tools used</b>:  
1) <b>Q</b>: Check the Maintenance Log.   
<b>A</b>: There were 850 injections and we normally change it at 2500. So it doesn't really look like column degradation.   
2) <b>Q</b>: Is sample overloaded?   
<b>A</b>: The right volume was injected.  
3) <b>Q</b>: Check the system suitability tests results.    
<b>A</b>: They like normal.  
4) It makes us suspicious of the sample itself. 

<b>Root Cause</b>: Samples were reconstituted with 100% acetonitrile.

<div class = "row">
<img width ="360" height= "200" src = "/docs/images/Screenshot 2022-08-18 221237.png" style ="float: left" HSPACE="10" VSPACE="10"/>
</div>

*Reference*:  
[MSACL: LC-MSMS Troubleshooting 101: Tips and Tricks for Getting Started : PART 1](https://www.msacl.org/index.php?header=Learning_Center&tab=Video_Library&subtab=Search_Video_Library)    

[MSACL: The Basics of LC-MSMS Troubleshooting: Tools, Strategy, Cases](https://www.msacl.org/index.php?header=Learning_Center&tab=Video_Library&subtab=Search_Video_Library)  

<button class="button" onclick="history.back()">Go Back</button>