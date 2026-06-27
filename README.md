# CMSC320 Final Project
### By: Yudiishbala S. (_@yudhiishvs_), Ethan Z. (_@realnumber1forever_), and Arvind K. (_@akakanav_)


# Table of Contents
* [Title](https://github.com/yudhiishvs/cmsc320-final-project#cmsc320-final-project)
  * [Authors](https://github.com/yudhiishvs/cmsc320-final-project#by-yudiishbala-s-yudhiishvs-ethan-z-realnumber1forever-and-arvind-k-akakanav)
* [Table of Contents](https://github.com/yudhiishvs/cmsc320-final-project#table-of-contents)
* [Repository Link](https://github.com/yudhiishvs/cmsc320-final-project#github-repository)
* [Dataset Link](https://github.com/yudhiishvs/cmsc320-final-project#dataset)
* [Initial Comments (_06/09/2026_)](https://github.com/yudhiishvs/cmsc320-final-project/tree/main#initial-dataset-comments-06092026)
  * [What Dataset?](https://github.com/yudhiishvs/cmsc320-final-project#what-dataset-are-we-using)
  * [Why Dataset?](https://github.com/yudhiishvs/cmsc320-final-project#why-are-we-using-this-dataset)
* [Initial Exploration (_06/26/2026_)](https://github.com/yudhiishvs/cmsc320-final-project/tree/main#initial-data-visualizationexploration-06262026)


# GitHub Repository
Link for GitHub Repository can be found here: https://github.com/yudhiishvs/cmsc320-final-project


# Dataset
Link of Project Dataset can be found here: https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Crashes/h9gi-nx95/about_data

*NOTE: This dataset will automatically be updated on a daily basis as more data is collected. However, the final dataset version that we are using for this Project is up-to-date as of <u><b>26th June, 2026</b></u>.*


# Initial Dataset Comments (_06/09/2026_)
## What Dataset Are We Using?
For this project, we are going to use the Motor Vehicle Collisions - Crashes dataset from NYC
Open Data. This dataset is maintained and published by the City of New York. This dataset
contains records of police reports about various motor vehicle collisions that have occurred
throughout the five boroughs of New York City. In this dataset, each row represents a single
crash event and includes information about when and where the collision occurred, along with
details about the types of vehicles that were involved, why the collision occurred, and the
resulting outcomes with regard to injuries and fatalities.

The dataset contains a lot of various features about each collision. These include: the date and
time of the crash, the borough in which it occurred, the ZIP code, latitude and longitude
coordinates, the number of people that were injured or killed in the collision, what contributed to
causing the collision in the first place, and the types of vehicles involved in the collision.
Because these variables provide information about both the circumstances and outcomes of
each collision, we were confident that this dataset would provide us with a detailed view of traffic
incidents across NYC.

This dataset contains millions of crash records, and it is continuously updated as new collision
reports become available. As a result, it can be said that it provides a diverse collection of
observations that span across many years, locations, vehicle types, contributing factors, and
crash outcomes. The size and scope of this dataset also make it very well suited for conducting
statistical analyses and help us better understand trends related to traffic safety and injury
outcomes. Because of this richness and variety in information that is available to us for each
crash, we believe that this dataset will provide a strong foundation for investigating patterns in
motor vehicle collisions and help us answer our research question regarding injury risk in NYC
traffic collisions: _**Can we predict whether a reported NYC motor vehicle collision results in
at least one injury, and which crash characteristics are most strongly associated with
injury risk?**_

## Why Are We Using This Dataset?
We decided to use this dataset because we believe that traffic safety is an important issue,
especially in a very dense city like New York City (NYC), and a dataset like this one would help
us get the details we need to be able to study the issue completely. Instead of us asking a
generic question, such as “_Where do crashes happen most often?_,” we can instead focus on a
question such as “_Can we predict whether a reported NYC motor vehicle collision results in at
least one injury, and which crash characteristics are most associated with injury risk?_”

This is a very large dataset with a lot of variations, because it contains crash level records
across many years, locations, different vehicles or contributing factors, and various measures of
injuries or fatalities. Furthermore, this dataset is updated very often. Currently, as of this time, the dataset seems to be updated on a daily basis. Because each row in the data set contains a separate crash event, we will be able to compare patterns of collisions across various times, places, and conditions, and make enough observations to the point that we can calculate various statistics, perform hypothesis tests, and in the end, visualize our final results in an effective manner.

This dataset also enables us to examine traffic collisions from multiple different perspectives.
We can begin to look at things such as how injury rates vary across the five boroughs of NYC,
the times of day that various collisions occurred, the types of vehicles involved in each collision,
and what caused the collision in the first place. By being able to look at all of this information,
we can explore whether certain conditions of the collision are correlated with the likelihood of
injury increasing or decreasing. Furthermore, we can gain a better understanding of the factors
that contribute to the injuries that occur in NYC traffic collisions.

Finally, this dataset provides our group with a stronger understanding and practical experience
of using beneficial data science skills. Because this dataset has so many rows and columns of observations, we can start to identify meaningful patterns within this data and learn how to determine whether these patterns are statistically significant. We can use techniques and tools, such as data exploration and analysis, summary statistics, visualizations, hypothesis testing, and eventually explore various Machine Learning Models/Algorithms so that we can better understand the relationships between different crash characteristics and injury outcomes. By doing all of this, we hope that we can answer our research question in a manner that focuses solely on the data, and develop a deeper understanding of the factors that are associated with injury risk in NYC traffic collisions. We believe that this dataset is a good choice for our project because it is comprehensive, it is updated frequently, it is publicly available, and it is well suited for studying an important, prevalent issue that can impact millions of people’s lives every year.


# Initial Data Visualization/Exploration (_06/26/2026_)
See alternative `master` branch for an initial exploration and visualization of the aforementioned data set: https://github.com/yudhiishvs/cmsc320-final-project/tree/master 


### [Back to Top](https://github.com/yudhiishvs/cmsc320-final-project#cmsc320-final-project)
