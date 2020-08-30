# GaussianClassiferFromScratchOneDimension

# Generative Model Approach

  - It’s simple, and powerful to build classifier.
  - It’s based on probability distribution.
  - It's a categorization of classifiers in Bayesian perspective. 
  - It's a statistical model of the joint probability distribution on P(X|Y)
  - Describes how data is generated, in terms of a probabilistic model.

# Example of generative classifiers:

    1 - naive Bayes classifier. </br>
    2 - linear discriminant analysis.</br>
    3 - Hidden Markov Models.</br>
  
 # The main idea:

    1 – fit the probability for each classes separately in our training data.</br>
    2 – fit the probability distribution for each classes in our training data.</br>
    3 – predict new point comes with maximize joint probability distribution.(Bayes' Theorem)</br>
 # How Generative model is classifying data in one dimension ?
 	- The Gaussian in one dimension is called Univariate gaussian.
	- It’s specified by just two parameter (mean, standard deviation)
  	- It used Bayes' rule for predicting/classifying new point.
   There are many steps for predict labels, And classify data.

# 1. Bayes’ Theorem
	
 <img src="Pic/bays.png" width="500" >
 
 	Which is:
		1. P(A|B) is the posterior probability or the probability of A to occur given event B already occurred.
		2. P(B|A) is the likelihood, or the probability of B given A.
		2. P(A), P(B) is the prior probability of event A and B to occur.
	
	Note :
		The variables are independent and P(B) dosn’t change, So we can removed it.
	
# 2. How Gaussian Classifier works ?
	
  
