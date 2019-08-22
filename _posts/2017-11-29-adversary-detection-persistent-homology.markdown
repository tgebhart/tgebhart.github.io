---
layout: post
title:  "Adversary Detection in Neural Networks via Persistent Homology"
date:   2019-01-08 01:00:00
last_modified_at:  2017-11-28 01:00:00
excerpt: "..."
categories: ""
tags:  adversary detection
image:
  feature: convolution.jpg
  topPosition: -10px
bgContrast: dark
bgGradientOpacity: darker
syntaxHighlighter: no
---

## Adversary Detection in Neural Networks via Persistent Homology

##### Thomas Gebhart and Paul Schrater

Full text [here](https://arxiv.org/abs/1711.10056){:target="_blank"}.

We outline a detection method for adversarial inputs to deep neural networks. By viewing
neural network computations as graphs upon which information flows from input space to output distribution, we compare the differences in graphs induced by different inputs. Specifically,
by applying persistent homology to these induced graphs, we observe that the structure of the
most persistent subgraphs which generate the first homology group differ between adversarial
and unperturbed inputs. Based on this observation, we build a detection algorithm that depends only on the topological information extracted during training. We test our algorithm
on MNIST and achieve 98% detection adversary accuracy with F1-score 0.98.
