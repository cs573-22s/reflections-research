# Week 11 Reflections
[Visualization of Large Hierarchical Data by Circle Packing](https://dl.acm.org/doi/pdf/10.1145/1124772.1124851)

This week I looked at a paper written on using circle packing to visualize large hierarchical trees. This paper was an
earlier work in the area and had some room for improvement, however it offered some interesting examples and provided a
general algorithm for circle packing. I generally like the concept, but one flaw I saw was that many datasets have a
small branching factor (at least initially) and can leave a lot of blank space within the working area. In this case,
data could better occupy a space if it were allowed to fill available space between circles. It also leaves open the
possibility for the adjustment of circle sizes to reflect another axis within the data similarly to bubble charts. 
This paper performed a small trial of 21 students on to gauge the utility of this type of visualization with a mostly
positive result from the 21 students who tried the visualization. However, it may have been in part biased by the
data being presented (the file system of a machine). Since all the students were already familiar with navigating
filesystems and there is little room for new insights when simply viewing the structure of one's hard drive it may
have been 

