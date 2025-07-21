---
title: "Research"
layout: gridlay
sitemap: false
permalink: /research/
---

<style>
img{
  border-radius: 10px;
}
.col-md-3 {
  margin-top:10px;
  margin-bottom:10px;
  padding:0px;
  display:block;
  overflow:hidden;
  text-align:center;
  display: table-cell;
  background: white;
  border-radius: 20px;
  height: auto;
}
iframe {
  margin:0;
  padding:0;
  width: 175px;
  display: inline;
  vertical-align: middle;
}
</style>

## Research <br><br>


#### Theory of Deep Neural Networks through polyhedral decompositions and homology
<img src="{{ '/images/RNN_decomp.png' | relative_url }}" alt="Your Name" style="width: 700px; border-radius: 0%; display: block;">


Neural networks with ReLU activation functions are known to split the input domain of a model into convex polyhedra. Furthermore, the set of all such networks is equivalent to the set of all piecewise-linear maps. This allows one to trade the global non-linear structure of a network with a locally structure that is locally linear. On an unrelated note, many people have tried to understand the behavior of neural networks by studying geometric or topological invariants (such as homology) of neural representations. 

In this research track, I leverage  the polyhedral geometry inherent to such neural networks to define topological invariants intrinsic to the network and the data manifold. Using this framework we can describe exactly how and where a network glues pieces of the data while solving a task. 

Future work will focus on making the developed methods more computationally efficient, understanding how different architectures impact these invariants and defining new invariants that track more than the homology groups of neural representations.

- For more information see the preprints: A rank decomposition for the topological classification of neural representations (K. Beshkov & G. T. Einevoll 2024) and A Relative Homology Theory of Representation in Neural Networks (K. Beshkov 2025)
<br><br>


#### Topological Data Analysis of large scale neural recordings
<img src="{{ '/images/phom_data.jpg' | relative_url }}" alt="Your Name" style="width: 700px; border-radius: 0%; display: block;">

The notion of a neural manifold has become a fundamental component for our understanding of how the brain represents and transforms information. However, truly understanding the structure of a neural manifold is a non-trivial task. For one these manifolds can be highly non-linear and have very high dimension, this often means that simply applying dimensionality reduction to visualize them can very often lead us astray. 

In this work, I focus on studying the topology of neural manifolds and adapt methods from topological data analysis (TDA) with the goal of overcoming the limitations imposed by the complex interactions of billions of neurons. My work has so far focused mainly on the visual system, which works with very high-dimensional stimulus spaces. Future work, involves understanding how the topology of complicated stimulus manifolds is transformed throughout the visual system.

- For more information see: Geodesic-based distance reveals nonlinear topological features in neural activity from mouse visual cortex (K. Beshkov & P. Tiesinga 2022) and Topological Structure of Population Activity in Mouse Visual Cortex Encodes Densely Sampled Stimulus Rotations (K. Beshkov, M. Fyhn, T. Hafting and G. T. Einevoll 2024)
<br><br>

#### De novo protein design with machine learning
<img src="{{ '/images/evol_algo_figure.png' | relative_url }}" alt="Your Name" style="width: 700px; border-radius: 0%; display: block;">
Machine learning for the generation of de novo protein design is a rapidly evolving field. In this research track I attempt to apply, develop and understand existing machine learning algorithms for de novo protein design. One direction of this work combines evolutionary algorithms, statistical modeling and neural networks to create and simplify existing proteins. 

Another goal of mine is to leverage tools from geometry, shape analysis and topological data analysis to understand how the space of protein representations in neural networks corresponds the space of actual proteins. Finally, I am also interested in applying tools from mechanistic interpretability to gain further insight into how large scale neural network models transform sequences of amino acids.
 <br><br>