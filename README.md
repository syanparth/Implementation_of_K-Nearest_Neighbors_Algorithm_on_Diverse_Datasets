# Implementation of K-Nearest Neighbors Algorithm on Diverse Datasets

This repository showcases the implementation of the K-Nearest Neighbors (KNN) algorithm applied to two distinct datasets: the Iris dataset and a BMI classification dataset. The project includes both a custom KNN algorithm built from scratch and a version utilizing the `scikit-learn` library.

## Table of Contents
- [Project Structure](#project-structure)
- [Usage](#usage)
- [Dataset Descriptions](#dataset-descriptions)
  - [Iris Dataset](#iris-dataset)
  - [BMI Dataset](#bmi-dataset)
- [KNN Using Scikit-Learn](#knn-using-scikit-learn)
  - [Iris Dataset](#iris-dataset-1)
  - [BMI Dataset](#bmi-dataset-1)
- [KNN from Scratch](#knn-from-scratch)
  - [Iris Dataset](#iris-dataset-2)
  - [BMI Dataset](#bmi-dataset-2)
- [Evaluation](#evaluation)
- [Results](#results)
- [License](#license)
- [Languages Used](#languages-used)

## Usage

To run the examples, execute the corresponding Python scripts. Ensure the dataset files are in the correct directories.

### For the Iris dataset using `scikit-learn`:

1. Ensure the Iris dataset is in the `data/` directory.
2. Run the script:
    ```bash
    python iris_knn_sklearn.py
    ```

### For the BMI dataset using `scikit-learn`:

1. Ensure the BMI dataset is in the `data/` directory.
2. Run the script:
    ```bash
    python bmi_knn_sklearn.py
    ```

### For the Iris dataset using the custom KNN implementation:

1. Ensure the Iris dataset is in the `data/` directory.
2. Run the script:
    ```bash
    python iris_knn_custom.py
    ```

### For the BMI dataset using the custom KNN implementation:

1. Ensure the BMI dataset is in the `data/` directory.
2. Run the script:
    ```bash
    python bmi_knn_custom.py
    ```

## Dataset Descriptions

### Iris Dataset
The Iris dataset is a well-known dataset in machine learning. It contains 150 samples of iris flowers, each described by four features: sepal length, sepal width, petal length, and petal width. The dataset is classified into three species of iris: setosa, versicolor, and virginica.

### BMI Dataset
The BMI classification dataset is used to categorize individuals based on their Body Mass Index (BMI). The dataset contains features such as height and weight, and the target variable represents BMI categories like underweight, normal weight, overweight, and obesity.

## KNN Using Scikit-Learn

### Iris Dataset
The implementation using `scikit-learn` for the Iris dataset demonstrates how to leverage this powerful library for quick and efficient KNN classification.

### BMI Dataset
Similarly, the BMI dataset is classified using the `scikit-learn` library's KNN implementation.

## KNN from Scratch

### Iris Dataset
The custom implementation of KNN for the Iris dataset allows you to understand the inner workings of the algorithm.

### BMI Dataset
The BMI dataset is also classified using a custom-built KNN algorithm to demonstrate its functionality.

## Evaluation
The evaluation section includes the performance metrics and comparison between the `scikit-learn` implementation and the custom implementation on both datasets.

## Results
This section summarizes the findings, including accuracy scores and insights gained from the experiment.

## License
This project is licensed under the MIT License.

## Languages Used
- Python







