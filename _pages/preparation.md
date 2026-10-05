---
permalink: /preparation/
title: "Preparation"
---

# Hello Participants in the Workshop!

**Making accounts** 

We are looking forward to our time together 19-23 October 2026. We need you to do a make a couple accounts at : 

* [posit.cloud](https://login.posit.cloud/login?redirect=%2Foauth%2Fauthorize%3Fredirect_uri%3Dhttps%253A%252F%252Fposit.cloud%252Flogin%26client_id%3Dposit-cloud%26response_type%3Dcode%26show_auth%3D0&product=cloud)  
* [Transkribus](https://www.transkribus.org/)

Please do this in advance of the first session. 

**Optional part:** 

We will also be using eScriptorium to a lesser extent. It is open source, but requires you

1. to download and install it on the command line 
2. to install Docker 
3. to have a computer with minimum 8GB of memory (16+ for training) and
4. to be quite patient. 
   
If you are feeling ambitious and would like to try an open source HTR on your own computer, also get that started before the week begins. We will have a clinic one of the days for help doing that, but it is time consuming and technically more demanding. The clearest instructions for this are for a [Mac from UPenn](https://www.library.upenn.edu/rdds/work/escriptorium-mac).  If you have a PC or Linux, use the instructions for installing with [Docker from Github](https://github.com/UB-Mannheim/escriptorium/tree/develop).  

Using the UPenn tutorial was somewhat straightforward, requiring some debugging with chatGPT. 

Here is how chatGPT summarized the issues, DJW encountered: 

_"The UPenn tutorial worked in broad terms, but there were several configuration/version mismatches with the current eScriptorium Docker images. On Apple Silicon, the images required AMD64 emulation; the web container’s health check was also broken because it called curl, which was not installed, and checked a /health endpoint that returned 404. In addition, nginx initially cached an incorrect Docker address for the web service, producing 502 Bad Gateway errors until nginx was restarted. Finally, Docker Desktop’s virtual disk filled up even though the Mac had ample free storage, causing PostgreSQL to enter a recovery loop and eScriptorium to return 500 errors; increasing Docker’s disk allocation resolved that issue."_

**Background reading**

Our suggestion for reading for the week is to take a look at the [new book on ATR](https://pub.uni-bielefeld.de/record/3017559) (Bielefeld UP) published open access by Schonhardt et al. 

Looking forward to meeting you!

