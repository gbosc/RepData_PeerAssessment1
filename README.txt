###########################################################################################
##
## Coursera Course: Reproducible Research
##          Week 2: Project Assignment #1
##         Student: Gilles Bosc
##
###########################################################################################

This repository contains my submission for the Course Project Assignment #1 for the
Reproducible Research course offered via Coursera.

The assignment consists of a data analysis submitted as an R Markdown file (and subsequently
transformed by knitr into a Markdown file and an HTML file, using RStudio) whereby reviewers
should be able to review the submission and be able to understand how the data analysis
was performed.

Tools Used
----------
The analysis was performed using R and RStudio.

The Data
--------
The data analysis pertains to data collected from a personal activity monitoring device.
The device collected data at 5 minute intervals throughout the day.
The dataset consists of two months of data from an anonymous individual collected during the
months of October and November, 2012 and include the number of steps taken in 5 minute
intervals each day.

Variables in the Dataset
------------------------
- steps: Number of steps taken in a 5-minute interval (missing values are coded as NA)
- date:  The date on which the measurement was taken in YYYY-MM-DD format
- interval: Identifier for the 5-minute interval in which measurement was taken

The dataset consists of a comma-separated-values (CSV) file and there are a total of 17,568
observations. 

Dataset Source
--------------
The original dataset was obtained from this URL:
https://d396qusza40orc.cloudfront.net/repdata%2Fdata%2Factivity.zip

The original dataset is stored in my C5_CourseProject1 repository.
The original dataset is named "activity.csv"

Literate Statistical Program
----------------------------
The script used to download, unzip, load and also perform all the data analysis is a literate statistical
program.  The filename is 'PA1_template.Rmd'. It is an R Markdown file.





