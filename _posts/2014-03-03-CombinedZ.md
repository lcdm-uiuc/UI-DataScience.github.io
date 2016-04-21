---
layout: post
title: "Novel Bayesian Combination of Photo-Z PDFs"
date: 2014-03-03
categories: papers
summary: "We have developed a new method for combining photometric redshift PDFs."
authors: "Matias Carrasco-Kind, Robert J. Brunner"
---

### Exhausting the Information: Novel Bayesian Combination of Photometric Redshift PDFs

**Authors**: Matias Carrasco Kind and Robert J. Brunner  
**Published**:   TBD  
**DOI**: N/A

### Access:

[arXiv Posting](http://arxiv.org/pdf/1403.0044.pdf)  


### Abstract:

The estimation and utilization of photometric redshift probability
density functions (photo-z PDFs) has become increasingly important over
the last few years. Primarily this is because of the prominent role
photo-z PDFs play in enabling photometric survey data to be used to make
cosmological constraints, especially when compared to single photo-z
estimates. Currently there exist a wide variety of algorithms to compute
photo-z ’s, each with their own strengths and weaknesses. In this paper,
we present a novel and efficient Bayesian framework that combines the
results from different photo-z techniques into a more powerful and
robust estimate by maximizing the information from the photometric data.
To demonstrate this we use a supervised machine learning technique based
on pre- diction trees and a random forest, an unsupervised method based
on self organizing maps and a random atlas, and a standard template
fitting method but can be easily extend to other existing techniques. We
use data from the DEEP2 survey and more than 106 galaxies from the SDSS
survey to explore different methods for combining the photo-z
predictions from these three techniques. In addition, by using different
performance metrics, we demonstrate that we can improve the accuracy of
our final photo-z estimate over the best input technique, that the
fraction of outliers is reduced, and that the identification of outliers
is significantly improved when we apply a Näıve Bayes Classifier to
this combined photo-z information. Furthermore, we introduce a new
approach to explore how different techniques perform across the
different areas within the information space supported by the
photometric data. Our more robust and accurate photo-z PDFs will allow
even more precise cosmological constraints to be made by using current
and future photometric surveys. These improvements are crucial as we
move to analyze photometric data that push to or even past the limits of
the available training data, which will be the case with the Large
Synoptic Survey Telescope.

### Implementation

The most recent implementation of the algorithm is not yet available,
but is planned for the next release of the MLZ package.

### Contact:

If you have any questions about the method or the code, please contact
the authors.
