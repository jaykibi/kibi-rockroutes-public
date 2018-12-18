
# Beginners’ Guide to Rock Climbing in Colorado

**<a href="https://sites.google.com/tamu.edu/rockroutes/home?authuser=1">Click here to go to the Rock Route website</a>**

**<a href="https://youtu.be/6yAllPr3bQk">Click here for Rock Route's Presentation VIDEO</a>**

**<a href="https://github.tamu.edu/GEOG478Project/RockRoutesCO/blob/master/REPORT/Rock%20Routes%20Slides.pdf">Click here for Rock Route's Presentation SLIDESHOW</a>**

![alt text](https://github.tamu.edu/GEOG478Project/RockRoutesCO/blob/master/REPORT/pictures/1.JPG)


## Created by: Adilah Amalia, Liliana Coronado, Martin Portillo, Raquibbi Samaun

**Goal - what were we planning to do?**

The goal of this project is to provide a quick visual guide that can be used by beginner rock climbers to browse, find, and navigate to a rock climbing site or route in Colorado.

We want to grant fast access and a clean look which focuses mainly on providing the user with routes that fit the user’s preferences. After a route has been picked and the user would like to navigate to it, he/she can go to our “Navigation to Routes” page, click on their specific site, and Google Maps will take them there. The website will also have a page on the introduction information on rock climbing; defining grades, types, equipments, etc..

**Motivation - why were we planning to do it, for whom, to solve what problem?**

Mountain Project is a website about climbing by REI Co-op which lets the user to find routes based on their preferences. The choices provided by Mountain Project is a lot and can be daunting for beginner climbers to choose from. It also does not show where the location of the routes are, the user has to go to another page to find the coordinates of the route. This makes it difficult for a user on the move to check which routes are nearby on MP.

RockRoutes is created for the user - beginner rock climbers - to easily find a climbing site or route from looking at a map. If the user is on a move and wants to see what appropriate routes are near them, they can do that quickly. Our website has also been filtered to provide only beginner difficulty levels (grades) for both rock climbing (5.3 to 5.8) and bouldering (V0 to V2), and to only show the best rated routes to ensure good experience for someone who just started climbing.

**Approach/Methods/Data:**

Architecture: our website was coded mainly with the use of HTML with JavaScript elements. The main premise of our code was to link a map view with shapefiles created within ArcGIS and uploaded to their online servers as a service. 

The building procedure is as follows:
 Figure out what data the user, in this case a beginner rock climber, needed.
We came to a consensus of limiting the difficulty of rock grades to include within our data, which was obtained on the Mountain Project website. 
Once a consensus was made on what to include, we sectioned off the data and began inputting into a shared spreadsheet. 
Each of us were in charge of a specific difficulty level in this case. 
Upon completion of the spreadsheet, that data was input into an attribute table within ArcGIS. 
The attribute table was then referenced to create the shapefiles that were needed to visualize the data.
In this case, we used fields we created within the spreadsheet called “lat” and “long” which corresponded to different latitudes and longitudes respectively on the map.
 Once the shapefiles were created, we uploaded them to ArcGIS online and used them as hosted feature service layers.
We did this so we could “call” on them later in our code. 
 Once the shapefiles were uploaded and hosted, we started the coding process. 
We used HTML and JavaScript for this project.
 When the coding was complete we embedded onto our website and started debugging. 
There were issues with the code in regards to nomenclature and that some of the desired events were not happening on the client. This issue was eventually debugged.
 The size and view of the map was then changed on the website and it was finally published. 

**Technology & API:**

We used various technologies to include: Google Sites, ArcGIS online, ArcMap, and ArcGIS Web App Builder. The different APIs used in this project can all be found in the API reference of the ArcGIS for Developers page. The different APIs used in our code are as follows (screenshots from actual code):

Map: 

![alt text](https://github.tamu.edu/GEOG478Project/RockRoutesCO/blob/master/REPORT/pictures/2.JPG)

MapView: 

![alt text](https://github.tamu.edu/GEOG478Project/RockRoutesCO/blob/master/REPORT/pictures/3.JPG)

FeatureLayer:

![alt text](https://github.tamu.edu/GEOG478Project/RockRoutesCO/blob/master/REPORT/pictures/4.JPG)

LayerList:

![alt text](https://github.tamu.edu/GEOG478Project/RockRoutesCO/blob/master/REPORT/pictures/5.JPG)

PopupTemplate:

![alt text](https://github.tamu.edu/GEOG478Project/RockRoutesCO/blob/master/REPORT/pictures/6.JPG)

**Participation within the project:**

There were specific niches within our group, the coding was completed with contributions from everyone. The presentation & video was put together by Martin, the main data collection was completed by both Adilah and Liliana, while the shapefiles were created and hosted by Raquibbi. 


**Results - what did we achieve?**

After collecting the data and figuring out how to write the HTML code for our project, our team was able to create a very useful website for beginner rock climbers. Our map has the ability of choosing which routes the user wants to see. There is also a custom google map on the website which users can use to navigate. A beginners guideline to rock climbing is also included on the website in order to provide a short background and help out the users. Overall, we were able to create a very useful website that will enhance the rock climbing experience in Colorado. 

**Discussion/Conclusion:**

We had set out to create a clean-looking visual website that helps a user to find beginners level rock climbing and bouldering routes quickly. We wanted for the user to input their preferences to our site and return them a map with their preferred choices, but we did not fully achieve that.

Since our Javascript coding experience did not allow us to achieve what we wanted, we created our maps to have different layers based on the level of difficulties that the users can choose from. By turning on and off the layers, they can see the range of routes shown on the map that they can choose from. When they click on a dot, a pop up will show all the info about the route. The navigation page serves almost the same function, with the added ability to take the users to Google Maps where they can navigate themselves to the route of their choice without putting in any complicated coordinates. We also provided a page that shows the difference between rock climbing and bouldering, as well as the definition of a “grade”.

The final product of our works very well and the website is easy to go through. Users are able to browse through whichever grade they want and see the information on the routes they picked. Not only is the website very easy to follow, it is also simple and visually appealing. 
