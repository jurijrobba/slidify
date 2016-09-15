---
title       : 1974 Motor Trend US magazine gas consumption data
subtitle    : 
author      : Jurij Robba
job         : 
framework   : shower        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Data

 * We are using dataset called 'mtcars'
 * Data extracted from 1974 Motor Trend US magazine
 * Only interested in miles per gallon and transmission

---

## Data


```
##       mpg              am        
##  Min.   :10.40   Min.   :0.0000  
##  1st Qu.:15.43   1st Qu.:0.0000  
##  Median :19.20   Median :0.0000  
##  Mean   :20.09   Mean   :0.4062  
##  3rd Qu.:22.80   3rd Qu.:1.0000  
##  Max.   :33.90   Max.   :1.0000
```

---

## Problem

 * We are comparing miles per galon for automatic and manual transmission
 * We want to compare histograms at different number of bins (different bin sizes)
 * X-axis of histograms need to be aligned for comparison

---

## Different resolutions

 * We are interested in between 1 to 50 bins
 * Number of bins needs to be user selectable (achioeved with slider)

---

## Conclusion

 * No matter bin resolution driving manual was more efficient in 1974!
 * App available at [this link](https://jurijrobba.shinyapps.io/manual_vs_automatic/)
