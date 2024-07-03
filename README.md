# Hotel_Booking_Analysis
Capstone project
# Hotel Booking Analysis EDA

This project involves exploratory data analysis (EDA) of hotel booking data to uncover insights that can help reduce customer churn, improve guest satisfaction, and optimize hotel operations.

## Project Description

The analysis aims to:
- Understand booking patterns and lead times
- Identify trends in cancellations
- Explore guest demographics and preferences
- Analyze seasonal trends and peak booking periods
- Investigate meal preferences and market segments
- Examine room allocation and booking changes

## Data Overview

The dataset includes the following columns:
- `hotel`: Name of the hotel (Resort Hotel or City Hotel)
- `is_canceled`: Booking cancellation status (1 if canceled, 0 otherwise)
- `lead_time`: Number of days between booking and arrival
- `arrival_date_year`: Year of arrival date
- `arrival_date_month`: Month of arrival date
- `arrival_date_week_number`: Week number of arrival date
- `arrival_date_day_of_month`: Day of arrival date
- `stays_in_weekend_nights`: Number of weekend nights (Saturday or Sunday) the guest stayed or booked to stay at the hotel
- `stays_in_week_nights`: Number of week nights (Monday to Friday) the guest stayed or booked to stay at the hotel
- `adults`: Number of adults
- `children`: Number of children
- `babies`: Number of babies
- `meal`: Type of meal booked
- `country`: Country of origin
- `market_segment`: Market segment designation
- `distribution_channel`: Booking distribution channel
- `is_repeated_guest`: Flag indicating if the guest is a repeated guest (1 if repeated guest, 0 otherwise)
- `previous_cancellations`: Number of previous bookings that were canceled by the customer
- `previous_bookings_not_canceled`: Number of previous bookings not canceled by the customer
- `reserved_room_type`: Code of room type reserved
- `assigned_room_type`: Code of room type assigned
- `booking_changes`: Number of changes made to the booking
- `deposit_type`: Type of deposit made by the customer
- `agent`: ID of the travel agency that made the booking

## Installation

To run the analysis, you need to have Python and the following libraries installed:
- pandas
- numpy
- matplotlib
- seaborn

You can install these libraries using pip:
```bash
pip install pandas numpy matplotlib seaborn
