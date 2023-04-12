# News Article Classification
This project aims to classify news articles into two categories - real and fake. The dataset used for this project is a collection of news articles labeled as either real or fake. The dataset contains a total of 38,729 articles, with 21,417 articles labeled as real and 23,481 articles labeled as fake. The dataset was obtained from Kaggle.

# Dataset Details
The dataset contains news articles in English language labeled as either real or fake. The dataset has the following columns:

title: the title of the article
text: the text of the article
subject: the subject of the article
date: the date the article was published

# Python Libraries Used
The following Python libraries were used for this project:

pandas: for data manipulation and analysis
numpy: for numerical operations
matplotlib: for data visualization
seaborn: for data visualization
nltk: for natural language processing
string: for string operations
wordcloud: for creating word clouds
collections: for creating counters
sklearn: for machine learning algorithms
pickle: for saving and loading trained models

# Machine Learning Algorithms Used
The following machine learning algorithms were used for this project:

XGBClassifier: XGBoost classifier
BaggingClassifier: Bagging classifier
RandomForestClassifier: Random forest classifier
DecisionTreeClassifier: Decision tree classifier
AdaBoostClassifier: AdaBoost classifier
GradientBoostingClassifier: Gradient boosting classifier
LogisticRegression: Logistic regression classifier
ExtraTreesClassifier: Extra trees classifier
SVC: Support Vector Machine classifier
KNeighborsClassifier: K-Nearest Neighbors classifier

#Results
The performance of the machine learning algorithms was evaluated using accuracy and precision metrics. The results are as follows:


# Conclusion
In this project, we built a machine learning model that could accurately classify news articles as either real or fake. We used a dataset of 44,264 articles labeled as real or fake, and trained several models using different algorithms. We then evaluated the models based on their accuracy and precision scores.

Our best performing model was the XGBoost algorithm, which achieved an accuracy of 99.82% and a precision score of 99.79%. We also achieved strong results with other models such as the Bagging Classifier and Random Forest Classifier, which achieved accuracies of 99.76% and 99.77% respectively.

Overall, our results suggest that machine learning models can be effective in identifying fake news articles with a high degree of accuracy. However, it's important to note that this is a challenging task and there may be limitations to the performance of any model. It's also important to continue to evaluate and refine these models as new data becomes available.

# Future Work
There are several areas where this project could be expanded or improved upon in future work:

Using a larger and more diverse dataset of news articles, which could improve the generalization of the model.
Exploring different text preprocessing techniques or feature engineering methods to improve model performance.
Investigating the impact of different types of news sources on model performance.
Deploying the model in a web application or browser extension to help users identify fake news articles in real time.
References
<li> Kaggle dataset: https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset
<li> XGBoost documentation: https://xgboost.readthedocs.io/en/latest/
<li> Scikit-learn documentation: https://scikit-learn.org/stable/documentation.html

#License
This project is licensed under the MIT License - see the LICENSE file for details.
