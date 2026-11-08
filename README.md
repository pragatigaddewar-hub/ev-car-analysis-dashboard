# EV Car Analysis Dashboard

A Power BI dashboard that analyzes electric vehicle (EV) car data, focusing on towing capacity, seating capacity, and drive configuration trends.

## Overview

This project uses Power BI to visualize how towing capacity and number of seats vary across different drive configurations of EV cars.

## Dataset

- **Table:** `cars_data_RAW`
- **Source:** EV cars dataset from Kaggle
- **Total records:** 353 cars
- **Fields used:** Towing_capacity_in_kg, Number_of_seats, Drive_Configuration

## Dashboard Contents

The dashboard has a single page (Page 1) with 6 visuals:

| Visual | Description |
|---|---|
| Average Towing Capacity | Card showing the average towing capacity in kg |
| Average Number of Seats | Card showing the average number of seats |
| Average Towing Capacity by Drive Configuration | Bar chart comparing average towing capacity across drive types |
| Average Towing Capacity by Number of Seats | Bar chart showing average towing capacity for each seat count |
| Drive Configuration Filter | Slicer to filter the dashboard by drive configuration |
| Drive Configuration Distribution | Donut chart showing the share of each drive configuration |

## Key Insights

- The dataset has 353 cars: 161 All Wheel Drive (45.61%), 104 Front Wheel Drive (29.46%) and 88 Rear Wheel Drive (24.93%).
- The average towing capacity is about 1.32K kg and the average number of seats is about 5.10.

## Author

Pragati Gaddewar

## How to View

1. Download `EV Car Analysis.pbix` from this repository.
2. Open it using Power BI Desktop.
3. Use the Drive Configuration Filter to explore the data by drive type.
