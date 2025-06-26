# Project I – Data Preparation - BMW Pricing Data Cleaning 🚗🧹

This repository contains the work for **Project I** of the Data Science Master's program at Nuclio Digital School. The focus of this project is on **data exploration and cleaning** of a dataset containing used BMW car listings.

## 🎯 Objective

The goal of this project is to perform a **comprehensive data cleaning process** to prepare the dataset for future machine learning tasks. This includes analyzing null values, handling duplicates, dropping irrelevant features, and addressing inconsistencies across categorical and numerical fields.

## 📂 Dataset

- **Name:** `bmw_pricing_v3.csv`
- **Origin:** Internal project dataset
- **Entries:** Approx. 10,000+ rows
- **Format:** CSV (tabular data)

## ⚙️ Project Scope

All steps were implemented within a single Jupyter Notebook and include:

- **Exploratory data analysis (EDA):**
  - Basic statistics, structure, and shape
  - Distribution of key features
- **Duplicate check:**  
  - Verified and confirmed no duplicate entries
- **Missing value analysis:**
  - Detailed inspection of rows with high null counts
  - Strategic decisions on whether to drop, impute, or keep rows based on feature importance
- **Feature evaluation:**
  - Dropped irrelevant columns
  - Considered impact of missing values in key variables

## 📊 Results Summary

The final outcome is a **cleaned version of the original dataset**, free from:

- Duplicates  
- High-impact missing values  
- Uninformative columns  

All transformations were documented and justified to ensure the dataset is now **ready for modeling and further analysis**.

📄 Repository Contents

This repository contains the following files:

- Project 1_Data Preparation_BMW:
A Jupyter Notebook that documents the complete data cleaning and preparation process, including missing value handling, feature evaluation, and decisions taken to produce a clean dataset ready for modeling.
- bmw_pricing_first50.xlsx:
An Excel file containing the first 50 rows of the original dataset, as requested for the project submission. This sample provides a quick overview of the data structure and key features before cleaning.

## 🚀 How to Run

1. Install required dependencies:

```bash
pip install pandas numpy matplotlib seaborn plotly
