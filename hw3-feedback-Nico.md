### ***Project 3 Feedback***

***Nico Van de Bovenkamp***

***

**Overall**  
Awesome work on this assignment! You effectively built the models, and interpreted all outputs. As we discussed earlier, what I recommend is that you take this analysis/model, and try your hand using sklearn! Maybe even try out some different types of models we have learned: KNN, Decision trees, random forest, boosted trees, naive bayes, or SVMs!

***Plotting***  
The plotting bonus question was actually looking for you to plot the probability of admittance against all GRE scores and then all GPA scores, stratified by prestige. Thus, it would like streaks increasing in probability as GRE, and GPA, increase, where probability is higher in absolute terms for each greater prestige. However, your plot is instructive in showing that average (I assume?) probability of admittance is greater as prestige increases.

***Incorrect Predictions***  
I think that your predictions are incorrect because of the `result` object you are predicting on. You have already fit your model on `Analysis` dataset. You must re-instantiate the class to make a new object, and then fit the model to predict on. Otherwise, your corresponding weights/parameters are all wrong, and it will output incorrect values. This is an example of how models are effective, but definitely not "smart".
