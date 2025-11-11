IRCTC Sentiment Analytics using Big Data

Big Data Analytics Project Report
Submitted by: Teesa Sharma
Roll Number: 24MBMB25
Course: MBA - Business Analytics
Institution: University of Hyderabad
Department: School of Management Studies
Submission Date: November 12, 2025

---

Project Overview
This project focuses on analyzing customer feedback for the IRCTC (Indian Railway Catering and Tourism Corporation) using Big Data Analytics.
The main objective is to classify customer sentiments, identify common issues, predict complaints, and analyze passenger loyalty patterns using Apache Spark and NLP techniques.
The dataset was collected from Google Play Store reviews of the IRCTC Rail Connect App.

---

Tools and Technologies Used

* Apache Spark (Core, SQL, MLlib, Structured Streaming)
* PySpark
* Python 3.x
* Databricks Platform
* Matplotlib and Pandas for visualization
* IRCTC review dataset from Google Play Store

---

Project Pipeline
The project uses a unified NLP and ML pipeline for all use cases.
The pipeline flow is as follows:

Data Ingestion
Data Cleaning and Preprocessing
Tokenization
Stopword Removal
TF-IDF Feature Extraction
Model Training and Evaluation
Visualization and Result Export

This pipeline ensures consistency, scalability, and reusability across all experiments.

---

Repository Structure

dataset - contains the original IRCTC review dataset
notebooks - includes Python or PySpark notebooks for all 5 use cases
pipeline - contains pipeline diagrams and architecture workflow
outputs - stores model outputs and processed CSV results
documentation - includes the final project report, PowerPoint, and viva script
README.md - contains an overview of the entire project

---

Use Cases Implemented

Use Case 1: Sentiment Classification
Objective: Classify reviews into Positive, Neutral, or Negative sentiments.
Result: Random Forest achieved the highest accuracy of approximately 89 percent.

Use Case 2: Service Aspect Analysis
Objective: Identify which IRCTC service areas (Food, Booking, Cleanliness, App) receive the most attention.
Result: Booking and App issues had the highest negative sentiment ratio.

Use Case 3: Time-Based Sentiment Trends
Objective: Analyze changes in customer sentiment over time.
Result: Negative reviews increased during peak festival seasons due to booking traffic.

Use Case 4: Complaint Probability Prediction
Objective: Predict whether a review represents a complaint.
Result: Logistic Regression achieved 88 percent accuracy in identifying complaints.

Use Case 5: Customer Loyalty and Engagement Insights
Objective: Cluster users based on loyalty and engagement using K-Means.
Result: Loyal customers accounted for 45 percent, while 18 percent were disengaged.

---

Results and Findings

1. Random Forest and Logistic Regression models provided the best accuracy.
2. Most customers shared positive experiences (around 70 percent).
3. Common complaints involved refund delays and app performance.
4. Loyal customers consistently rated 4 or above and contributed regular feedback.
5. Trends indicated strong correlation between app updates and customer sentiment.

---

Documentation Included

1. project_report - Final written project report
2. ppt.pptx - Project presentation slides

---

Future Enhancements

1. Create real-time dashboards using Spark Structured Streaming.
2. Extend analysis to Hindi and regional language reviews.
3. Integrate Power BI or Tableau for advanced visualization.
4. Incorporate Deep Learning NLP models such as BERT for improved accuracy.

---

Acknowledgment
I sincerely thank the School of Management Studies, University of Hyderabad, for guidance and academic support throughout the project.
Special thanks to mentors and classmates for their assistance and constructive feedback in completing this work successfully.

---
