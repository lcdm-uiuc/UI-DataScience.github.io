---
layout: post
title: "Efficient Storage of Photo-Z PDFs"
date: 2014-04-12
categories: papers
summary: "We have developed a new method for storing photo-z PDFs more efficiently"
authors: "Matias Carrasco-Kind, Robert J. Brunner"
---

### Sparse Representation of Photometric Redshift PDFs: Preparing for Petascale Astronomy

**Authors**: Matias Carrasco Kind and Robert J. Brunner  
**Published**:   TBD  
**DOI**: N/A

### Access:

[arXiv Posting](http://arxiv.org/abs/1404.6442)  


### Abstract:

One of the consequences of entering the era of precision cosmology is
the widespread adoption of photometric redshift probability density
functions (PDFs), which provide additional information over simple
photometric redshift estimates. Both current and future photometric
surveys are expected to obtain images of billions or more distinct
galaxies. As a result, storing and analyzing all of these photometric
redshift PDFs will be non- trivial; a result that is even more severe if
a survey decides to compute and store multiple di↵erent PDFs. In this
paper we explore this problem and propose the use of a sparse basis
representation to fully represent individual photo-z PDFs. For large
galaxy samples, we achieve an accuracy of 99.8% while reducing the
number of points required to represent a galaxy photometric redshift PDF
by an order of magnitude. By using an Orthogonal Matching Pursuit
algorithm and a combination of Gaussian and Voigt bases functions, we
demonstrate how our approach is superior to the a multi-Gaussian fitting
approach, as we require approximately half of the parameters for the
same fitting accuracy with the additional advantage that an entire PDF
can be stored by using a single four byte integer per basis function. By
using data from the CFTHLens survey, we demonstrate that only ten to
twenty points per galaxy are suffcient to reconstruct both the individual
PDF and the ensemble redshift distribution, N(z), to an accuracy of
99.9% when compared to the one built using the original photo-z PDFs
computed with a resolution of ffz = 0.01. Thus, in this example we reduce
the required storage from two hundred photo-z PDF values as originally
computed by a factor of ten to twenty. As a result, our proposed
approach will allow current and future surveys to easily manage and
store billions of PDFs and to also enable these same surveys to archive
multiple photo-z PDFs computed by di↵erent techniques. Finally, we
demonstrate how this functional basis representation can be directly
extended to a cosmological analysis, thereby increasing computational
performance without losing resolution or accuracy.

### Implementation

The most recent implementation of the algorithm is not yet available,
but is planned for the next release of the MLZ package.

### Contact:

If you have any questions about the method or the code, please contact
the authors.
