Motivation for performing the analysis:


Tesla has reduced the price of its Electric Vehicle(EV) models 3 times within a year .


The question we are seeking to answer is why is EV sales and price declining though Sales were projected to grow by 30% in 2025. Possible reasons can be growing competitors, more incentives, more inventory, insufficient charging infrastructure. Benefit of doing this work is understanding the market conditions to make better decisions from the consumer side as well as from the auto industry side. We would like to find out the number of EV makers over years, Production vs Deliveries vs price over the years. Incentive Act benchmark, unsold inventory, charging issues in major cities. Any relationship between these variables,  prediction for coming years through linear regression.

https://www.businessinsider.com/electric-car-ev-sales-prices-problem-transportation-2024-1


Likely data sources:

CSV/ Excel format


Dataset 1 (csv)

Historic Electric vehicle sales in US per year.( does not have much data for 2023)

https://www.kaggle.com/datasets/ratikkakkar/electric-vehicle-population-data


Dataset 2(csv)

Electric vehicle sales globally with projections till 2030.

https://www.kaggle.com/datasets/padmapiyush/global-electric-vehicle-dataset-2023


Dataset 3 (pdf)

Quarterly production vs sales for Tesla:
https://ir.tesla.com/tesla-vehicle-production-deliveries-and-date-financial-results-webcast-first-quarter-2024


Dataset 4 (Web Scraping):
EV Charging Station Counts by State table from 'https://www.cnet.com/roadshow/news/how-many-ev-charging-stations-are-there-in-the-us/' that contains the number of public charging stations per state.

Dataset 5 (PDF format)
Total EV sales 2023 and Q1 2024 for competitor analysis.
https://www.coxautoinc.com/wp-content/uploads/2024/04/Q1-2024-Kelley-Blue-Book-Electric-Vehicle-Sales-Report.pdf



Overall Flow: 


Data Gathering - we will download data from the websites mentioned in csv format, we will read data from the Tesla Annual reports in PDF. We will try to acquire more datasets for comprehensive analysis.

Data Cleansing - All the various datasets will be logically grouped into R data frames, anomalies fixed, missing values removed, formats corrected and tidy up.

Data Transformation - data from cleaned R data frames will be merged or joined, filtered,sorted,pivoted  to suit the analysis requirements and visualization needs.

Data Analysis  - Summary statistics for variables like EV sales, battery capacity, charging time. Time Series Analysis for trends and patterns in EV sales or charging station usage over time. we will plot appropriate visualizations for relationship between variables using bar chart, animate chart, correlation analysis.

Conclusions - based on the exploratory data analysis, we will derive key observations and outcomes and plot visualizations.

Roles and responsibilities


Dhanya to work on 3 datasets - EV variables across all countries in the world, Competitor Sales Analysis, Tesla's Overall vehicle production and deliveries trend over Quarters in 2023 and 2024 .

Evelyn will work on storytelling with the  historic EV sales for last decade (2011-2022). Web scraping battery capacity. Statistical analysis

