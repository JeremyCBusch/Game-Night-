# Game-Night


This program is a mobile app that connects people based on their interests in games or sports that appeal to their liking. It connects to a Google Firebase to give real time event updates and chat features.  

The purpose of writing this software was to be able to encourage those who enjoy playing board games and small sports to connect with more people and to get out of their comfort zone. I also wanted to learn more about how to connect a mobile app to Firebase.  

{Provide a link to your YouTube demonstration.  It should be a 4-5 minute demo of the software running, a walkthrough of the code, and a view of the cloud database.}

[Software Demo Video]https://vimeo.com/634159818/b6ba7912f0

# Cloud Database

{Describe the cloud database you are using.}
I am using Google Firebase's Realtime database

{Describe the structure of the database that you created.}
There are two main documents in the databse. Events, which houses the description of the game event, the person who started the event, the location, and the date that it was created, which acts as a primary key. The other document is event chats. There is a chat for every corresponding, event where people can message to each other to make plans.

# Development Environment

Android Studio

{Describe the programming language that you used and any libraries.}
I used REact NAtive and the expo satus bar library. This is an app that allows my iphone to connect to a live server of the code that i am running on my machine. This can help with live bug fixing and a more intuitive testing of the app.

# Useful Websites

{Make a list of websites that you found helpful in this project}
* [RNFirebase.io] https://rnfirebase.io/database/usage

# Future Work

{Make a list of things that you need to fix, improve, and add in the future.}
* I need to add delete features for events that have already past to save space
* I would love to make the UI much more user friendly
* Currently sending messages over the app is functioning so i would like to add that
