<strong>AirTagIt, Location history for Apple AirTags. </strong><br>

Please note! This project is Work in Progress! I'm still writing the code! <br> At first this code is able to upload latitude en longitude coordinates to Google Spreadsheets and from there you can map it to Google Mapbox or any other program! <br> 

Also i'm trying to setup a script for Home Assistant, so that the Apple AirTags can be updated within Home Assistant! 

<br>

<strong>Description</strong><br>
Do you want to save a copy of ALL the locations that you're Apple AirTag has been? Its possible with AirTagIt! 

Normally you can only see the current location of the Apple AirTag in the 'Find My' app without any location history. 
AirTagIt makes is possible to automatically send locations to Google Spreadsheet and MapBox, so you can see all location history!
You will see a dot on a map everytime the Apple AirTag updated his location.  

**How does it work?**

Just let the script run, and it will update the longitude en latitude coordinates everytime it changes via a Google App script to a Google Spreadsheet!
From there MapBox can be connected. https://www.mapbox.com/impact-tools/sheet-mapper

**Setting up:**

_Create Google Spreadsheet_ <br>
Create a Google Spreadsheet with the following information on row 1<br>
Battery - Date - Latitude - Longitude 


- Google App script
- Google Spreadsheets
- (free) mapbox account
- MacOs Big Sur

**How To Run the script**
1. Download AirTag it: https://github.com/PrutsMeneer/AirTagIt/archive/refs/heads/main.zip
2. Open terminal and navigate to ./AirTagIt.sh


More coming soon!
