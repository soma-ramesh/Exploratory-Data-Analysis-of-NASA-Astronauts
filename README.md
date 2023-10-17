# **Exploratory-Data-Analysis-of-NASA-Astronauts**
----------
**Data Analysis and Dashboard using Power BI**
----------
![Astronaut Intro](https://github.com/soma-ramesh/Exploratory-Data-Analysis-of-NASA-Astronauts/assets/143477687/9a063227-461b-46b2-a68c-ea35037952a8)

## Introduction:
This is a Power BI project on Exploratory Data Analysis of **NASA ASTRONAUTS** from 1959 - 2009 
This project is to analyze and derive the key insights, which are very interesting for Space Lovers.

**_Disclaimer_**: The Dataset, which is used for this project is a public domain licenced dataset provided by Maven Analytics.
(https://www.kaggle.com/datasets/nasa/astronaut-yearbook/)

## Problem Statement:
1. Which American astronaut has spent the most time in space❓
2. Which university has produced the most astronauts❓
3. What subject did the most astronauts major in at college❓
4. Have most astronauts served in the military❓ Which branch❓ What rank did they achieve❓
5. How many astronauts selected per year❓

-----

## Skills Used:
The following Power BI features were incorporated.
1. Data Extraction
2. Data Transformation
3. Data Loading
4. Dax
5. Date Table (New Table)
6. Measures
7. Data Model
8. Report
9. Slicers
10. Dashboard
11. Bookmarks

---

## DAX 

1. **Total Astronauts** = COUNT(astronauts_Kaggle[Name])
2. **Male** = CALCULATE(COUNT(astronauts_Kaggle[Name]), (astronauts_Kaggle[Gender] = "Male"))
3. **Female** = CALCULATE(COUNT(astronauts_Kaggle[Name]), (astronauts_Kaggle[Gender] = "Female"))
4. **Active** = CALCULATE(COUNT(astronauts_Kaggle[Name]),(astronauts_Kaggle[Status] = "Active"))
5. **Retire**d = CALCULATE(COUNT(astronauts_Kaggle[Name]),(astronauts_Kaggle[Status] = "Retired"))
6. **Total Missions** = CALCULATE(SUM(astronauts_Kaggle[Space Flights]))

# Key Insights:
(https://github.com/soma-ramesh/Exploratory-Data-Analysis-of-NASA-Astronauts/blob/main/Astronauts_page-0002.jpg)
