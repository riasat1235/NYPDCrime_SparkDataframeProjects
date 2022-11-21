# NYPD Crime Analysis with Spark Dataframe
<!--- Table of contents -->

<details open="open">
<summary>
<b> Table of Contents</b>
</summary>
<ol>
<li> <a href="#about-the-project"> About The Project </a></li>
<li> <a href="#outline-of-the-project"> Outline of the Project </a></li>
<li> <a href="#getting-started"> Getting Started </a></li>
</ol>
</details>


## About The Project

In this project, the crime data from New York Police Department (NYPD), collected from 
[NYPD open data](https://data.cityofnewyork.us/Public-Safety/NYPD-Complaint-Data-Historic/qgea-i56i),
will be analysed using Spark Dataframe. The dataframe is a good way to analysed the structured
data. This dataset includes all the valid felony, misdemeanor and violation crimes reported
to NYPD from the year 2006 to 2019. Here, some correlations in crime factors will be found
to make an effective crime prediction to improve the efficiency of the Police Department.


## Outline of the Project
- Stage 1: Data insights 
- Stage 2: Exploratory data analysis
  * Removing redundant data
  * Correcting data format
  * Data impunging
  * Checking correlation
  * Checking Skewness
- Stage 3: Analysing data 
  * Pattern of crime 
    + Total crime in different locations
    + Most frequent crimes
    + Most dangerous time
    + Risk and safe zones in different boroughs
    + Victims pattern
  * Crime density based on population 
  * Heat map of crime locations
- Stage 4: Classification : Predict crime level
- Stage 5: Performance of model

## Getting Started
