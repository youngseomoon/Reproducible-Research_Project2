# Peer-graded Assignment: Reproducible Research_Project2

#Introduction

Storms and other severe weather events can cause both public health and economic problems for communities and municipalities. Many severe events can result in fatalities, injuries, and property damage, and preventing such outcomes to the extent possible is a key concern.

This project involves exploring the U.S. National Oceanic and Atmospheric Administration's (NOAA) storm database. This database tracks characteristics of major storms and weather events in the United States, including when and where they occur, as well as estimates of any fatalities, injuries, and property damage.

#Data

The data for this assignment come in the form of a comma-separated-value file compressed via the bzip2 algorithm to reduce its size. You can download the file from the course web site:

Storm Data [47Mb]
There is also some documentation of the database available. Here you will find how some of the variables are constructed/defined.

National Weather Service Storm Data Documentation
National Climatic Data Center Storm Events FAQ
The events in the database start in the year 1950 and end in November 2011. In the earlier years of the database there are generally fewer events recorded, most likely due to a lack of good records. More recent years should be considered more complete.

#Review criteria
Has either a (1) valid RPubs URL pointing to a data analysis document for this assignment been submitted; or (2) a complete PDF file presenting the data analysis been uploaded?
Is the document written in English?
Does the analysis include description and justification for any data transformations?
Does the document have a title that briefly summarizes the data analysis?
Does the document have a synopsis that describes and summarizes the data analysis in less than 10 sentences?
Is there a section titled "Data Processing" that describes how the data were loaded into R and processed for analysis?
Is there a section titled "Results" where the main results are presented?
Is there at least one figure in the document that contains a plot?
Are there at most 3 figures in this document?
Does the analysis start from the raw data file (i.e. the original .csv.bz2 file)?
Does the analysis address the question of which types of events are most harmful to population health?
Does the analysis address the question of which types of events have the greatest economic consequences?
Do all the results of the analysis (i.e. figures, tables, numerical summaries) appear to be reproducible?
Do the figure(s) have descriptive captions (i.e. there is a description near the figure of what is happening in the figure)?
As far as you can determine, does it appear that the work submitted for this project is the work of the student who submitted it?

#Assignment

The basic goal of this assignment is to explore the NOAA Storm Database and answer some basic questions about severe weather events. You must use the database to answer the questions below and show the code for your entire analysis. Your analysis can consist of tables, figures, or other summaries. You may use any R package you want to support your analysis.

Questions

Your data analysis must address the following questions:

Across the United States, which types of events (as indicated in the EVTYPE variable) are most harmful with respect to population health?
Across the United States, which types of events have the greatest economic consequences?
Consider writing your report as if it were to be read by a government or municipal manager who might be responsible for preparing for severe weather events and will need to prioritize resources for different types of events. However, there is no need to make any specific recommendations in your report.

Requirements

For this assignment you will need some specific tools

RStudio: You will need RStudio to publish your completed analysis document to RPubs. You can also use RStudio to edit/write your analysis.
knitr: You will need the knitr package in order to compile your R Markdown document and convert it to HTML
