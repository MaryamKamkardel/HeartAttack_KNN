# Heart Attack Prediction Using K-Nearest Neighbors (KNN) Algorithm

## Overview

This repository contains a machine learning project aimed at predicting the likelihood of a heart attack using the K-Nearest Neighbors (KNN) algorithm. The project utilizes medical data to build a predictive model that can help identify individuals at risk of heart attacks based on various health metrics.

## Project Description

Cardiovascular diseases are among the leading causes of death worldwide, and early prediction and intervention can significantly reduce mortality rates. This project focuses on developing a predictive model to estimate the probability of heart attacks by analyzing patient data.

### Objectives
- **Data Analysis**: Conduct exploratory data analysis (EDA) to understand the dataset and identify important patterns and relationships.
- **Feature Engineering**: Select and engineer features that are significant for predicting heart attacks.
- **Model Training**: Train a K-Nearest Neighbors classifier to predict heart attack occurrences.
- **Model Evaluation**: Assess the model's performance using various metrics to ensure its reliability and accuracy.
- **Visualization**: Provide visual insights into the data and the model's decision-making process.

## Dataset

The dataset used in this project includes various health-related attributes such as age, gender, blood pressure, cholesterol levels, and more. The data is sourced from publicly available medical records or repositories dedicated to heart disease research.

### Key Features
- **Age**: Age of the patient.
- **Sex**: Gender of the patient (1 = male, 0 = female).
- **CP**: Chest pain type (4 types).
- **Trestbps**: Resting blood pressure.
- **Chol**: Serum cholesterol in mg/dl.
- **Fbs**: Fasting blood sugar > 120 mg/dl (1 = true, 0 = false).
- **Restecg**: Resting electrocardiographic results (values 0, 1, 2).
- **Thalach**: Maximum heart rate achieved.
- **Exang**: Exercise-induced angina (1 = yes, 0 = no).
- **Oldpeak**: ST depression induced by exercise relative to rest.
- **Slope**: The slope of the peak exercise ST segment.
- **Ca**: Number of major vessels (0-3) colored by fluoroscopy.
- **Thal**: Thalassemia (3 = normal, 6 = fixed defect, 7 = reversible defect).

## Methodology

1. **Data Preprocessing**: Clean the dataset by handling missing values, encoding categorical variables, and normalizing numerical features.
2. **Exploratory Data Analysis (EDA)**: Gain insights into the data through visualization and statistical analysis.
3. **Feature Selection**: Identify the most significant features contributing to heart attack prediction.
4. **Model Building**: Implement the K-Nearest Neighbors algorithm to build the predictive model.
5. **Model Evaluation**: Assess the model's performance using confusion matrix, accuracy score, precision, recall, and F1 score.
6. **Hyperparameter Tuning**: Optimize the model's parameters (e.g., number of neighbors) to enhance its predictive capability.

## Results

The KNN model demonstrated effective performance in predicting heart attacks, providing clear insights into which features most influence the risk. Visualizations such as feature importance plots help in understanding the decision-making process of the model.

## Installation

To run this project locally, follow these steps:

1. **Clone the repository**:
    ```sh
    git clone https://github.com/MaryamKamkardel/HeartAttack_KNN.git
    ```
2. **Navigate to the project directory**:
    ```sh
    cd HeartAttack_KNN
    ```
3. **Install required packages**:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

After installing the necessary packages, you can run the project scripts to train and evaluate the model. Example:
```sh
python train_model.py
```

## Contributing

Contributions are welcome! If you have suggestions for improvements or new features, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- The dataset used in this project is sourced from [source name].
- This project was inspired by the importance of early heart disease detection and prevention.
