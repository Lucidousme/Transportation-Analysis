# Lagos-Deliveries-Performance
# NOTE: The Dataset used in this project is not real and was simulated using an LLM
This project analyses delivery operations data from Lagos to understand the factors influencing delivery success and failure. The goal is to uncover operational patterns, identify high-risk delivery conditions, and generate insights that can help logistics companies improve efficiency and reliability. The analysis follows a full data analytics workflow, from data cleaning and preprocessing to feature engineering and exploratory data analysis (EDA).

# Objectives

Clean and preprocess raw delivery data for analysis

Identify key factors contributing to failed deliveries

Analyse delivery performance across distance, time, weight, and location zones

Visualise trends and patterns to support data-driven decision-making

# Dataset Description

The dataset contains delivery-level records, including:

Order and delivery dates

Delivery status (Delivered / Failed)

Pickup and delivery locations

Distance covered (km)

Delivery time and time slots

Package weight

# Data Cleaning & Preprocessing

Key preprocessing steps included:

Converting date columns to proper datetime formats

Standardising inconsistent delivery status values

Cleaning and standardising location names

Handling missing values using median imputation

Removing invalid records (e.g. zero distance values)

# Feature Engineering

New features were created to enhance analysis:

Failed Delivery Flag – Binary indicator for delivery failure

Is Weekend – Identifies weekend deliveries

Delivery Speed (km/hour) – Distance divided by delivery time

Time-Based Indicators – Morning and evening delivery flags

Binned Variables – Distance, delivery time, and package weight bands

# Exploratory Data Analysis

The analysis explored delivery failure rates across:

Distance bands

Delivery time duration

Day of the week

Package weight categories

Pickup-to-delivery zone combinations

Combined distance and delivery time interactions

Visualisations were created using Matplotlib and Seaborn to clearly communicate insights.

# Key Insights

Longer delivery distances are associated with higher failure rates

Certain delivery time windows show increased risk of failed deliveries

Specific zone-to-zone delivery routes experience consistently higher failure rates

Delivery failures vary by day of the week, indicating operational patterns

# Tools & Technologies

Python

Pandas & NumPy – Data manipulation and analysis

Matplotlib & Seaborn – Data visualisation

Jupyter Notebook – Interactive analysis

Day of the week
