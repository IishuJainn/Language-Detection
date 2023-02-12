# Language-Detection
Detect the Language using NLP.
![Language_Detection](https://user-images.githubusercontent.com/102272183/213641862-ac680f3b-0bc4-4018-8906-239046912390.png)

## Language Detection using Machine Learning3
This is a project to detect the language of a given text using machine learning algorithms such as K-Nearest Neighbors, Random Forest, and Multinomial Naive Bayes.

## Requirements
This project requires pandas, numpy, matplotlib, seaborn, re, sklearn libraries. To install them, run:
![image](https://user-images.githubusercontent.com/102272183/218292097-5afae4f5-080e-4947-ae2d-abebac4ead13.png)

## Data
The dataset used in this project is "Language Detection.csv" and is available on Kaggle.

## Preprocessing
The first step of the project is to preprocess the data. This includes cleaning the data by removing the symbols, numbers, and converting the text to lowercase. This step is implemented in the clean_function method.

## Exploratory Data Analysis (EDA)
The project involves visualizing the distribution of the different languages present in the data using a bar plot and pie chart.

## Model Selection and Training
The next step is to select the machine learning algorithms to build the model. In this project, we are using K-Nearest Neighbors, Random Forest, and Multinomial Naive Bayes algorithms. The dataset is split into training and testing datasets, and the models are trained on the training data.

## Evaluation
Finally, the performance of the models is evaluated using accuracy score and confusion matrix. The best performing model is selected based on these metrics.

## Conclusion
The accuracy of the MNB model is 0.98, which is very good and indicates that our model is performing well.

