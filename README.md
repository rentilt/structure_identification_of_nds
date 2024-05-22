# STRUCTURE IDENTIFICATION OF NETWORKED DYNAMICAL SYSTEMS UNDER PARTIAL OBSERVABILITY AND COLORED NOISE VIA MACHINE LEARNING TOOLS

Clean code from my Master thesis focusing on **Networked Dynamical Systems** and **Machine Learning**. We extracted **features** from the time series data and used a **CNN** to classify each pair of nodes as connected or disconnected.

## Goal
Infer the topology of the graph of NDS (Networked Dynamical Systems) from the activity of the nodes (time series)

## Main Conditions
**Partial Observability**: Only observe a subset of the nodes in the network. This is a crucial step in large scale systems where we can't probe all the nodes in the system because of different reasons (Computational cost, efficiency, locality).

**Colored Noise**: The noise signal is correlated across different nodes, meaning that the signal is not spatially independent.

## Files
- **training.ipynb** - explains the training process for the model and the architecture
- **tutorial.ipynb** - explains the process of generating the graphs, the time series and the colored noise
- **helper_functions.py** - contains all the utils functions used, such as the functions the generate the adjacency matrix, the functions to retrieve the features from the time series and much more...