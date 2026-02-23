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

(kept as is)

🔢 DAX Measures

(kept as is)

📊 Power BI Dashboards

(kept as is)

📈 Final Insights & Recommendations

(kept as is)

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

