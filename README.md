**City Transportation Arrangement System**

A C++ implementation of a city transportation arrangement system that uses Graph Theory and the Floyd–Warshall Shortest Path Algorithm to connect users with the nearest available cab. The project models a city as a weighted graph and provides an efficient way to estimate travel routes and fares.

The project represents a city as a weighted graph , where:
**Vertices (Nodes)** represent different locations in the city.
**Edges** represent roads connecting locations.
**Edge weights** represent distance between locations.

The system allows a user to select their current location and destination, then:

1- Finds the nearest available cab to the user.

2- Computes the shortest travel path.

3- Calculates the travel distance.

4- Estimates the fare.

5- Displays all relevant trip details.

**Features**
**1) Nearest Cab Detection**
Maintains the locations of available cabs.
Identifies the cab with the minimum distance from the user.

**2) Shortest Path Calculation**
Uses the Floyd–Warshall Algorithm to compute the shortest distance between every pair of locations.
Provides fast route lookup once preprocessing is complete.

**3) User Input**
Accepts the user's current location.
Accepts the desired destination.

**4)Fare Estimation**
Calculates total travel distance.
Estimates trip cost using a fixed fare per unit distance.

**Floyd–Warshall Algorithm**
The project uses the Floyd–Warshall Algorithm, an all-pairs shortest path algorithm.

Computes the shortest distance between every pair of vertices.
Makes route queries extremely fast after preprocessing.
Well suited for small to medium-sized city maps.






