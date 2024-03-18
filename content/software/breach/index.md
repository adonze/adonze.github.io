---
title: "Breach" 
tags: ["STL", "Matlab"]
description: "Breach Toolbox"
summary: "Breach is a Matlab/Simulink toolbox for time series analysis and simulation-based analysis of dynamical/CPS/Hybrid systems. It features Signal Temporal Logic (STL) monitoring, test case generation and optimization-based falsification methods."
#cover:
#    image: "/data1.png"
#    alt: "Figure caption"
#    relative: false
editPost:
    URL: "https://github.com/decyphir/breach"
    Text: "GitHub repository"
showToc: false
disableAnchoredHeadings: false

---

Breach is a Matlab toolbox for time series analysis and simulation-based analysis of dynamical/CPS/Hybrid systems. It can be useful to the prospective user (you) in the following situations:

- You have **time series data** and wants to check whether it satisfies some property 
- You need **signal temporal logic (STL) monitoring capability**, e.g., to check formal requirements on your data
- You have a **Simulink models** and wants to perform **extensive testing** by running multiple simulations (e.g., parameter sweep) and quickly browse through the results, and/or assert whether some (STL) property is satisfied by simulations (random/Monte-Carlo testing) 
- You need to **falsify** an STL requirement using various optimization algorithm, i.e., find **test cases of interest** 
- You want to do some or all of the above to for a model implemented with **a simulator other than Simulink**.

More on [Github](https://github.com/decyphir/breach)