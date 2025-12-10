Overview

This repository contains the code and tutorial developed for a university machine learning assignment. The project provides a detailed, experiment-driven explanation of why Random Forests generalise well, with a specific focus on variance reduction through ensemble averaging and controlled randomness.

The tutorial integrates theoretical foundations with reproducible experiments and visual analysis. All figures included in the tutorial are generated directly from the accompanying Jupyter Notebook.

Repository Structure
├── notebooks/
│   └── raghavendra_ml_code.ipynb
│
├── figures/
│   └── (generated figures – optional)
│
├── tutorial/
│   └── Random_Forest_Variance_Reduction.pdf
│
├── README.md
└── LICENSE

Topic Focus

Model: Random Forest
Core concept: Variance reduction via ensemble size and feature subsampling

The tutorial investigates:

the effect of the number of trees (n_estimators)

the effect of feature subsampling (max_features)

stability of predictions across ensembles

ensemble diversity measured through inter-tree prediction correlation

out-of-bag (OOB) estimation as a generalisation measure

Dataset

A synthetic classification dataset is generated using the sklearn.datasets.make_classification function.

Number of samples: 1,500

Number of features: 10 (including informative, redundant, and noisy features)

Number of classes: 2, balanced

The synthetic dataset ensures full experimental control, interpretability, and reproducibility.

Requirements

To run the notebook, Python 3.9 or later is required, along with the following packages:

pip install numpy pandas matplotlib scikit-learn

How to Run

Clone the repository:

git clone https://github.com/Binnari2001/machinelearning.git


Navigate to the notebook directory:

cd random-forest-variance/notebooks


Open the Jupyter Notebook:

jupyter notebook random_forest_variance_analysis.ipynb


Run all cells sequentially to reproduce all figures, tables, and results presented in the tutorial.

Accessibility Considerations

High-contrast plotting styles are used to ensure accessibility for users with colour-vision deficiencies. Figures include descriptive titles, axis labels, and captions. Tables present numerical values without reliance on colour encoding. The tutorial is structured using clear headings to support screen readers.

License

This project is released under the MIT License. The material may be used, modified, and redistributed with appropriate attribution.
