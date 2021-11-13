---
title: Non-Linear Constraint Optimization using Neural Networks
subtitle: ""
publication_types:
  - "8"
authors:
  - Palash Sethi
  - Shailesh Kumar
draft: false
featured: false
image:
  filename: featured.png
  focal_point: Smart
  preview_only: false
date: 2021-11-13T13:28:23.581Z
---
Adoption and implementation of automation technology is rapidly growing in several verticals of industry including Manufacturing, Refineries, Warehousing, Telecom etc. Any automation framework defines:

1. Each process-unit and its input-to-output relationship
2. How the process units interact with each other for the functioning of the end-to-end process. 


It should also allow us to tune certain control-parameter inputs within each process unit so that a certain business objective for productivity/profitability etc. is met. In this patent we propose a two stage ML based framework to perform constrained optimization on non-linear objective functions to find the optimal control-parameters for a given process-unit. Our approach first uses a hybrid dataset of historic along with synthetic simulation data of a process-unit to train a Neural Network based Digital Twin which accurately captures its input-to-output relationship. Next, using a novel Update-Less Back-Prop algorithm on top of this Digital Twin, we iteratively optimize the control-parameter inputs towards a defined profit based objective function. The objective function incorporates the high-level business inputs for eg.  price, cost, and profitability relations.

Neural Networks are used as universal function approximators in various industrial use cases. Our patent pertains to the field of process control optimization.  Industrial processes are non-linear and complex. The current benchmarks in the industry use linear programming methods for control parameters optimization for minimizing or maximizing an objective function which reflects the business use case such as profits, revenue or cost. Linear Programming based methods are high speed but provide less accuracy as they approximate a non-linear process with linear approximators such as linear regressors. Neural networks can be used to approximate these non-linear processes, and then further can be used to optimize the control parameters using the backpropagation algorithm in a constrained fashion. In this patent, we provide a methodology to use the backpropagation algorithm for performing constrained optimization on control parameters.

The current state of the art methodologies employs neural networks for performing non-linear control parameter optimization using various linear and non-linear optimization methods such as genetic search algorithms. Linear optimization for non-linear objective function gives accurate results only in a certain range while the non-linear methods only use the neural network in forward mode, that is, it only uses neural networks for calculating the outputs from the inputs. And the control parameters are changed further for optimization using various heuristics such as genetic search algorithms. Our work uses the gradient information calculated using backpropagation algorithm to change control parameters to minimize or maximize the objective function formulated for a specific business problem such as profit maximization, while following the constraints of the control parameters such as linear constraints and boundary constraints.
