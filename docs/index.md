---
title: Higher-Order Network Models for Temporal Network Data
permalink: /
---

Network-based data mining techniques such as graph mining, (social) network analysis, link prediction and graph clustering form an important foundation for data science applications in computer science, computational social science, and the life sciences. They help to detect patterns in large data sets that capture dyadic relations between pairs of genes, species, humans, or documents and they have improved our understanding of complex networks.

While the potential of analysing graph or network representations of relational data is undisputed, we increasingly have access to data on networks that contain more than just dyadic relations. Consider, e.g., data on user click streams in the Web, time-stamped social networks, gene regulatory pathways, or time-stamped financial transactions. These are examples for time-resolved or sequential data that not only tell us who is related to whom but also when and in which order relations occur. Recent works have exposed that the timing and ordering of relations in such data can introduce higher-order, non-dyadic dependencies that are not captured by state-of-the-art graph representations. This oversimplification questions the validity of graph mining techniques in time series data and poses a threat for interdisciplinary applications of network analytics.

To address this challenge, researchers have developed advanced graph modelling and representation techniques based on higher- and variable-order Markov models, which enable us to model non-Markovian characteristics in time series data on networks. Introducing this exciting research field, the goal of this tutorial is to give an overview of cutting-edge higher-order data analytics techniques. Key takeaways for attendees will be (i) hands-on experience with higher-order network analytics, model selection, and data visualisation, and (ii) a demonstration of the benefits of higher-order network analytics in real time series data on social systems.

# Tutors

[Anton Eriksson](https://antoneri.github.io/)  
Researcher  
Complex Systems Group  
Department of Physics  
Umeå University, SE  

[Jürgen Hackl](https://hackl.science)  
Assistant Professor  
Department of Civil Engineering and Industrial Design  
School of Engineering  
University of Liverpool, UK  

# Prerequisites

Participants should bring a laptop with a python 3.x environment. For the Session 1, a Python installation with jupyter, numpy, numba, pandas, sklearn and matplotlib (Optionally Docker and docker-compose). is required. For [`pathpy`](http://www.pathpy.net) the setup instructions can be found [here](/pathpy-tutorials/setup). Prior exposure to python is beneficial.

# Schedule

### Welcome Note and Tutorial Overvie

### Session 1: Mapping higher-order network flows

**Intro: Mapping higher-order network flows** (20 min) > [slides](https://github.com/mapequation/netscix-2020-tutorial)
- Coding theory
- The Map Equation
- Sparse Markov models

**Live Coding** (40 min) > [code](https://github.com/mapequation/netscix-2020-tutorial)

Unit | Topic | Time
----|----|----|----
1 | Infomap | 10 min
2 | Sparse state networks | 15 min
3 | Model selection and community detection | 15 min

### Coffee Break

### Session 2: Higher-order Network Analysis and Visualisation with `pathpy`

**Intro: Higher-Order Network Analytics for Time Series Data** (15 min) > [slides](https://github.com/pathpy/pathpy-tutorials/blob/master/docs/2020-01-NetSciX-short.pdf)
- Causal paths in temporal network data
- Ordering matters in time series data
- Higher-order generative models for causal paths
- Representation learning in temporal network data

**Live Coding** (40 min) > [code](https://github.com/pathpy/pathpy-tutorials/blob/master/code/NetSciX-2020.ipynb)

Unit | Topic | Time
----|----|----|----
1 | Introduction to [`pathpy`](http://www.pathpy.net) | 10 min
2 | (Spatial)-Temporal Network Analysis and Visualisation in [`pathpy`](http://www.pathpy.net) | 10 min
3 | Higher-order Models of Paths | 10 min
4 | Multi-order Model Selection | 10 min



