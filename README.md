# Mapping Earthquakes
## Overview of Project
> Basil and Sadhana like how you created your earthquake map with two different maps and the earthquake overlay. Now, Basil and Sadhana would like to see the earthquake data in relation to the tectonic plates’ location on the earth, and they would like to see all the earthquakes with a magnitude greater than 4.5 on the map, and they would like to see the data on a third map.

1. ***Deliverable 1***: Add Tectonic Plate Data
2. ***Deliverable 2***: Add Major Earthquake Data
3. ***Deliverable 3***: Add an Additional Map
4. ***Deliverable 4***: A written report on the Mapping Earthquakes analysis [`README.md`](https://github.com/emmanuelmartinezs/Mapping_Earthquakes/). 
 

## Resources

* Data Source: `tectonic_plate_starter_logic.js`, `tectonic_plate_starter_logic.js`, `tectonic_plate_starter_logic.js` and `index.html`
* Data Tools: JavaScript, JSON, GeoJSON and IO (Web Server)
* Software: ES6+, ECMAScript and Visual Studio Code 1.50.0

# Deliverable 1:  
## Add Tectonic Plate Data
Using your knowledge of JavaScript, Leaflet.js, and geoJSON data, you’ll add tectonic plate data using `d3.json()`, add the data using the `geoJSON()` layer, set the tectonic plate `LineString` data to stand out on the map, and add the tectonic plate data to the overlay object with the earthquake data.

### Results with detail analysis:

1. **The tectonic plate data is added as a second layer group.**
// 1. Add a 2nd layer group for the tectonic plate data.
let allEarthquakes = new L.LayerGroup();
let tectonicPlates = new L.LayerGroup();
![name-of-you-image](https://github.com/SLCunningham21/Mapping_Earthquakes-/blob/main/Resources/Images/1.1.JPG)

2. **The tectonic plate data is added to the overlay object.**

![name-of-you-image](https://github.com/SLCunningham21/Mapping_Earthquakes-/blob/main/Resources/Images/1.2.JPG)

3. **Use d3.json to make a call to get our Tectonic Plate geoJSON data.**
![name-of-you-image](https://github.com/SLCunningham21/Mapping_Earthquakes-/blob/main/Resources/Images/1.3.JPG)

4. **The earthquake data and tectonic plate data displayed on the map when the page loads.**
![name-of-you-image](https://github.com/SLCunningham21/Mapping_Earthquakes-/blob/main/Resources/Images/1.4.JPG)

# Deliverable 2:  
## Add Major Earthquake Data

1. The major earthquake data is added as a third layer group.
2. The major earthquake data is added to the overlay object.
3. The `d3.json()` callback is working and does the following:
  - Sets the color and diameter of each earthquake.
  - The major earthquake data is passed to the `geoJSON()` layer.
  - The **geoJSON()** layer creates a circle for each major earthquake, and adds a popup for each circle to display the magnitude and location of the earthquake
  - The major earthquake layer group variable is added to the map
4. All the earthquake data and tectonic plate data are displayed on the map when the page loads and the datasets can be toggled on or off.

 
### Results with detail analysis:

1. **The major earthquake data is added as a third layer group.**
![name-of-you-image](https://github.com/SLCunningham21/Mapping_Earthquakes-/blob/main/Resources/Images/2.1.JPG)

2. **The major earthquake data is added to the overlay object.**
![name-of-you-image](https://github.com/SLCunningham21/Mapping_Earthquakes-/blob/main/Resources/Images/2.2.JPG)

3. **The `d3.json()` callback is working and does the following:**
![name-of-you-image](https://github.com/SLCunningham21/Mapping_Earthquakes-/blob/main/Resources/Images/2.3.JPG)

4. **All the earthquake data and tectonic plate data are displayed on the map when the page loads and the datasets can be toggled on or off.**
![name-of-you-image](https://github.com/SLCunningham21/Mapping_Earthquakes-/blob/main/Resources/Images/2.4.JPG)

# Deliverable 3:  
## Add an Additional Map
1. A third map tile layer is created.
2. The third map is added to the overlay object.
3. All the earthquake data and tectonic plate data are displayed on the all maps of the webpage.

 
### Results with detail analysis:

1. **A third map tile layer is created.**

![name-of-you-image](https://github.com/SLCunningham21/Mapping_Earthquakes-/blob/main/Resources/Images/3.1.1.JPG)

2. **The third map is added to the overlay object.**

![name-of-you-image](https://github.com/SLCunningham21/Mapping_Earthquakes-/blob/main/Resources/Images/3.2.JPG)

3. **All the earthquake data and tectonic plate data are displayed on the all maps of the webpage.**

![name-of-you-image](https://github.com/SLCunningham21/Mapping_Earthquakes-/blob/main/Resources/Images/3.3.JPG)
