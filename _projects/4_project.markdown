---
layout: page
title: Characterizing the Shape of Activation Space in Deep Neural Networks
description:
img: /assets/img/characterizing_the_shape.jpg
---

Full text [here](https://arxiv.org/abs/1901.09496).

The representations learned by deep neural networks are difficult to interpret in
part due to their large parameter space and the complexities introduced by their
multi-layer structure. We introduce a method for computing persistent homology
over the graphical activation structure of neural networks, which provides access
to the task-relevant substructures activated throughout the network for a given
input. This topological perspective provides unique insights into the distributed
representations encoded by neural networks in terms of the shape of their activation
structures. We demonstrate the value of this approach by showing an alternative
explanation for the existence of adversarial examples. By studying the topology
of network activations across multiple architectures and datasets, we find that
adversarial perturbations do not add activations that target the semantic structure
of the adversarial class as previously hypothesized. Rather, adversarial examples
are explainable as alterations to the dominant activation structures induced by the
original image, suggesting the class representations learned by deep networks are
problematically sparse on the input space.
