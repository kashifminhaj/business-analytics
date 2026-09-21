# Hotel Revenue, Booking and Cancellation Analytics

## Task 2 – Data Wrangling and Cleaning

This project focuses on cleaning and preparing hotel booking data for business analytics. The dataset contains information about bookings, cancellations, guest details, stay duration, room pricing, market segments and booking channels.

### Objectives

* Identify and handle missing values.
* Remove duplicate records.
* Correct data types and inconsistent text values.
* Detect invalid values and potential outliers.
* Create useful features for further analysis.
* Validate and save the cleaned dataset.

### Tools Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

### Dataset

**Input:** `hotel_bookings.csv`
**Output:** `cleaned_hotel_bookings.csv`

The cleaned dataset will be used for **Week 3 visualization, Week 4 statistical analysis and prediction, Week 5 dashboard development, and Week 6 final evaluation**.

### Project Workflow

`Raw Data → Cleaning → Transformation → Feature Engineering → Validation → Clean Dataset`

### Key Features Created

* Total Nights
* Total Guests
* Cancellation Flag
* Stay Duration Category
* Lead Time Category
* Estimated Room Value

## Task 3 – Data Visualization and Reporting

This project focuses on analyzing hotel booking data through data visualization and reporting. The cleaned dataset prepared during Task 2 is used to create meaningful visualizations that help identify patterns in booking demand, cancellations, pricing, market segments, stay duration, lead time, and realized room value.

## Objectives

- Analyze monthly booking demand.
- Understand booking cancellation patterns.
- Compare cancellation rates across market segments.
- Analyze Average Daily Rate (ADR) by month.
- Compare booking volume across market segments.
- Analyze bookings based on stay duration.
- Examine cancellation rates by lead-time category.
- Compare realized room value across market segments.
- Calculate important business KPIs.
- Generate business insights from the visualizations.

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## Dataset

Input Dataset:

`cleaned_hotel_bookings.csv`

The dataset was prepared during Task 2 through data cleaning, transformation, duplicate removal, missing-value handling, and feature engineering.

## Project Workflow

Task 2 Cleaned Dataset  
↓  
Data Validation  
↓  
KPI Calculation  
↓  
Data Aggregation  
↓  
Data Visualization  
↓  
Business Interpretation  
↓  
Actionable Business Insights

## Visualizations Created

The notebook generates the following visualizations:

1. Monthly Booking Demand
2. Booking Cancellation Distribution
3. Cancellation Rate by Market Segment
4. Average ADR by Arrival Month
5. Bookings by Market Segment
6. Bookings by Stay Duration
7. Cancellation Rate by Lead Time Category
8. Realized Room Value by Market Segment

## Key Features Used

- `arrival_date_month`
- `arrival_date`
- `adr`
- `market_segment`
- `cancellation_flag`
- `total_nights`
- `stay_duration_category`
- `lead_time_category`
- `estimated_room_value`
- `realized_room_value`

## Key KPIs

The notebook calculates:

- Total Bookings
- Completed Bookings
- Cancelled Bookings
- Cancellation Rate
- Average ADR
- Average Length of Stay
- Total Realized Room Value
- Average Revenue per Completed Booking

## Main Libraries

### Pandas
Used for:
- Loading the dataset
- Data grouping
- Aggregation
- KPI calculation
- Data analysis

### NumPy
Used for:
- Numerical calculations
- Conditional operations
- Feature calculations

### Matplotlib
Used for:
- Creating bar charts
- Creating line charts
- Formatting and displaying visualizations



This task provides the clean and structured dataset required for the remaining stages of the Business Analytics project.
