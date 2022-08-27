---
weight: 4
title: Ferrule Issue - Worn Ferrule
authors: null
categories: ["LC: Peak Shape"]
tags: [Plumbing, Ferrule, Early Eluting Peak]
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
<img width ="360" height= "200" src = "/docs/images/Screenshot 2022-08-18 212950.png" style ="float: left" HSPACE="10" VSPACE="10"/>  

Here is an extracted ion chromatogram of two low QC injections for an opiates method.  They’re pretty perfectly overlaid except the very first peak.  This peak (in red trace) of one injection is fatter, almost a split peak. It is the morphine peak. The purple peak trace is the morphine peak after fix.  The next two peaks, the hydromorphone, and the oxymorphone, are almost exactly the same.  The earliest peak was distorted.

We truncated the run, we had some dead space in between the peak at about 3.5 minutes and at about 5.5 minutes.  The hash marks is representing the truncation.  
</div>

## Investigation, Troubleshooting Tool and Root Cause

<b>Troubleshooting Tool</b>:    
1) <b>Q</b>: Check the guard column and column change in the Maintenance Log.  
<b>A</b>: The guard column was changed just now, no injection on the guard column.  No problem. 
2) <b>Q</b>: Check the system suitability tests results.    
<b>A</b>: Morphine was not included in the standard mix, so no result is available.  
3) We assumed some type of error was created in the column connection when the new guard column was put on. when we took it off, we could see that the ferrule looked worn, tend to be a little bit hard to see. But what happens is the tip of the ferrule narrows, the walls get narrower, and it flares a little bit. And you can see that there’s that dark ring, that’s just indicating that it’s been in contact with the stainless steel. 

<b>Root Cause</b>: A worn ferrule

<div class = "row">
<img width ="360" height= "200" src = "/docs/images/Screenshot 2022-08-18 213225.png" style ="float: left" HSPACE="10" VSPACE="10"/>
<img width ="360" height= "200" src = "/docs/images/Screenshot 2022-08-18 213647.png" style ="float: left" HSPACE="10" VSPACE="10"/>
</div>

*Reference*:  
[MSACL: LC-MSMS Troubleshooting 101: Tips and Tricks for Getting Started : PART 1](https://www.msacl.org/index.php?header=Learning_Center&tab=Video_Library&subtab=Search_Video_Library)    
[MSACL: The Basics of LC-MSMS Troubleshooting: Tools, Strategy, Cases](https://www.msacl.org/index.php?header=Learning_Center&tab=Video_Library&subtab=Search_Video_Library)    

<button class="button" onclick="history.back()">Go Back</button>