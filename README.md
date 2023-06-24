# Youtube-channel-Insights
Youtube channel Insights

**1. Aims, objectives and background**
   
1.1. Introduction

Founded in 2005, YouTube has emerged as the second largest search engine globally, processing over 3 billion searches each month [1]. However, understanding the inner workings of the YouTube algorithm and the factors that contribute to a video's views and recommendations remains somewhat of a mystery. YouTube boasts one of the most expansive and sophisticated recommendation systems in the industry [2]. This presents a challenge for new content creators seeking to comprehend why certain videos gain traction while others do not. Numerous myths surround the success of YouTube videos [3], such as the belief that higher likes or comments or specific video durations guarantee success. Exploring and identifying trends within specific niches and the topics covered by YouTube channels is also valuable.

This project focuses specifically on data science channels, delving into the statistical analysis of approximately five of the most successful channels in this field. It's important to note that this project is limited in scope and does not consider other niches, which may possess distinct characteristics and audience bases.

1.2. Aims and objectives

Within this project, I would like to explore the following:

- Getting to know Youtube API and how to obtain video data.
- Analyzing video data and verify different common "myths" about what makes a - -video do well on Youtube, for example:
- Does the number of likes and comments matter for a video to get more views?
- Does the video duration matter for views and interaction (likes/ comments)?
- Does title length matter for views?
- How many tags do good performing videos have? What are the common tags among these videos?
- how often do they upload new videos? On which days in the week?
- Explore the trending topics using NLP techniques
- Which popular topics are being covered in the videos (e.g. using wordcloud for video titles)?
- Which questions are being asked in the comment sections in the videos

1.3. Steps of the project

1. Obtain video meta data via Youtube API for the top 10-15 channels in the data science niche (this includes several small steps: create a developer key, request data and transform the responses into a usable data format)
2. Prepocess data and engineer additional features for analysis
3. Exploratory data analysis
4. Conclusions
