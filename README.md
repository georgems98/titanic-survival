# The Titanic passengers data set
The Kaggle notebooks used in the competition / challenge of predicting whether a passenger on the Titanic survived or not, given some of their information. After experimenting with a couple of different classifiers and configurations of features, the gradient boosting classifier obtains a test accuracy of 81.1%. 

Interestingly, although this is in the top 4% of submissions on the leaderboard, it is not actually a vast improvement over a prediction that assumes that all men die and all women survive, which would score ~76%. It should also be noted that several of the top spots on the leaderboard have 100% prediction scores, presumably obtained using the actual test set survival data.

### Program listings
* titanic-explore.ipynb is an exploration of the data using graphs and summaries
* titanic-model-fit.ipynb fits the model to the data and outputs the predicitons on the test set