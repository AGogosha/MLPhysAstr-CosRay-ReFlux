# UNC-MLPhysAstr Final Project: ML Cosmic Ray Flux Reconstruction

Final project material for UNC course: Machine Learning in Physics and Astronomy

Material by Carter Chapman and Andrei Gogosha

License: BSD-3

PHYS 448 / ASTR 448 / Fall 2025
The University of North Carolina at Chapel Hill

## Project Description

We analyze data from the Pierre Auger Observatory to identify which atmospheric variables most affect cosmic-ray count rates. Using several years of temperature, pressure, and air density measurements, we train a linear $\texttt{SGDRegressor}$ and a nonlinear $\texttt{HistGradient Boosting Regressor}$, optimized via cross-validation. The $\texttt{SGDRegressor}$ achieves $\mathbf{7.87 \pm 0.01}$ MAE, while the gradient boosting model improves accuracy to $\mathbf{6.59 \pm 0.03}$ MAE. SHAP-based feature importance reveals the dominant atmospheric drivers. Our results demonstrate that machine-learning methods, particularly gradient boosting, effectively model the atmospheric modulation of cosmic-ray flux.

## A summary of the repository contents:

### [Final Paper](./paper)

Tex file and pdf copy of final paper writen for this project as well as a pdf copy of the final presentation given on this project.

### [Data](./data)

All data sets needed to run the included Notebooks. Data is taken from the [Pierre Auger Observatory Open Data release](https://doi.org/10.5281/zenodo.10488964) or generated using the [data preprocessing notebook](./src/data_preprocessing.ipynb).

### [Src](./src)

Notebooks to preprocess Auger data and train the ML models used in this project.

### [Plots](./plots)

Where all of the visualizations generated in the training notebooks are saved.

## Necessary Packages

Copy one of the lines of code below to install all the packages used in this project

<pre>
pip install matplotlib numpy pandas scikit-learn shap
<i>or</i>
conda install -c conda-forge matplotlib numpy pandas scikit-learn shap
</pre>
