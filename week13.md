# Week 13 Reflections
[Putting Recommendations on the Map – Visualizing Clusters and Relations](https://dl.acm.org/doi/pdf/10.1145/1639714.1639784?casa_token=n9zwf_k00gsAAAAA:hBM-rbJSvLwHoFjLi_GWkepjyqFN86sNvDmNpMiL0uSabbHliajNVKFyrdSpFoZyzBGYQ1bODkAJtg)

This week, my reflections were on a paper about visualizing clusters and relations. This paper has a couple of different
approaches to improving relational visualizations. The first method that the paper presents if a way to outline cluster
regions. The main point of this algorithm is to soften the border between clusters. Since the exact positions of points
are somewhat fluid there is less concern regarding overlap, and more concern with showing the outer bounds of a cluster
without creating oddly shaped regions like those often seen in voronoi diagrams. The main idea is to scatter random
points around the outer bounds of regions to soften boundaries between clusters and to limit the extent to which a
cluster can extend when uncontested. The next idea that the paper proposes to better display recommendations is to turn
the map into a heat map with. Since there may not be one singular region of interest, it helps to guide the viewer to
regions that they have showed interest in as well as bordering regions which they may want to investigate.