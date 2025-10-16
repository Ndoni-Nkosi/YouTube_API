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

<sub>PowerBI dashboard can be downloaded here</sub><br/>
<sub>The Python script can be found here</sub><br/>

## Data Structure Overview

The data was collected with the use of a YouTube API in Python. It extracted one table with the following columns, video_id, channelTitle, title, publish date, viewCount, likeCount, commentCount, and duration. The table consists of over 3000 rows.</br>
During a process of data cleaning and data manipulation, additional columns were added to improve data storytelling such as duration in seconds, subscribers, Name_check to categorise the different Big Brother seasons.</br>

<img width="392" height="211" alt="image" src="https://github.com/user-attachments/assets/1fd59054-2a52-4069-8e79-c551093e4be2" /><br/>

<sub>The YouTube video on data collection, data cleaning and data manipulation can be found here</sub><br/>

## Executive Summary

FSWG was established in 2017 and started getting traction in 2019 when she started uploading Big Brother review videos, then finally peaked in the year 2020. <br/>
Glory's audience engages more on Big Brother Naija (BBN) seasons compared to Big Brother Mzansi (BBM) seasons - TRY ADDING A METRIC <br/>
The titles of her videos help her gain traffic to her channel, which improves her viewCount.<br/>
The overall cahnnel performs well during the two BB seasons (South Africa and Nigeria). These Key Performance Indicators are discussed further in the report; and key improvement areas for the continuation of the channel are discussed as well. <br/>

Below is an overview of the Power BI dashboard and additional graphs are included in the report. <br/>

<img width="1316" height="737" alt="image" src="https://github.com/user-attachments/assets/acd9138e-d91d-4256-82f7-b434469c32df" />


## Insights Deep Dive


An overview of the data is that Glory's channel was created in 2017. Since then there have been over 3K video uploads to date, 359 000 subscribers and over 116 million views. There has been a lot of egagemnt on her videos where there has been more that 4 million likes and 893k comments.</br>

**Views trend analysis**: 
- Since the creation of the channel in 2017 the channel views started increasing in July 2019 with views from 17 799 in June 2019 to 625 942 in July 2019.The channel made its first peak in July 2020 on the launch of Big Brother Naija Season 5. This was a Covid period where peoplew were encouraged to stay home (indoors)
- We notice a trend during BB seasons that views increase at the start and peak of the show then drop again towards the end of the show.
- Every year from 2021 the channel views peak in August during the BBN seasons
- Since BBN aires from July to October we see a drop in views for the remaining months of the year. But, from 2022 there was a shift in views when Glory started uploading videos on the relaunched BBM Season 3.
- This means that the FSWG channel gets high views in the months of Jan to April (BBM seasons) and July to October (BBN seasons)

<img width="957" height="166" alt="image" src="https://github.com/user-attachments/assets/86bcff49-998e-49a4-90e1-a12eaf042e63" />


The graph on the top right shows us that since channel craetion date the channel peaked in the year 2020, during the reviews for BBN Season 5. The peak in views was due to Covid as a lot of people had to be indoors, so a lot of us watched a lot of television. The highest number of views was in BBN Season 6 in the year 2021. There is an occurrence of views peaking during the BBN seasons, especially for the uoploads in August. The channle did well during BBN season reviews (July-October). We notice a peak in views in a non-BBN season in 2022 (Jan-April), which is where BBM was back on people's screens with BBM Season 3. In 2023 January ther was a peak again where there was BB Titans, where there were Nigerain and South African contestants (Jan-April)</br>

**Video upload trend analysis**: 

According to the graph on the top left corner we see that the Other category has more video uploads amounting to 691. The other category is made up of shows that are not BB related. The least number of uploads is in the BBM seasons. This could be because there is a language barrier as BB housemates tend to to speak vernacular, which are languages that Glory does not understand as she is Nigerian. This makes ikt difficult for her to review the BBM seasons. A summarized snapshot of BBM seasons vs views has been shown below and we see that the numbers of views are decreasing since BBM returned where BBM Season was a hit vs the other seasons (Give a recommendation as this should improve in future).</br>



**Best performing videos**: The graph on the bottom left shows the top 5 videos in the entire channel. It looks like the videos with most views were from the reveiews of BBN Season 6, with the top video having over half a million views. This also aligns with the top right graph where we see most viewCounts in the year 2021. It is also evident in the graph that the best performing videos are related to the title of the video. There is a positive relationship with the name of the video and how many subscribers will click on the video. Action words such as fight, caught, smash, etc result in more traffic on the channel. Viewers love a bit of drama and seduction in the BB house.

**Does the duration of the video have an impact on the number of views one gets?** According to the graph on the bottom right we see no relationship between the two variables. The longest videos are created when Glory does reviews on BB reunions and their average views is low at 36k. Whereas on average her videos are between 1k-2k seconds she gets a fair amount of views on average. 

**Top videos**: The graph on the bottom left shows the top 5 videos in the playlist. Her highest number of views is from BBNaija Shine Ya Eye Season in 2021 with half a billion views. There is a positive realtionship between the title of the video and the number of views it gets. Most viewers click on the video based on what the title of the video is. Viewers may click the video for different reasons such as:
- Their favourite housemate's name on the title
- Words like 'drama', 'fight', 'shipping', 'kiss' cause fans of the show want to click the video and find out what transpired in the Big Brother House


## Recommendations

Conclusion:
- It looks like Glory's subscribers and non-subscribers seem to enjoy and engage more on BBN seasons compared to BBM seasons. BBN seasons have more views that BBM. All BBM seasons didn't perform well, but only when BB Titans was introduced then views increased, which could prove that the Nigerian audience is greater than the South African audience on Glory's channel.
- or just simply that the audience prefers BB shows where there are Nigerain contestants
- There is a positive realtionship in the title of the video and how many views it will get
- There is no relationship (correlation) between the length of the video and views

Recommendations:
There's a lesser audience watching BBM review videos compared to BBN review videos. 

## Contact

Please contact me on ...

