Project Name:
Document Classification using Machine Learning and Deep Learning Techniques

Description:
This project aims to classify a diverse set of documents into predefined categories using various machine learning and deep learning models.

Table of Contents:
* Dataset
* Models Used
* Evaluation
* Resources
* Code Implementation
* Features
* Dependencies
* Testing
* API Reference
* FAQ
* Changelog
* Contact


Installation:
Prerequisites:
* Python 3
* Google Colab (for running the provided notebook)

Installation steps:
* Clone the repository from Google Colab. (https://colab.research.google.com/drive/1j-RytXdZDXCAWKHlaQdFWmRo64SJt_3Y?usp=sharing) In Colab click File --> Save a copy in Colab. <img width="270" alt="Screenshot 2023-08-16 at 21 21 34" src="https://github.com/Michaelzats/ICA-ML/assets/92814061/02117dcb-9c6a-44fe-8f6d-e457cdb5010a"> 
* Install necessary Python libraries using !pip install 
(
pip install numpy
pip install pandas
pip install scikit-learn
pip install matplotlib
pip install seaborn
pip install nltk
pip install gensim
pip install tensorflow
pip install keras
)

Usage:
Basic examples:
* Load the dataset provided “DATA.ZIP”. You can do it by clicking on the file folder icon from the right in Colab and then draging “DATA.ZIP” File into the opened part.  Example how to drag “DATA.ZIP” into the file folder <img width="573" alt="Screenshot 2023-08-16 at 21 19 02" src="https://github.com/Michaelzats/ICA-ML/assets/92814061/fd7286c6-8529-4340-8c94-19580c6a57a7">
Do not unzip it before the excucution, the command # Once uploaded, unzip using: “!unzip DATASET.zip !ls” will do it.
* Train the model using the provided training set.
* Evaluate the model using the test set.

Detailed examples:
* The notebook provides detailed steps for implementing and evaluating each model.

Features:
* Classification of documents into predefined categories.
* Evaluation based on Precision, Recall, F1-Score, and Accuracy.
* Use of various machine learning (Naive Bayes, Support Vector Machines (SVM), and Random Forest) and deep learning model (Deep Neural Network).

Limitations:
* The prototype is recommended to be run in Google Colab as it was created there and can not be simply transferred to the other environment 
* The prototype is computationally heavy, therefore it takes long time to run it through.
* The prototype was done on MAC OS environment, therefore should you have any problems with running it on other environments, please contact mikhail.zats@praguecollege.cz

Testing:
* The models are evaluated using the test set provided in the dataset.
* Evaluation metrics include Precision, Recall, F1-Score, and Accuracy.
Contact:
* For any queries or feedback, please reach out to mikhail.zats@praguecollege.cz . 
