##Survival Analysis


##Introduction

This project aims to analyze churn risk in a telecommunications dataset using survival analysis techniques and customer lifetime value (CLV) modeling. The repository contains scripts and notebooks that perform exploratory data analysis (EDA), build parametric models, calculate CLV, and generate insights to aid in customer retention strategies.

##Description

Dataset
The dataset comprises various customer attributes, including Subscriber ID, region code, tenure, age, marital status, address duration, annual income, education level, retirement status, and categorical variables like gender, voice service, internet service, call forwarding, customer category, and churn status.

##Parametric Models

The project involves constructing Accelerated Time Failure (ATF) models using available distributions, comparing their performance, visualizing curves in a single plot, and determining the most suitable model for decision-making beyond simple comparisons. The process includes retaining significant features and finalizing the chosen model.

##Customer Lifetime Value (CLV)

Calculating CLV per customer based on the finalized model and exploring CLV across various customer segments are focal points within this project.

##Reporting

The project concludes with a concise report analyzing factors affecting churn risk. This report includes interpreting coefficients, defining valuable customer segments, estimating an annual retention budget based on CLV and survival probabilities, and proposing additional retention strategies.

##Tools and Libraries

The project employs Python and several libraries, including matplotlib, lifelines, pandas, numpy, seaborn, among others, to perform data analysis, modeling, and visualization.
