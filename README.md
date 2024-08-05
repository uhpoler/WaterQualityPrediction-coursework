# Water Quality Analysis Project
## Overview
This repository contains the coursework project focused on analyzing and predicting water quality using various machine learning techniques. The aim is to evaluate the effectiveness of different classifiers in predicting water quality based on several input parameters.

## Project Structure
- Data Collection: Identification and extraction of relevant water quality data from external sources.
- Literature Review: Examination of existing research and literature to understand the domain and the applicability of various machine learning methods.
- Method Justification: Justification for the selection of specific data analysis and machine learning techniques.
- Model Implementation and Evaluation: Application and comparison of the effectiveness of different machine learning models, including K-Nearest Neighbors (KNN), Decision Tree Classifier (DTC), and Random Forest Classifier (RFC).
- Documentation: Preparation of the explanatory note detailing the methodology, analysis, and findings.
- Submission and Defense: Submission of the project for review and defense of the coursework.

## Functionality
The software developed for this project includes the following functionality:
- Loading the dataset.
- Data preprocessing and exploration.
- Applying machine learning models.
- Predicting water quality.
- Analyzing factors affecting water quality.
- Visualizing and analyzing the results.

## Models and Results
- K-Nearest Neighbors (KNN)
  - Confusion Matrix Results:
    - 72.58% of observations for class 0 were correctly classified.
    - 4.48% of observations for class 0 were misclassified as class 1.
    - 14.86% of observations for class 1 were misclassified as class 0.
    - 8.08% of observations for class 1 were correctly classified.
  - Important Features:
    - High impact: Total Dissolved Solids, Chloride, Sulfate.
    - Low impact: Lead, Manganese, Iron.
- Random Forest Classifier (RFC)
  - Confusion Matrix Results:
    - 65.48% of observations for class 0 were correctly classified.
    - 11.58% of observations for class 0 were misclassified as class 1.
    - 0.89% of observations for class 1 were misclassified as class 0.
    - 22.05% of observations for class 1 were correctly classified.
  - Important Features:
    - High impact: pH, Turbidity, Manganese.
    - Low impact: Lead, Total Dissolved Solids.
- Decision Tree Classifier (DTC)
  - Confusion Matrix Results:
    - 68.92% of observations for class 0 were correctly classified.
    - 8.14% of observations for class 0 were misclassified as class 1.
    - 8.23% of observations for class 1 were misclassified as class 0.
    - 14.71% of observations for class 1 were correctly classified.
  - Important Features:
    - High impact: pH, Chloride, Turbidity, Manganese.
    - Low impact: Lead, Zinc, Sulfate.
## Conclusion
The analysis of water quality using KNN, RFC, and DTC models provided insights into the most influential parameters affecting water quality. Among the three methods, Random Forest Classifier demonstrated the highest accuracy and effectiveness in classifying water quality, making it the most suitable method for this analysis.
