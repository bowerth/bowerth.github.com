---
layout   : post
category : datascience
tagline  : 
tags     : [R, python]
---
{% include JB/setup %}

Torsten Hothorm (UZH) on [Big Data Science](http://user.math.uzh.ch/hothorn/talks/big_data_science_UZH_2014.pdf)

## 17 Great Machine Learning Libraries

Source: [daoudclarke.github.io/machine-learning-libraries](http://daoudclarke.github.io/machine%20learning%20in%20practice/2013/10/08/machine-learning-libraries/)

### Python

Scikit-learn
:   comprehensive and easy to use, I wrote a whole article on why I like this library.

PyBrain
:   Neural networks are one thing that are missing from SciKit-learn, but this module makes up for it.

nltk
:   really useful if you’re doing anything NLP or text mining related.

Theano
:   efficient computation of mathematical expressions using GPU. Excellent for deep learning.

Pylearn2
:   machine learning toolbox built on top of Theano - in very early stages of development.

MDP (Modular toolkit for Data Processing)
:   a framework that is useful when setting up workflows.

### Java

Spark
:   Apache’s new upstart, supposedly up to a hundred times faster than Hadoop, now includes MLLib, which contains a good selection of machine learning algorithms, including classification, clustering and recommendation generation. Currently undergoing rapid development. Development can be in Python as well as JVM languages.

Mahout
:   Apache’s machine learning framework built on top of Hadoop, this looks promising, but comes with all the baggage and overhead of Hadoop.

Weka
:   this is a Java based library with a graphical user interface that allows you to run experiments on small datasets. This is great if you restrict yourself to playing around to get a feel for what is possible with machine learning. However, I would avoid using this in production code at all costs: the API is very poorly designed, the algorithms are not optimised for production use and the documentation is often lacking.

Mallet
:   another Java based library with an emphasis on document classification. I’m not so familiar with this one, but if you have to use Java this is bound to be better than Weka.

JSAT
:   stands for “Java Statistical Analysis Tool” - created by Edward Raff and was born out of his frustation with Weka (I know the feeling). Looks pretty cool.

###.NET

Accord.NET
:   this seems to be pretty comprehensive, and comes recommended by primaryobjects on Reddit. There is perhaps a slight slant towards image processing and computer vision, as it builds on the popular library AForge.NET for this purpose.  
    Another option is to use one of the Java libraries compiled to .NET using IKVM - I have used this approach with success in production.

### C++

Vowpal Wabbit
:   designed for very fast learning and released under a BSD license, this comes recommended by terath on Reddit.

MultiBoost
:   a fast C++ framework implementing some boosting algorithms as well as some cascades (like the Viola-Jones cascades). It’s mainly focused on AdaBoost.MH so it is multi-class/multi-label.

Shogun
:   large machine learning library with a focus on kernel methods and support vector machines. Bindings to Matlab, R, Octave and Python.

### General

LibSVM and LibLinear
:   these are C libraries for support vector machines; there are also bindings or implementations for many other languages. These are the libraries used for support vector machine learning in Scikit-learn.

## Books

    The Elements of Statistical Learning
:   Author: Hastie, Tibshirani, and Friedman  
	Content: formal specifications of basic machine learning techniques (mathematics, statistics, computer science)
	URL: [www-stat.stanford.edu/~tibs/ElemStatLearn](http://statweb.stanford.edu/~tibs/ElemStatLearn/)

## Articles

### ASA

Statistics as a Science, Not an Art: The Way to Survive in Data Science
:   2015-02  
    [statscience_feb2015](http://magazine.amstat.org/blog/2015/02/01/statscience_feb2015/)

Statistics Losing Ground to Computer Science
:   2014-11  
    [statistics-losing-ground-to-computer-science](http://magazine.amstat.org/blog/2014/11/01/statistics-losing-ground-to-computer-science/)

Time to Embrace a New Identity?
:   2014-10  
    [statview-oct14](http://magazine.amstat.org/blog/2014/10/01/statview-oct14/)

Statistics Training: A Big Role in Big Data?
:   2014-05  
    [statview-big-data](http://magazine.amstat.org/blog/2014/05/01/statview-big-data/)

- [Why becoming a data scientist is NOT actually easier than you think](https://medium.com/cs-math/why-becoming-a-data-scientist-is-not-actually-easier-than-you-think-5b65b548069b)

## Data Sources

FLUENTD
:   data collector for unified logging layer  
	http://www.fluentd.org/

## Models

Generalized Linear Models (GLM)
:   

Probabilistic Graphical Models
:   

Latent Variable Models
:   

Time-Series Model
:   

Real-Time Learning
:    