---
layout: post
title:  "N-gram Reconstruction"
date:   2016-03-21 10:00:00 -0600
categories: project
---

## Abstract

[Cline Center for Democracy](http://www.clinecenter.illinois.edu/) uses data science to predict when and where social conflicts will happen by gathering news articles around the world and analyze them. However, some of articles are protected under copyright law. So the Cline Center can only distribute their metadata such as n-grams. The purpose of this project is to determine what is the highest possible value for n in n-grams under the condition that people cannot reconstruct the orignical document based on the n-grams data(so we won't violate the copyright).

#### To do list

1. Grab n-gram data from documents

2. Train regression model based on the n-gram data to reconstruct original document

3. Test the hypothesis that the value of n for n-gram is allowed to increase when the length of original document increases.

4. For what value of n can we reconstruct documents of a given length?

## People

* Professor Robert J. Brunner, Department of Astronomy 
* Andrew Mehrmann, Department of Statistics
* Kefu Zhu, Department of Statistics


## References

* Python
* NLTK
* Scikit-learn

## Code

[Github Repository](https://github.com/kfz0131/Statistics/blob/master/N-gram%20Reconstruction%20Project.ipynb)

