---
title: "Detection of Discriminative Neurological Circuits Using Hierarchical Graph Convolutional Networks in fMRI Sequences"
collection: publications
permalink: /publication/2020-BrainCircuit-number-4
excerpt: "<br/><img src='/images/paper3.PNG'/>"
date: 2020-10-04
venue: '3rd Workshop on GRaphs in biomedicAl Image anaLysis'
---
Graph convolutional network (GCN) has shown its potential on modeling functional MRI connectivity and recognition tasks. However, conventional GCN layers generally perform graph propagation operations which do not optimize the original graph topology hence lack the modeling of hierarchical graph representation. Besides, although the interpretability of GCN has also been widely investigated, such methods only limit to highlight one or two independent affected brain regions instead of neurological circuits, which are more desirable in functional connectivity studies. In this paper, we propose a hierarchical dynamic GCN, which combines the information from both low-order graph of brain regions and high-order graph of brain region clusters. The algorithm learns a consistent dynamic graph pooling rule which helps improve the classification accuracy by hierarchical graph representation learning and contributes to identify the affected neurological circuits. We employed two datasets to better test the performance of the proposed method: ADNI dataset containing 177 AD patients and 115 controls, and OCD (Obsessive-Compulsive Disorder) dataset containing 67 OCD patients and 61 controls. The classification accuracy reaches 88.0% on ADNI dataset and 91.7% on OCD dataset using 5-fold cross-validation. The affected brain circuits were also identified, which are in consistent with other psychological studies.

[See slides for descriptions here](http://academicpages.github.io/files/paper8.pptx)
[Download the paper here](https://doi.org/10.1007/978-3-030-60365-6\_12)
