# Hotel Booking Analysis – Excel & Python Dashboard
Capstone Project

## Overview

This project explores a comprehensive dataset of hotel bookings to uncover actionable insights that can help reduce cancellations, improve guest experiences, and optimize hotel operations. The analysis was performed using Python for in-depth EDA and Excel for developing an interactive dashboard.

🔗 **Dataset Used**: hotel_bookings.csv

📷 **Dashboard Snapshot**:  
*Add your dashboard image here once uploaded*  
Example:  

![image](https://github.com/user-attachments/assets/85777409-2012-426d-bd1b-5f49685d3c55)


## Project Objective

The primary goal is to analyze hotel booking behavior and identify key patterns to enhance strategic decision-making in the hospitality sector. The project focuses on:

- 📊 Booking trends, lead times, and cancellation patterns.
- 🧳 Guest demographics, including country of origin and repeat guests.
- 🛏️ Room allocation, booking changes, and meal preferences.
- 📆 Seasonal and monthly booking behaviors.
- 🔍 Identifying high-risk cancellation profiles and profitable customer segments.
- 📈 Developing a dashboard to visualize core business metrics.

## Dataset Description

The dataset contains the following information:

| Column Name                  | Description                                                                 |
|-----------------------------|-----------------------------------------------------------------------------|
| `hotel`                     | Type of hotel – City Hotel or Resort Hotel                                  |
| `is_canceled`               | Booking status – 1 if canceled, 0 otherwise                                 |
| `lead_time`                 | Days between booking and check-in                                           |
| `arrival_date_*`            | Date-related columns: year, month, week number, day of month                |
| `stays_in_weekend_nights`   | Number of weekend nights stayed                                             |
| `stays_in_week_nights`      | Number of weekday nights stayed                                             |
| `adults`, `children`, `babies` | Number of guests categorized by age                                       |
| `meal`                      | Type of meal plan chosen                                                    |
| `country`                   | Guest's country of origin                                                   |
| `market_segment`            | Segment source of booking – online, offline, corporate, etc.               |
| `distribution_channel`      | Channel through which booking was made                                     |
| `is_repeated_guest`         | Whether the guest is a repeat customer                                      |
| `previous_*`                | Booking history – cancellations and non-cancellations                       |
| `reserved_room_type`, `assigned_room_type` | Room reserved vs room allocated                             |
| `booking_changes`           | Number of booking modifications                                             |
| `deposit_type`              | Type of deposit paid                                                        |
| `agent`, `company`          | Booking source details                                                      |
| `days_in_waiting_list`      | Days booking stayed in the waitlist                                         |
| `customer_type`             | Guest type: transient, group, contract, etc.                                |
| `adr`                       | Average Daily Rate (cost per night)                                         |
| `required_car_parking_spaces` | Parking spaces requested                                                 |
| `total_of_special_requests` | Special requests made by the guest                                          |
| `reservation_status`, `reservation_status_date` | Final status and date of reservation              |

## Key Analysis Tasks

Here are the core insights and tasks accomplished:

- ❌ **Cancellation Analysis**: Identify patterns in booking cancellations.
- ⏱️ **Lead Time**: Analyze how early bookings are made and how that impacts cancellation rates.
- 🗓️ **Seasonal Trends**: Evaluate booking patterns across months and seasons.
- 🌍 **Country-Wise Guests**: Visualize where guests are coming from.
- 🍽️ **Meal & Market Segment Analysis**: Identify top meal plans and booking sources.
- 🔄 **Room Allocation Mismatches**: Compare reserved vs assigned room types.
- 💹 **ADR Trends**: Analyze revenue per room across customer types and stay durations.
- 🎯 **Repeat Guest Behavior**: Understand loyalty trends and marketing impact.
- 📊 **Dashboard Development**: Build a clear, interactive Excel dashboard for all KPIs.

## Tools & Libraries Used

- **Python Libraries**:  
  `pandas`, `numpy`, `matplotlib`, `seaborn` for data cleaning and EDA.

## Conclusion

This project delivers meaningful insights from hotel booking data using Python and Excel. Key trends in guest behavior, cancellations, room assignments, and revenue optimization were uncovered, enabling hotel managers to take data-driven actions to improve service and profitability.

📌 The interactive dashboard serves as a powerful tool for quick decision-making by visualizing essential metrics.
