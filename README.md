# Predicting-California-Housing-Prices

## Overview
This project utilizes machine learning techniques to predict housing prices in California based on various features such as median income, house age, and population density. The dataset used is the California Housing dataset, commonly used for regression tasks in machine learning.

## Features
- **Data Preprocessing:** Handling missing values, feature scaling, and encoding categorical variables.
- **Exploratory Data Analysis (EDA):** Visualizing correlations and distributions of key features.
- **Model Training & Evaluation:** Implementing various regression models and evaluating their performance.
- **Hyperparameter Tuning:** Optimizing model performance using techniques like Grid Search and Random Search.

## Installation
To run this project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/MannyChalak/Predicting-California-Housing-Prices.git
   cd Predicting-California-Housing-Prices
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the main script:
   ```bash
   python main.py
   ```

## Dataset
The dataset is sourced from [Scikit-learn’s California Housing dataset](https://scikit-learn.org/stable/datasets/real_world.html#california-housing-dataset). It contains the following features:
- `MedInc`: Median income in the block.
- `HouseAge`: Median house age in the block.
- `AveRooms`: Average number of rooms per household.
- `AveBedrms`: Average number of bedrooms per household.
- `Population`: Block population.
- `AveOccup`: Average household occupancy.
- `Latitude`: Block latitude.
- `Longitude`: Block longitude.

## Models Used
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor
- Support Vector Regressor (SVR)

## Results
The models are evaluated using metrics like:
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R-squared Score (R²)

## Contributing
If you’d like to contribute, please fork the repository and create a pull request with detailed explanations of your changes.

## License
This project is licensed under the MIT License. See `LICENSE` for details.

## Contact
For any inquiries, feel free to reach out to me at [your email] or open an issue in this repository.

