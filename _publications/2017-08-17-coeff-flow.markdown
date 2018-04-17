---
layout: post
title:  "An algorithm for calculating top-dimensional bounding chains"
date:   2017-08-17
categories: jekyll update
name: coeff-flow-paper

kind: "paper"
venue: "journal"
publication: "PeerJ (2018)"
ref: "https://peerj.com/computer-science/"
status: "Accepted"
author: "J. Frederico Carvalho, Mikael Vejdemo-Johansson, Danica Kragic, Florian T. Pokorny"
---

We describe the \textsc{Coefficient-Flow} algorithm for calculating the bounding chain of an $(n-1)$--boundary on an $n$--manifold-like simplicial complex $S$. We prove its correctness and show that it has a computational time complexity of $O(\|S^{(n-1)}\|)$ (where $S^{(n-1)}$ is the set of $(n-1)$--faces of $S$). We estimate the big-$O$ coefficient which depends on the dimension of $S$ and the implementation. We present an implementation, experimentally evaluate the complexity of our algorithm, and compare its performance with that of solving the underlying linear system.

Available as [PeerJ Preprint]. The accompanying code can be obtained on [Github]

[PeerJ Preprint]:https://peerj.com/preprints/3151/?td=bl
[Github]:https://github.com/crvs/coeff-flow
