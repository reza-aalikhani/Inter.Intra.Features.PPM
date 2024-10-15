# Inter.Intra.Features.PPM
Repository Overview
This repository contains supplementary material for the article titled "Enhancing Remaining Time Prediction in Business Processes by Considering System-Level and Resource-Level Inter-Case Features" by Reza Aalikhani, Mohammad Fathian, and Mohammad Reza Rasouli.

Purpose
This repository provides implementations of various models for remaining time prediction using a Predictive Process Monitoring approach. The experiments conducted aim to evaluate the impact of inter-case features on the accuracy of time predictions.

Methodology
To enhance intra-case features, we incorporate inter-case features such as resource multitasking, open cases, and other metrics related to resource behavior. The primary objective of these techniques is to predict the completion time of cases while minimizing the Mean Absolute Error (MAE).

Benchmark Details
The benchmark includes implementations of five sequence encodings (for further details, refer to the paper):

Last State Encoding
Aggregation Encoding
Previous Encoding
Combined Encoding
Index-Based Encoding
Additionally, the repository features four bucketing methods (see the paper for more information):

No Bucketing
State-Based Bucketing
Clustering
Prefix Length Based
The benchmark experiments utilize four regression models:

Random Forest
Gradient Boosted Trees (XGBoost)
Decision Tree
Support Vector Regressor (SVR)
