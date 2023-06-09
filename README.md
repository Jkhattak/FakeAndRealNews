# News Article Classification
This project aims to classify news articles into two categories - real and fake. The dataset used for this project is a collection of news articles labeled as either real or fake. The dataset contains a total of 44,898 articles, with 21,417 articles labeled as real and 23,481 articles labeled as fake. The dataset was obtained from Kaggle.

# Dataset Details
The dataset contains news articles in English language labeled as either real or fake. The dataset has the following columns:

<li> Title: the title of the article
<li> Text: the text of the article
<li> Subject: the subject of the article
<li> Date: the date the article was published

# Python Libraries Used
The following Python libraries were used for this project:

<li> pandas: for data manipulation and analysis
<li> numpy: for numerical operations
<li> matplotlib: for data visualization
<li> seaborn: for data visualization
<li> nltk: for natural language processing
<li> string: for string operations
<li> wordcloud: for creating word clouds
<li> collections: for creating counters
<li> sklearn: for machine learning algorithms
<li> pickle: for saving and loading trained models

# Machine Learning Algorithms Used
The following machine learning algorithms were used for this project:

<li> XGBClassifier: XGBoost classifier
<li> BaggingClassifier: Bagging classifier
<li> RandomForestClassifier: Random forest classifier
<li> DecisionTreeClassifier: Decision tree classifier
<li> AdaBoostClassifier: AdaBoost classifier
<li> GradientBoostingClassifier: Gradient boosting classifier
<li> LogisticRegression: Logistic regression classifier
<li> ExtraTreesClassifier: Extra trees classifier
<li> SVC: Support Vector Machine classifier
<li> KNeighborsClassifier: K-Nearest Neighbors classifier

# Results
The performance of the machine learning algorithms was evaluated using accuracy and precision metrics. The results are as follows:
![Results](NewsClassifierImage.png)


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

# License
This project is licensed under the MIT License - see the LICENSE file for details.
