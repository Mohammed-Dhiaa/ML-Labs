# Lab 3: Exploratory Data Analysis - Shopping Behavior

## 1. Project Overview
This project performs Exploratory Data Analysis (EDA) on a Customer Shopping Behavior dataset to identify trends and prepare the data for a Machine Learning classification model that predicts **Subscription Status**.

## 2. Dataset Information
- **Source:** shopping_behavior_updated (1).csv
- **Size:** 3,900 rows, 16 columns
- **Target Variable:** `Subscription Status` (Yes/No)

## 3. Key EDA Findings
Based on the analysis in the Jupyter Notebook:
- **Missing Values:** The dataset is clean with 0 missing values across all columns.
- **Top Category:** The most popular category by purchase volume is **Clothing**.
- **Average Spend:** The average purchase amount is approximately $59.
- **Gender Balance:** The dataset contains more Male shoppers than Female shoppers.
- **Subscription:** Roughly 27% of the customers in this dataset are active subscribers.

## 4. Problem Statement
The goal is to use customer features such as **Age, Gender, Category, and Purchase Amount** to build a classification model that accurately predicts if a customer will subscribe to the service.