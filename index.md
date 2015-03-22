---
title       : Dose-Response Estimation for Radiation
subtitle    : Survival time of rats exposed to radiation
author      : Edward D. Browne
job         : Researcher
logo        : slidify_logo.png
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [mathjax]           # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides

###logo        : clipart.jpeg
###logo        : clipart.pdf


--- &twocol

## Motivation

*** =left

We have an experimental dataset of the measured survival 
time for rats exposed to radiation for a small set of values of radiation.
A model to predict the survival time for exposure to any arbitrary dose
of radiation would be extremely valuable.
<p>
Through detailed analysis of the dataset, we arrived at the optimal
linear model to represent cause-and-effect relationship inherent in
the survival time resulting from the given dose of radiation administered
to the subject rats
</p>

*** =right

![plot of chunk unnamed-chunk-1](assets/fig/unnamed-chunk-1.png) 

---

## The result of our analysis is a quadratic curve

$y = 49.667 - 0.112x + 0.0000566x^2$

Using this predictive function, we will be able to predict the survival time
for any arbitrary dose of radiation with a 95% confidence level

---

## 

<div class="red2">

<b> This newfound ability to predict survival for untested doses gives us many benefits:</b>

</div>

<p> </p>



> - Reduces need for laboratory rats
> - Reduces unnecessary exposure for research personnel to radiation
> - Saves time and money


--- &twocol

## Summary of Analytic Results

*** =left
Raw data, from Rat Radiation Experiment

![plot of chunk unnamed-chunk-2](assets/fig/unnamed-chunk-2.png) 

*** =right
Linear model, quadratic degree, fitted to data
![plot of chunk unnamed-chunk-3](assets/fig/unnamed-chunk-3.png) 
*** =fullwidth
---




