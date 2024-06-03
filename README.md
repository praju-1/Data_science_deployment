# Data Science Project Deployments

This repository contains multiple data science projects, each in its own directory. Each project includes all necessary files for training, evaluation, and deployment.

## Introduction

This repository serves as a collection of various data science projects. Each project has its own set of files, including data, models, and scripts for easy setup and deployment.

## Projects

### Project 1: Banglore House Price Prediction
Predict the Price of House which is located in Banglore which is based on various features like location, sq_feet, balcony, bedroom etc

### Project 2: Car Price Prediction
Predict the selling price of cars based on various features like year, present price, kilometers driven, etc.


## Installation

Clone the repository and install the necessary dependencies for each project.

1. Clone the repository:
    ```sh
    git clone https://github.com/praju-1/Data_science_deployment.git
    ```

2. Navigate to a project directory, e.g., `car-price-prediction`:
    ```sh
    cd data-science-deployments/car-price-prediction
    ```

3. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

Repeat the steps for other projects as needed.

## Usage

Each project can be run independently. Follow the instructions below for each project.

### Car Price Prediction

1. **Train the Model:**
    ```sh
    python carprice.ipynb
    ```

2. **Deploy the Model:**
    ```sh
    python app.py
    ```
    Open your browser and go to `http://127.0.0.1:5000/`.

### Banglore House Price Prediction

1. **Train the Model:**
    ```sh
    python Banglore Housing Price Prediction.ipynb
    ```

2. **Deploy the Model:**
    ```sh
    python app.py
    ```
    Open your browser and go to `http://127.0.0.1:5000/`.


## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.
