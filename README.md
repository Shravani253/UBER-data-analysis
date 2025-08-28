# UBER-data-analysis
Uber ride data insights with Power BI visualization and ML prediction of booking/cancellation trends. 

This project focuses on analyzing Uber ride booking data for the NCR (National Capital Region) to understand booking trends, cancellations, and customer behavior. Using Python for data analysis and machine learning, along with visualization in Power BI, the study uncovers actionable insights that can support business decisions.

Objectives

To explore booking patterns and identify high-demand periods.
To analyze reasons behind ride cancellations from both customers and drivers.
To evaluate factors such as vehicle type, pickup/drop locations, and ratings on booking outcomes.
To build and compare machine learning models for predicting booking status and measure their accuracy.

Methodology

The analysis was carried out using Python libraries: Pandas, NumPy, Matplotlib, and Seaborn.
Data Exploration – Reviewed structure, summary statistics, and initial insights.
Data Cleaning – Created a new dataframe daily_stats by cleaning date, time, rows, and columns for consistency.

Data Visualization –
Bookings by ID and value using daily_stats.
Booking status distribution.
Vehicle types used.
Pickup and drop location analysis.
Reasons for cancellation (by drivers and customers).
Customer and driver ratings.
Correlation analysis using a heatmap.
Machine Learning Models – Applied multiple classification models to predict booking outcomes. Compared models based on accuracy scores, and plotted results to rank them.
Power BI Dashboard – Designed for interactive trend exploration and business insights.

Conclusion

The study highlights that ride demand in NCR is concentrated in peak hours, while cancellations occur more often in late hours and certain localities. Ratings, vehicle type, and locations strongly influence ride outcomes. Among all models tested, Random Forest performed the best in predicting booking status. The Power BI dashboard provided an interactive way to visualize these findings, making the analysis useful for both operational improvements and strategic planning.
