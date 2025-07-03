
 Paris 2024 Olympics Dashboard using Power BI](https://github.com/KUNDANKADAM/Paris2024-Olympics-PowerBI-Dashboard)

##  Objective

The objective of this project is to create an interactive Power BI dashboard that presents comprehensive insights into the Paris 2024 Olympic Games.  
The dashboard helps users analyze athlete participation, medal tallies, event schedules, and nation-wise performance with dynamic filtering and visual storytelling.

Throughout this project, I’ve had the opportunity to:

- Work with large, multi-table Olympic datasets.
- Design interactive visual dashboards using DAX measures and calculated columns.
- Gain insights on sports performance, country achievements, and scheduling patterns.

##  Steps Followed:

### 1. Data Collection:
- Sourced Olympic data from multiple CSV files: athletes, events, medalists, teams, venues, schedules, etc.
- Imported all files into Power BI and connected them through relationship modeling.

### 2. Data Cleaning & Modeling:
- Used Power Query to handle missing values, standardize naming, and transform data.
- Built a star schema model with `fact_medals`, `fact_athletes`, and related dimension tables.
- Created new calculated columns such as “Total Medals” and time-based fields for date intelligence.

### 3. DAX Measures:
- Created custom measures like:
  - `Total Medals`
  - `Gold/Silver/Bronze Count`
  - `Top Countries by Medals`
  - `Athletes per Country`
  - `Events by Venue` etc.

### 4. Visualizations:
- Designed the report using:
  - KPI Cards (Total Medals, Events, Athletes)
  - Stacked Column Charts
  - Line Charts for Time Trends
  - Donut Charts for Gender and Medal Distribution
  - Map visuals for country participation
  - Table and Matrix visuals
  - Dynamic slicers for filtering by year, event type, gender, and more

## Key Questions Answered:

-  Which countries are leading in medal tally?
-  How is athlete participation distributed by gender and nation?
-  Which venues host the most events?
-  What does the day-wise event schedule look like?
-  How are medals distributed across events and countries?
-  Which sports have the highest number of participants?

## Learned About:

1. Power BI Data Modeling
2. DAX for Calculations & KPIs
3. Using Slicers for Dynamic Filtering
4. Creating Interactive Reports
5. Building Date & Category-based Visual Analysis

## Key Insights Summary:

1. Top Performing Countries: Countries like USA, China, and host France are consistently on top of the medal tally.
2. Gender Participation: Male athletes dominate in total participation, but female representation is steadily increasing.
3. Sport-wise Dominance: Athletics and swimming are among the highest participated sports.
4. Event Distribution: Events are scheduled across multiple venues with some hosting significantly more games.
5. Medal Concentration: A few sports account for a majority of medal-winning opportunities, showing intense competitiveness in those domains.
6. Date-Wise Spread: The highest number of events are clustered around weekends for audience engagement.


## Dashboard Preview:

> [🔗 Click here to view the Dashboard](https://yourdashboardlink.com)

![Olympics Power BI Dashboard Preview](https://github.com/YourUsername/Paris2024-Olympics-PowerBI-Dashboard/assets/YourImageID/dashboard-preview.png)

---

## 📁 Dataset Sources:

- `athletes.csv`
- `coaches.csv`
- `events.csv`
- `medals.csv`
- `medals_total.csv`
- `medalists.csv`
- `nocs.csv`
- `schedule.csv`
- `teams.csv`
- `venues.csv`

---

## 🔧 Tools Used:

- Power BI Desktop
- Power Query
- DAX (Data Analysis Expressions)
- Relational Data Modeling
- Custom Visuals

##  Author

Kundan Kadam
MSc Data Science (2024–2026), NMIMS, Mumbai  
📫 [LinkedIn](https://www.linkedin.com/in/kundan-kadam) | [GitHub](https://github.com/kundankadam)



