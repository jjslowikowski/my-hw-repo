### ***Project 1 Feedback***

***Nico Van de Bovenkamp***

***

**Overall:** Good work on this! You presented a thorough analysis/research plan, and you're clearly familiar with some statistical methods for data analysis, which is key to making any claims about data. Don't have many comments outside of a new notes.

**Some Notes**

* *Pairplots and Scatter Matrix:* The scatter matrix you have just above question 2 is doing pair-wise plotting of each variable, with a histogram down the middle to just have a reference point for the variable's distribution. Histograms are nice because they give you a sense of skew and shape, as you noted below it! You can also test for skew, as you had done above. Additionally, you can re-shape your data by doing some transformations (maybe a log transform would reshape the data to make it more normal?).
* *Q.2a:* Awesome, and very appropriate, note on representation of the data. This is a crucial point to make when doing any analysis. Another assumption, though, is the distribution of the data. This is more pertinent when you are actually modeling the data, depending on what model you use.

**Something to think about**

Regarding covariance and generalized linear models (linear regressions/logistic regressions in this case), these are all linear metrics and estimators. Thus, these models will work will if the data is actually linear in structure. If there are some non-linearities, then the models will not work well and may lead to some false conclusions. Non-linear models is an area where the world of Machine Learning has far exceeded traditional statistics methods of estimation. If you are curious, I would be happy to share/discuss more in class!

***Note: Given you already have some solid exposure to statistical analysis and Python, if you ever feel a topic is too elementary or you want more, please ask for some suggestions for more advanced readings! I can send things your way, especially once we get into modeling!***
