---
layout: post
date: '2018-02-20 23:05 +0100'
author: Kyle
published: true
categories: 'Honours Project'
excerpt: ''
meta: 'Honours Project Strathclyde Glasgow Software Engineering'
---
**Progress:**
I have finally got a Working Fusion Speech to Text Pipeline Stage, this took alot longer than I had hoped. This is due to issues with the Google Client libraries which I was using for the API. None the less it is now working and it allows me to make a request to the Fusion backend and retrieve a transcribed result from Google Speech to Text API. These results can then be sent downstream to other Query stages.

**Problems:**
I had some problems with dependancies within the existing Fusion codebase, in particular with dependecies needed for Google Client Libraries, one way I could have got round this would be to shadow certain dependencies, however, I felt like this could be very complex and time consuming. To get round the problem I wrote my own classes which contact the API using the Unirest library which helps with making HTTP requests.

**Plans for next week:**
I still need to modify the existing Fusion Searchhub Ui to include a button to capture audio so it can be sent to the backend.
I hope to bring add the Google Natural Language Processing API into Fusion along with my Speech to Text Pipeline, this will allow for the enrichment of results. 

