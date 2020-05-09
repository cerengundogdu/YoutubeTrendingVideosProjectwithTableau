### Project Overview

The aim of the project is to visualize a dataset with Tableau by considering the audience needs and to get insighful outcomes for business questions. 

Please check the viz from this link:
https://public.tableau.com/views/TrendingVideosYoutube_StoryPoint/YoutubeTrendingVideos?:display_count=y&:origin=viz_share_link



### Business Questions

I would like to examine the data to make meaningful insights regarding YouTube trends. Today, it is obvious that the social media channels are more attractive for marketing and advertising goods and services. The mainstream media has been less preferred by advertisers. In that sense, understanding the trends in social media is crucial to keep track the world’s trends. With this dataset, I would like to reveal the common pattern on YouTube in each country and present the results in a most effective way. The main objectives of this project are:

- What are the trends (KPIs: views, likes, dislikes, number of comments) by categories for each country?
- How the most viewed, liked, disliked videos vary by countries and by categories?
- Is the publishing time important for the viewing numbers?
- Is there a common pattern between the most trending videos within the country and across the countries?

### Brief Info on Dataset

There are ten different files regarding trending videos on Youtube. However, since using all of them is too big and saving the notebook takes a very long time, I decided to analyze just 5 countries' data. So, I included this project Canada, US, UK, France, and Germany and make them a table by using 'union'. I especially focused on the countries which have relatively high English-speaking rate (Germany:56%, France: 39%; the official language is already English in US, UK, Canada) to be able to make meaningful comparisons between the same trending videos in different countries.

I created five new fields. One of them shows the name of countries, and the second one is for pointing out the category names. Regarding the dates, I created 'publish_day' column to see the weekday of publishing videos and 'publish_time_of_day' column to get publishing time of the day such as morning, evening, afternoon, etc. I divided the day into seven parts to be able to make an analysis regarding the publishing time of the video. Moreover, 'trending_date' was in string format. I converted it to date formatting.



