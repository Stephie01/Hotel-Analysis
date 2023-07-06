# Hotel-Analysis
## Problem Statement
The main aim is to investigate the impact of customer reviews on hotel satisfaction and identify key factors influencing customer sentiment in order to improve the overall guest experience and make informed business decisions for hotels.

## Objectives

Data Preparation: Preprocess and clean the hotel reviews dataset to ensure data quality and remove any irrelevant or redundant information.

Sentiment Analysis: Perform sentiment analysis on the customer reviews to determine the overall sentiment expressed by customers, such as positive, negative, or neutral.

Identify Key Factors: Analyze the customer reviews and extract the key factors that influence customer sentiment and satisfaction. These factors could include aspects like cleanliness, service quality, amenities, location, pricing, and staff behavior.

The need for the project lies in leveraging the wealth of customer review data to gain insights into the factors that influence hotel satisfaction, improve guest experiences, and enable hotels to make informed decisions for business success in the competitive hospitality industry.

## Success Metrics
Customer Satisfaction Score: Measure the overall customer satisfaction based on sentiment analysis of hotel reviews. This can be calculated as the percentage of positive reviews out of the total number of reviews.

Key Factors Identification: Evaluate the effectiveness of identifying key factors influencing customer sentiment by comparing the identified factors with expert knowledge or industry benchmarks. Measure the precision and recall of the identified factors.

## Data Understanding
This dataset contains 515,000 customer reviews and scoring of 1493 luxury hotels across Europe. Meanwhile, the geographical location of hotels are also provided for further analysis.

Data Content The csv file contains 17 fields. The description of each field is as below:

Hotel_Address: Address of hotel.

Review_Date: Date when reviewer posted the corresponding review.

Average_Score: Average Score of the hotel, calculated based on the latest comment in the last year.

Hotel_Name: Name of Hotel

Reviewer_Nationality: Nationality of Reviewer

Negative_Review: Negative Review the reviewer gave to the hotel. If the reviewer does not give the negative review, then it should be: 'No Negative'

Review_Total_Negative_Word_Counts: Total number of words in the negative review.

Positive_Review: Positive Review the reviewer gave to the hotel. If the reviewer does not give the negative review, then it should be: 'No Positive'

Review_Total_Positive_Word_Counts: Total number of words in the positive review.

Reviewer_Score: Score the reviewer has given to the hotel, based on his/her experience

Total_Number_of_Reviews_Reviewer_Has_Given: Number of Reviews the reviewers has given in the past.

Total_Number_of_Reviews: Total number of valid reviews the hotel has.

Tags: Tags reviewer gave the hotel.

days_since_review: Duration between the review date and scrape date.

Additional_Number_of_Scoring: There are also some guests who just made a scoring on the service rather than a review. This number indicates how many valid scores without review in there.

lat: Latitude of the hotel

lng: longtitude of the hotel
