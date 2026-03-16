# 📊 Social Media Engagement Analysis

## 📌 Project Overview
This project analyzes social media engagement data to understand how different factors such as post type, content category, sentiment, user demographics, and device usage influence audience interaction.

The goal of this analysis is to identify patterns that can help improve **content strategy, audience engagement, and overall social media performance**.

---

## 🎯 Objectives
- Analyze engagement metrics such as **likes, comments, and shares**
- Identify **best-performing content types**
- Determine which **content categories perform best**
- Study **user engagement trends**
- Understand the impact of **sentiment and device type on engagement**

---

## 📂 Dataset Information
The dataset contains **5000 social media posts** with the following attributes:

- Post ID
- Post Type
- Content Category
- Likes
- Comments
- Shares
- Impressions
- Watch Time
- Hashtags
- Sentiment
- User Age
- Country
- Device Type
- Verified Account Status

---

## 🧹 Data Cleaning
The following preprocessing steps were performed:

- Handled missing values
- Standardized categorical columns
- Cleaned sentiment labels
- Checked for unrealistic values in engagement metrics
- Converted data types where necessary

---

## ⚙️ Feature Engineering
New features were created to improve analysis:

**Engagement Score**
- Combined likes, comments, and shares to represent total engagement.

**Hashtag Count**
- Calculated the number of hashtags used in each post.

**Log-transformed Metrics**
- Applied log transformation to engagement variables to reduce skewness.

---

## 📊 Exploratory Data Analysis

### Content Performance
- Identified which **post types generate the highest engagement**
- Determined the **best-performing content category**
- Compared **engagement rates across different countries**

### User Trends
- Analyzed how **age affects engagement**
- Compared **verified vs non-verified accounts**

### Behavioral Insights
- Identified the **best time of day for impressions**
- Studied the **impact of device type on watch time**

### Sentiment Analysis
- Compared engagement across **positive, neutral, and negative sentiment posts**

---

## 🔍 Key Insights

- **Video posts generate the highest engagement** compared to other post types.
- **Entertainment and lifestyle content categories perform best**.
- **Users aged 18–34 show higher interaction levels**.
- **Verified accounts receive higher engagement** than non-verified accounts.
- **Evening posting times produce higher impressions**.
- **Mobile users show higher watch time compared to desktop users**.
- **Positive sentiment posts generate the highest engagement**.

---

## 🛠 Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---
