#### Reflection 11 - 03/28/2022
#### Mingjie Zeng (671222265)
#### Email:mzeng2@wpi.edu
----

This week's paper is DeepDrawing: A Deep Learning Approach to Graph Drawing: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8807275

This paper proposes a method to directly map network structures to graph drawing using a graph-LSTM-based approach. The authors train the proposed
graph-LSTM-based model to capture their layout characteristics given a set of layout examples as the training dataset. Then, the trained model is used to generate graph drawings in a
similar style for new networks. Furthermore, the authors evaluated the proposed approach on grid layouts and star layouts in both qualitative and quantitative ways and also a time cost assessment on the drawings of small graphs with 20 to 50 nodes were conducted.

Here is the workflow of graph drawing algorithms, (a) is traditional graph drawing algorithms and (b) is the proposed deep learning based approach.
![image](https://github.com/JasmineZZZ9/reflections-research/blob/main/pics/r11-workflow.jpg)

When using a drawing algorithm to visualize a specific graph using the traditional way, users also need to tune the algorithm parameters through
trial and error to achieve a suitable graph drawing result, which is tedious and time-consuming. But for the deep learning based approach, given a set of graph drawing examples with desirable aesthetic properties and their structures, the deep learning
model is trained to learn the mapping and corresponding algorithmspecific parameters for determining the desirable graph drawings. Once the deep learning model is successfully trained, when given a new graph, it can automatically analyze the graph
structure and directly generate a layout that carries the common visual properties of the drawing examples.

Besides the proposed DeepDrawing method, the authors also implement wonderful experiment for evaluation. The picture below is their qualitative evaluation results on star graphs with different number of nodes.
![image](https://github.com/JasmineZZZ9/reflections-research/blob/main/pics/r11-evaluzation.jpg)

They also conduct experiment on general graphs, here is a small part of the experiment results:
![image](https://github.com/JasmineZZZ9/reflections-research/blob/main/pics/r11-general.jpg)

Specially, the authors evaluate the time cost of the proposed approach in comparison with both the original graph drawing techniques and the baseline model.

This paper does not only propose a deep learning based method but also conduct wonderful experiments for evaluation which should be learned from. In the evaluation part, the authors use a lot of comparisons for the result which is clear and meaningful and the comparisons are from vary different aspects.
The combination of deep learning and graph drawing is full of inspiration but there are still limitations causing failure cases. Automatically creating visualizations is always a chanllenging but meaningful work, there are a lot more to explore.
