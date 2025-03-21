# Space Launch Analytics

## Overview

This project analyzes space mission launches using Python. The dataset contains information about organizations, locations, dates, costs, and mission statuses. The analysis aims to answer key questions related to launch frequencies, costs, and mission safety over time.

## Research Questions

- Which organization launched the most space missions in a given year?

- How many launches were conducted per year?

- How has the cost of a space mission varied over time?

- What months are the most popular for launches?

- Have space missions become safer, or have the chances of failure remained unchanged?

## Dataset

The dataset used for this analysis includes the following columns:

**Organisation:** The organization responsible for the launch.

**Location:** The site where the launch took place.

**Date:** The launch date and time.

**Detail:** Information about the mission.

**Rocket_Status:** Indicates if the rocket is active or retired.

**Price:** Cost of the mission (in million USD).

**Mission_Status:** The outcome of the mission (Success/Failure).

## Tools Used

- Python

- Pandas

- NumPy

- Matplotlib

- Seaborn

## Data Processing

- Extracted country and state information from the location.

- Converted date format and extracted year, month, day, weekday, and hour.

- Handled missing values and transformed data types.

- Performed exploratory data analysis (EDA) to visualize trends.

## Key Findings

- The organization with the most launches in 2018 was CASC (37 launches), followed by SpaceX.

- The peak years for launches were 2018, 1971, 1975, 1976, and 1977.

- The cost of space missions peaked around 2010 before declining and rising again in 2020.

- December had the highest number of launches.

- Failure rates have generally declined, but recent years show a slight increase.

## Visualizations

The project includes various plots:

- Bar charts for organization launches.

- Line charts for yearly launch trends and cost variations.

- Failure rate trend analysis.
