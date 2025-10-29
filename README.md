# Deep Learning Notebook Collection

This repository collects Jupyter notebooks and datasets used to explore core deep learning concepts. Each notebook focuses on a specific topic, ranging from gradient descent fundamentals to convolutional neural networks and regularization techniques. The notebooks are intended for interactive experimentation in JupyterLab or the classic Jupyter Notebook interface.

## Repository Structure

| Path | Description |
| --- | --- |
| `backpropagtion.ipynb` | Manual walkthrough of backpropagation and gradient updates. |
| `batch_norm.ipynb` | Demonstrates batch normalization and its effect on training dynamics. |
| `dropout1.ipynb`, `Dropout.ipynb` | Experiments with dropout regularization and its impact on overfitting. |
| `early-stoppping.ipynb` | Shows how early stopping can prevent overfitting during training. |
| `EWMA.ipynb` | Applies exponentially weighted moving averages for smoothing metrics. |
| `Graduate_admission.ipynb` | Predicts graduate admission outcomes using neural networks. |
| `Hand_written_digits.ipynb` | Classifies handwritten digits with feedforward networks. |
| `Hyperparameter_tuning/` | Contains datasets and notebooks exploring tuning strategies such as layer depth and learning rates. |
| `CNN/` | Contains convolution-focused notebooks covering series padding and pooling operations. |
| `Vanishing_GD_Problem.ipynb` | Investigates vanishing gradients and mitigation techniques. |
| `regularization.ipynb`, `normalizing_inputs.ipynb` | Additional notebooks covering feature scaling and regularization. |

The repository also includes several CSV files (for example `AP.csv`, `DailyDelhiClimateTest.csv`, `Social_Network_Ads.csv`) that serve as datasets for the corresponding notebooks.

## Prerequisites

* Python 3.9 or later
* JupyterLab or Jupyter Notebook
* Common scientific libraries (installable via `pip install -r requirements.txt` if you maintain one, or manually install packages such as `numpy`, `pandas`, `matplotlib`, `scikit-learn`, and `tensorflow`/`pytorch` as needed by each notebook)

## Getting Started

1. Create and activate a virtual environment (optional but recommended):
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # On Windows use `.venv\\Scripts\\activate`
   ```
2. Install the required Python packages.
3. Launch Jupyter:
   ```bash
   jupyter lab
   # or
   jupyter notebook
   ```
4. Open any notebook from this repository to explore the experiments.
