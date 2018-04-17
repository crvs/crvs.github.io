---
layout: post
title:  "Path Clustering with Homology Area"
date:   2017-09-16
categories: jekyll update
name: homology-clustering-paper

kind: "paper"
venue: "conference"
publication: "ICRA(2018)"
ref: "https://www.icra2018.org"
status: "Accepted"
author: "J. Frederico Carvalho, Mikael Vejdemo-Johansson, Danica Kragic, Florian T. Pokorny"
---

Path classification has found many applications in recent years. Common approaches to this problem use aggregates of the distances between points to provide a measure of dissimilarity between paths which do not satisfy the triangle inequality. Therefore, such distance measures need to be used with care to avoid cluster chaining. Furthermore, they do not take into account the topology of the space where the paths are embedded. To tackle this, we extend previous work in path clustering with homology, by employing homology area as a measure of distance between homologous paths in a triangulated mesh. Further, we show that the resulting distance satisfies the triangle inequality, and how we can exploit the properties of homology to reduce the amount of pairwise distance calculations necessary to cluster a set of paths by an order of magnitude.

Available [here].

[here]:{{ site.baseurl }}{% link files/homology_clustering_submitted.pdf %}
