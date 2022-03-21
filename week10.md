Week 10 Reflection - Lux: Always-on Visualization Recommendations for Exploratory Dataframe Workflows
--
Lux is introuduced as a tool for Jupyter notebook or other python markdown tool users as a way to visualize data before making any data analytics. It provides analytical tool to transform clean and analyze data and was produced by a large number of scientists from UC Berkeley (Doris Jung-Lin Lee, Dixin Tang, Kunal Agarwal, Thyne Boonmark, Caitlyn Chen, Jake Kang,
Ujjaini Mukhopadhyay, Jerry Song, Micah Yong, Marti A. Hearst, Aditya G. Parameswaran). [Read the article here.](https://www.researchgate.net/profile/Yong-Wang-149/publication/346555391_Applying_Machine_Learning_Advances_to_Data_Visualization_A_Survey_on_ML4VIS/links/603cd29e92851c4ed5a5590d/Applying-Machine-Learning-Advances-to-Data-Visualization-A-Survey-on-ML4VIS.pdf)

In the old system, people would need to first read in a csv and then plot out necessary charts and need to hand select and think what type and which graph to be plotted out. Lux provides an opportunity for people to plot out the images when people load the dataset. Then, they provide an interface for users to interact with the plots and select the ones they all like. All these algorithms deosn't add more than two seconds in the process of crafting dataframe. 

<div style="text-align:center">
<img src="./images/week10-1.JPG" />
</div>
<p align="center">Figure 1 This image shows the overarching logic for Lux and comparison to the old system. </p>

In the system, they employeed the technology of intent language formalization. In Intent grammar, it is composed of one or more clauses, each of which is either an axis or a filter of interest. Filters define a subset of data that the user is interested in. To
specify a filter, the attribute being filtered, the operation, and the value, are required.

<div style="text-align:center">
<img src="./images/week10-2.JPG" />
</div>
<p align="center">Figure 2 This image shows a comparison between Lux language logic and other existing ones. </p>