# Uber Ride Analytics – Hidden Patterns

## 📌 Project Overview
This project analyzes Uber ride data to uncover patterns in bookings, cancellations, demand trends, and revenue.

The workflow was divided into two main stages:
- **Data cleaning and preprocessing using Python**
- **Data analysis and visualization using Power BI**

This approach combines programming-based data preparation with interactive business dashboards.

---

## 🔄 Workflow
1. Cleaned and prepared the raw dataset using Python (Pandas & NumPy)
2. Exported the cleaned dataset for visualization
3. Built an interactive Power BI dashboard to analyze trends and performance

---

## 📊 Dataset
- **Source:** Kaggle – Uber Ride Analytics Dashboard  
- **Link:** https://www.kaggle.com/datasets/yashdevladdha/uber-ride-analytics-dashboard  

### Key Features:
- Booking Status
- Date & Time
- Vehicle Type
- Cancellation & Incomplete Ride Reasons
- Booking Value & Ride Distance
- Ratings & Payment Methods

---

## 🧹 Data Cleaning (Python)
Performed in Jupyter Notebook:
- Checked for duplicates 
- Handled missing values:
  - Numerical features → filled using median
  - Categorical features → filled using mode 
- Merged date and time columns
- Feature engineering:
  - Hour
  - Day of Week
  - Month
  - Peak Hour
  - Time of Day
- Standardized and cleaned inconsistent values

📁 Notebook: `notebooks/data_cleaning_and_eda.ipynb`

---

## 📈 Data Analysis & Visualization (Power BI)
The cleaned dataset was analyzed using Power BI to create an interactive dashboard showing:
- Booking status distribution
- Demand trends (monthly, weekly, hourly)
- Peak hour performance
- Cancellation and incomplete ride analysis
- Revenue trends across time and vehicle types

📁 Power BI file: `powerbi/uber_ride_dashboard.pbix`

---

## 🔍 Key Insights
- ~62% of bookings are successfully completed
- Highest demand occurs in the last quarter of the year (Oct–Dec)
- Fridays and Saturdays show the highest booking volume
- Evening hours are peak demand periods
- Majority of cancellation reasons are labeled as *Unknown*, indicating data quality gaps
- Revenue increases steadily toward year-end, indicating business sustainability

---

## 📌 Conclusion
The analysis shows that Uber maintains consistent demand and strong revenue growth throughout the year.  
While operational challenges such as cancellations exist, the platform demonstrates scalability and long-term sustainability.

---

## 🛠️ Tools & Technologies
- **Python** 
- **Jupyter Notebook**
- **Power BI**

---

## 👩‍💻 Authors
**SAMAHA MAREE ALHADDAD**  
**AHAD OMAR ALFARSI**  
**NOFA JAMAL ALSHARIF**  

