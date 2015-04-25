---
title       : Developing Data Products Project Presentation
subtitle    : Using Slidify
author      : Niraj Sardana
job         : Developing Data Products
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [bootstrap, quiz]            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
github:
  user: nirajsardana
  repo: devdataprodrep
---

## Course Project Details

1. Project is available at https://nirajsardana.shinyapps.io/CrsProject/

2. This Course Project has 4 sections

3. Section-1 shows example of using Text, Numeric, Radio Button, Checkbox, Date Inputs in R

4. Section-2 shows example of using Datasets

5. Section-3 shows example of using Sliders

6. Section-4 shows example of using Tabsets

--- .class #id
<style>
.title-slide {
  background-color: #EEE;
}

.title-slide hgroup > h1,
.title-slide hgroup > h2 {
  color: #005;
}
</style>

## Section-1: Example of using Text, Numeric, Radio Button, Checkbox, Date Inputs in R

This section takes the following inputs from the User and displays them on the right side  
- Name, Age (numeric input), Gender (Male/Female), Hobbies (Sports, Movies, Music), Date of Birth

## Section-2: Example to show Datasets

This section takes the following inputs from the User and displays them on the right side  
- Dataset Name (rock/pressure/cars)
- No. of observations to view

Based on the number of observations entered, this example displays that many rows from the selected dataset on the right side

---
## Section-3: Example to show Sliders

This section takes as an input a value within range for the following 5 areas and then displays the same on right side:
- Integer
- Decimal
- Range
- Custom Format
- Looping Animation

## Section-4: Example to show Tabsets

This section takes the following as an input and then displays the same on right side:
- Distribution Type (Normal, Uniform, Log-normal, Exponential)
- Number of Observations

--- &radio

## Example of Interactive R code (Interactive Quiz)
What is 5 * 5 ?

1. 20
2. 10
3. 15
4. _25_

*** .hint

This is a hint

*** .explanation

This is an explanation
