# geocode_clustering
A project to generate geolocation information (e.g. City name, State name, coordinates) based on the postal codes from input data, and perform location clustering base on the coordinates. This is useful for logistics planning purpose to identify customers that are located close to each other, despite of the difference in their postal codes.

The code uses 
- pgeocode library to generate the geolocation information
- geopandas library to create a geometric list with the coordinates data for the map visualization purpose
- Python Folium Map for interactive map visualization

Access the work file in Google Colab here: 
https://colab.research.google.com/drive/1-byd23cgjXetTqlDtKM1tfLcAxjqMi4k#scrollTo=f8eELDvXfY63

<img width="266" height="178" alt="image" src="https://github.com/user-attachments/assets/bf7f1494-b262-43f5-ad3e-589d1745b803" />

