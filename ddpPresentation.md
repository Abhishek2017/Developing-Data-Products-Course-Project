Developing Data Products - Week 4 Course Project
========================================================
author: Abhishek Panda 
date: 10 August 2017
autosize: true


2) Introduction
========================================================

This Shiny application shows a bar char of the number of Deaths in Virginia in 1940.

The user select a Population Group (Rural/Male, Rural/Female, Urban/Male and Urban/Female) from the dropbox.

The app then shows a bar chart with corresponding Age Group: 50-54, 55-59, 60-64, 65-69, 70-74

More detail can be found at
- Deployed application: https://abhishek777.shinyapps.io/ddpweek4CP/
- Source code: https://github.com/Abhishek2017/Developing-Data-Products-Course-Project

3) Data
========================================================
This app uses the 'VADeaths' dataset in the 'datasets' package.
'VADeaths' stores the Death Rates  per 1000 population of Virginia in 1940. They are cross-classified by age group (rows) and population group (columns).

```
   Rural Male     Rural Female     Urban Male     Urban Female  
 Min.   :11.70   Min.   : 8.70   Min.   :15.40   Min.   : 8.40  
 1st Qu.:18.10   1st Qu.:11.70   1st Qu.:24.30   1st Qu.:13.60  
 Median :26.90   Median :20.30   Median :37.00   Median :19.30  
 Mean   :32.74   Mean   :25.18   Mean   :40.48   Mean   :25.28  
 3rd Qu.:41.00   3rd Qu.:30.90   3rd Qu.:54.60   3rd Qu.:35.10  
 Max.   :66.00   Max.   :54.30   Max.   :71.10   Max.   :50.00  
```

4) How it works
========================================================
- The user selects a Population Group from the dropbox.
- The bar char is automatically generated accordingly 
- The bar chart is automatically refreshed each time when a new selection is made.

5) PLOT
========================================================

Here  is  a  sample  image  when  user  selection  is  "Urban Female""

![ALT text](play.png)

