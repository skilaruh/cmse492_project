# Credit Scoring with Neural Networks

## Details
Exploring the use of neural networks for predicting credit card default risk. Using a publicly available credit dataset, I aim to train and compare machine learning models (logistic regression, random forest, and feedforward neural networks) to predict whether a customer will default on their credit card payment.

## Project Directory Structure
```text
cmse492_project/
├── README.md                # Project overview and setup instructions
├── .gitignore               # Files and directories ignored by Git
├── data/
│   ├── raw/                 # Original dataset (e.g., UCI Credit Card Default dataset)
│   └── processed/           # Cleaned and preprocessed datasets used for modeling
├── notebooks/
│   └── exploratory/         # Jupyter notebooks for EDA, visualization, and experiments
├── src/
│   ├── preprocessing/       # Scripts for cleaning data, encoding features, and scaling
│   ├── models/              # Model definitions (logistic regression, neural networks, etc.)
│   └── evaluation/          # Scripts for model evaluation, metrics, and explainability
├── figures/                 # Generated plots, performance curves, and visualizations
├── docs/                    # Report, documentation, and references
└── requirements.txt         # List of dependencies needed to run the project
```

## Setup Instructions
1. Clone repo 
   - ```bashhttps://github.com/skilaruh/cmse492_project.git```
2. Install dependencies
   - ```pip install -r requirements.txt```

## Notable Dependencies
- Tensorflow
- scikit-learn
- matplotlib
- imbalanced-learn
- pandas
