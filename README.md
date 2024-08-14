This project focuses on classifying songs into genres, specifically "Rock" and "Hip-Hop," using machine learning algorithms. The goal was to build and evaluate models that can accurately distinguish between these genres based on various features extracted from the songs.

Data Cleaning and Exploration:

Cleaned and preprocessed the dataset to ensure it was ready for modeling.
Performed exploratory data visualization to understand the distribution of features and any patterns in the data.
Feature Reduction:

Applied feature reduction techniques to eliminate irrelevant or redundant data, simplifying the model training process.

Model Selection:

Started with a Decision Tree classifier to build an initial model.
Recognized the importance of testing alternative models, so a Logistic Regression model was also trained and evaluated for comparison.
Balancing the Dataset:

Identified a class imbalance in the dataset, with more "Rock" songs than "Hip-Hop" songs.
Balanced the dataset by adjusting the weighting of classes to ensure the model didn’t favor one genre over the other.

Model Evaluation:

Used K-Fold Cross-Validation to rigorously evaluate model performance by testing each model on multiple data splits.
Compared the performance of the Decision Tree and Logistic Regression models using metrics like precision, recall, and F1-score.
Found that balancing the dataset improved model performance, particularly in reducing bias towards the more prevalent "Rock" classification.

Final Results:

The project culminated in a comparison of the Decision Tree and Logistic Regression models, with both performing well but with nuanced differences in classification metrics.
The use of cross-validation provided a robust evaluation of how well the models would generalize to unseen data.

This project demonstrates the importance of testing multiple machine learning models, addressing class imbalances, and using cross-validation to ensure robust and unbiased model evaluation. The process of balancing the data and comparing models has led to a better understanding of the challenges involved in genre classification and how to overcome them.
