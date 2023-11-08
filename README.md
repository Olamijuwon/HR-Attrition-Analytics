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

### Meaning of Attrition is essential in this finding ?
Attrition is the down-sizing of a firms employee pool by HR proffessionals, can also be the number of people who leave a company over a given point.

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
    - - Columns that were grouped; - Distance from Home into near, far and very far.

                                  - Working Life Balance into Bad, Average, Good and Excellent.

                                   - Performance Rating into low and high.

                                    - Job involvement into very low, low, moderate and high.

## Exploratory Data Analysis

Key Performance Indicators:
- Total employee: 1470
- Attrition count: 237
- Avrrage years at company: 7
- Average Income: $6.5k

Key questions
- Which gender has higher attrition rate ?
- Which age bracket has higher attrition rate ?
- Does proximity to work place affect attrition ?
- Does being married or single affect attrition rate ?
- Does being educational field  affect attrition rate ?
- Does company position affect attrition rate ?


## Data Analysyis


DAX Measures used for the Nortwind Database


``` DAX
    Color = IF([Total Sales]>[Previous Month Sales], "Green", "Red")
```

``` DAX
    Color Sales/Target = IF([Total Sales] >= [Sales Target], "Green", "Red")
```

``` DAX
