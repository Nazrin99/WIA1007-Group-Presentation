---
title       : Spotify Music Recommendation
subtitle    : A little app that tries to help people
author      : Evangeline Monica a/p Rajen(S2123599),
              Yong Hua Qi(U2102791),
              Leow Jia Sheng(U2102826)
              Mohammad Nazrin bin Mohammad Nazri     Nages(U2000443)
job         : WIA 1007 Assignment Group 22 
framework   : io2012      # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
logo        : spotify1.jpg
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides


---

## Introduction

> 1. For our WIA1007 assignment, We choose to make a <span style ="color: #B0FC38; font-weight: strong; font-family: 'Constantia',Serif; font-size: 25px;">Music Recommendation App</span> as our project and its called <span style="color: #03AC13; font-weight: bold; font-family: 'Constantia',Serif; font-size: 25px;">Spotify Music Recommendation</span>
> 2. The purpose of the app is to <span style="font-family: 'Constantia',Serif; color: #028A0F; font-weight: bold;font-size: 25px;">recommend songs</span> to users based on their <span style="color: #028A0F; font-family: 'Constantia',Serif; font-weight: bold;font-size: 25px;">favourite genres</span> and <span style="color: #028A0F; font-family: 'Constantia',Serif; font-weight: bold;font-size: 25px;">favourite artists</span>

</br>
<span style="font-weight: bold; text-decoration: underline; color: #023047;">Contributors to this Project</span>

> 1. <span style="color: #023047;">Evangeline Monica A/P Rajen &nbsp; (S2123599)</span>     

> 2. <span style="color: #023047;">Yong Hua Qi  &nbsp;  (U2102791)</span>      

> 3. <span style="color: #023047;">Leow Jia Sheng &nbsp;(U2102826)</span>        

> 4. <span style="color: #023047;">Mohammad Nazrin bin Mohammad Nazri Nages &nbsp;  (U2000443) </span>      

--- .class #id 

## The dataset we used
<span>The dataset we obtained is from kaggle.com. Click <a href ="https://www.kaggle.com/leonardopena/top-spotify-songs-from-20102019-by-year" style="font-family: 'Constantia',Serif; color: #028A0F; font-weight: bold;">here</a> to view the dataset in browser</span>
<iframe src="top10s.html" width=50% height=50% allowtransparency="true"> </iframe>

--- .class #id 
## How to use this app

> 1. The user can <span style="color: #028A0F; font-family: 'Constantia',Serif; font-weight: bold;font-size: 25px;">select their favourite music genre</span>.There are a lot of music genre such as Acoustic Pop, Alaska India, Alternative R&B and so on.

> 2. Furthermore, the user can also <span style="color: #028A0F; font-family: 'Constantia',Serif; font-weight: bold;font-size: 25px;">select their favourite artist</span>. For example, Khalid, Sia, Adam Lambert and so on.

> 3. Then, our <span style="color: #028A0F; font-family: 'Constantia',Serif; font-weight: bold;font-size: 25px;">system will display the songs that the user may like</span> based on its popularity as well as the artist,genre and even the year that the song was published.

> 4. Last but not least,our application will also <span style="color: #028A0F; font-family: 'Constantia',Serif; font-weight: bold;font-size: 25px;">display a graph that are shows the popularity of each songs</span> from your favourite artist.

> 5. The user can view know the song recommendation and then <span style="color: #028A0F; font-family: 'Constantia',Serif; font-weight: bold;font-size: 25px;">choose a song that was recommended</span> and enjoy the music.



--- 
## The limitations for this app

> 1. The <span style="color: #028A0F; font-family: 'Constantia',Serif; font-weight: bold;font-size: 25px;">total song</span> in this application is <span style="color: #028A0F; font-family: 'Constantia',Serif; font-weight: bold;font-size: 25px;">insufficient.</span>
> 2. The user is <span style="color: #028A0F; font-family: 'Constantia',Serif; font-weight: bold;font-size: 25px;">unable to listen to the song directly through the app</span>, they will need to search for the song by themselves through Spotify or other music streaming platforms such as Youtube.
> 3. Since the data is obtained from a <span style="color: #028A0F; font-family: 'Constantia',Serif; font-weight: bold;font-size: 25px;">static dataset</span>, the popularity of the songs is only relevant at the time and date that the dataset was created. The app is <span style="color: #028A0F; font-family: 'Constantia',Serif; font-weight: bold;font-size: 25px;">unable to track future changes</span> to the songs' popularity.
