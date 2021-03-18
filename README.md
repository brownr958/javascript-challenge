# javascript-challenge

Level 1 of the assignment is under the folder: UFO-level-1. This contains the index.html file, 
a basic HTML web page that was created to display the dynamic table of UFO sightings. 

Using the UFO dataset that was provided in the form of an array of JavaScript objects, 
code was written in app.js that appends a table to the web page and then adds new rows of data for 
each UFO sighting.

Each UFO sighting will have data for date/time, city, state, country, shape, and comment.

A simple filter form was created using a date form where a user can select a date value from a dropdown menu.
A function called filterTable() was created using JavaScript that listens for events and searches through 
the date/time column to find rows that match user input and displays these to the webpage.

A function called resetTable() clears the body of the table, populates the dropdown menu with unique date 
values from the dataset and displays all data to the table as a starting point.
