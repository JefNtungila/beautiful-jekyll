---
layout: post
title: Data visualisation using Dimuon event information derived from the run2010B public Mu dataset
gh-repo: daattali/beautiful-jekyll
gh-badge: [star, fork, follow]
tags: [test]
comments: true
---


This is no way to be taken scientifically.

I am not a particle physicists, rather a data science students and thought it would be interesting to look at muons.

I was interested in looking at the energy level of Muons.
My guess was that dimuons would show similar energy levels for the same number of event.

![Comparing total energy levels (momentum P) of both Muons](https://github.com/JefNtungila/Data-story-telling-using-public-data-from-CERN-Run2010B-public-Mu-dataset-/blob/master/E1%20and%20E2.PNG)

Although E1 and E2 show similarities a correlation matrix test determined that their correlation was weak at only 5%.

I noticed antimuons with a charge of Q = 1 when still in the data set and could be influencing the correlation results. Filtering for Q = -1 weakened the correlation results to 0%.


![Comparing total energy levels (momentum P) of both Muons filtered for Q= -1](https://github.com/JefNtungila/Data-story-telling-using-public-data-from-CERN-Run2010B-public-Mu-dataset-/blob/master/E1%20and%20E2%20Q%20is%20min%201.PNG)

It is reasonable to conclude that no correlation is found in the energy levels of dimuons based on this dataset.




