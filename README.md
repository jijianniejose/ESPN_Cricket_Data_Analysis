📊 ESPN Cricket Data Analysis (Web Source: Power BI Project)

Overview

This project demonstrates an end-to-end data analysis workflow in Power BI, using live data scraped directly from the ESPN Cricinfo website. The dataset focuses on India vs South Africa ODI statistics, enabling exploration of batting, bowling, and fielding performance through interactive dashboards.

Data Source:
https://stats.espncricinfo.com/ci/engine/stats/index.html?class=2;opposition=3;team=6;template=results;type=batting

The project highlights skills in data acquisition (web scraping), transformation, DAX modeling, and insight storytelling using Power BI.

🎯 Project Objectives

Connect Power BI to the live ESPN web dataset.

Extract batting, bowling, and fielding statistics for India vs South Africa.

Clean and normalize data using Power Query.

Create calculated columns and DAX measures to enhance analysis.

Build interactive dashboards with KPIs, filters, and slicers.

Publish the final report to Power BI Service for sharing and automation.

🧠 Key Features

Web Data Connection – Live scraping from ESPN Cricinfo using Power BI’s “From Web” connector.

ETL Process – Implemented in Power Query, including column restructuring, null removal, and type correction.

DAX Modeling – Custom columns created with:

LOOKUPVALUE() for player categories

RANKX() for performance ranking

POWER() and ABS() for metric enhancement

Data Categories – Batting, Bowling, and Fielding performance data merged into structured tables.

Dashboard Components –

KPI cards for strike rate, averages, wickets, and economy

Dynamic slicers and span cards for comparative views

Report pages for batting, bowling, and fielding analysis

Automation & Publishing – Final model published to Power BI Service for web access and scheduled refresh.

🧾 Data Model Summary

Tables: Batting, Bowling, Fielding

Relationships: Player-based key fields for cross-table insights

Transformations: Header renaming, data type conversions, removal of extra rows

Calculated Columns & Measures:

Batting average, strike rate, boundary count

Bowling economy, average, wickets per match

Fielding dismissals ratio (D/I)

📈 Dashboard Highlights

Page 1: Batting Performance – KPIs, slicers, category cards

Page 2: Bowling Analysis – Economy trends, top bowlers

Page 3: Fielding Insights – D/I ratios, catch distribution

Interactive Elements: Filters for team, player, and match span

🛠️ Tools & Technologies

Power BI Desktop & Service

Power Query (ETL)

DAX (Data Analysis Expressions)

GitHub (Documentation)

Web Scraping via Power BI Connector

📚 Documentation

Each project stage is documented with screenshots, code snippets, and process notes:

Data Extraction (Web Scraping)

Data Cleaning (Power Query)

Modeling (DAX & Measures)

Dashboard Building

Publishing & Insights Summary
