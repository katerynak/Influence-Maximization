# Influence-Maximization
Code and data for experiments with evolutionary influence maximization

## Refactoring
- one file called "load" that contains everything related to loading functions
- one file called "spread" that contains all functions that evaluate influence spread over the network (simulation, lazy_fitness_evaluation, all approximations that do not really work)
- one file called "heuristics" that contains all heuristics that try to find influencial nodes in the network
- one file called "evolutionaryalgorithms" that contains all EAs (single and multi-objective)
- one file called "communities" that contains all methods related to community detection (we do not have stuff immediately available for networkx, but we might be able to find some library built on top of networkx)
- one file called "plots" to plot the graph in a nice way, highlighting the seed nodes (probably the way to go is to convert the graph from networkx to igraph and then use the nice plotting functions of igraph)
