---
title: "Alternating between Surrogate Model Construction and Search for Configurations of an Autonomous Delivery System"
collection: publications
permalink: /publication/2024-SANER
excerpt: '
Autonomous robots are emerging as a solution to various challenges of last mile goods delivery, like reducing traffic congestion, pollution, and costs. The configuration of an autonomous delivery robots system requires balancing aspects like delivery rate, cost of robots’ operation, and required monitoring efforts. Our industry partner Panasonic is employing a search-based approach to find the configurations of the system that optimise these three aspects for a given set of customers’ orders. The approach uses a simulator to assess the different configurations in the fitness functions’ computation. Due to the high cost of the simulation, the whole search-based approach is computationally expensive. A classic approach to speed up such approaches is to use surrogate models trained on example simulation data that allow to approximate the results of a simulated configuration with negligible computational cost. A risk when using such approaches is to underestimate the cost of building the surrogate model itself, that can exceed the computational gain obtained during the search, thus making the adoption of surrogate models detrimental. In this work, we propose an approach in which the surrogate model is not trained before the search; instead, the approach alternates between training the model on subsets of data of increasing size, and searching using these cheaper models until the search stagnates. Experiments over 144,000 settings of the search show that the proposed approach can significantly reduce the cost of searching for configurations, while having an acceptable impact on the quality of the configurations it finds.'
date: 2024-03
venue: 'The IEEE International Conference on Software Analysis, Evolution and Reengineering (SANER 2024, Industry Track)'
#paperurl: 'https://doi.org/10.1145/2938503.2938511'
#doi: 10.1145/2938503.2938511
#citation: ''
---

