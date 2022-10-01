---
weight: 99
title: Mobi Peak
authors: null
categories: ["LC-MS/MS: Peak Shape"]
tags:
date: "2022-08-18"
description:  
draft: true
lastmod: "2022-08-18"
series: null
toc: true
---
Directory: 03 Other Peak Problems  
file name: 99_mobi_peak


<!--more-->
---

## Symptom
<div class = "row">
<img width ="360" height= "200" src = "/docs/images/Screenshot 2022-07-31 225801.png" style ="float: left" HSPACE="10" VSPACE="10"/>
<img width ="360" height= "200" src = "/docs/images/Screenshot 2022-07-31 225909.png" style ="float: left" HSPACE="10" VSPACE="10"/>
</div>

It is seen on Waters TQS system, very reproducible, sometimes for a whole batch where we’ve had a slight shift in retention time. And this lines up perfectly with where there is an end of a function, or what is called a period with AB Sciex. And so what it seems like to us is that when there’s especially when there’s a lot of functions lining up or starting, and it happens at a certain part of the peak, you’ll have a signal drop out, it’s like there’s a delay in passing of the signal from the mass spec to the LC, if you smooth your data, you will never see it. if you don’t smooth, you’ll see it now. And then the current version that we’re using SCN 905 MassLynx isn’t supposed to have that. But it does create some very interesting peaks.


## Tool and Root Cause

<a href="https://troubleshooting-logbook.netlify.app/docs/troubleshooting-logbook/03-other-peak-problems/" class="button">Go to "OTHER PEAK PROBLEMS"</a>