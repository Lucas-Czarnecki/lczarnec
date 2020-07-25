---
title: "Cleaned Covid-19 Data from JHU"
date: 2020-07-22T15:46:52-06:00
Description: "Cleaned Covid-19 data from JHU"
Tags: ["GitHub", "R", "Covid-19"]
Categories: ["data"]
DisableComments: false
Draft: false
---

*This article discusses my GitHub repository [COVID-19-CLEANED-JHUCSSE](https://github.com/Lucas-Czarnecki/COVID-19-CLEANED-JHUCSSE), what it is, and why I created it.*

## Background

When the Covid-19 pandemic became the new normal for Canadians in March of 2020 I, like countless others, found myself at home feeling uncertain about the future. I occupied my time in those early weeks of the pandemic by examining data on the novel coronavirus in an effort to better understand the virus' impact. I spent most of this time reviewing data from Johns Hopkins University's (JHU) [Covid-19 dashboard](https://www.arcgis.com/apps/opsdashboard/index.html#/bda7594740fd40299423467b48e9ecf6), which remains one of the most popular online resources for tracking the global spread of Covid-19.

JHU's project was admirably ambitious at the time, being among the first to effectively track and aggregate data on Covid-19 from numerous health authorities around the world. 

JHU's repository, however, was not without its limitations. Each morning (or night) I would tweak my script to accommodate whatever changes JHU introduced that day. The frequency with which JHU introduced changes meant that a script which worked one day would be broken the next. As a result, some days I found myself spending more time diagnosing errors than analyzing data. 

In time, I could maintain a daily cleaned version of JHU's data for my analyses. On a whim, I decided to make the cleaned data public on GitHub - hoping it might spare someone else the grind of cleaning it themselves. 

To my surprise, I found some members of GitHub community using my cleaned repository for their projects. Encouraged by this development, I have promoted and maintained the repository ever since. 


## Download the Cleaned Data Set

You can find the data on my [GitHub repository](https://github.com/Lucas-Czarnecki/COVID-19-CLEANED-JHUCSSE) including the code I use to clean the data. The repository is updated daily. For that reason I recommend creating a local clone to fetch the daily updates. 

For those unfamiliar with GitHub and unsure where to start, I recommend using [GitHub Desktop](https://desktop.github.com). 

## More Information About the Cleaned Data

The COVID-19-CLEANED-JHUCSSE repository contains cleaned daily reports and time series data from the 2019 Novel Coronavirus COVID-19 (2019-nCoV) Data Repository by Johns Hopkins University for Systems Science and Engineering (JHU CSSE). 

I created this repository for multiple reasons. First, to provide a stable version of the JHU CSSE data repository where variable names would not be subject to change. Second, to provide a data set that maintains a consistent naming convention across all files. Third, to address various inconsistencies in how JHU managed their data; including how dates and time were encoded. Finally, I wanted to provide time series data to analysts in long rather than wide format. 

You will find more detailed information pertaining to the data on my GitHub repository's `README.md`.