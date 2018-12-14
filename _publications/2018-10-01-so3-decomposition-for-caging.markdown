---
layout: post
title:  "Caging and Path Non-Existence: a Deterministic Sampling-Based Verification Algorithm"
date:   2017-12-11
categories: jekyll update
name: path-non-existence

figure: "figures/epscore.png"
kind: "paper"
venue: "conference"
publication: "ISRR(2017)"
ref: "https://parasol.tamu.edu/isrr/isrr2017/index.php"
status: "Accepted"
author: "Anastasiia Varava, J. Frederico Carvalho, Florian T. Pokorny, and Danica Kragic"
---

Caging restricts the mobility of an object without necessarily immobilizing it completely. The object is caged if it cannot move arbitrarily far from its initial position. Apart from its common applications to grasping and manipulation, caging can also be considered as a problem dual to motion planning: an object is caged when it is isolated within a bounded connected component of its configuration space and is disconnected from the rest of the latter. In this paper, we address the problem of caging and path non-existence verification in 2D and 3D workspaces by representing a subset of the collision space as a simplicial complex and analyzing the connectivity of its complement. Since configuration spaces of 2D and 3D rigid objects are three-dimensional and six-dimensional respectively, it is computationally expensive to reconstruct them explicitly. Thus, we represent the object’s collision space as a union of a finite set of ‘slices’, corresponding to small intervals of the object’s orientation coordinates. We also discuss possible generalizations of our approach to higher dimensions.

Available [here].

[here]:{{ site.baseurl }}{% link files/path_non_ex.pdf %}
