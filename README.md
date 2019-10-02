# depression-sentiment-prediction
Depression Sentiment Prediction Project for Udacity's Machine Learning Engineer Nanodegree Capstone Project.
This repository houses all the files used for [Udacity's Machine Learning Engineer Nanodegree Capstone Project](https://www.udacity.com/course/machine-learning-engineer-nanodegree--nd009t)

**Repository Structure**
1. The Folder [Code](Code/) contains all the code in this project.
2. The Folder [models](models/) contains all the final Models that were trained on data (except one, which is *Random Forest Classification* model, reason being it's huge size which made it impossible to upload on Github).
3. The File [Proposal.pdf](proposal.pdf) contains the original proposal for the project.
4. The File [Report.pdf](report.pdf) contains the final project report for the project.

**Dependencies**
To code present in this project, you have to have following libraries with their specified versions.
```
numpy >= 1.15.4
pandas >= 0.23.4
matplotlib >= 3.0.2
wordcloud >= 1.5.0
nltk >= 3.4
sklearn >= 0.20.1
xgboost >= 0.90
```

The Project has several dependencies (as seen above) which can be easily installed issuing the following command from this directory in your local machine / cloud VM:

```
$ pip install -r requirements.txt
```
If that doesn't work for some reason, you can manually install them using;

```
$ pip install numpy pandas matplotlib sklearn xgboost nltk
```
**Dataset**
The Original dataset *isnot* included here due it's massive size. It can be downloaded from [here](https://www.kaggle.com/kazanova/sentiment140).
Note: To download the dataset, one must have a verified [Kaggle](https://kaggle.com) account.
