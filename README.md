# README: CO2 Emissions Prediction Using Machine Learning and Deep Learning

This project demonstrates the process of predicting CO2 emissions using machine learning models (Random Forest, SVM) and deep learning techniques. The dataset contains various features such as fuel consumption, vehicle count, and fuel type, and the goal is to predict CO2 emissions effectively.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Models Used](#models-used)
- [Performance](#performance)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction
CO2 emissions significantly impact global climate change. This project aims to leverage machine learning and deep learning to create accurate prediction models. By comparing various techniques, we achieve a robust model that can generalize well to unseen data.

## Dataset
The dataset includes information about:
- **Fuel consumption** (measured and estimated gaps).
- **Vehicle count**.
- **Fuel type** (e.g., Petrol, Diesel, Hybrid).

The target variable is `OBFCM CO2 emissions (g/km)`.

## Models Used
1. **Random Forest Regressor**
   - R^2: 0.76
   - RMSE: 27.43
2. **Support Vector Machine (SVM)**
   - R^2 :0.76
   - RMSE: 27.68
3. **Deep Learning (Optimized Neural Network)**
   - R^2: 0.96
   - RMSE: 140.07

## Performance
The optimized neural network significantly outperformed other models, achieving an R^2 of 96% on the test set.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Jules1109/ml_for_de.git
   cd ml_for_de
   ```
2. Install the required Python libraries:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Open the notebook:
   ```bash
   jupyter notebook carbon_footprint_estimation.ipynb
   ```
2. Follow the step-by-step code to preprocess the data, train models, and evaluate performance.

## Results
### Key Metrics:
- **Random Forest**: R^2 = 0.76, RMSE = 27.43
- **SVM (Optimized)**: R^2 = 0.76, RMSE = 27.68
- **Deep Learning (Optimized)**: R^2 = 0.96, RMSE = 140.07

### Visualizations:
- Distribution analysis 
- Residual analysis
- Learning curves for the neural network

## Contributing
Contributions are welcome! If you have suggestions for improving the project, feel free to submit a pull request or open an issue.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

