# Crop Prediction using Machine Learning

This project predicts the most suitable crop to grow based on environmental parameters such as temperature, humidity, soil pH, and rainfall using a Random Forest Classifier. It helps farmers make data-driven decisions to maximize crop yield.

# Project Overview

Agricultural productivity depends heavily on environmental factors. Choosing the right crop for specific conditions can significantly improve yield and reduce losses. This system uses a machine learning model trained on historical crop data to accurately recommend the optimal crop for given conditions.

# Dataset

The dataset cpdata.csv contains the following columns:

Feature	Description
| Feature     | Description                |
|------------|----------------------------|
| temperature | Average temperature (°C)   |
| humidity    | Relative humidity (%)      |
| ph          | Soil pH level              |
| rainfall    | Annual rainfall (mm)       |
| label       | Crop name (Target variable)|


Place cpdata.csv in the same directory as crop_prediction.py or update the file path in the script accordingly.

# Technologies Used

Python

Pandas

Scikit-learn

Random Forest Classifier

# Installation

Install the required Python packages using pip:


 pip install pandas scikit-learn


#How to Run

1.Clone or download this repository.

2.Make sure cpdata.csv is in the correct directory.

3.Run the script:
python crop_prediction.py

4.The script will:

Train the Random Forest model on the dataset

Print the model accuracy

Predict a sample crop based on example input
