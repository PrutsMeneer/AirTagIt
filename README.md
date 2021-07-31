# AirTagIt, Location history for AirTags. 
Do you want to save a copy of ALL the locations that you're AirTag has been? Its possible with AirTagIt! 

Normally you can only see the current location of the AirTag in the 'Find My' app and no location history. 
AirTagIt makes is possible to automatically send locations to Google Spreadsheet and MapBox, so you can see all location history!
You will see a dot on a map everytime the AirTag updated his location. 

**How does it work?**

Just let the script run, and it will update the longitude en latitude coordinates everytime it changes via a Google App script to a Google Spreadsheet!
From there MapBox can be connected. https://www.mapbox.com/impact-tools/sheet-mapper

**Setting up:**

_Create Google Spreadsheet_
Create a Google Spreadsheet with the following information on row 1
Battery - Date - Latitude - Longitude 


- Google App script
- Google Spreadsheets
- (free) mapbox account
- MacOs Big Sur

**How To Run the script**
1. Download AirTag it: https://github.com/PrutsMeneer/AirTagIt/archive/refs/heads/main.zip
2. Open terminal and navigate to ./AirTagIt.sh
