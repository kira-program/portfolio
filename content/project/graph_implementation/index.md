---
title: Graph Implementation
summary: Implementing a graph interface and algorithms to produce a virtual world
tags:
- programming
date: "2016-06-02T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: 

image:
  caption: Virtual world
  focal_point: Smart

---

Given an interface for an unweighted directedgraph, we wrote 2 classes in Java that implement the interface: an adjacency list and an adjacency matrix.
Next, we implmented algorithms that may be used for social network analysis using the graph implementations.
Breadth first search (BFS) and depth first search (DFS) can both be used to traverse a graph.
Using these, it is possible to find the common upstream and downstream vertices of 2 vertices, the distance between 2 vertices, and 
the graph diameter. We applied these algorithms to analysing a Twitter dataset, to find the common users that both user a and user b follow
and the minimum number of retweets needed for a message that user a tweets to appear in user b's feed. 

In an extension of graphs, we added some subtypes to the virtual world, such as giraffes, cars, and cats that all have unique commands to control 
their behaviour in the virtual world. This project was a fun way to think about code from a design point of view, and 
to practice using subtypes and programming with existing interfaces.  