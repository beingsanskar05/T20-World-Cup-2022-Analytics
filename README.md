# ICC Men's T20 World Cup 2022 Analytics Dashboard

<p align="center">
  <img src="assets/t20_world_cup.jpg" width="450">
</p>

<p align="center">
  <b>End-to-End Data Analytics Project using Python, Power BI, DAX, Data Modeling, and Interactive Visualizations</b>
</p>

---

# Project Overview

This project is an end-to-end sports analytics solution developed using Python and Power BI to analyze player performances from the ICC Men's T20 World Cup 2022.

The primary objective of the project is to identify the strongest possible Playing XI by evaluating players using role-specific performance metrics and advanced cricket analytics.

Instead of selecting players based on reputation or popularity, this project uses a completely data-driven approach to identify the best performers across different roles and build the strongest team based on tournament statistics.

The solution demonstrates the complete analytics lifecycle:

- Data Collection
- Data Cleaning
- Data Transformation
- Exploratory Data Analysis (EDA)
- Data Modeling
- DAX Calculations
- Dashboard Development
- Data Visualization
- Business Intelligence Reporting

---

# Business Problem

Selecting a cricket team often involves subjective judgment and personal bias.

This project addresses that challenge by using analytics to:

- Evaluate player performance objectively
- Compare players across different roles
- Identify top-performing players using statistical metrics
- Build the strongest World XI using data-driven decision making
- Provide interactive insights for performance analysis

---

# End-to-End Analytics Workflow

The project combines Python and Power BI to create a complete analytics pipeline.

```text
Raw JSON Files
      │
      ▼
Python Data Extraction
      │
      ▼
Data Cleaning & Transformation
      │
      ▼
Exploratory Data Analysis (EDA)
      │
      ▼
CSV Dataset Generation
      │
      ▼
Power BI Data Modeling
      │
      ▼
DAX Measures
      │
      ▼
Interactive Dashboard
      │
      ▼
Final World XI Selection
```

---

# Python Data Engineering & EDA

Before importing data into Power BI, Python was used extensively to prepare the dataset.

## Data Extraction

The original cricket data was available in JSON format.

Python was used to:

- Load JSON files
- Parse nested structures
- Extract player statistics
- Convert JSON into tabular datasets

## Data Cleaning

Data cleaning tasks included:

- Handling missing values
- Removing duplicates
- Standardizing column names
- Data type corrections
- Data validation
- Data consistency checks

## Feature Engineering

Additional analytical features were created using Python.

Examples:

- Boundary Percentage
- Batting Efficiency Metrics
- Bowling Efficiency Metrics
- Match Performance Indicators
- Role-Based Metrics

## Exploratory Data Analysis (EDA)

EDA was performed to understand player performance patterns.

### Analysis Performed

- Distribution Analysis
- Player Performance Trends
- Run Scoring Patterns
- Bowling Performance Analysis
- Correlation Analysis
- Outlier Detection
- Team Performance Comparison

## Export Process

The cleaned datasets were exported as CSV files and used as the data source for Power BI.

---

# Dataset Information

The project uses ICC Men's T20 World Cup 2022 player-level and match-level data.

## Dataset Components

### Player Information

- Player Name
- Team
- Batting Style
- Bowling Style
- Role

### Batting Statistics

- Runs
- Balls Faced
- Strike Rate
- Batting Average
- Boundary Percentage

### Bowling Statistics

- Wickets
- Economy Rate
- Bowling Strike Rate
- Dot Ball Percentage

### Match Information

- Match ID
- Opponent
- Tournament Stage
- Match Performance

---

# Data Modeling

A Star Schema data model was implemented in Power BI to optimize performance and maintain scalability.

## Fact Tables

### fact_batting_summary

Stores batting-related statistics.

### fact_bowling_summary

Stores bowling-related statistics.

## Dimension Tables

### dim_players

Player master information.

### match_summary

Match-level information.

## Benefits

- Faster dashboard performance
- Better filter propagation
- Efficient DAX calculations
- Improved scalability

---

# Power BI Features Implemented

- Star Schema Design
- Power Query Transformations
- DAX Measures
- KPI Cards
- Conditional Formatting
- Interactive Filters
- Dynamic Tooltips
- Page Navigation
- Cross Filtering
- Drill Through Functionality

