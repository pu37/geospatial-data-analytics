# Geospatial Data Analytics

Data analytics on geospatial database of a taxi cab firm, that contains pickup locations of several taxis along with real-time location data of their customer, to gain meaningful insights from the data.

## Phase-1

The phase-1 of the project focused on designing user defined functions that could be used to perform Spatial queries as below:

* Range query: Given a query rectangle R and a set of points P, find all the points within R.
* Range join query: Given a set of Rectangles R and a set of Points S, find all (Point, Rectangle) pairs such that the point is within the rectangle.
* Distance query: Given a point location P and distance D in km, find all points that lie within a distance D from P
* Distance join query: Given a set of Points S1 and a set of Points S2 and a distance D in km, find all (s1, s2) pairs such that s1 is within a distance D from s2 (i.e., s1 belongs to S1 and s2 belongs to S2).

## Phase-2

The phase-2 of the project focused on performing hotspot analysis as described below:

### Hot zone analysis
Find the number of customers within the boundary and use this information to obtain customer density and profitability for each boundary (hotspot).

### Hot cell analysis

Identify statistically significant hotspots by applying spatial statistics. In this task, Getis-Ord statistic was used.