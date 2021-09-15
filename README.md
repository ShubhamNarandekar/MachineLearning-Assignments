Question 1

  The objective of this question is to use the ensemble learning functionality to identify 
  the extent to which classification performance can be improved through the 
  combination of multiple models. Experiments will be run on a dataset extracted from 
  US Census data. The data contains 14 attributes including age, race, sex, marital 
  status etc, and the goal is to predict whether the individual earns over $50k per year. 
  We have prepared a dataset for each student. Please download the dataset 
  corresponding to your student id from Brightspace. Submissions using an incorrect 
  dataset will receive a 0 grade. 
  Using your dataset, perform the tasks below. In each task, summarise the differences 
  in performance, and describe some factors which might explain the results. You are 
  free to normalise and/or clean the dataset, as appropriate. Describe the cleaning 
  steps you took in your submission to sufficient degree. Also, note that this is a more 
  realistic dataset -- There may be missing values and many other issues that you have 
  to deal with. 


  (a) Evaluate the performance of three basic classifiers on your dataset: 
  Decision Tree, Neural Network and 1-NN. Carefully consider the evaluation 
  measure(s) that you use for this exercise and justify why you selected the 
  particular evaluation measure(s). 
  (b) Apply ensembles with bagging using the three classifiers from Task (a). 
  Investigate the performance of these classifiers as the ensemble size increases 
  (e.g., in steps of 2 from 2 to 20 members). Using the best performing ensemble 
  size, investigate how changing the number of instances in the bootstrap samples 
  affects classification performance (i.e. the “bag size”). 
  Page 1 of 2
  (c) Apply ensembles with random subspacing using the three classifiers from Task 
  (a). Investigate the performance of these classifiers as the ensemble size 
  increases (e.g., in steps of 2 from 2 to 20 members). Using the best performing 
  ensemble size, investigate how changing the number of features used when 
  applying random subspacing affects classification performance (i.e. the 
  “subspace size”). 
  (d) Based on the lectures, which set of classifiers is expected to benefit from 
  bagging techniques more and which set of classifiers is expected to benefit from 
  random subspacing techniques more? For your dataset, determine the best 
  ensemble strategy for each of these classifiers. Discuss if this is in line with what 
  you expected. 
  
  
Question 2 

  (a) Comment on the interpretability of different supervised learning techniques. How 
  easy or difficult it is to explain the reason behind predictions to a layman? Can 
  you easily find out which training examples need to be modified to change the 
  prediction for a particular query? Can you easily find out the weight of the 
  different features in your model? 
  (b) Explain the bias-variance tradeoff. Which classifiers generally suffer from high bias 
  and which classifiers generally suffer from high variance? Which ensemble 
  strategy helps you to deal with bias and which ensemble strategy helps you to 
  deal with variance issues? 
  (c) What are the main limitations of k-means in general and Lloyd's algorithm in 
  particular? Explain how the centroids are initialised in the k-means++ algorithm? 
  What is the intuition for initialising the centroids in this way? 
  (d) What does R2 measure represent in the case of linear regression? 
  (e) Explain the precision-recall tradeoff. 
  (f) Explain how the parameters are learnt in the training of neural networks. 
