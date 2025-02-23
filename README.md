# Optimizing Electricity Demand for eSC

## Team Members
- Austin Rodrigues
- Lekhith Reddy Kambham
- Likhith Kolli
- Prathyusha Murala
- Vishnu Charugundla

## Project Overview
This project aims to address challenges related to increased energy demand during peak summer months by optimizing electricity usage through predictive modeling and strategic energy management. Our approach focuses on leveraging data-driven insights to enhance sustainability and ensure reliable energy distribution without the need for additional infrastructure.

## Objectives
1. **Predict and Optimize Energy Consumption:** Develop predictive models to forecast hourly energy consumption during peak times, specifically in July, for residential areas served by eSC in South Carolina and parts of North Carolina.
2. **Identify Key Consumption Drivers:** Utilize data analysis to determine the major factors influencing energy usage and identify opportunities for efficiency improvements.
3. **Encourage Sustainable Practices:** Promote energy-saving measures among consumers to reduce peak demand and support eSC's sustainability goals.

## Methodologies
- **Data Integration and Preparation:** Merged static house data, energy usage, and weather data to create a comprehensive dataset for analysis.
- **Exploratory Data Analysis (EDA):** Conducted deep dives into energy consumption patterns to identify trends and anomalies.
- **Predictive Modeling:** Utilized machine learning techniques, including linear regression, random forest, and XGBoost, to build models predicting energy demand.
- **Scenario Simulation:** Tested models under 'extra hot' conditions by adjusting weather data to predict energy demand spikes and assess system robustness.

## Technologies Used
- **Data Management:** Employed big data tools like PySpark for data processing and analysis.
- **Predictive Analytics:** Utilized Scikit-learn and XGBoost for building and optimizing predictive models.
- **Visualization and Reporting:** Developed interactive dashboards using Shiny and Power BI for visualization of predictions and trends.

## Key Achievements
- **High Accuracy in Forecasting:** Achieved robust model performance with high R-squared values, indicating strong predictive capability.
- **Effective Demand Management Strategies:** Proposed practical strategies such as dynamic pricing and demand response programs, which were well-received by stakeholders.
- **Interactive Tool Development:** Created a Shiny app to enable eSC to dynamically explore different scenarios and manage energy demand in real-time.

## Future Directions
- **Advanced Model Development:** Explore deep learning and AI-enhanced forecasting models to further improve prediction accuracy.
- **Expand Geographic Scope:** Apply the model to additional regions to help other utilities optimize their energy management strategies.
- **Enhance Customer Engagement Tools:** Develop more advanced features in the Shiny app to provide customers with personalized energy consumption insights and recommendations.
