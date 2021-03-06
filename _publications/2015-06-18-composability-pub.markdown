---
layout: post
title:  "Distributed Verification of Structural Controllability for Linear Time-Invariant Systems"
date:   2015-06-18 11:54:00 +0100
categories: jekyll update
name: composability-paper
figure: "figures/Decentralized_disp.png"

kind: "paper"
venue: "journal"
publication: "Automatica"
ref: "http://www.journals.elsevier.com/automatica/"
status: "Accepted"
author: "J. Frederico Carvalho, Sergio Pequito, A. Pedro Aguiar, Soummya Kar, Karl H. Johansson"
---

Motivated by the development and deployment of large-scale dynamical systems, often composed of geographically distributed smaller subsystems, we address the problem of verifying their controllability in a distributed manner. In this work we study controllability in the structural system theoretic sense, structural controllability. In other words, instead of focusing on a specific numerical system realization, we provide guarantees for equivalence classes of linear time-invariant systems on the basis of their structural sparsity patterns, i.e., location of zero/nonzero entries in the plant matrices. To this end, we first propose several necessary and/or sufficient conditions to ensure structural controllability of the overall system, on the basis of the structural patterns of the subsystems and their interconnections. The proposed verification criteria are shown to be efficiently implementable (i.e., with polynomial time complexity in the number of the state variables and inputs) in two important subclasses of interconnected dynamical systems: similar (i.e., every subsystem has the same structure), and serial (i.e., every subsystem outputs to at most one other subsystem). Secondly, we provide a distributed algorithm to verify structural controllability for interconnected dynamical systems. The proposed distributed algorithm is efficient and implementable at the subsystem level; the algorithm is iterative, based on communication among (physically) interconnected subsystems, and requires only local model and interconnection knowledge at each subsystem. 

Available at [Automatica] or as a preprint on [ArXiv].

[Automatica]:https://www.sciencedirect.com/science/article/pii/S0005109816305246
[ArXiV]:http://arxiv.org/abs/1506.05770
