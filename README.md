## Suicide and Depression Detection based on Reddit Posts
This Python project delves into the world of social media and mental health, utilizing Natural Language Processing (NLP) techniques to potentially identify individuals struggling with depression or suicidal thoughts on Reddit. By analyzing the language used in user posts, machine learning models can be trained to recognize patterns often associated with these conditions. These patterns might include the frequent use of negative words, expressions of hopelessness, or indications of social isolation within the text.
#One of the most researched topics in the field of Data Analytics and which requires the application of various training models using concepts of Machine Learning and Natural Language Processing is "Sentiment Analysis". This requires tons of data to be first collected, then filtered, and finally processed through various training models and ensemble methods to finally declare/ predict its class with a given accuracy. 
The most sensitive and least discussed sentiments the ones involving suicidal and/ or depressional tendencies.
For this project, I am aiming to first divide the data into training and testing data using basic packages available in scikit - learn; followed by cleaning the discrepencies present in the data that includes missing values and any mismatch of data.
Then data will be plotted using various graph to visualise various patterns and trends. It is always easier to make deductions using plots as a whole rather than working on raw individual data point.
Using Data Visualization techniques, trends and patterns can be analysed and various statistical relations can be made between dependent and independent variables of the dataset.
The role of Natural Language Processing will be to interpret and analyze the language and written text in the posts. All the necessary tools and packages will be installed like WordCloud, label encoder etc. and applied to the available data that makes sense to the problem statement.
The predictive models will be trained using the classification algorithms including SVM, Decision Trees, Random Forest and Ensemble Algorithms like Adaboost and Gradient Boosting.
The test set will be applied on the trained models and then the classification report will be recorded that will include precision, recall, F1 score and accuracy.
Finally, hyperparameter tuning will be applied to the attributes in order to control the overall behavior of all the training models.


## TRAIN-TEST DATA SPLIT: 
The dataset will be divided into train and test data
using the train-test-split function of the scikit-learn package.
## DATA CLEANING: 
Any discrepancies in the data including missing values,
unclean values, mismatch of data type is rectified in this module.
## DATA VISUALIZATION: 
The data will be plotted using various graph to visualise
various patterns and trends. It is always easier to make deductions using plots
as a whole rather than working on raw individual data point.
## DATA ANALYSIS: 
By using the plots from the data visualization module, trends
and patterns can be analysed and various statistical relations can be made
between dependent and independent variables of the dataset.
## NATURAL LANGUAGE PROCESSING: 
Using the concepts of NLP, the language
and written text in the posts will be interpreted and analysed. All the necessary
tools and packages will be installed like WordCloud, label encoder etc. and
applied to the available data that makes sense to the problem statement.
## CLASSIFICATION ALGORITHMS: 
The predictive models will be trained using the
classification algorithms including SVM, Decision Trees, Random Forest and
Ensemble Algorithms like Adaboost and Gradient Boosting.
## TESTING: 
The test set will be applied on the trained models and then the
classification report will be recorded that will include precision, recall, F1 score
and accuracy
