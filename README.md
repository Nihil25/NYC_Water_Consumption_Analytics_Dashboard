# 💧NYC_Water_Consumption_Analytics_Dashboard

This project visualizes water consumption data across New York City boroughs using a Power BI dashboard. The goal is to analyze trends, costs, and efficiencies in water usage over time using data stored in a MySQL database and processed in Python.

![Dashboard Preview]....(./https://github.com/Nihil25/NYC_Water_Consumption_Analytics_Dashboard/blob/main/Preview%20of%20dashboard.png)



## 📊 Dashboard Features

- 📅 **Yearly Trends**: Total charges and consumption from 2010 to 2024.
- 🏙️ **Borough Analysis**: Compare water costs and usage across boroughs like Brooklyn, Queens, Manhattan, etc.
- ⚙️ **Efficiency Metrics**:
  - Cost per HCF (Hundred Cubic Feet)
  - Daily Consumption Rates
  - Estimated Meter Count
- 📈 **Visuals Used**:
  - Bar & Column Charts
  - Line Charts
  - KPIs and Cards
  - Donut/Pie Charts
  - Funnel Charts
  - Tables with conditional formatting

---

## 🛠️ Technologies Used

| Tool           | Purpose                         |
|----------------|----------------------------------|
| **Power BI**   | Dashboard & Data Visualization  |
| **MySQL**      | Relational database backend     |
| **Python (Jupyter)** | Data cleaning and processing |
| **Pandas / SQLAlchemy** | Data manipulation & upload |
| **GitHub**     | Version control and sharing     |

---

## 🧪 Data Source

The data includes detailed service-level water usage and billing information:
- `Service Start Date`, `Service End Date`
- `Consumption_HCF`
- `Charges_USD`, `Water_Sewer_Charges`
- `Borough`, `Development Name`
- Calculated fields: `Daily_Consumption`, `Cost_Per_HCF`, `Days_in_Period`

---

## 🚀 Setup Instructions

### 1. Clone the Repo

```bash
git clone https://github.com/yourusername/nyc-water-dashboard.git
cd nyc-water-dashboard
