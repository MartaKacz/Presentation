---
title       : Evaluation Comparison with Radar
subtitle    : My first presentation
author      : Marta Kaczmarz
job         : Kruk S.A.
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---


## What is an EvaluatorComparison with Radar

It is a shiny app which I created for Devoloping Data Products course on coursera.org. 

The idea was to see on one plot how my competitions where evaluated by other people i.e. team leader and workmates. I want to use some non popular chart but still the chart which summarize a basic information and is visually preatty ;).

--- .class #id 

## Example data

The example data is eveluation of my competition in my job. The data should be in csv file. In fact you can use different type of data, the things that you want to compare should be in rows and the features in the columns.

Example data frame:

```
##                 Work_Planning Goal_orienting Openness_On_Changes
## Self assessment          3.00           3.60                3.75
## Team Leader              3.25           3.40                3.50
## Team mates               3.20           3.31                3.28
##                 Cooperation Communication Inference Knowlege
## Self assessment         3.5          3.40      3.00     3.25
## Team Leader             4.0          3.29      3.25     3.23
## Team mates              3.3          3.40      3.36     3.25
```

--- .class #id 

## What is the Radar plot

Radar plot is also called 'spider plots' or 'web plots'. It can succinctly summarize a lot of information, and is visually pleasing.

Basically it take a data frame, scale all numeric columns, and then plot how far above/below average (the thick black line) each of the values are for a particular row of data.


![plot of chunk unnamed-chunk-2](assets/fig/unnamed-chunk-2-1.png) 

--- .class #id 

## Where you can find it?

You can see this app on shinyapps.io :

http://martakacz.shinyapps.io/EvaluationComparisonApp

