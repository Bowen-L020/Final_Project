Title:
Analysis of COVID-19 Case and Death Rates in the United States (2020–2023)

Description:
This project focuses on key aspects of the pandemic:

Identifying distinct pandemic waves across five periods.
Calculating state-level case and death rates over time.
Evaluating whether COVID-19 became less virulent through trends in mortality and case rates.

Data Sources:
Population Data: U.S. Census Bureau (2020–2023).
COVID-19 Case & Death Data: CDC (Centers for Disease Control and Prevention).

Tools and Packages
The analysis was in RStudio using the following key R packages:

tidyr: Data cleaning and transformation.
dplyr: Summarization and grouping of datasets.
lubridate: Handling and transforming date formats.
httr2: Retrieving CDC data from APIs.
ggplot2: Data visualization.
patchwork: Combining multiple plots.

Methodology
Data Collection:
Population data and COVID-19 case/death data were collected for all 50 states, Washington D.C., and Puerto Rico.

Data Cleaning:
Removed missing values.
Transformed population data to tidy format.
Combined datasets using state and time variables.

Analysis:
Case and Death Rates: Calculated per 100,000 population.
Periodization: Divided into 5 key pandemic periods based on trends and CDC literature.
Virulence Analysis: Assessed changes in case and death rates to evaluate disease severity over time.
Visualization: Created line plots, bar charts, and trend visualizations to illustrate pandemic evolution.

Findings:
Distinct Periods: Five pandemic waves were identified based on trends:
Period 1: Initial outbreak (2020-01-25 – 2021-01-01).
Period 2: Vaccine emergence (2021-01-01 – 2021-06-25).
Period 3: Delta variant (2021-06-25 – 2021-12-25).
Period 4: Omicron variant (2021-12-25 – 2022-04-30).
Period 5: Declining phase (2022-04-30 – 2023-05-13).
Death Rates: States like New Jersey and Arizona reported higher death rates in earlier periods due to healthcare disparities.
Virulence Trends:
Death rates consistently declined across periods.
Improved vaccination, treatments, and immunity reduced COVID-19 severity over time.

Limitations:
The analysis does not account for within-state disparities (e.g., urban vs. rural areas).
Confounding variables such as age distribution and socioeconomic factors were not considered.

