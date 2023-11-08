# HR-Attrition-Analytics

- [Project Overview](#project-overview)
- [Tools](#tools)
- [ Data Cleaning/Preparation](#data-cleaning/preparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysyis](#data-analysyis)
- [ Result/Findings](#result/findings)

## Project Overview

The scope of this project is how we can reduce employee's attrition through HR Analytics and also enhance employee's performance.
By analysing various aspects of the data, we seek to identify trends, dada driven recommendations and gain a deeper understanding of the employee's performance.


## Tools.
Excel and Power BI    - Data cleaning was donee in power query
Powe BI                - Data analysis was done too.
                        - Creating reports .

## Data Cleaning/Preparation

Initial data preparation phase;
- Data loading and inspection.
- Deleting of empty coloumns and removing of columns not needed for analysis.
   - - colums like Education, Monthly rate, over 18 (as all the employees are above 18) etc.
- Changing of some data types for wfficient visualization and to draw proper insights.
- Grouping of the data is an essential part of this analysys.
    - - Columns that were grouped; - Distance from Home into near, far and very far
                                  - Working Life Balance into Bad, Average, Good and Excellent.
                                  - Performance Rating into low and high
                                  - Job involvement…

## Exploratory Data Analysis

Key questions
- Showing Total sales by budget, last month, last year , last target this was done using Dax.
- Showing sales by continent.
- What is the average Sales Amount by Employee?
- Show sales representative that hits the highest target.
- Sales target by order month and title.

## Data Analysyis


DAX Measures used for the Nortwind Database


``` DAX
    Color = IF([Total Sales]>[Previous Month Sales], "Green", "Red")
```

``` DAX
    Color Sales/Target = IF([Total Sales] >= [Sales Target], "Green", "Red")
```

``` DAX
