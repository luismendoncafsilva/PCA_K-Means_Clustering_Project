# PCA Microvan Project

This project applies Principal Component Analysis (PCA) to survey data related to consumer preferences for microvans.  
The goal is to identify key factors influencing customer decisions and to reduce data dimensionality while preserving essential information.

## Project Overview

The dataset comprises responses from potential customers regarding various aspects of microvan features and their personal demographics.  
By performing PCA, we aim to:

- Reduce the number of variables while retaining most of the variance in the data.
- Identify underlying components that capture the essence of customer preferences.
- Visualize the data in a lower-dimensional space for better interpretability.

## Dataset Description

The dataset includes the following types of variables:

- **Survey Responses**: Opinions on various microvan features (e.g., safety importance, performance, design preferences).
- **Demographics**: Information such as age, income, number of children, and education level.

Each variable is coded for analysis, and a data dictionary is provided within the notebook for reference.

## Methodology

1. **Data Preprocessing**:
   - Handling missing values.
   - Standardizing variables to have zero mean and unit variance.

2. **Principal Component Analysis**:
   - Applying PCA to the standardized data.
   - Determining the number of components to retain based on explained variance.
   - Interpreting the principal components by examining variable loadings.

3. **Visualization**:
   - Scree plot to show explained variance by each component.
   - Biplots to visualize data points and variable contributions in the principal component space.

## Results

- **Explained Variance**: The first few principal components capture a significant portion of the total variance, indicating that dimensionality reduction is effective.
- **Component Interpretation**: Each principal component represents a combination of original variables, shedding light on underlying factors influencing customer preferences.
- **Visualization**: The biplots reveal clusters of respondents with similar preferences and highlight the most influential variables.

## Getting Started

### Prerequisites

Ensure you have the following installed:

- Python 3.x
- Jupyter Notebook
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn

### Running the Notebook

1. Clone the repository:
   ```bash
   git clone https://github.com/luismendoncafsilva/PCA_Project.git
