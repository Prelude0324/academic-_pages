---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<h1 style="color: #3cb371;">Education</h1>

* <div class="container" style="display: flex; justify-content: space-between;">
      <div><b>B.S. in Water Conservancy and Hydropower Engineering, Dalian University of Technology</b></div>
      <div>(2021)</div>
      </div>

* <div class="container" style="display: flex; justify-content: space-between;">
      <div><b>M.S. in Hydrology and Water Resources, Dalian University of Technology</b></div>
      <div>(2024, expected)</div>
      </div>

<h1 style="color: #3cb371;">Research Experience</h1>

- <div class="container" style="display: flex; justify-content: space-between;">
      <div><b>Research on Water-Energy-Ecosystem Nexus in hydro-based power systems</b></div>
      <div>(Apr 2023 - Present)</div>
      </div>

  - Establishing a multi-timescale two-layer nested framework to explore the Water-Energy-Ecosystem Nexus in hydro-based power systems.

  - The outer layer consists of a long-term river basin-wide multi-objective optimization model, considering objectives such as water supply, hydropower generation, shipping, and sub-daily hydrological regime (hydropeaking).

  - The inner layer consists of a scenario-based stochastic programming model for multiple grids peak shaving operation under uncertainty originating from variable renewable energy, with an hourly resolution.

- <div class="container" style="display: flex; justify-content: space-between;">
      <div><b>Research on multi-objective decision analysis for hydropower system</b></div>
      <div>(Aug 2022 - Mar 2023)</div>
      </div>

  - Constructing a short-term multi-objective mixed integer linear programming (MILP) model integrating multiple functions of hydropower reservoirs, including peak shaving, ship navigation, and power generation.
  - Developing a solution and decision-making framework based on Normalized Normal Constraint (NNC) and TOPSIS methods to obtain Pareto solutions and coordinate multi-sector performance.

- <div class="container" style="display: flex; justify-content: space-between;">
      <div><b>Research on short-term co-scheduling of giant and re-regulation reservoirs</b></div>
      <div>(Feb 2022 - Jul 2022)</div>
      </div>

  - Employing constraint aggregation and hexahedron gridding strategies to handle high-dimensional non-convex and nonlinear constraints in hydropower operation and improve solution efficiency.
  - .Establishing a multi-objective optimization model based on Normal Boundary Intersection (NBI) and MILP to analyze and mediate the conflict between peak shaving and shipping.

- <div class="container" style="display: flex; justify-content: space-between;">
      <div><b>Basic method practices in water resources system (Python)</b></div>
      <div>(Sep 2021 - Jan 2022)</div>
      </div>

  - Optimization methods for reservoir optimal operation: Genetic Algorithm (GA), Dynamic Programming (DP), Non-dominated Sorting Genetic Algorithm II (NSGA-II), etc.
  - Machine learning methods for runoff forecasting : Artificial Neural Network (ANN), Support Vector Regression (SVR), Seasonal AutoRegressive Integrated Moving Average (SARIMA), etc.

<h1 style="color: #3cb371;">Skills</h1>

- **Optimization**
  - Deterministic optimization: Mixed Integer Linear Programming (MILP), Dynamic Programming (DP), Genetic Algorithm (GA)
  - Uncertainty optimization: Stochastic Programming (SP)
  - Multi-objective optimization: Normalized Normal Constraint (NNC), Non-dominated Sorted Genetic Algorithm II (NSGA-II)

- **Statistics / Machine Learning:**
  - Supervised Learning: Artificial Neural Network (ANN), Support Vector Regression (SVR)
  - Unsupervised Learning: Kernel Density Estimation (KDE), K-means


- **Programming:** Python, MATLAB, C
- **Languages:**
  - Chinese (native speaker)
  - English (IELTS, 7.0)
- **Software:** 
  - [Gurobi](https://www.gurobi.com/) (Optimizer)
  - [ArcGIS](https://www.esri.com/en-us/home) 
  - [Adobe Illustrator](https://www.adobe.com/)
  - [Origin](https://www.originlab.com/)
  - ...
- **Python Packages:**
  - [Pyomo](http://www.pyomo.org/) (Optimization Modeling)
  - [Geatpy](https://github.com/geatpy-dev/geatpy) (Evolutionary Algorithm)
  - [Scikit Learn](https://scikit-learn.org/stable/index.html) (Machine Learning)
  - [Tensorflow](https://www.tensorflow.org/) (Deep Learing)
  - [Geopandas](https://geopandas.org/en/stable/) (Geospatial Data Processing)
  - ...

<h1 style="color: #3cb371;">Publications</h1>

  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
