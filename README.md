
# Introduction

## Introduction
This lesson summarizes the topics we'll be covering in section 28 and why they'll be important to you as a data scientist.

## Objectives
You will be able to:
* Understand and explain what is covered in this section
* Understand and explain why the section will help you to become a data scientist

## Graph Theory

And now for something completely different! There are certain classes of data science problems where building and then traversing a graph can be a very powerful way to solve them. Not just for analysing social networks, but for anomaly detection, recommendation systems and geospacial data (e.g. calculating shipping routes) graph based approaches can be a really useful tool. In this section, we're going to provide an introduction to graphs that you can use as a starting point if you want to use such techniques in the future.

### Introduction to Graph Theory

We start by providing a basic introduction to what a graph is - a series of nodes (sometimes called vertices or points) and edges (sometimes called arcs or lines). We also introduce some important properties of graphs such as directionality (I know of ex-President Obama, but he may not have heard of me!) and weight (anything from the strength of a friendship to the time it takes to drive between two cities).

### Graphs in Python with NetworkX

One of the most common packages for working with graphs in Python is NetworkX. In this lesson, we look at how to create and visualize graphs using NetworkX.

### Graph Data I/O

From there, we look at two common representations for serializing graphs - edge lists and adjacency matrices so you can load graph data into NetworkX.

### Implementing and Visualizing Graphs with NetworkX

We then provide you with a lab to pull together all the steps you learned in the previous lessons to get some practice creating and visualizing graphs using NetworkX and Matplotlib.

### Graph Theory: Simple and Shortest Paths

The real power of Graphs as a way of modeling data is that there are a huge number of powerful algorithms for performing analyses on graphs. In this lesson we introduce the idea of the simple and shortest paths for undirected, directed and weighted graphs and introduce Djikstras algorithm for calculating the shortest path between two nodes.

### Network Dynamics: Node Centrality

Another way of modeling graph data is to try to identify network centrality (in a social graph, think of people who have a *lot* of friends). In this lesson we introduce a number of measures for analysing graph data including degree, closeness, betweenness and eigenvector centrality measures.

### Network Dynamics: Bipartite Graphs

A bipartite graph is one in which every edge connects from one set to the other but no edge connects two nodes within the same set. In this lesson we introduce bipartite graphs and explain how measures of centrality work for such graphs.

### Network Connectivity: Community Detection

Community detection allows us to look at subsets of the nodes and edges within a graph (subgraphs) to find communities (networks which are more densely interconnected) within a larger graph. In this section we look at various techniques such as the Girvan-Newman algorithm for detecting communities within graphs. 

### Social Network Analysis: Ego Networks

Next up we introduce the island method and the idea of ego networks for analysing social networks.

### Amazon Recommendation System 

Finally, we end up the section by asking you to create a book recommendation system using an Amazon co-purchase data set.



## Summary

Once you know about graphs as a modeling technique, you'll start to see them everywhere. In this section we give you the tools to start to model data using a range of graph based algorithms.

