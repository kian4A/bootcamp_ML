# Eigenfaces — Face Compression & Recognition

Team 01 — **The Hidden Layer**  
Rahnema College Machine Learning Bootcamp

This project implements PCA and KNN with NumPy to compress, reconstruct, and recognize faces using the Olivetti Faces dataset.

## Contents

- Jupyter notebook with code and experiments
- Presentation slides
- Project report in PDF and LaTeX
- Figures and supporting assets

## Experiments

- Reconstruction error and explained variance
- PCA component selection using Elbow and Silhouette
- KNN evaluation with Accuracy, Precision, Recall, and F1
- Five-fold cross-validation with rotating 70/10/20 train/validation/test splits

## Run

Install the dependencies, then open the notebook and run all cells:

```bash
pip install numpy pandas matplotlib scikit-learn jupyter
```

For the LaTeX report, use XeLaTeX with the required fonts and image folders.

**Note:** Some saved results come from the earlier 60/20/20 split. Restart the kernel and run all cells to refresh results for 70/10/20.
