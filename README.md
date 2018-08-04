# Neighbourhood Map Project for FEND Udacity Scholarship Course

## Overview

The project is related to SPA (Single Page Application) developed with React library. 
The aim of the application is to display a map fetched thanks to Google Maps API
with five chosen locations of a given city. For my project i have chosen the city of Lisbon in Portugal.
When marker is clicked it should display infowindow with some additional data fetched from **third party API, 
in this case Random User Generator has been chosen https://randomuser.me/.**
The sidebar should appear, where filtering option is enabled.

## How to run the project

* first and foremost install node.js please
* after installing it, direct please to the neighbourhood map folder in your command line (remember to mention the whole path e.g. 
  cd Desktop\neighbourhood map\src)
* remember to install all dependecies by runnig the command npm install  
* start the development server with `npm start`
* navigate to http://localhost:3000

## Service Worker

It should be mentioned, that Service Worker is implemented in the production build mode. 
### How to run it ?
* enter 'npm run build' in your command line
* enter 'serve -s build' in your command line
* navigate to http://localhost:3000

