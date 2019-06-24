---
layout: post
title:  "Long-term Prediction of Motion Trajectories Using Path Homology Clusters"
date:   2019-06-24
categories: jekyll update
name: motion-prediction-iros

figure: "figures/IROS-motion-prediction.png"
kind: "paper"
venue: "conference"
publication: "IROS(2019)"
ref: "https://iros2019.org"
status: "Accepted"
author: "J. Frederico Carvalho, Mikael Vejdemo-Johansson, Florian T. Pokorny, and Danica Kragic"

---

Abstract:

In order for robots to share their workspace with people, they need to reason about human motion efficiently. In this work we leverage large datasets of paths in order to infer local models that are able to perform long-term predictions of human motion. Further, since our method is based on simple dynamics, it is conceptually simple to understand and allows one to interpret the predictions produced, as well as to extract a cost function that can be used for planning. The main difference between our method and similar systems, is that we employ a map of the space and translate the motion of groups of paths into vector fields on that map. We test our method on synthetic data and show its performance on the Edinburgh forum pedestrian long-term tracking dataset [1] where we were able to outperform a Gaussian Mixture Model tasked with extracting dynamics from the paths.

Available [here].

[here]:{{ site.baseurl }}{% link files/IROS-motion-prediction.pdf %}
[1]:http://homepages.inf.ed.ac.uk/rbf/FORUMTRACKING
