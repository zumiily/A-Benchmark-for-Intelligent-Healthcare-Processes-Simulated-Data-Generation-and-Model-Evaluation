# A Benchmark for Intelligent Healthcare Processes： Simulated Data Generation and Model Evaluation
A data generation method based on conditional probability transition functions within the partially observable Markov decision process (POMDP) framework, together with a benchmark algorithm testing library designed for the generated datasets.

## Overview
![](/fig/fig.png)
As shown in the figure, within the simulated data generation module, we construct seven health state transition models with distinct pathological characteristics based on conditional probabilities under the partially observable Markov decision process (POMDP) framework. These models are then used to generate seven corresponding simulated datasets. In the model evaluation module, based on the TIME SERIES LIBRARY proposed by Wang et al., we select several existing models and incorporate other advanced models to evaluate their predictive performance on the datasets. 

## Open-Source Notice
The code for this project will be released publicly after the corresponding paper is accepted.
