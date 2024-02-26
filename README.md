# UCAS 2021 Undergraduate Grade Analysis

## Overview
webpage: [2021 UCAS Grades](https://sjj1017.github.io/ucourses/)

This repository hosts a web tool for analyzing the average grades of 2021 UCAS (University of Chinese Academy of Sciences) undergraduates across various courses. Users can filter courses by name and view average grades sorted from high to low.

Data from all the courses taken by UCAS undergraduate students enrolled in 2021 in the past 5 semesters. (temporarily no P/NP,letter graded courses)

## Features

- **Grade Sorting:** View courses with their average grades sorted from high to low.
- **Text-based Filtering:** Filter courses by entering text to find specific subjects.
- **Visualization:** Currently uses FusionCharts for data visualization, with plans to modify or replace this in the future.
- ***Clarification1:** name of course: COURSE_NAME@{units}{e/r}, where e=[elective courses], r= [required courses]*
- ***Clarification2:** Unable to get more details except for name, units and e/r, there might be a bunch of courses by different professor/ offered by different institutions put together, which might lead to bias*
- ***Clarification3:** Also mind survivorship bias! Difficult courses may be taken by genius. :)*

## Usage

- **Filter Courses:** Enter the course name in the search box to filter the courses. Please use '/' to seperate querys and '-' to exclude. (e.g. 线性代数I/微积分I/-II)
- **View Data:** The courses will be listed along with their average grades, sorted from highest to lowest.

## Grade Analysis Image Gallery

A glimpse grade distribution(Temporarily closed source due to privacy concerns):

![GPA Major distribution](GPA.png "GPA Major distribution")
![Region_Avg](region_avg.png "Region avg GPA distribution")
![Region70](region_median.png "Region 70%rank GPA distribution")

## Future Updates
- P/NP and letter graded courses soon included
- Photos in Los Angeles :)
- Curve for each course
- Potential replacement or modification of the FusionCharts component.

## Privacy Statement:
In the data acquisition process, the data has been anonymized, and only the majors, course names, course information, and grades are recorded.

## Acknowledgments
- Appreciation to FusionCharts for providing the powerful charting library used in this project.
