---
layout: post
title: React-Native - Weather App
date: 2023-06-05 13:32:20 +0300
description: React-Native & Expo Project - Weather App. # Add post description (optional)
img: expo-4.png # Add image post (optional)
fig-caption: # Add figcaption (optional)
tags: [React-Native]
---

## Overview



This project is a basic intro into React Native, it creates a simple weather app based off the Open-Weather API. 
The App shows 3 simple screens controlled by a tabbed navigation bar at the bottom of the screen. 
The first screen displays the current weather. It changes the background colour, weather icon, weather desciption and a fun message relating to the weather type.
The second screen shows a `flat list` of the weather forecast for the next 5 days (in 3 hour time segments).
The third screen uses the native geolocation information from the Mobile device and shows some related information about the device's curren tocation (note: simulator defaults to San Fran in screenshots)


## Code Repo
[https://github.com/kiwiFella/weatherApp](https://github.com/kiwiFella/weatherApp)
 


## What I learnt during this project:
--------------------
- Installing mobile simulator on a Mac
- An introduction to React-Native and the Expo project
- Fetching API's and using `useState` & `useEffect` to output dynamic data
- Accessing mobile device's native geoloaction system, requesting permission and managing errors if permission not granted.
- Using Expo to generate both Android and iOS apps ready for app stores.

## Screenshots

![Screenshot-1]({{site.baseurl}}/assets/img/expo-1/1.current.png)
>Screenshot of the first screen showing the current weather - background, icon and messages change depending on the weather API's wetaher type (eg. Raining, suny, windy, snow, etc).

![Screenshot-2]({{site.baseurl}}/assets/img/expo-1/2.forecast.png)
>Screenshot of the second screen - a five day forcast at 3 hour intervals - uses a react-native flat list component and updates icon to match the weather type.

![Screenshot-3]({{site.baseurl}}/assets/img/expo-1/3.geo.png)
>Screenshot of the third screen asking the user for app permission to access device geolocation.

![Screenshot-4]({{site.baseurl}}/assets/img/expo-1/4.city.png)
>Screenshot of third screen showing location information (note: default simulator location is San Francisco).


