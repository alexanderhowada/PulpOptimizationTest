# PulpOptimizationTest

## PathOptimization.ipynb

Simple path optimization using pulp.

The goal is to find the path that visits all nodes and minimizes the sum of distances.

The script generates random points as the nodes and optimizes the path using pulp with many constraints.

The constraints guarantee that each node is visited only once and only one node is visited at a time.

## PulpOptimizationExample.ipynb

It is just the blending problem from pulp.

https://coin-or.github.io/pulp/CaseStudies/a_blending_problem.html
