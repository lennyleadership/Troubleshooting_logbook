---
weight: 2
title: Sample was not collected
authors: null
categories: ["LC-MS/MS: Sensitivity"]
tags: 
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
<img width ="360" height= "200" src = "/docs/images/Screenshot 2022-08-23 231811" style ="float: left" HSPACE="10" VSPACE="10"/>  
<figure>This is the marijuana metabolite at the lower limit of quantitation (the LLOQ) calibrator. Normally, the quantifier peak is about between 2000 - 3000 counts per second for the peak area. And in the problem chromatogram it's only 330.</figure> 
</div>

## Investigation, Troubleshooting Tool and Root Cause

<b>Investigation and Tools used</b>: 
1) <b>Q</b>: Check the system suitability tests results.  
<b>A</b>: We had not done a system suitability test for THC on that day, but we did do a system suitability test for vitamin D and that passed.  The result for vitamin D can't prove the LCMS performance is good for THC, because the vitamin D is positive mode, and the THC is a negative mode.  We can't rule out the LC-MS/MS yet.
2) <b>Q</b>: Run a THC LLOQ calibrator from the previous batch.  
<b>A</b>: The peak area looks normal.  We can rule out autosampler, LC and MS.  
3) <b>Q</b>: Check the pressure trace.   
<b>A</b>: Normal. We can rule out leak concern.
4) <b>Q</b>: We are suspicious sample preparation.  
<b>A</b>: We use solid phase extraction.  The technician forgot to take the waste bin away before they add the eluting solvent.


<b>Root Cause</b>: Sample was lost at the last step in the extraction using solid phase extraction.   
<div class = "row">
<img width ="720" height= "400" src = "/docs/images/.png" style ="float: left" HSPACE="10" VSPACE="10"/>  
<figure></figure>
</div>



*Reference*:  
[MSACL: The Basics of LC-MSMS Troubleshooting: Tools, Strategy, Cases](https://www.msacl.org/index.php?header=Learning_Center&tab=Video_Library&subtab=Search_Video_Library)  

<button class="button" onclick="history.back()">Go Back</button>