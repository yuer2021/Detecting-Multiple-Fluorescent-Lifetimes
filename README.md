# Detecting-Multiple-Fluorescent-Lifetimes
In this project, we simulated fluorescence lifetime imaging (FLIM) data for both single pixels and pixel grids of various sizes. 

The simulated data was based on the convolution of multiple exponential decays with an experimentally determined impulse response function (IRF). 

We used the simulated data to test and compare different machine learning techniques for predicting fluorescence lifetime parameters, including least squares, orthogonal distance regression, and a 3D convolutional neural network (CNN). 

We found that the least squares model was effective in predicting intensity parameters for a grid of two fluorescent molecules, but a CNN model may be necessary for predicting multiple parameters or for more complex situations. (In addition to the detecting the ratio of the lifetime components using least squares, more parameters such as the lifetimes can be detected with more complex method such as neural networks).

We also tested the robustness of these models to small input datasets and read noise. 
