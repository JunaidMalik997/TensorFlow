# TensorFlow
TensorFlow Syntax, TensorFlow for Regression and Classification

# 1. TensorFlow Syntax Basics:

Used the fake_reg.csv data , a fake dataset where we try to predct the price based on feature1 and feature2. We do some Exploratory Data Analysis and then split the data into training and testing using Scikit learn. We then do some data pre-processing by scaling the data using MinMaxScaler. We then import Sequential Model and Dense Layer from keras API packaged inside tensorflow (tensorflow.keras). We then place sequence of Dense Layers and in the end comile the model and fit it to our training dataset.

# 2. TensorFlow for Regression:

Used the kc_house_data.csv data , a house dataset where we try to predct the price based on various features. We do some Exploratory Data Analysis and some data cleaning to extract as much possible information from the available data. We then split the data into training and testing using Scikit learn. We then do some data pre-processing by scaling the data using MinMaxScaler. We then import Sequential Model and Dense Layer from keras API packaged inside tensorflow (tensorflow.keras). We then place sequence of Dense Layers and in the end compile the model and fit it to our training dataset. In the end we evaluate the performance of our model.

# 3. Tensorflow for Classification:

Used the cancer_classification.csv data , a cancer dataset where we try to classify 2 categorical classes MALIGNANT or BENIGN of lung cancer using various features present in the dataset. We do some Exploratory Data Analysis to get acquainted to our dataset. We then split the data into training and testing using Scikit learn. We then do some data pre-processing by scaling the data using MinMaxScaler. We then import Sequential Model and Dense Layer from keras API packaged inside tensorflow (tensorflow.keras). We then place sequence of Dense Layers and in the end compile the model and fit it to our training dataset. We also use the concept of early stoppings in ths case, in which we stop the training early if the losses on validation data starts increasing during the training. In the end we evaluate the performance of our model.
