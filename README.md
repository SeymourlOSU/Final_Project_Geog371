# Final_Project_Geog371

Project title: Parks in Benton County and Corvallis

Project description: An update of the original story map project with addtional text, images, links, and new formatting. 

 The Goal of this project is to introudce the area of Benton County within Oregon, then continue by going a level deeper each scene, type; management; playground; and finally dog access. This is all to give a better understanding about parks because its not known by everyone that there are different people managing all the parks in the county and that there is differen't designations and rules for each 

The core of the system architecture is based on mapbox basemap styles and built up from there, adding geojson features over them, with a javascript story map laid ontop of that. This was done this way becasue it was the same as the original story map that was created and it was the simiplist way i could think to do it , (2) the main functions of your web map using either a screenshot of the web map or a code snippet of the function, and a concomitant description. The main fuction of the web page is the story map container on the left hand side of the screen that can be scrolled through to see more images and different basemaps displaying different information. 
![capture](https://user-images.githubusercontent.com/32307321/33700232-d96127d0-dacc-11e7-87c6-f139adc56f68.PNG)

Reflection on the course of designing your web map: In reflection, at the end of everything i realized that manually recreating my Shapefiles in something like GeoJson.io and using 1 basemap for my whole story would have made more sense, be easier to code, loaded quicker, etc. but i was having issues with my shapefiles and making them into mapbox tilesets was easier at time, but harder in retrospect.

The data i got for this was from Benton Counties Gis data directory (http://gis.co.benton.or.us/gisdata/) and was further manipulated by me in ArcMap. 

Libraries (e.g., Leaflet) and Web Services (e.g., github, basemap) in use
Throughout the course of this project I used Leaflet sytlesheets  , Mapbox basemaps, Bo Zhao's https://github.com/jakobzhao for help, and my own respository to host the HTML and associated files 

Credit: leaflet, mapbox, github.

Acknowledgement: I used code snippets  https://github.com/jakobzhao and https://github.com/hannahfriedrich to help create this map


