# Folium_TIF

Folium is a cool Python wrapper for the Leaflet.js framework. Decided to use this to do a more lightweight and shareable mapping visualization of all capture districts in the City of Detroit. Ends with a cool .html map that is navigable and searchable for the most numberous type of capture projects - Brownfield Redevelopment.

https://python-visualization.github.io/folium/

What this does:

    1 - Uses TIFCalc database as generated in the TIF Calc repository
    2 - Calculates Base, Taxable and Capture values for DBRA, LDFA, EMWCIA and Detroit DDA projects.
    3 - LEFT Joins ParcelDetail to the Parcel information provided by Assessing and supplied through the Open Data Portal
    4 - Dissolves the joined geographic information by plan to create either a single Multipolygon or Polygon.
    5 - Writes each authority's data to Shapefile and GeoJson.
    6 - Uses GeoJson to read into Folium, saves resulting map as HTML.
  
