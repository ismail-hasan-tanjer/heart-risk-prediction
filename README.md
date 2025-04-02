# Heart Disease Analysis & Prediction

## Abstract
This project aims to analyze heart disease data and predict the risk of heart disease using data analysis and machine learning techniques. The objective is to identify key factors related to heart disease and develop a model to predict the likelihood of a person having heart disease. Leveraging **Databricks, Kafka, and Power BI**, we ensure scalable data processing, insightful visualization, and accurate predictions to support healthcare decision-making.

---

## 1. Introduction
### 1.1 Background
Heart disease remains a major global health challenge, affecting millions of people worldwide. Early and accurate prediction of heart disease can significantly reduce morbidity and mortality. This project adopts a **data-driven approach** utilizing **machine learning and big data technologies** to predict heart disease risk, aiming to facilitate timely preventive measures.

### 1.2 Objectives
- Develop a **scalable data pipeline** for heart disease data processing.
- Implement **advanced data engineering techniques** to clean and preprocess heart disease data.
- Train and evaluate multiple **machine learning models** to predict heart disease risk.
- Visualize key health insights through **interactive Power BI dashboards**.
- Deploy **real-time predictive models** using **Apache Kafka** to enable continuous monitoring.

---

## 2. Literature Review
Extensive research has been conducted on heart disease prediction using machine learning. Studies highlight the importance of factors such as age, cholesterol levels, blood pressure, and lifestyle habits. Models like **Logistic Regression** and **Random Forest** have shown promising results. This project builds on these studies to develop a more robust and scalable prediction pipeline.

---

## 3. Methodology
### 3.1 Design & Architecture
The project follows a structured approach:
- **Data Collection:** Sourcing heart disease datasets from public health databases.
- **Data Engineering:** Data preprocessing, handling missing values, feature selection, and transformation.
- **Machine Learning Models:** Logistic Regression, Random Forest, and Gradient Boosting; fine-tuning the best-performing model.
- **Real-Time Prediction:** Deploying trained ML models using **Apache Kafka** to enable real-time risk prediction.
- **Visualization:** Developing **Power BI dashboards** for insightful health analysis.
- **Integration:** Utilizing **Databricks** for efficient and scalable data processing.
- **Code Implementation:** ETL, streaming data processing, and inferencing models in a real-time environment using **Databricks**.

### 3.2 Workflow

![Heart Disease Prediction Data Bricks](https://github.com/ismail-hasan-tanjer/heart-risk-prediction/blob/main/data%20bricks.jpg)

**Figure 1:** Workflow data bricks of the heart risk prediction

![Heart Disease Prediction Workflow](https://github.com/ismail-hasan-tanjer/heart-risk-prediction/blob/main/workflow---.png)

**Figure 2:** Workflow of the heart disease prediction project

---

## 4. Data Insights & Visualizations
I developed various visualizations using **Power BI** to identify trends and correlations related to heart disease:

- **Age-wise Risk Distribution:** Analyzing age as a key factor in heart disease.
- **Cholesterol vs. Disease Outcome:** Exploring cholesterol levels' impact.
- **Gender and Heart Risk:** Visual representation of gender-wise analysis.
- **Blood Pressure Analysis:** Correlation between hypertension and heart disease.
- **Smoking Status and Risk:** Investigating the link between smoking and heart conditions.

### Dashboard Overview

![Power BI Dashboard](https://github.com/ismail-hasan-tanjer/heart-risk-prediction/blob/main/Picture%20of%20heart%20%20risk%20analysis_page-0001.jpg)

**Figure 3:** Power BI visualization of heart disease trends

![Correlation Heatmap](https://github.com/ismail-hasan-tanjer/heart-risk-prediction/blob/main/co%20rellation%20heat%20map-.png)

**Figure 4:** Correlation Heatmap


![Confusion Matrix](https://github.com/ismail-hasan-tanjer/heart-risk-prediction/blob/main/download%20(1).png)

**Figure 5:** Confusion Matrix


---

## 5. Conclusion
### 5.1 Summary
This project integrates **big data engineering, machine learning, and visualization tools** to predict heart disease risk accurately. The combination of **Databricks, Kafka, and Power BI** allows for real-time predictions and detailed data analysis, supporting healthcare professionals in making data-driven decisions.

### 5.2 Future Work
- Incorporate more diverse and comprehensive datasets.
- Improve prediction accuracy by including additional health parameters.
- Develop a mobile app for real-time risk assessment.

---

## 🔗 Project Repository & Documentation
All resources and documentation are available in the linked repository.

For further details, please refer to the complete documentation in the linked repository.

---

## How to Run This Project
### Prerequisites:
Ensure you have the following installed:
- Python 3.x
- Apache Kafka
- Databricks
- Power BI
- Required Python libraries (install via `requirements.txt`)

### Steps to Run:
1. Clone the repository:
   ```sh
   git clone <repository_link>
   cd Heart_Disease_Prediction
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Start Apache Kafka services.
4. Run the data pipeline script.
5. Train and evaluate the ML model.
6. View insights on the Power BI dashboard.

---

## Why This Project Stands Out
✔ **End-to-End Pipeline:** From data ingestion to real-time predictions.  
✔ **Scalability:** Uses **big data technologies** for handling large healthcare datasets.  
✔ **Industry-Relevant Tools:** Incorporates **Kafka, Databricks, Power BI, and ML models**.  
✔ **Real-Time Processing:** Enables continuous health risk monitoring.  
✔ **Interactive Visualizations:** Offers valuable insights for healthcare professionals.

---

**If you found this project useful, don't forget to ⭐ the repository!**

