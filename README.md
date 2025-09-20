# Linear_Regression_Model

A comprehensive project on linear regression, showcasing practical steps to predict continuous outcomes—in this case, the presence of heart disease—using a real-world dataset and modern Python tools.

## Table of Contents

- [Overview](#overview)
- [Screenshots](#screenshots)
- [Features](#features)
- [Getting Started](#getting-started)
- [Requirements](#requirements)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Overview

This project demonstrates a full machine learning pipeline using linear regression, from data loading and preprocessing, through exploratory analysis and feature engineering, to model training, evaluation, and visualization. The dataset used (`heart.csv`) is an example of structured health data, and the codebase is provided in a Jupyter notebook for interactive exploration.

## Screenshots

Sample project directory structure:

![image1](image1)

---

## Features

- **Data Cleaning:** Handles duplicates and missing values.
- **Categorical Encoding:** Converts categorical columns and applies one-hot encoding.
- **Exploratory Data Analysis:** Distribution plots, correlation heatmap, and pairplots.
- **Feature Engineering:** Log-transform skewed variables for better model performance.
- **Preprocessing:** Feature scaling and handling infinities/NaNs.
- **Model Training:** Fits a linear regression model (with Ridge and Lasso options supported).
- **Evaluation:** Reports key regression metrics (R², MAE, MSE, RMSE).
- **Interpretability:** Prints feature coefficients for insight.
- **Visualization:** Shows predictions vs. actuals, and residuals distribution.

## Getting Started

Clone the repository:

```bash
git clone https://github.com/vishal-04-singh/Linear_Regression_Model.git
cd Linear_Regression_Model
```

## Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- Jupyter Notebook (recommended for `new.ipynb`)

Install dependencies:

```bash
pip install -r requirements.txt
```
> If `requirements.txt` is missing, you can install them directly:
> `pip install pandas numpy matplotlib seaborn scikit-learn`

## Usage

1. Place your dataset (e.g., `heart.csv`) in the project directory.
2. Open `new.ipynb` in Jupyter Notebook or JupyterLab.
3. Run the notebook cells sequentially to:
   - Load and clean the data
   - Explore and visualize the dataset
   - Engineer features and preprocess input
   - Train, evaluate, and interpret the linear regression model
   - Visualize results (predictions and residuals)

**Example: Running the notebook**
```bash
jupyter notebook new.ipynb
```

## Project Structure

```
Vishal_project/
└── anaconda_projects/
    ├── heart.csv             # Dataset file
    ├── new.ipynb             # Main Jupyter notebook with all code and analysis
    └── README.md             # Project README (this file)
```

## Results

The notebook outputs regression metrics and plots, such as:

- Correlation heatmap
- Numeric distributions and pairplots
- Actual vs. Predicted scatter plot
- Residuals distribution

These help you assess model fit and feature relevance.

## Contributing

Contributions are welcome! If you have suggestions, improvements, or new ideas, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.