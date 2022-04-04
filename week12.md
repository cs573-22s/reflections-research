###### Marcus Chalmers 
###### CS573
###### 4/04/2022
###### Reflection Week 12

["Attribute Signatures: Dynamic Visual Summaries for Analyzing Multivariate Geographical Data"](https://ieeexplore.ieee.org/document/6875987)

This paper took a look at graphical data, specifically when trying to display many different collections of data on one map. Because all of
the data is intrinsically linked to its geography, if you want to show a lot of information on a map, you need to make sure there's enough space
for that information to be legible at that specific location on your map. This paper looked at UK census data from two years as an example
and, because they looked at every category available, there was a lot to show. The paper breaks down the fundamentals of showing data on a map with
regards to location, but also extent and resolution (for showing amounts). The paper also talks about how displaying data with different colors
can be helpful up to a certain number of data collections before it becomes more cluttered than useful. The solution expressed in this paper 
used small multiples. Only showing the extent of all of the data on the map itself freed up visual clutter and instead allowed
the user to see the data they were interested in on one of the many small graphs adjacents. Selecting an area would show each actual value stored
for that location, including multiple years if one so wanted. What is genius about this paper, however, is how they incorporated location into
the small multiple graphs. Selecting an area wouldn't just show the data for that area, but if you selected a path
from saying one city to another then you could see a graph of each value as the reported values varied along the path. This whole level
of interaction is what makes a map visualization of this size even remotely possible. This paper is a great example of how interactivity available
in digital visualizations has increased what's possible. 
