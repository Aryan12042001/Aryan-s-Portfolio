# Aryan-s-Portfolio
Data Analytics Portfolio

## **Featured Projects**

### **S&P 500 Live Dashboard with ChatGPT Integration**

**Project Overview**  
This project builds a dynamic and interactive dashboard for visualizing and analyzing the S&P 500 index's performance over various timeframes. The dashboard integrates Python's Streamlit and Plotly libraries for real-time interaction, visualization, and data analysis. The most innovative feature is the integration of ChatGPT, which provides contextual insights based on the selected data points.

**Key Features**
- **Data Visualization**: Candlestick, line, bar, and table charts for diverse analyses.
- **Time Range Filters**: Dynamic filtering for timeframes such as 1 month, 3 months, 1 year, 5 years, or the full dataset.
- **Interactive Analysis**: Clicking on a data point triggers detailed insights on the selected date.

**Advanced Data Analysis**  
- **Weekly Change Analysis**: Weekly percentage changes categorized into bins (e.g., "Extreme Decrease," "Moderate Increase").
- **Custom Color Scheme**: Highlights increases and decreases for pattern recognition.

**Macro-Economic Context**  
- Integrates key indicators like CPI, GDP, inflation rates, and S&P 500 earnings.
- Explores the relationships between economic conditions and market performance.

**AI-Powered Insights**  
- ChatGPT integration delivers context-specific insights based on user selections, providing valuable understanding of market dynamics.

**Technical Implementation**
- **Data Processing**: Preprocessed data for weekly changes, categorized labels, and standardized types. Optimized performance with Streamlit’s `@st.cache_data`.
- **Interactive Visualization**: Interactive graphs powered by Plotly, capturing click events with `plotly_events`.
- **Backend Integration**: Fetching insights from ChatGPT based on the data for AI-powered interpretation.

**Impact and Applications**
- A comprehensive platform for financial analysts, investors, and market enthusiasts to track and analyze S&P 500 performance.
- Helps users make informed decisions through real-time data and AI insights.

**Future Enhancements**
- Expand to include other indices or individual stocks.
- Incorporate predictive modeling for forecasting market trends.

---

### **Glycerin-to-Glycol Production Using Machine Learning**

**Project Overview**  
This project aims to optimize the conversion of glycerin (a biodiesel by-product) into ethylene glycol (EG) and propylene glycol (PG). These glycols have significant industrial applications. Leveraging machine learning, the study predicts yields, detects anomalies, and optimizes production parameters to improve efficiency.

**Key Objectives**
- **Predictive Modeling**: Build models to forecast glycol yields based on factors like hydrogen flow, temperature, and glycerol concentration.
- **Optimization**: Maximize propylene glycol yield while balancing efficiency and resource utilization.
- **Anomaly Detection**: Detect operational anomalies using machine learning techniques.

**Data and Methodology**
- The dataset consists of 228 samples with 38 variables. Key steps included data preprocessing, feature engineering, and model selection.

**Predictive Analysis**  
- Explored multiple models such as linear regression and multi-layer perceptrons to predict glycol yield, achieving robust results with RMSE, MAE, and R² metrics.

**Optimization Modeling**  
- A stacked ensemble model coupled with a Genetic Algorithm (GA) was used to optimize operational conditions. The optimization led to a 7% increase in PG yield.

**Anomaly Detection**  


## [Heart Disease Prediction Using Genetic Algorithms and Ensemble Learning](https://github.com/Aryan12042001/4830_Project)

**Project Overview:** Developed an advanced predictive model for heart disease using Genetic Algorithms (GA) for feature selection and Ensemble Learning methods. The project aimed to enhance prediction accuracy by optimizing feature subsets and combining multiple models.

**Key Techniques:**
- **Feature Selection:** Employed GA to identify the most relevant features.
- **Ensemble Methods:** Used Stacked Generalization with base models including Logistic Regression, SVM, and Random Forest, and a meta-model (AdaBoostClassifier).
- **Evaluation:** Applied K-Fold Cross-Validation and assessed models using accuracy, sensitivity, and specificity.

**Outcome:** The Stacked Genetic Algorithm model demonstrated superior performance with high accuracy and robustness, outperforming individual models and various feature sets.

## Workflow of the project: ![WorkFlow](Image/workflow.png)
---

## [Electric Vehicle Lithium-ion Battery Ageing Analysis Under Dynamic Conditions](https://github.com/Aryan12042001/CPSC_4830)

**Project Overview:** Analyzed lithium-ion battery health and performance in electric vehicles using machine learning techniques to predict battery state of health (SOH) and remaining useful life (RUL).

**Key Techniques:**
- **Data Analysis:** Utilized measurements from charge, discharge, and impedance tests.
- **Modeling:** Applied Linear Regression, Support Vector Regression (SVR), and XGBoost Regressor. XGBoost achieved the highest accuracy and lowest error rates.
- **Evaluation Metrics:** Focused on RMSE, MAE, and R2 scores to gauge model effectiveness.

**Outcome:** XGBoost Regressor was identified as the most effective model, significantly improving battery health predictions and providing valuable insights into battery aging dynamics.
## Comparison of the different models tested: ![Model_comparison](Image/model_comparison.png)
---

## [DANA_4840 Project: Clustering and Classification](https://github.com/Aryan12042001/DANA_4840_Project)

**Project Overview:** Conducted clustering analyses using k-means, PAM, and hierarchical methods on multiple datasets to explore clustering tendencies and determine optimal cluster numbers.

**Key Techniques:**
- **Clustering Methods:** Implemented partitioning (k-means, PAM) and hierarchical clustering.
- **Research Questions:** Investigated the impact of dimensionality reduction on clustering performance and the interpretation of feature similarities within clusters.

**Outcome:** Delivered insights into clustering patterns and validated clusters, providing a comprehensive understanding of dataset structure and clustering effectiveness.

---

## [MIMIC-III Database Analysis and Classification](https://github.com/Aryan12042001/Mimic-III)

**Project Overview:** Set up and analyzed a PostgreSQL database derived from the MIMIC-III ICU dataset to predict patient outcomes, specifically hospital expiration.

**Key Techniques:**
- **Database Setup:** Created and optimized PostgreSQL tables, indexes, and constraints.
- **Data Processing:** Addressed missing values, selected features using PCA, and cleaned data for analysis.
- **Modeling:** Developed a Gradient Boosting Classifier and examined the impact of dimensionality reduction on model performance.

**Outcome:** Successfully built a robust predictive model for patient outcomes, highlighting key features influencing hospital expiration and demonstrating effective data handling and analysis skills.
## Feature importance graph: ![Feature importance graph](Image/Mimic_III_feature_importance.png)


## Education
### Post-Degree Diploma in Data Analytics
Langara College, Vancouver, BC
Expected Completion: 2025

This program has provided me with in-depth training in data manipulation, statistical analysis, machine learning, and visualization. Through hands-on projects and assignments, I've gained experience in analyzing real-world datasets, building predictive models, and using tools like SQL, Python, and R to solve complex analytical problems. Key courses include:

#### Advanced Data Analysis and Modeling: Focused on machine learning algorithms, feature selection, and predictive modeling.
#### Big Data Analytics: Covered data processing in SQL and NoSQL databases, cloud computing, and handling large datasets.
#### Project Management: Provided foundational skills in managing analytics projects, risk assessment, and stakeholder communication.

