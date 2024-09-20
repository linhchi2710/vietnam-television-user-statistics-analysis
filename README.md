# Vietnam Television User Statistics Analysis

This project analyzes television user behavior in Vietnam from January 26 to January 29, 2023. The data consists of nearly 4 million rows and provides insights into user interactions across various platforms, devices, and content types.

## Project Overview
The goal of this project is to analyze television user statistics and gain insights into viewing behavior during a specific period. The project involves several key steps:

* Data cleaning and preprocessing
* Exploratory data analysis (EDA)
* Visualization of user activity trends
* Identification of top-watched content by platform, device, and ISP
* Hourly usage heatmaps to understand peak hours of viewing
* User behavior analysis across devices

## Technologies Used
* Python: for data manipulation and analysis using `pandas`
* Seaborn & Matplotlib: for data visualization
* Jupyter Notebook: for iterative coding and visualization

## Data Structure
Although the actual dataset is confidential and not shared, here is a general overview of the dataset's structure:

* device_id: Unique identifier for each device
* device_name: Name of the device (e.g., SmartTV, BoxOTT, Mobile)
* platform: Platform used for viewing (e.g., Android, iOS)
* itemname: Name of the content viewed (e.g., TV show or movie title)
* appid: Identifier for the application used
* receive_time: Timestamp of the user action (start, next, or previous event)
* event: Type of user action (e.g., StartChannel, NextMovie)

## Project Steps and Methodology
1. **Data Cleaning**:
   * Columns with missing values were identified and handled through imputation or removal.
   * Timestamps (`receive_time`) were converted to datetime objects for time-based analysis.
   * Dropped unnecessary columns to simplify the data.

2. **Exploratory Data Analysis (EDA)**:
   * User Behavior Analysis: Identified the most popular content across devices, platforms, and ISPs.
   * Content Viewership: Aggregated data to determine the top 10 most-watched content over the analysis period.
   * Created bar plots to visualize viewership trends.

3. **Visualizations**:
   * Heatmap of User Activity: Displayed user activity by hour to identify peak times.
   * Top Content by Device and ISP: Used bar charts to show popular content for each device and ISP.

4. **Key Insights**:
   * Top Content by Platform: BoxOTT accounted for 46% of total views, dominating device usage. Mobile and SmartTV were also significant.
   * Peak Viewing Times: Peak hours were identified between 19:00 and 21:00, with the highest user activity at 20:00 across all days.
   * Most Popular ISPs: FPT was the leading ISP, with the highest user engagement on VTV1 HD and VTV3 HD.
   * Device Usage: BoxOTT was the most popular device, followed by SmartTV and Mobile.
   * ISP Analysis: FPT had the highest user engagement, with VTV1 HD being the most-watched content.
