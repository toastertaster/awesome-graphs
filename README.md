# Awesome graphs

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)


A list of material for graph theory and software implementations.

# Theory

## Journals

[IEEE Transactions on Signal and Information Processing over Networks][ieeetsipn]

[ieeetsipn]: http://signalprocessingsociety.org/publications-resources/ieee-transactions-signal-and-information-processing-over-networks

## Books

- [graph book][graphbook1] a recent text with a modern perspective

- [graph book][graphbook2] a historical reference

- [Matrix computations][matrixbook] Golub's reference

[graphbook1]: http://math.tut.fi/~ruohonen/GT_English.pdf
[graphbook2]: http://www.dtic.mil/dtic/tr/fulltext/u2/705364.pdf
[matrixbook]: http://web.mit.edu/ehliu/Public/sclark/Golub%20G.H.,%20Van%20Loan%20C.F.-%20Matrix%20Computations.pdf

## Persistent Homology

Great introduction in the paper with background

Xiaojin Zhu. Persistent homology: An introduction and a new text representation for natural language processing. In The 23rd International Joint Conference on Artificial Intelligence (IJCAI), 2013. [paper][homologypaper] [charts][homologycharts] [poster][homologyposter] [original site][jerryzhu]

[jerryzhu]: http://pages.cs.wisc.edu/~jerryzhu/publications.html
[homologypaper]: http://pages.cs.wisc.edu/~jerryzhu/pub/homology.pdf
[homologycharts]: http://pages.cs.wisc.edu/~jerryzhu/pub/cvrghomology.pdf
[homologyposter]: http://pages.cs.wisc.edu/~jerryzhu/pub/ijcai13posterZhu.pdf


## Topological Data Analysis

- [tda.md notes][tda.md] Another awesome-style listing

- [wikipedia topological data analysis][wikitda]

[tda.md]: https://gist.github.com/turnersr/8668521
[wikitda]:https://en.wikipedia.org/wiki/Topological_data_analysis

# Implementation 

## Software packages for graph analysis

These software components implement graphs for GPUs

- [hornet][hornet] dynamic graph representation for GPUs (see their [paper][hornetpaper] for description)

- [Graph-tool][graphtool] python library

- [NetworkX][networkx] python library

- [GDA-Public][gdapublic] python library for TDA

- [gunrock][gunrock] high performance GPU primatives for static graph analysis

- [cub][nvlabscub] from NVIDIA Labs

- [moderngpu][moderngpu] GPU primatives

[hornet]: https://github.com/hornet-gt/hornet
[hornetpaper]: https://www.researchgate.net/publication/327569751_Hornet_An_Efficient_Data_Structure_for_Dynamic_Sparse_Graphs_and_Matrices_on_GPUs
[graphtool]: https://graph-tool.skewed.de/
[networkx]: https://networkx.github.io/
[gdapublic]: https://github.com/geomdata/gda-public
[gunrock]: https://github.com/gunrock/gunrock
[nvlabscub]: https://github.com/NVlabs/cub
[moderngpu]: https://github.com/moderngpu/moderngpu
[cuStinger]: https://github.com/cuStinger/cuStinger

## Software packages for graph stores

- [Neo4j][Neo4j] Neo4j graph database

- [Giraph][Giraph] Apache Giraph

[Neo4j]: https://neo4j.com/
[Giraph]: https://giraph.apache.org/

# Graph Datasets

These are locations to download graph data for study

- [networkrepository][networkrepository] has graphs of all sizes and types

- [Open Street Maps][osm] export city layout information

[networkrepository]: http://networkrepository.com/
[osm]: https://www.openstreetmap.org/export