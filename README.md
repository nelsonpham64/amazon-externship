# Amazon Workforce Sentiment & Burnout Analysis

**Amazon Externship Project | NLP, Sentiment Analysis, Workforce Analytics**

Analyzed 130+ employee feedback records from Glassdoor and YouTube using Python and Natural Language Processing (NLP) to identify burnout drivers and deliver data-driven workforce recommendations to improve morale and retention.

---

# Business Problem

Amazon fulfillment center employees were experiencing significant burnout and exhaustion, but it was difficult to identify root causes due to the volume of unstructured feedback.

This project aimed to answer:

**What are the root causes of employee burnout, and which operational interventions would have the greatest impact on workforce morale and retention?**

---

# Key Results

* Identified **burnout as the most dominant workforce issue** across both employee and public feedback
* Discovered **YouTube sentiment was significantly more negative than Glassdoor**, revealing dissatisfaction not fully captured in formal reviews
* Found that **workload intensity, production pressure, and insufficient recovery time** were primary burnout drivers
* Delivered **5+ actionable workforce recommendations**, including a pilot program designed to reduce fatigue and improve retention

---

# Tools & Technologies

* Python
* pandas
* NLTK
* TextBlob
* Matplotlib
* Google Colab
* Excel

---

# Dataset Overview

Analyzed **130+ employee feedback records** from two sources:

## Glassdoor Reviews

* Structured employee reviews (pros, cons, advice)
* Professional and balanced tone
* Provided reliable internal workforce perspective

## YouTube Comments & Transcripts

* Unstructured public feedback
* More emotionally direct and candid
* Revealed workforce frustrations not fully expressed in formal reviews

---

# Methodology

## Data Cleaning & Preprocessing

Built an end-to-end NLP pipeline to prepare raw text for analysis.

Key steps included:

* Loading raw CSV data into pandas DataFrames
* Removing null values and duplicate records
* Converting text to lowercase
* Removing punctuation and stopwords using NLTK
* Combining multiple review fields into a unified cleaned text column
* Exporting cleaned datasets for analysis

Relevant scripts:

scripts/amazon_review_data_cleaning.py
scripts/youtube_text_preprocessing.py

---

## Keyword Analysis

Performed keyword frequency analysis to identify dominant workforce themes.

Example keyword visualization:

![Amazon Keyword Analysis](visuals/AmazonKeywords.png)

![YouTube Keyword Analysis](visuals/YoutubeKeywords.png)

Relevant scripts:

scripts/amazon_review_keyword_analysis.py
scripts/youtube_keyword_analysis.py

---

## Sentiment Analysis

Applied TextBlob sentiment classification to categorize feedback as:

* Positive
* Neutral
* Negative

This enabled structured comparison across platforms and identification of burnout trends.

---

# Key Insights

Burnout emerged as the primary workforce risk factor.

Major drivers included:

* High workload intensity
* Aggressive productivity targets
* Limited recovery time between tasks
* Sustained physical and mental fatigue

A key strategic insight:

**Public sentiment on YouTube was significantly more negative than Glassdoor reviews, indicating formal reporting may underrepresent workforce dissatisfaction.**

---

# Business Recommendation

Based on analysis findings, a targeted pilot program was proposed:

## Task Rotation + Flexible Pacing Pilot

**Objective:** Reduce fatigue and improve retention

**Plan:**

* Rotate associates between tasks to reduce repetitive strain
* Temporarily adjust pacing during high-fatigue periods
* Implement in one fulfillment zone during high-volume shifts

**Success Metrics:**

* Reduction in fatigue complaints
* Improved morale feedback
* Lower turnover risk indicators

---

# Project Structure

amazon-workforce-sentiment-analysis/

data/
    glassdoor_cleaned_with_text.csv
    youtube_sentiment.csv

scripts/
    amazon_review_data_cleaning.py
    amazon_review_keyword_analysis.py
    youtube_text_preprocessing.py
    youtube_keyword_analysis.py

visuals/
    AmazonKeywords.png
    YoutubeKeywords.png

README.md

---

# Skills Demonstrated

This project demonstrates the ability to:

* Clean and process unstructured real-world data
* Perform Natural Language Processing (NLP)
* Conduct sentiment and keyword analysis
* Extract meaningful business insights from qualitative data
* Translate analysis into actionable business recommendations

---

# Why This Project Matters

This project reflects real-world analyst responsibilities, including:

* Workforce analytics
* Risk identification
* Operational improvement analysis
* Data-driven decision support

These skills are directly applicable to:

* Data Analyst roles
* Business Analyst roles
* Workforce Analytics
* Consulting

---

# Author

Nelson Pham
Business Analytics Student, California State University, Fullerton

Portfolio: https://nelsonpham64.github.io
GitHub: https://github.com/nelsonpham64
