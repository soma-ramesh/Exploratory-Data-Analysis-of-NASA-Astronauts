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

## DAX:

1. **Total Astronauts** = COUNT(astronauts_Kaggle[Name])
2. **Male** = CALCULATE(COUNT(astronauts_Kaggle[Name]), (astronauts_Kaggle[Gender] = "Male"))
3. **Female** = CALCULATE(COUNT(astronauts_Kaggle[Name]), (astronauts_Kaggle[Gender] = "Female"))
4. **Active** = CALCULATE(COUNT(astronauts_Kaggle[Name]),(astronauts_Kaggle[Status] = "Active"))
5. **Retire**d = CALCULATE(COUNT(astronauts_Kaggle[Name]),(astronauts_Kaggle[Status] = "Retired"))
6. **Total Missions** = CALCULATE(SUM(astronauts_Kaggle[Space Flights]))
----



# Key Insights:

![Astronauts_page-0002](https://github.com/soma-ramesh/Exploratory-Data-Analysis-of-NASA-Astronauts/assets/143477687/2bfad1b2-47af-4529-b91a-4a9e9538e412)
👉 We can see from the line plot above 1975 there is a sudden rise in the number of astronauts, similar to 1996.






![Astronauts_page-0003](https://github.com/soma-ramesh/Exploratory-Data-Analysis-of-NASA-Astronauts/assets/143477687/e7ac5aac-730b-49d6-b413-d73afc5182ff)

👉 From the above barplot, we can see that Two Astronauts **Franklin R. Chang-Diaz** and **Jerry L.Ross** took 7 times Filghts to Space and interestingly both are **North American Astronauts**.





![Astronauts_page-0004](https://github.com/soma-ramesh/Exploratory-Data-Analysis-of-NASA-Astronauts/assets/143477687/e3b429e6-0ba6-4287-9f60-0eb10ea14b44)
👉 From the above report, Pie Chart shows the count of **Male** Astronauts from the different continents. Out of **307 Male Astronauts** approx. **94.46%** are **North Americans**.






![Astronauts_page-0005](https://github.com/soma-ramesh/Exploratory-Data-Analysis-of-NASA-Astronauts/assets/143477687/250a85a4-1436-46f5-8ce1-ee528550a2d4)
👉 From the above report, Pie Chart shows the count of **Female** Astronauts from only two continents i.e **North America** and **Asia**. Out of **50 Female Astronauts**  **96%** are **North Americans**.


👉 **Asian** Female Astronauts are **Shannon W.Lucid (China)** and **Kalpana Chawla (India)**.


👉 **Kalpana Chawla** spent **734hr** of Time in Space.






![Astronauts_page-0006](https://github.com/soma-ramesh/Exploratory-Data-Analysis-of-NASA-Astronauts/assets/143477687/54b0bbc7-6401-44d3-8fd8-e225940271fa)

👉 From 1959 - 2009 Data, **NASA** selected a total of **357** Astronauts in years as different groups (20 groups upto 2009) for different Space Missions.


👉 A total of  340  American Astronauts, **Jeffrey N. Williams**, a **North American Astronaut** has spent most of the time in space i.e **12818hr** of time in space.







![Astronauts_page-0007](https://github.com/soma-ramesh/Exploratory-Data-Analysis-of-NASA-Astronauts/assets/143477687/3eb017f8-353c-4d38-a204-667a23a59d74)

👉 Out of  **357**  Astronauts, **211** i.e.  59.10% of the Astronauts served in military and the rest are civilians.

👉  Out of **50** Female Astronauts, **13** served in military.

👉  Out of **307** Male Astronauts, **198** served in military.








![Astronauts_page-0008](https://github.com/soma-ramesh/Exploratory-Data-Analysis-of-NASA-Astronauts/assets/143477687/a7c9c23f-f12c-4065-8b68-4c70dc97b2dc)

👉 **US Naval Academy** has produced maximum Astronauts of 12.

👉  Majority of the Astronauts are graduated in  Aeronautical Engineering followed  by Aerospace, Mechanical Engineering, Medicine.



-----


**NASA ASTRONAUTS Dashboard**

(https://github.com/soma-ramesh/Exploratory-Data-Analysis-of-NASA-Astronauts/blob/main/Astronaut.pbix)

-----


# Thank you
