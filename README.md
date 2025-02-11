
# **Capstone Module 3 - Machine Learning**

In today’s digital world, e-commerce has become a huge part of how businesses operate, making it easier than ever to reach customers anywhere. These businesses make money in different ways—through product sales, subscriptions, or even ads—but at the end of the day, none of that matters without customers. With competition fiercer than ever, keeping customers around is just as important as attracting new ones. If too many customers leave, or **churn**, companies start losing market share and revenue, forcing them to spend even more on marketing just to make up for the loss. That’s why understanding and preventing customer churn is key to staying ahead in such a competitive space.

An Anonymous E-Commerce Company has noticed a concerning trend: **customers are leaving**. However, their current approach to churn detection is entirely **manual and reactive**. They only realize a customer has churned after they’ve already stopped being a member. The **lack of proactive intervention** makes it difficult to retain customers before they disappear, leaving the company with no choice but to launch both **costly re-engagement campaigns** and **incentives like discount vouchers** to win them back.

To solve that problem, they have hired us as a Machine Learning Specialist to help them by giving them the ability to proactively engage potentially churning customers. To achieve this, we are to create a Machine Learning Model capable of identifying potentially churning customers. This will help the company to reduce customer churn and unnecessary expenses.

## **Project Objectives**
- Develop a machine learning model that predicts customer churn with high accuracy.
- Identify key factors that contribute to customer churn.
- Provide actionable insights to help the company implement proactive retention strategies.
- Reduce unnecessary marketing expenses by targeting the right customers for re-engagement.

## **Methodology**

1.  **Data Collection & Preprocessing:**
- Load and clean customer transaction and behavioral data.
- Handle missing values and outliers.
2.  **Model Development:**
- Train multiple machine learning models (e.g., Logistic Regression, Decision Trees, Random Forest, XGBoost) to predict customer churn.
- Evaluate models using the appropriate evaluation metrics (F2 score in this case).
- Optimize hyperparameters for the best-performing model.

3.  **Model Interpretation & Insights:**
- Analyze feature importance to understand key factors driving churn.
- Generate actionable insights for the business team.

## **Expected Outcomes**
- A machine learning model capable of accurately predicting customer churn.
- Business insights derived from key churn factors to guide retention strategies.
- Improved customer engagement and reduced marketing costs through targeted interventions.

## **Tools & Technologies Used**
-  **Programming Language:** Python
-  **Libraries:** pandas, numpy, matplotlib, seaborn, scikit-learn, XGBoost
-  **Visualization:** matplotlib, seaborn
-  **Model Evaluation Metrics:** fbeta_score

# **About the Program**
This repository contains:
1. A Python notebook file. This file contains the core of this project. It consists of an explanation of the business problem, data cleaning, preparation and modeling of the Machine Learning model. It has a detailed explanation of why each step was done and important findings throughout the project.
2. A best model file. This is saved through pickling so users dont have to hyper tune the model that may take a long time.
3. The dataset used for this project.

This Project was made in orde to fulfill the passing requirements of Purwadhika's Data Science & Machine Learning class.

This project is not in any way, shape, or form perfect, thus should be for educational purposes only. Proceed with caution when you wish to implement this into a real world production scenario. The creator of this project is not responsible for any damages or losses that may be caused by this program.