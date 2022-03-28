# Week 11

My reflection for this week:

## [Augmenting Parallel Coordinates Plotswith Color-coded Stacked Histograms](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9262081)

While parallel coordinates does a really great job to visualize multidimensional data, this paper tries to solve couple of problems associated with it.

1. Cluttering of polylines
2. Difficulty  in  estimating  relationships  between  non-adjacent axes

This paper introduces a new technique called Parallel Histogram Plot (PHP). In this technique, first user selects and attribute. The data is then split into equally sized groups based on the selected attribute. 

Then, a unique color is applied to each of the groups. Finally, a stacked bars histogram is built on each of the PCP axis. The order of the colors in the each stacked bars should match the order of the colors in the color scheme so that users perceive patterns from the color distribution.

So, PHP basically allows us to reveal a relationships of one of the attribute will all other attributes. User can explore data by changing the pivot attribute and see the relationships with other attributes. By adding a histogram, we don't need the attributes side by side to view the relationship. Also, we can get rid of lines that could create clutter.
