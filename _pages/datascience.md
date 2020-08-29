---
title: Data Science
layout: collection
permalink: /data-science/
collection: datascience
classes: wide
---
## Machine Learning

### PEMS for a Cogeneration Unit

The project provides an overview of Predictive Emissions Monitoring System's (PEMS) research, application, installation, and regulatory framework as well as develops predictive models for NOx emissions from a natural gas fired cogeneration unit using an open source machine learning library, Keras, and open source programming languages, Python and R. Nine neural network based predictive models were trained with 12,086 examples and tested with 3,020 examples. The neural network-based models use eight process parameters as inputs to predict NOx emissions. All models meet the regulatory requirements for precision. The best model (32-64-64-64) has four hidden layers and uses the Nadam method for optimization. The best model has a mean absolute error of 0.5982, r-value of 0.9451, and a difference of 0.14% between the measured and predicted emission values using the test dataset. The study demonstrated the feasibility of using open source machine learning library in PEMS development. It also provides guidance to facility operators to develop their own PEMS models for monitoring emissions.

Check out the full paper at [*IEEE Access*](https://ieeexplore.ieee.org/document/8771122) <https://ieeexplore.ieee.org/document/8771122>

### PEMS for a Once Through Steam Generator (OTGS)

Predictive emissions monitoring systems (PEMSs) are alternatives to continuous emissions monitoring systems (CEMSs) for monitoring air pollutants, such as NOx. Existing PEMSs and related research have focused on applying artificial neural network (ANN) algorithms. However, ANN-based models are treated as “black boxes”. Regulators and decision makers without a statistical background often have difficulty understanding these models, which poses a significant challenge for a broader application of PEMSs. In this study, we proposed a tree-based ensemble method with gradient boosting techniques for PEMS development. Compared to ANNs, tree-based methods are easier to understand and require less effort to preprocess data, fewer hyperparameters for model tuning, and less time for model training. We developed a predictive model using a gradient boosting machine learning library called XGBoost to monitor NOx emissions from a boiler located in Alberta, Canada. The model uses five process parameters as inputs and the predicted NOx emissions as output. We trained the model with 202,047 samples using random search methods to determine the best model and tested the model with 50,512 samples. We evaluated the test results against US EPA PEMS standards. The model passed all the statistical tests for precision outlined by US EPA Performance Specification 16. The Pearson correlation r value was 0.98 between the XGBoost-predicted NOx values and the CEMS-measured NOx values. The RMSE was 0.14, and the MAE was 0.09. We conclude that XGBoost is a good option for developing PEMSs. Facility operators can use the method provided in this study to develop PEMSs by themselves using the open-source library XGBoost at no cost.

Check out the full paper at [*Environmental Technology & Innovation*](https://www.sciencedirect.com/science/article/abs/pii/S2352186420313286).
[Download Preprint](./assets/files/PEMS_XGBoost_ETI.pdf)

## Data Visualization


