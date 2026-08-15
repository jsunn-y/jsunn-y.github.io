---
layout: page
title: lab
permalink: /lab/
description: Research directions in our lab
nav: true
nav_order: 2
---

We develop data-driven AI methods to engineer enzymes and biomolecules with *novel* and *useful* functions, and we integrate these with real-world experiments and automation. Our ultimate goal is to create an autonomous AI-driven ecosystem for biomolecular engineering, to address key challenges such as sustainable synthesis, therapeutics, environmental remediation, and more. 

Our research sits at the intersection of machine learning, protein engineering, computational biology, and computational chemistry. We focus on three central themes:
- data foundations: how to collect and utilize relevant empirical data and physics-based models?
- modeling: how to develop efficient AI methods for multi-modal tasks?
- application: how to bridge computational methods with real-world experimental constraints?

## Join Us!
If you are interested in collaborating or joining the group, please get in touch.

Prospective PhD students:
Prospective postdoctoral scholars:

## Research Thrusts

### Creating a computational platform for functional biomolecule **discovery**

Less than 1% of known protein sequences are annotated with functions, so an improved method to move between functional space and protein space is needed. Existing bioinformatics (e.g., BLAST) and ML methods can automatically retrieve unannotated sequences from databases (given a desired function) but struggle for sequences with remote homology to known proteins and previously uncharacterized functions. Our goal is to use data-driven computational methods to capture the universe of enzymatic catalysis, improving our understanding of metabolism/signaling and enabling discovery of functional biomolecules for nearly all desired applications. We are building new enzyme sequence-function datasets, as the basis for developing a multi-modal foundation model that captures a mapping from enzymes to their functions -- to enable enzyme annotation and retrieval for applications such as metabolic engineering for natural product synthesis, enzymes for biomass upcycling, and novel gene editors for therapeutics.

<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(220px, 1fr)); gap: 1rem; margin: 1.5rem 0;">
  <img src="/assets/img/publication_preview/alde.png" alt="Enzyme design project visualization" style="width: 100%; border-radius: 8px; box-shadow: 0 2px 10px rgba(0,0,0,0.08);" />
  <img src="/assets/img/publication_preview/trpB.png" alt="Protein engineering data and modeling" style="width: 100%; border-radius: 8px; box-shadow: 0 2px 10px rgba(0,0,0,0.08);" />
</div>

### Reimagining deep learning methods for structure-based biomolecular **design**

We aim to venture beyond the existing paradigm of de novo protein design, which largely simplifies proteins as static, structured entities and lacks physical consideration of dynamics and electronics, including when modeling protein interactions with other biomolecules. Many functions cannot be accessed with such existing approaches, so we are developing a generative model for protein structure where design is conditioned on desired physical interactions with substrate(s) to enable specific allosteric modulation or enzymatic chemistry. To facilitate to this effort, we integrate AI approaches into electronic structure theory to enable better modeling of catalysis.

<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(220px, 1fr)); gap: 1rem; margin: 1.5rem 0;">
  <img src="/assets/img/publication_preview/illuminating.jpg" alt="Biomolecular design and machine learning overview" style="width: 100%; border-radius: 8px; box-shadow: 0 2px 10px rgba(0,0,0,0.08);" />
  <img src="/assets/img/publication_preview/procalm.png" alt="Computational analysis of protein sequences" style="width: 100%; border-radius: 8px; box-shadow: 0 2px 10px rgba(0,0,0,0.08);" />
</div>

### Accelerating biomolecular **optimization** with generative modeling

After discovering or designing a protein with some level of desired function, proteins often need to be optimized (modified) to maximize fitness for specific objectives such as stability, activity, affinity, etc. We develop methods that are more efficient than directed evolution, through ML-assisted optimization, which involves an iterative cycle of collecting labeled data through expensive wet-lab measurements and using these data to update an ML model and suggest new sequences to further explore, known as active learning. To this end, we develop state-of-the-art ML methods that use labeled data to shift the distribution of generative models to conditionally sample sequences with higher fitness and integrate them into real-world active learning workflows.

<img src="/assets/img/publication_preview/vesicle.png" alt="Lab research image" style="width: 100%; max-width: 800px; display: block; margin: 1.5rem auto; border-radius: 10px; box-shadow: 0 2px 12px rgba(0,0,0,0.08);" />
