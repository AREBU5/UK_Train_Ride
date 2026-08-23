# UK Train Ride Analysis Project

[![Power BI](https://img.shields.io/badge/Power_BI-Dashboard-yellow?logo=powerbi)](https://github.com/AREBU5/UK_Train_Ride)
[![Databricks](https://img.shields.io/badge/Databricks-Notebooks-red?logo=databricks)](https://github.com/AREBU5/UK_Train_Ride/tree/main/Notebooks)
[![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)](https://www.python.org/)
[![SQL](https://img.shields.io/badge/SQL-Databricks-orange)](https://databricks.com/)

## Project Status Update
** Currently Working On:** A comprehensive Power BI dashboard report is currently under development and will be uploaded to this repository at a later date. The dashboard will provide interactive visualizations and executive-level insights based on the analysis performed in the notebooks.

---

##  Project Overview

This project provides an in-depth analysis of UK railway operations, focusing on passenger behavior, operational performance, route efficiency, and revenue generation. Using real-world train ride data, the analysis uncovers actionable insights to improve service quality, optimize routes, and enhance customer satisfaction.

###  Key Objectives
- Analyze passenger travel patterns and peak usage times
- Evaluate operational performance (delays, cancellations, on-time arrivals)
- Identify high-performing and underperforming routes
- Assess revenue streams and financial performance
- Provide data-driven recommendations for operational improvements

---

##  Project Structure

```
UK_Train_Ride/
│
├── Notebooks/
│   ├── Passenger Rail Usage.ipynb      # Passenger behavior and travel patterns
│   ├── Rail Performance.ipynb           # Operational performance metrics
│   ├── Route Analysis.ipynb             # Route efficiency and reliability
│   └── Sales Performance.ipynb          # Revenue analysis and financial insights
│
├── Dashboard/                           # (Coming Soon)
│   └── UK_Rail_Dashboard.pbix          # Power BI interactive dashboard
│
├── README.md                            # Project documentation
└── LICENSE                              # Project license
```

---

##  Data Source

** Maven Anaytics: https://mavenanalytics.io/data-playground/uk-train-rides

The dataset contains comprehensive information about UK train journeys including:
- **Journey Details:** Date, departure/arrival stations, routes
- **Passenger Information:** Ticket types, railcard usage, class of travel
- **Operational Metrics:** Journey status, delay reasons, cancellations
- **Financial Data:** Ticket prices, refund requests, revenue information

### Data Cleaning & Preparation
Prior to analysis, extensive data cleaning was performed including:
- Standardization of delay reason labels (e.g., "Weather", "Weather Conditions", "Bad Weather" → "Weather")
- Handling of null values and missing data
- Date formatting and temporal feature extraction
- Data type conversions and validation

---

##  Notebook Descriptions

### 1. Passenger Rail Usage
**Focus:** Understanding passenger behavior and travel patterns

**Key Analyses:**
- Monthly journey volume trends
- Peak vs. off-peak travel patterns
- Hourly usage distribution
- Railcard utilization analysis
- Ticket class preferences (Standard vs. First Class)

**Visualizations:**
- Monthly passenger journey trends (line chart)
- Peak hour distribution (bar chart)
- Railcard usage breakdown (pie chart)
- Ticket class comparison (bar chart)

**Key Insights:**
- Peak travel occurs during morning (7-9 AM) and evening (5-7 PM) commute hours
- January shows the highest passenger volume
- Majority of passengers travel without railcards
- Standard class dominates ticket sales

---

### 2. Rail Performance
**Focus:** Operational efficiency and service reliability

**Key Analyses:**
- Overall journey status distribution (On Time, Delayed, Cancelled)
- Monthly cancellation trends
- Comprehensive delay reason analysis
- Service reliability metrics

**Visualizations:**
- Journey status distribution (pie chart)
- Monthly cancellation trends (line chart)
- Top delay reasons (horizontal bar chart)
- Cancellation patterns over time (area chart)

**Key Insights:**
- Weather is the leading cause of delays and cancellations
- January experiences the highest cancellation rate (likely due to severe weather)
- Technical issues and signal failures are secondary delay causes
- Majority of journeys complete successfully despite challenges

---

### 3. Route Analysis
**Focus:** Route-level performance and efficiency

**Key Analyses:**
- Most and least popular routes (by passenger volume)
- Routes with highest cancellation rates
- Routes with most frequent delays
- Route reliability comparison
- Departure station performance metrics

**Visualizations:**
- Top 10 popular routes (bar chart)
- Bottom 10 routes by volume (bar chart)
- Routes with highest cancellations (horizontal bar chart)
- Routes with most delays (bar chart)
- Route reliability heatmap

**Key Insights:**
- London stations (Manchester Piccadilly, Reading, Birmingham New Street) serve as major hubs
- Certain routes are significantly more prone to delays and cancellations
- Route reliability varies widely, with some routes achieving >95% on-time performance
- Underperforming routes require targeted operational interventions

---

### 4. Sales Performance
**Focus:** Revenue generation and financial health

**Key Analyses:**
- Monthly net revenue trends
- Revenue distribution by ticket type (Advance, Anytime, Off-Peak)
- Revenue impact by journey status
- Refund analysis by journey status
- Top revenue-generating routes

**Visualizations:**
- Monthly revenue trend (line chart with area fill)
- Revenue by ticket type (pie chart)
- Revenue by journey status (bar chart)
- Refund analysis comparison (dual chart: amount + distribution)

**Key Insights:**
- Revenue peaks in spring/summer months, dips in winter
- Advance tickets generate the highest revenue
- Cancellations result in significant refund liabilities
- Delayed journeys contribute to revenue but incur customer satisfaction costs
- Strategic pricing and refund policies can optimize financial performance

---

##  Key Findings & Recommendations

### Operational Improvements
1. **Weather Preparedness:** Implement proactive weather monitoring and contingency planning
2. **Peak Hour Capacity:** Increase service frequency during 7-9 AM and 5-7 PM windows
3. **Route Optimization:** Focus resources on high-traffic routes; evaluate underperforming routes
4. **Technical Maintenance:** Preventive maintenance programs to reduce signal/technical failures

### Revenue Optimization
1. **Dynamic Pricing:** Leverage peak/off-peak demand patterns for pricing strategies
2. **Advance Booking Incentives:** Encourage advance purchases to stabilize revenue forecasting
3. **Railcard Promotions:** Increase railcard adoption to boost customer loyalty
4. **Refund Policy Review:** Balance customer satisfaction with financial impact

### Customer Experience
1. **Real-Time Updates:** Improve communication during delays and cancellations
2. **Alternative Routes:** Provide rebooking options for frequently disrupted routes
3. **First Class Value:** Enhance first-class offerings to justify premium pricing
4. **Delay Compensation:** Streamline refund processes for improved satisfaction

---

## Technologies Used

- **Databricks:** Cloud-based data engineering and analytics platform
- **Apache Spark:** Distributed data processing
- **SQL:** Data querying and transformation
- **Python:** Data analysis and visualization
  - `matplotlib` - Data visualization
  - `pandas` - Data manipulation
  - `PySpark` - Spark DataFrame operations
- **Power BI:** (In Progress) Interactive dashboard creation
- **Git/GitHub:** Version control and collaboration

##  Contact

For questions, suggestions, or collaboration opportunities, please open an issue in this repository or reach out via Email: danielarebu@outlook.com .


⭐ If you found this project helpful, please consider giving it a star!
