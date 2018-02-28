---
layout: post
date: '2018-2-28 17:05 +0100'
author: Kyle
published: true
categories: 'Honours Project'
excerpt: ''
meta: 'Honours Project Strathclyde Glasgow Software Engineering'
---
In order to demo the Speech to Text Pipeline, a frontend UI was required. I have now created a basic UI which can send requests to the Fusion backend and display the search results. The front end can also capture Audio, I now need to work on the code to convert this audio to the correct format to send to the backend to be processed by the Google API.

*Problems*
I was hoping to have a server by now for deployment and in order to work out any issues, however this has not happened. Therefore I have to do all development locally. I was having issues with Cross-Origin Resource Sharing, as the Angular UI and Fusion Backend run on different ports and Chrome is trying to protect against cross site scripting. Thankfuly firefox has an addon which allows you to get around this. 

![The Angular UI](kylemccann.github.io/images/Screen Shot 2018-02-28 at 15.39.49.png)



