---
title: "Codimensional surface tension flow using moving-least-squares particles"
collection: publications
permalink: /publication/2009-10-01-paper-title-number-1
excerpt: 'A novel Eulerian-Lagrangian approach to simulate various codimensional surface tension phenomena characterized by volume, thin sheets, thin filaments, and points using Moving-Least-Squares (MLS) particles'
date: 2020-08-12
venue: 'ACM Transactions On Graphics (SIGGRAPH)'
paperurl: 'https://dl.acm.org/doi/abs/10.1145/3386569.3392487'
citation: 'Hui Wang, Yongxu Jin, Anqi Luo, Xubo Yang, and Bo Zhu. 2020. Codimensional surface tension flow using moving-least-squares particles. ACM Trans. Graph. 39, 4, Article 42 (August 2020), 16 pages. https://doi.org/10.1145/3386569.3392487'
image: /images/2020-codim-mls/representative.jpg
authors: 'Hui Wang, Yongxu Jin, Anqi Luo, Xubo Yang, and Bo Zhu.'
publishinfo: 'ACM Trans. Graph. 39, 4, Article 42 (August 2020), 16 pages.'
---

![representative](/images/2020-codim-mls/representative.jpg)

### Abstract

We propose a new Eulerian-Lagrangian approach to simulate the various surface tension phenomena characterized by volume, thin sheets, thin filaments, and points using Moving-Least-Squares (MLS) particles. At the center of our approach is a meshless Lagrangian description of the different types of codimensional geometries and their transitions using an MLS approximation. In particular, we differentiate the codimension-1 and codimension-2 geometries on Lagrangian MLS particles to precisely describe the evolution of thin sheets and filaments, and we discretize the codimension-0 operators on a background Cartesian grid for efficient volumetric processing. Physical forces including surface tension and pressure across different codimensions are coupled in a monolithic manner by solving one single linear system to evolve the surface-tension driven Navier-Stokes system in a complex non-manifold space. The codimensional transitions are handled explicitly by tracking a codimension number stored on each particle, which replaces the tedious meshing operators in a conventional mesh-based approach. Using the proposed framework, we simulate a broad array of visually appealing surface tension phenomena, including the fluid chain, bell, polygon, catenoid, and dripping, to demonstrate the efficacy of our approach in capturing the complex fluid characteristics with mixed codimensions, in a robust, versatile, and connectivity-free manner.

### Video

<iframe width="560" height="315"
src="https://www.youtube.com/embed/ugJhLMlyctc" 
frameborder="0" 
allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" 
allowfullscreen>
</iframe>

### Links

[[DOI]](https://dl.acm.org/doi/abs/10.1145/3386569.3392487)
[[Youtube]](https://www.youtube.com/watch?v=ugJhLMlyctc)

### Bibtex

    @article{10.1145/3386569.3392487,
    author = {Wang, Hui and Jin, Yongxu and Luo, Anqi and Yang, Xubo and Zhu, Bo},
    title = {Codimensional Surface Tension Flow Using Moving-Least-Squares Particles},
    year = {2020},
    issue_date = {August 2020},
    publisher = {Association for Computing Machinery},
    address = {New York, NY, USA},
    volume = {39},
    number = {4},
    issn = {0730-0301},
    url = {https://doi.org/10.1145/3386569.3392487},
    doi = {10.1145/3386569.3392487},
    journal = {ACM Trans. Graph.},
    month = {aug},
    articleno = {42},
    numpages = {16},
    keywords = {moving-least-squares, surface tension, codimensional fluids, PIC/FLIP}
    }