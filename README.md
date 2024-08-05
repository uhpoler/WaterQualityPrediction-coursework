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
  - High impact: Total Dissolved Solids, Chloride, Sulfate.
  - Low impact: Lead, Manganese, Iron.
- Random Forest Classifier (RFC)
  - High impact: pH, Turbidity, Manganese.
  - Low impact: Lead, Total Dissolved Solids.
- Decision Tree Classifier (DTC)
  - High impact: pH, Chloride, Turbidity, Manganese.
  - Low impact: Lead, Zinc, Sulfate.

## Feature importance for KNN
![image](https://github.com/user-attachments/assets/d2993fe4-3e95-477f-ad39-51e5505385b3)

## Feature importance for RFC
![image](https://github.com/user-attachments/assets/59c79d06-5d29-4426-a9cd-1cb635601784)

## Feature importance for DТC
![image](https://github.com/user-attachments/assets/702eefd4-c7df-4f63-b134-934b8a92ca3a)


## Conclusion
The analysis of water quality using KNN, RFC, and DTC models provided insights into the most influential parameters affecting water quality. Among the three methods, Random Forest Classifier demonstrated the highest accuracy and effectiveness in classifying water quality, making it the most suitable method for this analysis.
