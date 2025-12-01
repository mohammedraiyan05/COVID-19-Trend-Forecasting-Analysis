# 📊 COVID-19 Trend & Forecasting Analysis  
### Python | Power BI | Time-Series Analysis

![Dashboard](https://github.com/mohammedraiyan05/COVID-19-Trend-Forecasting-Analysis/blob/main/Dashboard.png)

---

## 📝 Executive Summary

### 🔍 Problem
COVID-19 datasets from JHU CSSE are raw, unstructured, and spread across multiple CSV files.  
Direct analysis is difficult due to:
- Multiple date columns  
- Irregular formats  
- Missing values  
- No ready-made summary metrics  

A unified and interactive dashboard was needed to understand case growth, deaths, recoveries, and future trends.

---

### ✅ Solution
This project performs complete **data cleaning, transformation, time-series analysis, and visualization** using Python & Power BI.

It includes:
- Preprocessed global COVID-19 time-series data  
- Daily & cumulative trend analysis  
- Forecasting for future case movements  
- Interactive Power BI dashboard with KPIs and global map  

---

### 📈 The Number Impact
- **233+ countries** analyzed  
- **100k+ rows** of data processed  
- **4 main KPIs** (Confirmed, Deaths, Daily Cases, Recovered)  
- **Forecasting models** for trend prediction  
- **Dynamic date slicer** for detailed analysis  

---

## 🧩 Problem
The provided COVID-19 datasets contain:
- Global confirmed cases  
- Global death counts  
- Global recovered cases  
- Daily updated records across regions  

These files are not directly suitable for analysis due to:
- Wide format date columns  
- Lat/Long noise  
- Missing province/state values  
- Non-standardized date formats  

---

## 🔧 Methodology

### 1️⃣ Data Collection
Data sourced from the **Johns Hopkins CSSE COVID-19 Dataset**.

### 2️⃣ Data Preprocessing
Performed using **Python (Pandas)** + **Power Query**:
- Cleaned missing values  
- Unpivoted 300+ date columns  
- Converted inconsistent date formats  
- Removed unnecessary columns  
- Generated a standardized `DateTable`  
- Created country-level summary tables  

### 3️⃣ Data Modeling
A star schema model was created:

**Fact Tables**
- Confirmed_TS  
- Deaths_TS  
- Recovered_TS  
- Daily_Cases  

**Dimension Table**
- DateTable  
- CountrySummary  

Relationships:
- DateTable[Date] → Confirmed_TS[Date]
- DateTable[Date] → Deaths_TS[Date]
- DateTable[Date] → Recovered_TS[Date]


### 4️⃣ Dashboard Development
Built in **Power BI**:
- KPIs for total cases, deaths, recovered  
- Interactive world map  
- Horizontal bar charts by country  
- Time-series line charts  
- Cumulative trend visuals  
- Black-yellow COVID theme design  

### 5️⃣ Forecasting
Time-series forecasting applied using Power BI Analytics for:
- Daily cases  
- Cumulative trends  

---

## 🛠 Skills & Tools Used

### 📌 Python
- Pandas  
- NumPy  
- Data Cleaning  

### 📌 Power BI
- Power Query  
- Data Modeling  
- DAX  
- Forecasting  
- Dashboard Visualization  

### 📌 Concepts
- Time-series analysis  
- Unpivot transformation  
- KPI design  
- Global mapping  

---

## 📊 Results & Recommendations

### ✔ Key Insights
- Significant upward growth in cumulative COVID cases  
- US, India, Brazil consistently lead case counts  
- Mortality rate stabilizes after mid-2020  
- Recovery rates increase over time  

### ✔ Recommendations
- Continue monitoring high-risk regions  
- Use case forecasting for healthcare planning  
- Integrate vaccination data for deeper analysis  

---

## 🚀 Next Steps
- Add vaccination dataset  
- Build machine learning forecasting (Prophet / LSTM)  
- Automate ETL for real-time dashboard refresh  
- Create drill-through country-level pages  

---

## 🙌 Author
**Mohammed Raiyan A**  
*Data Analyst | Python | Power BI | Time-Series Analytics*

