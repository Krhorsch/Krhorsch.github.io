---
layout: post
title:      "jQuery front-end"
date:       2018-07-19 23:38:52 +0000
permalink:  jquery_front-end
---


For this project I had to create API's using the 'active_model_serializers' gem and then make use of the json responses to change data in the dom without a page refresh.  After installing the gem I used the command line to generate 2 seperate serializers.  Once these were  created I adjusted the attributes I wanted to make use of in both classes.

I used jQuery get requests to hit the API's and the get request then takes in a callback function which is where you handle what you would like to do with the data from the API.  

One of the best takeaways I had from this project is when I was dealing with a reponse continuing to happen on every click event: to resolve this I changed $(".userbeers").on("click", function(e) { } to $(".userbeers").one("click", function(e) { } which only let the callback function fire once and gave me the desired result.
