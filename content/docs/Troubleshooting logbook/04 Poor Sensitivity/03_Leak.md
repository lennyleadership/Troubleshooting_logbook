---
weight: 3
title: Leak Issue
authors: null
categories: ["LC-Sensitivity"]
tags: [Leak]
date: "2022-08-16"
description:  
draft: false
lastmod: "2022-08-27"
series: null
toc: true
---



<!--more-->
---

## Symptom
<div class = "row">
<img width ="360" height= "200" src = "/docs/images/Screenshot 2022-08-24 071956.png" style ="float: left" HSPACE="10" VSPACE="10"/>  
<figure>It's our benzodiazepine high calibrator.  The retention time is the same, the peak shape is the same.  When overlaying peaks from today with a peak from before, the retention times are the same, but the highest peak is only about 12% of the typical performance.</figure> 
</div>

## Investigation, Troubleshooting Tool and Root Cause

<b>Investigation and Tools used</b>:   
1) <b>Q</b>: Check the system suitability tests results.  
<b>A</b>: test passed.  
2) <b>Q</b>: Had a feeling of something not right with the LC.  
<b>A</b>: There was a pool in the tray underneath the post column switch.

<b>Root Cause</b>: Leak underneath the post column switch.

<b>Lesson Learned</b>: why did the system suitability test pass if there was a leak present? Well, we had set the threshold too low.  




*Reference*:  
[MSACL: The Basics of LC-MSMS Troubleshooting: Tools, Strategy, Cases](https://www.msacl.org/index.php?header=Learning_Center&tab=Video_Library&subtab=Search_Video_Library)  

<button class="button" onclick="history.back()">Go Back</button>