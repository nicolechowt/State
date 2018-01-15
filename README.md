# Project 1 - {State - A Health Tracker}

## Project Scope
State is a web-application that combines manually entered inputs as well as API data (weather and Fitbit) to submit a comprehensive user profile to the database. The application allows users to log and track their symptoms in hopes to find a pattern or commonality between episodes. 

## Demo
To use the application, the user must sign up through our sign up page.
![Sign Up]<img src="https://thumbs.gfycat.com/PoliteDigitalAmoeba-size_restricted.gif" width="500" height="400" />

Once registered, our database will now recognize this user and save his/her information under the unique user ID.
![Firebase Auth](https://github.com/nicolechowt/State/blob/master/readmefiles/firebaseAuth.jpg)

If the user has a Fitbit wearable, user may log in to grant read access to our application. User can then sync their health and fitness information with our database. Doing so will help our application to better understand the user's condition and monitor any unusual biomarker trends. 

If a symptom is experienced, user can go to the calendar page and manually add an entry to log his/her symptom. Upon the submitting this form, our application will make an AJAX call to the weather API to obtain the weather information in the area. The weather in the area could have a correlation to certain health issues.
![Data Entry Demo]<img src="https://thumbs.gfycat.com/PitifulHandmadeKob-size_restricted.gif" width="500" height="400" />

At anytime, the user may go back to a previous day to review the symptoms experienced. We used D3 to graph and visualize the data.
![Historical Data]<img src="https://thumbs.gfycat.com/VigorousSociableGrebe-size_restricted.gif" width="500" height="400" />


## Live Link
https://nicolechowt.github.io/State/index.html

## Current Features
-Make AJAX calls to Fitbit API and store Fitbit data on Firebase data structure
-Make AJAX calls to Wunderground Weather API Store weather/climate conditions on Firebase data structure
-Allow users to input symptoms on any given day
-Allow users to go back to any date in the past to review symptoms
-Perform analysis and inform the user whether it thinks there has been any ties between this episode and a previous episode. 
-Utilize D3 to generate graphs for both doctors and users

## Features for next iteration
-Social network/support group
-Allow users to search with a keyword or hashtag a specific symptom experienced
-Geolocation/google maps API
-Using Google Maps API to allow users to “anonymously” report an illness at a given location. Display such data on a heat map
-Twitter API
-Incorporating Twitter API for trending keywords
-Display user’s live HR 

## APIs Used
-Weather
-Fitbit

##Libraries
-Moment.js
-jquery
-calendar.js
-d3
-Bootstrap

## Technologies Used
firebase

