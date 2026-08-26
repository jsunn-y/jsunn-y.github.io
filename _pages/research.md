---
layout: page
title: research
permalink: /research/
description: 
nav: true
nav_order: 2
---

Our overarching vision is to create an **autonomous, AI-driven ecosystem for biomolecular engineering**, to address key challenges such as sustainable synthesis, therapeutics, environmental remediation, and more:
  <ul>
    <li><a href="https://www.sciencedirect.com/science/article/pii/S2405471225002054">Illuminating the Universe of Enzyme Catalysis in the Era of Artificial Intelligence</a></li>
    <li><a href="https://pubs.acs.org/action/showCitFormats?doi=10.1021/acscentsci.3c01275&ref=pdf">Opportunities and Challenges for Machine Learning-Assisted Enzyme Engineering</a></li>
  </ul>

<img src="/assets/img/research/overview.png" alt="Research overview" style="width: max(90%, 600px); max-width: 100%; display: block; margin: 1.5rem auto; border-radius: 8px; box-shadow: 0 2px 10px rgba(0,0,0,0.08);" />

To this end, we develop data-driven AI methods to engineer enzymes and biomolecules with *novel* and *useful* functions, and we integrate these with real-world experimental workflows. Our research sits at the intersection of machine learning, protein engineering, computational biology, and computational chemistry. We focus on three central themes:
- *data foundations:* how to collect and utilize relevant empirical data and physics-based models?
- *modeling:* how to develop efficient AI methods for multi-modal tasks?
- *application:* how to bridge computational methods with real-world experimental constraints?

## Research Thrusts

### Creating a computational platform for functional biomolecule **discovery**

<div style="margin: 2rem 0;">
  <img src="/assets/img/research/research1.png" alt="Research image 1" style="width: max(65%, 400px); max-width: 100%; display: block; margin: 0 auto 1.5rem; border-radius: 8px; box-shadow: 0 2px 10px rgba(0,0,0,0.08);" />
  <div>
    Less than 1% of known protein sequences are annotated with functions, so an improved method to discover useful enzymes with novel functions is needed. Existing bioinformatics (e.g., BLAST) and ML methods can automatically retrieve unannotated sequences from databases (given a desired function) but struggle for sequences with remote homology to known proteins and previously uncharacterized functions. We are building new enzyme sequence-function datasets as the basis for developing a multi-modal foundation model that captures a mapping from enzymes to their functions. Our goal is to capture the universe of enzymatic catalysis, to enable enzyme annotation and retrieval for applications such as metabolic engineering for natural product synthesis, enzymes for biomass upcycling, and novel gene editors for therapeutics. 
    <p style="margin-top: 0.5rem;">Related work:</p>
    <ul>
      <li><a href="http://arxiv.org/abs/2406.15669">CARE: A Benchmark Suite for the Classification and Retrieval of Enzymes</a></li>
      <li><a href="http://arxiv.org/abs/2410.03634">Function-Guided Conditional Generation Using Protein Language Models with Adapters</a></li>
    </ul>
  </div>
</div>

### Reimagining deep learning methods for structure-based biomolecular **design**

<div style="margin: 2rem 0;">
  <img src="/assets/img/research/research2.png" alt="Research image 2" style="width: max(40%, 350px); max-width: 100%; display: block; margin: 0 auto 1.5rem; border-radius: 8px; box-shadow: 0 2px 10px rgba(0,0,0,0.08);" />
  <div>
    We aim to venture beyond the existing paradigm of de novo protein design, which largely simplifies proteins as static, structured entities and lacks physical consideration of dynamics and electronics, including when modeling protein interactions with other biomolecules. Many functions cannot be accessed with such existing approaches, so we are developing a generative model for protein structure where design is conditioned on desired physical interactions with substrate(s) to enable specific allosteric modulation or enzymatic chemistry. To facilitate to this effort, we improve molecular models of biocatalysis by integrating AI with approaches from electronic structure theory and molecular dynamics.
    
    <p style="margin-top: 0.5rem;">Related work:</p>
    <ul>
      <li><a href="https://www.biorxiv.org/content/10.1101/2024.12.02.626353v3">Controllable All-Atom Protein Generation with Latent Diffusion</a></li>
      <li><a href="https://arxiv.org/abs/2604.05181">General Multimodal Protein Design Enables DNA-Encoding of Chemistry</a></li>
      <li><a href="https://doi.org/10.1038/s41467-026-68384-6">Sequence-Based Generative AI Design of Versatile Tryptophan Synthases</a></li>
      <li> and more to come!</li>
    </ul>
  </div>
</div>

### Accelerating biomolecular **optimization** with generative modeling

<div style="margin: 2rem 0;">
  <img src="/assets/img/research/research3.png" alt="Research image 3" style="width: max(55%, 400px); max-width: 100%; display: block; margin: 0 auto 1.5rem; border-radius: 10px; box-shadow: 0 2px 12px rgba(0,0,0,0.08);" />
  <div>
    After discovering or designing a protein with some level of desired function, proteins often need to be optimized (modified) to maximize fitness for specific objectives such as stability, activity, affinity, etc. We develop methods that are more efficient than directed evolution, through ML-assisted optimization, which involves an iterative cycle of collecting labeled data through expensive wet-lab measurements and using these data to update an ML model and suggest new sequences to further explore, known as active learning. To this end, we develop state-of-the-art ML methods that use labeled data to shift the distribution of generative models to conditionally sample sequences with higher fitness. Ulimately, we aim to integrate these strategies into real-world active learning workflows that are increasingly powered by agentic AI and autonomous discovery.

    <p style="margin-top: 0.5rem;">Related work:</p>
      <ul>
        <li><a href="https://www.nature.com/articles/s41467-025-55987-8">Active Learning-Assisted Directed Evolution</a></li>
        <li><a href="https://arxiv.org/abs/2505.15093v1">Steering Generative Models with Experimental Data for Protein Fitness Optimization</a></li>
      </ul>
  </div>
</div>

If you are interested in joining the group, please get in [touch](/team/)!