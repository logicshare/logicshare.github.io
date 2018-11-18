---
title       : mpgapp
subtitle    : App that predicts the MPG of a car
author      : Dain Thengunnal
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
github:
  user:logicshare
  repo:mpgapppitch
  
---

## Introduction

When buying a car, one of the most important factors one must assess about the car's performance is its mileage measured in Miles/(US) gallon (MPG).
The major component of the running cost is the skyrocketing fuel prices and one has to be diligent when deciding which car to buy to get your moneys worth.

---

## Why mpgapp?

This app predicts a car's MPG based on the inputs of Gross Horsepower, Weight and Transmission type of the car.
User can adjust the inputs in such a way that the desired predicted MPG is achieved.

### mpgapp screen sample

![](https://logicshare.github.io/mpgapp_screenshot.jpg)

---

## Sample data used by mpgapp to predict MPG


```r
tail(subset(mtcars,select=c("mpg","hp","wt","am")),10)
```

```
##                   mpg  hp    wt am
## AMC Javelin      15.2 150 3.435  0
## Camaro Z28       13.3 245 3.840  0
## Pontiac Firebird 19.2 175 3.845  0
## Fiat X1-9        27.3  66 1.935  1
## Porsche 914-2    26.0  91 2.140  1
## Lotus Europa     30.4 113 1.513  1
## Ford Pantera L   15.8 264 3.170  1
## Ferrari Dino     19.7 175 2.770  1
## Maserati Bora    15.0 335 3.570  1
## Volvo 142E       21.4 109 2.780  1
```

---

## References

App link    : http://logicshare.shinyapps.io/mpgapp

Source code : https://github.com/logicshare/DPPweek4Project




