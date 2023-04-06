---
layout: paper
title: 'ShipHullGAN: A generic parametric modeller for ship hull design using deep convolutional generative model'
image: /images/papers/2023-cmame-khan-shipgan.png
authors: Khan S, Goucher-Lambert K, Kostas K, and Kaklis P. 
year: 2023
ref: Khan et al.<i>CMAME</i> 2023
journal: Computer Methods in Applied Mechanics and Engineering (2023).
pdf: /pdfs/papers/khan-shipgan-cmame.pdf
doi:
---


# Abstract
In this work, we introduce ShipHullGAN, a generic parametric modeller built using deep convolutional generative adversarial networks (GANs) for the versatile representation and generation of ship hulls. At a high level, the new model intends to address the current conservatism in the parametric ship design paradigm, where parametric modellers can only handle a particular ship type. We trained ShipHullGAN on a large dataset of 52,591 physically validated designs from a wide range of existing ship types, including container ships, tankers, bulk carriers, tugboats, and crew supply vessels. We developed a new shape extraction and representation strategy to convert all training designs into a common geometric representation of the same resolution, as typically GANs can only accept vectors of fixed dimension as input. A space-filling layer is placed right after the generator component to ensure that the trained generator can cover all design classes. During training, designs are provided in the form of a shape-signature tensor (SST) which harnesses the compact geometric representation using geometric moments that further enable the inexpensive incorporation of physics-informed elements in ship design. We have shown through extensive comparative studies and optimisation cases that ShipHullGAN can generate designs with augmented features resulting in versatile design spaces that produce traditional and novel designs with geometrically valid and practically feasible shapes.
