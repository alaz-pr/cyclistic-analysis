# Cyclistic Bike-Share Analysis

## Executive Summary  
This project analyzes bike-share trip behavior to understand how annual members and casual riders use Cyclistic differently and how to convert more casual riders into members.

The analysis shows clear behavioral differences between the two groups. Members use the service primarily for commuting, with consistent weekday and rush-hour peaks. Casual riders take longer trips, ride mostly on weekends, and concentrate around leisure and tourist locations.

The main opportunity is to target casual riders when they are most engaged—on weekends, at high-traffic leisure destinations, and before the peak riding season.

---

## Business Problem  
Cyclistic aims to increase the number of annual members. To support this goal, the company needs to understand how casual riders differ from members in their usage patterns.

The key questions are:
- How do annual members and casual riders use Cyclistic bikes differently?  
- What behavioral patterns distinguish the two groups?  
- What actions could help convert more casual riders into annual members?  

---

## Note  

This project uses publicly available Divvy trip data from Q1 2019 and Q1 2020.  
The raw datasets are not included in this repository due to size and should be downloaded from the original source.

---

## Methodology  

**Data Source**  
- Divvy trip data provided by Motivate International Inc.  
- Q1 2019 and Q1 2020 datasets  
- 791,746 rides after cleaning  

**Data Cleaning**  
- Removed rides with zero or negative duration  
- Removed rides under 1 minute and over 24 hours  
- Removed test and maintenance stations  
- Standardized rider type labels  
- Aligned schemas between datasets using SQL  

**Exploratory Analysis**  
- Compared ride volume by rider type  
- Measured ride length (mean and median)  
- Analyzed patterns by day of week and hour of day  
- Identified top start stations by rider type  
- Compared year-over-year changes  

**Visualization**  
- Built charts in Python (pandas, matplotlib)  
- Created an interactive dashboard in Tableau Public  

👉 View the dashboard here:  
https://public.tableau.com/views/CyclisticCaseStudyMembervsCasualRiders/CyclisticDashboard

---

## Skills  

- SQL (SQLite) for data cleaning and aggregation  
- Python (pandas, matplotlib) for analysis and visualization  
- Tableau for dashboard development  
- Data cleaning and transformation  
- Exploratory data analysis  
- Behavioral segmentation  
- Translating analysis into business recommendations  

---

## Results and Business Recommendations  

**1. Members dominate overall ride volume**  
Members account for most rides, while casual riders represent a smaller but valuable segment.  
→ Focus on converting high-potential casual users rather than broad acquisition  

**2. Casual riders take significantly longer trips**  
Casual riders have much higher average and median ride lengths than members.  
→ Emphasize value of membership for frequent or extended use  

**3. Usage patterns differ by day and time**  
Members peak on weekdays and during commuting hours, while casual riders peak on weekends and midday.  
→ Target marketing campaigns during weekends and leisure-heavy hours  

**4. Casual riders cluster around leisure locations**  
High casual rider activity is concentrated near parks and tourist attractions.  
→ Use location-based promotions and signage at high-traffic stations  

**5. Casual ridership is growing faster than membership**  
Casual usage increased significantly year-over-year.  
→ Opportunity to convert a growing segment through seasonal campaigns  

---

## Next Steps  

- Extend analysis to full-year data for seasonal trends  
- Segment casual riders into tourists vs local users  
- Test targeted promotions at high-traffic stations  
- Evaluate the effectiveness of weekend and seasonal campaigns  
- Incorporate additional user-level or behavioral data  

---

## Results Preview  

### Rides by Day of Week  
![Rides by Day](charts/chart1_rides_by_day.png)

### Ride Length by Day  
![Ride Length](charts/chart2_ride_length_by_day.png)

### Rides by Hour  
![Rides by Hour](charts/chart3_rides_by_hour.png)

### Top Start Stations  
![Top Stations](charts/chart5_top_stations.png)
