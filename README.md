# Feature Engineering

This repository contains a collection of Jupyter notebooks and resources focused on feature engineering techniques in machine learning. Feature engineering is a crucial step in the data preprocessing pipeline, involving the creation, transformation, and selection of features to improve model performance.

## Table of Contents

- [Overview](#overview)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Overview

The repository is organized into several key areas of feature engineering:

- **Data Encoding**: Techniques for converting categorical variables into numerical representations.
- **Handling Imbalanced Dataset**: Methods to address class imbalance in datasets.
- **Handling Missing Values**: Approaches for dealing with missing data in datasets.
- **Handling Outliers**: Strategies for identifying and managing outliers in data.

Each section contains Jupyter notebooks with practical implementations and explanations.

## Project Structure

```
Feature Engineering/
├── .gitignore
├── README.md
├── requirements.txt
├── Data Encoding/
│   ├── LabelEncoding.ipynb
│   ├── OneHotEncoding.ipynb
│   ├── OrdinalEncoding.ipynb
│   └── TargetGuidedOrdinalEncoding.ipynb
├── Handling Imbalanced Dataset/
│   ├── Sampling.ipynb
│   └── SMOTE.ipynb
├── Handling Missing Values/
│   ├── Imputation.ipynb
│   └── LoadingDataset.ipynb
└── Handling Outliers/
    └── box_plot.ipynb
```

### Data Encoding

This folder contains notebooks demonstrating various encoding techniques:

- **LabelEncoding.ipynb**: Implements label encoding for ordinal categorical variables.
- **OneHotEncoding.ipynb**: Demonstrates one-hot encoding for nominal categorical variables.
- **OrdinalEncoding.ipynb**: Shows ordinal encoding techniques.
- **TargetGuidedOrdinalEncoding.ipynb**: Implements target-guided ordinal encoding based on target variable relationships.

### Handling Imbalanced Dataset

Notebooks in this folder focus on addressing class imbalance:

- **Sampling.ipynb**: Covers various sampling techniques like undersampling and oversampling.
- **SMOTE.ipynb**: Implements Synthetic Minority Over-sampling Technique (SMOTE) for generating synthetic samples.

### Handling Missing Values

This section deals with missing data imputation:

- **Imputation.ipynb**: Demonstrates various imputation methods (mean, median, mode).
- **LoadingDataset.ipynb**: Shows how to load and prepare datasets for missing value analysis.

### Handling Outliers

- **box_plot.ipynb**: Uses box plots and statistical methods to detect and handle outliers.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/ashay-patil/Feature-Engineering.git
   cd Feature Engineering
   ```
2. Make virtual environment :
   ```bash
   conda create -p venv python==3.10.0
   conda activate .\venv\
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Dependencies

The project requires the following Python libraries:
- scikit-learn==1.3.2
- imbalanced-learn==0.11.0
- numpy==1.26.4
- pandas==2.1.4
- seaborn==0.13.2

## Usage

1. Ensure you have Jupyter Notebook or JupyterLab installed.
2. Navigate to the desired folder and open the relevant notebook:
   ```bash
   jupyter notebook
   ```
3. Run the cells in order to understand and execute the feature engineering techniques.

Each notebook includes:
- Theoretical explanations
- Code implementations
- Visualizations where applicable
- Best practices and considerations

### Made by Ashay Patil