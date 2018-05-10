---
layout: project
type: project
image: images/opqlogoonblue.png
title: Open Power Quality
permalink: projects/opq
# All dates must be YYYY-MM-DD format!
date: 2018-03-30
labels:
  - React
  - Meteor
summary: Implemented UI components in React for a web application called OPQView
---
## Introduction
For my final project in ICS 314, I had the opportunity to join Professor Philip Johnson and his developer team on the Open Power Quality Project (OPQ). The rise of renewable energy sources presents new problems in power quality and OPQ provides a way to monitor these issues and collect the data needed to improve society's transition into renewables. The OPQ system is made up of four hardware and software components: OPQ Box, OPQ Makai, OPQ Mauka and OPQ View. My tasks fall under OPQ View, which is the web application that helps visualize the data in a user friendly way.  

## So far...
<br>
<img class="ui image" src="{{ site.baseurl }}/images/edit-component.png">

The first issue I worked on for this project was implementing an edit page for the opq boxes. The edit page allows users to modify the meta data for the boxes that they own. This component allows the name, description, calibration constant, and locations to be changed. As users shouldn't have full access to the database, the [insecure package](https://atmospherejs.com/meteor/insecure) is disabled for OPQView. In order to write to the database, I learned what [meteor methods](https://guide.meteor.com/methods.html) are and how to use them. After implementing this, the representation of location data has been changed and I am currently working on updating the edit page to use the new representation. 

The alert manager allows users to configure "Alerts". Alerts are user-configurable representations for a set of events that the user is interested in. Currently the alert manager page features preset alerts where the user can select a time interval (start and end day) and press the submit button to find all events specified by the alert. 
<img class="ui fluid left floated medium image" src="{{ site.baseurl }}/images/alerts_manager.png">

<br>
## VIP Poster Session
<br>
<img class="ui left floated medium image" src="{{ site.baseurl }}/images/vip-poster.jpg">
In early April of 2018, OPQ was presented at the Vertically Integrated Projects (VIP) Poster Session at UH Manoa. I assisted in putting together the poster and presenting it. It allowed me to build my communication skills and was my first experience participating in an undegraduate showcase. 
