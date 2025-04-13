# Hotel Booking Analysis

This project focuses on analyzing a hotel booking dataset to uncover insights about customer booking behaviors, predict booking cancellations, and examine the factors influencing the Average Daily Rate (ADR). The analysis includes data visualization, correlation analysis, and machine learning to explore booking trends, cancellations, and customer demographics.

## Project Overview

The goal of this project is to explore and analyze a hotel booking dataset in order to:
- Understand booking trends across different hotel types, months, and market segments.
- Predict booking cancellations by analyzing key factors like lead time, booking source, and previous booking history.
- Identify the key drivers of Average Daily Rate (ADR) across hotel types and booking characteristics.

## Dataset

The dataset includes information about hotel bookings, with attributes like:

- `hotel`: Type of hotel (City Hotel or Resort Hotel)
- `is_canceled`: Whether the booking was canceled (1 = canceled, 0 = not canceled)
- `lead_time`: Number of days between booking and arrival
- `adr`: Average Daily Rate (ADR)
- `arrival_date_month`: Arrival month
- `market_segment`: Market segment through which the booking was made
- `distribution_channel`: Channel through which the booking was made
- `previous_bookings_not_canceled`: Number of previous bookings not canceled
- `total_people`: Total number of people in the booking (adults, children, babies)
- `same_room_alloted_or_not`: Whether the customer was assigned the same room they reserved

## Key Insights and Visualizations

### 1. **Average Daily Rate (ADR) Analysis**
   - Trends of ADR across different hotel types and market segments.

### 2. **Booking Cancellations**
   - Factors influencing booking cancellations, such as distribution channel and market segment.

### 3. **Booking Behavior**
   - Analysis of repeated guests and their booking cancellations.
   
### 4. **Optimal Stay Length**
   - Identifying the ideal length of stay for both hotel types.

### 5. **Correlation Analysis**
   - Exploring relationships between key features such as lead time, total stay, and ADR.

## Project Workflow

### 1. **Data Preprocessing**
   - Data cleaning and handling of missing values.
   - Feature engineering, such as the creation of `same_room_alloted_or_not`.

### 2. **Exploratory Data Analysis (EDA)**
   - Visualizations using libraries like `Matplotlib` and `Seaborn` to uncover trends and patterns in the data.
   - Summary statistics and feature correlations.

### 3. **Machine Learning Models (Optional)**
   - Development of predictive models (e.g., logistic regression, decision trees) for predicting cancellations based on features like lead time, booking source, and previous bookings.

## Technologies Used

- **Python**
- **Pandas** for data manipulation
- **NumPy** for numerical operations
- **Matplotlib/Seaborn** for data visualization
- **Scikit-learn** for machine learning (optional)
