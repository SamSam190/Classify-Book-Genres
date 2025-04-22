# Classify-Book-Genres

    Introduction
In the digital age, book categorization plays a critical role in organizing content, enhancing discoverability, and improving recommendation systems. With the massive volume of literature published daily, manually tagging books by genre has become inefficient and prone to inconsistency. To address this challenge, machine learning offers a scalable solution by automatically classifying books based on key metadata features.
This project focuses on classifying books into genres using structured metadata such as author popularity, book length, and the number of keywords associated with each title. These features provide valuable insight into the nature and scope of a book’s content, enabling effective classification.
By applying a supervised learning approach, the goal is to predict a book’s genre—such as Fiction, Fantasy, Mystery, or Non-Fiction—based on these input features. The project leverages the Random Forest algorithm due to its robustness and suitability for handling tabular data. The results are evaluated using key metrics such as accuracy, precision, recall, and a confusion matrix to assess model performance.

 
    Methodology
                       
This project used a machine learning approach to classify book genres based on structured metadata.
 Data Loading
•	The dataset was loaded and checked for structure and completeness using pandas.
  Feature Selection
•	Selected features included author popularity, book length, and Num keywords. The target was the genre column.
Label Encoding
•	Genre labels were encoded into numeric form using LabelEncoder for model compatibility.
Train-Test Split
•	Data was split into 70% training and 30% testing to evaluate performance on unseen data.
 Model Training
•	A RandomForestClassifier was trained on the training data due to its effectiveness with structured data.
Prediction & Evaluation
•	The model predicted test genres and results were evaluated using a confusion matrix and classification report (precision, recall, F1-score).
Visualization
•	A heatmap was created to visualize prediction accuracy, and feature importance was plotted to identify influential attributes.
