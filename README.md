# Twitter US Airline Sentiment Analysis (Interactive dashboard created using Power BI)
# Project Analysis
The Twitter US Airline Sentiment Dataset aims to analyze public opinion on major U.S. airlines by categorizing tweets into positive, neutral, and negative sentiments.

## Dataset Used
[Dataset](https://github.com/Ramlah0/Twitter-US-Airline-Sentiment-Analysis/blob/main/Tweets.csv)

## Questions
-What number of tweets are positive, neutral, and negative?

-Which airline has the highest number of negative tweets?

-Which airline has the highest number of positive tweets?

-Which airline is the most frequently mentioned on Twitter?

-Is there a correlation between the number of tweets and sentiment?

-Which airline has the lowest number of negative tweets?

Dashboard Interaction[View Dashboard](https://github.com/Ramlah0/Twitter-US-Airline-Sentiment-Analysis/blob/main/Twitter%20dashboard.pbix)

## Process
Data Cleaning in Excel:

-Removed outliers.

-Removed blank or missing values to ensure completeness.

-Verified that all sentiment labels (Positive, Neutral, Negative) were correctly assigned.

-Imported the cleaned dataset into Power BI for further processing.

Data Cleaning in Power BI (Power Query):

-Removed duplicate tweets based on tweet ID.

-Ensured columns like Date, Sentiment, and Tweet Text had the correct data types.

-Visualized the cleaned dataset in Power BI to analyze sentiment trends, airline performance, and customer complaints.

## Dashboard
[airline](https://github.com/Ramlah0/Twitter-US-Airline-Sentiment-Analysis/blob/main/airline.PNG)

## Insights
-Tweets:

There are 2,340 positive tweets, 3,074 positive tweets and 9,118 negative tweets

Among the negative tweets, United Airline has 2,633 tweets, US Airways Airline has 2,263 tweets, American Airline has 1,900 tweets, Southwest Airline has 1,186 tweets, Delta Airline has 955 tweets and Virgin America Airline has 181 tweets

This shows that United Airline has the highest number of negative tweets while Virgin America has the lowest

United Airline is the most tweeted airline with 3,822 tweets, this could be as a result of the high number of negative tweets while Virgin America is the least tweeted airline with 504 tweets 

The number of tweet an airline receives is positively correlated with the number of negative tweets

-Sentiment Distribution:

The sentiment of tweets vary from Airline to Airline

For negative sentiments: United Airline has the highest negative tweet of 2,633 tweets while Virgin America Airline has the lowest negative tweet of 181 tweets

For positive sentiments: Southwest Airline has the highest positive tweet of 570 tweets while Virgin American Airline has the lowest positive tweet of 152 tweets

For neutral sentiments: Delta Airline has the highest neutral tweets of 723 while Virgin America has the lowest neutral tweet of 171 tweets

-Customer Complaints:

Customers complained the most about poor customer service while customers complained the least about damaged luggage

## Recommendations
-Airlines should improve customer service by reducing cancellations and delays and ensuring timely communication with passengers

-Regular staff trainings should be conducted to improve complaint handling and conflict resolution

-The root cause of high number of negative tweets about United Airline should be investigated

-There should be increased awareness about Virgin Airline as it has the lowest brand engagement 
