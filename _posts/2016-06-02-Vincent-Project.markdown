---
layout: post
title:  "High Performance Data Science"
date:   2016-06-02 15:15:00 -0600
categories: project
---

## Abstract

Over the last decade, two fields related to computer science have emerged: petascale supercomputing and data science. In the first category, we find high performance numerical simulations such as the ones produced in cosmology, condensed matter and climate science. The second fied is very linked to statistics and include research topics such as machine learning. The two fields tend to use different technologies, the first one being centered around compiled languages to extract the best possible performances from supercomputers, and the second one being centered around libraries written in higher level languages such as Python and R. However, in a not so far future, cross-field problematics will arise: how to use machine learning techniques on high performance simulations producing petabytes of data? And how will data science algorithms scale to datasets of billions or thousands of billions of unique elements?

To explore these questions of high performance data science, we started to investigate fundamental data structures and especially trees. Trees are everywhere in computer science, from simulation in physics (spatial trees) to compilers (abstract syntax trees), and from hierarchical databases to the web (xml and html trees). But while arrays, lists and maps benefit from standard, high performance implementations in most languages, trees are still missing. Our research aims at designing generic and efficient tree building blocks to make the most of present-day and future supercomputing architectures. It involves algorithmic and software design research as well as low-level development. We aim at providing a library that would satisfy the highest development quality standards, and be ready for standardization in a future version of the C++ language.
