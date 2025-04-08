## Country GDP Bump Chart Power BI Challenge (Workout Wednesday W45/2024)
![image](https://github.com/user-attachments/assets/fcb2c2d3-f196-4daf-8f33-7662726e0133)

This project was created as part of the [Workout Wednesday Power BI Challenge – Week 45/2024](https://workout-wednesday.com/pbi-2024-w45/). The task was to recreate a **bump chart** showing the **GDP ranking of countries over time**. The chart visualizes how countries move up and down in the ranking from **2000 to 2022** based on GDP data.

## Key Features
**Bump Chart Visualization**: Countries are ranked per year, and their rank trajectory is plotted across time.
**Interactive Tooltip**: Hovering over each country reveals detailed information about its GDP and rank per year.
**Dynamic Labeling**: Labels are displayed only at the beginning and end of the line, per challenge instructions.
**Data Normalization**: Used Power BI measures to calculate GDP rank for each country by year using `RANKX`.
**Custom Formatting**: Applied theme styling and color logic to maintain clarity and alignment with the original challenge.

## What I Learned
How to use **RANKX with ALLEXCEPT** for year-based ranking.
How to use **line charts with disconnected tooltips** and dynamic labeling.
Techniques for **highlighting user interaction** while keeping the chart minimal.

## Tools Used
Power BI (Measures, Line Chart, Tooltip Page)
DAX (RANKX, CALCULATE, ALLEXCEPT)
Power Query (Data reshaping and cleaning)
