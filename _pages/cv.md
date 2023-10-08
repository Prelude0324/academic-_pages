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
* M.S. in Hydrology and Water Resources, Dalian University of Technology, 2023 (expected)

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
- Decision making support:
  - Optimization
  - Robustness analysis
  - Scenario discovery
  - Sensitivity analysis
- Machine learning:
  - Prediction in ungauged basins with ML
- Programming: Python, MATLAB
- Software: 
  - Gurobi (Optimizer)
  - ArcGIS
  - Adobe Illustrator
  - Origin
- Python Packages:
  - Geatpy (Evolutionary Algorithm)
  - Scikit Learn
  - Geopandas

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
