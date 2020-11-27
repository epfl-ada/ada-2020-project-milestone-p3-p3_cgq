# 1.Title:
Comparing Random Forest with Neural Network and support vector machine for predicting class imbalanced civil war onset
 
# 2.Abstract :
While the paper proved the superiority of Random Forest algorithms on logistic regressions for predicting civil war onset, we will now compare Random Forest with Neural Networks and Support vector machine algorithms. We will focus our effort on finding the best possible way to predict civil war onset and compare the importance that the different algorithms give to the different features. We will not try to make causality assumptions but only observe if a “trend” exists between the algorithms.
 
# 3.Research Questions
1.  What is the best model to predict Civil war onset?
2.  Do the different models agree on the weight of the different features in predicting civil war onset?
#4.Proposed dataset
We will use the whole dataset given in the article ( Sambanis dataset) instead of only working on several features. 
The dataset’s size is (7140* 285)  thus machine learning algorithms are suitable to analyze it within a reasonable timeframe. 
We should be able to identify for each method which features are the most important and those features should have a mostly similar level of importance across the algorithms. We expect 3 features to be of great importance, the features that most civil war models use as “core features” (Sambanis and Helgre (2006)): the natural log of population (in the dataset lnpop), the length of peacetime until the outbreak of a war (pt8), and the natural log of per capita gross domestic product (GDP) in constant dollars (lngdp).

# 5.Methods
## 1.   Comparing results of the different algorithms with AUC of the different ROC curves obtained on the testing set.
We will need to implant the three algorithms of machine learning then to calculate the scores for each model and to plot the ROC curves. 
## 2.   Look at the features weight to identify 4 - 5 important factors in each algorithm and compare them.
We will need to calculate the mean decrease in a measure of predictive accuracy, called the Gini Score for each feature to identify the "top ones". 

# 6.Proposed Timeline
## 27.01-06.12
Draw the Roc curves of Random Forest, Neural Network and Support vector machine on the new data set.
## 07.12-10.12
Compare the results obtained and deduce which is the best predicting algorithm
## 11.12-14.12
Compare the importance of the features for the different algorithms
## 15.12-18.12
Conclude

# 7.Organization within the team
Each of us will oversee 1 of the 3 algorithms for the first 10 days. Quentin will take care of Random Forest, Clement of Neural Network and Gianluca of the support vector machine. 
We will then join to compare the results we obtained and compare the dominant features in each algorithm. 



