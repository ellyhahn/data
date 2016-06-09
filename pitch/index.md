---
title       : Coursera - Data Product Pitch Presentation
subtitle    : 
author      : Elly Han
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Personal Finance Management

This Shiny App for me and my team. Me and my team members came from Korea, currently work in Hong Kong, and have to relocate United States in this year. So my team have to 3 different currency management, and all of us want to see 1 year forecast.  

--- 

## Parameters

- Checking account balance in US
- Checking account balance in Hong Kong
- Checking account balance in Korea
- Monthly Income
- Monthly Spending
- Yearly tax rate

---

## FX rates

- 1 U.S. dollar / Hong Kong dollar = 7.76
- 1 U.S. dollar / South Korean won = 1165.5

---

## Calculation

checkingUS + checkingHK/7.76 + checkingKR/1165.5 +

(monthlyIncome - monthlySpending - monthlyIncome * taxrate/100 ) * 12


