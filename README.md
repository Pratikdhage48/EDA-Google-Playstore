# EDA-Google-Playstore

1. Project
An exploratory data analysis (EDA) project using Python to analyze mobile application data from the Google Play Store. This project uncovers trends in app categories, user ratings, reviews, pricing, and installs.

2. Description / Purpose

The Google Play Store EDA project is designed to provide insights into the Android app ecosystem by analyzing publicly available app data. The analysis helps developers, marketers, and analysts understand app trends, user engagement patterns, and monetization strategies.

3.  Tech Stack

This project was built using the following tools and technologies:

🐍 Python – Core programming language for analysis

📓 Jupyter Notebook – Interactive Python notebook environment

📊 Pandas – Data manipulation and cleaning

🔢 NumPy – For numerical operations

📈 Matplotlib – For creating visualizations

💹 Seaborn – For creating advanced visualization

🧼 Regular Expressions (re) – For text preprocessing

📁 File Format – .ipynb (Jupyter Notebook) and .csv dataset


4. Data Source

Source: Kaggle - Google Play Store Apps Dataset

Data Structure:

Contains information about ~10,000 Android apps, including:

App Name, Category

Rating, Number of Reviews

Installs, Type (Free/Paid), Price

Size, Content Rating

Genres, Last Updated, etc.


5. Business Problem

With over 3 million apps on the Play Store, identifying trends, high-performing categories, and user preferences is crucial for app developers and business strategists. Raw data alone doesn’t help in making decisions unless visualized and analyzed properly.

6. Goal of the Project

To perform an in-depth exploratory analysis of Google Play Store data to:

Identify top-performing categories

Analyze factors affecting app ratings and installs

Compare free vs paid apps in terms of popularity and price

Detect outliers or inconsistencies in app data

7. Features / Highlights
   
• Walkthrough of Key Insights

Rating Distribution: Most apps are rated between 4.0 and 4.5

Top Categories: 'Family' and 'Game' are the most common app categories

App Types: Majority are free apps; paid apps are a small fraction

Installs Distribution: Extremely skewed; very few apps have over 1M installs

Price Outliers: Identified apps with unusually high prices for further review

Correlation Analysis: Relationship between reviews, rating, and installs

Data Cleaning: Converted price and install columns, handled nulls and duplicates

📈 Business Impact & Insights

Developers: Identify which app types and categories to focus on

Marketers: Understand what drives installs and reviews

Product Teams: Compare free vs paid models for monetization

Business Strategy: Recognize gaps in the market by genre and category
