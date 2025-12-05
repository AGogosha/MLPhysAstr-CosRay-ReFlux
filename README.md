# UNC-MLPhysAstr Final Project: ML Cosmic Ray Flux Reconstruction

Final project material for UNC course: Machine Learning in Physics and Astronomy

Material by Carter Chapman and Andrei Gogosha

License: BSD-3

PHYS 448 / ASTR 448 / Fall 2025
The University of North Carolina at Chapel Hill

## Project Description

## A summary of the repository contents:

### [Final Paper](./paper)

Tex file and pdf copy of final paper writen for this project as well as a pdf copy of the final presentation given on this project.

### [Data](./Data)

All data sets needed to run the included Notebooks. Data is taken from the [Pierre Auger Observatory Open Data release](https://doi.org/10.5281/zenodo.10488964) or generated using the [data preprocessing notebook](src/data_processing.ipynb).

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