---

# DAX Measures Used

## Batting Metrics

- Total Runs
- Total Innings
- Batting Average
- Strike Rate
- Boundary Percentage
- Average Balls Faced

## Bowling Metrics

- Total Wickets
- Economy Rate
- Bowling Strike Rate
- Dot Ball Percentage

---

# Dashboard Pages

## Power Hitters / Openers

Evaluates aggressive opening batters based on:

- Strike Rate
- Boundary Percentage
- Batting Average
- Average Balls Faced

## Anchors / Middle Order

Evaluates consistency-focused batters based on:

- Batting Average
- Strike Rate
- Total Runs
- Match Impact

## Finishers

Identifies players capable of accelerating scoring during death overs.

## All Rounders

Evaluates players contributing with both bat and ball.

## Specialist Fast Bowlers

Identifies the most effective bowlers using:

- Economy Rate
- Bowling Strike Rate
- Dot Ball Percentage
- Wickets Taken

---

# Final Playing XI

The Final Playing XI was selected using role-specific performance criteria.

Selection was based on:

- Batting Average
- Strike Rate
- Boundary Percentage
- Economy Rate
- Bowling Strike Rate
- Dot Ball Percentage
- Match Impact
- Consistency

The final team represents the strongest performing XI from the ICC Men's T20 World Cup 2022 using a data-driven selection methodology.

---

# Visualizations Used

| Visual Type | Purpose |
|------------|----------|
| KPI Cards | Performance Indicators |
| Table Visuals | Player Comparison |
| Scatter Charts | Player Clustering |
| Line Charts | Trend Analysis |
| Tooltips | Detailed Insights |
| Navigation Buttons | User Experience |
| Slicers | Dynamic Filtering |
| Conditional Formatting | Performance Highlighting |

---

# Dashboard Screenshots

## Power Hitters

![Power Hitters](Screenshots/Power_Hitters.png)

## Anchors / Middle Order

![Anchors](Screenshots/Anchors.png)

## Finishers

![Finishers](Screenshots/Finishers.png)

## All Rounders

![All Rounders](Screenshots/All_Rounders.png)

## Specialist Fast Bowlers

![Specialist Fast Bowlers](Screenshots/Specialist_Fast_Bowlers.png)

## Final Playing XI

![Final XI](Screenshots/Final_11.png)

---

# Skills Demonstrated

## Python

- Data Cleaning
- Data Transformation
- JSON Processing
- Exploratory Data Analysis
- Feature Engineering
- Data Validation

## Power BI

- Data Modeling
- Power Query
- DAX
- Dashboard Development
- Interactive Reporting

## Analytics

- Sports Analytics
- KPI Design
- Data Storytelling
- Data Visualization
- Business Intelligence

---

# Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Power BI
- Power Query
- DAX
- Excel
- GitHub

---

# Repository Structure

T20-WorldCup
│
├── Dashboard
│   └── T20W_2022.pbix
│
├── Python
│   ├── t20_data_preprocessing.ipynb
│   
│
├── Dataset
│   ├── dim_players.csv
│   ├── fact_batting_summary.csv
│   ├── fact_bowling_summary.csv
│   └── dim_match_summary.csv
│
├── Screenshots
│   ├── Power_Hitters.png
│   ├── Anchors.png
│   ├── Finishers.png
│   ├── All_Rounders.png
│   ├── Specialist_Fast_Bowlers.png
│   └── Final_11.png
│
├── assets
│   └── t20_world_cup_2022_logo.png
│
└── README.md

# Why This Project Matters

This project demonstrates a complete Data Analytics workflow from raw JSON data to actionable business insights.

It showcases:

- Python Data Engineering
- Data Cleaning & EDA
- JSON Processing
- CSV Dataset Creation
- Data Modeling
- DAX Calculations
- Interactive Dashboard Development
- Sports Analytics
- Business Intelligence Reporting
- Data-Driven Decision Making

---

# Author

## Sanskar Pandey

M.Sc. Data Science

GitHub: https://github.com/beingsanskar05

LinkedIn: https://www.linkedin.com/in/sanskar-pandey-631349212
