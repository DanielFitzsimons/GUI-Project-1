# Gesture UI - Project 1 (2024)

## Overview

This project involves analyzing vehicle sensor data to classify driving styles, road surface conditions, or traffic conditions using three different classification algorithms: SVM, Logistic Regression, and k-Nearest Neighbors (kNN). The dataset was sourced from Kaggle.

## Objective

- Clean and preprocess the dataset.
- Train and compare three classifiers.
- Use cross-validation to evaluate performance.

## Dataset Description

- **Source**: [Kaggle Dataset](https://www.kaggle.com/gloseto/traffic-driving-style-road-surface-condition)
- **Features**: 14 sensor features from two vehicles (Opel Corsa and Peugeot 207) over two journeys each.
- **Target Outputs**:
  - **Driving Style**: Even Pace or Aggressive
  - **Road Surface Condition**: Smooth Condition or Uneven Condition
  - **Traffic Congestion**: Low Congestion, High Congestion, and others

## Methodology

1. **Data Cleaning**: Addressed missing values and formatting issues.
2. **Feature Engineering**: Converted categorical classes to numeric values.
3. **Data Scaling**: Normalized feature values.
4. **Classifier Training**: Trained SVM, Logistic Regression, and kNN classifiers.
5. **Cross-Validation**: Evaluated classifiers using k-fold cross-validation.

## Results

- Compared classifiers based on accuracy, precision, recall, and F1 score.
- Included visualizations to illustrate performance.

## Conclusion

This project demonstrated the potential of machine learning in predicting driving styles from vehicle sensor data. Through comprehensive data preprocessing and comparative analysis of three classifiers—Logistic Regression, SVM, and kNN—the kNN model emerged as the most effective, achieving superior accuracy and robustness. Key insights include the importance of handling imbalanced datasets and the benefits of rigorous feature selection and scaling. These findings suggest promising directions for future research, including the incorporation of diverse features and advanced modeling techniques like ensemble and deep learning, to further enhance predictive accuracy and contribute to the development of smarter driver assistance systems.

## Deliverables

- **Report**: Detailed methodology, results, and conclusions.
- **Code**: Python notebooks/.py files for data cleaning, training classifiers, and generating results.
