# Week 13

My reflection for this week:

## [A Nutritional Label for Rankings](https://dl.acm.org/doi/pdf/10.1145/3183713.3193568)

I did this paper for my reflection because this it is similar to the research project I am working on.

This short paper is about a web based application called **Ranking Facts**. It tries to explain the details of ranking methodology. Ranking is used in many scenarios like admissions, hiring or finding dating partners. However, there could be bias when algorithms generate a ranking for us. This paper emphasizes on informing the user about the diversity in a ranking and explain the details of the ranking.

For example, if we want to rank foods by how spicy it is. Foods could have attributes like amount of sugar, lemon, salt, pepper, type of pepper, hot sauce, etc. Our initial thoughts could be that amount of pepper determines spicy level and an algorithm could generate the ranking based on it. However, a detailed inspection of the ranking could reveal that generated ranking is also equally or more affected by amount of hot sauce or amount of sugar present in it. For analyzing the details of ingredients of the ranking, the system in this paper has ingredients view which shows the details of the attributes that strongly influence the ranking.

Similarly, the paper also explores the demonstration of fairness in the ranking. The user can select an attribute as a protected attribute, and see the distribution of the groups in that attribute in top 10 ranking and overall ranking.

Finally, the system gives label saying whether the ranking is fair for a given protected attribute based on different definitions of fairness.

As a future work, they will by trying to explore and implement group fairness measures that go beyond binary protected attributes.


