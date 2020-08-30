---
title: "The Uncertain Future of API Research"
date: 2020-08-26T15:59:36-06:00
Description: "Describes the current state of social media research"
Tags: ["Facebook", "Twitter", "API", "Social Media", "Research"]
Categories: ["article"]
DisableComments: false
Draft: true
---

*This article discusses some of the new challenges and uncertainties involved in social media research following the Cambridge Analytica scandal.*

## Background

I never anticipated when collecting data for my masters thesis that the methods I would use would become obsolete overnight as a result of a major political scandal. The scandal involved a private consulting company (that you have probably heard of by now) called Cambridge Analytica, which abused Facebook's API to collect the personal information of tens of millions of Facebook users without their consent. Cambridge Analytica then used that data to microtarget individuals with customized advertisements that they claimed could sway undecided voters to support Donald Trump for president in 2016. 

The efficacy of Cambridge Analytica's methods are [highly dubious](), but besides the point. In abusing Facebook's API the company sparked an international conversation about data privacy that regrettably dichotomized privacy and open science. Indeed, the data I collected **-- ethically --** from Facebook used the same API that Cambridge Analytica had abused. 

Facebook in 2018, after the Cambridge Analytica story became public knowledge, decided to terminate access to its public Graph API. Facebook's decision came as the scope of the scandal fully emerge and as public and political scrutiny mounted. Unfortunately, Facebook's decision impacted developers and researchers alike rending many methods and practices for obtaining data from Facebook obsolete.  

In another blog I will discuss the issue further and will cover more recent developments within Facebook that will be of interest to social and data scientists as well as some of the alternative approaches coming out of companies like Twitter. (Just in passing, Twitter has taken the exact opposite approach to Facebook and has pushed to make its API **more** accessible). For now, I'll turn the discussion to my data.

## The Data and the 2015 Canadian Election Campaign
 
I was able, before Facebook terminated access to its public Graph API, to collect data relevant to the 2015 Canadian general election campaign on Facebook. The campaign was the longest in modern Canadian history at 78 days. The election was also salient to Canadians who turned out to vote in the highest numbers seen in Canada since the 1990s. The campaign touched on multiple high profile issues including the Syrian migration crisis, the controversial niqab ban, the senate expenses scandal, and heated debates about the Canadian economy. Overall, the issues, salience, and length of the campaign make it one of the most interesting elections in recent memory for social scientists to study. 

The data consists of party leaders' campaign messages and Facebook user responses to those messages from August 4th until October 19th, 2015; the duration of the 2015 election campaign on Facebook. In total, the data includes over 1,700 campaign messages from three major political parties in Canada (i.e., the Conservatives, Liberals, and New Democratic Party) and over 200,000 Facebook user comments from 92,516 unique users made in response to these messages.

[The data](https://github.com/Lucas-Czarnecki/Facebook_Canada2015) are organized relationally such that Facebook users’ party identification, political preferences, and emotional responses to campaign messages can be identified and measured. This repository thus offers a unique look at how the three major parties campaigned on Facebook during 2015. Given the events following Cambride Analytica it is unlikely that a data set like this will be made available anytime soon (at least not with Facebook data).

