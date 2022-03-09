# YouTube Trending Videos Analysis


## Background
Our project is focused on trending YouTube Video Statistics. YouTube maintains a list of the top trending videos on the platform to YouTube using a combination of factors including measuring users’ interactions (number of views, shares, comments and likes). The dataset is a daily record of the top trending YouTube videos. This dataset includes several months of data on daily trending YouTube videos. Data is included for the USA, Great Britain, Germany, Canada, France, Russia, Mexico, South Korea, Japan and India, with up to 200 listed trending videos per day.


## Dataset
The dataset includes data from videos on YouTube that are within trending category each day in the US and UK regions. There are two kinds of data files, one includes video statistics and the other includes comments.


- Video Data
  - video_id
  -	title
  -	channel_title
  -	category_id (Can be looked up using the included JSON files, but varies per region)
  -	tags (Separated by | character, [none] is displayed if there are no tags)
  -	views
  -	likes
  -	dislikes
  -	thumbnail_link
  -	date (Formatted like: [day].[month])

- Comments Data
  -	video_id
  -	comment_text
  -	likes
  -	replies


## Research Question
The primary research question is to analyze the factors that affect the popularity of a YouTube video. The secondary research questions could be performing statistical analysis over time and sentiment analysis around a video.


## Plan for Data Analysis
-	Exploratory Data Analysis: To perform statistical analysis on the data in order to better understand the data and generate insights and hypothesis based on the EDAs performed

-	Data Cleaning: To identify null values and outliers and treat them

-	Feature Selection and Engineering: To identify the scope for deriving new features/variables and then identify the most important features that affect the popularity of a YouTube video

-	Modeling: To build a model to identify the sentiment around a video using the comments and test the accuracy of the model by using sampling and validation techniques.
