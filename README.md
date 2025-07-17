# A Benchmark for Intelligent Healthcare Processes： Simulated Data Generation and Model Evaluation
A data generation method based on conditional transition probability functions under the framework of partially observable Markov decision processes (POMDP), along with a benchmark algorithm testing library tailored for the generated datasets.

## Overview
<img width="1906" height="699" alt="image" src="https://github.com/user-attachments/assets/780baed4-0d2c-4a81-9adb-c790efa15b66" />
As shown in the figure, within the simulated data generation module, we construct seven health state transition models with distinct pathological characteristics under the framework of partially observable Markov decision processes (POMDP), based on a conditional probability. These models are used to generate seven corresponding simulated datasets. In the model evaluation module, we test these seven datasets using the TIME SERIES LIBRARY proposed by Wang et al.

## Open-Source Notice
The code for this project will be released publicly after the corresponding paper is accepted.

## References
Wang Y, Wu H, Dong J, et al. Deep time series models: A comprehensive survey and benchmark[J]. arXiv preprint arXiv:2407.13278, 2024.

Greff K, Srivastava R K, Koutník J, et al. LSTM: A search space odyssey[J]. IEEE transactions on neural networks and learning systems, 2016, 28(10): 2222-2232.

Beck M, Pöppel K, Spanring M, et al. xlstm: Extended long short-term memory[J]. arXiv preprint arXiv:2405.04517, 2024.
