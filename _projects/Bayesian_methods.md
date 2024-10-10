---
layout: page
title: Bayesian methods
description: Models and computation
img:
importance: 4
category: work
related_publications: false
---

Bayesian methods are well-recognized for their strong performance in low-sample settings and for their ability to quantify uncertainty, which is crucial for various causal inference tasks, including the design of interventional experiments. However, despite these advantages, Bayesian methods face great computational challenges, particularly in the context of causal structure learning. Scaling the problem to datasets with more than a few hundred variables without imposing constraints remains demanding, and many sampling algorithms struggle with mixing issues.

Another problem is that in causal discovery, many model assumptions are imposed to enable causal identification. However, in practice, these assumptions can be restrictive and may not always hold. The consequences of violating these assumptions are relatively less understood. Additionally, finite-sample guarantees — such as the required sample size and signal strength for accurately recovering the true causal structure — remain underexplored. This work aims to address these challenges from a Bayesian perspective.
