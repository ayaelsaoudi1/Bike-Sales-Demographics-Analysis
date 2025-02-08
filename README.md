# Bike Sales Analysis Project

## Overview

This project analyzes bike sales data using **Excel**. The dataset contains **13,350 records** with demographic data and bike purchase information. The analysis involves creating pivot tables, charts, and a dashboard that summarizes key insights into customer behavior and purchasing patterns. Excel was chosen as the primary tool due to its powerful data processing, analysis, and visualization features.

## Why Excel?

Excel is a powerful tool for data analysis because of its ability to:
- **Easily handle large datasets**: It provides quick access to data manipulation and summarization features.
- **Create pivot tables**: Pivot tables allow for dynamic summarization and filtering of data, which is critical for analyzing patterns and trends.
- **Visualization tools**: Excel's charting capabilities, including bar charts, line graphs, and pivot charts, make it easy to visualize complex data and uncover actionable insights.
- **Versatility**: From raw data cleaning to advanced analysis, Excel supports a wide range of tasks for both beginners and advanced analysts.

## Data Overview

The dataset contains the following columns: **Row ID**, **Marital Status**, **Gender**, **Income**, **Children**, **Education**, **Occupation**, **Home Owner**, **Cars**, **Commute Distance**, **Region**, **Age**, **Purchased Bike** (Yes/No)

The dataset includes **13,350 rows**, providing insights into customer demographics and their purchasing behavior.

## Steps Taken

### 1. **Data Cleaning and Transformation**
   - **Remove duplicates**: All duplicate entries were removed to ensure the integrity of the dataset.
   - **Categorical data transformation**: Unclear categorical data (e.g., "m" and "s" for marital status) were cleaned and standardized.
   - **Age range transformation**: The age column was converted into age ranges using **nested IF statements**.

### 2. **Pivot Tables and Analysis**
   Several pivot tables were created to summarize key insights:

   - **Gender-based Bike Purchase & Income**: A pivot table was created to show how gender correlates with bike purchases and average income. It reveals that **males** generally have a higher average income compared to **females**, and both genders show fairly similar purchase patterns.

   - **Purchase by Commute Distance**: A pivot table was created to examine the relationship between commute distance and bike purchases. It shows that customers with a **commute distance of 0-1 miles** have the highest number of bike purchases, while those with **commutes longer than 10 miles** have the fewest purchases.

   - **Purchase by Age Bracket**: Another pivot table focused on age brackets (Adolescent, Middle Age, and Old). The results highlight that the **middle-aged group** has the highest number of bike purchases, while the **adolescent** and **old** groups show significantly lower purchase rates.

### 3. **Charts and Graphs**
   - A **bar chart** was created from the gender-based pivot table to visually compare average income and bike purchases for each gender.
   - Two **line graphs** were created from the pivot tables above to visualize trends in bike purchases based on **commute distance** and **age brackets**.

### 4. **Dashboard**
   All the findings were summarized in a **separate dashboard sheet**. The dashboard includes **slicers** for filtering data by **marital status**, **region**, **education**, and **gender**, providing an interactive way to explore the data.

   - A **screenshot of the dashboard** is provided below for reference:

   ![Dashboard Screenshot](https://github.com/user-attachments/assets/4afd7adb-3ad8-42e5-b915-ed3ce6607478)


## Conclusion

This project showcases the power of **Excel** in analyzing customer data for insights into **bike sales trends**. By cleaning the data, creating pivot tables, and visualizing the results through graphs and dashboards, the project provides a comprehensive view of how demographics like age, commute distance, and marital status influence bike purchases.
