# 📊 Revenue Opportunities Report - Power BI Dashboard

This repository contains the Power BI dashboard for the **Revenue Opportunities Report**, providing a comprehensive overview of opportunity revenue, opportunity count, and pipeline insights.

## 📌 Dashboard Overview

The dashboard contains the following key sections:

### 1️⃣ Opportunity Revenue and Count
Displays the total opportunity revenue ($1.97bn) and the total opportunity count (444).

### 2️⃣ Opportunity Count by Region
A treemap visualization representing the distribution of opportunities across the East, Central, and West regions.

### 3️⃣ Pipeline by Stage
A bar chart visualization breaking down the opportunity count across different sales stages:
- 🟢 Lead
- 🔵 Qualify
- 🟠 Solution
- 🟣 Proposal
- 🔴 Finalize

### 4️⃣ Revenue and Opportunity Count by Month
A combination chart showing monthly revenue (bar chart) and opportunity count (line chart) to track trends over time.

### 5️⃣ Revenue by Region and State
A bar chart visualizing revenue across three main regions (East, Central, and West). This section also supports drill-through to analyze data by individual states.

📌 **Note:** Map and filled map visuals are currently disabled for the organization. To enable them, contact your tenant admin.

### 🧩 Customer Segmentation Insight
A donut chart displays revenue distribution across three customer segments:

Suggested Dataset: [Customer Segmentation on Kaggle](https://www.kaggle.com/datasets)

![Revenue by Segment](https://github.com/user-attachments/assets/8973f5a5-7d58-462d-a0d2-0749e790326b)
revenue_by_segment.png)

For advanced analysis, you can integrate customer segmentation data from Kaggle datasets to better understand customer behavior and improve targeted marketing.

🔗 Suggested Dataset: Customer Segmentation on Kaggle

## 🔍 Data Loading and Transformation Process

### Data Source Integration:
- Imported data from SQL Server and CSV files.

### Data Cleaning:
- Removed duplicate records and null values.
- Standardized date formats and currency values.
- Ensured consistent data types across fields for accurate aggregation.

### Data Transformation:
- Created calculated columns for revenue segmentation.
- Applied DAX measures for dynamic aggregations.
- Merged datasets using Power Query to enrich insights.
- Implemented data relationships between fact and dimension tables.

## 🚀 Power BI Features Used

This Power BI dashboard utilizes a variety of advanced features:
- **Power Query:** For data transformation, merging, and enrichment of datasets.
- **DAX (Data Analysis Expressions):** Used for creating calculated columns and dynamic measures for revenue segmentation.
- **Bar Charts, Treemaps, Donut Charts, and Combination Charts:** To visualize the opportunity revenue, pipeline stages, and customer segmentation.
- **Drill-through Functionality:** Enabling deeper insights by drilling down into regions and states.
- **Conditional Formatting:** Used for highlighting key insights within the charts.
- **Slicers and Filters:** To allow users to dynamically filter data by regions, stages, or time periods.

## 🚀 Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/revenue-opportunities-dashboard.git
   ```

2. Open the Power BI file (.pbix) in **Microsoft Power BI Desktop**.

3. Ensure your data source is correctly configured and refreshed.

4. Check that map and filled map visuals are enabled in your organization's **Power BI Admin Portal** if required.

## 🛠️ Troubleshooting

If maps are not displaying:

1. Verify that geographic data is properly categorized (e.g., State, Country, Latitude/Longitude).
2. Ensure map visuals are enabled by your organization's Power BI admin.
3. Check your network connection and permissions for external map services.

## 🤝 Contributing

We welcome contributions to improve and extend the dashboard! Please follow these steps:

1. Fork the repository.
2. Create a new feature branch.
3. Commit your changes and open a pull request.

## 📄 License

This project is licensed under the MIT License.

## 📧 Contact

For questions or support, please reach out via GitHub Issues.

