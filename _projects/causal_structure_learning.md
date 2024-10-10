---
layout: page
title: Causal structure learning
description: Models and assumptions
img:
importance: 2
category: work
related_publications: false
---

Causal structure learning has been widely studied in the literature. However, most existing work focuses on continuous data with relatively simple structures, which reduces their relevance in complex, real-world scenarios. For instance, multivariate categorical data are commonly encountered in domains such as survey data and clinical records. The goal is to extend causal structure learning to accommodate discrete and mixed data while accounting for potential spatial-temporal patterns.

The first step toward achieving this goal is to develop methods for causal discovery tailored to categorical data. This involves uncovering causal relationships between disease traits and survey items. In such data, latent confounders are prevalent, and this work aims to address this challenge by employing two distinct methods.

The first method leverages the cardinality of latent variables and applies the rank condition to sequentially detect and remove these latent variables. Finally, the Markov equivalence class of the true causal structure can be recovered, under proper rank and structure assumptions.

The second method is specifically designed for binary variables, utilizing the multivariate probit model and pseudo-interventions, i.e., instrumental variables, to address latent confounding. This approach is inspired by genomics studies, where genetic variants are employed to investigate biological systems, adhering to the principles of Mendelian inheritance.
