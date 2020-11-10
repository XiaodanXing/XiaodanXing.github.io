---
title: "Dynamic Spectral Graph Convolutional Networks with Assistant Task Learning for Early MCI Diagnosis"
collection: publications
permalink: /publication/2019-DSGCN-number-3
excerpt: "<br/><img src='/images/paper2.PNG'>"
venue: 'Medical Image Computing and Computer Assisted Interventions 2019'
date: 2019-10-16
paperurl: 'https://doi.org/10.1007/978-3-030-32251-9_70'
---
Functional Connectivity (FC) matrices measure the regional interactions in the brain and have been widely used in neurological brain disease classification. A brain network, also named as connectome, could form a graph structure naturally, the nodes of which are brain regions and the edges are interregional connectivity. Thus, in this study, we proposed novel graph convolutional networks (GCNs) to extract efficient disease-related features from FC matrices. Considering the time-dependent nature of brain activity, we computed dynamic FC matrices with sliding-windows and implemented a graph convolution based LSTM (long short time memory) layer to process dynamic graphs. Moreover, the demographics of patients were also used as additional outputs to guide the classification. In this paper, we proposed to utilize the demographic information as extra outputs and to share parameters among three networks predicting subject status, gender and age, which serve as assistant tasks. We tested the performance of the proposed architecture in ADNI II dataset to classify Alzheimer’s disease patients from normal controls. The classification accuracy, sensitivity and specificity reach 90.0%, 91.7% and 88.6% on ADNI II dataset.   
