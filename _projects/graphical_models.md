---
layout: page
title: Graphical models
description: Understand latent variables and cycles
img:
importance: 1
category: work
related_publications: false
---

Latent variables and cycles are common in real-world systems but often overlooked. Directed acyclic graphs are popular for their well-understood properties and learning algorithms, but their assumptions are restrictive. Directed mixed graphs and cyclic graphs provide better representations of real-world data-generating processes, but their theoretical properties and learning algorithms remain under-explored.

Maximal ancestral graphs are projections of directed mixed graphs that preserve all conditional independence constraints. While constraint-based methods like the fast causal inference algorithm have been proposed for learning these graphs, explorations into score-based algorithms have only recently emerged. A key aspect is understanding Meek's conjecture for maximal ancestral graphs, which is crucial for greedy graph-based or permutation-based search algorithms.

Maximal arid graphs are also projections of directed mixed graphs, but they capture a broader class of equality constraints, including Verma constraints. This class of graphs is relatively new to the community, making it important to understand their nested Markov properties and develop scalable algorithms for structure learning.


