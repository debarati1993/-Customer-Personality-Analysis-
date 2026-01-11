# -Customer-Personality-Analysis-
### Objective:
####  The primary goal of this project is to perform a detailed Customer Personality Analysis to help a business better understand its customers and optimize its marketing strategies.         By shifting from a "one-size-fits-all" approach to a data-driven targeted strategy, the business can improve customer engagement and maximize return on investment (ROI).

####  The project is divided into two core phases:
    
####    1. Customer Segmentation (Unsupervised Learning):  To analyze customer demographics, spending patterns across various product categories (Wines, Fruits, Meat, etc.), and purchasing channels.
 ####   2. Response Prediction (Supervised Learning):** To develop a predictive classification model that identifies which customers are most likely to respond to a marketing campaign.
 
### 🔍 Project Overview:
#### 1. Dataset Analysis: Explored profiles of 2,240 customers, analyzing demographics, spending habits, and campaign history.
#### 2. Data Engineering: Performed cleaning, handled missing values, and engineered new features like 'Age' and 'Total Spend' to sharpen the model's accuracy.
#### 3. Strategic Workflow: Implemented an end-to-end pipeline from Exploratory Data Analysis (EDA) to a final predictive model.

### 📊 Key Insights Extracted:
#### 1. Customer Segmentation using KMeans Clustering: Used the K-Elbow method to identify 6 distinct customer personas. This allowed for a deep understanding of natural groupings within the customer base.
#### 2. The "High-Value" Elite: Discovered a specific cluster of high-income individuals who drive the majority of profits in premium categories like Wines and Meat.
#### 3. Targeted Predictors: By training multiple models, I found that Random Forest was the most effective, achieving a 0.8984 ROC AUC.
#### 4. Marketing ROI: The model achieved 72% Precision, meaning it can accurately identify "Likely Buyers," allowing the business to focus resources on the most profitable 30% of the audience.

### 🛠 Tech Stack:
#### Python | Pandas | Scikit-Learn | Matplotlib | Seaborn | KMeans Clustering | Random Forest | EDA

