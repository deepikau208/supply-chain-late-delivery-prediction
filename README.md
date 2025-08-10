# supply-chain-late-delivery-prediction
A machine learning-based solution to predict late deliveries in supply chain logistics using historical delivery data. The project includes data pre processing, feature engineering, classification modeling, and interactive dashboards for performance monitoring.
Project Overview
This project focuses on predicting delivery delays in the supply chain using Machine Learning and visualizing operational insights through an interactive Power BI dashboard.
It aims to help companies identify delay-prone areas, understand reasons behind delays, and take proactive steps to improve on-time delivery performance.

📂 Files in this Repository
Logistics model.ipynb → Jupyter Notebook with the machine learning model for delay prediction.

complete dashboard(logistics).pbix → Power BI dashboard showing insights and KPIs.

project_presentation.pptx → Presentation summarizing the project findings and recommendations.

dataset/ → Dataset used for training and analysis.

📊 Dataset Overview
The dataset contains:

Delivery and pickup times

Courier details and vehicle types

Delivery region and city

Delay status (on-time or late)

Geographic details for mapping

🔄 Data Preprocessing Steps
Handling missing values – Filled or removed incomplete records.

Feature engineering – Created new fields such as day of week, time slots, and delay categories.

Encoding categorical variables – Converted region, vehicle type, etc., into numeric format.

Scaling features – Standardized data for ML algorithms.

📌 Power BI Insights
Top delay-prone regions – Identified areas where late deliveries are most common.

Courier performance comparison – Tracked top and bottom performers.

Idle time analysis – Found periods when vehicles were underutilized.

Delay trend over time – Monitored performance changes by week and month.

🤖 Machine Learning Model
Objective → Predict if a delivery will be late based on time, region, and vehicle details.

Algorithm Used → Random Forest Classifier (Best performing model).

Evaluation Metrics → Precision, Recall, F1-score for balanced performance.

🎯 Impact of Delays
Loss of customer trust

Increased operational costs

Bottlenecks in supply chain flow

Penalties for missed delivery SLAs

💡 Recommendations
Use predictive alerts for high-risk deliveries.

Assign best-performing couriers to high-delay regions.

Optimize route planning based on historical delay data.

Monitor real-time KPIs using dashboards.

📌 Limitations
Dataset is historical; real-time prediction requires live data integration.

External factors like weather and traffic not included in this version.

Model accuracy may vary for new regions not in the training data.

🚀 How to Use
Open Logistics model.ipynb in Jupyter Notebook to run the ML model.

Open  dashboard(logistics).pbix in Power BI Desktop to explore insights.

View the project_presentation.pptx for the summarized findings

