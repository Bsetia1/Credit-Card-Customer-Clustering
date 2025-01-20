# Credit Card Customer Clustering

## Overview
This project uses unsupervised machine learning techniques to segment credit card customers based on their behavior. By clustering customers into meaningful groups, the analysis aims to support AllLife Bank in personalizing marketing campaigns and improving operational efficiency. The insights will help target new customers and upsell to existing ones while addressing customer concerns about support services.

---

## Context
AllLife Bank plans to focus on its credit card customer base to increase market penetration. The marketing team intends to run personalized campaigns, while the operations team aims to enhance service delivery. This project helps identify customer segments based on their spending patterns and past interactions with the bank.

---

## Objective
- Identify customer segments based on behavior using clustering techniques.
- Provide actionable insights for personalized marketing and service improvements.

---

## Dataset
**Source**: Bank's customer data.

### Features:
1. **Sl_No**: Customer Serial Number.
2. **Customer Key**: Unique customer identifier.
3. **Avg_Credit_Limit**: Average credit limit of the customer.
4. **Total_Credit_Cards**: Number of credit cards held by the customer.
5. **Total_visits_bank**: Number of visits to the bank.
6. **Total_visits_online**: Number of online interactions with the bank.
7. **Total_calls_made**: Number of calls made to customer service.

---

## Workflow

### **1. Data Exploration**
- Load and clean the dataset.
- Understand the distribution of features using descriptive statistics and visualizations.

### **2. Data Preprocessing**
- Standardize numerical features using z-score normalization.
- Handle missing values and outliers.

### **3. Clustering Techniques**
- **K-Means Clustering**:
  - Applied to identify customer clusters based on spending patterns and interactions.
- **K-Medoids Clustering**:
  - Used as an alternative to K-Means for better handling of outliers.
- **Gaussian Mixture Models (GMM)**:
  - Explored for probabilistic clustering.

### **4. Evaluation and Insights**
- Visualize clusters using pair plots and bar charts.
- Interpret cluster characteristics to derive actionable business insights.

---

## Tools and Technologies
- **Python Libraries**:
  - `pandas` and `numpy`: Data manipulation and analysis.
  - `matplotlib` and `seaborn`: Data visualization.
  - `sklearn`: Clustering algorithms and preprocessing.
  - `scikit-learn-extra`: Advanced clustering techniques like K-Medoids.

---

## Results
- **Clusters Identified**:
  - Segments of customers based on credit limit, interaction patterns, and the number of credit cards.
- **Business Insights**:
  - Identified high-value customers for upselling.
  - Highlighted segments requiring improved support services.
  - Recommended strategies for targeting specific customer groups through personalized campaigns.

---

## How to Run the Project
1. Clone this repository:
   ```bash
   git clone https://github.com/Bsetia1/Credit-Card-Customer-Clustering.git
