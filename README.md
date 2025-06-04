# E-commerce Sales Dashboard


## 📋 Table of Contents

- [📊 Project Overview](#-project-overview)
  
- [🎯 Key Metrics & KPIs](#-key-metrics--kpis)
  
- [🚀 Dashboard Features](#-dashboard-features)
  
- [📈 Trends Analysis](#-trends-analysis)
  
- [🔧 Technical Details](#-technical-details)
  
- [📊 Data Sources](#-data-sources)
  
- [🗃️ Data Model](#️-data-model)
  
- [🎮 How to Use This Dashboard](#-how-to-use-this-dashboard)
  
- [💡 Key Insights & Recommendations](#-key-insights--recommendations)
  
- [📁 Project Structure](#-project-structure)
  
- [🛠️ Project Development](#️-project-development)
  
- [📞 Contact](#-contact)



## 📊 Project Overview


This is a **personal portfolio project** that showcases advanced **Power BI development skills** and **data analysis capabilities**. I built this E-commerce Sales Dashboard from scratch to demonstrate proficiency in business intelligence, data modeling, and interactive visualization design.
 

---

 
## 🎯 Key Metrics & KPIs


### 💰 Primary Business Metrics

- **Total Revenue**: **$15.70M**
  
- **Total Orders**: **100K**
  
- **Average Order Value**: **$157**
  
- **Total COGS**: **$19.61M**
  
- **Gross Profit**: **$8.87M**
  
- **Average Profit Margin**: **0.27 (27%)**
  
- **Total Shipping Costs**: **$570.27K**
  

### 📊 Performance Indicators

- **Revenue Growth Trends** by month/year analysis
  
- **Order Volume Patterns** and seasonal variations
  
- **Customer Acquisition vs Retention** rates comparison
  
- **Geographic Revenue Distribution** across regions
  
- **Marketing Channel ROI** effectiveness metrics
  
- **Daily and Weekly Sales Patterns** operational insights
  

## 🚀 Dashboard Features


### 📱 Multi-View Analysis

- **Year/Month View**: **Long-term trend analysis** with seasonal patterns identification
  
- **Day/Week View**: **Short-term performance monitoring** for daily operations optimization

### 🎛️ Interactive Filters

- **Year Filter**: **Multi-year comparison** capabilities for historical analysis
  
- **Month Filter**: **Seasonal analysis** and month-over-month trend evaluation
  
- **Day/Week Filter**: **Granular time-based** filtering for operational insights
  
- **Country Filter**: **Geographic performance** analysis by region
  
- **Marketing Channel Filter**: **Channel effectiveness** evaluation and comparison
  
- **Customer Type Filter**: **New vs returning customer** behavioral insights

### 📊 Advanced Visualization Components

- **KPI Cards**: **High-level metric summaries** with trend indicators
  
- **Line Charts**: **Sales trends over time** with interactive drill-down
  
- **Bar Charts**: **Country and channel performance** comparisons
  
- **Donut Chart**: **Customer segmentation** analysis with percentages
  
- **Geographic Analysis**: **Revenue distribution mapping** by country performance


## 📈 Trends Analysis


### 📊 Sales Performance Analysis

- **Monthly Trends**: **Seasonal pattern identification** with peak performance periods
  
- **Daily Patterns**: **Weekday vs weekend** performance comparative analysis
  
- **Geographic Insights**: **Top-performing regions** (Poland, France, Spain, Germany)

### 👥 Customer Behavior Insights

- **Customer Segmentation**: **18.2% new customers**, **81.8% repeat customers**
  
- **Customer Lifetime Value**: **Derived metrics** from repeat purchase patterns
  
- **Acquisition Channel Analysis**: **Marketing channel effectiveness** evaluation

### 📢 Marketing Channel Performance

- **Balanced Performance**: **Consistent results** across all marketing channels
  
- **Channel Distribution**: **SEO, Newsletter, Social Media, Affiliate, Direct, SEM**
  
- **Revenue Allocation**: **Approximately $2.6M per channel** distribution


## 🔧 Technical Details


## 📊 Data Sources

### Primary Data Sources

- **Simulated Sales Data**: Created realistic transaction datasets
  
- **Custom Customer Profiles**: Generated customer segmentation data
  
- **Product Catalog**: Designed comprehensive product information
  
- **Marketing Attribution**: Modeled channel performance data
  
- **Geographic Mapping**: Implemented country-based analysis

### Data Integration

- Self-designed ETL processes using Power Query
  
- Custom data transformation and modeling techniques
  
- Simulated realistic business scenarios for analysis

## 🗃️ Data Model

### Core Tables

- **Sales**: Transaction-level data with order details
  
- **Customers**: Customer master data and segmentation
  
- **Products**: Product catalog and pricing information
  
- **Geography**: Country and regional mapping
  
- **Time**: Calendar table for time-based analysis
  
- **Marketing**: Channel and campaign attribution data

### Calculated Measures

```dax
Total Revenue = SUM(Sales[Revenue])
Average Order Value = DIVIDE([Total Revenue], [Total Orders])
Gross Profit = [Total Revenue] - [Total COGS]
Profit Margin = DIVIDE([Gross Profit], [Total Revenue])
New Customer Rate = DIVIDE([New Customers], [Total Customers])
```


## 🎮 How to Use This Dashboard

### Getting Started

1. **Open Dashboard**: Launch the .pbix file in Power BI Desktop
   
2. **Refresh Data**: Click "Refresh" to update with latest data
   
3. **Navigate Views**: Use the tabs at the bottom to switch between Year/Month and Day/Week views

### Interactive Features

- **Filtering**: Use the dropdown filters at the top to focus on specific time periods, countries, or channels
  
- **Cross-Filtering**: Click on any chart element to filter other visuals
  
- **Drill-Down**: Double-click on time-based charts to drill down to more granular levels
  
- **Tooltips**: Hover over data points for additional context

### Best Practices

- Start with the Year/Month view for strategic analysis
  
- Use Day/Week view for operational monitoring
  
- Apply filters systematically to maintain context
  
- Export insights to PowerPoint for presentations


## 💡 Key Insights & Recommendations


### ✅ Current Performance Strengths

✅ **Strong Customer Retention**: **81.8% repeat customer rate** indicates excellent customer satisfaction

✅ **Diversified Revenue Streams**: **Balanced performance** across multiple countries and marketing channels

✅ **Healthy Profitability**: **Consistent 27% profit margin** across all operations

✅ **Stable Operations**: **Predictable revenue patterns** with identifiable trends

### 🔍 Optimization Opportunities

🔍 **Geographic Expansion**: **Poland shows highest revenue** - consider expanding to similar markets

🔍 **Channel Optimization**: **All channels performing similarly** - investigate specific underperforming areas

🔍 **Seasonal Planning**: **Identify peak periods** for strategic inventory and marketing planning

🔍 **Customer Acquisition**: **18.2% new customer rate** presents improvement opportunities through targeted campaigns

### 📋 Strategic Action Items

1. **Implement Targeted Marketing Campaigns** in **high-performing geographic regions**
   
2. **Analyze Customer Journey Mapping** to **improve new customer acquisition strategies**
   
3. **Optimize Inventory Management** based on **seasonal trend analysis**
   
4. **Develop Channel-Specific Strategies** to **maximize individual channel ROI**
   
5. **Create Customer Retention Programs** to **maintain high repeat customer rates**


## 📁 Project Structure


####   E-commerce_Sales_Dashboard_PowerBI/

##### ├── E-commerce_Sales_Dashboard.pbix # Main Power BI dashboard file

##### ├── README.md # Project documentation

##### ├── Data/ # Data sources folder

##### └── e-commerce sales dataset.xlsx # Sales data source

##### └── Screenshots/ # Dashboard visuals

##### │ ├── E-Commerce_Sales_Day_Week_view.png # Dashboard preview image

##### │ └── E-Commerce_Sales_Year_Month_view.png # Dashboard preview image



## 🛠️ Project Development


- **Tool Used:** Power BI Desktop  

- **Dataset:** Sample Sales data *(anonymized/synthetic)*  

- **Development Time:** Personal project  


---


## 📞 Contact


- **Email**: ekaterine.mashchenko.1@btu.edu.ge
- **GitHub**: [Katherinam4](https://github.com/Katherinam4)
  
