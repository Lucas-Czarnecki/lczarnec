---
title: "Canadian Federal Elections from 1867 to the Present (DATA)"
date: 2020-08-30T14:16:54-06:00
Description: "GitHub Repository of Canadian Federal Election Results"
Tags: ["GitHub", "R", "Federal", "Canada", "Elections"]
Categories: ["data"]
DisableComments: false
Draft: false
---

*This post describes a GitHub repository I created to organize elections data from the Canadian Library of Parliament.*

## Introduction

A couple months back, I created a data repository consisting of Canadian federal election results from 1867 to the present. The data are originally from the [Canadian Library of Parliament](https://www.parl.ca/) and feature candidate-level vote totals dating back to confederation. 

The Library of Parliament should be commended for concatenating these data and making them available to the public. Those who study elections in Canada know that such results are seldom digitized and are typically not presented with scholars and journalists in mind.  

Thanks to the Library of Parliament, users can download the original data set from the library’s [Parlinfo webpage]( https://lop.parl.ca/sites/ParlInfo/default/en_CA/ElectionsRidings/Elections). Parlinfo enables users to filter data according to parliament, type of election (i.e., general or by-election), date, and other variables such as political affiliation and gender. Desired data can then be exported in excel format. 

## Why Create This Repository?

While the library’s data are clean, and generally well-presented, the format does not immediately lend itself to analysis in most statistical programs. The purpose of my repository then was to reorganize the data into more researcher-friendly formats. To this end, the original data set was wrangled into long-formatted .csv files and a master .Rds file for R-users. The cleaned data also contains modified variables intended to facilitate data exploration and analysis. 

The modified data set, for example, contains three “new” variables, which are presented as columns rather than as rows; the latter being the approach in the original data set. These include `Parliament`, which records the session of parliament, `Election_Date`, which records the date of the election, and `Election_Type`, which distinguishes between general and by-elections. 

Other data wrangling procedures were applied to improve how the Library of Parliament recorded candidates’ names. Among the procedures, new variables were created to distinguish between candidates’ first, middle, and last names. Candidate names were also cleaned to address inconsistent uses of uppercase within candidates’ last names. Other text cleaning operations, such as removing erroneously inserted punctuation marks, were also applied to correct candidates’ names. The scripts used for these and all other operations are included in the repository such that users may replicate my work.

## Download the Data

Interested parties can download or clone this repository from [GitHub](https://github.com/Lucas-Czarnecki/Canadian-Federal-Elections). Note that the Library of Parliament updates their data set with recent by-election and general election results. The cleaned data in this repository will also be updated to reflect the most recent Canadian federal general and by-election results.
