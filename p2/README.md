## New Applications of IT (TNUI) course labwork from Computer Science Bachelor's degree at University of Barcelona (UB)
============================================

###Contributors:
* Igor Dzinka (idzinkdz7@alumnes.ub.edu)
* Vicent Roig (vroigrip8@alumnes.ub.edu)

--------------------------------------------

###Introduction

We want to classify a set of blogs corresponding to militants of four political parties as its ideology. In order to achieve that, we will use RSS or Atom feeds. From his entries we will create a vector of feature that describe us the content of the blog. Finally we will develop a probabilistic Naïve Bayes Classifier to allow us identify the ideology of a new blog, given its description in the chosen features.

###Supervised learning

Supervised learning is the machine learning task of inferring a function from labeled training data.[1] The training data consist of a set of training examples. In supervised learning, each example is a pair consisting of an input object (typically a vector) and a desired output value (also called the supervisory signal). A supervised learning algorithm analyzes the training data and produces an inferred function, which can be used for mapping new examples. An optimal scenario will allow for the algorithm to correctly determine the class labels for unseen instances. This requires the learning algorithm to generalize from the training data to unseen situations in a "reasonable" way (see inductive bias).

###Naïve Bayes classifier

Naïve Bayes is a simple technique for constructing classifiers: models that assign class labels to problem instances, represented as vectors of feature values, where the class labels are drawn from some finite set. It is not a single algorithm for training such classifiers, but a family of algorithms based on a common principle: all naive Bayes classifiers assume that the value of a particular feature is independent of the value of any other feature, given the class variable. For example, a fruit may be considered to be an apple if it is red, round, and about 10 cm in diameter. A naive Bayes classifier considers each of these features to contribute independently to the probability that this fruit is an apple, regardless of any possible correlations between the color, roundness and diameter features.