Week 12 Reflection - Ordered Treemap Layouts
--
Treemap are very good visualization for hierachical dataset; however, there are several problem going on with it. One most crucial thing is how this visualization tool handles real time data. Ben Shneiderman and Martin Wattenberg mentions a solution in the paper. [Read the article here.](http://www.ifs.tuwien.ac.at/~mlanzenberger/teaching/ps/ws08/stuff/00963283.pdf)

The ordered treemap algorithm ensures that items near each other in the given order will be near each other in the treemap layout. Using experimental evidence from Monte Carlo trials, we show that compared to other layout algorithms ordered treemaps are more stable while maintaining relatively favorable aspect ratios of the constituent rectangles. A second test set uses stock market data. 
In order to compare treemap algorithms there are two measures: the average aspect ratio of a treemap layout, and the layout distance change function, which quantify the visual problems created by poor layouts. As of natural measure, although certainly not the only possibility. On the other hand, a weighted average places greater emphasis on larger items, since they contribute more to the overall visual impression. We choose an unweighted average since the chief problems with high aspect ratio rectangles—poor visibility and awkward labeling—are at least as acute for small rectangles as large ones. 

<div style="text-align:center">
<img src="./images/week12-1.JPG" />
</div>