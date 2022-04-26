#### Reflection 12 - 04/04/2022
#### Mingjie Zeng (671222265)
#### Email:mzeng2@wpi.edu
----

This week's paper is GUIRO: User-Guided Matrix Reordering: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8807245

Matrix representations are very effective visualization techniques for relational or network data. However, it's very difficult to dicide which matrix reordering algorithm should be applied basee on different dateset. What's worse is that different reordering algorithms applied to the same dateset may let significantly different visual matrix patterns emerge. 
This paper presents GUIRO, a Visual Analytics system that helps novices, network analysts, and algorithm designers to investigate the usefulness and expressiveness of 70 accessible matrix reordering algorithms. GUIRO helps
to increase the transparency of matrix reordering algorithms, thus helping a broad range of users to get a better insight into the complex
reordering process, in turn supporting data and reordering algorithm insights.

This is a simple example demonstrating the basic design of GUIRO. This picture shows a specific dataset with three reodering options in the left part. And in the right part, the projection space shows that distinct groups of rows/columns can be formed.
![image](https://github.com/JasmineZZZ9/reflections-research/blob/main/pics/r12-emp.jpg)

The system provides 71 different choices of reordering algorithms which shows the comparisons between the different matrix reodering results:

![image](https://github.com/JasmineZZZ9/reflections-research/blob/main/pics/r12-choice.jpg)

Based on the matrix reodering results, then the system represents matrix reoderings in the projection space and then interprets reodering results in the projection space.

The system proposed in this paper guides the user to submatrices, which could potentially be improved by showing row/column similarity in a novel projection view. And the user may choose to apply an arbitrary automatic matrix reordering algorithm on selected submatrices.
This system also helps the user by showcasing thumbnails of the local reorderings to help to anticipate the operation’s outcome. Furthermore, the user is free to rearrange the rows and columns—or groups thereof—manually. 
In addition, the approach allows the hierarchical construction of new matrix reordering algorithms, by applying local optimizations on a global matrix reordering result.

For me, it's very interesting to solve the relationship between network data in this way and I'm still curious how to deal with the relationship or order data in a network graph. The matrix reodering method mentioned in the paper may give up some inspirations.
