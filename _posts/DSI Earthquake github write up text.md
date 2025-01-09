---
layout: post
title: Earthquake Tracking Dashboard Using Tableau
image: "/posts/DSI_Earthquake_Map_Viz.png"
tags: [Tableau, Data Viz]
---

This is a Tableau Dashboard that tracks global Earthquake activity across a 30-day period

<iframe seamless frameborder="0" src="https://public.tableau.com/shared/25WXXNKNN?:embed=yes&:display_count=yes&:showVizHome=no" width = '1090' height = '900'></iframe>


# 30-Day Earthquake Tracker Dashboard

## Overview
This Tableau dashboard provides an interactive and visual summary of earthquake data for a 30-day period (July 11, 2022 – August 10, 2022). Although based on a sample dataset designed for learning purposes, it showcases the types of insights that could be delivered to geologists, disaster management teams, or the general public.

The dashboard includes four primary visualizations, each offering unique perspectives on earthquake activity.

---

## Dashboard Features
1. **Top 10 Largest Earthquakes Table**
   - Displays the **location** and **magnitude** of the top 10 largest earthquakes in the dataset.
   - **Interactivity**: Users can sort the table alphabetically by location or numerically by magnitude (ascending or descending).

2. **Interactive Earthquake Map**
   - Provides a geographical representation of earthquake locations.
   - **Visual Encoding**:
     - **Color**: A gradient from green (lower magnitude) to red (higher magnitude).
     - **Size**: Dot size correlates with the earthquake's magnitude relative to others.
   - The map offers a quick, intuitive understanding of both the locations and relative magnitudes of the earthquakes.

3. **% Earthquake by Location (Broad)**
   - A table summarizing the **percentage** of total earthquakes for each broad region (e.g., North America, Asia, Europe).
   - **Interactivity**: Sort the regions alphabetically or by their percentage contribution.

4. **Location Analysis Bar Graphs**
   - Comprises three separate bar graphs showing earthquake data by country (or state for the U.S.):
     - **Frequency**: The number of earthquakes.
     - **Average Magnitude**: The mean magnitude of earthquakes in that region.
     - **Maximum Magnitude**: The highest recorded magnitude for that region.
   - **Interactivity**: Users can sort the graphs by any of the three metrics (ascending or descending).

---

## Using the Dashboard
1. **Filter by Date**:
   - Use the date filter at the top to narrow the data to a specific time range within the 30-day window. The default view includes all dates.

2. **Sort Options**:
   - For tabular and graphical views, sorting options are available to help focus on specific regions or metrics.

3. **Key Insights**:
   - **Magnitude Trends**: Identify the largest earthquakes and their geographical patterns.
   - **Regional Impact**: Analyze which broad regions and countries experienced the most activity or the strongest quakes.
   - **Visualization Aesthetics**: The black-and-white theme emphasizes the brightly colored map dots, drawing attention to the most significant earthquake events.

---

## Design Philosophy
The dashboard’s clean, minimalistic design ensures that critical data and insights are visually striking. Features like color-coded magnitude gradients and sortable tables make the dashboard intuitive and engaging for users.
