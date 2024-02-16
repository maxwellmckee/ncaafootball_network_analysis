# NCAA College Football Network Analysis

## Overview
This project explores the structural properties and community structures within the NCAA College Football Network. Utilizing the `football.gml` file for the network's empirical data, and `football-hrg.gml` for hierarchical random graph analysis, the project aims to understand complex network dynamics through various statistical and graphical methods.

## Tools and Libraries
The analysis is performed using Python, leveraging libraries such as:
- `NetworkX` for network analysis,
- `PyHRG` for working with hierarchical random graphs,
- `numpy`, `scipy` for numerical computations,
- `matplotlib` for visualization.

## Part 1: Structural Properties Analysis
In the first part, we:
- Calculated key network statistics such as diameter, characteristic path length, clustering coefficient, transitivity, assortativity, and degree sequence.
- Identified community structures using the Louvain algorithm across different resolutions, compared these structures to a ground truth, and visualized the results.
- Analyzed the inter-community connection density through matrix representation and heatmap visualization.

## Part 2: Graph Generation and Comparison
The second part focuses on:
- Generating graphs based on empirical network statistics using the Configuration Model, Stochastic Block Model, and Hierarchical Random Graphs.
- Comparing generated graphs to the empirical network to evaluate model accuracy through statistical measures and visualizations.

## Part 3: D3.js Visualization (Work in Progress)
- **Note**: An attempt is being made to visualize the NCAA network graph using D3.js on a force-directed graph. However, this part of the project is not yet finished and is currently under development.
