---
title: 'Super Bowl Squares'
subtitle: 'infographic'
date: 2018-06-30 00:00:00
description: An infographic showing the most frequently occuring super bowl square combinations.
featured_image: '/images/superbowl/sbs.png'
---


#### Project Overview

Super Bowl squares are a simple way to gamble or make the football game a little more exciting. Participants have the opportunity to purchase from 100 squares which correspond to a pair of scores for each team. At the end of each quarter, the last digit of each team's total score determines the box that wins. Knowing the 100 possible score outcomes, I wondered how frequently certain outcomes have occurred.

To get to the bottom of this, I first pulled the score of each quarter of each Super Bowl and parsed out the last digit of each team's score using R. Then I explored the data and found there were different trends between the first quarter and the other three. Meaning to keep it simple, I chose heatmaps which mimic the layout of a Super Bowl Squares sheet. I first thought of presenting the data through an <a href="http://mike-maieli.shinyapps.io/SuperBowlBoxes" target="_blank"><u>interactive dashboard</u></a>, but thought it would be more effective to show all of the quarters in one view and easily customize the layout.

I developed an infographic which focuses on a large graphic which shows the most frequently occurring square combinations of all quarters, with small multiples to show the most occurring squares of each quarter.

<br/>

![](/images/superbowl/superbowlsquares_large.png)