---
layout: project
comments: True
title:  "Signal 13 Analysis"
date:   2015-05-13 15:00:00
author: Admin
categories:
- project
img: portfolio_02.jpg
carousel:
- 1280x600.gif
website: https://github.com/BaltimoreCityDataLab
blurb: The goal of this project is to use to BPD radio communications to better record the civil unrest unfolding in Baltimore in the aftermath of Freddie Gray's funeral on April 27th. This project uses radio communications to track police activity on April 27th and 28th, the days of heigtened civil unrest in the city. 
---


Baltimore Police radio correspondences allow our city’s law enforcement to coordinate efforts quickly and effectively. 
The goal of this project is to use to BPD radio communications to better understand what happend in the aftermath of Freddie Gray's funeral on April 27th. This project uses radio communications to track police activity on April 27th and 28th, the days of heigtened civil unrest in the city. 

The Entire Recordings can be found at: <a href="http://www.broadcastify.com/archives/feed/3918">Baltimore Police Scanner Recording Archives</a>
These Recordings were put up by the guy behind scan Baltimore: <a href="http://scanbaltimore.com/"> Scan Baltimore </a>

Our datapage includes a zip file of all of the archived audio recordings from the 27th and 28th: <a href="{{"/data/" | prepend: site.baseurl }}">Full Recordings of 27th and 28th</a>

By using a Matlab tools developed by "Insert Name Here" we identified the times at which all Signal 13 calls (code for: officer needs assistance (urgent)) made by BPD that night. We've cut up audio snippets ranging from a minute to a few minutes around the time these Signal 13 were made.

The Audio Snippets can be found at our SoundCloud page: <a href="https://soundcloud.com/baltimorecitydatalab">soundcloud.com/baltimorecitydatalab</a>

#### Project Tasks

1. <strong> Track Locations </strong> <br>
	Signal 13 calls include the location of the officer requesting assistance. However, these calls can be difficult to understand and transcribe. We've offered some of our best guesses at these recordings but we're calling on the open source communities to provide feedback on our transcriptions and offer alternative suggestions. Ultimatley we hope to use a dataset of "correct transcriptions" to create a training set for a future machine learning algorithm 

2.  <strong>Transcribe  </strong> <br>
	If there is anything else on these recordings you find interesting transcribe it!


## Additional Details

* The most Signal 13 calls are concluded with their relevant police district. This helps narrows the geographic area of your search. An overlay of the BPD district map can be found at ScanBaltimore:  http://scanbaltimore.com/

* Almost all signal 13’s are eventually followed by a10-32 call (sufficient units on scene). If you are having trouble understanding the address in the initial Signal 13 call, look out for the corresponding10-32 call. They can be made anywhere between a minute to a few minutes after the initial Signal 13. Hearing the address being spoken in two different instances greatly improves your chance of hearing it correctly. 

* ScanBaltimore provides a table that details all the code and signal calls made by BPD
http://scanbaltimore.com/

* Listen to communications immediately after the signal 13. Sometimes other officers will repeat the address in their own communications. 

* Even if you don’t think you heard the address correctly try searching it on Google anyway. If nothing shows up try various small phonetic variations. Google will do it’s best to match your guess it its already existing catalogue of Baltimore street names. 

* Avoid searching common words that sound similar but you know are incorrect. They are likely to turn up irrelevant search results. 

* Listen for landmarks (shopping centers, parks etc.). They are usually easier to identify and will refine your search. 

* Practice and Repetition: Just by practicing active listening, you will get better at decoding the messages with time. 
