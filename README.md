Hospitality Revenue & Cancellation Analysis
1. Executive Summary
This project analyzed a dataset of 119,390 hotel bookings to identify the primary drivers of cancellations and provide actionable insights for revenue management. By cleaning the data and applying machine learning, I developed a predictive model to flag high-risk bookings before they impact the hotel's bottom line.

2. Key Technical Achievements
Data Engineering: Cleaned 119k+ records, resolving missing country data and removing "ghost" bookings (0 guests) to ensure data integrity.

Exploratory Data Analysis (EDA): Identified that July and August represent the highest Average Daily Rate (ADR) period, with Resort Hotels seeing the most significant seasonal price spikes.

Geographical Risk Assessment: Discovered that while Portugal (PRT) provides the highest booking volume, it also carries a disproportionately high cancellation risk compared to international markets.

Predictive Modeling: Built a Decision Tree Classifier to identify guest behavior patterns, achieving significant accuracy in predicting stays vs. cancellations.

3. Business Insights & Recommendations
Lead Time Threshold: Bookings made more than 100 days in advance are significantly more likely to cancel.

Recommendation: Implement "Early Bird" non-refundable rates for bookings made 90+ days out.

Segment Risk: "Groups" and "Online Travel Agents" are the most volatile segments.

Recommendation: Require higher deposits for group blocks and monitor OTA distribution channels for "phantom" bookings.

Value of Engagement: Guests who make Special Requests or require Parking Spaces have a much higher "Stay" rate.

Recommendation: Use automated pre-arrival emails to encourage special requests, as this increases guest "buy-in" and reduces cancellation probability.

4. Tools & Technologies
Python: Pandas, NumPy

Visualization: Matplotlib, Seaborn

Machine Learning: Scikit-Learn (Decision Tree Classifier)

Environment: Jupyter Notebook
