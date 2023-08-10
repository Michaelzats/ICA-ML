**Document Classification using Machine Learning and Deep Learning Techniques**

In the realm of automated document classification, we embarked on an exploration to classify a diverse set of documents into predefined categories. The dataset under scrutiny, sourced from Kaggle, is titled "[(10)Dataset Text Document Classification](https://www.kaggle.com/datasets/jensenbaxter/10dataset-text-document-classification)". It comprises documents categorized under the following labels: 'business', 'entertainment', 'food', 'graphics', 'historical', 'medical', 'politics', 'space', 'sport', and 'technology'. Each category is represented by 100 text files, culminating in a comprehensive dataset.

For the purpose of training and evaluation, the dataset was partitioned into a 70-30 split, with 70% allocated for training and the remaining 30% reserved for testing.

Our investigative approach encompassed a range of machine learning models, namely Naive Bayes, Support Vector Machines (SVM), and Random Forest. Additionally, a Deep Neural Network *(due to this model, the chanks of codes might take a while to load)*, a paradigm of deep learning, was also employed. To enhance the performance and robustness of these models, various techniques were integrated into the pipeline:

Feature Engineering: Utilization of N-grams to capture local word order information.
Word Embeddings: Leveraging pre-trained embeddings to represent words in a dense vector space.
Feature Selection: The Chi-Squared Test was employed to select significant features.
Model Ensembling: Bagging was used to reduce variance by training multiple models.
Regularization Techniques: Dropout was introduced to prevent overfitting in the deep learning model.
The models were evaluated on multiple metrics, including Precision, Recall, F1-Score, and Accuracy. The F1-Score, which harmoniously balances Precision and Recall, was chosen as the primary metric to determine the best model.

Upon thorough evaluation, Dropout Deep Neural Network showed as the superior model with an F1 Score 0.983524. Nonetheless, as the model load time is significant, the second best model SVM without enhancement techniques is chosen with an F1 Score of 0.980188 is chosen as the best. While other models with feature enhancements were closely competitive, the computational overhead and marginally inferior performance make the standardized SVM the recommended choice for this document classification task.

The development and refinement of our approach were greatly aided by resources from StackOverflow, ChatGPT, and a series of YouTube tutorials:

[Python Machine Learning #4 - Support Vector Machines
](https://www.youtube.com/watch?v=99Eyw7Quacc)

[Neural Network Python | How to make a Neural Network in Python | Python Tutorial | Edureka](https://www.youtube.com/watch?v=9UBqkUJVP4g)

[Machine Learning Tutorial Python - 11 Random Forest
](https://www.youtube.com/watch?v=ok2s1vV9XW0)

[Naive Bayes Classifier in Python (from scratch!)
](https://www.youtube.com/watch?v=3I8oX3OUL6I)

**Literature used for deeper understanding of the models:**
Alpaydin, E., 2020. Introduction to machine learning. MIT press.
Baltrušaitis, T., Ahuja, C. and Morency, L.P., 2018. Multimodal machine learning: A survey and taxonomy. IEEE transactions on pattern analysis and machine intelligence, 41(2), pp.423-443.
Chen, Y.W. and Lin, C.J., 2006. Combining SVMs with various feature selection strategies. Feature extraction: foundations and applications, pp.315-324.
Goodfellow, I., Bengio, Y. and Courville, A., 2016. Deep learning. MIT press.
Liaw, A. and Wiener, M., 2015. randomForest: Breiman and Cutler’s random forests for classification and regression. R package version, 4, p.14.
McCallum, A. and Nigam, K., 1998, July. A comparison of event models for naive bayes text classification. In AAAI-98 workshop on learning for text categorization (Vol. 752, No. 1, pp. 41-48).
Oliphant, T.E., 2007. Python for scientific computing. Computing in science & engineering, 9(3), pp.10-20.
Provost, F. and Fawcett, T., 2013. Data Science for Business: What you need to know about data mining and data-analytic thinking. " O'Reilly Media, Inc.".
Shawe-Taylor, J. and Cristianini, N., 2004. Kernel methods for pattern analysis. Cambridge university press.
Srivastava, N., Hinton, G., Krizhevsky, A., Sutskever, I. and Salakhutdinov, R., 2014. Dropout: a simple way to prevent neural networks from overfitting.
The journal of machine learning research, 15(1), pp.1929-1958.


