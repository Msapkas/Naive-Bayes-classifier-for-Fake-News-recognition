# Naive-Bayes-classifier-for-Fake-News-recognition
Physics of Data Masters Degree - 2nd Semester - Advanced Statistics For Physics Analysis - Final Project

For the final project of Advanced Statistics we implemented the Naive Bayess Classifier. 
The idea of Bayesian inference has been known since the work of Bayes (1763), and was first applied to text classification by Mosteller and Wallace (1964).

The multinomial naive Bayes classifier, so called because it is a Bayesian classifier that makes a simplifying (naive) assumption about how the features interact.

We represent a text document as if it were a bag of words, that is, an unordered set of words with their position ignored, keeping only their frequency in the document. In the example in the figure, instead of representing the word order in all the phrases like “I love this movie” and “I would recommend it”, we simply note that the word *I* occurred 5 times in the entire excerpt, the word *it* 6 times, the words *love, recommend, and movie* once, and so on.

Naive Bayes is a probabilistic classifier, meaning that for a document d, out of all classes C the classifier returns the class which has the maximum posterior probability given the document.
