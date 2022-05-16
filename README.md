# Mapping_Earthquakes
## Overview
  The Disaster Reporting Network provides data-driven storytelling on natural disasters around the world. An interactive map was created to display earthquake data from around the world. The hope is that this interactive site will create "buzz" about the Disaster Reporting Network. 

## Results
  GeoJSON data from the US Geological Survey website was traversed and earthquake data was retrieved using JavaScript, D3, and leaflet. The data was then plotted on a Mapbox map through API requests. Using Mapbox, three map styles were added so that users could change between street, satellite, and night navigation map styles. The default was set to street, so this is what users will first see when the website is loaded. 
  There were also three different layers added to this map. The first shows circle markers for all recent earthquakes within the last 7 days. The circles are color-coded based on the magnitude of the earthquake, and the size of the circles depends on the magnitude as well. The second layer shows all tectonic plate data. The last layer shows users all major earthquakes (earthquakes with a magnitude greater than 4.5) with similar color coding and circle sizes.
  For all of the earthquakes on this map, users can click on any circle marker and a pop-up will display that shows the magnitude and location data of each earthquake. 
