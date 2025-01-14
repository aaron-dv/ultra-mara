

# Ultra Marathon EDA

#### Exploratory Data Analysis using Python & Pandas

## Table of Contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Findings](#findings)

## Project Overview

This data analysis project, completed as a guided learning exercise, aims to provide insights into the race performance of athletes who have participated in ultra marathon events.
Through the analysis of the data, we can draw insights as to whether factors such as season, gender, race distance & age influenced the performance of the athletes.

---

### Data Sources

The primary dataset used for this analysis is the "[The big dataset of ultra-marathon running](https://www.kaggle.com/datasets/aiaiaidavid/the-big-dataset-of-ultra-marathon-running) " found on Kaggle.

> The data in this file is a large collection of ultra-marathon race records registered between 1798 and 2022 (a period of well over two centuries) being therefore a formidable long term sample.

> The dataset contains 7,461,226 ultra-marathon race records from 1,641,168 unique athletes.
  
---

### Tools

- Python
  - Data Cleaning
- Pandas
  - Data Cleaning
- Seaborn
  - Data Visualisation

---

### Data Cleaning & Preparation

In the initial data preparation phase, we performed the following tasks:
1. Filtering the dataframe to include only events of the top 2 most frequent event distances, 
held in South Africa, from the year 2000 onwards
2. Feature creation by creating an athlete age column from the 'Athlete year of birth' and 'Year of event' columns
3. Manipulating the 'Event name' and 'Athlete performance' columns to remove unnecessary characters
4. Dropping unneeded columns
5. Handling missing & duplicate values
6. Fixing datatypes of columns
7. Renaming & rearranging columns

---

### Exploratory Data Analysis

EDA involved exploring the athlete data to answer key questions, such as:
- What is the difference in average speed between men and women?
  - How does event distance affect the difference (if any)?
- How does the age of an athlete affect their average speed in an event?
  - Which age group has the highest average speed?
  - Which age group has the lowest average speed?
- How does the season affect an athlete's average speed in an event?

---

### Findings

The analysis results can be summarised as follows:
1. Males have a slightly faster average speed than females across both 56km & 87km races
   1. There is a greater difference in average speed between males and females in 56km races compared to 87km races, this may infer that endurance is more of a key factor in long distance races
2. Average speed decreases as the age of an athlete increases - this decrease is more pronounced for male athletes than for female athletes
   1. 29-year-olds had the highest mean average speed
   2. 73-year-olds had the lowest mean average speed
3. In this South African context, season does not seem to have any major impact on athlete mean average speed - this is most likely due to the region's mild climate

---

### References

1. [Data Analyst Portfolio Project (EDA with Python Pandas)](https://www.youtube.com/watch?v=4sZFkPw87ng) - Ryan & Matt Data Science