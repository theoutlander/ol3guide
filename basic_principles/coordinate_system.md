# Coordinate System

<img src='http://upload.wikimedia.org/wikipedia/commons/2/2c/3D_coordinate_system.svg'>

The ***Geographical Coordinate System*** follows the same principles of the ***Cartesian Coordinate System***. It allows us to uniquely identify each location on the Earth via a set of numbers. These numbers are expressed in the order - Longitude, Latitude, Elevation.

# Coordinates

<img src='http://upload.wikimedia.org/wikipedia/commons/6/62/Latitude_and_Longitude_of_the_Earth.svg'>

***Longitude*** is a geographic coordinate that specifies the east-west position of a point on the earth's surface.

***Latitude*** is a geographic coordinate that specifies the north-south position of a point on the earth's surface.

***Elevation*** is a geographic coordinate that specifies the vertical distance from the sea-level (in meters?).

In 2D space, we will only be using Longitude and Latitude.

The **ol.Coordinate** definition represents a coordinate which is simply an alias for **Array of Numbers**.

# Longitude-Latitude



We've usually referenced Geographical Coordinates as (Latitude,Longitude) and the axis of Cartesian Coordinate's as (X,Y). If you look closely, you'll notice that the Longtiude is actually on the X axis where as the Latitude is on the Y axis. Since the map is in a Cartisian Coordinate System, we want to be able to think in terms of (X,Y). In order to standardize, we reference Geographical Coordinates as (Longitude,Latitude) which is synonymous to (X,Y).
