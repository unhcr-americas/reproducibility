# Reproducibility: Why & How

## Intro 

This repo contains the slides of a webinar to promote reproducible aproaches in UNHCR - specifically when dealing with Household survey dataset

Slides are available in [English](https://unhcr-americas.github.io/reproducibility/index.html) & [French](https://unhcr-americas.github.io/reproducibility/index_fr.html) - and were converted in PDF ([English](https://unhcr-americas.github.io/reproducibility/index.pdf) & [French](https://unhcr-americas.github.io/reproducibility/index_fr.pdf)) with the following:

```{r }
source("https://git.io/xaringan2pdf")
remotes::install_github("rstudio/chromote")
install.packages(c("progress", "jsonlite", "pdftools", "digest"))
xaringan_to_pdf("index.html")
xaringan_to_pdf("index_fr.html")
```

## Objectives:
As a result of the webinar, Learners will:
1.	Understand what they can gain from analysis reproducibility.
2.	Know what the main technical requirements are to set up for their analysis to be reproducible.
3.	Recipes & cookbook: data science is like cooking! Have a demonstration of a practical way to make a cake using household survey data: crunching, analysis & interpretation & data stories!

##  Target Participants:
Staff at country, regional or global levels with functions related to information management, operational data management or data-related work, such as statisticians, data analysts, BI specialists, economists, etc.

## Promotional Blurb

Have you ever completed the development of a data product with the feeling that you may have done a mistake or not have used the optimal way to clean or process your data? 
As an analyst, if using “point & click” interface, “rewinding” all the steps at an advanced stage of the development of your product can be extremely painful and lengthy. Errare humanum est sed perseverare... If you want to learn from your mistake rather than to suffer from them, then analysis reproducibility is what you need...
In this session, we will introduce you to the basics of analysis reproducibility and explain you what elements you need to watch for when you kick start your analysis so that you can always rewind and improve any products you have already spent time on. We will also show you how you can learn from analysis done in a reproducible way done by other colleagues.
We will also show you through practical examples how to implement a fully reproducible data analysis workflow applied to a Household Survey dataset using R statistical Language: from initial data exploration to joint interpretation till the creation of data stories. 

Last, we hope that this session will motivate you to join the vibrant R users community in UNHCR and soon become an R champion. 

In order to make the most of the session, we would advise you to install the following open source environment:
-	[R](https://cran.r-project.org/bin/windows/base/) & [Rtools]()
-	[Rstudio Free version](https://www.rstudio.com/products/rstudio/download/)
-	Create an [account on Github](https://github.com/join?)  and install [Github desktop](https://desktop.github.com/)

You may also start installing UNHCR Packages – following the instruction in their respective documentation published on Github:
1.	Use UNHCR Open data  - https://unhcr.github.io/unhcrdatapackage/docs/ 
2.	API to connect to internal data source - https://unhcr-web.github.io/hcrdata/docs/
3.	Perform High Frequency Check https://unhcr.github.io/HighFrequencyChecks/docs/
4.	Process data crunching for survey dataset - https://unhcr.github.io/koboloadeR/docs/ 
5.	Use UNHCR graphical template- https://unhcr-web.github.io/unhcRstyle/docs/

Last, you may also take advantage of going through one or more of the R learning content on  [UNHCR Learn & Connect- R training](https://unhcr.csod.com/ui/lms-learner-playlist/PlaylistDetails?playlistId=e90e2279-e3a4-4ef2-8b74-757f91d224b2)  and see some practical tutorial on [humanitarian-useR-group](https://humanitarian-user-group.github.io/)

The best way to start and learn is to have a concrete project! If you have one and need mentoring, we can liaise after the session.

## Webinar Content:

1.	Why do you need to work in a reproducible way?
a.	Being scientific.
b.	Being productive.
c.	Being open to learning.

2.	Conditions for reproducibility.
a.	Work from curated data source (RIDL... RIDL... RIDL...).
b.	Use a statistical language & packages.
c.	Document your process!

3.	Hands-on practice: a practical run-through based on Household survey dataset.
a.	Data Crunching for automatic data exploration.
b.	Preparing for and recording findings from joint data interpretation session.
c.	Generating microsite to tell stories with data.

