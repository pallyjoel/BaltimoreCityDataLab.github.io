---
layout: project
comments: True
title:  "Signal 13's on 4/27 and 4/28"
date:   2015-07-04 15:00:00
author: Admin
categories:
- project
img: portfolio_02.jpg
carousel:
- 1280x600.gif
website: https://github.com/BaltimoreCityDataLab
blurb: The goal of this project is to use a sampling of BPD radio communications, recorded by <a href="http://scanbaltimore.com/"> scanbaltimore </a>, to better understand the civil unrest and police response on April 27th and 28th. 
---


Baltimore Police Department radio correspondence allows the city’s police force to coordinate efforts quickly and effectively. 
The goal of this project is to use a sampling of audio recordings of BPD radio communications to better understand what happend in the aftermath of Freddie Gray's funeral on April 27th and 28th.


The full sampling of recordings is available on our data page as a <a href="{{"/data/" | prepend: site.baseurl }}">zipped folder</a> that includes 58 audio files recorded  by <a href="http://scanbaltimore.com/"> scanbaltimore </a> on April 27th and 28th.

<!-- 
By using a Matlab tools developed by "Insert Name Here" we identified the times at which all Signal 13 calls (code for: officer needs assistance (urgent)) made by BPD that night. 
-->

For this project, we have sampled from the original 30-minte audio to produce 22 "snippets," typically of a few minutes encapsulating all "Signal 13" calls. "Signal 13" is police code for "officer needs assistance (urgent)," and it can be initiated either by the dispatcher or a police officer in the field.

These audio snippets can be found at the BCDL SoundCloud page: <a href="https://soundcloud.com/baltimorecitydatalab/sets">soundcloud.com/baltimorecitydatalab</a>.

#### Project Tasks

1. <strong> Identify Locations </strong> <br>
	Signal 13 calls include the location of the officer requesting assistance. However, these calls can be difficult to understand and transcribe. On SoundCloud, in the comments section of each snippet, we have attempted a first transcription of the location and time (if possible) for each Signal 13.  We hope that the open source community will provide feedback on our transcriptions and offer alternative suggestions for improvement. If you don't already have one, SoundCloud will ask you to set up a free account. The end goal is both to understand the events of April 27th and 28th a bit better, but also to build a log of correct location transcriptions to move us toward the development of a machine learning algorithm to aid future transcription efforts.

	As you will see on the SoundCloug page, for this project we have two playlists.  To enter comments, first go to the playlist view and click on the individual track.  Then, when the player shows up on the bottom of the window, click on the track name to go to the specific track page where commenting is permitted. Enter a comment by moving the cursor to the appropriate time in the recording and begin typing.

2.  <strong>Transcribe  </strong> <br>
	If there is anything else on these recordings that you find interesting, transcribe it!  Just add additional comments on the SoundCloud page for the relevant track.  (And, if you are particularly generous with your time, don't hesitate to download the full set of audio recordings from our data page and send your thoughts and additional transcription to us at BaltimoreCityDataLab@gmail.com.)

## Tips

* Most Signal 13 calls are concluded with a reference to the relevant police district. This reference helps to narrow the geographic area of your search. An overlay of the BPD district map can be found at <a href="https://www.google.com/maps/d/viewer?mid=zvHdn4L65G5k.kCi2PxFEsjkg&msa=0&hl=en&ie=UTF8&t=m&ll=39.284888,-76.620026&spn=0.255105,0.439453&z=11&source=embed"> Scan Batlimore</a>.

* Almost all Signal 13’s are eventually followed by a 10-32 call, which is police code for "sufficient units on scene." If you are having trouble understanding the address in the initial Signal 13 call, listen for the corresponding 10-32 call. These 10-32 calls can be issued anywhere between a minute to a few minutes after the initial Signal 13. Hearing the address in two different instances greatly improves your chance of hearing it correctly. 

* Scanbaltimore provides a <a href="http://scanbaltimore.com/"> table </a> that details all the code and signal calls made by BPD

* Listen to talk that follows each the Signal 13 call. Sometimes other officers will repeat the address. 

* Even if you don’t think you heard the address correctly, try searching for it on Google anyway. If nothing shows up, try various small phonetic variations after looking at the Google Map on scanbaltimore. Google will do its best to match your guess to its already existing catalogue of Baltimore street names, and you can narrow the range of possibilities if you have already identified the <a href="https://www.google.com/maps/d/viewer?mid=zvHdn4L65G5k.kCi2PxFEsjkg&msa=0&hl=en&ie=UTF8&t=m&ll=39.284888,-76.620026&spn=0.255105,0.439453&z=11&source=embed"> relevant police district</a>.

* Avoid searching common words that sound similar but you know are incorrect. They are likely to turn up irrelevant search results. 

* Listen for landmarks (shopping centers, parks, etc.). They are usually easier to identify and will refine your search. 

* Practice and repetition: Just by practicing active listening, you will get better at decoding the messages with time.  
