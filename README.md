# European-Flights-Analytics-Dashboard-Power-BI-DAX-Excel
End-to-end Power BI dashboard analyzing European flight traffic, airport performance, market share, seasonality, and COVID-19 impact.
# Recommended Structure and Order
# 1. Project Title / Headline

Multi-page Power BI dashboard providing insights into European aviation performance, airport traffic, country-level flight activity, COVID-19 impact, and seasonal travel patterns from 2016–2022.
# 2. Short Description / Purpose

This interactive Power BI dashboard analyzes over 87 million flight movements across 333 airports and 42 European countries between 2016 and 2022.

The dashboard enables stakeholders to monitor airport performance, compare country-level traffic, evaluate the impact of COVID-19 on aviation, and identify seasonal travel trends through KPI-driven analytics and interactive visualizations.
# 3. Tech Stack

The dashboard was built using the following tools and technologies:

• 📊 Power BI Desktop – Primary platform for dashboard development and visualization.

• 📂 Power Query – Used for data cleaning, transformation, and preparation.

• 🧠 DAX (Data Analysis Expressions) – Used for KPIs, market share calculations, recovery rates, YoY analysis, seasonality metrics, and time-intelligence functions.

• 📅 Custom Calendar Table – Created to support time intelligence calculations such as SAMEPERIODLASTYEAR, YoY Growth, Recovery Analysis, and Seasonal Trends.

• 📝 Data Modeling – Relationships established among:

Flights
Airports
Countries
Calendar Table

to enable filtering, aggregation, and analytical calculations.

• 📁 File Format – .pbix for development and .png for dashboard previews.

# 4. Features / Highlights
# (i) Business Problem

The European aviation industry generates large volumes of airport and flight activity data across multiple countries and years. Monitoring airport performance, identifying traffic concentration, evaluating pandemic impact, and understanding seasonal demand patterns can be challenging without a centralized analytics solution.

# (ii) Goal of the Dashboard

The goal of this dashboard is to provide a comprehensive aviation analytics platform that enables users to:

Monitor flight traffic trends.
Analyze airport performance.
Compare country-level aviation activity.
Measure COVID-19 impact and recovery.
Identify seasonal travel patterns.
Support data-driven aviation planning and decision-making.
# (iii) Walkthrough of Key Visuals
# •Executive Overview Dashboard
![Executive Overview](https://github.com/Robin1311-jaiswal/European-Flights-Analytics-Dashboard-Power-BI-DAX-Excel/raw/main/1.%20Executive%20Overview%20Dashboard.png)
 Key KPIs
Total Flights: 87.06M
Airports Tracked: 333
Countries Covered: 42
Total Arrivals: 43.5M
Total Departures: 43.5M

These KPIs provide a high-level summary of European aviation activity during the study period.

•Monthly Flight Trend
Displays aggregated monthly flight activity across all years.

•Key observation:
Flight activity peaks during summer months.
Lower traffic is observed during winter periods.

•Top 5 Airports by Total Movements
Highlights the busiest airports in Europe.

•Key observation:
Amsterdam Schiphol consistently records the highest traffic volume.

•Top 5 Countries by Total Flights
Compares aviation activity across countries.

•Key observation:
Spain generated the highest flight traffic volume.

# •Airport Performance Dashboard
![Airport Performance](https://github.com/Robin1311-jaiswal/European-Flights-Analytics-Dashboard-Power-BI-DAX-Excel/raw/main/2.Airport%20Performance%20Dashboard.png)
•Key KPIs
Busiest Airport
Airport Market Share %
Average Flights per Airport
Total Airports

•Airport Ranking Analysis
Ranks airports by total flight movements.

Key observation:
Traffic is concentrated among a small number of major hub airports.

•Departures vs Arrivals Analysis
Compares operational balance across major airports.

•Airport Market Share Analysis
Evaluates each airport's contribution to total European traffic.

# •Country Analysis Dashboard
![Country Analysis](https://github.com/Robin1311-jaiswal/European-Flights-Analytics-Dashboard-Power-BI-DAX-Excel/raw/main/3.Country%20Analysis.png)
•Key KPIs
Top Traffic Country
Average Flights per Country
Country Market Share %
Total Countries

•Flights by Country
Ranks countries based on total flight volume.

•Airport Distribution by Country
Shows how airport infrastructure varies across countries.

•Country Share Analysis
Highlights the concentration of aviation activity among leading countries.

•Traffic Trend by Country
Compares country performance over time and reveals the impact of COVID-19.

# •COVID-19 Impact Dashboard
![COVID Impact](https://github.com/Robin1311-jaiswal/European-Flights-Analytics-Dashboard-Power-BI-DAX-Excel/raw/main/4.Covid%2019%20Impact%20analysis.png)
•Key KPIs
Pre-COVID Peak (2019): 17.2M Flights
COVID Crash (2020): 7.42M Flights
Traffic Recovery (2021): 9.25M Flights
Recovery Rate (2021): 53.84%

•Total Flights by Year
Shows the dramatic decline in traffic during 2020.

•Year-over-Year Flight Change
Highlights annual gains and losses.

•Key observation:
2020 experienced the largest decline in aviation activity.

•Monthly Comparison (2019 vs 2020)
Compares monthly traffic before and during the pandemic.

•Recovery Trajectory (2020–2022)
Tracks aviation recovery following the COVID-19 disruption.

# •Seasonality Analysis Dashboard

![Seasonality](https://github.com/Robin1311-jaiswal/European-Flights-Analytics-Dashboard-Power-BI-DAX-Excel/raw/main/5.Seasonality%20Dashboard.png)
•Key KPIs
Peak Month: August
Off-Peak Month: December
Peak Quarter: Q3
Average Monthly Flights: 7.25M
Peak vs Off-Peak Difference: 34.22%
Seasonal Gap: 2.10M Flights
•Monthly Seasonality Trend
Illustrates recurring seasonal traffic patterns.

• Seasonality Heatmap
Displays monthly flight intensity across years.
Key observation:
Summer months consistently experience the highest traffic volume.
•Peak vs Off-Peak Analysis
Compares high-demand and low-demand travel periods.

•Pre-COVID vs Post-COVID Seasonal Comparison

Examines how seasonal travel patterns changed following COVID-19.

# (iv) Business Impact and Insights
-European aviation peaked at 17.2M flights in 2019 before declining by 56.8% during COVID-19 in 2020.
-Traffic recovered by 24.8% in 2021 but remained below pre-pandemic levels.
-Amsterdam Schiphol emerged as the busiest airport across the study period.
-Spain recorded the highest flight volume among European countries.
-Aviation activity is highly concentrated among a small number of airports and countries.
-August is the busiest month while December records the lowest traffic volume.
-Peak-month traffic is 34.2% higher than off-peak traffic, highlighting strong seasonal demand.
Q3 consistently records the highest aviation activity due to summer tourism and holiday travel.

