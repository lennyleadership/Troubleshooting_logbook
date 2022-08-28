---
weight: 1
title: Guard Column Issue
authors: null
categories: ["LC: Peak Shape"]
tags: [Peak Broadening]
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
<img width ="360" height= "200" src = "/docs/images/Screenshot 2022-08-18 154827.png" style ="float: left" HSPACE="10" VSPACE="10"/>   
<figure>The analyte is Temazepam.  The peak is broadened, almost to split for all three MRM.</figure> 
</div>

## Troubleshooting Tool and Root Cause

<div class = "row">

<b>Troubleshooting Tool</b>: 
1) <b>Q</b>: Check the Maintenance Log.   
<b>A</b>: 615 injections.
2) <b>Q</b>: Check the system suitability tests results.    
<b>A</b>: They like normal.  


<b>Root Cause</b>: The guard column should be replaced at 500 injections, and there were 615 injections on it.  

</div>

*Reference*:  
[MSACL: LC-MSMS Troubleshooting 101: Tips and Tricks for Getting Started : PART 1](https://www.msacl.org/index.php?header=Learning_Center&tab=Video_Library&subtab=Search_Video_Library)  
[MSACL: The Basics of LC-MSMS Troubleshooting: Tools, Strategy, Cases](https://www.msacl.org/index.php?header=Learning_Center&tab=Video_Library&subtab=Search_Video_Library)  

<button class="button" onclick="history.back()">Go Back</button>