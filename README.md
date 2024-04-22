# Concrete Compressive Strength Prediction

## Problem Statement
The quality of concrete is determined by its compressive strength, which is measured using a conventional crushing test on a concrete cylinder. The strength of the concrete is crucial for achieving the requisite longevity of structures. However, the traditional 28-day testing period for strength assessment can be time-consuming. To expedite this process, the project aims to utilize data science techniques to estimate the quantity of raw materials needed to achieve acceptable compressive strength.

## Approach
The project follows a classical machine learning pipeline, involving the following steps:
- **Data Exploration**: Analyze the dataset to understand its structure, distributions, and relationships between variables.
- **Data Cleaning**: Preprocess the data to handle missing values, outliers, and inconsistencies.
- **Feature Engineering**: Identify relevant features and create new ones that may influence concrete strength.
- **Model Building**: Train machine learning algorithms on the preprocessed data to predict compressive strength.
- **Model Testing**: Evaluate the performance of the trained models using appropriate metrics.

Different machine learning algorithms will be explored to determine the best fit for the problem at hand.

## Results
The objective of the project is to develop a predictive solution capable of estimating the compressive strength of concrete. The effectiveness of the solution will be assessed based on its ability to accurately predict compressive strength using the provided dataset.

## Dataset
The dataset used for this project contains information on various concrete mixtures, including the quantities of raw materials used and their corresponding compressive strengths. It serves as the basis for training and testing machine learning models.

## Usage
To run the project locally, follow these steps:
1. Create conda environment: `conda create -p venv python=3.9-y`
2. Activate the environment: `conda activate venv`
3. Install the required dependencies: `python setup.py install`
4. Execute the main script: `python app.py`

By Mahenoor Merchant
