# MATLAB Feedforward Deep Neural Network for Battery State of Charge Estimation

The provided code along with the [associated files](https://github.com/ghanrabban/MATLAB-Extended-Kalman-Filter-for-EV-Battery), forms the core dataset for the forthcoming research titled "DSP-Based Estimation of Battery State of Charge: Comparative Study on Extended Kalman Filter and Feedforward Deep Neural Networks," which the preprint version has been published at [Heliyon First Look](https://dx.doi.org/10.2139/ssrn.4881808)

This code is a modified version of the original work by Carlos Vidal et al. from McMaster University, titled [LG 18650HG2 Li-ion Battery Data and Example Deep Neural Network xEV SOC Estimator Script](https://doi.org/10.17632/cp3473x7xv.3).

Several modifications have been made, primarily to adjust the neuron layers and to utilize NVIDIA CUDA GPU power for fitting different battery dataset, which originates from the same university and is published on [Mendeley Data - Samsung INR21700 30T 3Ah Li-ion Battery Data](https://data.mendeley.com/datasets/9xyvy2njj3/1).

The "Battery Datasets" folder is divided into "Preprocessed Dataset" and "Raw Dataset" subfolders. The Preprocessed Dataset folder contains a list of input data for machine learning training, please do not modify these files. The Raw Dataset folder contains the original Samsung INR21700 30T 3Ah Li-ion Battery Dataset.

The "Original Code" folder includes the original works by Carlos Vidal and his colleagues.

Lastly, the "Simulation Results" folder contains a collection of training results and supplementary data for the research paper.
