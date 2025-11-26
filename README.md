---
layout: home

---

# Home Credit Project IS-6812 
This repository contains highlights from our practice capstone project for Home Credit.  The project focused on leveraging machine learning models to solve the real-world business problem for Home Credit.  The project will showcase the complete workflow from understanding the business problem, to completing exploratory data analysis, building of four different predictive models, and evaluating results.  The project demonstrates business value to Home Credit by being able to analyze their incomplete data, draw insights, and produce business use cases to better predict if a customer will default on the loan.  

---
## ⭐ Highlights ⭐
- Business Problem

- Solution to Business Problem
  
- Personal Contribution

- Business Value of Solution

- Difficulties During Project

- Key Takeaways 


## 🚩 Business Problem 🚩
Home Credit is a financial services provider specializing in lending to individuals with little or no credit history, empowering them with easy and safe access to financing. It is crucial for Home Credit to accurately assess a customer’s ability to repay in order to identify reliable target customers. By effectively predicting repayment capability, Home Credit can responsibly extend credit to a larger customer base while minimizing financial risk to the company and its investors.

## 🏳️ Solution to Business Problem 🏳️
To address Home Credit's need for reliable and responsible lending decisions, our project will develop a machine learning model to use as a risk assessment to predict whether a customer is likely to default on a loan.  By anlayzing various variables provided in the loan-application process the models will quantify the customer's repayment capability when standard credit history is limited. 

## ▶️ Personal Contribution ▶️
My personal contributions to the project include 

📝Business Problem Statement - Defined the problem scope, objectives, and business context for Home Credit 

📊Exploratory Data Analysis - Analyzed and visualized data to uncover patterns and anomalies 

🤖Logistic Regression Model - Developed and evaluated a logistic regression model to predict loan defaulters 

📉Decision Tree Model - Built and fine-tuned decision tree model to address class imbalance and identify efficiencies 

🧍Presentation Slide Deck - Summarized core findings, methodology, and business impacts 

## 🥇 Business Value of Solution 🥇
There are four objectives in the project solution that add value to Home Credit: 

- Maximize Customer Base

- Minimize Financial Risk

- Empower Financial Freedom of Customers

- Enhance Operation Efficiency 

By accurately predicting customer's likelihood of defaulting on a loan with limited credit history, Home Credit can make more informed lending decisions.  This will enable Home Credit to responsibly extend credit to a broader range of customers while reducing their risk of default.  The project solution supports responsible lending for Home Credit and financial inclusion for it's customers, who generally are underserved.  A bi-product of the decision tree model is the ability generate automated approval / rejection processes based on specific loan application responses.  Overall, these predictive models empower Home Credit to balance financial inclusion with risk mitigation, strengthening Home Credit's customer reach and sustainability.  

## 🪨 Difficulties During Project 🪨
The main difficulty during the project was combatting class imbalance. Only about 8% of the target variable represented loan defaults, which caused the models to be biased toward predicting non-defaulters. To address this challenge the decision tree model weighted the minority class 5:1 during training, helping the model pay more attention to the defaulting class.  Additional, cross-valiation techniques were applied to improve model performance to ensure more robust and generalized predictions. These measures to handle class imbalance highlighted the importances of careful processing, evaluation, and tuning for predictive models.  

## 🧠 Key Takeaways 🧠
This practice project provided valuable experience for myself and the team to work with real-world data.  It allowed the opporunity to gain key learnings from true data that is messy, missing values, imbalanced, and imperfect.  Working on real world data highlighted the need for data cleaning and the time spent upfront in the process to clean the data and understand the variables will pay dividends later on.  Spending time during the EDA will help identify which features are important and which features just add noise.  By selecting the right features we are able to improve the models learning ability and more accurately predict defaulters. The final takeaway I have from the project is appreciating the iterative process of experimenting with different models and tuning parameters to determine the best-performing solution for the dataset to develop a good model.  

