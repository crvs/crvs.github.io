---
layout: post
title:  "Static Output Feedback: On Essential Feasible Information Patterns"
date:   2015-09-08 11:54:00 +0100
categories: jekyll update

figure: "figures/essential_feasible.png"
kind: "paper"
venue: "conference"
ref: "http://www.cdc2015.ctrl.titech.ac.jp/"
publication: "CDC"
status: "Accepted"
author: "J. Frederico Carvalho, Sergio Pequito, A. Pedro Aguiar, Soummya Kar, George J. Pappas"
---

In this paper, for linear time-invariant plants, where a collection of possible inputs and outputs are known a priori, we address the problem of determining the communication between outputs and inputs, i.e., information patterns, such that desired control objectives of the closed-loop system (for instance, stabilizability) through static output feedback may be ensured.

We address this problem in the structural system theoretic context. To this end, given a specified structural pattern (locations of zeros/non-zeros) of the plant matrices, we introduce the concept of essential information patterns, i.e., communication patterns between outputs and inputs that satisfy the following conditions: (i) ensure arbitrary spectrum assignment of the closed-loop system, using static output feedback constrained to the information pattern, for almost all possible plant instances with the specified structural pattern; and (ii) any communication failure precludes the resulting information pattern from attaining the pole placement objective in (i).

Subsequently, we study the problem of determining essential information patterns. First, we provide several necessary and sufficient conditions to verify whether a specified information pattern is essential or not. Further, we show that such conditions can be verified by resorting to algorithms with polynomial complexity (in the dimensions of the state, input and output). Although such verification can be performed efficiently, it is shown that the problem of determining essential information patterns is in general NP-hard. The main results of the paper are illustrated through examples. 

Available at [IEEEXplore] and as a preprint on [ArXiv].

[IEEEXplore]:https://ieeexplore.ieee.org/document/7402839/
[ArXiV]:http://arxiv.org/abs/1509.02383
