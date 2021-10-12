# Assignment-3---602

# **Exploring YouTube's Trending Video and Comments Datasets**

* Exploratory Data Analysis of the 2017 Youtube Statistics from Kaggle.com

* Data is from [Kaggle](https://www.kaggle.com/datasnaek/youtube?select=UScomments.csv)

* This dataset consists of 11 features with about 7992 rows.

There are two kinds of data files, one includes comments and one includes video statistics. They are linked by the unique video_id field.

#### The headers in the video file are:

* video_id (Common id field to both comment and video csv files)
* title
* channel_title
* category_id (Can be looked up using the included JSON files, but varies per region so use the appropriate JSON file for the CSV file's country)
* tags (Separated by | character, [none] is displayed if there are no tags)
* views
* likes
* dislikes
* thumbnail_link
* date (Formatted like so: [day].[month])

#### The headers in the comments file are:

* video_id (Common id field to both comment and video csv files)
* comment_text
* likes
* replies


# Assignment 5 - Regression

We have already performed EDA on this dataset and now we are going to perform EDA on this dataset. 
And now we are going to apply regression on this dataset to answer this question.

#### **How can we predict the number of views from the number of likes,dislikes,comments?**
