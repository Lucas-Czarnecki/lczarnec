---
title: "The 2015 Canadian Federal Election on Facebook (DATA)"
date: 2020-08-30T14:16:54-06:00
Description: ""
Tags: ["GitHub", "R", "Facebook", "Canada", "Elections"]
Categories: ["data"]
DisableComments: false
Draft: false
---

*This post introduces my GitHub repository [Facebook_2015](https://github.com/Lucas-Czarnecki/Facebook_Canada2015) and the kinds of research questions it can help answer.*

## Introduction 

I have created a new repository called [Facebook_2015](https://github.com/Lucas-Czarnecki/Facebook_Canada2015) in a recent effort to move my past and current projects onto GitHub. This repository contains data that I collected for my masters thesis and that I believe will be of general interest to social scientists.

Note that this blog post only offers a quick summary of the data. For more detailed information, please see the repository's [main page](https://github.com/Lucas-Czarnecki/Facebook_Canada2015).

## Context: The 2015 Election Campaign

The repository contains Facebook user data from the 2015 Canadian general election, which was the longest in modern Canadian history at 78 days and resulted in one the highest voter turnouts in Canada since the 1990s. The campaign touched on multiple issues that were salient to voters at the time. Issues include the Syrian migration crisis, the controversial proposal to ban niqabs during citizenship swearing-in ceremonies, the senate expenses scandal, and heated debates concerning the health of the Canadian economy. Overall, the issues, their public salience, and the length of the campaign, makes 2015 one of the most interesting electoral case studies in recent memory.

## The Data: What's Inside?

The data consists of three federal party leaders’ campaign messages (N = 1,711); more specifically, these are the Facebook posts published from Stephen Harper, Justin Trudeau, and Tom Mulcair's official public Facebook pages. The data also includes the responses to these messages from everyday Facebook users (n = 92,516). Data range from August 4th to October 19, 2015; the duration of the campaign on Facebook. 

The scripts I used to clean and organize the data are also included on GitHub. You will find more information pertaining to how the data were wrangled on the repository's [main page](https://github.com/Lucas-Czarnecki/Facebook_Canada2015) and in the [raw data folder](https://github.com/Lucas-Czarnecki/Facebook_Canada2015/tree/master/data/raw). 

The repository contains both raw as well as cleaned datasets. These are separated into their respective folders; [dataset](https://github.com/Lucas-Czarnecki/Facebook_Canada2015/tree/master/data/datasets) and [raw](https://github.com/Lucas-Czarnecki/Facebook_Canada2015/tree/master/data/raw).  

## How the Cleaned Data are Organized

The cleaned data are presented as three relational data sets. Each data set has unique attributes that makes it suitable for different kinds of analyses. Below is a brief description of each data set and a few broad suggestions for the kinds of research questions you might ask.

### <b> 1.  The Facebook Pages Dataset </b>

This data set (N = 1,711) contains **structured information** pertaining to every campaign message (i.e., Facebook post) published from the three aforementioned party leaders' Facebook pages. Structured data include metrics that record how much engagement Facebook posts received; more specifically, fields record the total number of likes, comments, and shares that each post received throughout the campaign. 

This data set will be useful to researchers interested in gauging campaign performances on Facebook. For example, the data can be analyzed to demonstrate how successful candidates' Facebook campaigns were based on overall user engagement. Analyses can also, thanks to timestamps that record when each post was published, observe engagement over time to see how candidates' performances changed throughout the course of the campaign. 

### <b> 2. The Campaign Messages Dataset </b>

The second data set contains the text-based portions of the Facebook posts (n = 1,530) found in the Facebook Pages Dataset. Note then that posts, which did not include text-based messages (e.g., a photo from the campaign trail without accompanying text) are not captured here. The data set also contains many of the same structured fields found in the first data set; including timestamps and metrics for measuring Facebook user engagement.

This data set is relevant to researchers who want to examine the kinds of words and rhetoric used during political campaigning. The most valuable data here, therefore, are the text-based messages, which will be of interest to those studying campaign messaging generally and will be especially relevant to politics scholars who are interested in **text analysis**. Note that the text data in this data set has already been cleaned of noise (e.g., URL links) that would otherwise obfuscate most text analyses. A raw version of the text data is also available to those wishing to preprocess the text data themselves.

### 3. <b> The Facebook Users Dataset </b>

The final data set is a collection of over 200,000 Facebook user responses to party leaders' campaign messages during the 2015 campaign. These responses come from more than 92,000 unique Facebook users of whom over 26,000 have identifiable partisan preferences. The data include the text-based portions of users' comments, which create a very large corpus suitable for text analysis. The data set also contains many of the same fields as the two previous data sets. Note that the data set has been preprocessed to remove common noise from the text data, but that a raw version of the text is also available to those wishing to preprocess the text data themselves.

The sheer size of this data set suggests to me that it will be of interest to many researchers for answering very different kinds of research questions. The most obvious kinds of questions to me involve campaign effects and partisanship. Because of the relational relationship between data sets, researchers can, for example, identify the effects that exposure to campaign messaging on Facebook has on users' emotions or political preferences. Indeed, that was what I used these data for when writing my thesis. 

One area that I think could use more scholarly attention is online partisanship. For example, does repeated exposure to campaign messaging on Facebook increase partisanship? I believe that the data I have assembled here can help answer these kinds of timely questions as well.

## Download the Data

You can download the data on [GitHub](https://github.com/Lucas-Czarnecki/Facebook_Canada2015).

If you use the data, please cite either the repository's [DOI](https://zenodo.org/record/4001164#.X0wmg--SlPY) or my [thesis](https://prism.ucalgary.ca/handle/1880/110936); which ever is more appropriate to your project. 