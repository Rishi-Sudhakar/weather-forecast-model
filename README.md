# Weather Forecasting Model

## Introduction

This repository contains a machine learning model designed for forecasting weather using the Neural Prophet framework, a robust and scalable time-series forecasting tool. This project leverages historical weather data to predict future weather conditions with high accuracy, catering to various use cases such as agriculture, disaster management, and daily weather predictions.

## Features

- **High Accuracy Forecasting:** Utilizes Neural Prophet, a state-of-the-art framework for time-series forecasting.
- **Scalable Architecture:** Can be adapted for various time-series forecasting tasks beyond weather prediction.
- **Extensive Preprocessing:** Includes detailed preprocessing steps to handle missing values, outliers, and feature engineering.
- **Customizable:** Easily customizable for different regions and types of weather data.
- **Comprehensive Evaluation:** Provides multiple metrics to evaluate the performance of the forecasting model.

## Repository Structure

The repository contains the following files and directories:

- **IndianWeatherRepository.csv.zip:** Compressed file containing historical weather data for India.
- **LICENSE:** The MIT License file for the project.
- **Proj.ipynb:** Jupyter notebook containing the step-by-step implementation of the weather forecasting model.
- **README.md:** This readme file.
- **proj.py:** Python script for training and evaluating the weather forecasting model.

## Getting Started

### Prerequisites

Before you begin, ensure you have met the following requirements:

- Python 3.7 or later installed on your local machine.
- Jupyter Notebook installed (if you plan to run the `Proj.ipynb` notebook).
- Required Python packages installed (see below).

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/Rishi-Sudhakar/weather-forecast-model.git
    ```

2. Navigate to the project directory:

    ```bash
    cd weather-forecast-model
    ```

### Data Preparation

1. Unzip the `IndianWeatherRepository.csv.zip` file:

    ```bash
    unzip IndianWeatherRepository.csv.zip
    ```

2. Place the extracted CSV file in the project directory.

### Running the Model

#### Using Jupyter Notebook or Google colab

1. Open the Jupyter Notebook or Google colab

    ```bash
    jupyter notebook
    ```

2. Open `Proj.ipynb` and run the cells sequentially to train and evaluate the model. Do this step directly, if you're using Google Colab.

#### Using Python Script

1. Run the Python script:

    ```bash
    python proj.py
    ```

## Model Description

The weather forecasting model is built using Neural Prophet, which is designed to handle non-linear time-series data with seasonality, holidays, and other special events. Below is a brief description of the main components:

### Data Preprocessing

- **Handling Missing Values:** Uses interpolation and forward filling techniques to handle missing data points.
- **Outlier Detection and Removal:** Identifies and removes outliers to ensure data quality.
- **Feature Engineering:** Creates additional features such as month, day, and year to capture seasonal patterns.

### Model Training

- **Neural Prophet Framework:** Utilizes Neural Prophet's capabilities to model complex time-series patterns.
- **Hyperparameter Tuning:** Includes a grid search approach to find the optimal hyperparameters.
- **Cross-Validation:** Implements k-fold cross-validation to ensure model robustness.

### Evaluation Metrics

- **Mean Absolute Error (MAE):** Measures the average magnitude of errors in the predictions.
- **Root Mean Squared Error (RMSE):** Provides a quadratic scoring rule to measure the differences between predicted and observed values.
- **R-squared (R²):** Indicates the proportion of the variance in the dependent variable predictable from the independent variables.

## Results

The model achieves high accuracy in forecasting weather, demonstrating the effectiveness of Neural Prophet in capturing time-series patterns. Detailed results and plots are available in the `Proj.ipynb` notebook.

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new Pull Request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Acknowledgments

- [Neural Prophet](https://neuralprophet.com/) for providing an excellent time-series forecasting framework.
- Ofcourse, Myself lol.

## Contact

For any questions or inquiries, please open an issue in the repository.
