# AI - Projects

This is a repo showing projects with computer vision Implementation & NLP done in Kaggle for free GPU usage, however, they are posted here because of few saving issues

Kaggle Profile: https://www.kaggle.com/jimysalem/code

# Insight on the Repo - Computer Vision & NLP

The dataset given by Kaggle showcases images concerned with the face expression of people

The datset for NLP given also by Kaggle

# Computer Vision:

## Dataset Issues - Computer Vision Trials:

The first trial was done by using 6000 random images it shows that there are class imbalances and therefore the second strategy in trial 2 is to pick a good number that will showcase a balance between classes.

## Models Used and their issues - Computer Vision

1. ViT: judging from the confusion matrix, some classes weren't identified , ViT requires a high number of data that wasn't represented in this project
2. ResNet50: ResNet50 is one of the most used and widely recognized CNN. It is a pretrained model used for tasks requiring high accuracy. the accuracy achieved is 41%
3. Due to memory errors: NasNet wasn't applied
4. Instead a CNN that was applied similar to NasNet was used but wih little accuracy of 31%

## Solution - Computer Vision
1. Identified a CNN for 62% accuracy

# NLP:

## Models Used and their issues:

All of the models are state of the art for NLP and are experiencing overfitting:
1. CNN: which preformed the best
2. Transformers & Others: captured few classes while not identifying the others 

## Solution - NLP:

Use a CNN which got to 70+%accuracy
