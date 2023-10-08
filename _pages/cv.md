---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B.S. in Water Conservancy and Hydropower Engineering , Dalian University of Technology, 2021
* M.S. in Hydrology and Water Resources, Dalian University of Technology, 2024 (expected)

# Research Experience

- Research on Water-Energy-Ecosystem Nexus in hydro-based power systems (Apr 2023 - Present):
  - Establishing a multi-timescale two-layer nested framework to explore the Water-Energy-Ecosystem Nexus in hydro-based power systems.
  - The outer layer consists of a long-term river basin-wide multi-objective optimization model, considering objectives such as water supply, hydropower generation, shipping, and sub-daily hydrological regime (hydropeaking).
  - The inner layer consists of a scenario-based stochastic programming model for multiple grids peak shaving operation under uncertainty originating from variable renewable energy, with an hourly resolution.
- Research on multi-objective decision analysis for hydropower system (Aug 2022 - Mar 2023):
  - Constructing a short-term multi-objective mixed integer linear programming (MILP) model integrating multiple functions of hydropower reservoirs, including peak shaving, ship navigation, and power generation.
  - Developing a solution and decision-making framework based on Normalized Normal Constraint (NNC) and TOPSIS methods to obtain Pareto solutions and coordinate multi-sector performance.
- Research on short-term co-scheduling of giant and re-regulation reservoirs (Feb 2022 - Jul 2022):
  - Employing constraint aggregation and hexahedron gridding strategies to handle high-dimensional non-convex and nonlinear constraints in hydropower operation and improve solution efficiency.
  - .Establishing a multi-objective optimization model based on Normal Boundary Intersection (NBI) and MILP to analyze and mediate the conflict between peak shaving and shipping.
- Basic method practices in water resources system (Python) (Sep 2021 - Jan 2022):
  - Optimization methods for reservoir optimal operation: Genetic Algorithm (GA), Dynamic Programming (DP), Non-dominated Sorting Genetic Algorithm II (NSGA-II), etc.
  - Machine learning methods for runoff forecasting : Artificial Neural Network (ANN), Support Vector Regression (SVR), Seasonal AutoRegressive Integrated Moving Average (SARIMA), etc.

Skills
======
- Optimization
  - Deterministic optimization: Mixed Integer Linear Programming (MILP), Dynamic Programming (DP), Genetic Algorithm (GA)
  - Uncertainty optimization:  Stochastic Programming (SP)
  - Multi-objective optimization: Normalized Normal Constraint (NNC), Non-dominated Sorted Genetic Algorithm II (NSGA-II)

- Statistics / Machine Learning：
  - Supervised Learning: Artificial Neural Network (ANN), Support Vector Regression (SVR)
  - Unsupervised Learning: Kernel Density Estimation (KDE), K-means


- Programming: Python, MATLAB, C
- Languages:
  - Chinese (native speaker)
  - English (IELTS, 7.0)
- Software: 
  - [Gurobi](https://www.gurobi.com/) (Optimizer)
  - [ArcGIS](https://www.esri.com/en-us/home) 
  - [Adobe Illustrator](https://www.adobe.com/)
  - [Origin](https://www.originlab.com/)
  - ...
- Python Packages:
  - [Pyomo](http://www.pyomo.org/) (Optimization Modeling)
  - [Geatpy](https://github.com/geatpy-dev/geatpy) (Evolutionary Algorithm)
  - [Scikit Learn](https://scikit-learn.org/stable/index.html) (Machine Learning)
  - [Tensorflow](https://www.tensorflow.org/) (Deep Learing)
  - [Geopandas](https://geopandas.org/en/stable/) (Geospatial Data Processing)
  - ...

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
