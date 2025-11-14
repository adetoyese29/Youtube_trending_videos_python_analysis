# Youtube_trending_videos_python_analysis

## Description and objective
This project focuses on data cleaning, transformation, and exploratory data analysis (EDA) to uncover trends and insights from the "Trending YouTube Video Statistics" data gotten from kaggle. The dataset was processed to handle missing values, date formatting, category mapping, and creation of new features such as publish hour, day of the week, and time-to-trend.

The main objectives of this project are to:
- Prepare the YouTube datasets for analysis by handling inconsistencies, missing values, and formatting issues.
- Engineer meaningful features to better understand video performance and trends.
- Perform exploratory data analysis to identify insights such as:
- Which categories receive the most views, likes, or comments
- The effect of publishing hour or day on video engagement
- The time it takes for videos to appear on trending
- Ratio of likes to dislikes across categories
- Visualize trends and patterns to facilitate understanding of YouTube audience behavior.
- Provide a clean, structured dataset that can be used for further analysis, machine learning modeling, or reporting.

## Dataset
The dataset is a dataset containing data and statistics of trending youtube videos from different countries. The dataset can be found here: https://www.kaggle.com/datasets/datasnaek/youtube-new

## Data cleaning
Some of the data cleaning exercises done were:
- Fixing Data Types
- combining all dataframes into a single big dataframe
- Making copy of original dataframe
- Sorting according to latest trending date while removing duplicates
- Adding a new column 'category' to the DataFrames

## Exploratory analysis
- Top categories
- Top channels
- Videos per country
- Ratio of likes-dislikes in different categories
- Correlation between views, likes and comments
- time to trend


## Libraries used
- pandas
- numpy
- glob
- dateime
- json
- matplotlib
- seaborn

## Key Insights
- Categories like Entertainment, people&blogs and news&politics dominate the trending videos
- Pets & animals, music, howto & style have the highest ratio of likes to dislikes. This tells us that people are more tolerant and love wholesome videos
- I found out that while there are a few outliers, most videos go viral in their first 24 hours of publishing, and even with the outliers, videos tend to go viral inthe first 5 day of publishing. This means creators should look to promote their videos early on
- 
