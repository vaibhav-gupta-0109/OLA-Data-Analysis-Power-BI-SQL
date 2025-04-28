**🚖 OLA Data Analyst Project**

**🧠 Overview**

This project demonstrates the end-to-end workflow of analyzing OLA ride-hailing data using Excel, SQL, and Power BI Desktop. It highlights the process of data cleaning in Excel, SQL-based data processing, and the creation of a dynamic dashboard in Power BI. The goal is to derive meaningful insights from the dataset, empowering business analysts to make data-driven decisions.

**📚 Project Description**

The dataset, inspired by OLA's operations, contains comprehensive information about ride bookings, including:

🚗 Vehicle Type: Bikes, sedans, SUVs, etc., reflecting customer preferences.

📈 Total Bookings: Insights into overall ride demand.

⭐ Customer and Driver Ratings: Metrics for driver performance and customer satisfaction.

🛣️ Overall Kilometers: Tracking ride distance usage patterns.

📋 Booking Status: Completed, canceled, or pending rides.

❌ Cancel Details: Reasons behind cancellations to identify operational issues.

🕒 Date and Time: Time-series data to observe ride trends.

⚠️ Incomplete Rides: Highlighting partially serviced rides.

💳 Payment Methods: Cash, credit card, digital wallets, and more.

**🛠️ Workflow Highlights**

1. 🧹 Data Cleaning in Excel
📥 Loaded Raw Data: Imported into Excel for inspection.

🧹 Handled Missing and Inconsistent Data:

Removed irrelevant or heavily incomplete rows.

Standardized fields like Vehicle Type, Booking Status, and Payment Method.

🎨 Applied Conditional Formatting: Highlighted anomalies (e.g., extreme ratings).

📅 Normalized Dates and Times: Ensured consistency for time-based analysis.

💾 Exported to CSV: Prepared cleaned dataset for SQL ingestion.

**2. 🗄️ Data Processing in SQL**

📂 Data Ingestion: Loaded cleaned CSV into a SQL database.

🏗️ Schema Design: Proper datatypes assigned for text, numeric, and temporal fields.

🔄 Data Aggregation and Transformation:

Ride Completion Rates, Cancellation Rates, and Aggregated Bookings.

Derived metrics like Average Driver Rating and Distance per Ride.

📊 Query-Based Insights:

Peak booking hours.

Correlations between ratings and cancellations.

KPIs for Power BI visualization.

**3. 📈 Interactive Dashboard in Power BI Desktop**

🔗 Data Import: Connected Power BI Desktop to the SQL database.

🔍 Filter Implementation:

Filter by Date, Vehicle Type, Booking Status, and Ratings.

🖥️ Dashboard Features:

Booking Status Overview.

Trends in Customer and Driver Ratings.

Revenue and Ride Distance Metrics.

Cancellation Analysis.

Payment Method Insights.

🎯 Objectives and Business Value
🚗 Vehicle Preferences: Which categories are most popular?

📈 Booking and Cancellation Trends: Peak times and operational pain points.

🔧 Operational Efficiency: Analyze ride completion rates.

⭐ Customer and Driver Satisfaction: Identify patterns from ratings.

💵 Revenue Insights: Understand the impact of payment methods and ride distances.

These insights enable optimized fleet management, improved customer experiences, and strategic decision-making.

💼 Skills Demonstrated
Excel:

Data cleaning, transformation, and anomaly detection.

SQL:

Advanced querying, data aggregation, schema design.

Power BI:

Building dynamic dashboards with filters and visuals.

Business Analysis:

Translating raw datasets into actionable strategies.

**🚀 Future Enhancements**

🗺️ Advanced Visualization: Incorporate geospatial mapping in Power BI.

🤖 Machine Learning Models: Predict demand, churn rates, and cancellations.

🚛 Fleet Optimization: Analyze operational efficiencies based on distance and usage patterns.

**📝 How to Use This Project**

📥 Load the raw dataset into Excel and clean it.

💾 Export the cleaned data into CSV format.

📂 Import the CSV into a SQL database and run transformation scripts.

📊 Connect Power BI Desktop to your database and design visualizations.

🔎 Explore insights interactively with filters and slicers.

**🧰 Tools and Technologies Used**

🧹 Excel for data preparation and cleaning.

🗄️ SQL for data processing and transformation.

📈 Power BI Desktop for visualization and interactive dashboard building.

**🏁 Conclusion**

This project provides a comprehensive example of how Excel, SQL, and Power BI can work together to transform raw ride-hailing data into insightful dashboards and business strategies.
An excellent demonstration of leveraging data analytics for real-world decision-making!
