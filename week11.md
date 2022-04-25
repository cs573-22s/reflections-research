###### Marcus Chalmers 
###### CS573
###### 3/28/2022
###### Reflection Week 11

["Visual Exploration of Sparse Traffic Trajectory Data"](https://ieeexplore.ieee.org/document/6876014)

This paper focuses on traffic data collected over half a year. As the paper mentions, traffic data
can be measured in many different ways: event-based, location-based, and movement-based. Event-based 
data might consist of data taken by hand at specific incidents and locations. Location-based data consists
mostly of roadside detectors responsible for collecting vehicle data in one area. Finally, movement-based
data is what might be more expected where GPS or other larger picture software can detect vehicles
individually or the location of busses and cabs in a given city. This paper uses a combination of movement
and location data to collect all types of cars (not just cabs/busses) at specific locations around the city.
The researchers took this data and created a directed graph or map of each node showing the busyness
and average speed at a given time. The visualizations in this paper were intriguing because of what they had to
work with. This rather disconnected set of traffic data didn't allow you to definitively tell where anyone's car 
was going, only the number of vehicles in a given place at a given time. This proved difficult for them when
they were attempting to make an animation from the data set but they were still able to be successful. 
The visualizations they were able to complete further confirmed their hypothesizes and observations and, in
In the end, one interesting thing they were able to create was a graph that could be traversed to find an optimal
path at a given time in the city. Because the roads are broken into nodes with weights of traffic thickness, 
you could create an algorithm to find the path of least resistance through the city given a specific time to
try and find a better commute. 
