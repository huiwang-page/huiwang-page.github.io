---
title: "A CNN-based Flow Correction Method for Fast Preview"
collection: publications
permalink: /publication/2019-flow-correct
excerpt: ''
date: 2019-06-07
venue: 'Computer Graphics Forum'
paperurl: 'https://doi.org/10.1111/cgf.13649'
citation: 'Xiangyun Xiao, Hui Wang, and Xubo Yang. "A novel CNN-based Poisson solver for fluid simulation." IEEE transactions on visualization and computer graphics 26.3 (2018): 1454-1465. https://doi.org/10.1111/cgf.13649'
image: /images/2019-flow-correct/representative.png
authors: 'Xiangyun Xiao, Hui Wang, and Xubo Yang.'
publishinfo: 'Computer Graphics Forum. Vol. 38. No. 2. 2019.'
---

![representative](/images/2019-flow-correct/representative.png)

Shape correction examples for three-dimensional case. Our ML-based method correct the overall shape of a low-resolution simulation to closely follow the shape of the high-resolution version.

### Abstract

Eulerian-based smoke simulations are sensitive to the initial parameters and grid resolutions. Due to the numerical dissipation on different levels of the grid and the nonlinearity of the governing equations, the differences in simulation resolutions will result in different results. This makes it challenging for artists to preview the animation results based on low-resolution simulations. In this paper, we propose a learning-based flow correction method for fast previewing based on low-resolution smoke simulations. The main components of our approach lie in a deep convolutional neural network, a grid-layer feature vector and a special loss function. We provide a novel matching model to represent the relationship between low-resolution and high-resolution smoke simulations and correct the overall shape of a low-resolution simulation to closely follow the shape of a high-resolution down-sampled version. We introduce the grid-layer concept to effectively represent the 3D fluid shape, which can also reduce the input and output dimensions. We design a special loss function for the fluid divergence-free constraint in the neural network training process. We have demonstrated the efficacy and the generality of our approach by simulating a diversity of animations deviating from the original training set. In addition, we have integrated our approach into an existing fluid simulation framework to showcase its wide applications.

<!-- ### Video

<iframe width="560" height="315"
src="https://www.youtube.com/embed/ugJhLMlyctc" 
frameborder="0" 
allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" 
allowfullscreen>
</iframe> -->

### Links

[[DOI]](https://doi.org/10.1111/cgf.13649)

### Bibtex


<pre>
@article {10.1111:cgf.13649,
  journal = {Computer Graphics Forum},
  title = {{A CNN-based Flow Correction Method for Fast Preview}},
  author = {Xiao, Xiangyun and Wang, Hui and Yang, Xubo},
  year = {2019},
  publisher = {The Eurographics Association and John Wiley & Sons Ltd.},
  ISSN = {1467-8659},
  DOI = {10.1111/cgf.13649}
}
</pre>