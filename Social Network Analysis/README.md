# MACS 40101: Social Network Analysis

This folder contains files from my final project for this course. This project used data on the Los Angeles Sheriff's Department (LASD) to create a bipartitie social network of deputies and case file numbers for descriptive analysis of the network position of deputies most often involved in use of force incidents. This course was my first introduction to R. All code is in R. 

### data_cleaning_LASD.Rmd:
This file contains the code for the data cleaning process. The data comes from a project I was a research assistant on. We performed qualitative coding on LASD reports received from FOIA requests to create a database of misconduct and use of force incidents (one row per incident per deputy per victim). The beginning of the file also includes the write-up portion of the project. 

### data_analysis_LASD.Rmd
In this file, the cleaned data is used to create a bipartite network where the two types of nodes are deputies and case file numbers. The projection network of deputy nodes only is used for the bulk of the analysis. I conducted descriptive analysis of how network characteristics reflected the number of incidents a deputy was involved in. I also looked for patterns to reveal a covert network of deputies in gangs as the data includes some but not all identified gang members. 

This project is currently being expanded into a larger project on missing data strategies and deputy gangs. 
