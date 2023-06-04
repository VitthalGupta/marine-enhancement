# Enhancing Marine Surveliance with Machine Learning

## Introduction

Accurate identification of fishing boats is crucial for ensuring safe maritime activities. Traditional methods for classifying boat types, such as radar recognition and optical recognition, have limitations. However, in the case of fishing boat identification based on Automatic Identification System (AIS) data, both static and dynamic information can be utilized, making it less affected by weather conditions. This project presents a comprehensive performance analysis of different classification models to enhance the accuracy of fishing boat identification.

## Objectives

The main objectives of this project are as follows:

1. Develop and evaluate different machine learning models for fishing boat classification.
2. Analyze the performance of the models using various evaluation metrics.
3. Identify the most effective model for accurate fishing boat identification.
4. Provide valuable insights for decision-making in similar classification tasks.

## Methodology

The project utilizes the following methodologies:

1. **Data Collection:** AIS data is collected, which includes both static information (vessel characteristics) and dynamic information (vessel movements).

2. **Data Preprocessing:** The collected AIS data is processed and cleaned to remove any inconsistencies or noise.

3. **Feature Engineering:** Relevant features are extracted from the AIS data to represent the characteristics and movements of fishing boats.

4. **Model Selection:** Different classification models, including Random Forest (RF), J48 Decision Tree, Logistic Regression, and Support Vector Machines (SVM), are evaluated for their effectiveness in boat classification.

5. **Model Evaluation:** The models are evaluated using various metrics such as Accuracy, Average Precision, Average Recall, and Average F1 score.

6. **Performance Analysis:** The results obtained from the analysis are compared to identify the top-performing model for accurate fishing boat identification.

## Results

The performance analysis of different classification models yielded the following results:

- Random Forest (RF) outperformed the other models in terms of all evaluation metrics, achieving an Accuracy of 84.05%, the highest among the considered models.
- RF demonstrated the highest Average Precision and Average Recall of 84.2% and 84.1% respectively, showcasing its effectiveness in accurate classification and identification of positive instances.
- J48 Decision Tree, Logistic Regression, and Random Tree performed slightly lower in terms of Accuracy and other metrics.

## Conclusion

Based on the performance analysis, Random Forest emerged as the top-performing model for accurate fishing boat classification and identification. The results support its suitability for similar classification tasks in marine surveillance. The ensemble of Logistic Regression, Random Forest, and SVM further enhances the predictive capabilities, leading to improved overall accuracy. These findings provide valuable insights for decision-making and improving the efficiency of marine surveillance systems.

For more information refer to this link: [Enhancing Marine Surveillance:
Machine Learning-based Approach for Fishing Boat Classification](https://drive.google.com/file/d/1b2MbpsvNnUQUlc73yn05_PUAL97ZB6qt/view?usp=drive_link)

### License

This project is licensed under the [MIT License](https://github.com/git/git-scm.com/blob/main/MIT-LICENSE.txt). Feel free to use the code and data for research and non-commercial purposes.
