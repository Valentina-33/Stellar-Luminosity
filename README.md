# Stellar Luminosity Regression

## Purpose

This project explores how regression models learn from data by studying the relationship between stellar mass and luminosity. Linear and polynomial regression models are implemented from first principles using NumPy, including prediction, cost calculation, gradients, and gradient descent. The project also compares both models and explores their behavior inside and outside the observed data range.

## Requirements

- Python 3
- NumPy
- Matplotlib
- Jupyter Notebook

## How to Run

1. Clone or download this repository.
2. Open `stellar_luminosity_hands_on.ipynb` in Jupyter Notebook or JupyterLab.
3. Run all cells from top to bottom.

No machine-learning libraries such as scikit-learn, TensorFlow, or PyTorch are required.

## Main Learning

The experiment showed that a model can successfully minimize its error while still being limited by its representation. The linear model learned a straight-line approximation, while adding the squared mass feature allowed the polynomial model to better represent the nonlinear behavior of the observed data. The extrapolation experiment also showed that a model can produce predictions outside the training range even when the available data does not provide enough evidence to trust them.
