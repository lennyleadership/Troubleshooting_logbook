---
weight: 4
title: MS Interface Region Issue
authors: null
categories: ["LC-MS/MS: Sensitivity"]
tags: [MS Interface Region]
date: "2022-08-16"
description:  
draft: false
lastmod: "2022-08-27"
series: null
toc: true
---
Directory: 04 Poor Sensitivity    
File name: 04_dirty_MS_interface_region



<!--more-->
---
<b>Note</b>: There was no problems with mobile phase or needle wash or any method changes.  

## Symptom
<div class = "row">
<img width ="360" height= "200" src = "/docs/images/Screenshot 2022-08-24 072206.png" style ="float: left" HSPACE="10" VSPACE="10"/>  
<figure>The bottom green trace is the 25-hydroxy vitamin D2 internal standard when we identify the problem, and then the red trace which is several fold higher after we fix the problem.</figure> 
</div>

## Investigation, Troubleshooting Tool and Root Cause

<b>Investigation and Tools used</b>: 
1) <b>Q</b>: Checked the system suitability tests results.  
<b>A</b>: The system suitability test is border lined.  
2) <b>Q</b>: Double checked with yesterday's calibrator.  
<b>A</b>: It was also low.  
3) <b>Q</b>: Investigate extraction.  
<b>A</b>: Nothing wrong with it.  
4) <b>Q</b>: Double-checked with the autosampler  
<b>A</b>: Injected an opiate low calibrator. Got a normal peak area.  The autosampler was okay, no leak.  
5) <b>Q</b>: Check the trend of the system suitability test results.  
<b>A</b>: Looked at the trend of vitamin D to internal standard peak area.  We saw the peak areas were dropped over time.  
That is particularly true if I tell you that our other mass spec instrument instrument number two has D2 IS mean peak areas that are around 90,000, about where we started out in February with instrument number one. So we took the samples from one and injected them on two. And we did see those higher peak areas again suggesting that there's problem with the Mass Spec of number one. 
6) <b>Q</b>: Checked with the mass spec and drilled down to the specific part:   
&emsp;a) The electrospray ionization capillary could be aged.  
&emsp;b) The mass calibration or resolution could have drifted.  
&emsp;c) The detector voltage could be low.   
&emsp;d) The mass spec interface region could be dirty.   
<b>A</b>: &nbsp;a) the ESI capillary had been changed fairly recently, we didn't think that was the problem.   
&emsp;b) The resolution and calibration were all fine.  
&emsp;c) The detector voltage was fine.  
&emsp;d) Replaced the mass spec interface region, the peak area was almost doubling.

<b>Root Cause</b>: dirty mass spec interface region





*Reference*:  
[MSACL: The Basics of LC-MSMS Troubleshooting: Tools, Strategy, Cases](https://www.msacl.org/index.php?header=Learning_Center&tab=Video_Library&subtab=Search_Video_Library)  

<button class="button" onclick="history.back()">Go Back</button>