---
layout: post
title: "SDSS DR7 Galaxy Two-Point Angular Correlation Function"
date: 2013-07-01
categories: papers
summary: "We calculate the galaxy two-point angular correlation function for the SDSS DR7"
authors: "Yiran Wang, Robert J. Brunner"
---

### The SDSS Galaxy Angular Two-Point Correlation Function
 
**Authors**: Yiran Wang, Robert J. Brunner, and Josh C. Dolence  
**Published**:   July 1, 2013  
**DOI**: 10.1093/mnras/stt450

### Access:

[MNRAS Journal Article](http://mnras.oxfordjournals.org/content/432/3/1961)  
[NASA ADS Record](http://adsabs.harvard.edu/abs/2013MNRAS.432.1961W)  
[arXiv Posting](http://arxiv.org/abs/1303.2432)  


### Abstract:

We present the galaxy two-point angular correlation function for
galaxies selected from the seventh data release of the Sloan Digital Sky
Survey. The galaxy sample was selected with $r$-band apparent magnitudes
between $17$ and $21$; and we measure the correlation function for the
full sample as well as for the four magnitude ranges: $17$--$18$,
$18$--$19$, $19$--$20$, and $20$--$21$. We update the flag criteria to
select a clean galaxy catalog and detail specific tests that we perform
to characterize systematic effects, including the effects of seeing,
Galactic extinction, and the overall survey uniformity. Notably, we find
that optimally we can use observed regions with seeing $< 1.5^{\prime\prime}$, and
 $r$-band extinction $< 0.13$ magnitudes, smaller than previously
published results. Furthermore, we confirm that the uniformity of the
SDSS photometry is minimally affected by the stripe geometry. We find
that, overall, the two-point angular correlation function can be 
described by a power law, $\omega(\theta) = A_\omega
\theta^{(1-\gamma)}$ with $\gamma \simeq 1.72$, over the range
$0.005^{\circ}$--$10^{\circ}$. We also find similar relationships for the four
magnitude subsamples, but the amplitude within the same angular interval
for the four subsamples is found to decrease with fainter magnitudes, in
agreement with previous results. We find that the systematic signals are
well below the galaxy angular correlation function for angles less than
approximately $5^{\circ}$, which limits the modeling of galaxy angular
correlations on larger scales. Finally, we present our custom, highly
parallelized two-point correlation code that we used in this analysis.


### Implementation

The measurements presented in this paper made use of our fast two point
correlation function [code](/code/tpacf.html), which we have publicly released.

### Data

We have released the [data](/data/sdssDR7-tpacf.html) used in the
measurements of the SDSS DR7 Two-Point Correlation Functions as described in the paper.

### Contact:

If you have any questions about the method, data, or code, please contact
the authors.
