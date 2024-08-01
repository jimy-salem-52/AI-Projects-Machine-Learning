# AI - Projects

This is a repo showing projects with computer vision Implementation & NLP done in Kaggle for free GPU usage, however, they are posted here because of few saving issues

Kaggle Profile: https://www.kaggle.com/jimysalem/code

# Insight on the Repo

The dataset provided by Kaggle showcases images related to people's facial expressions.

The dataset for NLP is also provided by Kaggle.

For the machine learning and visualization projects: the datasets consist of two parts. The first part consists of instances of hourly average responses of five metal oxide chemical sensors. The second part aims to classify people described by a set of attributes as good or bad credit risks.

Music Genre Classifier: the dataset shows multiple features concerning the Fourier transform features and others to indentify the music genre.

# Computer Vision:

## Dataset Issues - Computer Vision Trials:

The first trial used 6000 random images and revealed class imbalances. Therefore, the strategy in the second trial was to select a balanced number of images between classes.

## Models Used and their issues - Computer Vision

1. ViT: judging from the confusion matrix, some classes weren't identified , ViT requires a high number of data that wasn't represented in this project
2. ResNet50: ResNet50 is one of the most used and widely recognized CNN. It is a pretrained model used for tasks requiring high accuracy. the accuracy achieved is 41%
3. Due to memory errors: NasNet wasn't applied
4. Instead a CNN that was applied similar to NasNet was used but wih little accuracy of 31%

## Solution - Computer Vision
1. Identified a CNN for 62% accuracy

# NLP:

## Models Used and their issues:

All of the models are state-of-the-art for NLP and experienced overfitting:

1. CNN: Performed the best.
2. Transformers & Others: Captured a few classes while not identifying others.

## Solution - NLP:

Use a CNN which got to 70+%accuracy

# Machine Learning & Visualisation

## Part 1:

The dataset represents the target output as numerical. An EDA was performed on the dataset and visualization was done, including a covariance matrix showing a strong linear relationship between variables and the ground truth explaining most of the dataset.

### Models Used:

Various models were used, showcasing issues with overfitting. The best models were chosen based on features and ground truth variables that are to be predicted.

## Part 2:ng MLP

The dataset shows obvious issues with class imbalances, which will affect the machine learning models used.

The target variable was not initially identified or provided in the dataset but was chosen to avoid imbalance.

### Models Used:

Random Forest showed the best performance, and SHAP values were later analyzed, showing some differences, but overall class imbalance affects the models.

# Music Genre - Classifier

## Dataset:

The dataset contains features extracted from the Fourier Transform of audio files, which are used to predict the music genre label. An Exploratory Data Analysis (EDA) was performed, along with Principal Component Analysis (PCA) to reduce the dimensionality of the dataset. The PCA identified the features that account for 95% of the data variance.

## Models Used: 

Several models were experimented with, and their performances were compared. The Multi-Layer Perceptron (MLP) model performed the best among the models tested 
