# 🚗 NCR Ride Analytics Dashboard

## 📌 Project Overview

NCR Ride Analytics is an interactive Power BI analytics project built to analyze ride-booking performance, operational efficiency, revenue, and customer experience.

The project analyzes 73K+ ride booking records and converts raw ride-booking data into meaningful business insights using Python, Excel, and Power BI.

---

## 🎯 Business Objectives

The main objectives of this project are:

- Analyze overall ride-booking performance
- Identify booking and revenue trends
- Analyze vehicle-type demand
- Understand cancellation patterns
- Identify peak cancellation hours
- Analyze high-cancellation locations
- Evaluate revenue performance
- Understand customer and driver ratings
- Analyze customer waiting time (CTAT)
- Identify operational improvement opportunities

---

## 📊 Dataset

- Records: 73K+ ride bookings
- Attributes: 35+ columns
- Domain: Ride-hailing / Mobility Analytics
- Dataset Type: Simulated ride-booking dataset inspired by real-world ride-hailing platforms

### Key Data Fields

- Booking ID
- Date
- Vehicle Type
- Booking Status
- Booking Value
- Ride Distance
- Payment Method
- Pickup Location
- Customer Rating
- Driver Rating
- CTAT
- Cancellation Reasons
- Hour
- Weekday
- Month
- Year

---

## 🛠️ Tools & Technologies

- Python
- Pandas
- Power BI
- DAX
- Microsoft Excel
- Data Visualization
- Exploratory Data Analysis

---

## 🔄 Project Workflow

Raw Dataset
      ↓
Data Cleaning
      ↓
Data Transformation
      ↓
Feature Engineering
      ↓
KPI Development
      ↓
Power BI Data Modeling
      ↓
Interactive Dashboards
      ↓
Data Validation
      ↓
Business Insights

---

## 🧹 Data Preparation

Python and Pandas were used for:

- Data type correction
- Missing-value analysis
- Duplicate detection
- Data cleaning
- Date transformation
- Feature engineering
- KPI preparation

Additional analytical features were created such as:

- Month
- Month Name
- Year
- Weekday
- Peak Hour
- Weekend Flag
- Revenue per KM

---

# 📈 Power BI Dashboards

The project contains three interactive dashboards.

## 1️⃣ Executive Overview

Provides a high-level view of business performance.

### KPIs

- Total Bookings
- Total Revenue
- Completion Rate
- Average Booking Value
- Average Ride Distance

### Visualizations

- Bookings Trend Over Time
- Revenue Trend Over Time
- Bookings by Vehicle Type
- Bookings by Weekday
- Booking Status Distribution

---

## 2️⃣ Operations Overview

Focuses on operational problems and ride cancellations.

### KPIs

- Driver Cancellation Rate
- Customer Cancellation Rate
- Incomplete Ride Rate
- No Driver Rate

### Visualizations

- Booking Status Distribution
- Customer Cancellation Reasons
- Cancelled Bookings by Hour
- Cancelled Bookings by Pickup Location

---

## 3️⃣ Revenue & Customer Experience

Analyzes revenue efficiency and customer satisfaction.

### KPIs

- Revenue per KM
- Peak Hour Share
- Average Driver Rating
- Average Customer Rating
- Average CTAT

### Visualizations

- Revenue by Vehicle Type
- Bookings by Payment Method
- Customer Rating Distribution
- Peak Hour Demand Analysis

---

# 📌 Key KPIs

| KPI | Value |
|---|---:|
| Total Bookings | 73.91K |
| Total Revenue | ₹37.56M |
| Completion Rate | 61.91% |
| Average Booking Value | ₹508.19 |
| Average Ride Distance | 24.69 km |
| Driver Cancellation Rate | 18% |
| Customer Cancellation Rate | 7% |
| Incomplete Rate | 6% |
| No Driver Rate | 7.10% |
| Revenue per KM | ₹20.58 |
| Peak Hour Share | 29.54% |
| Average Driver Rating | 4.23 |
| Average Customer Rating | 4.40 |
| Average CTAT | 29.13 min |

---

# 🔍 Key Insights

### Booking Performance
The platform recorded more than 73K bookings, with a completion rate of approximately 62%.

### Vehicle Demand
Auto and Go Mini account for a significant portion of total bookings.

### Operational Issues
Driver cancellations are higher than customer cancellations, indicating potential driver availability or supply-side issues.

### Peak Hours
Ride demand and cancellation activity increase during evening peak hours.

### Customer Experience
Average customer and driver ratings are above 4, indicating generally positive service experience.

### Payment Behavior
Digital payment methods, particularly UPI, represent a significant share of bookings.

---

# 💡 Business Recommendations

Based on the analysis:

1. Increase driver availability during peak hours.
2. Introduce driver incentives to reduce driver cancellations.
3. Improve pickup-location and address validation.
4. Identify and optimize high-cancellation locations.
5. Reduce customer waiting time to improve experience.
6. Monitor vehicle-type demand for better fleet allocation.
7. Use peak-hour demand forecasting for driver allocation.

---

# ✅ Data Validation

Dashboard results were validated against the underlying dataset using Microsoft Excel and Power BI measures.

Validation included:

- Total booking count
- Vehicle-type booking counts
- Booking-status distribution
- Monthly booking trends
- Revenue calculations
- Cancellation rates
- Peak-hour booking counts
- Customer rating distribution

This ensured that dashboard visualizations and KPIs accurately represented the underlying data.

