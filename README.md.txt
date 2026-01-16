# Customer Complaint Root Cause Analysis using NLP

## Overview
This project analyzes real-world customer complaint narratives to identify the
root causes behind complaints across different financial products using
Natural Language Processing (NLP) techniques.

The goal is to move beyond simple complaint counts and understand **why**
customers are dissatisfied by analyzing the language used in their complaints.

## Objective
- Analyze customer-written complaint narratives
- Identify major product categories with high complaint volumes
- Extract root-cause keywords that explain customer issues
- Demonstrate practical NLP and machine learning skills

## Dataset
The dataset used in this project is the **CFPB Consumer Complaint Database**, a
public dataset containing real-world complaints related to financial services.

Due to file size limitations, the raw CSV dataset is not included in this
repository. The dataset can be downloaded directly from the official CFPB
website or Kaggle.

## Methodology
- Data cleaning and preprocessing
- Filtering complaints with valid narrative text
- Exploratory Data Analysis (EDA) to identify major complaint categories
- Text vectorization using TF-IDF
- Complaint category modeling using Naive Bayes
- Root cause identification through keyword extraction

## Key Visualization
The chart below shows the top complaint categories, highlighting where customer
issues are most concentrated.

![Top Complaint Categories](visuals/top_complaint_categories.png)

## Key Insights
- Banking and credit-related products receive the highest number of complaints
- Common root causes include billing issues, overdraft fees, late payments, and
  inaccurate credit reporting
- Debt collection complaints frequently reference aggressive or repeated contact
- NLP-based analysis provides deeper insights than numerical summaries alone

## Tools & Technologies
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook / VS Code

## Conclusion
This project demonstrates how Natural Language Processing can be applied to
large-scale customer complaint data to extract actionable business insights.
The identified root causes can help organizations prioritize operational
improvements and enhance customer satisfaction.
