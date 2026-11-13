Google Play Store: App Market & User Sentiment Analysis

An Interactive 13-Page Power BI Dashboard

Author: Nikhil Sharma
Project: Capstone Project 4
Tools: Power BI Desktop, Excel, Power Query, DAX

⸻

1. Project Overview

This project explores the Google Play Store ecosystem through an interactive Power BI dashboard to understand the key factors influencing app popularity, quality, pricing and user satisfaction.

The analysis combines Google Play Store application data with user review sentiment to generate actionable business insights for app developers, product managers and marketing teams.

Project Highlights

Metric	Value
Total Unique Apps	9,638
App Categories	33
User Reviews	29,692
Apps with Reviews	865
Dashboard Pages	13

⸻

2. Business Objectives

The dashboard addresses five key business questions:

1. Which app categories dominate in terms of app count and installs?
2. Does app quality (rating) correlate with popularity (installs)?
3. How do free and paid apps differ in reach, rating and pricing?
4. What is the overall user sentiment, and which categories receive the most negative feedback?
5. Do star ratings accurately reflect what users express in written reviews?

⸻

3. Dataset Description

The project uses the Google Play Store Apps and User Reviews dataset.

Dataset workbook: Capstone_Project_4_Play_Store_and_User_Reviews_Cleaned.xlsx

Dataset 1: Play Store Apps

* 9,659 original rows
* 9,638 unique apps after duplicate removal
* 13 columns
* 33 categories

Key attributes include:

* App name
* Category
* Rating
* Reviews
* Size
* Installs
* Type (Free/Paid)
* Price
* Content Rating
* Genres
* Last Updated
* Current Version
* Android Version

Dataset 2: User Reviews

* 29,692 reviews
* 865 apps
* 5 columns

Key attributes include:

* App
* Translated Review
* Sentiment (Positive, Neutral, Negative)
* Sentiment Polarity
* Sentiment Subjectivity

⸻

4. Data Cleaning and Preparation

Data preparation and modelling were performed using Excel, Power Query and DAX.

Key steps:

* Removed duplicate apps using a clean AppKey column (uppercase and trimmed app names).
* Preserved missing ratings as blank rather than replacing them with zero or average values.
* Established a many-to-one relationship between the application and review tables using AppKey.
* Excluded unmatched reviews from category-level analysis.
* Considered Google Play Store install figures as lower-bound ranges.

⸻

5. Dashboard Overview

The Power BI dashboard contains 13 interactive pages, designed with a consistent navy-and-orange theme, navigation menu, KPI cards, slicers and cross-filtering.

Dashboard Pages

Page	Dashboard Section	Analysis
1	Cover	Project introduction and dataset overview
2	Executive Summary	Overall KPIs and Free/Paid slicer
3	Category Landscape	App distribution across categories
4	Installs & Reach	Category-wise app installations
5	Update Freshness	App updates and install performance
6	App Quality	Ratings and category performance
7	Free vs Paid	Pricing, ratings and installs
8	Quality vs Reach	Relationship between ratings and installs
9	Review Sentiment	Positive, neutral and negative reviews
10	Most-Reviewed Apps	Apps with the highest review counts
11	Sentiment by Category	Category-wise sentiment distribution
12	Ratings vs Sentiment	Comparison of star ratings and review sentiment
13	Conclusions	Key findings and recommendations

⸻

6. Key Business Insights

A. App Market Analysis

* Family, Game and Tools account for 37% of all apps.
* Game generates approximately 13.9 billion installs.
* Communication generates approximately 11 billion installs.
* Communication leads in average installs per app at approximately 35 million.

B. App Quality and Pricing

* Average app rating: 4.17 stars.
* 77% of rated apps have a rating of 4.0 or higher.
* Approximately 92% of apps are free.
* Free apps average 8.4 million installs, compared with 76,000 for paid apps.
* Paid apps have a slightly higher average rating of 4.26 compared with 4.17 for free apps.
* Median paid-app price: $2.99.

C. Update Freshness

Apps updated in 2018 average approximately 11.2 million installs, compared with 1.6 million for apps last updated in 2017.

This indicates a relationship between recent updates and app reach, although it does not establish causation.

D. User Sentiment Analysis

Out of 29,692 user reviews:

* Positive: 64%
* Neutral: 15%
* Negative: 21%

Additional findings:

* Games have the highest negative review share at 35%.
* Health & Fitness has 78% positive reviews.
* Angry Birds Classic has 55% negative reviews among the most-reviewed apps.
* ColorNote Notepad has 92% positive reviews.

E. Ratings vs Sentiment

* Correlation between app installs and ratings: approximately 0.08.
* Correlation between star ratings and review sentiment polarity: approximately 0.27.

This suggests that app ratings and written user feedback provide different but complementary perspectives on app quality.

⸻

7. Business Recommendations

For App Developers

* Evaluate category competition before launching new applications.
* Consider free pricing strategies to increase reach.
* For paid apps, understand customer willingness to pay and competitive pricing.

For Product Managers

* Monitor application updates regularly.
* Track user sentiment as an early-warning indicator.
* Investigate negative feedback to improve user experience.

For Marketing Teams

* Do not rely only on app ratings to estimate popularity.
* Focus on distribution, branding and marketing strategies.

For Game Developers

* Investigate negative review themes.
* Evaluate complaints related to advertisements, in-app purchases and game difficulty.

⸻

8. Tools and Technologies

Tool	Purpose
Power BI Desktop	Dashboard development and visualization
Excel	Dataset preparation
Power Query	Data transformation and cleaning
DAX	Measures and KPI calculations

⸻

9. Project Files

* Power BI Dashboard: Nikhil_4th_Capston_Project_Presentation.pbix
* Detailed Project Report: Nikhil_Sharma_Capstone4_PlayStore_Dashboard_Report.docx

Download the files from the repository above.

⸻

10. Project Limitations

* Install figures are lower-bound ranges rather than exact counts.
* Only 865 apps (approximately 9%) have associated user reviews.
* Approximately 15% of apps have missing ratings.
* Sentiment scores are model-generated.
* The dataset represents a snapshot up to August 2018 and does not provide current market trends.

⸻

11. Future Improvements

* Perform text mining on user review content.
* Develop predictive models for app installs and ratings.
* Add category slicers and drill-through pages.
* Refresh the dashboard using more recent datasets.

⸻

Conclusion

This project transforms Google Play Store application data and user reviews into actionable business insights.

By combining app performance, pricing, ratings and sentiment analysis, the dashboard helps identify market opportunities, understand customer satisfaction and support data-driven business decisions.

⸻

Developed by Nikhil Sharma | Power BI Capstone Project 4
