# Event Survey Analysis

# Introduction

This project analyses 716 responses to a survey conducted by an organisation who organised an event held in Scotland. The survey was conducted after the event and seeks to understand the background of attendees and their experience of all aspects of the event. For client privacy purposes, I have used the Synthpop package to synthesise all of the data. 

# Requirements

Libraries: <br>

Tidyverse <br>
Janitor <br>
Keyring <br>
Gmapsdistance 

This project utilises the Google Distance Matrix API which provides driving distances between two specified locations more information is available at https://developers.google.com/maps/documentation/distance-matrix/start 
Accessing the API requires a key which can be set up using the link above. I have used the keyring library to access my key which is stored locally. 
