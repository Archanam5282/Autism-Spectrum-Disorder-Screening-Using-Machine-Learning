# Autism-Spectrum-Disorder-Screening-Using-Machine-Learning

### Summary: 
Autism Spectrum Disorder (ASD) is a neurodevelopmental disorder in which a person has a lifelong effect on interaction and communication with others. Autism can be diagnosed at any stage in once life, the symptoms usually appears in the first two years of life, so it is said to be a "behavioural disease". The ASD problem starts with childhood and continues to keep going on into adolescence and adulthood. 

Due to the rise in use of machine learning techniques in the research dimensions of medical diagnosis, in this project there is an attempt to try some of the techniques such as Naïve Bayes, KNN, Decision Tree and Random Forest for predicting and analysis of ASD using the behavioural traits. The proposed techniques are evaluated on available dataset from the sources; Kaggle. The obtained dataset related to ASD screening contains a total of 704 instances and 21 attributes. After applying various machine learning techniques and doing some pre-processing like handling missing values and one-hot-encoding, results suggest that Random Forest and Decision Tree prediction models work better on the datasets with higher accuracy of more than 90%. Classifiers like Random forests has a feature_importance_ attribute, which is a function that ranks the importance of features according to the chosen classifier hence the accuracy is more. The results are obtained by using Evaluation technique such as Confusion Matrix and ROC-AUC.

### System Requirements:
To run this project to perform the machine learning algorithms, below software and libraries are were installed:

For Windows, Python 3.6 was installed with the help of the free version of Anaconda. Jupyter Notebook was used as a tool to run the python code. 
The libraries required to run this project are:

•	NumPy

•	Pandas 

•	Matplotlib

•	Seaborn

•	Sklearn

### About Dataset:
A dataset related to autism screening of adults that contained 21 and 704 instances. 
The dataset has ten behavioural features (AQ-10-Adult) plus ten individuals characteristics that have proved to be effective in detecting the ASD.

### About code:
The jupyter notbook present in this repository is the code for the project. It has the step by step instructions. 

### Conclusion
After exploring ASD dataset with different kind of learning algorithms, I can come to a conclusion that all of my model work extremely well with the data. I have used different metric such as accuracy, AUC score and F-score to measure the performance of my models. It looks like all of the metric indicated an almost perfect classification of the ASD cases. Apart from the reasons I mentioned in the first paragraph of the Results section, I also think the reason of this high performances with different models is the fact that only one of the feature is predominant over all others which I have shown and confirmed with the description about features mentioned in the second paragraph of the Result section.

Even though the results are good, we cannot say it is a optimum model as the dataset was very small. So, we need to have access to more larger datasets to build a better and accurate model. However, the models can serve as benchmark models for any machine learning researcher/practitioner who will be interested to explore this dataset further. With this fact in mind, I think this are very well developed model that can detect ASD in individuals with certain given attributes.

