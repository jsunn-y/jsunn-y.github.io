---
layout: page
title: research
permalink: /research/
description: Research directions in our lab
nav: true
nav_order: 2
---

We develop data-driven AI methods to engineer enzymes and biomolecules with *novel* and *useful* functions, and we integrate these with real-world experiments. Our ultimate goal is to create an autonomous, AI-driven ecosystem for biomolecular engineering, to address key challenges such as sustainable synthesis, therapeutics, environmental remediation, and more.

<img src="/assets/img/research/overview.png" alt="Research overview" style="width: 100%; max-width: 800px; display: block; margin: 1.5rem auto; border-radius: 8px; box-shadow: 0 2px 10px rgba(0,0,0,0.08);" />

Our research sits at the intersection of machine learning, protein engineering, computational biology, and computational chemistry. We focus on three central themes:
- data foundations: how to collect and utilize relevant empirical data and physics-based models?
- modeling: how to develop efficient AI methods for multi-modal tasks?
- application: how to bridge computational methods with real-world experimental constraints?

## Research Thrusts

### Creating a computational platform for functional biomolecule **discovery**

<div style="display: flex; gap: 1.5rem; align-items: flex-start; margin: 1.5rem 0;">
  <div style="flex: 3; min-width: 0;">
    Less than 1% of known protein sequences are annotated with functions, so an improved method to move between functional space and protein space is needed. Existing bioinformatics (e.g., BLAST) and ML methods can automatically retrieve unannotated sequences from databases (given a desired function) but struggle for sequences with remote homology to known proteins and previously uncharacterized functions. Our goal is to use data-driven computational methods to capture the universe of enzymatic catalysis, improving our understanding of metabolism/signaling and enabling discovery of functional biomolecules for nearly all desired applications. We are building new enzyme sequence-function datasets, as the basis for developing a multi-modal foundation model that captures a mapping from enzymes to their functions -- to enable enzyme annotation and retrieval for applications such as metabolic engineering for natural product synthesis, enzymes for biomass upcycling, and novel gene editors for therapeutics.
  </div>
  <div style="flex: 1; min-width: 0;">
    <img src="/assets/img/research/research1.png" alt="Research image 1" style="width: 100%; display: block; border-radius: 8px; box-shadow: 0 2px 10px rgba(0,0,0,0.08);" />
  </div>
</div>

### Reimagining deep learning methods for structure-based biomolecular **design**

<div style="display: flex; gap: 1.5rem; align-items: flex-start; margin: 1.5rem 0;">
  <div style="flex: 3; min-width: 0;">
    We aim to venture beyond the existing paradigm of de novo protein design, which largely simplifies proteins as static, structured entities and lacks physical consideration of dynamics and electronics, including when modeling protein interactions with other biomolecules. Many functions cannot be accessed with such existing approaches, so we are developing a generative model for protein structure where design is conditioned on desired physical interactions with substrate(s) to enable specific allosteric modulation or enzymatic chemistry. To facilitate to this effort, we integrate AI approaches with electronic structure theory and molecular dynamics to improve molecular models of biocatalysis.

    <p>Related work:</p>
    <ul>
      <li><a href="https://www.sciencedirect.com/science/article/pii/S2405471225002054">Illuminating the universe of enzyme catalysis in the era of artificial intelligence</a></li>
      <li><a href="https://doi.org/10.1038/s41467-026-68384-6">Sequence-based generative AI design of versatile tryptophan synthases</a></li>
      <li><a href="https://arxiv.org/abs/2505.15093v1">Steering Generative Models with Experimental Data for Protein Fitness Optimization</a></li>
    </ul>
  </div>
  <div style="flex: 1; min-width: 0;">
    <img src="/assets/img/research/research2.png" alt="Research image 2" style="width: 100%; display: block; border-radius: 8px; box-shadow: 0 2px 10px rgba(0,0,0,0.08);" />
  </div>
</div>

### Accelerating biomolecular **optimization** with generative modeling

<div style="display: flex; gap: 1.5rem; align-items: flex-start; margin: 1.5rem 0;">
  <div style="flex: 3; min-width: 0;">
    After discovering or designing a protein with some level of desired function, proteins often need to be optimized (modified) to maximize fitness for specific objectives such as stability, activity, affinity, etc. We develop methods that are more efficient than directed evolution, through ML-assisted optimization, which involves an iterative cycle of collecting labeled data through expensive wet-lab measurements and using these data to update an ML model and suggest new sequences to further explore, known as active learning. To this end, we develop state-of-the-art ML methods that use labeled data to shift the distribution of generative models to conditionally sample sequences with higher fitness and integrate them into real-world active learning workflows.
  </div>
  <div style="flex: 1; min-width: 0;">
    <img src="/assets/img/research/research3.png" alt="Research image 3" style="width: 100%; display: block; border-radius: 10px; box-shadow: 0 2px 12px rgba(0,0,0,0.08);" />
  </div>
</div>

If you are interested in joining the group, please get in [touch](/team/)!