# PassWord_Strength_Classifier

This project utilizes Natural Language Processing (NLP) techniques and logistic regression to classify the strength of passwords. The goal is to predict the strength of a password as either weak, medium, or strong based on its characteristics.

The logistic regression model is trained on a labeled dataset of passwords with their corresponding strength labels. The model extracts relevant features from the passwords, such as length, complexity, and patterns, and uses them to make predictions.

### Dataset
The dataset used for training and evaluation consists of a collection of passwords along with their corresponding strength labels. It is split into a training set and a test set to assess the performance of the trained model.

### Requirements
* Python 3.x
* Libraries: numpy, pandas, scikit-learn, nltk, plotly.express

### Results
The trained model achieves an accuracy of 82% on the test set, demonstrating its effectiveness in predicting password strength.


### Discussion
This project demonstrates the application of NLP and logistic regression in password strength classification. The model is based on a labeled dataset and leverages various features to make accurate predictions.

Future improvements could include refining the feature extraction process, exploring different classification algorithms, and expanding the dataset to enhance model performance.
