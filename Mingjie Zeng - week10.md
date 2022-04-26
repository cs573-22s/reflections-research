#### Reflection 10 - 03/21/2022
#### Mingjie Zeng (671222265)
#### Email:mzeng2@wpi.edu
----

This week's paper is about a method called Text-to-Viz of automatically generating visualizations from proportion-related natural language statements: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8813126

First of all, here are some examples created by Text-to-Viz:
![image](https://github.com/JasmineZZZ9/reflections-research/blob/main/pics/r10-exp.jpg)
For example, (e) and (f) are generated from the statement: “40 percent of USA freshwater is for agriculture.” We can see that the visualizations can effectively deliver messages and information about numbers in an outstanding and memorable way. Although there are many tools to create vary kinds of infographics, it takes time to know how to create these visualizations.
In this paper, the authors explore a method to automatically generate these visualizations from natural language statements for those who are either unwilling to take time to learn the tools or lacking in proper
design expertise to create a professional infographic.

The authors first conducted a preliminary study to explore the design space of infographics. The goal of this survey was to better understand how infographics are used in real life and identify a specific type on which to build this proof-of-concept system. 
And the authors categorized all the infographic into four main types: statistical-based, timeline-based, process-based and location-based. And also they further discovered diverse patterns in terms of graphic designs and the underlying messages, which were categorized into four major sub-categories, namely proportion, quantity, change, and rank.

Based on the preliminary study, they built a proof-of-concept system that automatically converts statements about simple proportion-related statistics to a set of infographics with pre-designed styles. 
The two main part of this system are text analyzer and visual generator. In the text analyzer part, a textual statement is identified by the analyzer and is segmented into 5 basic segments such as modifier, whole, part, number and others.
Then the original statement and the extracted segments are fed into the visual generator for infographic construction for each dimension including layout, description, graphic, and color. Then, the system enumerates all combinations of
these elements, to synthesize valid infographic candidates. Finally, all the synthesized results are evaluated and ranked, and the ones with high scores are recommended to users.

Finally, they demonstrated the usability and usefulness of the system through sample results, exhibits, and expert reviews.

But this work may not always be successful. For some complicated and long statements, the texutal analyzer may not segment correctly and provide correct tags, which will eventually lead to incomprehensible infographics. The design also has some limitations in terms of capability. The foremost limitation is that the current approach
can only handle a relatively small set of information. Also this approach lacks human creativity and is based on a set of pre-designed infographic styles.


Although this method has many limitations, I think it's creative and a good combination of natural language processing and data visualization. The idea of automatically generating the visualizations by some textual information is not only cool but also has a lot of usage, especially for today's situation about information explosion, people need to use visualization to make the info more straightforward to let people spend less time to take that info in.
