# Week 12:

My reflection for this week is [this paper](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.150.9377&rep=rep1&type=pdf). 
This paper is about illustrative parallel coordinates. It is a technique used to augment and improve parallel coordinate visualizations.  

## Limitations of parallel coordinate visualizations:

1. Cluttering. 
2. Distribution of data on axis (How dense/sparse the data points are)

## Description of goals: 

1. Each data point is rendered as a polycurve which allows edge bundling and decluters the visulization
2. Clusters are visualized with semi transparent polygons bounded by spline curves. Higher opacity - higher density of points in cluster.
3. Distribution of data can be viewed at different levels by displaying clusters in tree like manner.
4. Density plot to show correlations between axis
5. Distribution along an axis are shown as quadrilateral strips which  also provide per cluster histogram

## Features
1. Sulhouetts
2. Shadows
3. Histograms
4. Density plot


## Limitations
1. Density plots with histograms give unsatisfactory results
2. Shadows and halos can be undesirable at times
