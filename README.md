**Road Accident Dashboard in Excel**
Excel dashboard project: road accident data analysis. KPIs, filters (severity, vehicle, year 2021-22), interactive via slicers. Kaggle demo dataset.

You can access the project files, including the data used for analysis, through the following Google Drive link:

[[Access Project Files on Google Drive](https://shorturl.at/LRn0F)]

Please note that this link will take you to a Google Sheet containing the dataset used for the Excel-based Road Accident Dashboard. You can download the dataset and use it to replicate the steps described in the project.

**Overview**

This project involves the design and development of a dynamic and interactive dashboard using Excel to analyze road accidents data. The dashboard is designed to display key performance indicators (KPIs) and various insights from the data, allowing the user to filter the information based on accident severity, vehicle types, and year (2021-2022). This is achieved using slicers and filters for interactivity. The data used in the project is taken from a Kaggle dataset, which is a demo dataset for practice purposes.

**Key Features**

Dynamic Filters: The dashboard allows users to interact with the data through two key filters:
Area Location Filter (Urban/Rural): Toggle between urban and rural accident data.
Accident Date Filter (Timeline): View the data for specific years (2021 and 2022) or quarters.

**Primary KPIs:**
The dashboard highlights the following key metrics:

1.Total Casualties from road accidents.
2.Casualties by Severity: Fatal, Serious, and Slight accidents.
3.Vehicle Type Casualties: Maximum casualties by specific vehicle types.
4.Secondary KPIs: Visualizing the data based on:
5.Casualties by Vehicle Type (cars, buses, motorcycles, etc.).
6.Casualties by Road Surface (dry, damp, snow, etc.).
7.Monthly Trend Comparison: A visual representation of casualties across months for 2021 and 2022.

**Charts:**

Bar Charts: For visualizing casualty distribution by road type and other parameters.
Donut Charts: To show casualties by accident severity, road surface, etc.
Tree Map: Visualize casualties by road surface conditions.

**Steps Taken**

**Requirement Gathering:**
              The client requested a road accident dashboard with primary KPIs, secondary KPIs, and charts visualizing the trend, vehicle types, and accident severity.

**Data Cleaning:**
              The initial data cleaning involved removing duplicates, handling missing values, and correcting any typos in the dataset (e.g., changing "fetal" to "fatal").

**Data Processing**:
              Custom columns like "Month" and "Year" were added for trend analysis and pivoting.

**Data Analysis:**
              Pivot tables were used to aggregate casualty data and compute percentages, which were then visualized in different charts.

**Slicers and Timelines:** 
              The use of slicers allows for easy navigation between different datasets, and the timeline slicer provides a clear view of accident trends over time.

**Data Analysis and Visualization:**

Created pivot tables to analyze the total casualties, casualties by severity, and casualties by vehicle type.
Used charts (bar, donut, and tree maps) to visualize this data.
Combined the KPIs and charts into a visually appealing and user-friendly dashboard.
Integrated dynamic elements like slicers and timeline filters to allow users to interact with the data.

**Final Touches:** 

Styled the dashboard with colors and added hyperlinks for easy navigation between different sheets.

**Technologies Used**

Excel: Used for data cleaning, processing, analysis, and dashboard creation.
Pivot Tables: For data aggregation and calculation of KPIs.
Slicers & Timelines: For interactivity and filtering.
Charts: Bar charts, donut charts, and tree maps for visualizing data.
Formulas: Used for calculating percentages and extracting custom data (e.g., month and year).

**Future Enhancements**

Integration with Real-time Data: Use real-world data from government databases to make the dashboard more accurate and practical.
Interactive Web Dashboard: Develop the dashboard as a web application using a tool like Power BI for better interactivity and real-time updates.
Advanced Analytics: Implement more advanced statistical methods to predict trends in road accidents and their casualties.

**Conclusion**

The Road Accident Dashboard is a powerful tool for visualizing and analyzing accident data. With dynamic filters, multiple KPIs, and various charts, users can gain valuable insights into road accidents and the impact of different factors like accident severity, vehicle types, and road conditions.

