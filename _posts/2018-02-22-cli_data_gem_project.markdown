---
layout: post
title:      "CLI Data Gem Project"
date:       2018-02-22 14:42:01 +0000
permalink:  cli_data_gem_project
---


When I first started to tackle the project I was preoccupied with the scraping that needed to be done in order to get the data I needed.  This resulted in me making a funtioning CLI that worked just as a wanted, buuut after sleeping on it I realized I wasn't using objects.  I was scraping different parts of the website separately and then 'zippering' them together.  This 'zippering' as Avi calls it makes it difficult to expand on functionality in the future.  I was pretty happy with myself for figuring out my mistake before submitting.  What needed to be done was create a new Class and give instances of that class attributes through only one scrape of my source website.

The most notable 'lesson' I learned from this project was the idea of 'separation of concern'.  In talking with a tech coach about my gem he used this phrase and although I am sure I have heard it before it really had substance now.  I was able to run my CLI and it had the desired outcomes, but the code behind the scenes wasn't positioned in necessarily the most appropriate classes.  So as I move forward I will continue to ask, does this Class need to know about this method?
