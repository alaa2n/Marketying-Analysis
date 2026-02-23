Marketing & Sales Analytics Power BI Project

A complete data analytics project combining SQL, Python, Sentiment Analysis, DAX, and Power BI to analyze marketing performance, customer engagement, product conversions, and customer reviews.

🧠 Sentiment Analysis (Python)

One of the key components of this project is performing Sentiment Analysis on customer reviews using Python before loading the cleaned data into Power BI.

Why Sentiment Analysis?

The raw customer reviews contained unstructured text.
To properly analyze customer satisfaction and generate insights, I needed to convert these review texts into sentiment categories that Power BI can measure.

🛠 Steps Performed in Python
1️⃣ Text Cleaning & Preprocessing

I performed NLP preprocessing to clean the review text:

Lowercasing

Removing punctuation

Removing extra whitespace

Tokenization

Removing stopwords

Lemmatization

2️⃣ Sentiment Classification

I applied a pretrained NLP sentiment model to classify each review into:

Positive

Negative

Neutral

Mixed Positive

Mixed Negative

This turned raw text into actionable categorical data.

3️⃣ Exporting Cleaned Data

After processing, I exported the results into a refined table:

fact_customer_reviews → containing sentiment labels, rating, product, date, and cleaned review text.

This table was then loaded into Power BI as part of the final data model.

🧹 SQL Data Cleaning

I cleaned all fact tables using SQL before importing them into Power BI.

Key Cleaning Steps

Removed duplicates

Standardized column names

Corrected datatypes

Converted review text into structured sentiment categories

Cleaned invalid product names and empty values

Created a refined fact table (fact_customer_reviews) using SQL SELECT queries

This ensured reliable, consistent data for analysis.
📐 DAX Measures
Conversion Measures

ConversionRate

MTD ConversionRate

PrevMTD ConversionRate

ConversionRate by Product

Time intelligence: MTD, YTD, Month-over-Month

Engagement Measures

EngagementRate

CTR

TotalLikes, TotalViews, TotalClicks

Monthly trends for views, likes, and clicks

Customer Reviews Measures

AvgRating

MTD AvgRating

Reviews by SentimentCategory

Reviews by Rating

These measures drove all KPI cards, line charts, comparison visuals, and trends.

📊 Power BI Dashboards

I designed three full dashboards, each focusing on different analytical goals.

1️⃣ Conversion Dashboard
Includes

MTD Conversion Rate KPI with comparison to last month

Monthly conversion trend

Conversion by product

Conversion by month matrix

Total purchases KPI

Insights Unlocked

Identifying high-converting products

Tracking seasonal performance

Detecting months with weak conversion (e.g., May, August)

2️⃣ Engagement Dashboard
Includes

Engagement Rate KPI

CTR KPI

Views, clicks, and likes over time

Campaign count by product

Views by content type (Blog, Social Media, Video)

Views by month & product

Insights Unlocked

Views decline in the second half of the year

Blogs outperform all other content types

Opportunities to improve CTR with stronger CTAs

3️⃣ Customer Reviews Dashboard
Includes

MTD Average Rating

Review count by rating

Sentiment analysis distribution

Avg rating by sentiment category (monthly)

Full review table with filters

Insights Unlocked

Majority of feedback is positive

Mixed comments show improvement opportunities

Seasonal drops in rating trends

📈 Final Insights & Recommendations

Based on dashboard insights, I developed actionable recommendations:

✔ Increase conversions

Focus on top-performing products

Run campaigns during low-conversion months

✔ Boost engagement

Improve content formats

Strengthen call-to-action strategies

Increase content output in Sep–Dec

✔ Improve customer satisfaction

Analyze mixed/negative reviews

Implement feedback resolution workflows

Encourage updated reviews after solving issues

🛠 Tools & Technologies

SQL → Data cleaning & preprocessing

Power BI → Data modeling, DAX, dashboards

DAX → KPI calculations & time intelligence

Star Schema Modeling → Optimized analytics structure

🛠 Tools & Technologies

Updated with Python:

Python (NLP / Sentiment Analysis)

SQL

Power BI

DAX

Star Schema Modeling

🚀 Summary

This project represents a full end-to-end analytics pipeline:

SQL → Python NLP → Data Modeling → DAX Measures → Power BI Dashboards
<img width="1272" height="661" alt="Screenshot (267)" src="https://github.com/user-attachments/assets/e4884000-3039-4dc2-9d96-2c398f6d0cb3" />
<img width="1277" height="673" alt="Screenshot (268)" src="https://github.com/user-attachments/assets/51598587-bfdd-4af3-903e-e9145bc3eb4c" />
<img width="1279" height="670" alt="Screenshot (269)" src="https://github.com/user-attachments/assets/f1a4b7dc-21bc-44b8-b275-4815a171231b" />
<img width="1267" height="672" alt="Screenshot (270)" src="https://github.com/user-attachments/assets/fe47151a-4e8f-4a37-a2c4-bb1547d29a67" />
<img width="1920" height="1080" alt="Screenshot (259)" src="https://github.com/user-attachments/assets/cd37a7c7-db92-4e4f-8c8d-e5280e8b2e59" />

