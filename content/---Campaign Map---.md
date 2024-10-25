```leaflet
id: faerun-map
image: [[Faerun Map.jpg]]

### 1. Measure pixels between start and finish of measure board
###     eg 1820px for 500miles
### 2. scale = 1820/500 
### 3. Bounds second line = [mapImageWidth / scale , mapImageHeight / scale]
### imageWidthInPixels
bounds:
    - [0, 0]
    - [1813, 2802] 
scale: 1 

### longitude is pixels from bottom left to right
### latitude is pixels from bottom left to top
lat: 1300 ### To center the map, make this half of the map width.  
long: 1200 ### To center the map, make this half of the map height.  

### Zoom
maxZoom: 3
defaultZoom: 0
minZoom: -1

### Frame dimensions
height: 900px ### Size of the leaflet embed in px on your screen  
width: 100% ### Size of the leaflet embed in your note  

unit: miles 
recenter: true  
darkmode: false ### marker  
```