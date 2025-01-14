# Fish Weight Prediction

## Project Overview

This project aims to predict the weight of different fish species based on their physical features such as length, height, and width. By utilizing various machine learning models, we develop a model that can accurately estimate fish weight, which can be valuable in industries like fisheries, environmental studies, and food production. The dataset used contains detailed measurements for various fish species, including Bream, Perch, Roach, and others.

## Technical Highlights

- **Data Loading**: The dataset is loaded using Pandas from a CSV file, containing 159 entries with 7 columns of fish attributes.
- **Data Visualization**: A variety of visualizations such as heatmaps, pair plots, and histograms are used to explore correlations and distributions of features.
- **Preprocessing**: Categorical variables are transformed using one-hot encoding, and the dataset is split into training and testing sets.
- **Model Training**: Multiple regression models, including Linear Regression, Ridge Regression, XGBoost, Random Forest, AdaBoost, Gradient Boosting, and Bagging, are used to predict fish weight.
- **Evaluation**: The models are evaluated using metrics like R2 score and Mean Squared Error (MSE), with Gradient Boosting Regressor showing the best performance.

## Purpose and Applications

- **Fisheries and Aquaculture**: Predicting fish weight can help in estimating stock levels and improving the efficiency of breeding and harvesting processes.
- **Environmental Studies**: Understanding fish growth patterns and weight distributions in different ecosystems can assist in ecological monitoring.
- **Food Production and Retail**: Accurate weight predictions can support the pricing and quality control processes in the seafood industry.
  
## Installation

To run this project on your local machine, you will need to install the following dependencies:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/BhaveshBhakta/Fish-Weight-Prediction-Using-ML.git
    cd Fish-Weight-Prediction-Using-ML
    ```
2. **Run the Jupyter notebook**:


## Collaboration

Contributions are welcome! Feel free to fork the repository, make improvements, and submit a pull request.
