research link https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8509240

Data visualization is invaluable for explaining the
significance of data to people who are visually oriented. The
central task of automatic data visualization is, given a dataset,
to visualize its compelling stories by transforming the data (e.g.,
selecting attributes, grouping and binning values) and deciding
the right type of visualization (e.g., bar or line charts).
We present DEEPEYE, a novel system for automatic data
visualization that tackles three problems: (1) Visualization
recognition: given a visualization, is it “good” or “bad”?
(2) Visualization ranking: given two visualizations, which one
is “better”? And (3) Visualization selection: given a dataset,
how to find top-k visualizations? DEEPEYE addresses (1) by
training a binary classifier to decide whether a particular
visualization is good or bad. It solves (2) from two perspectives:
(i) Machine learning: it uses a supervised learning-to-rank
model to rank visualizations; and (ii) Expert rules: it relies
on experts’ knowledge to specify partial orders as rules.
Moreover, a “boring” dataset may become interesting after
data transformations (e.g., binning and grouping), which forms
a large search space. We also discuss optimizations to efficiently
compute top-k visualizations, for approaching (3). Extensive
experiments verify the effectiveness of DEEPEYE.

We have presented DEEPEYE, a novel automatic data
visualization system. We leveraged machine learning techniques as black-boxes and expert specified rules, to solve
three challenging problems faced by DEEPEYE, namely,
visualization recognition, visualization ranking, and visualization selection. We have shown promising results using
real-world data and use cases. One major future work is to
support keyword queries such that users specify their intent
in a natural way