## Education Data in School & Student Improvement

**Time**: January 2020

**Goal**: 

This is a small individual project, including analyzing educational data from AF for Schoolwide and comparzing individual student improvement, and providing valuable thoughts for further research.

Following [suggestions](http://nicercode.github.io/blog/2013-04-05-projects/) by [RICH FITZJOHN](http://nicercode.github.io/about/#Team) (@richfitz). This folder is orgarnized as follows.

```
proj/
├── data/ data used in this project
├── code/ codes run
└── doc/ instruction, pdf reports, and presentation slides if present
```

## Introduction

As part of this project is to close the achievement gap for our scholars, AF enroll students from neighborhoods that traditionally have low student achievement. As a consequence, it is not surprising that students will enter the 5th grade significantly below grade level. AF are committed to helping all students read at grade level by the end of 8th grade.

In order to better understand the story behind the students' data, I analyzed the provided data set and prepare a set of findings using `R` that will deliver to the AF leadership team and school principals. The analysis contains the students from two AF middle schools: **BMS** and **CHMS** 

AF will utilize the results of this analysis as a reference to deliver equal educational opportunities for all the students regardless of their race and economic status. Beyond this analysis, AF as an engaged parter in the community will take this exercise as an example to discuss how to improve public education quality and enhance the students’ academic performance in the larger conversation.

## Data
* [Sample Data](data/F&P_Sample_Data_Set.xlsx) 

Each row in the dataset represents a single student and contains the student’s beginning of year (BOY) and end of year (EOY) F&P reading scores. It will be necessary to use the information contained within the “F&P Proficiency levels” tab to convert raw F&P scores into their respective proficiency levels

## Code
* [Rmd Code](code/AF_DA_Cici_Chen.Rmd)

## Reports
* [RMarkdown PDF Report](doc/AF_DA_Cici_Chen.pdf)
