---
weight: 3
title: Post Column Leak Issue
authors: null
categories: ["Sensitivity <- HPLC"]
tags: [Leak]
date: "2022-08-16"
description:  
draft: false
lastmod: "2022-08-27"
series: null
toc: true
---
Directory: 04 Poor Sensitivity    
File name: 03_Post_column_leak



<!--more-->
---
<b>Note</b>: There was no problems with mobile phase or needle wash or any method changes.  

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

<b>Root Cause</b>: Leak underneath the post column switch.  The reason that chromatography was normal is that the leak was post column, the separation had already occurred. And the nature of this leak I guess, was such that 90% of the flow ended up in the tray beneath the valve and 10% of the flow went to the mass spec without any distortion in the peak. 

<b>Lesson Learned</b>: why did the system suitability test pass if there was a leak present? Well, we had set the threshold too low.  

<b>Question for follow-up</b>: Could pressure trace be handy for detecting post-column leak?



*Reference*:  
[MSACL: The Basics of LC-MSMS Troubleshooting: Tools, Strategy, Cases](https://www.msacl.org/index.php?header=Learning_Center&tab=Video_Library&subtab=Search_Video_Library)  

<button class="button" onclick="history.back()">Go Back</button>