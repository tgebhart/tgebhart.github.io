---
layout: page
title: research
permalink: /research/
description:
nav: true
---

My research is focused on the study of complex systems through a topological lens.
These complex systems are often naturally characterized by a network. The
interaction between the topological structure of the network and functional properties
of the processes which exist on or are described by the network are often linked.
An understanding of the interaction between the topology and function of complex
systems provides a foothold for understanding their fundamental pieces, composing
these pieces to create more complex behaviors, and augmenting the behavior of these
systems for greater societal benefit.


<h3>
<p style="text-align: center;">Topological Data Analysis</p>
</h3>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-0" src="/assets/img/persistent_homology.png" alt="" title="persistent homology" />
    </div>
</div>
<div class="caption">
</div>

Topological Data Analysis (TDA) is a relatively new applied-mathematical
field whose methods are derived from the much older field of algebraic topology.
TDA is concerned with characterizing the “shape” of spaces in an invariant manner.
Work in the past two decades have brought theory from algebraic topology into the
data sciences by discretizing traditional topological concepts. With this
discretization comes powerful methods for tracking local-to-global structural
properties within high-dimensional data. My research borrows many methods from
TDA, including persistent homology, combinatorial Hodge theory, and the theory of
cellular sheaves. Foundational research in TDA is ongoing.

<h3>
<p style="text-align: center;">Neural Network Topology</p>
</h3>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-0" src="/assets/img/nn_topology.png" alt="" title="persistent homology" />
    </div>
</div>
<div class="caption">
</div>

The connectivity structure of deep neural networks plays a dominant role in their
function. However, due to the large and complicated nature of these networks,
little is understood about the relationship between neural network structure and
function. I am interested in how this parameter connectivity interacts with network
performance. More specifically, I am interested in the implicit biases embedded
within networks due to their architectural specifications and initialization methods,
and how this connectivity topology interacts with the topology structure of the input.
An understanding of these biases can help point us towards network architectures
that are better suited for particular tasks that will train more quickly, require less
data, and generalize to unseen data in more expected ways. An understanding of these
network biases is crucial in gaining an understanding of the function of neural networks,
and aligning the behavior of these networks with societal ethics and intuitions.
Relatedly, I am also interested in optimally pruning strategies for neural networks.
Pruning neural networks provides us with networks whose performance is comparable
or even better than their unpruned counterparts while enjoying substantial
decreases in energy and memory consumption. These efficiency gains from pruning
will be necessary moving forward, as the state-of-the-art models are growing ever
larger. With the energy and data required to train these models growing in tandem,
this growth is unsustainable both from an environmental and scientific perspective.


<h3>
<p style="text-align: center;">Statistical Systems and Belief Propagation</p>
</h3>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-0" src="/assets/img/abstract_mp.png" alt="" title="persistent homology" />
    </div>
</div>
<div class="caption">
</div>

The energy landscape of statistical systems is known to depend heavily on the
topological structure of its underlying interactions. However, the extent to
which the topology of the system implies its global properties is not well understood.
For example, message passing on graphical models is not well-defined when the
underlying graph contains cycles, but loopy belief propagation often converges in
these cases. [Recent work](https://arxiv.org/abs/1903.06088) has shown a connection
between the homological structure of these systems and their energy landscape, implying
a re-statement of belief propagation as a diffusion procedure on a properly-defined
sheaf structure. Finding the proper level of abstraction at which to interrogate
statistical systems is a necessary step towards broadening the distributions that
are amenable to message passing and a better understanding of belief propagation
on non-tree graphs.
