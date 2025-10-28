# YouTube API project

Big Brother is a reality show where contestants live in a house where they are constantly surveilled and voted out by viewers in the end to win a cash prize. It is a show that has hit Africa by storm since its launch. Contestants come into the house and play whichever strategy they think will work for them to be the 'last person standing.' </br>
Strategies commonly played by contestants include creating drama, forming alliances, taking on roles such as the house chef or stylist, and developing romantic relationships with fellow housemates (often referred to as 'shipping'). It is popularly known for its drama and explores social dynamics. </br>
The YouTube_API project aims to analyse data from one of the most viewed Big Brother review/commentary channles in Africa, 'Frankly Speaking with Glory Elijah'.</br>
**DISCLAIMER**
_This project features a YouTube channel that contains titles and themes of a sexual nature. The content is presented for creative and analytical purposes only and may not be suitable for all audiences. Viewer discretion is advised._

## Table of Contents

- [Background and Overview](#BackgroundandOverview)
- [Data Structure Overview](#DataStructureOverview)
- [Executive Summary](#ExecutiveSummary)
- [Insights Deep Dive](#InsightsDeepDive)
- [Recommendations](#Recommendations)
- [Contact](#contact)

## Background and Overview

Glory Elijah is a Nigerian content creator known for her reviews and commentary on reality TV shows. She runs a YouTube channel called "Frankly Speaking with Glory Elijah," where she focuses on discussing entertainment shows such as _Big Brother Naija_, _Big Brother Mzansi_, _The Real Housewives of Lagos_, _Young, Famous & African_, among others, as well as movies and trending topics on social media.

Insights and recommendations are provided on the following key points:

- **Views Trend Analysis**: An analysis of historical viewing patterns on the channel and identifying which genres or categories perform best
- **Best Performing Videos**: An analysis of the videos with the highest number of views
- **Video Upload Trend Analysis**: An analysis of the number of video uploads during different Big Brother seasons.
- **Duration Analysis**: An exploration of whether the length of the videos influences total views.

<sub>PowerBI dashboard can be downloaded here</sub><br/>
<sub>The Python script can be found here</sub><br/>

## Data Structure Overview

The data was collected using the YouTube API in Python, resulting in a table that contains the following columns: video_id, channelTitle, title, publish date, viewCount, likeCount, commentCount, and duration. This table comprises over 3,000 rows.</br>
During a process of data cleaning and data manipulation, additional columns were created to improve data storytelling. These columns include duration in seconds, subscribers, and a Name_check column to categorise the different Big Brother seasons.</br>

<img width="392" height="211" alt="image" src="https://github.com/user-attachments/assets/1fd59054-2a52-4069-8e79-c551093e4be2" /><br/>

<sub>The YouTube video on data collection, data cleaning and data manipulation can be found here</sub><br/>

## Executive Summary

FSWG was established in 2017 and began gaining traction in 2019 with the release of Big Brother review videos, resulting in the channel peaking in 2020 <br/>
Glory's audience engages more on Big Brother Naija (BBN) seasons compared to Big Brother Mzansi (BBM) seasons - TRY ADDING A METRIC <br/>
The titles of her videos help her attract traffic to her channel, which improves her view counts.<br/>
However, there has been a noticeable decline in views for BBN review videos over the years, which raises concerns about the future performance of Glory's channel.<br/>
Overall, the channel performs well during both Big Brother seasons (South Africa and Nigeria). These Key Performance Indicators are discussed further in the report, along with key improvement areas to ensure the sustainability of the channel. <br/>

Below is an overview of the Power BI dashboard, and supplementary graphs are included in the report. <br/>

<img width="1316" height="737" alt="image" src="https://github.com/user-attachments/assets/acd9138e-d91d-4256-82f7-b434469c32df" />


## Insights Deep Dive


_Frankly Speaking with Glory Elijah_ (FSWG) YouTube channel was created in 2017. More than 3K videos have been uploaded since then with a current number of subscribers at 359k. The channel has over 116 million views with over 4 million likes and 893k comments.</br>

**Views trend analysis**: 
- Since the creation of the channel in 2017, the number of views increased significantly, from 17,799 in June 2019 to 625,942 in July 2019. The channel experienced its first major peak in July 2020 with the launch of _Big Brother Naija Season 5_. This surge in views was likely influenced by the COVID-19 pandemic, which led people to stay indoors and turn to television and social media for entertainment.
- During the Big Brother Naija (BBN) seasons, audience engagement with the channel is highest in the first two months of the show, particularly peaking in August, before gradually declining towards the end of the season. 
- Since BBN airs from July to October each year, there tends to be a drop in views in the remaining months. However, starting in 2022, there was a noticeable shift in viewership when Glory began uploading review videos and content related to the relaunched Big Brother South Africa, commonly known as Big Brother Mzansi.
- This indicates that the channel performs well during the _Big Brother Mzansi_ (BBM) and _Big Brother Naija_ (BBN) seasons, which run from January to April and July to October, respectively.

<img width="957" height="166" alt="image" src="https://github.com/user-attachments/assets/86bcff49-998e-49a4-90e1-a12eaf042e63" />


**Video upload trend analysis**: 

- Shows that are not related to Big Brother have the highest number of uploads in the 'Other' category, currently totaling 703 uploads. This is followed by _Big Brother Naija_ (BBN) Season 6, which has 306 uploads. The categories with fewer video uploads are _Big Brother Mzansi_ (BBM) Season 5 and Season 4, with 123 and 97 uploads, respectively. 
- The decline in total views for the BBM seasons may be linked to the lower number of video uploads. Additionally, Glory could be uploading fewer review videos during the BBM seasons due to a language barrier, as most housemates in the BBM house communicate in South African languages, while she is from Nigeria.

<img width="916" height="552" alt="image" src="https://github.com/user-attachments/assets/c08527d4-dd09-418e-8cf5-d8f098e32da6" />


**Top videos**:

- The most viewed videos are from BBN Season 6, which has the highest view count of 532,347 - use % representation.
- After the BB seasons, Glory provides commentary on the post-BB lives of housemates, movie reviews, and trending reality TV shows such as _The Real Housewives of Lagos_. In the 'Other' category, the most popular video is titled "Who is Big Brother?" with 212,164 views, followed by her review of the movie _Acrimony_, which received 133,854 views.
- The high view counts can be attributed to the titles of the videos. Since BB is known for its dramatic content, the way Glory titles her videos significantly influences the number of views she receives. Using engaging verbs such as "fight," "disqualified," "kiss," and others in the titles helps intrigue viewers and capture their attention.

**Duration analysis**:

- The duration of the video does not dictate how many views one will get.
- Longer videos do not perform well in content that is not Big Brother related, as seen in the 'Other' category, with an average video length of 3k (50 minutes), but the lowest average views at 13k views.
- The channel performs better when uploading videos that are 2k seconds (30 minutes) as the average of views is high.


## Recommendations

- Glory should aim to upload more videos during the _Big Brother Mzansi_ seasons, as there is a positive correlation between the number of uploads and total views. Increased uploads lead to higher view counts, which will help grow her viewer base during those seasons.
- Since the channel has low views after the Big Brother seasons, Glory can improve her views in those months by uploading commentary videos on trending movies (movies that are popular among audiences), and focusing more on Netflix shows, as her reviews of Netflix content tend to receive high view counts.
- Videos in the 'Other' category should ideally be between 1k and 2k seconds (16 to 33 minutes) long. This length keeps the videos engaging while also maintaining watch time.


## Contact

Please contact me via email at ndoni.nkosi@yahoo.com

