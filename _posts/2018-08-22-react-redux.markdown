---
layout: post
title:      "React-Redux"
date:       2018-08-22 20:29:52 +0000
permalink:  react-redux
---


In a react/redux application, if you are fetching data that needs to be displayed on the page immediately you want to make sure to trigger the action creator inside the componentDidMount() lifecycle method. The general flow for a react redux app is:

User triggers an event ie: onClick, onSubmit.  Inside an event handler method an action creator then gets called.  After the action creator has been called it gets to the reducers and runs through all of them until the case that matched the action.type.  Following this is there is an update to state the dom rerenders.

