# YouTube API project
Big Brother is a reality show where contestants live in a house where they are constantly surveillanced and voted out by viewers in the end to win a cash prize. It is a show that has hit Africa by storm since its launch. Contestants come into the house and play whichever strategy they think will work for them to be the 'last man standing.' Strategies commonly played by contestants include, causing drama (conflict), creating alliances, being the chef or stylist of the house, start a romantic relationship with a fellow housemate ('shipping'), etc. It is popularly known for its drama and tests out social dynamics. The YouTube_API project aims to analyse data from one of the most viewed Big Brother reviewers/commentaries Frankly Speaking with Glory Elijah in Africa.

## Table of Contents

- [Background and Overview](#BackgroundandOverview)
- [Data Structure Overview](#DataStructureOverview)
- [Executive Summary](#ExecutiveSummary)
- [Insights Deep Dive](#InsightsDeepDive)
- [Recommendations](#Recommendations)
- [Contact](#contact)

## Background and Overview

Glory Elijah is a Nigerian content creator who reviews and comments on reality TV shows. She has a YouTube channel called 'Frankly Speaking with Glory Elijah'. The channel focuses on reviewing and commenting on entertainment shows such as _Big Brother Naija_ and _Big Brother Mzansi_, _The Real Housewives of Lagos_, _Young Famous and African_, etc, movies and trending topics on social media.

Insights and recommendations are provided on the following key points:

- **Views trend analysis**: An analysis on the historical views patterns in the channel and which genres/categories perform best
- **Best performing videos**: An analysis on the videos that have the highest number of views
- **Video upload trend analysis**: An analysis on how many video uploads in the different Big Brother seasons
- **Duration analysis**: An analysis on whether the duration of the video contributes to total views

<sub>PowerBI dashboard can be downloaded here</sub><br/>
<sub>The Python script can be found here</sub><br/>

## Data Structure Overview

The data was collected with the use of a YouTube API in Python. It extracted one table with the following columns, video_id, channelTitle, title, publish date, viewCount, likeCount, commentCount, and duration. The table consists of over 3000 rows.</br>
During a process of data cleaning and data manipulation, additional columns were added to improve data storytelling such as duration in seconds, subscribers, Name_check to categorise the different Big Brother seasons.</br>

<img width="392" height="211" alt="image" src="https://github.com/user-attachments/assets/1fd59054-2a52-4069-8e79-c551093e4be2" /><br/>

<sub>The YouTube video on data collection, data cleaning and data manipulation can be found here</sub><br/>

## Executive Summary

FSWG was established in 2017 and started gaining traction in 2019 when she started uploading Big Brother review videos, then finally peaked in the year 2020. <br/>
Glory's audience engages more on Big Brother Naija (BBN) seasons compared to Big Brother Mzansi (BBM) seasons - TRY ADDING A METRIC <br/>
The titles of her videos help her gain traffic to her channel, which improves her viewCount.<br/>
There is a drop in views for BBN review videos over the years which could be a huge concern for Glory's channel in future.<br/>
The overall channel performs well during the two Big Brother seasons (South Africa and Nigeria). These Key Performance Indicators are discussed further in the report; and key improvement areas for the continuation of the channel are discussed as well. <br/>

Below is an overview of the Power BI dashboard and additional graphs are included in the report. <br/>

<img width="1316" height="737" alt="image" src="https://github.com/user-attachments/assets/acd9138e-d91d-4256-82f7-b434469c32df" />


## Insights Deep Dive


_Frankly Speaking with Glory Elijah_ (FSWG) YouTube channel was created in 2017. More than 3K videos have been uploaded since then with a current number of subscribers at 359k. The channel has over 116 million views with over 4 million likes and 893k comments.</br>

**Views trend analysis**: 
- Since the creation of the channel in 2017 the channel views started increasing 17 799 in June 2019 to 625 942 in July 2019.The channel made its first peak in July 2020 on the launch of Big Brother Naija Season 5. Views were possibly attributed by the Covid period where people were encouraged to stay indoors, so television and social media was all we had to keep ourselves busy at the time.
- During BBN seasons the audience engage more with the channel in the first 2 months of the show (highest views in August), then views drop gradually towards the end of the show.
- Since BBN aires from July to October we see a drop in views for the remaining months of each year. But, from 2022 there was a shift in views when Glory started uploading review videos/content on the relaunched Big Brother South Africa, otherwise known as _Big Brother Mzansi_.
- This entails that the  channel performs well during BBM and BBN seasons which are from January to April and July to October respectively. 

<img width="957" height="166" alt="image" src="https://github.com/user-attachments/assets/86bcff49-998e-49a4-90e1-a12eaf042e63" />


**Video upload trend analysis**: 
- Shows that are not Big Brother related have the most uploads with the category 'Other' at currently 703 uploads followed by BBN Season 6 with 306 uploads. The categories with less video uploads are BBM Season 5 and 4 with 123 uploads and 97 uploads, respectively.
- The drop in total views for BBM seasons could be attributed to the low total video uploads
- Low video uploads may be attributed to the fact that there is a language barrier as most of the time housemates in the BBM house speak in South African languages and Glory is from Nigeria

<img width="916" height="552" alt="image" src="https://github.com/user-attachments/assets/c08527d4-dd09-418e-8cf5-d8f098e32da6" />

**Top videos**:
- The most viewed videos are from BBN Season 6 with the highest view count of 532 347 - use % representation.
- After BB seasons Glory does commentaries on the after BB life of housemates, movie reviews and trending reality shows such as _The real housewives of Lagos_ with the 'Other' category having top views for  'who is Big Brother?' at 212 164 views followed by _Acrimony_ movie review at 133 854 views
- The views seem to be high due to the title of the videos. Since BB is known for having drama content, how Glory names her videos plays a role in how many views she will get for the upload. Verbs like fight, disqualified, kiss, etc in the title play a role in intriguing the viewer and getting their attention.

**Duration analysis**:
- The duration of the video does not dictate how many views one will get.
- Longer video lengths with an average of 3000 (50 minutes) do not perform well compared to an average video length of 2000 (30 minutes).
- Longer videos do not perform well in content that is not Big Brother as seen in the 'Other' category with an average video length of 3k (50 minutes), but the lowest average views at 13k views.
- The channel performs better with uploading videos that are  2k seconds (30 minutes) as the average of views are high.


## Recommendations
- Glory should try to upload more videos during the BBM seasons as there is a positive relationship between the total number of uploads and total views. More uploads result in more views. This will in turn increase he viewer base during those seasons.
- Since the channel has low views after the Big Brother seasons, Glory can improve her views in those months by uploading commentary videos on trending movies (movies that are being watched by the masses), and more Netflix shows since the views are high for her reviews on Netflix shows.
- The 'other' category videos should be between 1k and 2k seconds (16 and 33 minutes) in order to keep videos short and sweet and still maintain watchtime


## Contact

Please contact me via email at ndoni.nkosi@yahoo.com

