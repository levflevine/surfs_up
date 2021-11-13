# Surf Up - Advanced Data Storage

## Overview of the analysis

The project delivers data analysis of weather at the Oahu island in Hawaii that is used by a private investor to make a decision about investing into the Surf n' Shake Shop serving surf boards and ice cream.

Specifically, the investor requested the analysis of the temperature data for the months of June and December in order to determine if the surf and ice cream shop business is sustainable year-round.

### Deliverables: 

1. Determine the Summary Statistics for June
2. Determine the Summary Statistics for December
3. A written report for the statistical analysis

### Tools and Data Sources

#### Tools

- Python Scripts
- SQLAlchemy Library
- SQLite
- Jupyter Notebook

#### Data Source

- [Weather Data](https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-online/module_9/hawaii.sqlite)

## Results

### Deliverable 1. Using Python, Pandas functions and methods, and SQLAlchemy, retrieved all the temperatures for the month of **June** for the years 2010 - 2017 and generated the summary statistics

***June Temperature DataFrame***

![June Temp](/Resources/Jun_Temp_DF.png)

***June Temperature Summary Statistics***

![June Stat](/Resources/Jun_Temp_Stat.png)

### Deliverable 2. Using Python, Pandas functions and methods, and SQLAlchemy, retrieved all the temperatures for the month of **December** for the years 2010 - 2017 and generated the summary statistics

***December Temperature DataFrame***

![Dec Temp](/Resources/Dec_Temp_DF.png)

***December Temperature Summary Statistics***

![Dec Stat](/Resources/Dec_Temp_Stat.png)

### Deliverable 3. Summary Report

#### Overview of the statistical analysis

The purpose of the analysis has been to summarize and provide quantitative description about the sample weather data for June and December. Key chracteristics analyzed were:

- distribution
- central tendency
- dispersion

#### Results 

Key differences in weather between June and December:

- *Central Tendency*: 

    - **Mean** temperature in June is **74.9 Degrees**, which is **3.6 Degrees** higher than in December
    - **Median** temperature in June is **75.0 Degrees**, which is **4.0 Degrees** higher than in December

- *Dispersion*: 

    - **Standard Deviation** in June is **3.3 Degrees**, which is **0.5 Degrees lower** than in December
    - **Inter-Quartile Range** in June is **4.0 Degrees**, which is **1.0 Degree lower** than in December
    - **Range** in June is **21.o Degrees**, which is **6.0 Degrees lower** than in December

- *Distribution*: 

    - The **Skewness** of the June Temperature sample distribution is nearly **symmetric** (negligent skewness to the left) with only 0.1 Degree difference between the Median and the Mean
    - The **Skewness** of the December Temperature sample distribution is nearly **symmetric** (negligent skewness to the right) with only 0.04 Degree difference between the Median and the Mean

- *Histograms*:

    - June Data

    ![June Data](/Resources/Jun_Hist.png)

    - December Data

    ![Dec Data](/Resources/Dec_Hist.png)

#### Summary of the results
    and there are two additional queries to perform to gather more weather data for June and December.

