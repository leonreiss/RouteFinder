# Overview

Te "Navigation.py" implements a route finding application using Streamlit and OSMnx. It allows the user to enter a start and destination address, 
select a map style and then calculate the shortest driving route between the two locations. The code first downloads the road network data for 
the specified location using OSMnx and then calculates the route using the NetworkX shortest path algorithm. 
The route is visualised on a Folium map, where different map styles such as Satellite, OpenStreetMap or Stamen Terrain can be selected. 
In addition, the map contains markers for the start and end points, a polyline for clear visualisation of the route and a l
ayer control for switching between different map functions.

See UI below:
<img width="1093" alt="Screenshot 2025-01-31 at 14 56 05" src="https://github.com/user-attachments/assets/d71839e1-0543-4757-844b-2c8f7894ae98" />

