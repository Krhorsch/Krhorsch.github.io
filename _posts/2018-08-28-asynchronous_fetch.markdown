---
layout: post
title:      "asynchronous fetch"
date:       2018-08-28 18:45:51 +0000
permalink:  asynchronous_fetch
---


THe Javascript fetch() function is asynchronous.  This means that the rest of the code in a file will continue to run while the fetch request is resolving.  One way to handle this in a react application is to write a simple if statement to account for state not being defined yet. 

`if(!this.props.reviews.reviews) {
      return (<div>Loading...</div>)
    }`
		
	Making sure to include a snippet of code similar to the one above in your render() will make sure that your application does not error out.
		
