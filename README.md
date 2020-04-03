Solution landscape
==================

Visualize and explore the solution landscape of [Infomap](https://github.com/mapequation/infomap) based on [clusters of network partitions](https://github.com/mapequation/partition-validation). The [solution landscape notebook](solution-landscape.ipynb) helps you:

1. Identify how many times you need to run Infomap to obtain a solution with given resolution and accuracy.

<p align="right">
    <img height="200" alt="Validation score" src="images/validation_score.png">
</p>

2. Visualize the solution landscape with alternative solutions.

<p align="right">
    <img height="300" alt="Solution landscape" src="images/solution_landscape.png">
</p>

3. Explore how node assignments change between different solutions.

<p align="right">    
    <img height="200" alt="Alluvial diagram" src="images/alluvial_diagram.png"> 
</p>

The notebook uses Infomap as an example, but works for any network clustering algorithm producing two-level or multilevel partitions. 

Reference
--------

The notebook presents methods introduced in
<br>
**Exploring the solution landscape enables more reliable network community detection**
<br>
Joaquín Calatayud, Rubén Bernardo-Madrid, Magnus Neuman, Alexis Rojas, and Martin Rosvall.
<br>
[Phys. Rev. E 100, 052308 (2019)](https://doi.org/10.1103/PhysRevE.100.052308)
<br>
[arXiv:1905.11230](https://arxiv.org/abs/1905.11230)
<br>
> To understand how a complex system is organized and functions, researchers often identify communities in the system's network of interactions. Because it is practically impossible to explore all solutions to guarantee the best one, many community-detection algorithms rely on multiple stochastic searches. But for a given combination of network and stochastic algorithm, how many searches are sufficient to find a solution that is good enough? The standard approach is to pick a reasonably large number of searches and select the network partition with the highest quality or derive a consensus solution based on all network partitions. However, if different partitions have similar qualities such that the solution landscape is degenerate, the single best partition may miss relevant information, and a consensus solution may blur complementary communities. Here we address this degeneracy problem with coarse-grained descriptions of the solution landscape. We cluster network partitions based on their similarity and suggest an approach to determine the minimum number of searches required to describe the solution landscape adequately. To make good use of all partitions, we also propose different ways to explore the solution landscape, including a significance clustering procedure. We test these approaches on synthetic and real-world networks, and find that different networks and algorithms require a different number of searches and that exploring the coarse-grained solution landscape can reveal noteworthy complementary solutions and enable more reliable community detection.

Feedback
--------

If you have any questions, suggestions, or issues regarding the software,
please add them to [GitHub issues](https://github.com/mapequation/solution-landscape/issues)

Authors
-------

Daniel Edler, Anton Eriksson, Martin Rosvall

For contact information, see [mapequation.org/about.html](https://www.mapequation.org/about.html)

Terms of use
------------

See [LICENSE](LICENSE)
